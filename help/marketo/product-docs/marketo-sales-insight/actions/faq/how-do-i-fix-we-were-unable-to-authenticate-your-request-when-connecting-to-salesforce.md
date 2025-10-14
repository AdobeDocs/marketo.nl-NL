---
description: Hoe los ik "We konden uw verzoek niet verifiëren" bij het verbinden met Salesforce - Marketo Docs - productdocumentatie
title: Hoe kan ik "We konden uw verzoek niet verifiëren" herstellen bij verbinding met Salesforce
exl-id: ef876f0f-bd76-4ba5-bf48-885ee048ceae
feature: Sales Insight Actions
source-git-commit: 65d607e279fb86b0816ccaec2f4bf3c69e309cb9
workflow-type: tm+mt
source-wordcount: '349'
ht-degree: 0%

---

# Hoe kan ik &quot;We konden uw verzoek niet verifiëren&quot; herstellen bij verbinding met [!DNL Salesforce] {#how-do-i-fix-we-were-unable-to-authenticate-your-request-when-connecting-to-salesforce}

Als u probeert om uw exemplaar van de Verkoop van Marketo aan Salesforce aan te sluiten en u ziet de fout &quot;Wij kunnen uw verzoek niet voor authentiek verklaren&quot;, is het waarschijnlijk verwant aan hoe uw instantie van Salesforce wordt gevormd.

Er zijn twee soorten fouten die deze mislukte verificatiepagina kunnen veroorzaken.

* Toegangsfout beperkt domein voor aanmelding
* Oauth App Blocked

U kunt bepalen welk type u krijgt door URL te controleren.

![](assets/how-do-i-fix-we-were-unable-to-authenticate-1.png)

![](assets/how-do-i-fix-we-were-unable-to-authenticate-2.png)

## Oplossen van aanmeldfout met beperkt domein {#resolve-login-error-restricted-domain}

Deze fout wijst typisch op u een douanedomein hebt dat wij niet aan kunnen leiden. U lost deze fout op door u aan te melden bij het Salesforce-exemplaar waarmee u eerst verbinding wilt maken. Voer vervolgens de stappen uit om verbinding te maken met Salesforce.

Als de instantie waarmee u verbinding probeert te maken een Salesforce Sandbox-domein is en u een fout krijgt, moet u aanvullende stappen doorlopen om uw instantie bij te werken zodat deze compatibel is met Salesforce Sandbox. [&#x200B; leer meer &#x200B;](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/set-up-a-sales-insight-actions-sandbox.md){target="_blank"}.

## Oauth-app geblokkeerd oplossen {#resolve-oauth-app-blocked}

Als u het foutbericht &quot;We konden uw verzoek niet verifiëren&quot; hebt ontvangen met het fouttype Oauth App Blocked (of een ander type) in de URL, is er mogelijk een beperking op uw toegang tot de Salesforce API. Neem contact op met uw Salesforce Admin om ervoor te zorgen dat de onderstaande onderdelen aanwezig zijn.

### API inschakelen in gebruikersmachtigingen {#enable-api-in-user-permissions}

1. Laat Salesforce Admin zich aanmelden bij Salesforce.
1. Selecteer **Opstelling**.
1. Selecteer **leiden Gebruikers**.
1. Selecteer **Profielen**.
1. Vind het Profiel dat de gebruikers ToutApp onder zijn en klik **uitgeven**.
1. De rol neer aan **Administratieve Toestemmingen** en zorgt ervoor **Toegelaten API** wordt gecontroleerd.

### Controleren of Salesforce Insight-acties voor verkoop blokkeert via verbinding {#check-if-salesforce-is-blocking-sales-insight-actions-from-connecting}

1. Laat Salesforce Admin zich aanmelden bij Salesforce.
1. Selecteer **Opstelling**.
1. Selecteer **beheert Apps**.
1. Selecteer **Verbonden toepassingen OAuth Gebruik**.
1. Zorg ervoor dat bij Handelingen van Insight verkopen de optie Blokkeren wordt weergegeven. Als je Blokkering opheffen ziet, klik je op de button om de toegang tot Salesforce voor Insight-acties verkopen te ontgrendelen.
