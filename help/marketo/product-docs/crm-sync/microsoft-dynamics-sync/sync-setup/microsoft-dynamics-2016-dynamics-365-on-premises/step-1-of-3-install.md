---
description: Marketo for Microsoft Dynamics 2016/Dynamics 365 On-Premises 1 of 3 - Marketo Docs - Productdocumentatie installeren
title: Marketo for Microsoft Dynamics 2016/Dynamics 365 On-Premises Stap 1 van 3 installeren
exl-id: 0a494ae7-87da-4ff9-bb47-990b957533e1
feature: Microsoft Dynamics
source-git-commit: 15cb3ddcd82fa1ba60fae3aa1adaac3d5964a0fa
workflow-type: tm+mt
source-wordcount: '270'
ht-degree: 1%

---

# Stap 1 van 3: Sync User for Marketo configureren (2016 On-Prem /Dynamics 365 On-Premises) {#step-of-configure-sync-user-for-marketo-on-premises-2016}

Voordat u Microsoft Dynamics 2016 On-Prem/Dynamics 365 kunt synchroniseren met Marketo Engage, moet u eerst de Marketo-oplossing installeren in Dynamics.

>[!NOTE]
>
>Nadat u Marketo synchroniseert met een CRM, kunt u geen nieuwe CRM synchroniseren met de bestaande Marketo-instantie.

>[!PREREQUISITES]
>
>Als u Microsoft Dynamics On-Premise gebruikt, moet u [Implementatie van internetbestanden](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701){target="_blank"} (IFD) with [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx){target="_blank"} 2.0+ (ADFS) geconfigureerd. Opmerking: het IFD-document wordt automatisch gedownload wanneer u op de koppeling klikt.
>
>[Download de Marketo Lead Management Solution](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"} voordat u begint.

>[!NOTE]
>
>**Beheerdersrechten voor dynamiek vereist**.
>
>U hebt CRM-beheerdersrechten nodig om deze synchronisatie uit te voeren.

1. Meld u aan bij Dynamiek. Klik op de knop **[!UICONTROL Microsoft Dynamics CRM]** vervolgkeuzelijst en selecteert u **[!UICONTROL Settings]**.

   ![](assets/image2015-3-19-8-33-29.png)

1. Selecteer onder **[!UICONTROL Settings]** de optie **[!UICONTROL Solutions]**.

   ![](assets/image2015-3-19-8-33-3.png)

1. Klik op **[!UICONTROL Import]**.

   ![](assets/image2015-3-19-8-34-8.png)

1. Klikken **[!UICONTROL Browse]** en selecteer de oplossing die u [gedownload](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"}. Klikken **Volgende**.

   ![](assets/image2015-3-19-9-20-56.png)

1. Bekijk de Informatie van de Oplossing en klik **[!UICONTROL View solution package details]**.

   ![](assets/image2015-11-18-11-12-8.png)

1. Wanneer u alle details hebt gecontroleerd, klikt u op **[!UICONTROL Close]**.

   ![](assets/step6.png)

1. Terug op de pagina van de Informatie van de Oplossing, klik **[!UICONTROL Next]**.

   ![](assets/image2015-3-19-9-21-50.png)

1. Controleer of het selectievakje voor de SDK-optie is ingeschakeld. Klik op **[!UICONTROL Import]**.

   ![](assets/image2015-3-19-9-19-12.png)

1. Wacht tot het importeren is voltooid.

   >[!TIP]
   >
   >U moet pop-ups in uw browser inschakelen om het installatieproces te voltooien.

   ![](assets/image2015-3-11-11-34-9.png)

1. Download een logbestand (indien gewenst) en klik op **[!UICONTROL Close]**.

   >[!NOTE]
   >
   >Je ziet mogelijk een bericht met de melding &quot;Marketo Lead Management completed with warning&quot; (Beheer van leads is voltooid met een waarschuwing). Dat wordt volledig verwacht.

   ![](assets/image2015-3-13-9-54-39.png)

1. Marketo Lead Management wordt nu weergegeven op het tabblad **[!UICONTROL All Solutions]** pagina.

   ![](assets/image2015-3-19-8-40-38.png)

1. Selecteer de Marketo-oplossing en klik op **[!UICONTROL Publish All Customizations]**.

   ![](assets/image2015-3-19-8-41-21.png)

   Hoogste vijf! De installatie is voltooid.

   >[!CAUTION]
   >
   >Als u een van de Marketo SDK Messaging Processes uitschakelt, wordt de installatie verbroken!

   >[!MORELIKETHIS]
   >
   >[Marketo for Dynamics 2015 On-Prem en 2016 365 On-Prem Step 2 of 3 installeren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-2-of-3-set-up.md){target="_blank"}
