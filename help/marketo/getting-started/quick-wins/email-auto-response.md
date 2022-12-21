---
unique-page-id: 2359416
description: Automatische e-mailrespons - Marketo Docs - Productdocumentatie
title: Automatische reactie e-mail
exl-id: c9c0a154-65ec-4845-97a0-a2100223cb13
source-git-commit: 1c350eb17992e45b9e0f825e1abd5c86555d0a0a
workflow-type: tm+mt
source-wordcount: '385'
ht-degree: 0%

---

# Automatische reactie e-mail {#email-auto-response}

## Opdracht: Een e-mailbericht sturen waarin een persoon een formulier invult {#mission-send-out-a-thank-you-email-when-a-person-fills-out-a-form}

>[!PREREQUISITES]
>
>* [Instellen en een persoon toevoegen](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md){target=&quot;_blank&quot;}
>* [Openingspagina met formulier](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target=&quot;_blank&quot;}


## Stap 1: Een e-mail maken {#step-create-an-email}

1. Ga naar het gebied Marketingactiviteiten.

   ![](assets/email-auto-response-1.png)

1. Selecteer uw programma in het linkermenu, klik op **Nieuw** en selecteert u **Nieuw lokaal element**.

   ![](assets/email-auto-response-2.png)

1. Selecteren **E-mail**.

   ![](assets/email-auto-response-3.png)

1. Geef uw e-mail de naam &quot;Auto Response Email&quot;, kies een sjabloon en klik op **Maken**.

   ![](assets/email-auto-response-4.png)

   Een e-maileditor wordt geopend in een nieuw venster of op een nieuw tabblad. Als pop-ups worden geblokkeerd, klikt u op **Concept bewerken** op de overzichtspagina voor middelen om het e-mailbericht te openen.

1. Voer een onderwerpregel in en dubbelklik op het bewerkbare gebied van de e-mail.

   ![](assets/email-auto-response-5.png)

   _Boven op de e-maileditor wordt een RTF-editor geopend._

1. Markeer de bestaande e-mailinhoud.

   ![](assets/email-auto-response-6.png)

1. Typ uw e-mailinhoud en klik op **Opslaan**.

   ![](assets/email-auto-response-7.png)

1. Klik op de knop **E-mailhandelingen** vervolgkeuzelijst en selecteer **Goedkeuren en Sluiten**.

   ![](assets/email-auto-response-8.png)

## Stap 2: Een slimme campagne maken {#step-create-a-smart-campaign}

1. Selecteer uw programma, klik **Nieuw** vervolgkeuzelijst en selecteer **Nieuwe slimme campagne**.

   ![](assets/email-auto-response-9.png)

1. **Naam** uw slimme campagne &quot;Auto Response Campaign&quot; en klik op **Maken**.

   ![](assets/email-auto-response-10.png)

1. Ga naar de **Slimme lijst** tab.

   ![](assets/email-auto-response-11.png)

   Deze campagne wordt uitgevoerd wanneer iemand het formulier invult dat u hebt gemaakt in [**Openingspagina met formulier**](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target=&quot;_blank&quot;}.

1. Zoek en sleep de **Formulier wordt ingevuld** activeren op het canvas.

   ![](assets/email-auto-response-12.png)

1. Selecteren **Mijn formulier** in de vervolgkeuzelijst. Klik vervolgens op de knop **Stroom** tab.

   ![](assets/email-auto-response-13.png)

1. Sleep de **E-mail verzenden** stroomactie naar het linkercanvas.

   ![](assets/email-auto-response-14.png)

1. Selecteer uw **E-mail met automatische reactie**. Klik vervolgens op de knop **Schema** tab.

   ![](assets/email-auto-response-15.png)

1. Klikken **Bewerken**.

   ![](assets/email-auto-response-16.png)

1. Selecteren **Elke keer** en klik op **Opslaan**.

   ![](assets/email-auto-response-17.png)

1. Klikken **Activeren**.

   ![](assets/email-auto-response-18.png)

1. Klikken **Activeren** op het bevestigingsscherm.

   ![](assets/email-auto-response-19.png)

>[!NOTE]
>
>Zodra actief, zal deze campagne lopen telkens als een persoon het gespecificeerde formulier invult. De campagne blijft actief tot ze gedeactiveerd is.

## Stap 3: Het formulier invullen {#step-fill-out-the-form}

1. Selecteren **Mijn pagina** (dit is gemaakt in het dialoogvenster [Openingspagina met formulier](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target=&quot;_blank&quot;} quick win) en klik op **Voorvertoning**.

   ![](assets/email-auto-response-20.png)

   _De openingspagina voor gratis proefversie wordt geopend op een nieuw tabblad._

1. Vul het formulier in met uw voornaam, achternaam en e-mailadres en klik vervolgens op **Verzenden**.

   ![](assets/email-auto-response-21.png)

>[!NOTE]
>
>Gebruik uw werkelijke e-mailadres zodat u het e-mailbericht kunt ontvangen.

## Opdracht voltooid {#mission-complete}

Binnen een paar minuten ziet u het e-mailbericht voor automatische reacties in uw Postvak IN. Geweldig werk!

<br> 

[◄ Missie 3: Eenvoudige scores](/help/marketo/getting-started/quick-wins/simple-scoring.md)

[Missie 5: Een lijst met personen importeren ►](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md)
