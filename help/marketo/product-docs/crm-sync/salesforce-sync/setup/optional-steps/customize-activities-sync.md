---
unique-page-id: 4719294
description: Activiteitssynchronisatie aanpassen - Marketo-documenten - productdocumentatie
title: Activiteiten synchroniseren aanpassen
exl-id: 938d83dc-b9b1-41d8-bf98-04548b074ec4
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '253'
ht-degree: 0%

---

# Activiteiten synchroniseren aanpassen {#customize-activities-sync}

Als u Marketo Sales Insight niet gebruikt, kan Marketo Engage Salesforce Activity History Records voor bepaalde gebeurtenissen maken. Hier is hoe je ze kunt inschakelen.

>[!NOTE]
>
>De Salesforce/Marketo Engage-synchronisatie zal geen activiteiten naar Salesforce duwen die zich hebben voorgedaan voordat de persoon naar Salesforce werd geduwd.

1. Ga naar **[!UICONTROL Admin]** .

   ![](assets/customize-activities-sync-1.png)

1. Klik op **[!DNL Salesforce]** en vervolgens op **[!UICONTROL Edit Sync Options]** .

   ![](assets/two-1.png)

1. Schakel de selectievakjes in naast de activiteiten die Marketo naar Salesforce moet uitvoeren en klik op **[!UICONTROL Save]** .

   ![](assets/three-1.png)

   >[!NOTE]
   >
   >Als Marketo eenmaal ingeschakeld is, wordt de activiteithistorie van drie maanden verlengd. Afhankelijk van de hoeveelheid gegevens, _zou dit verscheidene dagen kunnen vergen om_ te voltooien. Updates die plaatsvinden tijdens de eerste activiteitenpush kunnen worden uitgesteld tot nadat de eerste activiteitensynchronisatie is voltooid.

<table>
 <colgroup>
  <col>
  <col>
 </colgroup>
 <thead>
  <tr>
   <th>Type activiteit</th>
   <th>Beschrijving</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td>[!UICONTROL Filled out form]</td>
   <td>Alle Marketo-formulieren invullen</td>
  </tr>
  <tr>
   <td>[!UICONTROL Added to list]</td>
   <td><p>Stroom stap: is toegevoegd aan een statische lijst</p></td>
  </tr>
  <tr>
   <td>[!UICONTROL Email sent]</td>
   <td>Stroom: is een e-mail verzonden</td>
  </tr>
  <tr>
   <td>[!UICONTROL Email delivered]</td>
   <td>Een e-mail ontvangen (niet teruggestort)</td>
  </tr>
  <tr>
   <td>[!UICONTROL Email opened]</td>
   <td>Een e-mail geopend (zonder afbeeldingen te blokkeren)</td>
  </tr>
  <tr>
   <td>[!UICONTROL Clicked link in email]</td>
   <td>Klik op een koppeling in een e-mailbericht van Marketo</td>
  </tr>
  <tr>
   <td>[!UICONTROL Removed from list]</td>
   <td>Stroom stap: is verwijderd uit een statische lijst</td>
  </tr>
  <tr>
   <td>[!UICONTROL Remove from flow]</td>
   <td>Stroom stap: verwijderen uit stroom</td>
  </tr>
  <tr>
   <td>[!UICONTROL Sales email sent]</td>
   <td>Is per e-mail verzonden via Marketo Sales Insight</td>
  </tr>
  <tr>
   <td>[!UICONTROL Sales email opened]</td>
   <td>Open een e-mail die via Marketo Sales Insight is verzonden</td>
  </tr>
  <tr>
   <td>[!UICONTROL Click link in sales email]</td>
   <td>Klik op een koppeling in een e-mailbericht dat via Marketo Sales Insight is verzonden</td>
  </tr>
  <tr>
   <td>[!UICONTROL Sales email received]</td>
   <td>Een e-mail werd ontvangen en door de Verkoper in de Insteekmodule van Vooruitzichten MSI geregistreerd</td>
  </tr>
 </tbody>
</table>

>[!NOTE]
>
>&quot;Verkoop e-mail ontvangen&quot;betekent _niet_ geleverde. De geleverde status wordt niet vastgelegd voor e-mails die via Sales Insight worden verzonden.

>[!TIP]
>
>Als u in het krijgen van meer informatie van Marketo in Salesforce geinteresseerd bent, controleer ons [ product van de Verkoop Insight van 0&rbrace; Marketo.](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"}
