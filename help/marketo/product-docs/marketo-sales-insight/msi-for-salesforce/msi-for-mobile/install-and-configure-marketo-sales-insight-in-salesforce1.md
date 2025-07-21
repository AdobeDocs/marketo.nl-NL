---
unique-page-id: 7511512
description: Marketo Sales Insight installeren en configureren in Salesforce1 - Marketo Docs - Productdocumentatie
title: Marketo Sales Insight in Salesforce1 installeren en configureren
exl-id: 9f26e90b-3199-4ef8-92bc-95e8bd81f1c5
feature: Marketo Sales Insights
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '284'
ht-degree: 4%

---

# Installeren en configureren [!DNL Marketo Sales Insight] in [!DNL Salesforce1] {#install-and-configure-marketo-sales-insight-in-salesforce}

>[!NOTE]
>
>Bestaande klanten, gelieve [ Uw Pakket MSI ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md) te bevorderen alvorens u verdergaat!

>[!PREREQUISITES]
>
>Als u Salesforce Enterprise/Unlimited hebt:
>
>* [ Stap 1 van 3: Voeg de Gebieden van Marketo aan  [!DNL Salesforce]  toe (Onderneming/Onbeperkt) ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)
>* [ Stap 2 van 3: Creeer a [!DNL Salesforce]  Gebruiker voor Marketo (Onderneming/Onbeperkt) ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)
>* [ Stap 3 van 3: Verbind Marketo en  [!DNL Salesforce]  (Onderneming/Onbeperkt) ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-3-of-3-connect-marketo-and-salesforce-enterprise-unlimited.md)
>* [ vorm  [!DNL Marketo Sales Insight]  in  [!DNL Salesforce]  Onderneming/Onbeperkt ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md)
>
>Als u Salesforce Professional hebt:
>
>* [ vorm Marketo Verkoop Insight in de Professionele Uitgave van Salesforce ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md)
>

