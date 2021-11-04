---
description: Privacyverzoeken - Marketo-documenten - productdocumentatie
title: Privacyverzoeken
source-git-commit: da290279eb6daa9ee96baed54482482ec6640301
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Privacyverzoeken {#privacy-requests}

Dit document biedt een overzicht van het beheer van individuele privacyverzoeken voor gegevens die u naar Marketo Engage kunt verzenden via de gebruikersinterface van de Privacy Service en de **Privacy Service-API**.

>[!NOTE]
>
>De verzoeken van de privacy die door Privacy Service UI of API voor Marketo Engage worden voorgelegd zijn slechts op die van toepassing die Marketo Engage + rt-CDP, B2B en B2P Editions hebben.

U kunt individuele verzoeken om tot consumentengegevens van Marketo Engage toegang te hebben en te schrappen op twee manieren voorleggen:

* Via de [UI Privacy Service](https://privacyui.cloud.adobe.io/). Zie de documentatie [hier](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html#!api-specification/markdown/narrative/tutorials/privacy_service_tutorial/privacy_service_ui_tutorial.md).
* Via de **Privacy Service-API**. Zie de documentatie [hier](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html#!api-specification/markdown/narrative/tutorials/privacy_service_tutorial/privacy_service_api_tutorial.md) en de API-referentie [hier](https://www.adobe.io/apis/experiencecloud/gdpr/api-reference.html#!acpdr/swagger-specs/privacy-service.yaml).

De [Privacy Service](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html) ondersteunt twee typen verzoeken: gegevenstoegang en gegevensverwijdering.

Zie hoe u aanvragen voor toegang en verwijderen kunt maken.

## Vereiste opstelling om verzoeken om Marketo Engage te verzenden {#required-setup-to-send-requests-for-marketo-engage}

Om tot Gegevens van de Toegang en van de Schrapping voor Marketo Engage te verzoeken, moet u:

1. Vermeld het volgende:

   a. IMS Org ID<br/>
b. E-mailadres van de persoon aan wie u wilt optreden

   Een IMS-organisatie-id is een alfanumerieke tekenreeks van 24 tekens die wordt toegevoegd met @AdobeOrg. Als uw marketingteam of interne beheerder van het Adobe-systeem de IMS Org-id van uw organisatie niet kent, neemt u contact op met de klantenservice van Adobe op gdprsupport@adobe.com. U hebt de IMS Org ID nodig om aanvragen in te dienen bij de Privacy API.

1. In Privacy Service, kunt u verzoeken van de Toegang en van de Schrapping voorleggen aan Marketo Engage, en de status van bestaande verzoeken controleren.

## Vereiste veldwaarden in Marketo Engage JSON-verzoeken {#required-field-values-in-marketo-engage-json-requests}

&quot;companyContext&quot;:

* &quot;namespace&quot;: **imsOrgID**
* &quot;waarde&quot;: `<Your IMS Org ID Value>`

&quot;gebruikers&quot;:

* &quot;actie&quot;: ofwel **toegang** of **delete**
* &quot;userIDs&quot;:
   * &quot;namespace&quot;: **email**
   * &quot;type&quot;: **standaard**
   * &quot;waarde&quot;: `<Data Subject’s Email Address>`

&quot;include&quot;:

* **marketo** (dit is het product van de Adobe dat op het verzoek van toepassing is)

&quot;verordening&quot;:

* **gdpr**, **ccpa**, **pdpa**, **lgpd_bra**, of **nzpa_nzl**  (dit is de privacyverordening die van toepassing is op het verzoek)

## Voorbeeld één: GDPR-verzoek verwijderen {#gdpr-delete-request}

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
