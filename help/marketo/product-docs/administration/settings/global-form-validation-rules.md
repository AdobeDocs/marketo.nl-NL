---
description: Algemene regels voor formuliervalidatie - Marketo-documenten - productdocumentatie
title: Algemene regels voor formuliervalidatie
exl-id: a44db893-00b5-40d2-8be3-41d52b2fd7b5
source-git-commit: b71729a678ff4a676bb60803d845d0a44118f7e5
workflow-type: tm+mt
source-wordcount: '232'
ht-degree: 1%

---

# Algemene regels voor formuliervalidatie {#global-form-validation-rules}

Met deze functie kunt u blokkeren dat bepaalde domeinen naar Marketo Engage-formulieren worden verzonden.

## Hoe te om Toegang toe te laten {#how-to-enable-access}

Voordat u deze functie kunt gebruiken, moet u de machtigingen per gewenste rol inschakelen.

1. Klik in Marketo op **[!UICONTROL Admin]**.

   ![](assets/global-form-validation-rules-1.png)

1. Klik op **[!UICONTROL Users & Roles]**.

   ![](assets/global-form-validation-rules-2.png)

1. Klik op de knop **[!UICONTROL Roles]** tab.

   ![](assets/global-form-validation-rules-3.png)

1. Dubbelklik op de rol waaraan u machtigingen wilt verlenen.

   ![](assets/global-form-validation-rules-4.png)

1. Klik op de knop **+** ondertekenen naast Access Admin.

   ![](assets/global-form-validation-rules-5.png)

1. Omlaag schuiven en selecteren **[!UICONTROL Access Form Validation Rules]** en klik op **[!UICONTROL Save]**.

   ![](assets/global-form-validation-rules-6.png)

## Nieuwe regel voor formuliervalidatie maken {#create-new-form-validation-rule}

>[!IMPORTANT]
>
>Deze regels zijn van toepassing op alle formulieren in uw Marketo Engage-abonnement(en).

1. Klik in Marketo op **[!UICONTROL Admin]**.

   ![](assets/global-form-validation-rules-7.png)

1. Klik op **[!UICONTROL Global Form Validation Rule]**.

   ![](assets/global-form-validation-rules-8.png)

1. Klik op **[!UICONTROL New Form Validation Rule]**.

   ![](assets/global-form-validation-rules-9.png)

   >[!NOTE]
   >
   >Met de vervolgkeuzelijst Handelingen formuliervalidatieregel kunt u bestaande regels verwijderen of bewerken.

1. Geef de regel een naam, geef deze een optionele beschrijving en voer het foutbericht in dat de bezoekers van het formulier moeten zien. Voer in het vak Regels het domein of de domeinen in die u wilt blokkeren. Selecteer **[!UICONTROL Activate Rule]** en klik op **[!UICONTROL Create]**.

   ![](assets/global-form-validation-rules-10.png)

>[!NOTE]
>
>Marketo Engage heeft een bepaalde lijst van gewezen personen van vrije consument e-maildomeinen die worden geblokkeerd wanneer het gebruiken van onze vooraf geladen &quot;Lijst van gewezen personen van het Domein van de Consumenten E-mail&quot;regel. [Deze lijst hier weergeven](/help/marketo/product-docs/administration/settings/assets/freemaildomains.csv).

## Toegang per formulier uitschakelen{#how-to-disable-access-per-form}

Zodra deze optie is ingeschakeld, zijn de regels van toepassing op alle formulieren. Als u echter een formulier met specifieke vereisten hebt en u wilt dat niets wordt afgewezen, kunt u [!UICONTROL Global Form Validation Rules] in de instellingen van het formulier.

1. Klik in het gewenste formulier op **[!UICONTROL Form Settings]** vervolgens **[!UICONTROL Settings]**.

   ![](assets/global-form-validation-rules-11.png)

1. Klik op de knop **[!UICONTROL Global Form Validation Rules]** vervolgkeuzelijst en kies **[!UICONTROL Disabled]**.

   ![](assets/global-form-validation-rules-12.png)

Als u het formulier goedkeurt en plaatst, negeert het uw [!UICONTROL Global Form Validation Rules].
