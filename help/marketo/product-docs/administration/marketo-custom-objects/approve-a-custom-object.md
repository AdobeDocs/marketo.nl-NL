---
unique-page-id: 10094188
description: Een aangepast object goedkeuren - Marketo Docs - Productdocumentatie
title: Een aangepast object goedkeuren
exl-id: 8bae94df-91fe-4722-8c75-c26df882c65d
feature: Custom Objects
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 0%

---

# Een aangepast object goedkeuren {#approve-a-custom-object}

U moet een aangepast object goedkeuren voordat u het kunt gebruiken. Het proces is iets anders voor nieuwe aangepaste objecten en objecten die u hebt bewerkt.

## Een nieuw aangepast object goedkeuren {#approve-a-new-custom-object}

U hebt een gloednieuw aangepast object gemaakt. Hier is hoe je het goedkeurt.

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/approve-a-custom-object-1.png)

1. Klik op **[!UICONTROL Marketo Custom Objects]**.

   ![](assets/approve-a-custom-object-2.png)

1. Selecteer een object in de status Concept.

   ![](assets/approve-a-custom-object-3.png)

1. Klik op de vervolgkeuzelijst **[!UICONTROL Custom Object Actions]** en selecteer **[!UICONTROL Approve Object]** .

   ![](assets/approve-a-custom-object-4.png)

1. De status verandert in [!UICONTROL Approved] .

   ![](assets/approve-a-custom-object-5.png)

   >[!NOTE]
   >
   >Een douanevoorwerp dat op a _wordt gebruikt één-aan-vele structuur_ moet minstens één dedupe gebied, een verbindingsgebied, een verbonden objecten naam, en een verbonden te goedkeuren gebiedsnaam hebben.
   >
   >Een douanevoorwerp dat in a _wordt gebruikt veel-aan-vele structuur_ **vereist geen** verbindingsgebied, verbonden objecten naam, of een verbonden gebiedsnaam wanneer u het goedkeurt (omdat zij in het intermediaire voorwerp) leven.
   >
   >Een douanevoorwerp dat als _wordt gebruikt intermediair voorwerp_ vereist een verbindingsgebied, een verbonden objecten naam, en een verbonden gebiedsnaam maar **vereist geen** dedupe gebied.
   >
   >Zie [&#x200B; Begrijpend de Voorwerpen van de Douane van Marketo &#x200B;](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md) voor meer informatie.

Dat is het! U kunt nu uw aangepaste object selecteren met de beperkingen van de filters en triggers die u in uw campagnes wilt gebruiken.

## Een bewerkt aangepast object goedkeuren {#approve-an-edited-custom-object}

Nadat u een goedgekeurd aangepast object hebt bewerkt, moet u het concept goedkeuren om het aangepaste object terug te brengen naar de status Goedgekeurd.

1. Wanneer u een reeds goedgekeurd douanevoorwerp uitgeeft, ontvangt het een [!UICONTROL Approved with Draft] staat.

   ![](assets/approve-a-custom-object-6.png)

1. Als u klaar bent om het concept goed te keuren, klikt u op de vervolgkeuzelijst **[!UICONTROL Custom Object Actions]** en selecteert u **[!UICONTROL Approve Object]** .

   ![](assets/approve-a-custom-object-7.png)

1. In een voorvertoning worden de items weergegeven die in het concept zijn gewijzigd. Klik op **[!UICONTROL Approve]**.

   ![](assets/approve-a-custom-object-8.png)
