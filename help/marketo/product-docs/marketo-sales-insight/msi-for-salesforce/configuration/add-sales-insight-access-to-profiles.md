---
description: Verkoop Insight Access toevoegen aan profielen - Marketo Docs - Productdocumentatie
title: Insight-toegang voor verkoop toevoegen aan profielen
exl-id: 269f9093-f530-4e3b-aac7-e317976cf0f0
feature: Marketo Sales Insights
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '363'
ht-degree: 0%

---

# [!DNL Sales Insight] Toegang tot profielen toevoegen {#add-sales-insight-access-to-profiles}

Hieronder wordt beschreven hoe u een profiel maakt met toegang tot [!DNL Sales Insight] terwijl u de toegang voor andere profielen verwijdert. Dit is voor gebruikers die reeds het [[!DNL Sales Insight]  pakket van AppExchange ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"} hebben geïnstalleerd.

>[!IMPORTANT]
>
>Als u eerder [!DNL Sales Insight] toegang tot alle profielen hebt verleend, moet u [ de toegang van het profielniveau ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/remove-sales-insight-access.md){target="_blank"} verwijderen om deze toestemmingsreeks te gebruiken.

## Een nieuw profiel maken voor [!DNL Sales Insight] {#create-a-new-profile-for-sales-insight}

Als u een specifiek profiel voor uw [!DNL Sales Insight] -gebruikers hebt, kunt u deze stap overslaan.

1. Ga in [!DNL Salesforce] naar de pagina Setup.

1. Zoek naar profielen in Snelle Vondst en selecteer de **[!UICONTROL Profile]** optie.

1. Klik op de knop **[!UICONTROL New Profile]** boven aan de pagina.

1. Kies een profiel om te klonen en geef dit een naam (bijvoorbeeld Insight-gebruiker verkopen).

1. Klik op **[!UICONTROL Save]** als u klaar bent.

## [!DNL Sales Insight] Machtigingen toevoegen {#add-sales-insight-permissions}

1. Ga terug naar de lijst met profielen.

1. Klik op de koppeling **[!UICONTROL Edit]** voor het nieuwe profiel dat u zojuist hebt gemaakt (of op een ander bestaand profiel dat u [!DNL Sales Insight] toegang wilt geven).

1. Op de bewerkingspagina moet u een aantal instellingen wijzigen.

   **voor profielen die toegang worden verleend[!DNL Sales Insight]**:

   * Wijzig in Tabinstellingen de Marketo-tabbladen in Standaard ingeschakeld
   * In de Toestemmingen van de Objecten van de Douane, controleer Gelezen, creeer, geef uit, en schrap [!DNL Marketo Sales Insight] Config (als de gebruiker toegang tot de config montages zou moeten hebben - typisch gebruikt voor Admins)

   **voor profielen die geen toegang tot[!DNL Sales Insight]** worden toegestaan:

   * Wijzig in Tabinstellingen de tabbladen van Marketo in Tabblad Hidden
   * Schakel in Aangepaste objectmachtigingen de optie Lezen, Maken, Bewerken en Verwijderen uit in [!DNL Marketo Sales Insight] Configuratie

1. Klik op **[!UICONTROL Save]** als u klaar bent.

## Lay-out maken voor [!DNL Sales Insight] {#create-layout-for-sales-insight}

1. Ga naar de pagina Setup en klik vervolgens op **[!UICONTROL App Setup]** > **[!UICONTROL Customize]** > **[!UICONTROL Leads]** > **[!UICONTROL Page Layouts]** . Klik vervolgens op de knop **[!UICONTROL New]** .

1. Kloont de lay-out en geef de lay-out een geschikte naam (bijvoorbeeld Verkoopindeling Insight).

1. Klik op **[!UICONTROL Save]** als u klaar bent.

1. Herhaal deze stappen voor de paginalay-outs [!UICONTROL Contacts] , [!UICONTROL Opportunities] en [!UICONTROL Accounts] .

## Profiel toewijzen aan layout {#assign-profile-to-layout}

1. Ga terug naar de sectie Pagina-indelingen en klik op de knop **[!UICONTROL Page Layout Assignment]** .

1. Selecteer **[!UICONTROL Edit Assignment]** .

1. Selecteer uw [!DNL Sales Insight] profiel van de lijst, dan selecteer uw [!DNL Sales insight] lay-out van &quot;[!UICONTROL Select Page Layout]&quot;drop-down.

1. Klik op **[!UICONTROL Save]** als u klaar bent.

1. Herhaal deze stappen voor de paginalay-outs [!UICONTROL Contacts] , [!UICONTROL Opportunities] en [!UICONTROL Accounts] .

## Overige wijzigingen {#other-changes}

Hier zijn enkele andere plaatsen waar [!DNL Sales Insight] -items kunnen worden weergegeven. U moet ze rechtstreeks verwijderen omdat u geen profielen kunt gebruiken om de toegang te beperken tot:

* Verwijder [!DNL Sales Insight] -knoppen uit Zoekindelingen voor [!UICONTROL Contacts] , [!UICONTROL Leads] en [!UICONTROL Accounts]
* [!DNL Sales Insight] kolommen verwijderen uit lijst met contactpersonen en leads
