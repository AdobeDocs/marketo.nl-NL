---
unique-page-id: 3571805
description: Stap 1 van 3 - Installeer de Marketo-oplossing (2011 op locatie) - Marketo Docs - Productdocumentatie
title: Stap 1 van 3 - Installeer de Marketo-oplossing (2011 op locatie)
exl-id: 6e559b10-5273-4dc2-b98d-49c509cbeff7
feature: Microsoft Dynamics
source-git-commit: 821d69736b1cbeac0c80718c58a7a3c471387545
workflow-type: tm+mt
source-wordcount: '258'
ht-degree: 1%

---

# Stap 1 van 3: Installeer de Marketo-oplossing (2011 op locatie) {#step-of-install-the-marketo-solution-on-premises}

Voordat u Microsoft Dynamics On-Premises en Marketo Engage kunt synchroniseren, moet u eerst de Marketo-oplossing installeren in Dynamics.

>[!NOTE]
>
>Nadat u Marketo synchroniseert met een CRM, kunt u geen nieuwe synchronisatie uitvoeren zonder de instantie te vervangen.

>[!PREREQUISITES]
>
>U moet [Implementatie van internetbestanden](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701){target="_blank"} (IFD) with [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx){target="_blank"} 2.0, 2.1 of 3.0 (ADFS) geconfigureerd. **Opmerking**: Het IFD-document wordt automatisch gedownload wanneer u op de koppeling klikt.
>
>[Download de Marketo Lead Management Solution](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"} voordat u begint.

>[!NOTE]
>
>**Beheerdersrechten voor dynamiek vereist**.
>
>U hebt CRM-beheerdersrechten nodig om deze synchronisatie uit te voeren.

1. Log in bij Dynamiek en selecteer **[!UICONTROL Settings]** in het linker onderste menu.

   ![](assets/image2015-4-2-11-3a32-3a53.png)

1. Selecteren **[!UICONTROL Solutions]** in de boom.

   ![](assets/image2015-4-2-11-3a35-3a28.png)

1. Klik op **[!UICONTROL Import]**.

   ![](assets/image2015-4-2-11-3a37-3a33.png)

1. Klik op **[!UICONTROL Browse]**. Selecteer de Marketo Lead Management-oplossing [gedownload](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"}. Klik op **[!UICONTROL Next]**.

   ![](assets/image2015-4-2-11-3a40-3a33.png)

1. Bekijk de Informatie van de Oplossing en klik **[!UICONTROL View solution package details]**.

   ![](assets/image2015-11-18-11-3a12-3a8.png)

1. Wanneer u alle details hebt gecontroleerd, klikt u op **[!UICONTROL Close]**.

   ![](assets/image2015-10-9-14-3a57-3a3.png)

1. Terug op de pagina van de Informatie van de Oplossing, klik **[!UICONTROL Next]**.

   ![](assets/image2015-4-2-11-3a41-3a48.png)

1. Controleer of het selectievakje voor de optie voor SDK-berichten is ingeschakeld. Klik op **[!UICONTROL Next]**.

   ![](assets/image2015-4-2-11-3a42-3a37.png)

   >[!TIP]
   >
   >U moet pop-ups in uw browser inschakelen om het installatieproces te voltooien.

1. Wacht nu tot het importeren is voltooid. Opstaan en wat stretches uitvoeren.

   ![](assets/image2015-4-2-11-3a43-3a51.png)

1. Klik op **[!UICONTROL Close]**.

   >[!NOTE]
   >
   >Je ziet mogelijk een bericht met de melding &quot;Marketo Lead Management completed with warning&quot; (Beheer van leads is voltooid met een waarschuwing). Dat wordt volledig verwacht.

   ![](assets/image2015-4-2-11-3a44-3a44.png)

1. Marketo Lead Management wordt nu weergegeven op het tabblad **Alle oplossingen** pagina.

   ![](assets/image2015-4-2-11-3a46-3a55.png)

1. Selecteer Marketo Lead Management en klik op **[!UICONTROL Publish All Customizations]**.

   ![](assets/image2015-4-2-11-3a48-3a21.png)

>[!CAUTION]
>
>Als u een van de Marketo SDK Messaging Processes uitschakelt, wordt de installatie verbroken!

>[!MORELIKETHIS]
>
>[Stap 2 van 3: Marketo Sync User instellen in Dynamics (2011 op locatie)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-set-up-2011.md){target="_blank"}
