---
unique-page-id: 2359414
description: Eenvoudig scoren - Marketo Docs - Productdocumentatie
title: Eenvoudige scores
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '425'
ht-degree: 0%

---


# Eenvoudige scores {#simple-scoring}

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

>[!PREREQUISITES]
>
>* [Instellen en een persoon toevoegen](get-set-up-and-add-a-person.md)
>* [Openingspagina met formulier](landing-page-with-a-form.md)

>



## Stap 1: Een scoringcampagne maken {#step-create-a-scoring-campaign}

1. Ga naar het gebied **Marketingactiviteiten** .

   ![](assets/ma-1.png)

1. Klik met de rechtermuisknop op de **map Learning** en klik op **Nieuwe campagnemap**.

   ![](assets/two-2.png)

1. Geef de map &#39;Scoring&#39; voor de campagne een naam.

   ![](assets/three-1.png)

   >[!NOTE]
   >
   >Als u al een map met scores hebt, geeft u deze een andere naam, bijvoorbeeld Scoring 1. Mapnamen moeten uniek zijn.

1. Klik vervolgens met de rechtermuisknop op de nieuwe **map voor het** scoren en selecteer **Nieuwe slimme campagne**.

   ![](assets/four.png)

1. **Geef** de campagne de naam &#39;Score wijzigen&#39; en klik op **Maken**.

   ![](assets/five-1.png)

1. Klik op het tabblad **Slimme lijst** .

   ![](assets/six-1.png)

   We willen dat deze campagne wordt uitgevoerd wanneer iemand uw aanvraagformulier voor **proefversie invult**.

1. Zoek en sleep de trigger Formulier **** invullen naar het linkercanvas.

   ![](assets/image2014-9-24-11-3a43-3a35.png)

1. Selecteer **Mijn formulier**.

   >[!NOTE]
   >
   >Als u de [bestemmingspagina hebt voltooid met een formulier](landing-page-with-a-form.md) dat u snel kunt winnen, hebt u het formulier nodig. Als u een andere naam hebt gebruikt voor het formulier, selecteert u die naam.

   ![](assets/image2014-9-24-11-3a44-3a16.png)

1. Klik op het tabblad **Flow **tab.

   ![](assets/image2014-9-24-11-3a44-3a33.png)

1. Sleep de **actie Score** wijzigen naar het linkercanvas.

   ![](assets/image2014-9-24-11-3a44-3a45.png)

1. U kunt elke waarde typen die u aan de persoonlijke score wilt toevoegen. Voer &#39;+5&#39; in het veld **Wijzigen** .

   ![](assets/eleven-1.png)

   >[!TIP]
   >
   >Goede scoringcampagnes zijn essentieel om mensen van hoge kwaliteit aan de Verkoop te leveren. Lees [**de Definitieve Gids aan het Toren van de Lood**](http://www.marketo.com/definitive-guides/lead-scoring/).

1. Klik op het tabblad **Schema** en op de knop **Activeren** .

   ![](assets/twelve-1.png)

1. Klik op **Activeren** op het bevestigingsscherm.

   ![](assets/thirteen-1.png)

>[!NOTE]
>
>Zodra deze campagne actief is, wordt deze uitgevoerd telkens wanneer een persoon het formulier invult. De campagne blijft actief tot ze gedeactiveerd is.

## Stap 2: Het formulier invullen {#step-fill-out-the-form}

1. Selecteer de openingspagina die u op de [bestemmingspagina hebt gemaakt met een formulier](landing-page-with-a-form.md) dat u snel kunt winnen.

   ![](assets/fourteen-1.png)

1. Klik op Goedgekeurde pagina **** weergeven. De landingspagina wordt geopend op een nieuw tabblad.

   ![](assets/image2014-9-24-11-3a47-3a51.png)

1. Vul het formulier in met uw voornaam, achternaam en e-mailadres en klik vervolgens op **Verzenden** .

   ![](assets/image2014-9-24-11-3a47-3a59.png)

   >[!NOTE]
   >
   >Gebruik dezelfde naam en hetzelfde e-mailadres als u hebt gebruikt toen u zichzelf voor het eerst als persoon hebt ingevoerd om de score + 5 toe te passen.

## Stap 3: Persoonsgegevens weergeven {#step-view-the-person-info}

1. Ga naar het gebied Database.

   ![](assets/db-2.png)

1. Zoeken naar het e-mailadres dat u hebt gebruikt bij het invullen van het formulier.

   ![](assets/eighteen.png)

1. Dubbelklik op uw persoon.

   ![](assets/nineteen.png)

De gegevens van uw persoon worden geopend in een nieuw tabblad of venster. Zie hoe uw score met 5 punten is verhoogd om het formulier in te vullen?!

![](assets/twenty.png)

**Gefeliciteerd!** Je hebt een scoring campagne gemaakt.
[◄ Missie 2: Openingspagina met formulier](landing-page-with-a-form.md) [Mission 4: Automatische e-mailrespons ►](email-auto-response.md)