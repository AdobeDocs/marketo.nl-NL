---
description: Aanpassing van Salesforce Activity Detail - Marketo-documenten - Productdocumentatie configureren
title: Aanpassing Salesforce Activity Detail configureren
exl-id: 534ebdb5-7a5b-48eb-98f7-2d05a9eae8e8
source-git-commit: 02354356949aef7aa8836d4753ec538b7819a65a
workflow-type: tm+mt
source-wordcount: '709'
ht-degree: 0%

---

# Aanpassing Salesforce Activity Detail configureren {#configure-salesforce-activity-detail-customization}

>[!PREREQUISITES]
>
>* Handelingen voor Salesforce en Sales Insight [moet zijn aangesloten](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/connect-your-sales-insight-actions-account-to-salesforce.md)
>* E-mailactiviteit registreren via API [moet worden ingeschakeld](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/sync-sales-activities-to-salesforce.md)

De Aanpassing van het Detail van de activiteit staat Admins toe om de informatie te vormen die aan het Taak Salesforce - Onderwerp Gebied zal registreren, wanneer een de activiteit/de herinneringstaak van het Inzicht van de Verkoop aan Salesforce wordt gesynchroniseerd.

>[!NOTE]
>
>* De updates aan het onderwerpgebied in de Acties van het Inzicht van de Verkoop van een herinneringstaak worden gemaakt zullen in het overeenkomstige het onderwerpgebied van de taak van Salesforce worden weerspiegeld, als u gebruikt `{{activity_subject}}` dynamisch veld in de aanpassing van het activiteitsgegeven.
>* Regeleinden worden niet ondersteund wanneer gegevens worden geregistreerd naar het onderwerpveld Salesforce. Om het even welke lijnonderbrekingen in de redacteur van de Aanpassing van het Detail van de Activiteit zullen worden verwijderd wanneer een onderwerp van de verkooptaak wordt bijgewerkt.

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

* Door aan te passen welke informatie zichtbaar is over het onderwerpveld, zijn de activiteitsdetails gemakkelijk te scannen voor verkoop in Salesforce.
* Beheerders kunnen het onderwerpveld labelen met een unieke id, zoals &quot;Mkto_sales&quot;, zodat activiteiten van Handelingen van het Inzicht van de Verkoop gemakkelijk kunnen worden geïdentificeerd en onderscheiden van andere e-mailactiviteiten, callactiviteiten en taken.
* Verminder de behoefte aan de gebieden van de douaneactiviteit. Salesforce past limieten toe op het aantal velden voor aangepaste activiteiten, waardoor kan worden beperkt welke gegevens beschikbaar zijn voor gebruik in rapporten. Als u dynamische velden voor activiteit gebruikt om toetsgegevens toe te voegen aan de onderwerpregel, kunt u het aantal velden voor aangepaste activiteit dat u in uw Salesforce-instantie moet maken, verminderen.
* Het onderwerpgebied van activiteiten en taken zal een verenigbaar patroon volgen dat door Admin van de Acties van het Inzicht van de Verkoop wordt bepaald.

>[!NOTE]
>
>Als u e-mailantwoorden als activiteiten aan Salesforce registreert, zullen zij niet de montages van de Aanpassing van het Detail van de Activiteit Salesforce gebruiken. In plaats daarvan logt u dan af op &quot;Reageren: E-mailonderwerp.&quot;

## Ondersteunde dynamische velden voor activiteiten {#activity-dynamic-fields-supported}

De dynamische de verwijzingsinformatie van Gebieden van de activiteit over uw verkoopactiviteiten om gegevens te bevolken. Vandaag, kunnen zij met de Aanpassing van het Detail van de Activiteit van Salesforce worden gebruikt.

>[!NOTE]
>
>Als er geen waarde is om het dynamische gebied voor een specifieke activiteit/een taak te bevolken, zal het geen gegevens voor dat dynamische gebied bevolken wanneer Salesforce Taak - Onderwerp Gebied wordt bijgewerkt.

<table>
 <tr>
  <th>Veld</th>
  <th>Beschrijving</th>
 </tr>
 <tr>
  <td>{{activity_type}}</td>
  <td>Hiermee vult u het taaktype in als E-mail, Bel, InMail of Aangepast.</td>
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

## Aanpassing Salesforce Activity Detail configureren {#configuring-salesforce-activity-detail-customization}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist.**

Wanneer het vormen van uw activiteitendetails, overweeg welke gegevens voor verkoop het meest relevant zouden zijn wanneer het herzien van taakgeschiedenis in Salesforce.

1. Klik op het tandwielpictogram en selecteer **Instellingen**.

   ![](assets/configure-salesforce-activity-detail-customization-3.png)

1. Klikken **Salesforce**.

   ![](assets/configure-salesforce-activity-detail-customization-4.png)

1. Klikken **Instellingen synchroniseren**.

   ![](assets/configure-salesforce-activity-detail-customization-5.png)

1. Voeg in de redacteur van de Aanpassing van de Details van de Activiteit om het even welke vrije tekst toe u wilt. De tekst die u toevoegt, is niet dynamisch en blijft ongewijzigd voor het onderwerpveld van alle taken die zijn gesynchroniseerd met Salesforce.

   ![](assets/configure-salesforce-activity-detail-customization-6.png)

   >[!TIP]
   >
   >Hoewel niet vereist, kan het voor sommige mensen gemakkelijker worden om toegevoegde tekst tussen de gegevens te merken wanneer het aan een onderwerpgebied in Salesforce wordt bevolkt. Voorbeeld: `[Sales Insight Actions] - {{Activity_type}}`

1. Voeg aanvullende dynamische velden toe die u wilt toevoegen door op de knop **Dynamisch veld toevoegen** knop.

   ![](assets/configure-salesforce-activity-detail-customization-7.png)

1. Selecteer de gewenste dynamische velden.

   ![](assets/configure-salesforce-activity-detail-customization-8.png)

1. Klikken **Opslaan**.

   ![](assets/configure-salesforce-activity-detail-customization-9.png)

>[!NOTE]
>
>Salesforce past een limiet van 255 tekens toe. Als uw activiteitendetail dat overschrijdt, zal het worden beknot om de informatie te verzekeren op het Salesforce onderwerpgebied wordt opgeslagen.

>[!MORELIKETHIS]
>
>* [Verkoopactiviteiten synchroniseren met Salesforce](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/sync-sales-activities-to-salesforce.md)
>* [Herinnering taaksynchronisatie met Salesforce](/help/marketo/product-docs/marketo-sales-insight/actions/tasks/reminder-task-sync-with-salesforce.md)
