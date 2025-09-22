---
unique-page-id: 7504736
description: Marketo for Microsoft Dynamics 2015 op locatie installeren Stap 1 van 3 - Marketo Docs - Productdocumentatie
title: Marketo voor Microsoft Dynamics 2015 op locatie installeren Stap 1 van 3
exl-id: c9b6d365-15c1-4eff-938c-8433b1fe7f24
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '261'
ht-degree: 1%

---

# Stap 1 van 3: Sync User for Marketo configureren (2015 op voorgrond) {#step-of-configure-sync-user-for-marketo-on-premises-2015}

Voordat u [!DNL Microsoft Dynamics] 2015 On-Premises (Op locatie) kunt synchroniseren met Marketo, moet u eerst de Marketo-oplossing installeren in [!DNL Dynamics] .

>[!NOTE]
>
>Nadat u Marketo synchroniseert met een CRM, kunt u geen nieuwe CRM synchroniseren met de bestaande Marketo-instantie.

>[!PREREQUISITES]
>
>Als u [!DNL Microsoft Dynamics] op-Voorwendsel gebruikt, moet u [ Internet Facing Plaatsing ](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701) (IFD) met [ de Actieve Diensten van de Federatie van de Folder hebben ](https://msdn.microsoft.com/en-us/library/bb897402.aspx) 2.0+ (ADFS) gevormd. Opmerking: het IFD-document wordt automatisch gedownload wanneer u op de koppeling klikt.
>
>[ Download de Oplossing van het Beheer van de Lood van Marketo ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"} alvorens u begint.

>[!NOTE]
>
>{de Vereiste toestemmingen van Admin van de Dynamica 0} **.**
>
>U hebt CRM-beheerdersrechten nodig om deze synchronisatie uit te voeren.

1. Meld u aan bij **[!DNL Dynamics].** Klik op de vervolgkeuzelijst **[!UICONTROL Microsoft Dynamics CRM]** en selecteer **[!UICONTROL Settings]** .

   ![](assets/image2015-3-19-8-33-29.png)

1. Selecteer onder **[!UICONTROL Settings]** de optie **[!UICONTROL Solutions]** .

   ![](assets/image2015-3-19-8-33-3.png)

1. Klik op **[!UICONTROL Import]**.

   ![](assets/image2015-3-19-8-34-8.png)

1. Klik **[!UICONTROL Browse]** en selecteer de oplossing u [&#128279;](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md) downloadde. Klik op **[!UICONTROL Next]**.

   ![](assets/image2015-3-19-9-20-56.png)

1. Bekijk [!UICONTROL Solution Information] en klik **[!UICONTROL View solution package details]**.

   ![](assets/image2015-11-18-11-12-8.png)

1. Klik op **[!UICONTROL Close]** als u alle details hebt gecontroleerd.

   ![](assets/step6.png)

1. Klik weer op de [!UICONTROL Solution Information] pagina op **[!UICONTROL Next]** .

   ![](assets/image2015-3-19-9-21-50.png)

1. Controleer of het selectievakje SDK is ingeschakeld. Klik op **[!UICONTROL Import]**.

   ![](assets/image2015-3-19-9-19-12.png)

1. Wacht tot het importeren is voltooid.

   >[!TIP]
   >
   >U moet pop-ups in uw browser inschakelen om het installatieproces te voltooien.

   ![](assets/image2015-3-11-11-34-9.png)

1. Download een logbestand (als u dat wilt) en klik op **[!UICONTROL Close]** .

   >[!NOTE]
   >
   >Je ziet mogelijk een bericht met de melding &quot;Marketo Lead Management completed with warning&quot; (Beheer van leads is voltooid met een waarschuwing). Dat wordt volledig verwacht.

   ![](assets/image2015-3-13-9-54-39.png)

1. Marketo Lead Management wordt nu op de pagina **[!UICONTROL All Solutions]** weergegeven.

   ![](assets/image2015-3-19-8-40-38.png)

1. Selecteer de Marketo-oplossing en klik op **[!UICONTROL Publish All Customizations]** .

   ![](assets/image2015-3-19-8-41-21.png)

   Mooi werk! De installatie is voltooid.

   >[!CAUTION]
   >
   >Als u een van de Marketo SDK Messaging Processes uitschakelt, wordt de installatie verbroken!

   >[!MORELIKETHIS]
   >
   >[ installeer Marketo voor  [!DNL Microsoft Dynamics]  2015 On-Premises Stap 2 van 3 ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-set-up-2015.md)
