---
unique-page-id: 27656223
description: Aanpassing van Salesforce voor klanten van de Professional Edition installeren - Marketo Docs - Productdocumentatie
title: Aanpassing van Salesforce voor klanten van de Professional Edition installeren
exl-id: dc004a28-b580-4449-9fde-e744681ac53a
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 0%

---

# Aanpassing van Salesforce voor klanten van de Professional Edition installeren {#install-salesforce-customization-for-professional-edition-customers}

Klanten met Salesforce Professional Edition moeten deze stappen volgen om aanpassingen te installeren.

>[!PREREQUISITES]
>
>* Sales Connect Admin moet hun Salesforce- en Sales Connect-accounts verbinden.
>* Er moet ruimte zijn voor de installatie van Salesforce Instance om dertien aangepaste activiteitsvelden te kunnen installeren.

## Installatie {#installation}

1. Klik in Sales Connect op het tandwielpictogram rechtsboven en selecteer **Instellingen**.

   ![](assets/one-4.png)

1. Klik onder Beheerinstellingen op **Salesforce**.

   ![](assets/two-4.png)

1. Controleer of u verbinding hebt met uw Salesforce-account.

   >[!CAUTION]
   >
   >Als u verbonden bent, zult u een groene &quot;installeren&quot;knoop zien. **NIET** Klik op deze knop en ga verder met stap 4.

1. Meld u aan bij de Salesforce-account waarmee u verbinding hebt en klik op [deze koppeling](https://login.salesforce.com/packaging/installPackage.apexp?p0=04t0b000001oWEZ).
1. U wordt naar de pagina voor installatie van Sales Connect verzonden.

   ![](assets/install-package.png)

1. Kies de gebruikers u aanpassingen voor wilt installeren: Alleen beheerder, alle gebruikers of specifieke profielen.
1. Klik op de knop **Installeren** om aanpassing te installeren.
1. Meld u aan bij uw Salesforce-account om te bevestigen dat de installatie is gelukt.
1. Klikken **Instellen**, zoek naar &quot;Geïnstalleerde pakketten&quot; in de zoekbalk en klik op **Geïnstalleerde pakketten**.

   Hier vindt u Marketo Sales Connect-aanpassingen.

   Om Sales Connect in uw Salesforce-exemplaar te configureren, volgt u de stappen die beginnen in de sectie &quot;CONFIGURING THE SALES ENGAGE SALESFORCE PACKAGE&quot; op pagina 7 van de installatiegids.

   >[!NOTE]
   >
   >Sales Engage is de vorige naam voor Sales Connect.

## Hulplijnen {#guides}

[Installatiehandleiding voor Salesforce Classic](https://s3.amazonaws.com/tout-user-store/salesforce/assets/Marketo+Sales+Engage+For+Salesforce_+Installation+and+Success+Guide.pdf)

[Installatiehandleiding voor Salesforce Lightning](https://s3.amazonaws.com/tout-user-store/salesforce/assets/SF+Guide+for+Lightning.pdf)
