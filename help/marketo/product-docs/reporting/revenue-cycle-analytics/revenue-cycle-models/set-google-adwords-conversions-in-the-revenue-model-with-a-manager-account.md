---
unique-page-id: 7504923
description: Google AdWords-conversies in het inkomstenmodel instellen met een beheerdersaccount - Marketo Docs - Productdocumentatie
title: Google AdWords-conversies in het inkomstenmodel instellen met een beheerdersaccount
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '448'
ht-degree: 0%

---


# Google AdWords-conversies in het inkomstenmodel instellen met een beheerdersaccount {#set-google-adwords-conversions-in-the-revenue-model-with-a-manager-account}

Koppel uw Google AdWords-account aan Marketo om offline conversiegegevens van Marketo automatisch te uploaden naar Google AdWords. Dan, van AdWords UI, zult u gemakkelijk kunnen zien welke klikken in gekwalificeerde lood, kansen en nieuwe klanten (of welke omzetstadia resulteerden u wilt volgen) nadat u douanekolommen [in AdWords](https://support.google.com/adwords/answer/3073556) toevoegt.

Als u meerdere Google Adwords-accounts hebt, kunt u deze integreren met Marketo met een [Google AdWords Manager-account](https://www.google.com/adwords/manager-accounts/) (voorheen Mijn Client Center genoemd).

U kunt AdWords off-line omzettingen in kaart brengen aan één of meerdere stadia in een model van de Inkomsten. Er zijn twee manieren:

* Werkgebiedactie
* Toewijzing van adWoorden

>[!PREREQUISITES]
>
>* [Google AdWords toevoegen als opstartservice met een beheerdersaccount](../../../../product-docs/administration/additional-integrations/add-google-adwords-as-a-launchpoint-service-with-a-manager-account.md)

>



## Werkgebiedactie gebruiken {#use-stage-action}

Wijs een Advertentieconversie onder de Acties van het Stadium toe.

1. Selecteer de stap u aan een omzetting wilt in kaart brengen AdWords.

   ![](assets/image2015-2-26-16-3a40-3a2.png)

1. Selecteer onder het keuzemenu **Werkgebiedhandelingen** de optie **Advertentieconversie** instellen.

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. Stel een **ADW-conversie** in.

   >[!NOTE]
   >
   >Voor elk onderliggend account kan een andere AdWords-conversie worden geselecteerd.

   ![](assets/image2015-3-27-17-3a16-3a37.png)

   Tip: Als u geen omzettingen AdWords hebt, creeer één door **+Nieuwe Omzetting** te klikken.

   ![](assets/image2015-3-27-17-3a18-3a58.png)

1. Klik op **Opslaan**.

   ![](assets/image2015-3-27-17-3a21-3a15.png)

1. Nadat u klaar bent met het in kaart brengen van al uw omzettingen AdWords in opbrengststadia, ga terug naar de summiere pagina. Selecteer **Modelhandelingen** en kies **Fases** goedkeuren.

   ![](assets/image2015-2-27-12-3a20-3a20.png)

## Pro-tip: Nieuwe conversie toevoegen {#pro-tip-add-a-new-conversion}

Pro tip! Van Marketo kan een nieuwe offline conversie van AdWords worden gemaakt.

>[!CAUTION]
>
>Nieuwe omzettingen die zijn gemaakt met Marketo hebben de instelling voor optimalisatie ingeschakeld. Dit betekent dat Advertentiestrategieën worden toegestaan om uw biedingen voor die omzettingen te optimaliseren. U kunt deze instelling wijzigen vanuit uw AdWords-account.

1. Selecteer onder het keuzemenu **Werkgebiedhandelingen** de optie **Advertentieconversie** instellen.

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. Selecteer **Nieuwe omzetting**.

   ** ![](assets/image2015-3-27-17-3a23-3a13.png)

   **

1. Voer een **conversienaam** in. Klik op **Opslaan**.

   ![](assets/image2015-3-27-17-3a24-3a49.png)

   Uitstekend! Deze nieuwe conversie wordt weergegeven in uw AdWords-account.

## Toewijzing van adWoorden gebruiken {#use-adwords-mapping}

U kunt al uw modelstadia met uw Conversie AdWords in één plaats associëren gebruikend Toewijzingen AdWords.

1. Selecteer Toewijzingen van **woorden bewerken**.

   ![](assets/image2015-2-26-17-3a3-3a29.png)

1. Selecteer de gewenste **Advertentiewoordenrekening** en de gewenste **Conversie** AdWords voor elk stadium dat u wilt volgen.

   ![](assets/image2015-3-27-17-3a30-3a15.png)

1. Nadat u de stappen hebt toegewezen, klikt u op **Opslaan**.

   ![](assets/image2015-3-27-17-3a30-3a48.png)

1. Nadat u klaar bent met het in kaart brengen van al uw omzettingen AdWords in opbrengststadia, ga terug naar de summiere pagina. Selecteer **Modelhandelingen** en kies **Fases** goedkeuren.

   ![](assets/image2015-2-27-12-3a20-3a20.png)

Als u de gegevens van de offline conversie wilt weergeven, moet u zich aanmelden bij uw AdWords-account. We raden u aan de functie [](https://support.google.com/adwords/answer/3073556) Aangepaste kolommen te gebruiken om conversietellingkolommen te maken voor elke offline conversie die u importeert van Marketo.
