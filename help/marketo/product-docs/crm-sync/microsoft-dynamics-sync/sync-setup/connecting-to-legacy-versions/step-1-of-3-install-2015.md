---
unique-page-id: 7504736
description: Marketo for Microsoft Dynamics 2015 op locatie installeren Stap 1 van 3 - Marketo Docs - Productdocumentatie
title: Marketo for Microsoft Dynamics 2015 op locatie installeren Stap 1 van 3
exl-id: c9b6d365-15c1-4eff-938c-8433b1fe7f24
source-git-commit: 1e20fdd1d3c6bba265ceabe499e0d7a4babf4ef1
workflow-type: tm+mt
source-wordcount: '291'
ht-degree: 0%

---

# Stap 1 van 3: Sync User for Marketo configureren (2015 On-Prem) {#step-of-configure-sync-user-for-marketo-on-premises-2015}

Voordat u Microsoft Dynamics 2015 On-Premises kunt synchroniseren met Marketo, moet u eerst de Marketo-oplossing installeren in Dynamics.

>[!NOTE]
>
>Nadat u Marketo synchroniseert met een CRM, kunt u geen nieuwe CRM synchroniseren met de bestaande Marketo-instantie.

>[!PREREQUISITES]
>
>Als u Microsoft Dynamics On-Premise gebruikt, moet u [Implementatie van internetbestanden](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701) (IFD) met [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx) 2.0+ (ADFS) geconfigureerd. Opmerking: Het IFD-document wordt automatisch gedownload wanneer u op de koppeling klikt.
>
>[Download de Marketo Lead Management Solution](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md) voordat u begint.

>[!NOTE]
>
>**Beheerdersrechten voor dynamiek vereist.**
>
>U hebt CRM-beheerdersrechten nodig om deze synchronisatie uit te voeren.

1. Aanmelden bij **Dynamiek.** Klik op de knop **Microsoft Dynamics CRM** vervolgkeuzelijst en selecteert u **Instellingen**.

   ![](assets/image2015-3-19-8-33-29.png)

1. Onder **Instellingen**, selecteert u **Oplossingen**.

   ![](assets/image2015-3-19-8-33-3.png)

1. Klikken **Importeren**.

   ![](assets/image2015-3-19-8-34-8.png)

1. Klikken **Bladeren** en selecteer de oplossing die u [gedownload](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md). Klikken **Volgende**.

   ![](assets/image2015-3-19-9-20-56.png)

1. Bekijk de Informatie van de Oplossing en klik **Details van oplossingspakket weergeven**.

   ![](assets/image2015-11-18-11-12-8.png)

1. Wanneer u alle details hebt gecontroleerd, klikt u op **Sluiten**.

   ![](assets/step6.png)

1. Terug op de pagina van de Informatie van de Oplossing, klik **Volgende**.

   ![](assets/image2015-3-19-9-21-50.png)

1. Controleer of het selectievakje voor de SDK-optie is ingeschakeld. Klikken **Importeren**.

   ![](assets/image2015-3-19-9-19-12.png)

1. Wacht tot het importeren is voltooid.

   >[!TIP]
   >
   >U moet pop-ups in uw browser inschakelen om het installatieproces te voltooien.

   ![](assets/image2015-3-11-11-34-9.png)

1. Download een logbestand (indien gewenst) en klik op **Sluiten**.

   >[!NOTE]
   >
   >Je ziet mogelijk een bericht met de melding &quot;Marketo Lead Management completed with warning&quot; (Beheer van leads is voltooid met een waarschuwing). Dat wordt volledig verwacht.

   ![](assets/image2015-3-13-9-54-39.png)

1. Marketo Lead Management wordt nu weergegeven op het tabblad **Alle oplossingen** pagina.

   ![](assets/image2015-3-19-8-40-38.png)

1. Selecteer de Marketo-oplossing en klik op **Alle aanpassingen publiceren**.

   ![](assets/image2015-3-19-8-41-21.png)

   Hoogste vijf! De installatie is voltooid.

   >[!CAUTION]
   >
   >Als u een van de Marketo SDK Messaging Processes uitschakelt, wordt de installatie verbroken!

   >[!MORELIKETHIS]
   >
   >[Marketo for Microsoft Dynamics 2015 op locatie installeren Stap 2 van 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-set-up-2015.md)
