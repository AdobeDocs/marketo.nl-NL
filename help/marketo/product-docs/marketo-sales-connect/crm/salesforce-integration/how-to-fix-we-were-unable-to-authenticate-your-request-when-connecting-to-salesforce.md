---
unique-page-id: 14352484
description: Hoe te om "wij konden niet uw verzoek"bevestigen wanneer het verbinden met Salesforce - Marketo Docs - de Documentatie van het Product bevestigen
title: Hoe te om "Wij konden niet uw verzoek voor authentiek verklaren"wanneer het verbinden met Salesforce
translation-type: tm+mt
source-git-commit: 1dd80b7de801df78ac7dde39002455063f9979b7
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 0%

---


# Hoe te om &quot;wij te bevestigen konden uw verzoek&quot;niet verklaren wanneer het verbinden met Salesforce {#how-to-fix-we-were-unable-to-authenticate-your-request-when-connecting-to-salesforce}

Als u het foutbericht &quot;We konden uw verzoek niet verifiëren&quot; ontvangt wanneer u probeert Sales Connect aan te sluiten op Salesforce, is er mogelijk een beperking op uw toegang tot de API van Salesforce. Neem contact op met uw Salesforce Admin om te controleren of de volgende functies aanwezig zijn.

## API inschakelen in gebruikersmachtigingen {#enable-api-in-user-permissions}

1. Een Salesforce Admin-aanmelding bij SFDC.
1. Selecteer **Setup**.
1. Selecteer **Gebruikers beheren**.
1. Selecteer **Profielen**.
1. Zoek het profiel onder de ToutApp-gebruikers en klik op **Bewerken**.
1. Schuif omlaag naar **Administratieve Machtigingen** en controleer of **API Enabled** is ingeschakeld.

## Controleren of Salesforce Sales Connect blokkeert door {#check-if-salesforce-is-blocking-sales-connect-from-connecting} te verbinden

1. Een Salesforce Admin-aanmelding bij SFDC.
1. Selecteer **Setup**.
1. Selecteer **Apps beheren**.
1. Selecteer **OAuth-gebruik van aangesloten apps**.
1. Zorg ervoor dat in Sales Connect naast de optie Blok wordt weergegeven. Als u &quot;Unblock&quot; ziet, klikt u op de knop om de toegang van Sales Connect tot Salesforce te blokkeren.
