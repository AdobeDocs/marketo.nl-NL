---
unique-page-id: 14352484
description: '"We konden uw verzoek niet verifiëren" bij verbinding met Salesforce - Marketo Docs - productdocumentatie'
title: Hoe te om "Wij konden niet uw verzoek"voor authentiek verklaren wanneer het verbinden met Salesforce
exl-id: ddd49064-f584-4490-8d45-29cf61ed3ebe
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 0%

---

# Hoe te om &quot;Wij konden niet uw verzoek&quot;voor authentiek verklaren wanneer het verbinden met Salesforce {#how-to-fix-we-were-unable-to-authenticate-your-request-when-connecting-to-salesforce}

Als u het foutbericht &quot;We konden uw verzoek niet verifiëren&quot; ontvangt wanneer u probeert Sales Connect aan te sluiten op Salesforce, is er mogelijk een beperking op uw toegang tot de API van Salesforce. Neem contact op met uw Salesforce Admin om te controleren of de volgende functies aanwezig zijn.

## API inschakelen in gebruikersmachtigingen {#enable-api-in-user-permissions}

1. Een Salesforce Admin-aanmelding bij SFDC.
1. Selecteren **Instellen**.
1. Selecteren **Gebruikers beheren**.
1. Selecteren **Profielen**.
1. Zoek het profiel onder de ToutApp-gebruikers en klik op **Bewerken**.
1. Omlaag schuiven naar **Administratieve machtigingen** en zorg ervoor **API ingeschakeld** is ingeschakeld.

## Controleren of Salesforce de verbinding met Sales Connect blokkeert {#check-if-salesforce-is-blocking-sales-connect-from-connecting}

1. Een Salesforce Admin-aanmelding bij SFDC.
1. Selecteren **Instellen**.
1. Selecteren **Apps beheren**.
1. Selecteren **OAuth-gebruik van aangesloten apps**.
1. Zorg ervoor dat in Sales Connect naast de optie Blok wordt weergegeven. Als u &quot;Unblock&quot; ziet, klikt u op de knop om de toegang van Sales Connect tot Salesforce te blokkeren.
