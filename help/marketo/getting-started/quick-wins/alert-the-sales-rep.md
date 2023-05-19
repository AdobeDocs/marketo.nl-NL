---
unique-page-id: 2359424
description: Waarschuwing bij verkoper - Marketo-documenten - productdocumentatie
title: Waarschuwing voor verkoper
exl-id: 4ad7d7b8-ee1e-4605-b4e0-e72a7e573c05
source-git-commit: 80512816eaf0a70a3f10a50c34aeea14edd9046b
workflow-type: tm+mt
source-wordcount: '342'
ht-degree: 0%

---

# Waarschuwing voor verkoper {#alert-the-sales-rep}

## Opdracht: De verkoper waarschuwen wanneer iemand een formulier op uw website invult {#mission-alert-the-sales-rep-when-a-person-fills-out-a-form-on-your-web-site}

Als je automatisch e-mailberichten wilt verzenden naar verkopers, hoef je alleen maar een waarschuwingsbericht en een e-mailcampagne te sturen. Zo doe je het.

>[!PREREQUISITES]
>
>[Openingspagina met formulier](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target="_blank"}

## Stap 1: Een waarschuwings-e-mail maken {#step-create-an-alert-email}

1. Ga naar de **[!UICONTROL Marketing Activities]** gebied.

   ![](assets/alert-the-sales-rep-1.png)

1. Selecteren **Mijn programma** die u hebt gemaakt in het dialoogvenster [Openingspagina met formulier](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target="_blank"} quick win , then under **[!UICONTROL New]** klikken **[!UICONTROL New Local Asset]**.

   ![](assets/alert-the-sales-rep-2.png)

1. Klik op **[!UICONTROL Email]**.

   ![](assets/alert-the-sales-rep-3.png)

1. **Naam** Selecteer een sjabloon en klik op **[!UICONTROL Create]**.

   ![](assets/alert-the-sales-rep-4.png)

1. Voer de **Van naam**, **Van e-mail**, **[!UICONTROL Reply-to]**, en **[!UICONTROL Subject]** dat u uw verkoopteam wilt zien.

   ![](assets/alert-the-sales-rep-5.png)

1. Dubbelklik om de e-mailtekst te bewerken.

   ![](assets/alert-the-sales-rep-6.png)

1. Typ de e-mailinhoud.

   ![](assets/alert-the-sales-rep-7.png)

1. Plaats de cursor op de plaats waar u de contactgegevens van de persoon wilt invoegen en klik op de knop **Token invoegen** pictogram.

   ![](assets/alert-the-sales-rep-8.png)

1. Zoek en selecteer de `{{SP_Send_Alert_Info}}` **[!UICONTROL Token]** en klik op **[!UICONTROL Insert]**.

   ![](assets/alert-the-sales-rep-9.png)

   >[!NOTE]
   >
   >{{SP_Send_Alert_Info}} is een speciale token voor e-mailberichten met een waarschuwing. Zie [Het token voor waarschuwinggegevens verzenden gebruiken](/help/marketo/product-docs/email-marketing/general/using-tokens/use-the-send-alert-info-token.md){target="_blank"}{target="_blank"} voor meer informatie.

1. Klik op **[!UICONTROL Save]**.

   ![](assets/alert-the-sales-rep-10.png)

1. Klik op de knop **[!UICONTROL Email Actions]** vervolgkeuzelijst en selecteer **[!UICONTROL Approve and Close]**.

   ![](assets/alert-the-sales-rep-11.png)

## Stap 2: Een waarschuwingsactiecampagne maken {#step-create-an-alert-trigger-campaign}

1. Selecteren **Mijn programma** eerder gemaakt, dan onder **[!UICONTROL New]** klikken **[!UICONTROL New Smart Campaign]**.

   ![](assets/alert-the-sales-rep-12.png)

1. **Naam** de campagne &quot;My Alert Campaign&quot; en klik op **[!UICONTROL Create]**.

   ![](assets/alert-the-sales-rep-13.png)

1. Onder de **[!UICONTROL Smart List]** , zoekt en sleept u de **[!UICONTROL Fills Out Form]** activeren op het canvas.

   ![](assets/alert-the-sales-rep-14.png)

1. Selecteer het formulier dat we eerder hebben gemaakt.

   ![](assets/alert-the-sales-rep-15.png)

1. Onder de **[!UICONTROL Flow]** , zoekt en sleept u de **[!UICONTROL Send Alert]** stroomactie naar het canvas.

   ![](assets/alert-the-sales-rep-16.png)

1. Selecteren **[!UICONTROL My Alert Email]** eerder gemaakt en verlaat **[!UICONTROL Send To]** als **[!UICONTROL Sales Owner]**.

   ![](assets/alert-the-sales-rep-17.png)

1. Typ uw e-mailadres in het dialoogvenster **[!UICONTROL To Other Emails]** veld.

   ![](assets/alert-the-sales-rep-18.png)

1. Ga naar de **[!UICONTROL Schedule]** en klik op de knop **[!UICONTROL Activate]** knop.

   ![](assets/alert-the-sales-rep-19.png)

   >[!TIP]
   >
   >Stel de **[!UICONTROL Qualification Rules]** tot **[!UICONTROL every time]** (door de slimme campagne te bewerken) zodat dezelfde persoon waarschuwingen meerdere keren kan activeren.

1. Klikken **[!UICONTROL Activate]** op het bevestigingsscherm.

   ![](assets/alert-the-sales-rep-20.png)

## Stap 3: Test het! {#step-test-it-out}

1. Selecteer de openingspagina en klik op **[!UICONTROL View Approved Page]**.

   ![](assets/alert-the-sales-21.png)

   >[!NOTE]
   >
   >Vergeet niet landingspagina&#39;s goed te keuren. ze gaan niet live tot ze goedgekeurd zijn.

1. Het formulier invullen en klikken **[!UICONTROL Submit]**.

   ![](assets/alert-the-sales-22.png)

1. Je ontvangt binnenkort je e-mail. Nadat u hebt gecontroleerd dat alles werkt zoals het hoort, verwijdert u uw e-mailadres uit de verzendwaarschuwingsstroom (zie stap 2.7 hierboven).

   >[!NOTE]
   >
   >Klik op de knop **[!UICONTROL Person Info]** in Marketo om de contactgegevens te bekijken.

## Opdracht voltooid! {#mission-complete}

<br> 

[◄ Missie 7: Een e-mail aanpassen](/help/marketo/getting-started/quick-wins/personalize-an-email.md)

[Missie 9: Persoonlijke gegevens bijwerken ►](/help/marketo/getting-started/quick-wins/update-person-data.md)
