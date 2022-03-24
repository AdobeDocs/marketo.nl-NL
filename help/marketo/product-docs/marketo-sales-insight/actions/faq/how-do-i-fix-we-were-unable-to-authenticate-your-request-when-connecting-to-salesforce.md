---
description: Hoe los ik "Wij konden uw verzoek niet voor authentiek verklaren"wanneer het verbinden met Salesforce - Marketo Docs - de Documentatie van het Product
title: Hoe bevestig ik "wij konden uw verzoek"niet voor authentiek verklaren wanneer het verbinden met Salesforce
exl-id: ef876f0f-bd76-4ba5-bf48-885ee048ceae
source-git-commit: d9b8b92ac5f051178b8eb9b450c4949b56d50b99
workflow-type: tm+mt
source-wordcount: '193'
ht-degree: 0%

---

# Hoe bevestig ik &quot;wij konden uw verzoek&quot;niet voor authentiek verklaren wanneer het verbinden met Salesforce {#how-do-i-fix-we-were-unable-to-authenticate-your-request-when-connecting-to-salesforce}

Als u het foutbericht &quot;We konden uw verzoek niet verifiëren&quot; ontvangt wanneer u probeert een verbinding tot stand te brengen tussen Handelingen van het Inzicht van de Verkoop en Salesforce, kan er een beperking zijn op uw toegang tot de API van Salesforce. Neem contact op met uw Salesforce Admin om te controleren of de volgende functies aanwezig zijn.

## API inschakelen in gebruikersmachtigingen {#enable-api-in-user-permissions}

1. Een Salesforce Admin-aanmelding bij SFDC.
1. Selecteren **Instellen**.
1. Selecteren **Gebruikers beheren**.
1. Selecteren **Profielen**.
1. Zoek het profiel onder de ToutApp-gebruikers en klik op **Bewerken**.
1. Omlaag schuiven naar **Administratieve machtigingen** en zorg ervoor **API ingeschakeld** is ingeschakeld.

## Controleren of Salesforce de Acties van het Inzicht van de Verkoop van Verbinding blokkeert {#check-if-salesforce-is-blocking-sales-insight-actions-from-connecting}

1. Een Salesforce Admin-aanmelding bij SFDC.
1. Selecteren **Instellen**.
1. Selecteren **Apps beheren**.
1. Selecteren **OAuth-gebruik van aangesloten apps**.
1. Zorg ervoor dat de Acties van het Inzicht van de Verkoop &quot;Blok&quot;naast het tonen. Als u &quot;Unblock&quot;ziet, klik de knoop om de toegang van het Inzicht van de Verkoop tot Salesforce te ontgrendelen.
