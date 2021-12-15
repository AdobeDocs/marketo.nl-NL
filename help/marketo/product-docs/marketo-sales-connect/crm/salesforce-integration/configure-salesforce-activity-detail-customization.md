---
description: Aanpassing van Salesforce Activity Detail - Marketo-documenten - Productdocumentatie configureren
title: Aanpassing Salesforce Activity Detail configureren
hide: true
hidefromtoc: true
exl-id: 4b20ca29-18d6-4026-9bf9-77656ad1442d
source-git-commit: 87f43fb58b5739c0465a1a74fb60cdf5c5f6b759
workflow-type: tm+mt
source-wordcount: '573'
ht-degree: 0%

---

# Aanpassing Salesforce Activity Detail configureren {#configure-salesforce-activity-detail-customization}

Aanpassing van het Detail van de activiteit staat beheerders toe om de informatie te vormen die aan het Salesforce Taak - Onderwerp gebied zal registreren, wanneer een de activiteit/herinneringstaak van de Verkoop wordt gesynchroniseerd aan Salesforce.

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
* Beheerders kunnen het onderwerpveld labelen met een unieke id, zoals &quot;Mkto_sales&quot;. Activiteiten van Sales Connect kunnen dus gemakkelijk worden geïdentificeerd en onderscheiden van andere e-mailactiviteiten, callactiviteiten en taken.
* Verminder de behoefte aan de gebieden van de douaneactiviteit. Salesforce past limieten toe op het aantal velden voor aangepaste activiteiten, waardoor kan worden beperkt welke gegevens beschikbaar zijn voor gebruik in rapporten. Als u dynamische velden voor activiteit gebruikt om toetsgegevens toe te voegen aan de onderwerpregel, kunt u het aantal velden voor aangepaste activiteit dat u in uw Salesforce-instantie moet maken, verminderen.
* Het werkgebied en de taken volgen een consistent patroon dat is gedefinieerd door de Sales Connect Admin.

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
  <td>{{activity_type}</td>
  <td>Hiermee vult u het taaktype in als E-mail, Bel, InMail of Aangepast.</td>
 </tr>
 <tr>
  <td>{{activity_subject}</td>
  <td><p>Zal het onderwerp van de taak vullen.</p>
      <p>In het geval van een e-mail wordt de onderwerpregel van de e-mail ingevuld.</p>
      <p>In het geval van vraag, inMail, of douane, zal het een waarde bevolken als er een herinneringstaak was die met een waarde op het de taaknaam/onderwerpgebied werd gecreeerd.</p></td>
 </tr>
 <tr>
  <td>{{sales_campagne_name}}</td>
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
  <td>{call_result}</td>
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

PICC

1. Klikken **Salesforce**.

PICC

1. Klikken **Instellingen synchroniseren**.

PICC

1. In de redacteur van de Aanpassing van de Details van de Activiteit voeg om het even welke vrije tekst toe u wilt, zal dit voor het onderwerpgebied van alle taken onveranderd blijven die aan Salesforce worden gesynchroniseerd.

1. Voeg dynamische velden toe die u wilt toevoegen door op de knop Dynamisch veld te klikken en de gewenste dynamische velden in de lijst te selecteren.

1. Klikken **Opslaan**.

>[!NOTE]
>
>Salesforce past een limiet van 255 tekens toe. Als uw activiteitendetail dat overschrijdt, zal het worden afgekapt om ervoor te zorgen de informatie op het Salesforce onderwerpgebied kan worden opgeslagen.

>[!MORELIKETHIS]
>
>* [Instellingen synchroniseren](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/salesforce-sync-settings.md)
>* [Herinnering taaksynchronisatie met Salesforce](/help/marketo/product-docs/marketo-sales-connect/tasks/reminder-task-sync-with-salesforce.md)
>* [Aanpassing van Sales Connect voor CRM](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-customization/sales-connect-customizations-for-crm.md)

