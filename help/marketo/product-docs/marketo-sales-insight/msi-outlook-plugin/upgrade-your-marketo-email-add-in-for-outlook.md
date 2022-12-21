---
unique-page-id: 2949279
description: Upgrade uw Marketo E-mailinvoegtoepassing voor Outlook - Marketo Docs - Productdocumentatie
title: Upgrade uw Marketo-invoegtoepassing voor e-mail voor Outlook
exl-id: 079f1142-8062-448c-aa07-59ecd89a718f
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '405'
ht-degree: 0%

---

# Upgrade uw Marketo-invoegtoepassing voor e-mail voor Outlook {#upgrade-your-marketo-email-add-in-for-outlook}

Als er een nieuwe versie van de Marketo E-mailinvoegtoepassing voor Outlook beschikbaar is, volgt u deze instructies om een upgrade uit te voeren.

>[!NOTE]
>
>Vanaf 10/1/20, steunt de recentste versie van de stop van Vooruitzichten niet meer off-line wijze. Dit wordt van kracht na de installatie/upgrade op of na 10/1.

## Installatieprogramma downloaden {#download-installer}

Download het installatieprogramma dat geschikt is voor uw versie van Microsoft Outlook.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th><br></th> 
   <th colspan="2">Uitnodiging voor één gebruiker installeren</th> 
   <th colspan="2">Installatie van Enterprise Key</th> 
  </tr> 
  <tr> 
   <td><strong>Outlook-versie</strong></td> 
   <td><strong>32-bits</strong></td> 
   <td><strong>64-bits</strong></td> 
   <td><strong>32-bits</strong></td> 
   <td><strong>64-bits</strong></td> 
  </tr> 
  <tr> 
   <td>Outlook 2000</td> 
   <td>Niet ondersteund</td> 
   <td>N.v.t.</td> 
   <td>Niet ondersteund</td> 
   <td>N.v.t.</td> 
  </tr> 
  <tr> 
   <td>Outlook 2003</td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">Downloaden</a></td> 
   <td>N.v.t.</td> 
   <td>Niet ondersteund</td> 
   <td>N.v.t.</td> 
  </tr> 
  <tr> 
   <td>Outlook 2007</td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">Downloaden</a></td> 
   <td>N.v.t.</td> 
   <td>Niet ondersteund</td> 
   <td>N.v.t.</td> 
  </tr> 
  <tr> 
   <td>Outlook 2010</td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">Downloaden</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">Downloaden</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">Downloaden</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">Downloaden</a></td> 
  </tr> 
  <tr> 
   <td>Outlook 2013</td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">Downloaden</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">Downloaden</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">Downloaden</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">Downloaden</a></td> 
  </tr> 
  <tr> 
   <td>Outlook 2016</td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">Downloaden</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">Downloaden</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">Downloaden</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">Downloaden</a></td> 
  </tr> 
  <tr> 
   <td colspan="1">Outlook 2019</td> 
   <td colspan="1"><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">Downloaden</a></td> 
   <td colspan="1"><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">Downloaden</a></td> 
   <td colspan="1"><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">Downloaden</a></td> 
   <td colspan="1"><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">Downloaden</a></td> 
  </tr> 
  <tr> 
   <td>Outlook voor Mac</td> 
   <td>Niet ondersteund</td> 
   <td>Niet ondersteund</td> 
   <td>Niet ondersteund</td> 
   <td>Niet ondersteund</td> 
  </tr> 
  <tr> 
   <td colspan="1">Outlook Web App</td> 
   <td colspan="1">Niet ondersteund</td> 
   <td colspan="1">Niet ondersteund</td> 
   <td colspan="1">Niet ondersteund</td> 
   <td colspan="1">Niet ondersteund</td> 
  </tr> 
  <tr> 
   <td colspan="1">Office 365*</td> 
   <td colspan="1"><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">Downloaden</a></td> 
   <td colspan="1"><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">Downloaden</a></td> 
   <td colspan="1"><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">Downloaden</a></td> 
   <td colspan="1"><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">Downloaden</a></td> 
  </tr> 
 </tbody> 
</table>

&#42;Versie Office 365: Alleen Windows-client (in Windows 10, Enterprise of Pro).

## Upgrade {#upgrade}

1. Identificeer uw [Microsoft Outlook-versie](https://support.microsoft.com/en-us/office/what-version-of-outlook-do-i-have-b3a9568c-edb5-42b9-9825-d48d82b2257c?ui=en-us&amp;rs=en-us&amp;ad=us).

1. Selecteer uw versie in de bovenstaande lijst.

1. Voer het installatieprogramma uit.

   ![](assets/image2014-9-23-16-3a53-3a56.png)

1. Klikken **Volgende**.

   ![](assets/image2014-9-23-16-3a54-3a8.png)

   >[!NOTE]
   >
   >In bepaalde gevallen ontbreken de gegevens. Kopieer het uit de registratie-e-mail en sluit Outlook.

1. Sluit Microsoft Outlook.

   ![](assets/ent-key-close-outlook-hand.png)

1. Je ziet dat al je gegevens zijn voorgevuld. Eenvoudig klikken **Volgende**.

   ![](assets/image2014-9-23-16-3a54-3a40.png)

   >[!TIP]
   >
   >Als de installatie mislukt, werkt u samen met uw IT-afdeling om ervoor te zorgen dat HTTPS-verkeer niet wordt geblokkeerd. Het installatieprogramma vereist dat HTTPS-verkeer is geopend.

1. Klikken **Volgende** om op de standaardlocatie te installeren.

   ![](assets/image2014-9-23-16-3a54-3a55.png)

1. Klikken **Volgende**.

   ![](assets/image2014-9-23-16-3a55-3a20.png)

1. De installatie is nu voltooid. Klikken **Sluiten**.

   ![](assets/image2014-9-23-16-3a55-3a34.png)

1. Open nu Microsoft Outlook om de nieuwste versie van de Marketo-knoppen te bekijken.

   ![](assets/image2016-8-24-15-3a47-3a38.png)

>[!MORELIKETHIS]
>
>* [Een e-mail verzenden en bijhouden met de Marketo E-mailinvoegtoepassing voor Outlook](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/send-and-track-an-email-with-the-email-add-in-for-outlook.md)
>* [Verzenden en volgen vanuit Outlook met een Marketo-sjabloon](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/send-and-track-from-outlook-using-a-marketo-template.md)

