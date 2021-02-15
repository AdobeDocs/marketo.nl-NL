---
unique-page-id: 3571739
description: Installeer en vorm het Inzicht van de Verkoop van de Marketo in de Dynamica 365 van Microsoft - Marketo Docs - de Documentatie van het Product
title: Het Inzicht van de Verkoop van de Marketo in de Dynamica 365 van Microsoft installeren en vormen
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '458'
ht-degree: 0%

---


# Het Inzicht van de Verkoop van de Marketo in de Dynamica 365 van Microsoft installeren en vormen {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Marketo Sales Insight is een fantastisch hulpmiddel om uw verkoopteam een &quot;venster&quot;in de rijkdom aan gegevens te geven het team van de Marketing heeft. Hier is hoe te installeren en te vormen.

>[!PREREQUISITES]
>
>Voltooi uw integratie van Marketo-Microsoft.
>
>[Download de correcte ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) oplossing voor uw versie van CRM van de Dynamica van Microsoft.

## Oplossing {#import-solution} importeren

1. Meld u aan bij [Microsoft Office 365](https://login.microsoftonline.com/).

   ![](assets/image2015-3-16-15-58-55.png)

1. Klik op het menu ![—](assets/image2015-3-16-16-1-13.png) en selecteer **CRM**.

   ![](assets/image2015-3-16-16-0-10.png)

1. Klik op het menu ![—](assets/image2015-5-13-10-5-8.png). Selecteer **Instellingen** in de vervolgkeuzelijst en selecteer **Oplossingen**.

   ![](assets/image2015-5-13-10-4-1.png)

   >[!NOTE]
   >
   >U zou [reeds moeten geïnstalleerd en de oplossing van het Marketo ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-1-of-3-install.md) hebben alvorens zich vooruit te bewegen.

1. Klik **Importeren**.

   ![](assets/image2014-12-12-9-3a5-3a27.png)

1. Klik in het nieuwe venster op **Bladeren**. Kies de [Marketo Sales Insight-oplossing die u in stap 1 hebt gedownload](#msi). Klik **Volgende**.

   ![](assets/image2015-5-13-15-3a38-3a49.png)

1. De oplossing wordt geüpload. U kunt de inhoud van het pakket desgewenst weergeven. Klik **Volgende**.

   ![](assets/image2014-12-12-9-3a6-3a10.png)

1. Zorg ervoor dat het vak **ingeschakeld** blijft en klik op **Importeren**.

   ![](assets/image2014-12-12-9-3a6-3a19.png)

1. U kunt het logbestand vrij downloaden. Klik **Close**.

   ![](assets/image2014-12-12-9-3a6-3a29.png)

1. Geweldig! U moet nu de oplossing zien. Als het er niet is, vernieuw uw scherm.

   ![](assets/image2015-5-13-15-3a42-3a29.png)

1. Klik **Alle aanpassingen publiceren**.

   ![](assets/image2015-11-10-11-3a15-3a40.png)

## {#connect-marketo-and-sales-insight}

Laten we je Marketo-instantie aan Sales Insight in Dynamics koppelen. Hieronder wordt beschreven hoe:

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Meld u aan bij Marketo en ga naar de sectie **Admin**.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. Klik onder **Sales Insight** sectie op **API-configuratie bewerken**.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. Kopieer **Marketo Host**, **API URL** en **API Gebruiker ID** voor gebruik in een recentere stap. Voer een **API-beveiligingssleutel** van uw keuze in en klik op **Opslaan**.

   >[!CAUTION]
   >
   >Gebruik geen en-teken (&amp;) in de geheime API-sleutel.

   ![](assets/image2014-12-12-9-3a7-3a9.png)

   >[!NOTE]
   >
   >De volgende gebieden moeten met Marketo voor _zowel Lood als Contact_ voor het Inzicht van de Verkoop worden gesynchroniseerd om te werken:
   >
   > * Prioriteit
   > * Urgentie
   > * Relatieve score

   >
   >Als een van deze velden ontbreekt, wordt in Marketo een foutbericht weergegeven met de naam van de ontbrekende velden. Om dit te bevestigen, voer [deze procedure](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md) uit.

1. Klik in Microsoft Dynamics op het pictogram ![](assets/image2015-5-13-15-3a49-3a19.png) naast Instellingen en selecteer **Marketo API Config** in het vervolgkeuzemenu.

   ![](assets/image2015-5-13-16-3a4-3a1.png)

1. Klik **Standaardconfiguratie**.

   ![](assets/image2015-5-13-16-3a5-3a2.png)

1. Voer de informatie in die u van Marketo eerder hebt gekopieerd.

   ![](assets/image2015-5-13-16-3a7-3a6.png)

1. Klik op het pictogram ![](assets/image2015-5-13-16-3a8-3a51.png) in de rechterbenedenhoek om de wijzigingen op te slaan.

## Gebruikerstoegang {#set-user-access} instellen

U moet gebruikers toestemmingen geven om het Inzicht van de Verkoop te gebruiken.

1. Klik op het menu ![](assets/image2015-5-13-10-3a5-3a8.png). Selecteer **Instellingen** in het vervolgkeuzemenu en selecteer **Beveiliging**.

   ![](assets/image2015-5-13-16-3a12-3a12.png)

1. Klik **Users**.

   ![](assets/image2015-4-29-14-3a57-3a46.png)

1. Selecteer de gebruiker(s) u toegang tot het Inzicht van de Verkoop wilt geven aan en **Rollen beheren** klikken.

   ![](assets/image2015-4-29-14-3a59-3a31.png)

1. Selecteer de rol **Marketo Sales Insight** en klik **OK**.

   ![](assets/image2014-12-12-9-3a9-3a22.png)

   En jullie moeten allemaal klaar zijn! Tot slot om te testen, login als gebruiker die toegang tot het Inzicht van de Verkoop van de Marketo heeft en bekijk een lood of een contact.

   ![](assets/image2015-4-29-15-3a2-3a27.png)

U hebt nu de macht van het Inzicht van de Verkoop van de Marketo voor uw verkoopteam ontgrendeld.

>[!MORELIKETHIS]
>
>[Sterren en vlammen instellen voor lead/contact-records](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
