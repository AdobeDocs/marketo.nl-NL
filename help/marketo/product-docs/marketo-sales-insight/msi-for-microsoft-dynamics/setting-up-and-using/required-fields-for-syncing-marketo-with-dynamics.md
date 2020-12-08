---
unique-page-id: 11375827
description: Vereiste velden voor het synchroniseren van markeertekens met dynamiek - Marketo Docs - Productdocumentatie
title: Vereiste velden voor het synchroniseren van markeertekens met dynamiek
translation-type: tm+mt
source-git-commit: c33b7ab59e612f37d3f64bb954579700dc574068
workflow-type: tm+mt
source-wordcount: '180'
ht-degree: 0%

---


# Vereiste velden voor het synchroniseren van markeertekens met dynamiek {#required-fields-for-syncing-marketo-with-dynamics}

Deze gebieden *moeten* met Marketo voor zowel Lood als Contact voor het Inzicht van de Verkoop worden gesynchroniseerd om te werken:

* Prioriteit
* Urgentie
* Relatieve score

Als een van deze velden ontbreekt, wordt in Marketo een foutbericht weergegeven met de naam van de ontbrekende velden. U kunt dit corrigeren door in te checken of de velden zijn gesynchroniseerd voor zowel **lead** als **contact**. Zo niet, voegt u deze toe.

Hieronder wordt beschreven hoe u synchronisatievelden kunt verifiëren en toevoegen.

1. Ga naar Admin en klik de Dynamica van Microsoft.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Klik op Bewerken op Veldsynchronisatiedetails.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Schakel onder Lead het selectievakje Prioriteit in.

   ![](assets/image2016-6-8-13-3a33-3a50.png)

1. Blader nu omlaag en schakel het selectievakje Urgentie in...

   ![](assets/image2016-6-8-13-3a35-3a22.png)

1. ...en het selectievakje Relatieve score.

   ![](assets/image2016-6-8-13-3a36-3a1.png)

1. Schakel vervolgens de selectievakjes voor Prioriteit, Urgentie en Relatieve score in voor Contact.

   ![](assets/image2016-6-8-13-3a36-3a36.png)

1. Klik op Opslaan.

   ![](assets/image2016-6-8-13-3a41-3a27.png)

>[!NOTE]
>
>Wacht minstens 10 minuten voordat een synchronisatie wordt uitgevoerd voordat u controleert of u het probleem hebt opgelost.

>[!NOTE]
>
>**Verwante artikelen**
>
>[Sterren en vlammen instellen voor lead/contact-records](http://docs.marketo.com/x/BICMAg)

