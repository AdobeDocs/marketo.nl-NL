---
unique-page-id: 2949711
description: De Marketo E-mailinvoegtoepassing voor Outlook installeren met een registratiecode - Marketo Docs - Productdocumentatie
title: De Marketo E-mailinvoegtoepassing voor Outlook installeren met een registratiecode
exl-id: d7a877c2-f71e-44da-b323-04f6cdb44eb0
feature: Marketo Sales Insights
source-git-commit: 40fe81d465d04be97ae5e216250b7e06e6d3791e
workflow-type: tm+mt
source-wordcount: '491'
ht-degree: 0%

---

# De Marketo E-mailinvoegtoepassing voor Outlook installeren met een registratiecode {#install-the-marketo-email-add-in-for-outlook-with-a-registration-code}

Als gebruikers toegang hebben tot de beheerinstellingen op hun laptops, kunt u een registratiecode rechtstreeks naar hen sturen.

Als u geen uitnodigings-e-mail hebt ontvangen, vraagt u de Marketo-beheerder om u uit te nodigen.

>[!PREREQUISITES]
>
>U moet [heeft een Marketo-licentie voor e-mailinvoegtoepassingen uitgegeven](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/issue-a-marketo-email-add-in-license.md).

>[!IMPORTANT]
>
>Installatie wordt niet ondersteund op pc&#39;s waarin de map Windows User tekens bevat die niet uit het Engels bestaan. Deze map wordt automatisch onder Windows gegenereerd `<System Root>\Users\` op basis van de gebruikersnaam van Windows en mag niet-Engelse tekens bevatten als de gebruikersnaam van de Windows-gebruiker een niet-Engelse naam is. Werk samen met uw IT-team om te controleren of er installatiekwesties optreden.

>[!NOTE]
>
>De mogelijkheden van Handelingen van het Inzicht van de verkoop, met inbegrip van verzenden Verkoop E-mail, toevoegen aan de Campagne van de Verkoop, en Taken, zijn niet beschikbaar in de e-mailplug-ins van het Inzicht van de Verkoop voor Gmail en Vooruitzichten. Op dit moment kunnen gebruikers alleen een e-mailbericht met of zonder Marketo-sjabloon van hun e-mailclient verzenden als ze de e-mailplug-ins voor Insight gebruiken.

## Installatieprogramma downloaden {#download-installer}

1. Identificeer uw [Microsoft Outlook-versie](https://support.office.com/en-us/article/what-version-of-outlook-do-i-have-b3a9568c-edb5-42b9-9825-d48d82b2257c){target="_blank"}

1. Klik op de koppeling om het juiste installatieprogramma voor uw versie van Microsoft Outlook te downloaden.

   >[!NOTE]
   >
   >Op dit moment werken de onderstaande koppelingen alleen in Microsoft Edge of door met de rechtermuisknop in Chrome te klikken. Sorry voor enig ongemak.

   | Outlook-versie | 32-bits Outlook | 64-bits Outlook |
   |---|---|---|
   | Outlook 2000 | Niet ondersteund | NVT |
   | Outlook 2003 | [Downloaden](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | NVT |
   | Outlook 2007 | [Downloaden](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | NVT |
   | Outlook 2010 | [Downloaden](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [Downloaden](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |
   | Outlook 2013 | [Downloaden](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [Downloaden](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |
   | Outlook 2016 | [Downloaden](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [Downloaden](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |
   | Outlook 2019 | [Downloaden](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [Downloaden](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |
   | Outlook voor Mac | Niet ondersteund | Niet ondersteund |
   | Outlook Web App | Niet ondersteund | Niet ondersteund |
   | Office 365* | [Downloaden](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [Downloaden](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |

   *Office 365-versie: alleen Windows-client (Windows 10, Enterprise of Pro).

   >[!IMPORTANT]
   >
   >Microsoft heeft een [nieuwe versie van Outlook voor Windows](https://techcommunity.microsoft.com/t5/outlook-blog/new-outlook-for-windows-now-available/ba-p/3932068){target="_blank"}. This new version does not support the existing MSI Outlook plugin. The MSI Outlook plugin will continue to work for Windows desktops running the classic version of Outlook. To learn more about the new Outlook for Windows for organizations, [click here](https://techcommunity.microsoft.com/t5/outlook-blog/the-new-outlook-for-windows-for-organization-admins/ba-p/3929169){target="_blank"}.

## Je inschrijvingscode kopiëren {#copy-your-registration-code}

1. Kopieer de registratiecode van de uitnodigings-e-mail u hebt ontvangen.

   ![](assets/image2016-7-22-10-3a45-3a10.png)

1. Sluit Microsoft Outlook.

   ![](assets/ent-key-close-outlook-hand.png)

## Installeren {#install}

1. Voer het installatieprogramma uit.

   ![](assets/image2016-7-25-10-3a23-3a33.png)

   >[!NOTE]
   >
   >Als je een beveiligingswaarschuwing krijgt, maak je dan geen zorgen! Alleen klikken **Uitvoeren**.

1. Klikken **Volgende**.

   ![](assets/welcome-to-the-setup-wizard-hand.png)

1. Invullen **Voornaam**, **Achternaam**, **E-mailadres** kopieert en plakt u vervolgens de **Registratiecode** van de e-mail naar het formulier en klik op **Volgende**.

   ![](assets/enter-your-information-hands.png)

   >[!TIP]
   >
   >Als de installatie mislukt, raadpleegt u uw IT-afdeling om ervoor te zorgen dat HTTPS-verkeer niet wordt geblokkeerd. Het installatieprogramma vereist dat HTTPS-verkeer is geopend.

1. Klikken **Volgende** om op de standaardlocatie te installeren.

   ![](assets/select-installation-folder-hand.png)

1. Klikken **Volgende**.

   ![](assets/confirm-installation-hand.png)

   >[!NOTE]
   >
   >Als er een beveiligingswaarschuwing verschijnt over een onbekende uitgever, klikt u op **Ja**.

1. De installatie is nu voltooid. Klik op **Sluiten**.

   ![](assets/image2014-9-23-15-3a52-3a11.png)

1. Open nu Microsoft Outlook en bekijk de Marketo-knoppen.

   ![](assets/image2016-8-24-15-3a47-3a38.png)

   Uitstekend! De Marketo-knoppen zijn nu beter geplaatst.

Meer informatie over het gebruik van Marketo Message and Log With Marketo-handelingen.

>[!MORELIKETHIS]
>
>* [Een e-mail verzenden en bijhouden met de Marketo E-mailinvoegtoepassing voor Outlook](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/send-and-track-an-email-with-the-email-add-in-for-outlook.md){target="_blank"}
>* [Verzenden en volgen vanuit Outlook met een Marketo-sjabloon](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/send-and-track-from-outlook-using-a-marketo-template.md){target="_blank"}
