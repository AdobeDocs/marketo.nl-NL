---
unique-page-id: 10094188
description: Een aangepast object goedkeuren - Marketo Docs - Productdocumentatie
title: Een aangepast object goedkeuren
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---


# Een aangepast object goedkeuren {#approve-a-custom-object}

U moet een aangepast object goedkeuren voordat u het kunt gebruiken. Het proces is iets anders voor nieuwe aangepaste objecten en objecten die u hebt bewerkt.

## Een nieuw aangepast object goedkeuren {#approve-a-new-custom-object}

U hebt een gloednieuw aangepast object gemaakt. Hier is hoe je het goedkeurt.

1. Klik in Admin op **Marketo Custom Objects** en selecteer een object in de status Concept.

   ![](assets/one.png)

1. Klik op de vervolgkeuzelijst **Aangepaste-objectacties** en selecteer **Object** goedkeuren.

   ![](assets/two.png)

1. De status verandert in Goedgekeurd.

   ![](assets/three.png)

   >[!NOTE]
   >
   >Een aangepast object dat in een *een-op-veel-structuur* wordt gebruikt, moet ten minste één deduplicatieveld, een koppelingsveld, een naam van een gekoppeld object en een gekoppelde veldnaam hebben die moeten worden goedgekeurd.
   >
   >
   >Een aangepast object dat in een structuur ** met veel objecten wordt gebruikt, heeft **geen** koppelingsveld, naam van een gekoppeld object of naam van een gekoppeld veld nodig wanneer u het goedkeurt (omdat het object in het intermediaire object staat).
   >
   >
   >Een aangepast object dat als een *intermediair object* wordt gebruikt, vereist een koppelingsveld, een gekoppelde objectnaam en een gekoppelde veldnaam, maar **heeft geen** deduplicatieveld nodig.
   >
   >
   >Zie [Inzicht in aangepaste objecten](understanding-marketo-custom-objects.md) markeren voor meer informatie.

Dat is het! U kunt nu uw aangepaste object selecteren met de beperkingen van de filters en triggers die u in uw campagnes wilt gebruiken.

## Een bewerkt aangepast object goedkeuren {#approve-an-edited-custom-object}

Nadat u een goedgekeurd aangepast object hebt bewerkt, moet u het concept goedkeuren om het aangepaste object terug te brengen naar de status Goedgekeurd.

1. Wanneer u een reeds goedgekeurd douanevoorwerp uitgeeft, ontvangt het een Goedgekeurd met de staat van het Ontwerp.

   ![](assets/four.png)

1. Als u klaar bent om het concept goed te keuren, klikt u op de vervolgkeuzelijst **Aangepaste objectacties** en selecteert u **Object** goedkeuren.

   ![](assets/five-1.png)

1. In een voorvertoning worden de gewijzigde items in het concept weergegeven. Klik op **Goedkeuren**.

   ![](assets/six-1.png)

