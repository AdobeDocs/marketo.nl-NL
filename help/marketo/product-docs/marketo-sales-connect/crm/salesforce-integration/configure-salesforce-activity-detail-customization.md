---
description: Aanpassing van Salesforce Activity Detail - Marketo-documenten - Productdocumentatie configureren
title: Aanpassing van Salesforce-activiteitsgegevens configureren
exl-id: 4b20ca29-18d6-4026-9bf9-77656ad1442d
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '667'
ht-degree: 1%

---

# [!DNL Salesforce] Aanpassing activiteitendetails configureren {#configure-salesforce-activity-detail-customization}

>[!PREREQUISITES]
>
>* [!DNL Salesforce] en [!DNL Marketo Sales Connect] [ moeten worden verbonden ](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/connect-your-sales-connect-account-to-salesforce.md)
>* Het registreren van e-mailactiviteit via API [ moet worden toegelaten ](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/salesforce-sync-settings.md)

Met Aanpassing van activiteitendetails kunnen beheerders de informatie configureren die wordt aangemeld bij het veld Salesforce Task - Subject wanneer een [!DNL Sales Connect] activiteit/herinneringstaak wordt gesynchroniseerd met Salesforce.

>[!NOTE]
>
>* Updates die in [!DNL Sales Connect] van een herinneringstaak aan het onderwerpveld van een [!DNL Salesforce] -taak worden aangebracht, worden weergegeven in het onderwerpveld van die `{{activity_subject}}` -taak als u het dynamische veld in de aanpassing van het Activiteitendetail gebruikt.
>* Regeleinden worden niet ondersteund wanneer gegevens worden geregistreerd naar het onderwerpveld van [!DNL Salesforce] . Om het even welke lijnonderbrekingen in de redacteur van de Aanpassing van het Detail van de Activiteit zullen worden verwijderd wanneer een onderwerp van de verkooptaak wordt bijgewerkt.

![](assets/configure-salesforce-activity-detail-customization-1.png)

![](assets/configure-salesforce-activity-detail-customization-2.png)

<table>
 <tr>
  <td><strong>1</td>
  <td>Taak InMail-herinnering</td>
 </tr>
 <tr>
  <td><strong>2</td>
  <td>E-mailactiviteit</td>
 </tr>
 <tr>
  <td><strong>3</td>
  <td>Oproepactiviteit</td>
 </tr>
</table>

De functie kan worden gebruikt om de volgende voordelen te ontgrendelen:

* Door aan te passen welke informatie zichtbaar is op het onderwerpveld, kunnen de activiteitsgegevens gemakkelijk worden gescand voor verkoop in Salesforce.
* Beheerders kunnen het onderwerpveld labelen met een unieke id, zoals &quot;Mkto_sales&quot;. Activiteiten van Sales Connect kunnen dus gemakkelijk worden geïdentificeerd en onderscheiden van andere e-mailactiviteiten, callactiviteiten en taken.
* Verminder de behoefte aan de gebieden van de douaneactiviteit. Salesforce past limieten toe op het aantal velden voor aangepaste activiteiten, waardoor kan worden beperkt welke gegevens beschikbaar zijn voor gebruik in rapporten. Als u dynamische velden voor activiteiten gebruikt om toetsgegevens toe te voegen aan de onderwerpregel, kunt u het aantal aangepaste activiteitsvelden verminderen dat u in uw Salesforce-instantie moet maken.
* Het werkgebied en de taken volgen een consistent patroon dat is gedefinieerd door de Sales Connect Admin.

>[!NOTE]
>
>Als u e-mailantwoorden registreert als activiteiten aan [!DNL Salesforce] , worden de instellingen voor [!DNL Salesforce] Aanpassing activiteitendetails niet gebruikt. In plaats daarvan registreert u zich als &quot;Reply: Email Subject&quot;.

## Ondersteunde dynamische velden voor activiteiten {#activity-dynamic-fields-supported}

De dynamische de verwijzingsinformatie van Gebieden van de activiteit over uw verkoopactiviteiten om gegevens te bevolken. Vandaag de dag kunnen ze worden gebruikt met [!DNL Salesforce] Activity Detail Customization.

>[!NOTE]
>
>Als er geen waarde is om het dynamische veld voor een specifieke activiteit/taak te vullen, worden er geen gegevens voor dat dynamische veld gevuld wanneer het veld [!DNL Salesforce] Taak - Onderwerp wordt bijgewerkt.

