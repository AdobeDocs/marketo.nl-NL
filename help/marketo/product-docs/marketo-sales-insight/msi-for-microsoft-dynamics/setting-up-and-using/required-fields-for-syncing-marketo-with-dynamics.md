---
unique-page-id: 11375827
description: Vereiste velden voor het synchroniseren van Marketo met Dynamics - Marketo Docs - Productdocumentatie
title: Vereiste velden voor het synchroniseren van Marketo met dynamiek
exl-id: c1b9d208-bdc0-4718-b3e5-e9e915b8ae0f
feature: Marketo Sales Insights
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '174'
ht-degree: 0%

---

# Vereiste velden voor het synchroniseren van Marketo met dynamiek {#required-fields-for-syncing-marketo-with-dynamics}

Deze velden *moet* zijn gesynchroniseerd met Marketo voor zowel lead als contact voor Sales Insight voor gebruik:

* Prioriteit
* Urgentie
* Relatieve score

Als een van deze velden ontbreekt, wordt in Marketo een foutbericht weergegeven met de naam van de ontbrekende velden. Controleer of de velden voor beide zijn gesynchroniseerd om dit te corrigeren **Lood** en **Contact**. Zo niet, voegt u deze toe.

Hieronder wordt beschreven hoe u synchronisatievelden kunt verifiëren en toevoegen.

1. Ga naar Beheer en klik op **Microsoft Dynamics**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Klikken **Bewerken** op Veldsynchronisatiedetails.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Schakel onder Lead het selectievakje Prioriteit in.

   ![](assets/image2016-6-8-13-3a33-3a50.png)

1. Blader nu omlaag en schakel het selectievakje Urgentie in...

   ![](assets/image2016-6-8-13-3a35-3a22.png)

1. ...en het selectievakje Relatieve score.

   ![](assets/image2016-6-8-13-3a36-3a1.png)

1. Schakel vervolgens de selectievakjes voor Prioriteit, Urgentie en Relatieve score in voor Contact.

   ![](assets/image2016-6-8-13-3a36-3a36.png)

1. Klikken **Opslaan**.

   ![](assets/image2016-6-8-13-3a41-3a27.png)

>[!NOTE]
>
>Wacht minstens 10 minuten voordat een synchronisatie wordt uitgevoerd voordat u controleert of u het probleem hebt opgelost.

>[!MORELIKETHIS]
>
>[Sterren en vlammen instellen voor lead/contact-records](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