>[!NOTE]
>
>[!DNL Marketo Sales Insight] in [!DNL Salesforce1] omvat: [!DNL B test Bets &#x200B;], voer van het Lood, het Interesten Momenten, en voeg aan de Campagne van Marketo toe.

## De mobiele toepassing van [!DNL Salesforce1] inschakelen {#enable-the-salesforce1-mobile-app}

1. Klik op **[!DNL Setup]** en vervolgens op **[!DNL Mobile Administration]**.

   ![](assets/image2015-4-21-15-3a29-3a22.png)

1. Klik op **[!UICONTROL Salesforce1]**.

   ![](assets/image2015-4-21-15-3a30-3a51.png)

1. Klik op **[!UICONTROL Salesforce1 Settings]**.

   ![](assets/image2015-4-21-15-3a32-3a21.png)

1. Klik op **[!UICONTROL Enable the Salesforce1 mobile browser app]**.

   ![](assets/image2015-4-21-15-3a34-3a27.png)

1. Klik op **[!UICONTROL Save]**.

   ![](assets/image2015-4-21-15-3a42-3a48.png)

1. Selecteer **[!UICONTROL Mobile Administration]** .

   ![](assets/image2015-4-22-11-3a10-3a14.png)

1. Klik op **[!UICONTROL Manage the mobile navigation menu]**.

   ![](assets/image2015-4-22-11-3a13-3a10.png)

1. Selecteer **[!UICONTROL Marketo]** en **[!UICONTROL Add]** het aan de **[!UICONTROL Selected]** menu-items.

   ![](assets/image2015-4-22-14-3a55-3a37.png)

1. Selecteer **[!UICONTROL Marketo]** , verplaats het **[!UICONTROL Up]** naar een gewenst gebied en klik op **[!UICONTROL Save]** .

   ![](assets/image2015-4-22-17-3a20-3a56.png)

## Verouderd aangepast Marketo-object verbergen {#hide-outdated-marketo-custom-object}

1. Klik op **[!UICONTROL Setup]**.

   ![](assets/image2015-4-22-15-3a13-3a48.png)

1. Selecteer **[!UICONTROL Manage Users]** .

   ![](assets/image2015-5-5-11-3a13-3a45.png)

1. Selecteer **[!UICONTROL Profiles]** .

   ![](assets/image2015-5-5-11-3a15-3a21.png)

1. Klik om de gewenste profielen **[!UICONTROL Edit]** te selecteren.

   ![](assets/image2015-5-5-13-3a51-3a36.png)

1. Onder **[!UICONTROL Tab Settings]**, selecteer _eerst_ **[!UICONTROL Marketo]**.

   ![](assets/image2015-5-5-13-3a55-3a36.png)

1. Selecteer **[!UICONTROL Tab Hidden]** .

   ![](assets/image2015-5-5-14-3a2-3a29.png)

   >[!NOTE]
   >
   >Verberg het tabblad Marketo voor alle gewenste profielen.

## Tabs aanpassen {#customize-tabs}

1. Klik **+**.

   ![](assets/image2015-4-22-17-3a14-3a49.png)

1. Klik op **[!UICONTROL Customize My Tabs]**.

   ![](assets/image2015-4-22-17-3a16-3a22.png)

1. Selecteer **[!UICONTROL Marketo]** en **[!UICONTROL Add]** het aan de Geselecteerde Lusjes.

   ![](assets/image2015-4-22-17-3a17-3a15.png)

1. Selecteer **[!UICONTROL Marketo]** , verplaats het **[!UICONTROL Up]** naar een gewenst gebied en klik op **[!UICONTROL Save]** .

   ![](assets/image2015-4-22-18-3a29-3a47.png)

## Paginalay-outs aanpassen {#customize-page-layouts}

1. Klik op **[!UICONTROL Setup]**.

   ![](assets/image2015-4-22-17-3a26-3a56.png)

1. Klik op **[!UICONTROL Setup]** , typ **[!UICONTROL Page Layouts]** en klik op **[!UICONTROL Page Layouts]** onder Leads.

   >[!NOTE]
   >
   >Herhaal de stappen voor elke pagina-indeling die uw organisatie gebruikt (marketing, verkoop, enz.) voor de objecten Contact, Account en Opportunity.

   ![](assets/image2015-4-22-17-3a34-3a33.png)

1. Klik op **[!UICONTROL Edit]** om wijzigingen aan te brengen in de layout van de lead.

   ![](assets/image2015-4-22-17-3a44-3a0.png)

1. Klik op **[!UICONTROL Visualforce Pages]** en sleep **[!UICONTROL Lead Mobile]** naar de sectie Mobiele kaarten.

   ![](assets/image2015-4-22-17-3a49-3a37.png)

1. Wijzig de hoogte in 66 en klik op **[!UICONTROL OK]** .

   ![](assets/image2015-4-22-17-3a52-3a15.png)

1. Klik op **[!UICONTROL Fields]** en sleep **[!UICONTROL Add to Marketo Campaign]** naar de sectie **[!UICONTROL Marketo Sales Insight]** .

   ![](assets/configure-step-6.png)

   >[!TIP]
   >
   >Typ &quot;Toevoegen aan&quot; in de snelzoekopdracht om Toevoegen aan Marketo-campagne gemakkelijk te vinden.

1. Klik op **[!UICONTROL Save]**.

   ![](assets/image2015-4-22-18-3a1-3a56.png)

Phew! U bent klaar met de installatie van [!DNL Marketo Sales Insight] for [!DNL Salesforce1]! Ga je gang en geef jezelf een stukje op de rug.

>[!MORELIKETHIS]
>
>* [[!DNL Best Bets]  in  [!DNL Salesforce1]](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/msi-for-mobile/best-bets-in-salesforce1.md)
>* [ Interesserende Momenten in  [!DNL Salesforce1]](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/msi-for-mobile/interesting-moments-in-salesforce1.md)
>* [ verzend Marketo E-mail en Campagne en de Acties van de Controlelijst in  [!DNL Salesforce1]](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/msi-for-mobile/send-marketo-email-and-campaign-and-watchlist-actions-in-salesforce1.md)
