---
description: Abonnementen synchroniseren met Salesforce - Marketo Docs - Productdocumentatie
title: Abonnementen synchroniseren met Salesforce
exl-id: b5b0f625-e38c-4a03-81e7-010082001636
feature: Sales Insight Actions
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '458'
ht-degree: 0%

---

# Abonnementen synchroniseren met [!DNL Salesforce] {#syncing-unsubscribes-with-salesforce}

Als u afmeldingsgegevens wilt synchroniseren met een veld om te weigeren in Salesforce, kunt u de synchronisatie van Salesforce afmelden gebruiken.

## Vereisten voor Afmelden voor synchronisatie met Salesforce {#requirements-for-unsubscribes-to-sync-to-salesforce}

* Synchronisatie voor afmelden moet zijn ingeschakeld (voor nachtelijke synchronisatie)
* Het veld Uitschakelen moet zijn geïnstalleerd in [!DNL Salesforce]
* Persoonsrecords in [!DNL Marketo Sales] moeten een [!DNL Salesforce] ID hebben

**duw Unsubscribes**

Wanneer een abonnement wordt opgehaald in [!DNL Marketo Sales] , wordt dit in realtime naar [!DNL Salesforce] verplaatst en worden de velden voor Weigeren bijgewerkt waarmee u hebt geselecteerd voor synchronisatie. Als u de synchronisatie van [!DNL Salesforce] hebt uitgeschakeld, wordt de e-mailmelding weer verzonden naar de e-mailoptie Weigeren.

**Unsubscribe Synchronisatie**

Wanneer u de synchronisatie voor afmelden hebt ingeschakeld (stap 3 hieronder), schakelt u de nachtelijke synchronisatie in. De synchronisatie vindt eenmaal per dag plaats rond 08.00 uur PST. :00 Alle afmeldingsgegevens in Marketo Sales worden bidirectioneel gesynchroniseerd met het veld Opt Out in Salesforce.

>[!NOTE]
>
>Als u de synchronisatie met Salesforce afsluit, worden de abonnementen gesynchroniseerd, maar worden herabonnementen niet gesynchroniseerd. Als je een abonnement op Marketo Sales en Salesforce wilt verwijderen, schakel je het abonnement in Salesforce uit en verwijder je het abonnement op Marketo Sales.

## Synchronisatie voor afmelden configureren naar [!DNL Salesforce] {#configure-unsubscribe-sync-to-salesforce}

Gebruikers kunnen beslissen of ze hun afmeldingsgegevens willen synchroniseren met het standaardveld Afmelden via e-mail waarmee Marketo ook kan synchroniseren, of ze kunnen synchroniseren met het veld [!DNL Marketo Sales] Afmelden uitschakelen zodat afmeldingsgegevens voor verkoop en Afmeldingsgegevens voor marketing kunnen worden gedifferentieerd.

1. Klik op het tandwielpictogram en selecteer **[!UICONTROL Settings]** .

   ![](assets/syncing-unsubscribes-with-salesforce-1.png)

1. Onder [!UICONTROL Admin Settings] selecteert u **[!UICONTROL Unsubscribes]** .

   ![](assets/syncing-unsubscribes-with-salesforce-2.png)

1. Klik op de tab **[!UICONTROL Integrations]** . Schakel onder [!UICONTROL Sync to Salesforce] de nachtelijke synchronisatie in.

   ![](assets/syncing-unsubscribes-with-salesforce-3.png)

1. Selecteer het veld waarmee u wilt synchroniseren.

   ![](assets/syncing-unsubscribes-with-salesforce-4.png)

   | Veld | Beschrijving |
   |---|---|
   | **Synchronisatie aan [!DNL Salesforce] Weigeren gebied** | Hiermee wordt het veld [!DNL Salesforce] Weigeren alleen bijgewerkt. Deze optie is standaard ingeschakeld. |
   | **Synchronisatie aan [!DNL Marketo Sales] Weigeren gebied** | Als u verkoop en Marketing wilt scheiden unsubscribes, verkies deze optie om extra [[!DNL Marketo Sales]  uit gebied bij te werken.](#msoo) |

## Het veld Weigeren installeren in de paginalayout {#installing-the-opt-out-field-in-the-page-layout}

**E-mail verlaat**

E-mail Weigeren is een standaardveld in [!DNL Salesforce] dat u kunt installeren vanuit [!DNL Salesforce] . U moet een [!DNL Salesforce] Admin zijn om het te installeren.

1. Ga naar [ Salesforce.com ](https://salesforce.com) en teken binnen.

   ![](assets/syncing-unsubscribes-with-salesforce-5.png)

1. Klik op uw gebruikersnaam en selecteer **[!UICONTROL Setup]** .

   ![](assets/syncing-unsubscribes-with-salesforce-6.png)

1. Zoek in het vak Snel zoeken naar Contactpersoon of Lead. In dit scenario installeren wij het gebied aan de de paginalay-out van het Contact, maar u zult voor beide persoonverslagen willen installeren.

   ![](assets/syncing-unsubscribes-with-salesforce-7.png)

1. Selecteer **[!UICONTROL Page Layouts]**.

   ![](assets/syncing-unsubscribes-with-salesforce-8.png)

1. Selecteer **[!UICONTROL Edit]** naast de pagina-indeling waaraan u het veld wilt toevoegen.

   ![](assets/syncing-unsubscribes-with-salesforce-9.png)

1. Selecteer **[!UICONTROL Fields]**.

   ![](assets/syncing-unsubscribes-with-salesforce-10.png)

1. Sleep [!UICONTROL Email Opt Out] naar de pagina-indeling.

   ![](assets/syncing-unsubscribes-with-salesforce-11.png)

1. Klik op **[!UICONTROL Save]**.

   ![](assets/syncing-unsubscribes-with-salesforce-12.png)

## Marketo-verkoop niet beschikbaar {#marketo-sales-opt-out}

Het gebied van de Verkoop van Marketo uit is een douanegebied dat aan gebruikers beschikbaar is die het pakket van Insight van de Verkoop van Marketo [ van AppExchange ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"} hebben geïnstalleerd.

Zodra u het Marketo Sales Insight-pakket van de AppExchange naar Salesforce hebt geïnstalleerd, ziet u het veld Marketo Sales Opt Out dat voor u beschikbaar is.
