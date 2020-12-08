---
unique-page-id: 2359424
description: Waarschuwing bij verkoper - Marketo Docs - Productdocumentatie
title: Waarschuwing voor verkoper
translation-type: tm+mt
source-git-commit: 09dbd3a141fed0525aec8bf1ca6d141be2a6ce46
workflow-type: tm+mt
source-wordcount: '454'
ht-degree: 0%

---


# Waarschuwing voor verkoper {#alert-the-sales-rep}

## Opdracht: De verkoper waarschuwen wanneer iemand een formulier op uw website invult {#mission-alert-the-sales-rep-when-a-person-fills-out-a-form-on-your-web-site}

Als je automatisch e-mailberichten wilt verzenden naar verkopers, hoef je alleen maar een waarschuwingsbericht en een e-mailcampagne te sturen. Zo doe je het.

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

>[!NOTE]
>
>**Vereisten**
>
>* [Openingspagina met formulier](landing-page-with-a-form.md)

>



## Stap 1: Een waarschuwings-e-mail maken {#step-create-an-alert-email}

1. Ga naar het gebied **Marketingactiviteiten** .

   ![](assets/one-5.png)

1. Selecteer **Mijn programma** dat u op de [Openingspagina hebt gemaakt met een Form](landing-page-with-a-form.md) quick win, en klik vervolgens onder **Nieuw** op **Nieuw Lokaal element**.

   ![](assets/two-6.png)

1. Klik op **E-mail**.

   ![](assets/three-5.png)

1. **Geef** het e-mailbericht &quot;Mijn e-mailwaarschuwing&quot; een naam, selecteer een sjabloon en klik op **Maken**.

   ![](assets/four-4.png)

1. Ga **van Naam**, **van E-mail**, **antwoord-aan**, en **Onderwerp** in dat u uw verkoopteam wilt zien.

   ![](assets/five-5.png)

1. Dubbelklik om de e-mailtekst te bewerken.

   ![](assets/six-5.png)

1. Typ de e-mailinhoud.

   ![](assets/seven-6.png)

1. Plaats de cursor op de plaats waar u de contactgegevens van de persoon wilt invoegen en klik op het pictogram Token **** invoegen.

   ![](assets/eight-4.png)

1. Zoek en selecteer het `{{SP_Send_Alert_Info}}` token **en klik op** Invoegen ****.

   ![](assets/image2014-9-24-13-3a10-3a0.png)

   >[!NOTE]
   >
   >{SP_Send_Alert_Info} is een speciale token voor e-mailmeldingen. Zie [Gebruik het token](../../product-docs/email-marketing/general/using-tokens/use-the-send-alert-info-token.md) voor waarschuwinginfo verzenden voor meer informatie.

1. Klik op **Opslaan**.

   ![](assets/ten-5.png)

1. Sluit het tabblad/venster van de e-maileditor.

   ![](assets/eleven-5.png)

1. Klik onder **E-mailhandelingen** op **Goedkeuren**.

   ![](assets/twelve-4.png)

## Stap 2: Een waarschuwingsactiecampagne maken {#step-create-an-alert-trigger-campaign}

1. Selecteer **Mijn eerder gecreeerd Programma** , dan onder **Nieuw **klik **Nieuwe Slimme Campagne**.

   ![](assets/image2014-9-24-13-3a14-3a17.png)

1. **Geef** de campagne de naam &quot;Mijn waarschuwingscampagne&quot; en klik op **Maken**.

   ![](assets/image2014-9-24-13-3a14-3a28.png)

1. Zoek op het tabblad **Slimme lijst** de trigger Formulier **** invullen en sleep deze naar het canvas.

   ![](assets/image2014-9-24-13-3a14-3a43.png)

1. Selecteer het formulier dat we eerder hebben gemaakt.

   ![](assets/image2014-9-24-13-3a14-3a58.png)

1. Zoek en sleep onder het tabblad **Stroom** de actie **Waarschuwing** verzenden naar het canvas.

   ![](assets/image2014-9-24-13-3a15-3a10.png)

1. Selecteer **Mijn eerder gemaakte e-mail** met waarschuwing en laat **Verzenden naar** als **eigenaar** van de transactie.

   ![](assets/eighteen-1.png)

1. Typ uw e-mailadres in het veld **Naar andere e-mails** .

   ![](assets/nineteen-2.png)

1. Ga naar het tabblad **Schema** en klik op de knop **Activeren **.

   ![](assets/twenty-2.png)

   >[!TIP]
   >
   >
   >Plaats de Regels **van de** Kwalificatie aan **elke keer** (door de Slimme Campagne uit te geven) om de zelfde persoon toe te staan om alarm veelvoudige tijden teweeg te brengen.

1. Klik op **Activeren** op het bevestigingsscherm.

   ![](assets/twenty-one-1.png)

## Stap 3: Test het! {#step-test-it-out}

1. Selecteer de openingspagina en klik op Goedgekeurde pagina **** weergeven.

   ![](assets/image2014-9-24-13-3a17-3a8.png)

   >[!NOTE]
   >
   >**Herinnering**
   >
   >
   >Vergeet niet landingspagina&#39;s goed te keuren. ze gaan niet live tot ze goedgekeurd zijn.

1. Vul het formulier in en klik op **Verzenden**.

   ![](assets/image2014-9-24-13-3a17-3a41.png)

1. Je ontvangt binnenkort je e-mail. Nadat u hebt gecontroleerd dat alles werkt zoals het hoort, verwijdert u uw e-mailadres uit de verzendwaarschuwingsstroom (zie stap 2.7 hierboven).

   >[!NOTE]
   >
   >Klik op het tabblad **Personinfo** in Marketo om de contactinfo weer te geven.

## Opdracht voltooid! {#mission-complete}

<br> 

[◄ Missie 7: Een e-mailmissie](personalize-an-email.md) [9 personaliseren: Loodgegevens bijwerken ►](update-person-data.md)