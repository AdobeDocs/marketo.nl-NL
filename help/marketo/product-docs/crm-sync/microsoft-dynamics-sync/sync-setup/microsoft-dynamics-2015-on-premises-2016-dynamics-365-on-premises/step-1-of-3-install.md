---
unique-page-id: 7504736
description: Marketo for Dynamics 2015 On-Prem en 2016 365 On-Prem Stap 1 van 3 - Marketo Docs - Productdocumentatie installeren
title: Marketo for Dynamics 2015 On-Prem en 2016 365 On-Prem Stap 1 van 3 installeren
exl-id: c9b6d365-15c1-4eff-938c-8433b1fe7f24
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '298'
ht-degree: 0%

---

# Stap 1 van 3: Sync User for Marketo configureren (2015 On-Prem en 2016 365 On-Prem) {#step-of-configure-sync-user-for-marketo-on-premises-and-365}

Voordat u Microsoft Dynamics 2015 On-Premises of 2016 (Dynamics 365) kunt synchroniseren met Marketo, moet u eerst de Marketo-oplossing installeren in Dynamics.

>[!NOTE]
>
>Nadat u Marketo synchroniseert met een CRM, kunt u geen nieuwe CRM synchroniseren met de bestaande Marketo-instantie.

>[!PREREQUISITES]
>
>Als u de Dynamica van Microsoft On-Premise gebruikt, moet u [Internet Facing Plaatsing](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701) (IFD) met [de Actieve Diensten van de Federatie van de Folder](https://msdn.microsoft.com/en-us/library/bb897402.aspx) 2.0+ (ADFS) gevormd hebben. Opmerking: Het IFD-document wordt automatisch gedownload wanneer u op de koppeling klikt.
>
>[Download de Marketo Lead Management ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md) Solution voordat u begint.

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
   >Je ziet mogelijk een bericht met de melding &quot;Marketo Lead Management completed with warning&quot; (Beheer van leads is voltooid met een waarschuwing). Dat wordt volledig verwacht.

   ![](assets/image2015-3-13-9-54-39.png)

1. Marketo Lead Management wordt nu weergegeven op de pagina **All Solutions**.

   ![](assets/image2015-3-19-8-40-38.png)

1. Selecteer de Marketo-oplossing en klik op **Alle aanpassingen publiceren**.

   ![](assets/image2015-3-19-8-41-21.png)

   Hoogste vijf! De installatie is voltooid.

   >[!CAUTION]
   >
   >Als u een van de Marketo SDK Messaging Processes uitschakelt, wordt de installatie verbroken!

   >[!MORELIKETHIS]
   >
   >[Marketo for Dynamics 2015 On-Prem en 2016 365 On-Prem Step 2 of 3 installeren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2015-on-premises-2016-dynamics-365-on-premises/step-2-of-3-set-up.md)
