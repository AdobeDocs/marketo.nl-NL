---
unique-page-id: 11375827
description: Vereiste velden voor het synchroniseren van Marketo met Dynamics - Marketo Docs - Productdocumentatie
title: Vereiste velden voor het synchroniseren van Marketo met dynamiek
exl-id: c1b9d208-bdc0-4718-b3e5-e9e915b8ae0f
feature: Marketo Sales Insights
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '150'
ht-degree: 1%

---

# Vereiste velden voor het synchroniseren van Marketo met [!DNL Dynamics] {#required-fields-for-syncing-marketo-with-dynamics}

Deze gebieden *moeten* met Marketo voor zowel [!UICONTROL Lead] als voor [!UICONTROL Contact] voor [!DNL Sales Insight] worden gesynchroniseerd om te werken:

* Prioriteit
* Urgentie
* Relatieve score

Als een van deze velden ontbreekt, wordt in Marketo een foutbericht weergegeven met de naam van de ontbrekende velden. Controleer of de velden zijn gesynchroniseerd voor zowel **[!UICONTROL Lead]** als **[!UICONTROL Contact]** om dit probleem op te lossen. Als dat niet het geval is, voegt u deze toe.

Hieronder wordt beschreven hoe u synchronisatievelden kunt verifiëren en toevoegen.

1. Ga naar [!UICONTROL Admin] en klik op **[!UICONTROL Microsoft Dynamics]** .

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Klik op **[!UICONTROL Edit]** op [!UICONTROL Field Sync Details] .

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Schakel onder [!UICONTROL Lead] het selectievakje [!UICONTROL Priority] in.

   ![](assets/image2016-6-8-13-3a33-3a50.png)

1. Nu omlaag schuiven en het selectievakje [!UICONTROL Urgency] inschakelen..

   ![](assets/image2016-6-8-13-3a35-3a22.png)

1. ...en het selectievakje [!UICONTROL Relative Score] .

   ![](assets/image2016-6-8-13-3a36-3a1.png)

1. Schakel vervolgens de selectievakjes in voor [!UICONTROL Priority] , [!UICONTROL Urgency] en [!UICONTROL Relative Score] voor [!UICONTROL Contact] .

   ![](assets/image2016-6-8-13-3a36-3a36.png)

1. Klik op **[!UICONTROL Save]**.

   ![](assets/image2016-6-8-13-3a41-3a27.png)

>[!NOTE]
>
>Wacht minstens 10 minuten voordat een synchronisatie wordt uitgevoerd voordat u controleert of u het probleem hebt opgelost.

>[!MORELIKETHIS]
>
>[ de Sterren en Flames van de Opstelling voor Lood/de Verslagen van het Contact ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
