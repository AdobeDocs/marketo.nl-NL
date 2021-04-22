---
description: OAuth 2.0 instellen - Marketo Docs - Productdocumentatie
title: OAuth 2.0 instellen
exl-id: 0a70505d-d2b8-4dc9-ad11-decc86588f7f
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '327'
ht-degree: 0%

---

# OAuth 2.0 {#setting-up-oauth-2-0} instellen

Salesforce gebruikt het protocol OAuth om gebruikers van toepassingen toe te staan om tot gegevens veilig toegang te hebben (de toepassing voor authentiek te verklaren gebruikend OAuth 2.0) via REST API vraag zonder het moeten login geloofsbrieven openbaren. Hieronder vindt u de stappen die moeten worden uitgevoerd om Marketo veilig te verbinden en te synchroniseren met Salesforce.

## Aangesloten app {#set-up-connected-app} instellen

1. In Salesforce, onder Opstelling, binnen de Hulpmiddelen van het Platform, navigeer aan Apps, Manager van de Toepassing, en klik **Nieuwe Verbonden App**.

   ![](assets/setting-up-oauth-2-1.png)

1. Vul de details in en klik **Save**.

   ![](assets/setting-up-oauth-2-2.png)

1. Klik op het selectievakje **OAuth-instellingen inschakelen**. Voor Callback URL, ga `https://app.marketo.com/salesforce/getSfdcOAuthTokensRedirect` in. Selecteer alle beschikbare OAuth-bereiken en klik op **Toevoegen**.

   ![](assets/setting-up-oauth-2-3.png)

1. Klik **Opslaan**.

   ![](assets/setting-up-oauth-2-4.png)

1. Klik **Doorgaan**.

   ![](assets/setting-up-oauth-2-5.png)

1. Kopieer de Consumentensleutel en Consumentengeheim.

   ![](assets/setting-up-oauth-2-6.png)

>[!NOTE]
>
>Sla de Consumentencode en Consumentengeheim informatie op voor later gebruik in Marketo.

## Marketo {#set-up-marketo} instellen

>[!PREREQUISITES]
>
>* API-toegang moet zijn ingeschakeld voor de Salesforce Sync-gebruiker (als u een Salesforce Professional Edition-gebruiker bent, is deze toegang standaard niet beschikbaar. Neem contact op met uw Salesforce Account Executive).
>* Marketo Sync-gebruiker moet worden gemaakt in Salesforce.
>* Voor bestaande klanten, wordt de Eigenschap om &quot;OAuth voor synchronisatie toe te laten SFDC&quot;toegelaten op het abonnement van de klant.
>* Pop-upblokkeerders zijn uitgeschakeld.
>* Connected App is gemaakt en we hebben de Consumer Key en Consumer Secret beschikbaar voor gebruik.


1. Klik in de sectie Marketo Admin op **CRM** en **Synchroniseren met Salesforce**.

   ![](assets/setting-up-oauth-2-7.png)

1. Voeg de gegevens Consumentencode en Consumentengeheim toe die u eerder hebt opgenomen en klik en **Opslaan**.

   ![](assets/setting-up-oauth-2-8.png)

1. Klik op de synchronisatiepagina van Marketo Salesforce op de knop **Aanmelden met Salesforce**.

   ![](assets/setting-up-oauth-2-9.png)

1. Er wordt een pop-up weergegeven met de aanmeldingspagina voor verkopers. Sleutel in uw aanmeldingsgegevens voor &quot;Marketo Sync User&quot; (Gebruiker synchroniseren) en meld u aan.

   ![](assets/setting-up-oauth-2-10.png)

1. Voer de verificatiecode in die u hebt ontvangen via e-mail (verzonden door Salesforce) en klik op **Verifiëren**.

   ![](assets/setting-up-oauth-2-11.png)

1. Na succesvolle verificatie wordt de toegangspagina weergegeven met het verzoek om toegang. Klik **Toestaan**.

   ![](assets/setting-up-oauth-2-12.png)

1. Over een paar minuten verschijnt er een pop-up in Marketo. Klik **Credentials bevestigen**.

   ![](assets/setting-up-oauth-2-13.png)

1. Klik op **Salesforce Sync starten** wanneer de veldsynchronisatie is voltooid.

   ![](assets/setting-up-oauth-2-14.png)

1. Klik **Sync starten**.

   ![](assets/setting-up-oauth-2-15.png)

Uw Synchronisatie tussen Marketo en Salesforce is nu aan de gang.

![](assets/setting-up-oauth-2-16.png)
