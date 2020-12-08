---
unique-page-id: 2359416
description: Automatische e-mailrespons - Marketo Docs - Productdocumentatie
title: Automatische reactie e-mail
translation-type: tm+mt
source-git-commit: 09dbd3a141fed0525aec8bf1ca6d141be2a6ce46
workflow-type: tm+mt
source-wordcount: '436'
ht-degree: 0%

---


# Automatische reactie e-mail {#email-auto-response}

## Opdracht: Een e-mailbericht sturen waarin een persoon een formulier invult {#mission-send-out-a-thank-you-email-when-a-person-fills-out-a-form}

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

>[!NOTE]
>
>**Vereisten**
>
>* [Instellen en een persoon toevoegen](get-set-up-and-add-a-person.md)
>* [Openingspagina met formulier](landing-page-with-a-form.md)

>



## Stap 1: Een e-mail maken {#step-create-an-email}

1. Ga naar het gebied Marketingactiviteiten.

   ![](assets/one-2.png)

1. Selecteer Mijn Programma in het linkermenu, klik Nieuwe drop-down, en selecteer Nieuw Lokaal Middel.

   ![](assets/two-3.png)

1. Klik op E-mail.

   ![](assets/three-2.png)

1. Geef uw e-mail de naam &quot;Auto Response Email&quot;, kies een sjabloon en klik op Maken.

   ![](assets/four-1.png)

   Een e-maileditor wordt geopend in een nieuw venster of op een nieuw tabblad. Als pop-ups zijn geblokkeerd, klikt u op** Concept bewerken** op de overzichtspagina voor middelen om het e-mailbericht te openen.

1. Voer een onderwerpregel in en dubbelklik op het bewerkbare gebied van de e-mail.

   ![](assets/five-2.png)

   Boven op de e-maileditor wordt een RTF-editor geopend.

1. Markeer de bestaande e-mailinhoud.

   ![](assets/six-2.png)

1. Typ uw e-mailinhoud en klik op Opslaan.

   ![](assets/seven-2.png)

1. De wijzigingen worden automatisch opgeslagen. Sluit het tabblad/venster van de e-maileditor.

   ![](assets/eight-1.png)

1. Selecteer uw nieuwe e-mail. Klik onder E-mailhandelingen op Goedkeuren.

   ![](assets/image2014-9-24-11-3a55-3a16.png)

## Stap 2: Een slimme campagne maken {#step-create-a-smart-campaign}

1. Klik met de rechtermuisknop op **Mijn programma** en klik op **Nieuwe slimme campagne**.

   ![](assets/image2014-9-24-11-3a56-3a13.png)

1. **Geef** uw slimme campagne de naam ‘Auto Response Campaign’ en klik op **Maken**.

   ![](assets/image2014-9-24-11-3a56-3a25.png)

1. Ga naar de **Slimme Lijst **tabel.

   ![](assets/image2014-9-24-11-3a56-3a38.png)

   Deze campagne wordt uitgevoerd wanneer iemand het formulier invult dat u met een formulier [**op de**](landing-page-with-a-form.md) landingspagina hebt gemaakt.

1. Zoek de trigger Formulier **** invullen en sleep deze naar het linkercanvas.

   ![](assets/image2014-9-24-11-3a57-3a18.png)

1. Selecteer **Mijn formulier** in de vervolgkeuzelijst. Klik op het tabblad **Flow **tab.

   ![](assets/image2014-9-24-11-3a57-3a29.png)

1. Sleep de actie **E-mail verzenden **flow naar het linkercanvas.

   ![](assets/image2014-9-24-11-3a57-3a41.png)

1. Selecteer uw **Auto E-mail** van de Reactie en ga naar **Schema **tabel.

   ![](assets/image2014-9-24-11-3a57-3a53.png)

1. Klik op **Bewerken**.

   ![](assets/8.png)
Selecteer deze optie telkens en klik op Opslaan.
   ![](assets/9.png)

1. Klik op **Activeren**.

   ![](assets/10.png)

1. Klik op **Activeren **op het bevestigingsscherm.

   ![](assets/11.png)

>[!NOTE]
>
>Zodra actief, zal deze campagne lopen telkens als een persoon het gespecificeerde formulier invult. De campagne blijft actief tot ze gedeactiveerd is.

## Stap 3: Het formulier invullen {#step-fill-out-the-form}

1. Selecteer **Mijn pagina**. Dit bestand is gemaakt op de [bestemmingspagina met een snelle overwinning op het formulier](landing-page-with-a-form.md) .

   ![](assets/image2014-9-24-12-3a0-3a8.png)

1. Klik op Goedgekeurde pagina **** weergeven.

   ![](assets/image2014-9-24-12-3a0-3a18.png)

   De openingspagina voor gratis proefversie wordt geopend op een nieuw tabblad.

1. Vul het formulier in met uw voornaam, achternaam en e-mailadres en klik vervolgens op **Verzenden**.

   ![](assets/image2014-9-24-12-3a0-3a28.png)

>[!NOTE]
>
>Gebruik uw werkelijke e-mailadres zodat u het e-mailbericht kunt ontvangen.

## Opdracht voltooid {#mission-complete}

Binnen een paar minuten ziet u het e-mailbericht voor automatische reacties in uw Postvak IN. Geweldig werk!

<br> 

[◄ Missie 3: Eenvoudige score](simple-scoring.md) [missie 5: Een lijst met leads importeren ►](import-a-list-of-people.md)