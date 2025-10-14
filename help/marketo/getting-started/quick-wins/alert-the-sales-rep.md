---
unique-page-id: 2359424
description: Waarschuwing bij verkoper - Marketo-documenten - productdocumentatie
title: Waarschuwing voor verkoper
exl-id: 4ad7d7b8-ee1e-4605-b4e0-e72a7e573c05
feature: Getting Started
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '348'
ht-degree: 0%

---

# Waarschuwing voor verkoper {#alert-the-sales-rep}

## Mission: waarschuwen als iemand een formulier invult op uw website {#mission-alert-the-sales-rep-when-a-person-fills-out-a-form-on-your-web-site}

Als je automatisch e-mailberichten wilt verzenden naar verkopers, hoef je alleen maar een waarschuwingsbericht en een e-mailcampagne te sturen. Zo doe je het.

>[!PREREQUISITES]
>
>[&#x200B; het Bestaan Pagina met een Vorm &#x200B;](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target="_blank"}

## Stap 1: Een e-mail met een waarschuwing maken {#step-create-an-alert-email}

1. Ga naar het **[!UICONTROL Marketing Activities]** -gebied.

   ![](assets/alert-the-sales-rep-1.png)

1. Selecteer **Mijn Programma** dat u in de [&#x200B; het Bestaan Pagina met een Vorm &#x200B;](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target="_blank"} snel wint, toen onder **[!UICONTROL New]** klikt **[!UICONTROL New Local Asset]** creeerde.

   ![](assets/alert-the-sales-rep-2.png)

1. Klik op **[!UICONTROL Email]**.

   ![](assets/alert-the-sales-rep-3.png)

1. **Naam** e-mail &quot;Mijn e-mailalarm&quot;, selecteer een malplaatje en klik **[!UICONTROL Create]**.

   ![](assets/alert-the-sales-rep-4.png)

1. Ga **van Naam** in, **van E-mail**, **[!UICONTROL Reply-to]**, en **[!UICONTROL Subject]** dat u uw verkoopteam wilt zien.

   ![](assets/alert-the-sales-rep-5.png)

1. Dubbelklik om de e-mailtekst te bewerken.

   ![](assets/alert-the-sales-rep-6.png)

1. Typ de e-mailinhoud.

   ![](assets/alert-the-sales-rep-7.png)

1. Plaats uw curseur waar u de het contactinfo van de persoon wilt opnemen en **klikken Symbolisch** pictogram van het Tussenvoegsel.

   ![](assets/alert-the-sales-rep-8.png)

1. Zoek en selecteer de `{{SP_Send_Alert_Info}}` **[!UICONTROL Token]** en klik op **[!UICONTROL Insert]** .

   ![](assets/alert-the-sales-rep-9.png)

   >[!NOTE]
   >
   >{{SP_Send_Alert_Info}} is een speciale token voor e-mailmeldingen. Zie [&#x200B; Gebruik het Send Token van Info van de Waarschuwing &#x200B;](/help/marketo/product-docs/email-marketing/general/using-tokens/use-the-send-alert-info-token.md){target="_blank"}{target="_blank"} om meer te leren.

1. Klik op **[!UICONTROL Save]**.

   ![](assets/alert-the-sales-rep-10.png)

1. Klik op de vervolgkeuzelijst **[!UICONTROL Email Actions]** en selecteer **[!UICONTROL Approve and Close]** .

   ![](assets/alert-the-sales-rep-11.png)

## Stap 2: Een waarschuwingscampagne maken {#step-create-an-alert-trigger-campaign}

1. Selecteer **Mijn die Programma** eerder, dan onder **[!UICONTROL New]** wordt gecreeerd klikt **[!UICONTROL New Smart Campaign]**.

   ![](assets/alert-the-sales-rep-12.png)

1. **Naam** de campagne &quot;Mijn Waakzame Campagne&quot;en klik **[!UICONTROL Create]**.

   ![](assets/alert-the-sales-rep-13.png)

1. Zoek en sleep de trigger **[!UICONTROL Smart List]** onder het tabblad **[!UICONTROL Fills Out Form]** naar het canvas.

   ![](assets/alert-the-sales-rep-14.png)

1. Selecteer het formulier dat we eerder hebben gemaakt.

   ![](assets/alert-the-sales-rep-15.png)

1. Zoek onder het tabblad **[!UICONTROL Flow]** de **[!UICONTROL Send Alert]** -flowactie naar het canvas en sleep deze.

   ![](assets/alert-the-sales-rep-16.png)

1. Selecteer **[!UICONTROL My Alert Email]** die u eerder hebt gemaakt en laat **[!UICONTROL Send To]** as **[!UICONTROL Sales Owner]** staan.

   ![](assets/alert-the-sales-rep-17.png)

1. Typ uw e-mailadres in het veld **[!UICONTROL To Other Emails]** .

   ![](assets/alert-the-sales-rep-18.png)

1. Ga naar de tab **[!UICONTROL Schedule]** en klik op de knop **[!UICONTROL Activate]** .

   ![](assets/alert-the-sales-rep-19.png)

   >[!TIP]
   >
   >Stel **[!UICONTROL Qualification Rules]** in op **[!UICONTROL every time]** (door de slimme campagne te bewerken) zodat dezelfde persoon waarschuwingen meerdere keren kan activeren.

1. Klik op **[!UICONTROL Activate]** op het bevestigingsscherm.

   ![](assets/alert-the-sales-rep-20.png)

## Stap 3: Test het! {#step-test-it-out}

1. Selecteer de openingspagina en klik op **[!UICONTROL View Approved Page]** .

   ![](assets/alert-the-sales-21.png)

   >[!NOTE]
   >
   >Vergeet niet landingspagina&#39;s goed te keuren, ze gaan niet live tot ze goedgekeurd zijn.

1. Vul het formulier in en klik op **[!UICONTROL Submit]** .

   ![](assets/alert-the-sales-22.png)

1. Je ontvangt binnenkort je e-mail. Nadat u hebt gecontroleerd dat alles werkt zoals het hoort, verwijdert u uw e-mailadres uit de verzendwaarschuwingsstroom (zie stap 2.7 hierboven).

   >[!NOTE]
   >
   >Klik op de tab **[!UICONTROL Person Info]** in Marketo om de contactgegevens weer te geven.

## Opdracht voltooid! {#mission-complete}

<br> 

[◄ Opdracht 7: Een e-mail personaliseren](/help/marketo/getting-started/quick-wins/personalize-an-email.md)

[Mission 9: Update Person Data ►](/help/marketo/getting-started/quick-wins/update-person-data.md)
