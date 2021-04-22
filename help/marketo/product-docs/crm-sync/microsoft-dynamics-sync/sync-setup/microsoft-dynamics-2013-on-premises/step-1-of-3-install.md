---
unique-page-id: 3571813
description: Stap 1 van 3 - Installeer de Marketo-oplossing in Dynamics (2013 op locatie) - Marketo Docs - Productdocumentatie
title: Stap 1 van 3 - Installeer de Marketo-oplossing in Dynamics (2013 op locatie)
exl-id: 89f90bca-b459-447f-bbdd-363f232a1059
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '290'
ht-degree: 0%

---

# Stap 1 van 3: Installeer de Marketo-oplossing in Dynamics (2013 op locatie) {#step-of-install-the-marketo-solution-in-dynamics-on-premises}

Voordat u Microsoft Dynamics On-Premises en Marketo kunt synchroniseren, moet u eerst de Marketo-oplossing installeren in Dynamics.

>[!NOTE]
>
>Nadat u Marketo synchroniseert met een CRM, kunt u geen nieuwe synchronisatie uitvoeren zonder de instantie te vervangen.

>[!PREREQUISITES]
>
>U moet [Internet Facing Deployment](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701) (IFD) hebben met [de Actieve Diensten van de Federatie van de Folder](https://msdn.microsoft.com/en-us/library/bb897402.aspx) 2.0, 2.1 of 3.0 (ADFS) gevormd. Opmerking: Het IFD-document wordt automatisch gedownload wanneer u op de koppeling klikt.
>
>[Download de Marketo-](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md) oplossing voordat u begint.

>[!NOTE]
>
>**Beheerdersrechten voor dynamiek vereist.**
>
>U hebt CRM-beheerdersrechten nodig om deze synchronisatie uit te voeren.

1. Log in **Dynamics**. Klik **Microsoft Dynamics CRM** drop-down menu en selecteer **Montages**.

   ![](assets/image2014-12-11-10-3a39-3a41.png)

1. Selecteer **Oplossingen** onder **Instellingen**.

   ![](assets/image2014-12-11-10-3a39-3a51.png)

1. Klik **Importeren**.

   ![](assets/image2015-3-26-9-3a52-3a10.png)

1. Klik **Bladeren** en selecteer [gedownloade oplossing](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md). Klik **Volgende**.

   ![](assets/image2015-3-26-9-3a54-3a1.png)

1. Bekijk de Informatie van de Oplossing en klik **de details van het oplossingspakket van de Mening**.

   ![](assets/image2015-11-18-11-3a12-3a8.png)

1. Wanneer u klaar bent met het controleren van alle details, klik **Close**.

   ![](assets/image2015-10-9-14-3a57-3a3.png)

1. Terug op de pagina van de Informatie van de Oplossing, klik **Volgende**.

   ![](assets/image2015-3-26-9-3a55-3a17.png)

1. Controleer of de optie SDK is ingeschakeld. Klik **Importeren**.

   ![](assets/image2015-3-26-10-3a3-3a11.png)

1. Wacht tot het importeren is voltooid.

   >[!TIP]
   >
   >U moet pop-ups in uw browser inschakelen om het installatieproces te voltooien.

   ![](assets/image2014-12-11-10-3a41-3a5.png)

1. Download een logbestand (als u dat wilt) en klik op **Close**.

   >[!NOTE]
   >
   >Je ziet mogelijk een bericht met de melding &quot;Marketo Lead Management completed with warning&quot; (Beheer van leads is voltooid met een waarschuwing). Dat wordt volledig verwacht.

   ![](assets/image2014-12-11-10-3a41-3a14.png)

1. Marketo Lead Management wordt nu weergegeven op de pagina **All Solutions**.

   ![](assets/image2015-3-26-10-3a1-3a21.png)

1. Selecteer de Marketo-oplossing en klik op **Alle aanpassingen publiceren**.

   ![](assets/image2014-12-11-10-3a41-3a32.png)

Was het niet zo erg? Kom op, ik zal je door de rest blijven lopen.

>[!CAUTION]
>
>Als u een van de Marketo SDK Messaging Processes uitschakelt, wordt de installatie verbroken!

>[!MORELIKETHIS]
>
>[Stap 2 van 3: Synchronisatiegebruiker voor Marketo configureren (2013 op locatie)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2013-on-premises/step-2-of-3-configure.md)
