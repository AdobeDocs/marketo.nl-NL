---
description: Privacyverzoeken - Marketo-documenten - productdocumentatie
title: Privacyverzoeken
exl-id: ae61eabc-ad8f-4c7b-8097-838e89c1a3ec
source-git-commit: 0abb315be0f9cb5f42fa41d72b446de8c2f62c1e
workflow-type: tm+mt
source-wordcount: '354'
ht-degree: 0%

---

# Privacyverzoeken {#privacy-requests}

Dit document biedt een overzicht van het beheer van individuele verzoeken om gegevensprivacy die u naar het Marketo Engage kunt verzenden via de gebruikersinterface van de Privacy Service en de Privacy Service-API.

>[!NOTE]
>
>De verzoeken van de privacy die door Privacy Service UI of API voor Marketo Engage worden voorgelegd zijn slechts op het volgende van toepassing:
>
>* Marketo Engage gebruikers die aan het Systeem van de AdobeIdentity Management hebben ingezien
>
>**-of-**
>
>* Gebruikers van Marketo&#39;s Engage die een ander Experience Cloud-product gebruiken dat zich al op het Identity Management-systeem van de Adobe bevindt (bijvoorbeeld RT-CDP, B2B en B2P Editions, Audience Manager).

U kunt individuele verzoeken om tot consumentengegevens van Marketo Engage toegang te hebben en te schrappen op twee manieren voorleggen:

* Via de [UI PRIVACY SERVICE](https://privacyui.cloud.adobe.io/). Zie de documentatie [hier](https://experienceleague.adobe.com/docs/experience-platform/privacy/ui/user-guide.html){target="_blank"}.
* Via de Privacy Service-API. Zie de documentatie [hier](https://developer.adobe.com/experience-platform-apis/references/privacy-service/){target="_blank"} and API information [here](https://developer.adobe.com/experience-platform-apis/){target="_blank"}.

De [Privacy Service](https://experienceleague.adobe.com/docs/experience-platform/privacy/home.html){target="_blank"} ondersteunt twee soorten verzoeken: toegang tot gegevens en verwijdering van gegevens.

Zie hoe u verzoeken van de Toegang en van de Schrapping kunt tot stand brengen.

## Vereiste opstelling om verzoeken om Marketo Engage te verzenden {#required-setup-to-send-requests-for-marketo-engage}

Om tot Gegevens van de Toegang en van de Schrapping voor Marketo Engage te verzoeken, moet u:

1. Vermeld het volgende:

   a. IMS Org ID<br/>
b. E-mailadres van de persoon aan wie u wilt optreden

   Een IMS-organisatie-id is een alfanumerieke tekenreeks van 24 tekens die wordt toegevoegd met @AdobeOrg. Als uw marketingteam of de beheerder van het interne Adobe-systeem de IMS Org-id van uw organisatie niet kent, neemt u contact op met de klantenservice van de Adobe op `gdprsupport@adobe.com`. U hebt de IMS Org ID nodig om aanvragen in te dienen bij de Privacy API.

1. In Privacy Service, kunt u verzoeken van de Toegang voorleggen en van de Schrapping aan Marketo Engage, en de status van bestaande verzoeken controleren.

## Vereiste veldwaarden in JSON-verzoeken van Marketo Engage {#required-field-values-in-marketo-engage-json-requests}

&quot;companyContext&quot;:

* &quot;namespace&quot;: **imsOrgID**
* &quot;waarde&quot;: `<Your IMS Org ID Value>`

&quot;gebruikers&quot;:

* &quot;actie&quot;: **toegang** of **delete**
* &quot;userIDs&quot;:
   * &quot;namespace&quot;: **email**
   * &quot;type&quot;: **standaard**
   * &quot;waarde&quot;: `<Data Subject's Email Address>`

&quot;include&quot;:

* **marketo** (dit is het Adobe product dat van toepassing is op het verzoek)

&quot;verordening&quot;:

* **gdpr**, **ccpa**, **pdpa**, **lgpd_bra**, of **nzpa_nzl**  (dit is de privacyverordening die van toepassing is op het verzoek)

## Voorbeeld één: GDPR-aanvraag verwijderen {#gdpr-delete-request}

JSON-aanvraag

```text
{
  "companyContexts": [
    {
      "namespace": "imsOrgID",
      "value": "1231659F56A68A8B7F000101@AdobeOrg"
    }
  ],
  "users": [
    {
      "action": [
        "delete"
      ],
      "userIDs": [
        {
          "namespace": "email",
          "type": "standard",
          "value": "john.doe@adobe.com"
        }
      ]
    }
  ],
  "include": [
    "marketo"
  ],
  "regulation": "gdpr",
}
```

JSON-reactie

```text
{
  "requestId": "16331241037112570RX-245",
  "totalRecords": 1,
  "jobs": [
    {
      "jobId": "997b01e3-9568-402c-904b-b4e60a437875",
      "customer": {
        "user": {
          "action": [
            "delete"
          ],
          "userIDs": [
            {
              "namespace": "email",
              "value": "john.doe@adobe.com",
              "type": "standard",
              "namespaceId": 6,
              "isDeletedClientSide": false
            }
          ]
        }
      }
    }
  ]
}
```

## Voorbeeld twee: CCPA-verzoek om toegang {#ccpa-access-request}

JSON-aanvraag

```text
{
  "companyContexts": [
    {
      "namespace": "imsOrgID",
      "value": "1231659F56A68A8B7F000101@AdobeOrg"
    }
  ],
  "users": [
    {
      "action": [
        "access"
      ],
      "userIDs": [
        {
          "namespace": "email",
          "type": "standard",
          "value": "john.doe@adobe.com"
        }
      ]
    }
  ],
  "include": [
    "marketo"
  ],
  "regulation": "ccpa",
}
```

JSON-reactie

```text
{
  "requestId": "16329573462631890RX-207",
  "totalRecords": 1,
  "jobs": [
    {
      "jobId": "3115e42d-011b-47ab-a2b0-ed4356af4d3e",
      "customer": {
        "user": {
          "action": [
            "access"
          ],
          "userIDs": [
            {
              "namespace": "email",
              "value": "john.doe@adobe.com",
              "type": "standard",
              "namespaceId": 6,
              "isDeletedClientSide": false
            }
          ]
        }
      }
    }
  ]
}
```

>[!MORELIKETHIS]
>
>[Privacybeheer](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/privacy-management.md)
