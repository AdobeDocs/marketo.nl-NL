---
unique-page-id: 3571805
description: Stap 1 van 3 - Installeer de Marketo-oplossing (2011 op locatie) - Marketo Docs - Productdocumentatie
title: Stap 1 van 3 - Installeer de Marketo-oplossing (2011 op locatie)
exl-id: 6e559b10-5273-4dc2-b98d-49c509cbeff7
feature: Microsoft Dynamics
source-git-commit: e3f61755dccd9bea1378a429fc428b440fc3ecb4
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 1%

---

# Stap 1 van 3: Installeer de Marketo-oplossing (2011 op locatie) {#step-of-install-the-marketo-solution-on-premises}

Voordat u Microsoft Dynamics On-Premises en Marketo Engage kunt synchroniseren, moet u eerst de Marketo-oplossing installeren in Dynamics.

>[!NOTE]
>
>Nadat u Marketo synchroniseert met een CRM, kunt u geen nieuwe synchronisatie uitvoeren zonder de instantie te vervangen.

>[!PREREQUISITES]
>
>U moet [ Internet hebben dat Plaatsing ](https://learn.microsoft.com/en-us/dynamics365/customerengagement/on-premises/deploy/configure-an-internet-facing-deployment){target="_blank"} (IFD) met [ de Actieve Diensten van de Federatie van de Folder ](https://msdn.microsoft.com/en-us/library/bb897402.aspx){target="_blank"} 2.0, 2.1 of 3.0 (ADFS) gevormd. **Nota**: Het IFD document downloadt automatisch wanneer u de verbinding klikt.
>
>[ Download de Oplossing van het Beheer van de Lood van Marketo ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"} alvorens u begint.

>[!NOTE]
>
>{de Vereiste toestemmingen van Admin van de Dynamica 0} **.**
>
>U hebt CRM-beheerdersrechten nodig om deze synchronisatie uit te voeren.

1. Meld u aan bij Dynamiek en selecteer **[!UICONTROL Settings]** in het menu linksonder.

   ![](assets/image2015-4-2-11-3a32-3a53.png)

1. Selecteer **[!UICONTROL Solutions]** in de structuur.

   ![](assets/image2015-4-2-11-3a35-3a28.png)

1. Klik op **[!UICONTROL Import]**.

   ![](assets/image2015-4-2-11-3a37-3a33.png)

1. Klik op **[!UICONTROL Browse]**. Selecteer de oplossing van het Beheer van de Lood van Marketo u [&#128279;](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"} downloadde. Klik op **[!UICONTROL Next]**.

   ![](assets/image2015-4-2-11-3a40-3a33.png)

1. Bekijk de Informatie van de Oplossing en klik **[!UICONTROL View solution package details]**.

   ![](assets/image2015-11-18-11-3a12-3a8.png)

1. Klik op **[!UICONTROL Close]** als u alle details hebt gecontroleerd.

   ![](assets/image2015-10-9-14-3a57-3a3.png)

1. Klik op de pagina Oplossingsgegevens op **[!UICONTROL Next]** .

   ![](assets/image2015-4-2-11-3a41-3a48.png)

1. Controleer of het selectievakje voor de optie SDK-bericht is ingeschakeld. Klik op **[!UICONTROL Next]**.

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

1. Het Beheer van de Lood van Marketo zal nu op **Alle Oplossingen** pagina verschijnen.

   ![](assets/image2015-4-2-11-3a46-3a55.png)

1. Selecteer Marketo Lead Management en klik op **[!UICONTROL Publish All Customizations]** .

   ![](assets/image2015-4-2-11-3a48-3a21.png)

>[!CAUTION]
>
>Als u een van de Marketo SDK Messaging Processes uitschakelt, wordt de installatie verbroken!

>[!MORELIKETHIS]
>
>[ Stap 2 van 3: De Gebruiker van de Synchronisatie van Marketo van de opstelling in Dynamiek (2011 op-Premises) ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-set-up-2011.md){target="_blank"}
