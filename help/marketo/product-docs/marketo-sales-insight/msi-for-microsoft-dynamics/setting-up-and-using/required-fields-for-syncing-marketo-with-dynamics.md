---
unique-page-id: 11375827
description: Vereiste velden voor het synchroniseren van markeertekens met dynamiek - Marketo Docs - Productdocumentatie
title: Vereiste velden voor het synchroniseren van markeertekens met dynamiek
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '174'
ht-degree: 0%

---


# Vereiste velden voor het synchroniseren van markeertekens met dynamiek {#required-fields-for-syncing-marketo-with-dynamics}

Deze velden *must* moeten met Marketo worden gesynchroniseerd voor zowel Lead als Contact voor het Inzicht van de Verkoop om te werken:

* Prioriteit
* Urgentie
* Relatieve score

Als een van deze velden ontbreekt, wordt in Marketo een foutbericht weergegeven met de naam van de ontbrekende velden. Om dit te bevestigen, controleer uw instantie om ervoor te zorgen dat de gebieden voor zowel **Lood** als **Contact** worden gesynchroniseerd. Zo niet, voegt u deze toe.

Hieronder wordt beschreven hoe u synchronisatievelden kunt verifiëren en toevoegen.

1. Ga naar Admin en klik **de Dynamica van Microsoft**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Klik op **Bewerken** op Details van veldsynchronisatie.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Schakel onder Lead het selectievakje Prioriteit in.

   ![](assets/image2016-6-8-13-3a33-3a50.png)

1. Blader nu omlaag en schakel het selectievakje Urgentie in...

   ![](assets/image2016-6-8-13-3a35-3a22.png)

1. ...en het selectievakje Relatieve score.

   ![](assets/image2016-6-8-13-3a36-3a1.png)

1. Schakel vervolgens de selectievakjes voor Prioriteit, Urgentie en Relatieve score in voor Contact.

   ![](assets/image2016-6-8-13-3a36-3a36.png)

1. Klik **Opslaan**.

   ![](assets/image2016-6-8-13-3a41-3a27.png)

>[!NOTE]
>
>Wacht minstens 10 minuten voordat een synchronisatie wordt uitgevoerd voordat u controleert of u het probleem hebt opgelost.

>[!MORELIKETHIS]
>
>[Sterren en vlammen instellen voor lead/contact-records](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
