---
unique-page-id: 7504736
description: Marketo installeren voor Dynamics 2015 On-Prem en 2016 365 On-Prem Stap 1 van 3 - Marketo Docs - Productdocumentatie
title: Marketo installeren voor Dynamics 2015 On-Prem en 2016 365 On-Prem Stap 1 van 3
translation-type: tm+mt
source-git-commit: 2b5ccd7220557a5e966d33436d0f0d2a65e4589d
workflow-type: tm+mt
source-wordcount: '298'
ht-degree: 0%

---


# Stap 1 van 3: Sync User for Marketo configureren (2015 On-Prem en 2016 365 On-Prem) {#step-of-configure-sync-user-for-marketo-on-premises-and-365}

Voordat u Microsoft Dynamics 2015 On-Premises of 2016 (Dynamics 365) met Marketo kunt synchroniseren, moet u eerst de oplossing Marketo in Dynamics installeren.

>[!NOTE]
>
>Nadat u Marketo aan CRM synchroniseert, kunt u geen nieuwe CRM aan de bestaande instantie van Marketo synchroniseren.

>[!PREREQUISITES]
>
>Als u de Dynamica van Microsoft On-Premise gebruikt, moet u [Internet Facing Plaatsing](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701) (IFD) met [de Actieve Diensten van de Federatie van de Folder](https://msdn.microsoft.com/en-us/library/bb897402.aspx) 2.0+ (ADFS) gevormd hebben. Opmerking: Het IFD-document wordt automatisch gedownload wanneer u op de koppeling klikt.
>
>[Download de ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md) Oplossing van het Beheer van de Lood van het Marketo alvorens u begint.

>[!NOTE]
>
>**Beheerdersrechten voor dynamiek vereist.**
>
>U hebt CRM-beheerdersrechten nodig om deze synchronisatie uit te voeren.

1. Meld u aan bij **Dynamica.** Klik het  **drop-down menu van de Dynamica** CRMCRM van Microsoft en selecteer  **Montages**.

   ![](assets/image2015-3-19-8-33-29.png)

1. Selecteer **Oplossingen** onder **Instellingen**.

   ![](assets/image2015-3-19-8-33-3.png)

1. Klik **Importeren**.

   ![](assets/image2015-3-19-8-34-8.png)

1. Klik **Bladeren** en selecteer de oplossing u [downloadt](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md). Klik **Volgende**.

   ![](assets/image2015-3-19-9-20-56.png)

1. Bekijk de Informatie van de Oplossing en klik **de details van het oplossingspakket van de Mening**.

   ![](assets/image2015-11-18-11-12-8.png)

1. Wanneer u klaar bent met het controleren van alle details, klik **Close**.

   ![](assets/step6.png)

1. Terug op de pagina van de Informatie van de Oplossing, klik **Volgende**.

   ![](assets/image2015-3-19-9-21-50.png)

1. Controleer of het selectievakje voor de SDK-optie is ingeschakeld. Klik **Importeren**.

   ![](assets/image2015-3-19-9-19-12.png)

1. Wacht tot het importeren is voltooid.

   >[!TIP]
   >
   >U moet pop-ups in uw browser inschakelen om het installatieproces te voltooien.

   ![](assets/image2015-3-11-11-34-9.png)

1. Download een logbestand (als u dat wilt) en klik op **Close**.

   >[!NOTE]
   >
   >Je ziet mogelijk een bericht met de melding &quot;Beheer van leads markeren voltooid met waarschuwing&quot;. Dat wordt volledig verwacht.

   ![](assets/image2015-3-13-9-54-39.png)

1. Marketo Lead Management wordt nu weergegeven op de pagina **All Solutions**.

   ![](assets/image2015-3-19-8-40-38.png)

1. Selecteer de oplossing Marketo en klik **Alle aanpassingen publiceren**.

   ![](assets/image2015-3-19-8-41-21.png)

   Hoogste vijf! De installatie is voltooid.

   >[!CAUTION]
   >
   >Het onbruikbaar maken van om het even welke processen van het Overseinen van SDK van de Marketo zal in gebroken installeren resulteren!

   >[!MORELIKETHIS]
   >
   >[Marketo installeren voor Dynamics 2015 On-Prem en 2016 365 On-Prem Step 2 of 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2015-on-premises-2016-dynamics-365-on-premises/step-2-of-3-set-up.md)
