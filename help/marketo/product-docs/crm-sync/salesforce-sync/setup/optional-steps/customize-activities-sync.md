---
unique-page-id: 4719294
description: Activiteiten synchroniseren - Marketo Docs - Productdocumentatie aanpassen
title: Activiteiten synchroniseren aanpassen
translation-type: tm+mt
source-git-commit: 2b5ccd7220557a5e966d33436d0f0d2a65e4589d
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 0%

---


# Activiteitssynchronisatie aanpassen {#customize-activities-sync}

Als u het Inzicht van de Verkoop van de Marketo niet gebruikt, kan de Marketo Verslagen van de Geschiedenis van de Activiteit Salesforce voor bepaalde gebeurtenissen tot stand brengen. Hier is hoe je ze kunt inschakelen.

1. Ga naar **Admin**.

   ![](assets/admin.png)

1. Klik **Salesforce**, dan klik **geef de Opties van de Synchronisatie** uit.

   ![](assets/two-1.png)

1. Schakel de selectievakjes in naast de activiteiten die u wilt uitvoeren door Marketo op Salesforce en klik op **Opslaan**.

   ![](assets/three-1.png)

   >[!NOTE]
   >
   >Als Marketo eenmaal is ingeschakeld, wordt de activiteithistorie van drie maanden verlengd. Afhankelijk van de hoeveelheid gegevens kan _dit enkele dagen duren om te voltooien_. Updates die plaatsvinden tijdens de eerste activiteitenpush kunnen worden uitgesteld tot nadat de eerste activiteitensynchronisatie is voltooid.

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
   <td><p>Stroom: Is toegevoegd aan een statische lijst</p></td> 
  </tr> 
  <tr> 
   <td>E-mail verzonden</td> 
   <td>Stroom: Is per e-mail verzonden</td> 
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
   <td>Klik op een koppeling in een e-mailbericht dat Marketo heeft verzonden</td> 
  </tr> 
  <tr> 
   <td>Verwijderd uit lijst</td> 
   <td>Stroom: Is verwijderd uit een statische lijst</td> 
  </tr> 
  <tr> 
   <td>Verwijderen uit stroom</td> 
   <td>Stroom: Verwijderen uit stroom</td> 
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
   <td>Verkoop-e-mail ontvangen</td> 
   <td>Een e-mail werd ontvangen en door de Verkoper in de Plug-in MSI Outlook geregistreerd</td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>&quot;Ontvangen e-mail van de Verkoop&quot;betekent **niet** geleverde. De geleverde status wordt niet vastgelegd voor e-mails die via Verkoopcontrole worden verzonden.

>[!TIP]
>
>Als u in het krijgen van meer informatie van de Marketo in Salesforce geinteresseerd bent, controleer ons [product van het Inzicht van de Verkoop van de Marketo](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md).
