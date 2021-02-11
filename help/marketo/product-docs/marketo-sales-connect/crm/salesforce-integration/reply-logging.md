---
unique-page-id: 14352480
description: Reply Logging (SFDC) - Marketo Docs - Productdocumentatie
title: Reply Logging (SFDC)
translation-type: tm+mt
source-git-commit: 1dd80b7de801df78ac7dde39002455063f9979b7
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---


# Reply Logging (SFDC) {#reply-logging-sfdc}

Met Sales Connect kunt u de antwoorden van uw vooruitzichten automatisch laten registreren bij Salesforce. De structuur waarmee u dit kunt doen, is gebaseerd op het bijhouden van onze e-mailantwoorden. Als we het antwoord van het vooruitzicht kunnen volgen, kunnen we dat antwoord aan Salesforce loslaten.

## Vereisten {#requirements}

* E-mails via API-registratie moeten worden geregistreerd
* Moet een antwoord [kunnen volgen](/help/marketo/product-docs/marketo-sales-connect/email/common-tracking-questions/how-reply-tracking-works.md)
* Moet zijn aangesloten op Salesforce
* Moet Salesforce [API-aanroepen](https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm) beschikbaar hebben

## Logboekregistratie voor reactie inschakelen {#enable-reply-logging}

1. Om antwoordregistreren toe te laten kunt u over aan uw de montagespagina van Salesforce leiden. Zodra het registreren van API wordt gecontroleerd zult u de optie zien om _Reacties van het Logboek_ te controleren.

   >[!NOTE]
   >
   >Voor het registreren van antwoorden gelden dezelfde regels als voor het registreren van e-mails die worden verzonden. Hieronder valt ook de manier waarop e-mails worden geregistreerd; op leads en contacten; wanneer er een dubbel record is; als er geen overeenkomende records worden gevonden.

## Type instellen op Reageren in Salesforce {#setting-type-to-reply-in-salesforce}

Het is belangrijk dat u zinvolle gegevens krijgt uit uw Salesforce-rapporten. Doordat het veld Type kan worden ingevuld als &#39;Reageren&#39;, kunt u die gegevens via uw rapporten ophalen. Partner up with your `Salesforce admin` to get this setup.

1. Ga naar **Setup** > **Aanpassen** > **Activiteiten** > **Taakvelden**.
1. Klik **Type**.
1. Onder de Waarden van de Picklist van het Type van Taak, klik **Nieuw**.
1. Typ &quot;Reageren&quot; in het lege vak. Zorg ervoor u &quot;R&quot;kapitaliseert en **sparen** klikt.

   >[!NOTE]
   >
   >U hoeft geen standaard te selecteren in de keuzelijst Type. Sales Connect ziet dat dit type activiteit beschikbaar is in uw Salesforce-exemplaar en vult het taakveld dienovereenkomstig in op uw inkomende activiteiten.
