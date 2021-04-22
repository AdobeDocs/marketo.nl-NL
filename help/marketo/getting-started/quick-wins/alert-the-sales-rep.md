---
unique-page-id: 2359424
description: Waarschuwing bij verkoper - Marketo-documenten - productdocumentatie
title: Waarschuwing voor verkoper
exl-id: 4ad7d7b8-ee1e-4605-b4e0-e72a7e573c05
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '401'
ht-degree: 0%

---

# De verkoopvertegenwoordiger waarschuwen {#alert-the-sales-rep}

## Opdracht: De verkoper waarschuwen wanneer iemand een formulier op uw website invult {#mission-alert-the-sales-rep-when-a-person-fills-out-a-form-on-your-web-site}

Als je automatisch e-mailberichten wilt verzenden naar verkopers, hoef je alleen maar een waarschuwingsbericht en een e-mailcampagne te sturen. Zo doe je het.

>[!PREREQUISITES]
>
>[Openingspagina met formulier](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md)

## Stap 1: Een waarschuwingsbericht maken {#step-create-an-alert-email}

1. Ga naar **Marketing Activities** gebied.

   ![](assets/one-5.png)

1. Selecteer **Mijn programma** dat u in [Landing Page met een Vorm](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md) snel win, dan onder **Nieuw** klikt **Nieuw Lokaal Activum**.

   ![](assets/two-6.png)

1. Klik **E-mail**.

   ![](assets/three-5.png)

1. **Geef** het e-mailbericht Mijn e-mailwaarschuwing een naam, selecteer een sjabloon en klik op  **Maken**.

   ![](assets/four-4.png)

1. Voer **Van naam**, **Van e-mail**, **Reactie-aan**, en **Onderwerp** in dat u uw verkoopteam wilt zien.

   ![](assets/five-5.png)

1. Dubbelklik om de e-mailtekst te bewerken.

   ![](assets/six-5.png)

1. Typ de e-mailinhoud.

   ![](assets/seven-6.png)

1. Plaats de cursor op de plaats waar u de contactgegevens van de persoon wilt invoegen en klik op het pictogram **Token invoegen**.

   ![](assets/eight-4.png)

1. Zoek en selecteer `{{SP_Send_Alert_Info}}` **Token** en klik **Invoegen**.

   ![](assets/image2014-9-24-13-3a10-3a0.png)

   >[!NOTE]
   >
   >{SP_Send_Alert_Info} is een speciale token voor e-mailmeldingen. Zie [Gebruik het Send Token van Info van het Alarm](/help/marketo/product-docs/email-marketing/general/using-tokens/use-the-send-alert-info-token.md) om meer te leren.

1. Klik **Opslaan**.

   ![](assets/ten-5.png)

1. Sluit het tabblad/venster van de e-maileditor.

   ![](assets/eleven-5.png)

1. Klik onder **E-mailhandelingen** op **Goedkeuren**.

   ![](assets/twelve-4.png)

## Stap 2: Een waarschuwingsactiecampagne {#step-create-an-alert-trigger-campaign} maken

1. Selecteer **Mijn eerder gemaakte Programma**, dan onder **Nieuw** klik **Nieuwe Slimme Campagne**.

   ![](assets/image2014-9-24-13-3a14-3a17.png)

1. **Geef** de campagne &quot;Mijn waarschuwingscampagne&quot; een naam en klik op  **Maken**.

   ![](assets/image2014-9-24-13-3a14-3a28.png)

1. Zoek en sleep onder het tabblad **Slimme lijst** de trigger **Formulier invullen** naar het canvas.

   ![](assets/image2014-9-24-13-3a14-3a43.png)

1. Selecteer het formulier dat we eerder hebben gemaakt.

   ![](assets/image2014-9-24-13-3a14-3a58.png)

1. Zoek en sleep onder het tabblad **Stroom** de stroomactie **Waarschuwing** verzenden naar het canvas.

   ![](assets/image2014-9-24-13-3a15-3a10.png)

1. Selecteer **Mijn eerder gemaakte e-mail** en laat **Verzenden naar** als **Eigenaar van verkoop** staan.

   ![](assets/eighteen-1.png)

1. Typ uw e-mailadres in het veld **Naar andere e-mails**.

   ![](assets/nineteen-2.png)

1. Ga naar het **Schema** lusje en klik **Activate** knoop.

   ![](assets/twenty-2.png)

   >[!TIP]
   >
   >Plaats **Kwalificatieregels** aan **telkens** (door de Slimme Campagne uit te geven) om de zelfde persoon toe te staan om alarm veelvoudige tijden teweeg te brengen.

1. Klik **Activeer** op het bevestigingsscherm.

   ![](assets/twenty-one-1.png)

## Stap 3: Test het! {#step-test-it-out}

1. Selecteer de openingspagina en klik op **Goedgekeurde pagina weergeven**.

   ![](assets/image2014-9-24-13-3a17-3a8.png)

   >[!NOTE]
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

[◄ Missie 7: Een e-mail aanpassen](personalize-an-email.md)

[Missie 9: Loodgegevens bijwerken ►](update-person-data.md)
