---
unique-page-id: 7504923
description: Google AdWords-conversies in het inkomstenmodel instellen met een beheerdersaccount - Marketo Docs - Productdocumentatie
title: Conversies van Google AdWords in het inkomstenmodel instellen met een beheerdersaccount
exl-id: 8c9f50cf-0a8b-4f9a-a0bd-bb57eeac24cf
feature: Reporting, Revenue Cycle Analytics
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '448'
ht-degree: 0%

---

# Conversies van Google AdWords in het inkomstenmodel instellen met een beheerdersaccount {#set-google-adwords-conversions-in-the-revenue-model-with-a-manager-account}

Koppel uw Google AdWords-account aan Marketo om automatisch offline conversiegegevens te uploaden van Marketo naar Google AdWords. Dan, van AdWords UI, zult u gemakkelijk kunnen zien welke klikken in gekwalificeerde lood, kansen en nieuwe klanten (of welke opbrengststadia u wilt volgen) na u resulteerden [aangepaste kolommen toevoegen](https://support.google.com/adwords/answer/3073556) in AdWords.

Als u meerdere Google Adwords-accounts hebt, kunt u een [Google AdWords Manager-account](https://www.google.com/adwords/manager-accounts/) (voorheen bekend als Mijn Client Center) om deze te integreren met Marketo.

U kunt AdWords off-line omzettingen in kaart brengen aan één of meerdere stadia in een model van de Inkomsten. Er zijn twee manieren:

* Werkgebiedactie
* Toewijzing van adWoorden

>[!PREREQUISITES]
>
>[Google AdWords toevoegen als opstartservice met een beheerdersaccount](/help/marketo/product-docs/administration/additional-integrations/add-google-adwords-as-a-launchpoint-service-with-a-manager-account.md)

## Werkgebiedactie gebruiken {#use-stage-action}

Wijs een Advertentieconversie onder de Acties van het Stadium toe.

1. Selecteer de stap u aan een omzetting wilt in kaart brengen AdWords.

   ![](assets/image2015-2-26-16-3a40-3a2.png)

1. Onder de **Werkgebiedhandelingen** vervolgkeuzelijst, selecteren **Advertentieconversie instellen**.

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. Een **Advertentieconversie**.

   >[!NOTE]
   >
   >Voor elk onderliggend account kan een andere AdWords-conversie worden geselecteerd.

   ![](assets/image2015-3-27-17-3a16-3a37.png)

   Tip: Als u geen omzettingen AdWords hebt, creeer één door te klikken **+Nieuwe conversie**.

   ![](assets/image2015-3-27-17-3a18-3a58.png)

1. Klikken **Opslaan**.

   ![](assets/image2015-3-27-17-3a21-3a15.png)

1. Nadat u klaar bent met het in kaart brengen van al uw omzettingen AdWords in opbrengststadia, ga terug naar de summiere pagina. Selecteren **Modelhandelingen** en kiest u **Fases goedkeuren**.

   ![](assets/image2015-2-27-12-3a20-3a20.png)

## Pro-tip: Nieuwe conversie toevoegen {#pro-tip-add-a-new-conversion}

Pro tip! Er kan een nieuwe offline AdWords-conversie worden gemaakt vanuit Marketo.

>[!CAUTION]
>
>Voor nieuwe omzettingen die zijn gemaakt met Marketo is de instelling &quot;optimalisatie&quot; ingeschakeld. Dit betekent dat Advertentiestrategieën worden toegestaan om uw biedingen voor die omzettingen te optimaliseren. U kunt deze instelling wijzigen vanuit uw AdWords-account.

1. Onder de **Werkgebiedhandelingen** vervolgkeuzelijst, selecteren **Advertentieconversie instellen**.

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. Selecteren **Nieuwe conversie**.

   ![](assets/image2015-3-27-17-3a23-3a13.png)

1. Voer een **Conversienaam**. Klikken **Opslaan**.

   ![](assets/image2015-3-27-17-3a24-3a49.png)

   Uitstekend! Deze nieuwe conversie wordt weergegeven in uw AdWords-account.

## Toewijzing van adWoorden gebruiken {#use-adwords-mapping}

U kunt al uw modelstadia met uw Conversie AdWords in één plaats associëren gebruikend Toewijzingen AdWords.

1. Selecteren **Toewijzingen van adWoorden bewerken**.

   ![](assets/image2015-2-26-17-3a3-3a29.png)

1. Selecteer het gewenste **AdWords-account** en gewenst **Advertentieconversie** voor elk werkgebied dat u wilt bijhouden.

   ![](assets/image2015-3-27-17-3a30-3a15.png)

1. Nadat u de stadia hebt toegewezen, klikt u op **Opslaan**.

   ![](assets/image2015-3-27-17-3a30-3a48.png)

1. Nadat u klaar bent met het in kaart brengen van al uw omzettingen AdWords in opbrengststadia, ga terug naar de summiere pagina. Selecteren **Modelhandelingen** en kiest u **Fases goedkeuren**.

   ![](assets/image2015-2-27-12-3a20-3a20.png)

Als u de gegevens van de offline conversie wilt weergeven, moet u zich aanmelden bij uw AdWords-account. We raden je aan hun [Functie Aangepaste kolommen](https://support.google.com/adwords/answer/3073556) om conversietelling te maken voor elke offline conversie die u uit Marketo importeert.
