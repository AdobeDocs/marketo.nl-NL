---
unique-page-id: 14352480
description: Reply Logging (SFDC) - Marketo Docs - Productdocumentatie
title: Reply Logging (SFDC)
exl-id: 11f84157-55b7-42a7-81d0-f5848adbb9f4
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---

# Reply Logging (SFDC) {#reply-logging-sfdc}

Met Sales Connect kunt u de antwoorden van uw vooruitzichten automatisch laten registreren bij Salesforce. De structuur waarmee u dit kunt doen, is gebaseerd op het bijhouden van onze e-mailantwoorden. Als we het antwoord van het vooruitzicht kunnen volgen, kunnen we dat antwoord aan Salesforce loslaten.

## Vereisten {#requirements}

* E-mails via API-registratie moeten worden geregistreerd
* Moet in staat zijn [antwoorden bijhouden](/help/marketo/product-docs/marketo-sales-connect/email/common-tracking-questions/how-reply-tracking-works.md)
* Moet zijn aangesloten op Salesforce
* Moet Salesforce hebben [API-aanroepen](https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm) beschikbaar

## Logboekregistratie voor reactie inschakelen {#enable-reply-logging}

1. Om antwoordregistreren toe te laten kunt u over aan uw de montagespagina van Salesforce leiden. Als de API-logboekregistratie is uitgeschakeld, ziet u de optie om te controleren _Log reacties_.

   >[!NOTE]
   >
   >Voor het registreren van antwoorden gelden dezelfde regels als voor het registreren van e-mails die worden verzonden. Hieronder valt ook de manier waarop e-mails worden geregistreerd; op leads en contacten; wanneer er een dubbel record is; als er geen overeenkomende records worden gevonden.

## Type instellen op Reactie in Salesforce {#setting-type-to-reply-in-salesforce}

Het is belangrijk dat u zinvolle gegevens krijgt uit uw Salesforce-rapporten. Doordat het veld Type kan worden ingevuld als &#39;Reageren&#39;, kunt u die gegevens via uw rapporten ophalen. Partner up-to-date met uw `Salesforce admin` om deze instelling op te halen.

1. Ga naar **Instellen** > **Aanpassen** > **Activiteiten** > **Taakvelden**.
1. Klikken **Type**.
1. Klik onder Picklist voor taaktype op **Nieuw**.
1. Typ &quot;Reageren&quot; in het lege vak. Zorg ervoor dat u de letter &#39;R&#39; gebruikt en klik op **Opslaan**.

   >[!NOTE]
   >
   >U hoeft geen standaard te selecteren in de keuzelijst Type. Sales Connect ziet dat dit type activiteit beschikbaar is in uw Salesforce-exemplaar en vult het taakveld dienovereenkomstig in op uw inkomende activiteiten.
