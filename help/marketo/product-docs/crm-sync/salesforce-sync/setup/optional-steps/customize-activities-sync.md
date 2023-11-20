---
unique-page-id: 4719294
description: Activiteitssynchronisatie aanpassen - Marketo-documenten - productdocumentatie
title: Activiteiten synchroniseren aanpassen
exl-id: 938d83dc-b9b1-41d8-bf98-04548b074ec4
feature: Salesforce Integration
source-git-commit: 756a38ba87dd5af9ee783e9709056d444d4f415b
workflow-type: tm+mt
source-wordcount: '267'
ht-degree: 0%

---

# Activiteiten synchroniseren aanpassen {#customize-activities-sync}

Als u Marketo Sales Insight niet gebruikt, kan het Marketo Engage de Records van de Geschiedenis van de Activiteit Salesforce voor bepaalde gebeurtenissen tot stand brengen. Hier is hoe je ze kunt inschakelen.

1. Ga naar **[!UICONTROL Admin]**.

   ![](assets/admin.png)

1. Klikken **[!DNL Salesforce]** en klik vervolgens op **[!UICONTROL Edit Sync Options]**.

   ![](assets/two-1.png)

1. Schakel de selectievakjes in naast de activiteiten die u op Marketo wilt uitvoeren en klik op **[!UICONTROL Save]**.

   ![](assets/three-1.png)

   >[!NOTE]
   >
   >Als Marketo eenmaal ingeschakeld is, wordt de activiteithistorie van drie maanden verlengd. Afhankelijk van de hoeveelheid gegevens, _dit kan enkele dagen duren voordat de bewerking is voltooid_. Updates die plaatsvinden tijdens de eerste activiteitenpush kunnen worden uitgesteld tot nadat de eerste activiteitensynchronisatie is voltooid.

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
   <td>Formulier invullen</td> 
   <td>Alle Marketo-formulieren invullen</td> 
  </tr> 
  <tr> 
   <td>Toegevoegd aan lijst</td> 
   <td><p>Stroom stap: is toegevoegd aan een statische lijst</p></td> 
  </tr> 
  <tr> 
   <td>E-mail verzonden</td> 
   <td>Stroom: is een e-mail verzonden</td> 
  </tr> 
  <tr> 
   <td>E-mail bezorgd</td> 
   <td>Een e-mail ontvangen (niet teruggestort)</td> 
  </tr> 
  <tr> 
   <td>E-mail geopend</td> 
   <td>Een e-mail geopend (zonder afbeeldingen te blokkeren)</td> 
  </tr> 
  <tr> 
   <td>Op koppeling in e-mail klikken</td> 
   <td>Klik op een koppeling in een e-mailbericht van Marketo</td> 
  </tr> 
  <tr> 
   <td>Verwijderd uit lijst</td> 
   <td>Stroom stap: is verwijderd uit een statische lijst</td> 
  </tr> 
  <tr> 
   <td>Verwijderen uit stroom</td> 
   <td>Stroom stap: verwijderen uit stroom</td> 
  </tr> 
  <tr> 
   <td>Verkoopemail verzonden</td> 
   <td>Is via Marketo Sales Insight per e-mail verzonden</td> 
  </tr> 
  <tr> 
   <td>Verkoopbericht geopend</td> 
   <td>Open een e-mail die via Marketo Sales Insight is verzonden</td> 
  </tr> 
  <tr> 
   <td>Klik op de koppeling in het e-mailbericht voor verkopen</td> 
   <td>Klik op een koppeling in een e-mailbericht dat via Marketo Sales Insight is verzonden</td> 
  </tr> 
  <tr> 
   <td>Verkoopbericht ontvangen</td> 
   <td>Een e-mail werd ontvangen en door de Verkoper in de Insteekmodule van Vooruitzichten MSI geregistreerd</td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>&quot;E-mailadres van verkoper ontvangen&quot; doet dit _niet_ gemiddeld geleverd. De geleverde status wordt niet vastgelegd voor e-mails die via Verkoopcontrole worden verzonden.

>[!TIP]
>
>Als je meer Marketo-informatie in Salesforce wilt krijgen, kun je onze [Marketo Sales Insight](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"} product.
