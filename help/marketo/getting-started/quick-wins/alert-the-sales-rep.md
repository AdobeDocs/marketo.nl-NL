---
unique-page-id: 2359424
description: Waarschuwing bij verkoper - Marketo-documenten - productdocumentatie
title: Waarschuwing voor verkoper
exl-id: 4ad7d7b8-ee1e-4605-b4e0-e72a7e573c05
source-git-commit: 0da33dfa840dd1e5a5618fcd762b482f7a2e0789
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Waarschuwing voor verkoper {#alert-the-sales-rep}

## Opdracht: De verkoper waarschuwen wanneer iemand een formulier op uw website invult {#mission-alert-the-sales-rep-when-a-person-fills-out-a-form-on-your-web-site}

Als je automatisch e-mailberichten wilt verzenden naar verkopers, hoef je alleen maar een waarschuwingsbericht en een e-mailcampagne te sturen. Zo doe je het.

>[!PREREQUISITES]
>
>[Openingspagina met formulier](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target=&quot;_blank&quot;}

## Stap 1: Een waarschuwings-e-mail maken {#step-create-an-alert-email}

1. Ga naar de **Marketingactiviteiten** gebied.

   ![](assets/one-5.png)

1. Selecteren **Mijn programma** die u hebt gemaakt in het dialoogvenster [Openingspagina met formulier](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target=&quot;_blank&quot;} quick win, then under **Nieuw** klikken **Nieuw lokaal element**.

   ![](assets/two-6.png)

1. Klikken **E-mail**.

   ![](assets/three-5.png)

1. **Naam** Selecteer een sjabloon en klik op **Maken**.

   ![](assets/four-4.png)

1. Voer de **Van naam**, **Van e-mail**, **Antwoord aan**, en **Onderwerp** dat u uw verkoopteam wilt zien.

   ![](assets/five-5.png)

1. Dubbelklik om de e-mailtekst te bewerken.

   ![](assets/six-5.png)

1. Typ de e-mailinhoud.

   ![](assets/seven-6.png)

1. Plaats de cursor op de plaats waar u de contactgegevens van de persoon wilt invoegen en klik op de knop **Token invoegen** pictogram.

   ![](assets/eight-4.png)

1. Zoek en selecteer de `{{SP_Send_Alert_Info}}` **Token** en klik op **Invoegen**.

   ![](assets/image2014-9-24-13-3a10-3a0.png)

   >[!NOTE]
   >
   >{{SP_Send_Alert_Info}} is een speciale token voor e-mailberichten met een waarschuwing. Zie [Het token voor waarschuwinggegevens verzenden gebruiken](/help/marketo/product-docs/email-marketing/general/using-tokens/use-the-send-alert-info-token.md){target=&quot;_blank&quot;}{target=&quot;_blank&quot;} voor meer informatie.

1. Klikken **Opslaan**.

   ![](assets/ten-5.png)

1. Sluit het tabblad/venster van de e-maileditor.

   ![](assets/eleven-5.png)

1. Onder **E-mailhandelingen** klikken **Goedkeuren**.

   ![](assets/twelve-4.png)

## Stap 2: Een waarschuwingsactiecampagne maken {#step-create-an-alert-trigger-campaign}

1. Selecteren **Mijn programma** eerder gemaakt, dan onder **Nieuw** klikken **Nieuwe slimme campagne**.

   ![](assets/image2014-9-24-13-3a14-3a17.png)

1. **Naam** de campagne &quot;My Alert Campaign&quot; en klik op **Maken**.

   ![](assets/image2014-9-24-13-3a14-3a28.png)

1. Onder de **Slimme lijst** , zoekt en sleept u de **Formulier wordt ingevuld** activeren op het canvas.

   ![](assets/image2014-9-24-13-3a14-3a43.png)

1. Selecteer het formulier dat we eerder hebben gemaakt.

   ![](assets/image2014-9-24-13-3a14-3a58.png)

1. Onder de **Stroom** , zoekt en sleept u de **Waarschuwing verzenden** stroomactie naar het canvas.

   ![](assets/image2014-9-24-13-3a15-3a10.png)

1. Selecteren **Mijn e-mail met waarschuwing** eerder gemaakt en verlaat **Verzenden naar** als **Verkoopeigenaar**.

   ![](assets/eighteen-1.png)

1. Typ uw e-mailadres in het dialoogvenster **Naar andere e-mails** veld.

   ![](assets/nineteen-2.png)

1. Ga naar de **Schema** en klik op de knop **Activeren** knop.

   ![](assets/twenty-2.png)

   >[!TIP]
   >
   >Stel de **Kwalificatieregels** tot **elke keer** (door de slimme campagne te bewerken) zodat dezelfde persoon waarschuwingen meerdere keren kan activeren.

1. Klikken **Activeren** op het bevestigingsscherm.

   ![](assets/twenty-one-1.png)

## Stap 3: Test het! {#step-test-it-out}

1. Selecteer de openingspagina en klik op **Goedgekeurde pagina weergeven**.

   ![](assets/image2014-9-24-13-3a17-3a8.png)

   >[!NOTE]
   >
   >Vergeet niet landingspagina&#39;s goed te keuren. ze gaan niet live tot ze goedgekeurd zijn.

1. Het formulier invullen en klikken **Verzenden**.

   ![](assets/image2014-9-24-13-3a17-3a41.png)

1. Je ontvangt binnenkort je e-mail. Nadat u hebt gecontroleerd dat alles werkt zoals het hoort, verwijdert u uw e-mailadres uit de verzendwaarschuwingsstroom (zie stap 2.7 hierboven).

   >[!NOTE]
   >
   >Klik op de knop **Persoonsgegevens** in Marketo om de contactgegevens te bekijken.

## Opdracht voltooid! {#mission-complete}

<br> 

[◄ Missie 7: Een e-mail aanpassen](/help/marketo/getting-started/quick-wins/personalize-an-email.md)

[Missie 9: Persoonlijke gegevens bijwerken ►](/help/marketo/getting-started/quick-wins/update-person-data.md)
