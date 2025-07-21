---
unique-page-id: 3571813
description: Stap 1 van 3 - Installeer de Marketo-oplossing in Dynamics (2013 op locatie) - Marketo Docs - Productdocumentatie
title: Stap 1 van 3 - Installeer de Marketo-oplossing in Dynamics (2013 op locatie)
exl-id: 89f90bca-b459-447f-bbdd-363f232a1059
feature: Microsoft Dynamics
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '250'
ht-degree: 1%

---

# Stap 1 van 3: Installeer de Marketo-oplossing in [!DNL Dynamics] (2013 op locatie) {#step-of-install-the-marketo-solution-in-dynamics-on-premises}

Voordat u [!DNL Microsoft Dynamics] Op locatie en Marketo kunt synchroniseren, moet u eerst de Marketo-oplossing installeren in [!DNL Dynamics] .

>[!NOTE]
>
>Nadat u Marketo synchroniseert met een CRM, kunt u geen nieuwe synchronisatie uitvoeren zonder de instantie te vervangen.

>[!PREREQUISITES]
>
>U moet [ Internet hebben dat Plaatsing ](https://learn.microsoft.com/en-us/dynamics365/customerengagement/on-premises/deploy/configure-an-internet-facing-deployment){target="_blank"} (IFD) met [ de Actieve Diensten van de Federatie van de Folder ](https://msdn.microsoft.com/en-us/library/bb897402.aspx){target="_blank"} 2.0, 2.1 of 3.0 (ADFS) gevormd. Opmerking: het IFD-document wordt automatisch gedownload wanneer u op de koppeling klikt.
>
>[ Download de Oplossing van Marketo ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"} alvorens u begint.

>[!NOTE]
>
>**[!DNL Dynamics]Beheerdersmachtigingen vereist.**
>
>U hebt CRM-beheerdersrechten nodig om deze synchronisatie uit te voeren.

1. Meld u aan bij **[!DNL Dynamics]** . Klik op de vervolgkeuzelijst **[!UICONTROL Microsoft Dynamics CRM]** en selecteer **[!UICONTROL Settings]** .

   ![](assets/image2014-12-11-10-3a39-3a41.png)

1. Selecteer onder **[!UICONTROL Settings]** de optie **[!UICONTROL Solutions]** .

   ![](assets/image2014-12-11-10-3a39-3a51.png)

1. Klik op **[!UICONTROL Import]**.

   ![](assets/image2015-3-26-9-3a52-3a10.png)

1. Klik **[!UICONTROL Browse]** en selecteer de [ gedownloade oplossing ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md). Klik op **[!UICONTROL Next]**.

   ![](assets/image2015-3-26-9-3a54-3a1.png)

1. Bekijk [!UICONTROL Solution Information] en klik **[!UICONTROL View solution package details]**.

   ![](assets/image2015-11-18-11-3a12-3a8.png)

1. Klik op **[!UICONTROL Close]** als u alle details hebt gecontroleerd.

   ![](assets/image2015-10-9-14-3a57-3a3.png)

1. Klik weer op de [!UICONTROL Solution Information] pagina op **[!UICONTROL Next]** .

   ![](assets/image2015-3-26-9-3a55-3a17.png)

1. Controleer of de optie SDK is ingeschakeld. Klik op **[!UICONTROL Import]**.

   ![](assets/image2015-3-26-10-3a3-3a11.png)

1. Wacht tot het importeren is voltooid.

   >[!TIP]
   >
   >U moet pop-ups in uw browser inschakelen om het installatieproces te voltooien.

   ![](assets/image2014-12-11-10-3a41-3a5.png)

1. Download een logbestand (als u dat wilt) en klik op **[!UICONTROL Close]** .

   >[!NOTE]
   >
   >Je ziet mogelijk een bericht met de melding &quot;Marketo Lead Management completed with warning&quot; (Beheer van leads is voltooid met een waarschuwing). Dat wordt volledig verwacht.

   ![](assets/image2014-12-11-10-3a41-3a14.png)

1. Marketo Lead Management wordt nu op de pagina **[!UICONTROL All Solutions]** weergegeven.

   ![](assets/image2015-3-26-10-3a1-3a21.png)

1. Selecteer de Marketo-oplossing en klik op **[!UICONTROL Publish all Customizations]** .

   ![](assets/image2014-12-11-10-3a41-3a32.png)

>[!CAUTION]
>
>Als u een van de Marketo SDK Messaging Processes uitschakelt, wordt de installatie verbroken!

>[!MORELIKETHIS]
>
>[ Stap 2 van 3: Vorm de Gebruiker van de Synchronisatie voor Marketo (2013 On-Premises) ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-configure-2013.md){target="_blank"}
