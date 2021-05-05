---
description: Spam-formulierverzendingen blokkeren - Marketo Docs - Productdocumentatie
title: Spam-formulierverzendingen blokkeren
translation-type: tm+mt
source-git-commit: 35ab8d353a2518a1603cb508a6f8c0ea650483e4
workflow-type: tm+mt
source-wordcount: '160'
ht-degree: 0%

---

# Spam-formulierverzendingen blokkeren {#how-to-block-spam-form-submissions}

Formulierverzendingen met een ongeldige of ontbrekende controlesom (meestal van bots) kunnen vaak leiden tot onjuiste statistieken. Zo voorkomt u dat.

>[!CAUTION]
>
>Deze eigenschap verwerpt vormvoorlegging die met programmatic POSTs aan het leadCapture/save2 eindpunt wordt gemaakt. Als uw bedrijf gebruikmaakt van een integratie die met die methode formulieren naar Marketo verzendt, worden deze verzendingen geblokkeerd als u deze functie inschakelt. Het gebruik van leadCapture/save2 als API of het direct verzenden van programmatische formulieren naar dit programma wordt niet ondersteund en is verboden. Zorg ervoor dat uw bedrijf alleen formulieren verzendt met: Formulierelementen, ingesloten formuliercode, Forms2.js-API of de REST-API voor formulier verzenden.

1. Klik **Admin**.

   ![](assets/how-to-block-spam-form-submissions-1.png)

1. Klik **Schat op borst**.

   ![](assets/how-to-block-spam-form-submissions-2.png)

1. Naast **Person Capture - Afwijzen ongeldige controlesom Waarden**, klik **Edit**.

   ![](assets/how-to-block-spam-form-submissions-3.png)

1. Selecteer het selectievakje **Ingeschakeld** en klik op **Opslaan**.

   ![](assets/how-to-block-spam-form-submissions-4.png)

>[!NOTE]
>
>Als u deze functie inschakelt, wordt er mogelijk een neerzetbewerking van de formulieractiviteit weergegeven, omdat valse getallen worden uitgefilterd.
