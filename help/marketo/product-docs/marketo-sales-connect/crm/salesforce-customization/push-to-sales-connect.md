---
unique-page-id: 14352477
description: Push to  [!DNL Sales Connect]  - Marketo Docs - Productdocumentatie
title: Naar  [!DNL Sales Connect] duwen
exl-id: 8fb99d28-d6c6-47c3-b4d2-c416251aff47
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '146'
ht-degree: 2%

---

# Naar [!DNL Sales Connect] duwen {#push-to-sales-connect}

Met de knop [!UICONTROL Push to Tout] maakt u een lijst met uw leads/contactpersonen in [!DNL Salesforce] en plaatst u deze in een groep in [!DNL Sales Connect] . Vervolgens kunt u snel een aanpasbare groep e-mailen met de functie Tout bijhouden.

## Vereisten {#requirements}

* [!DNL Sales Connect Salesforce] -pakket geïnstalleerd door [!DNL Salesforce] Admin

* [!UICONTROL Push to Sales Connect] knop die door [!DNL Salesforce] Admin is geïnstalleerd als lijstweergave

* [!DNL Salesforce] Verbinding gemaakt met [!DNL Sales Connect] voor gebruiker die de drukknop maakt

## Procedure {#how-to}

1. Klik op de tab **[!UICONTROL Lead/Contact]** in [!DNL Salesforce] .
1. Schakel over naar de lijstweergave waar u naar wilt duwen [!DNL Sales Connect] naast de knop [!UICONTROL Go] .
1. Klik op **[!UICONTROL Go]**.
1. Selecteer alle leads/contactpersonen die u wilt laten afdrukken.
1. Selecteer **[!UICONTROL Push to MSE]**.
1. Er wordt een nieuw venster weergegeven waarin het aantal leads/contactpersonen dat u wilt laten aanwijzen, wordt gecontroleerd. Selecteer **[!UICONTROL Proceed to Group]**.[!DNL Sales Connect] drukt geen contactpersonen over die zijn gemarkeerd als [!UICONTROL Email Opt Out] in [!DNL Salesforce] of [!UICONTROL Unsubscribed] in [!DNL Sales Connect] .

   >[!NOTE]
   >
   >[!DNL Sales Connect] zal deze groep getiteld &quot;SFDC-...&quot;aan de pagina van Verhoudingen op de [ Webtoepassing ](https://toutapp.com/login) toevoegen.

1. Selecteer **[!UICONTROL Email Entire Group]** om deze groep-e-mail te verzenden.
