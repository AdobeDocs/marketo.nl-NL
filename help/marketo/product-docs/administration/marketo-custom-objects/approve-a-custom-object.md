---
unique-page-id: 10094188
description: Een aangepast object goedkeuren - Marketo Docs - Productdocumentatie
title: Een aangepast object goedkeuren
exl-id: 8bae94df-91fe-4722-8c75-c26df882c65d
feature: Custom Objects
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 0%

---

# Een aangepast object goedkeuren {#approve-a-custom-object}

U moet een aangepast object goedkeuren voordat u het kunt gebruiken. Het proces is iets anders voor nieuwe aangepaste objecten en objecten die u hebt bewerkt.

## Een nieuw aangepast object goedkeuren {#approve-a-new-custom-object}

U hebt een gloednieuw aangepast object gemaakt. Hier is hoe je het goedkeurt.

1. Ga naar de **[!UICONTROL Admin]** gebied.

   ![](assets/approve-a-custom-object-1.png)

1. Klik op **[!UICONTROL Marketo Custom Objects]**.

   ![](assets/approve-a-custom-object-2.png)

1. Selecteer een object in de status Concept.

   ![](assets/approve-a-custom-object-3.png)

1. Klik op de knop **[!UICONTROL Custom Object Actions]** vervolgkeuzelijst en selecteer **[!UICONTROL Approve Object]**.

   ![](assets/approve-a-custom-object-4.png)

1. De status verandert in [!UICONTROL Approved].

   ![](assets/approve-a-custom-object-5.png)

   >[!NOTE]
   >
   >Een aangepast object dat in een _een-op-een-structuur_ moet ten minste één deduplicerveld, een koppelingsveld, een naam van een gekoppeld object en een gekoppelde veldnaam hebben die moeten worden goedgekeurd.
   >
   >Een aangepast object dat in een _veel-op-veel-structuur_ **niet** hebt een koppelingsveld, een naam van een gekoppeld object of een gekoppelde veldnaam nodig wanneer u deze goedkeurt (omdat deze in het intermediaire object staan).
   >
   >Een aangepast object dat als een _tussenliggend object_ vereist een koppelingsveld, een naam van een gekoppeld object en een naam van een gekoppeld veld, maar **niet** vereist een deduplicatieveld.
   >
   >Zie [Aangepaste Marketo-objecten begrijpen](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md) voor meer informatie .

Dat is het! U kunt nu uw aangepaste object selecteren met de beperkingen van de filters en triggers die u in uw campagnes wilt gebruiken.

## Een bewerkt aangepast object goedkeuren {#approve-an-edited-custom-object}

Nadat u een goedgekeurd aangepast object hebt bewerkt, moet u het concept goedkeuren om het aangepaste object terug te brengen naar de status Goedgekeurd.

1. Wanneer u een reeds goedgekeurd douanevoorwerp uitgeeft, ontvangt het [!UICONTROL Approved with Draft] status.

   ![](assets/approve-a-custom-object-6.png)

1. Als u klaar bent om het concept goed te keuren, klikt u op de knop **[!UICONTROL Custom Object Actions]** vervolgkeuzelijst en selecteer **[!UICONTROL Approve Object]**.

   ![](assets/approve-a-custom-object-7.png)

1. In een voorvertoning worden de gewijzigde items in het concept weergegeven. Klik op **[!UICONTROL Approve]**.

   ![](assets/approve-a-custom-object-8.png)
