---
description: Aanmelden met OAuth 2.0 - Marketo Docs - Productdocumentatie
title: Aanmelden met OAuth 2.0
exl-id: 0a70505d-d2b8-4dc9-ad11-decc86588f7f
feature: Salesforce Integration
source-git-commit: 4045f262889d06304111288d30da893529396e81
workflow-type: tm+mt
source-wordcount: '492'
ht-degree: 1%

---

# Aanmelden met OAuth 2.0 {#log-in-using-oauth-2-0}

Salesforce gebruikt het protocol OAuth om gebruikers van toepassingen toe te staan om tot gegevens veilig toegang te hebben (de toepassing voor authentiek te verklaren gebruikend OAuth 2.0) zonder het moeten login geloofsbrieven openbaren. Hieronder staan de stappen die moeten worden uitgevoerd om Marketo Engage veilig te verbinden en te synchroniseren met Salesforce.

>[!IMPORTANT]
>
>Als u Marketo en Salesforce wilt verbinden met gebruik van OAuth, meldt u zich aan bij Marketo via een privébrowser (incognito) om te voorkomen dat u verbinding maakt met Salesforce met de verkeerde gebruikersnaam.

## Connected App instellen {#set-up-connected-app}

1. Navigeer in Salesforce, onder Setup, in de Hulpmiddelen van het Platform naar Apps, de Manager van de App, en klik **[!UICONTROL New Connected App]**.

   ![](assets/setting-up-oauth-2-1.png)

1. Vul de details in en klik op **[!UICONTROL Save]**.

   ![](assets/setting-up-oauth-2-2.png)

1. Klik op de knop **[!UICONTROL Enable OAuth Settings]** selectievakje. Voor URL callback, ga binnen `https://app.marketo.com/salesforce/getSfdcOAuthTokensRedirect`. Selecteer alle beschikbare OAuth-bereiken en klik op **[!UICONTROL Add]**.

   ![](assets/setting-up-oauth-2-3.png)

1. Klik op **[!UICONTROL Save]**.

   ![](assets/setting-up-oauth-2-4.png)

1. Klik op **[!UICONTROL Continue]**.

   ![](assets/setting-up-oauth-2-5.png)

1. Kopieer de Consumentensleutel en het Geheim van de Consumenten (u zult hen voor gebruik in Marketo Engage later nodig hebben).

   ![](assets/setting-up-oauth-2-6.png)

>[!CAUTION]
>
>Terwijl nog op de Nieuwe Verbonden App pagina, scrol neer en zorg ervoor &quot;vereist Sleutel van het Bewijs voor de Uitwisseling van de Code (PKCE)&quot;checkbox is _NOT_ gecontroleerd, aangezien het met opstelling zou interfereren.

## Marketo instellen {#set-up-marketo}

>[!PREREQUISITES]
>
>* API-toegang moet zijn ingeschakeld voor de Salesforce Sync-gebruiker (als u een Salesforce Professional Edition-gebruiker bent, is deze toegang niet standaard beschikbaar. Neem contact op met de Salesforce Account Executive).
>* Marketo Sync-gebruiker moet worden gemaakt in Salesforce.
>* Voor bestaande klanten is de functie &quot;OAuth inschakelen voor SFDC-synchronisatie&quot; ingeschakeld op het abonnement van de klant.
>* Pop-upblokkeerprogramma&#39;s zijn uitgeschakeld.
>* Connected App is gemaakt en we hebben de Consumer Key en Consumer Secret beschikbaar voor gebruik.

>[!CAUTION]
>
>Verberg alle velden die u niet nodig hebt in Marketo door de synchronisatiegebruiker voordat u op **[!UICONTROL Sync Fields]**. Nadat u op Velden synchroniseren hebt geklikt, worden alle velden die de gebruiker kan zien in SFDC permanent gemaakt in Marketo en kunnen deze niet meer worden verwijderd.

1. Klik in de sectie Marketo Admin op **[!UICONTROL CRM]** vervolgens **[!UICONTROL Sync with Salesforce]**.

   ![](assets/setting-up-oauth-2-7.png)

1. Voeg de informatie die u eerder hebt opgenomen over Consumentensleutel en Consumentengeheim toe en klik en **[!UICONTROL Save]**.

   ![](assets/setting-up-oauth-2-8.png)

1. Klik op de synchronisatiepagina van Marketo Salesforce op **[!UICONTROL Login with Salesforce]** knop.

   ![](assets/setting-up-oauth-2-9.png)

   >[!CAUTION]
   >
   >Als u de velden Gebruikersnaam/Wachtwoord/Token ziet en niet de knop Aanmelden met Salesforce, is uw Marketo-abonnement ingeschakeld voor Basisverificatie. Zie [Marketo instellen met basisverificatie](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-3-of-3-connect-marketo-and-salesforce-enterprise-unlimited.md){target="_blank"}. Wanneer de synchronisatie begint met het gebruik van een set aanmeldingsgegevens, wordt er niet overgeschakeld op Salesforce-gegevens of -abonnement. Als u Oauth 2.0 wilt gebruiken, contacteer aan het Team van de Rekening van de Adobe (uw Manager van de Rekening).

1. Er wordt een pop-up weergegeven met de aanmeldingspagina voor verkopers. Sleutel in uw aanmeldingsgegevens voor &quot;Marketo Sync User&quot; (Gebruiker synchroniseren) en meld u aan.

   ![](assets/setting-up-oauth-2-10.png)

1. Voer de verificatiecode in die je via e-mail hebt ontvangen (verzonden door Salesforce) en klik op **[!UICONTROL Verify]**.

   ![](assets/setting-up-oauth-2-11.png)

1. Na succesvolle verificatie wordt de toegangspagina weergegeven met het verzoek om toegang. Klik op **[!UICONTROL Allow]**.

   ![](assets/setting-up-oauth-2-12.png)

1. Over een paar minuten verschijnt er een pop-up in Marketo. Klik op **[!UICONTROL Confirm Credentials]**.

   ![](assets/setting-up-oauth-2-13.png)

1. Klik op Veldsync bij voltooiing **[!UICONTROL Start Salesforce Sync]**.

   ![](assets/setting-up-oauth-2-14.png)

1. Klik op **[!UICONTROL Start Sync]**.

   ![](assets/setting-up-oauth-2-15.png)

Uw Synchronisatie tussen Marketo en Salesforce is nu aan de gang.

![](assets/setting-up-oauth-2-16.png)

>[!MORELIKETHIS]
>
>* [Stap 1 van 3: Voeg Marketo-velden toe aan Salesforce (Enterprise/Onbeperkt)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md){target="_blank"}
>* [Stap 2 van 3: Een Salesforce-gebruiker voor Marketo maken (Enterprise/Onbeperkt)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target="_blank"}
>* [Marketo Sales Insight Package installeren in Salesforce AppExchange](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"}
>* [Marketo Sales Insight configureren in Salesforce Enterprise/Onbeperkt](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md){target="_blank"}
