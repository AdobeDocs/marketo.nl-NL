---
unique-page-id: 42762511
description: Toewijzing organisatie Adobe instellen - Marketo-documenten - productdocumentatie
title: Toewijzing organisatie Adobe instellen
exl-id: d20be0d5-508f-40b9-a267-b6752643c311
feature: Integrations
source-git-commit: 5ef17e8c3988706a4d95332312ffb035f35bb269
workflow-type: tm+mt
source-wordcount: '220'
ht-degree: 1%

---

# Toewijzing organisatie Adobe instellen {#set-up-adobe-organization-mapping}

Voor synchronisatie met Adobe-toepassingen, zoals Audience Manager, de B2B CDP Marketo-connector, [!DNL Dynamic Chat], enzovoort, moet u eerst uw Adobe IMS Org-referenties in het Marketo Engage invoeren.

>[!NOTE]
>
>* Een implementatie van een Marketo-instantie die klaar is voor HIPAA, kan deze integratie niet gebruiken.
>* Marketo en uw andere Adobe-toepassingen moeten zich op dezelfde org bevinden, anders werkt de integratie niet.

>[!IMPORTANT]
>
>Voor degenen die aan het Bedrijfs Platform van de Adobe en Systeem van Identity Management worden geregistreerd, zal identiteitskaart van de Org verbonden aan het abonnement reeds bevolkt zijn en is een read-only gebied. De stappen in dit artikel zijn daarom niet van toepassing.

1. Klik in Marketo op **[!UICONTROL Admin]**.

   ![](assets/set-up-adobe-experience-cloud-audience-sharing-1.png)

1. Klik onder Integratie op **[!UICONTROL Adobe Organization Mapping]**.

   ![](assets/set-up-adobe-experience-cloud-audience-sharing-2.png)

1. Klik op **[!UICONTROL Edit]**.

   ![](assets/set-up-adobe-experience-cloud-audience-sharing-3.png)

1. Voer uw Adobe IMS-organisatie-id in (leer hoe u dat kunt vinden) [hier](https://experienceleague.adobe.com/docs/control-panel/using/faq.html?lang=nl-NL){target="_blank"}) en klik op **[!UICONTROL OK]**.

   ![](assets/set-up-adobe-experience-cloud-audience-sharing-4.png)

1. Klik op **[!UICONTROL Confirm]**.

   ![](assets/set-up-adobe-experience-cloud-audience-sharing-5.png)

1. Klik op **[!UICONTROL Close]**.

   ![](assets/set-up-adobe-experience-cloud-audience-sharing-6.png)

   >[!IMPORTANT]
   >
   >Om veiligheidsredenen, moet u een Admin van de Org voor de Organisatie van de Adobe zijn waaraan u wilt in kaart brengen. Als je dat niet bent, zal de actie mislukken. Bovendien moeten de gebruiker van de Adobe en de Gebruiker van Marketo het zelfde e-mailadres gebruiken wanneer het programma openen.

1. Als je _niet_ al aangemeld, wordt een pop-up weergegeven in een nieuw tabblad/venster. Meld u aan bij de org van uw Adobe (deze bewerking valideert de toegang tot de org).

En dat is het! U kunt nu [delen van publieksgegevens](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/send-a-list-to-adobe-experience-cloud.md){target="_blank"} to, or [sync an audience](/help/marketo/product-docs/adobe-experience-cloud-integrations/sync-an-audience-from-adobe-experience-cloud.md){target="_blank"} uit Adobe Experience Cloud.