<table>
 <tr>
  <th>Veld</th>
  <th>Beschrijving</th>
 </tr>
 <tr>
  <td>{{activity_type}}</td>
  <td>Het taaktype wordt ingevuld als E-mail, Bel, InMail of Aangepast.</td>
 </tr>
 <tr>
  <td>{{activity_subject}}</td>
  <td><p>Zal het onderwerp van de taak vullen.</p>
      <p>In het geval van een e-mail wordt de onderwerpregel van de e-mail ingevuld.</p>
      <p>In het geval van vraag, inMail, of douane, zal het een waarde bevolken als er een herinneringstaak was die met een waarde op het de taaknaam/onderwerpgebied werd gecreeerd.</p></td>
 </tr>
 <tr>
  <td>{{sales_campaign_name}}</td>
  <td>Als de activiteit van een verkoopcampagne werd geïnitieerd, zal het de naam van de verkoopcampagne bevolken.</td>
 </tr>
 <tr>
  <td>{{sales_campaign_day}}</td>
  <td>Als de activiteit van een verkoopcampagne werd geïnitieerd, zal het het aantal van de de verkoopcampagne dag van deze activiteit bevolken op.</td>
 </tr>
 <tr>
  <td>{{sales_campaign_step}}</td>
  <td>Als de activiteit van een verkoopcampagne werd geïnitieerd, zal het het stapaantal binnen de dag van de verkoopcampagne bevolken deze activiteit op voorkwam.</td>
 </tr>
 <tr>
  <td>{{call_outcome}}</td>
  <td>Als de activiteit een vraag is en een vraagresultaat wordt geselecteerd, zal dit de waarde van het vraagresultaat bevolken.</td>
 </tr>
 <tr>
  <td>{{call_reason}}</td>
  <td>Als de activiteit een vraag is en een vraagreden wordt geselecteerd, zal dit de waarde van de vraagreden bevolken.</td>
 </tr>
</table>

## Aanpassing van Salesforce-activiteitsgegevens configureren {#configuring-salesforce-activity-detail-customization}

>[!NOTE]
>
>**vereiste toestemmingen Admin.**

Wanneer het vormen van uw activiteitendetails, overweeg welke gegevens voor verkoop het meest relevant zouden zijn wanneer het herzien van taakgeschiedenis in [!DNL Salesforce].

1. Klik op het tandwielpictogram en selecteer **[!UICONTROL Settings]** .

   ![](assets/configure-salesforce-activity-detail-customization-3.png)

1. Klik op **[!UICONTROL Salesforce]**.

   ![](assets/configure-salesforce-activity-detail-customization-4.png)

1. Klik op **[!UICONTROL Sync Settings]**.

   ![](assets/configure-salesforce-activity-detail-customization-5.png)

1. Voeg in de redacteur van de Aanpassing van de Details van de Activiteit om het even welke vrije tekst toe u wilt. De tekst die u toevoegt, is niet dynamisch en blijft ongewijzigd voor het onderwerpveld van alle taken die zijn gesynchroniseerd met [!DNL Salesforce] .

   ![](assets/configure-salesforce-activity-detail-customization-6.png)

   >[!TIP]
   >
   >Hoewel niet vereist, kan het voor sommige mensen gemakkelijker worden om toegevoegde tekst tussen de gegevens te merken wanneer het aan een onderwerpgebied in Salesforce wordt bevolkt. Voorbeeld: `[Sales Connect] - {{Activity_type}}`

1. Voeg aanvullende dynamische velden toe die u wilt toevoegen door op de knop **[!UICONTROL Add Dynamic Field]** te klikken.

   ![](assets/configure-salesforce-activity-detail-customization-7.png)

1. Selecteer de gewenste dynamische velden.

   ![](assets/configure-salesforce-activity-detail-customization-8.png)

1. Klik op **[!UICONTROL Save]**.

   ![](assets/configure-salesforce-activity-detail-customization-9.png)

>[!NOTE]
>
>[!DNL Salesforce] past een limiet van 255 tekens toe. Als uw activiteitendetails dit overschrijden, wordt het afgebroken om ervoor te zorgen dat de informatie wordt opgeslagen in het onderwerpveld [!DNL Salesforce] .

>[!MORELIKETHIS]
>
>* [ de Montages van de Synchronisatie ](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/salesforce-sync-settings.md)
>* [ de Synchronisatie van de Taak van de herinnering met  [!DNL Salesforce]](/help/marketo/product-docs/marketo-sales-connect/tasks/reminder-task-sync-with-salesforce.md)
>* [[!DNL Sales Connect]  Aanpassing voor CRM ](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-customization/sales-connect-customizations-for-crm.md)
