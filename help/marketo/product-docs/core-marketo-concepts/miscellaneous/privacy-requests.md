---
description: Privacyverzoeken - Marketo-documenten - productdocumentatie
title: Privacyverzoeken
exl-id: ae61eabc-ad8f-4c7b-8097-838e89c1a3ec
source-git-commit: b95458ffab422901ef5e674756ae5e413ec542fd
workflow-type: tm+mt
source-wordcount: '335'
ht-degree: 0%

---

# Privacyverzoeken {#privacy-requests}

Dit document biedt een overzicht van het beheer van individuele privacyverzoeken voor gegevens die u naar Marketo Engage kunt verzenden via de gebruikersinterface van Privacy Service en de Privacy Service-API.

>[!NOTE]
>
>Privacy-aanvragen die via de gebruikersinterface van Privacy Service of de API voor Marketo Engage worden ingediend, zijn alleen van toepassing op:
>
>* Marketo Engage-gebruikers die zijn aangemeld bij Adobe Identity Management System
>
>**-or-**
>
>* Marketo Engage-gebruikers die een ander Experience Cloud-product gebruiken dat zich al op het Adobe Identity Management-systeem bevindt (bijvoorbeeld RT-CDP, B2B en B2P Editions, Audience Manager).

U kunt individuele verzoeken om toegang tot en verwijdering van consumentengegevens vanuit Marketo Engage op twee manieren verzenden:

* Via de gebruikersinterface van Privacy Service: `https://experience.adobe.com/#/@YOURCOMPANYNAME/privacy`. Zie de documentatie [ hier ](https://experienceleague.adobe.com/docs/experience-platform/privacy/ui/user-guide.html){target="_blank"}.
* Via de Privacy Service API. Zie hier de documentatie [ ](https://developer.adobe.com/experience-platform-apis/references/privacy-service/){target="_blank"} en API informatie [ ](https://developer.adobe.com/experience-platform-apis/){target="_blank"}.

[ Privacy Service ](https://experienceleague.adobe.com/docs/experience-platform/privacy/home.html){target="_blank"} steunt twee soorten verzoeken: gegevenstoegang en gegevensschrapping.

Zie hoe u verzoeken van de Toegang en van de Schrapping kunt tot stand brengen.

## Vereiste installatie voor het verzenden van aanvragen voor Marketo Engage {#required-setup-to-send-requests-for-marketo-engage}

Als u een aanvraag wilt indienen om gegevens voor Marketo Engage te openen of te verwijderen, moet u:

1. Vermeld het volgende:

   a. IMS Org ID <br/>
b. E-mailadres van de persoon aan wie u wilt optreden

   Een IMS-organisatie-id is een alfanumerieke tekenreeks van 24 tekens die wordt toegevoegd met @AdobeOrg. Als uw marketingteam of interne Adobe-systeembeheerder de IMS Org-id van uw organisatie niet kent, neemt u contact op met de klantenservice van Adobe op `gdprsupport@adobe.com` . U hebt de IMS Org ID nodig om aanvragen in te dienen bij de Privacy API.

1. In Privacy Service kunt u aanvragen voor toegang en verwijderen naar Marketo Engage verzenden en de status van bestaande aanvragen controleren.

## Vereiste veldwaarden in Marketo Engage JSON-verzoeken {#required-field-values-in-marketo-engage-json-requests}

&quot;companyContext&quot;:

* &quot;namespace&quot;: **imsOrgID**
* &quot;value&quot;: `<Your IMS Org ID Value>`

&quot;gebruikers&quot;:

* &quot;actie&quot;: of **toegang** of **schrapping**
* &quot;userIDs&quot;:
   * &quot;namespace&quot;: **e-mail**
   * &quot;type&quot;: **standaard**
   * &quot;value&quot;: `<Data Subject's Email Address>`

&quot;include&quot;:

* **marktto** (dat het product is van Adobe dat op het verzoek van toepassing is)

&quot;verordening&quot;:

* **gdpr**, **ccpa**, **pdpa**, **lgpd_bra**, of **nzpa_nzl** (dat de privacyverordening is die op het verzoek van toepassing is)

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
>[ het Beheer van de Privacy ](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/privacy-management.md)
