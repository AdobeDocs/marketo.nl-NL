---
unique-page-id: 12981050
description: Verkoopsjabloon vergrendelen - Marketo-documenten - productdocumentatie
title: Verkoopsjabloon vergrendelen
exl-id: 005dde5d-ed60-444b-b7a3-b91be72a0151
feature: Marketo Sales Insights
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '183'
ht-degree: 1%

---

# Verkoopsjabloon vergrendelen {#lock-sales-template}

Om de gebruikers van CRM te verhinderen verkoopmalplaatjes uit te geven, kunnen de beheerders de capaciteit toelaten om malplaatjes te sluiten, die dan gebruikers toestaan om malplaatjes individueel van de e-mailredacteur te sluiten.

>[!CAUTION]
>
>Deze functie werkt alleen voor [!DNL Salesforce] en is niet compatibel met [!DNL Microsoft Dynamics] of andere CRM&#39;s. Sjablonen die via de plug-ins [!DNL Outlook] of Gmail worden geopend, worden niet vergrendeld omdat de editor niet door Marketo wordt beheerd.

## Sjabloon vergrendelen inschakelen {#enable-lock-template}

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

1. Ga naar **[!UICONTROL Admin]** en klik vervolgens op **[!UICONTROL Sales Insight]** .

   ![](assets/1.png)

1. Klik onder **[!UICONTROL Settings]** op **[!UICONTROL Edit]** .

   ![](assets/2.png)

1. Schakel **[!UICONTROL Enable ability to lock templates]** in. Klik op **[!UICONTROL Save]**.

   ![](assets/image2017-10-9-8-3a19-3a45.png)

>[!NOTE]
>
>Dit selectievakje is standaard ingeschakeld en de mogelijkheid sjablonen te vergrendelen is ingeschakeld. Als u de optie uitschakelt, wordt de functie voor vergrendelingssjablonen in de e-maileditor uitgeschakeld.

>[!NOTE]
>
>Het veranderen van dit het plaatsen als admin zal **niet** met terugwerkende kracht bestaande malplaatjes beïnvloeden; d.w.z., zal het hen niet automatisch sluiten.

## Sjabloon vergrendelen in de e-maileditor {#lock-template-in-the-email-editor}

1. Selecteer het e-mailbericht dat u wilt vergrendelen en klik op **[!UICONTROL Edit Draft]** .

   ![](assets/5.png)

1. Klik in de e-maileditor op **[!UICONTROL Email Settings]** .

   ![](assets/6.png)

1. Controleer **[!UICONTROL Publish to Marketo Sales Insight]** als het nog niet is gecontroleerd. U kunt nu **[!UICONTROL Allow CRM user to edit email]** uitschakelen om de sjabloon te vergrendelen. Klik op **[!UICONTROL Save]**.

   ![](assets/7.png)

   >[!NOTE]
   >
   >Dit selectievakje is standaard ingeschakeld en CRM-gebruikers mogen e-mailberichten bewerken.
