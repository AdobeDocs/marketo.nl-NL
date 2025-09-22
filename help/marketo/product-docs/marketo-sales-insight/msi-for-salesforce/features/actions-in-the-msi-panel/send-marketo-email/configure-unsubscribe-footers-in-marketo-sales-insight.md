---
unique-page-id: 2953373
description: Abonnementsvoetteksten configureren in Marketo Sales Insight - Marketo Docs - Productdocumentatie
title: Abonnement op voetteksten opzeggen in Marketo Sales Insight configureren
exl-id: 16c1fcba-6826-400c-ab7c-371d8653d4ad
feature: Marketo Sales Insights
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 0%

---

# Abonnementsvoetteksten configureren in [!DNL Marketo Sales Insight] {#configure-unsubscribe-footers-in-marketo-sales-insight}

E-mails over verkopen plaatsen automatisch de voettekst voor het afmelden van abonnementen onderaan. U kunt de instellingen echter aan uw wensen aanpassen.

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

>[!NOTE]
>
>**Definitie**
>
>**E-mails van de Verkoop** zijn die verzonden van [!DNL Sales Insight] (het omvat niet die verzonden van de Insteekmodule van Marketo Outlook).

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/one-1.png)

1. Klik op **[!UICONTROL Sales Insight]** en vervolgens op **[!UICONTROL Edit Settings]** .

   ![](assets/two-1.png)

   Er zijn verschillende opties. Laten we eerst eens kijken naar de typen e-mails waarvoor u de instellingen kunt wijzigen.

   ![](assets/three-1.png)

   * **[!UICONTROL No Template]** - Handmatig samengesteld door verkoopgebruiker.
   * **[!UICONTROL Standard Email]** - E-mails op basis van een sjabloon.
   * **[!UICONTROL Operational Email]** - E-mails waarin de limiet voor abonnementen, marketingonderbreking en communicatie wordt genegeerd (ze verzenden niets).

   U kunt voor elk type een ander gedrag instellen.

   >[!CAUTION]
   >
   >**[!UICONTROL Respect Unsubscribe Settings]**: niet-geabonneerde leads ontvangen de e-mail NIET, zelfs niet als de gepubliceerde e-mail &quot;operationeel&quot; is
   >
   >**[!UICONTROL Ignore Unsubscribe Settings]**: niet-geabonneerde leads ontvangen het e-mailbericht

1. Breng de gewenste wijzigingen aan en klik op **[!UICONTROL Save]** .

   >[!TIP]
   >
   >Met de laatste twee opties kunt u dynamisch de voettekst opnemen of uitsluiten, afhankelijk van het aantal ontvangers (groter dan 1 of groter dan 5).

   ![](assets/four-1.png)

Waar! Een beetje gecompliceerd, maar behoorlijk flexibel, toch?
