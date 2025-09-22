---
unique-page-id: 9437340
description: RTP implementeren met Tealium Tag Manager - Marketo Docs - Productdocumentatie
title: RTP implementeren met behulp van Tealium Tag Manager
exl-id: 7a099184-625c-46b2-a741-3bcdad0a238e
feature: Web Personalization
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 0%

---

# RTP implementeren met [!DNL Tealium] tagbeheer {#implementing-rtp-using-tealium-tag-manager}

Volg onderstaande installatie-instructies om uw RTP-tag te implementeren.

1. Meld u aan bij uw account voor [!DNL Tealium] tagbeheer.

1. Navigeer naar de tab [!UICONTROL Tags] en voeg de tab [!UICONTROL Tealium Custom Container Tag] toe, onder de tab [!UICONTROL Misc] van de Marketplace Codes.

1. In [!UICONTROL Title field], ga **Marketo RTP** in en klik **[!UICONTROL Finish]**.

1. Sla uw wijzigingen op.

   >[!NOTE]
   >
   >De nieuwe container hoeft nog niet te worden gepubliceerd.

1. Nadat het profiel is opgeslagen, klikt u op uw naam/e-mailadres in de rechterbovenhoek van de iQ-console van Tealium.

1. Klik in het menu [!UICONTROL Admin] op **[!UICONTROL Manage Templates]** onder [!UICONTROL Account Admin] .

1. Selecteer **[!UICONTROL Tealium Custom Container]: Marketo RTP** van de drop-down lijst om het malplaatje van de Markering te openen.

1. Meld u aan bij uw RTP-account.

1. Ga naar [!UICONTROL Account Settings] .

   >[!NOTE]
   >
   >Ga door met stap 11 als je je JavaScript-tag al van Support hebt ontvangen.

1. Zoek onder Domein het relevante domein en klik op **[!UICONTROL Generate Tag]** .

1. Kopieer de JavaScript-tag RTP en plak deze tussen [!UICONTROL Start Tag Library Code] en [!UICONTROL End Tag Library Code] in de sjabloon voor het thealprofiel.

   >[!NOTE]
   >
   >**Belangrijke Stappen**
   >
   >Verwijder de tags `<!-- RTP tag -->` en `<!-- End of RTP tag -->` uit de code die u in dit bestand plaatst.
   >
   >Verwijder `<script type='text/javascript'>` - en `</script>` -tags uit de code die u in dit bestand plaatst.

1. Klik op **[!UICONTROL Save Profile Template]** en publiceer uw nieuwe profiel.
