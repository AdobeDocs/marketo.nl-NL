---
unique-page-id: 14352484
description: Hoe te om "wij konden niet uw verzoek"bevestigen wanneer het verbinden met Salesforce - Marketo Docs - de Documentatie van het Product bevestigen
title: Hoe te om "Wij konden niet uw verzoek voor authentiek verklaren"wanneer het verbinden met Salesforce
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 0%

---


# Hoe te om &quot;Wij konden niet uw verzoek voor authentiek verklaren&quot;wanneer het verbinden met Salesforce {#how-to-fix-we-were-unable-to-authenticate-your-request-when-connecting-to-salesforce}

Als u het foutbericht &quot;We konden uw verzoek niet verifiëren&quot; ontvangt wanneer u probeert Sales Connect aan te sluiten op Salesforce, is er mogelijk een beperking op uw toegang tot de API van Salesforce. Neem contact op met uw Salesforce Admin om te controleren of de volgende functies aanwezig zijn.

## API inschakelen in gebruikersmachtigingen {#enable-api-in-user-permissions}

1. Een Salesforce Admin-aanmelding bij SFDC.
1. Selecteer **Instellen**.
1. Selecteer Gebruikers **beheren**.
1. Selecteer **Profielen**.
1. Zoek het profiel onder de ToutApp-gebruikers en klik op **Bewerken**.
1. Blader omlaag naar **Beheersbevoegdheden** en controleer of **API ingeschakeld** is.

## Controleren of Salesforce de verbinding met Sales Connect blokkeert {#check-if-salesforce-is-blocking-sales-connect-from-connecting}

1. Een Salesforce Admin-aanmelding bij SFDC.
1. Selecteer **Instellen**.
1. Selecteer **Toepassingen** beheren.
1. Selecteer OAuth-gebruik **voor aangesloten apps**.
1. Zorg ervoor dat in Sales Connect naast de optie Blok wordt weergegeven. Als u &quot;Unblock&quot; ziet, klikt u op de knop om de toegang van Sales Connect tot Salesforce te blokkeren.

