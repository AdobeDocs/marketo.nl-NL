---
unique-page-id: 3571739
description: Marketo Sales Insight installeren en configureren in Microsoft Dynamics 365 - Marketo Docs - Productdocumentatie
title: Marketo Sales Insight installeren en configureren in Microsoft Dynamics 365
exl-id: c1f06b8c-48fd-4015-9502-7c9693632589
source-git-commit: 17cacaa56a437a568bd0d2cc23020f3f880eaf52
workflow-type: tm+mt
source-wordcount: '458'
ht-degree: 0%

---

# Marketo Sales Insight installeren en configureren in Microsoft Dynamics 365 {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Marketo Sales Insight is een fantastisch hulpmiddel om uw verkoopteam een &quot;venster&quot; te geven in de schat aan gegevens die het marketingteam heeft. Hier is hoe te installeren en te vormen.

>[!PREREQUISITES]
>
>Voltooi uw integratie tussen Marketo en Microsoft.
>
>[Download de juiste oplossing](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) voor uw versie van Microsoft Dynamics CRM.

## Oplossing importeren {#import-solution}

1. Aanmelden bij [Microsoft Office 365](https://login.microsoftonline.com/).

   ![](assets/image2015-3-16-15-58-55.png)

1. Klik op de knop ![—](assets/image2015-3-16-16-1-13.png) en selecteert u **CRM**.

   ![](assets/image2015-3-16-16-0-10.png)

1. Klik op de knop ![—](assets/image2015-5-13-10-5-8.png) -menu. Selecteer in de vervolgkeuzelijst de optie **Instellingen** selecteert u vervolgens **Oplossingen**.

   ![](assets/image2015-5-13-10-4-1.png)

   >[!NOTE]
   >
   >U moet al [De Marketo-oplossing installeren en configureren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md) voordat u verder gaat.

1. Klikken **Importeren**.

   ![](assets/image2014-12-12-9-3a5-3a27.png)

1. Klik in het nieuwe venster op **Bladeren**. Kies de optie [Marketo Sales Insight-oplossing die u in stap 1 hebt gedownload](#msi). Klikken **Volgende**.

   ![](assets/image2015-5-13-15-3a38-3a49.png)

1. De oplossing wordt geüpload. U kunt de inhoud van het pakket desgewenst weergeven. Klikken **Volgende**.

   ![](assets/image2014-12-12-9-3a6-3a10.png)

1. Zorg ervoor dat u de doos verlaat **ingeschakeld** en klik op **Importeren**.

   ![](assets/image2014-12-12-9-3a6-3a19.png)

1. U kunt het logbestand vrij downloaden. Klikken **Sluiten**.

   ![](assets/image2014-12-12-9-3a6-3a29.png)

1. Geweldig! U moet nu de oplossing zien. Als het er niet is, vernieuw uw scherm.

   ![](assets/image2015-5-13-15-3a42-3a29.png)

1. Klikken **Alle aanpassingen publiceren**.

   ![](assets/image2015-11-10-11-3a15-3a40.png)

## Connect Marketo en Sales Insight {#connect-marketo-and-sales-insight}

Laten we je Marketo-exemplaar koppelen aan Sales Insight in Dynamics. Hieronder wordt beschreven hoe:

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Meld u aan bij Marketo en ga naar de **Beheer** sectie.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. Onder de **Verkoopoverzicht** sectie, klikt u op **API-configuratie bewerken**.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. Kopieer de **Marketo-host**, **API-URL** en **API-gebruikersnaam** voor gebruik in een latere stap. Voer een **API-beveiligingssleutel** van uw keuze en klik op **Opslaan**.

   >[!CAUTION]
   >
   >Gebruik geen en-teken (&amp;) in de geheime API-sleutel.

   ![](assets/image2014-12-12-9-3a7-3a9.png)

   >[!NOTE]
   >
   >De volgende velden moeten met Marketo worden gesynchroniseerd voor _Zowel lead als contact_ voor Sales Insight om te werken:
   >
   > * Prioriteit
   > * Urgentie
   > * Relatieve score

   >
   >Als een van deze velden ontbreekt, wordt in Marketo een foutbericht weergegeven met de naam van de ontbrekende velden. Om dit te verhelpen, voert u [deze procedure](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md).

1. Klik in Microsoft Dynamics op de knop ![](assets/image2015-5-13-15-3a49-3a19.png) pictogram naast Instellingen en selecteer vervolgens **Marketo API Config** in de vervolgkeuzelijst.

   ![](assets/image2015-5-13-16-3a4-3a1.png)

1. Klikken **Standaardconfiguratie**.

   ![](assets/image2015-5-13-16-3a5-3a2.png)

1. Voer de gegevens in die u eerder uit Marketo hebt gekopieerd.

   ![](assets/image2015-5-13-16-3a7-3a6.png)

1. Klik op de knop ![](assets/image2015-5-13-16-3a8-3a51.png) in de rechterbenedenhoek om de wijzigingen op te slaan.

## Gebruikerstoegang instellen {#set-user-access}

U moet gebruikers toestemmingen geven om het Inzicht van de Verkoop te gebruiken.

1. Klik op de knop ![](assets/image2015-5-13-10-3a5-3a8.png) -menu. Selecteer in het vervolgkeuzemenu **Instellingen** selecteert u vervolgens **Beveiliging**.

   ![](assets/image2015-5-13-16-3a12-3a12.png)

1. Klikken **Gebruikers**.

   ![](assets/image2015-4-29-14-3a57-3a46.png)

1. Selecteer de gebruiker(s) aan wie je toegang wilt geven tot Verkoopoverzicht en klik op **Rollen beheren**.

   ![](assets/image2015-4-29-14-3a59-3a31.png)

1. Selecteer **Marketo Sales Insight** rol en klik **OK**.

   ![](assets/image2014-12-12-9-3a9-3a22.png)

   En jullie moeten allemaal klaar zijn! Tot slot om te testen, login als gebruiker die toegang tot het Inzicht van de Verkoop van Marketo heeft en bekijk een lood of een contact.

   ![](assets/image2015-4-29-15-3a2-3a27.png)

Je hebt nu de kracht van Marketo Sales Insight voor je verkoopteam ontgrendeld.

>[!MORELIKETHIS]
>
>[Sterren en vlammen instellen voor lead/contact-records](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
