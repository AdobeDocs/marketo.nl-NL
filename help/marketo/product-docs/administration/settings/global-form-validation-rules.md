---
description: Algemene regels voor formuliervalidatie - Marketo-documenten - productdocumentatie
title: Algemene regels voor formuliervalidatie
exl-id: a44db893-00b5-40d2-8be3-41d52b2fd7b5
feature: Administration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '240'
ht-degree: 1%

---

# Algemene regels voor formuliervalidatie {#global-form-validation-rules}

Met deze functie kunt u blokkeren dat specifieke domeinen naar Marketo Engage-formulieren verzenden.

## Hoe te om Toegang toe te laten {#how-to-enable-access}

Voordat u deze functie kunt gebruiken, moet u de machtigingen per gewenste rol inschakelen.

1. Klik in Marketo op **[!UICONTROL Admin]** .

   ![](assets/global-form-validation-rules-1.png)

1. Klik op **[!UICONTROL Users & Roles]**.

   ![](assets/global-form-validation-rules-2.png)

1. Klik op de tab **[!UICONTROL Roles]** .

   ![](assets/global-form-validation-rules-3.png)

1. Dubbelklik op de rol waaraan u machtigingen wilt verlenen.

   ![](assets/global-form-validation-rules-4.png)

1. Klik **+** teken naast **Admin van de Toegang**.

   ![](assets/global-form-validation-rules-5.png)

1. Schuif omlaag, selecteer **[!UICONTROL Access Form Validation Rules]** en klik op **[!UICONTROL Save]** .

   ![](assets/global-form-validation-rules-6.png)

## Nieuwe regel voor formuliervalidatie maken {#create-new-form-validation-rule}

>[!IMPORTANT]
>
>Deze regels gelden voor alle formulieren in uw Marketo Engage-abonnement(en).

1. Klik in Marketo op **[!UICONTROL Admin]** .

   ![](assets/global-form-validation-rules-7.png)

1. Klik op **[!UICONTROL Global Form Validation Rule]**.

   ![](assets/global-form-validation-rules-8.png)

1. Klik op **[!UICONTROL New Form Validation Rule]**.

   ![](assets/global-form-validation-rules-9.png)

   >[!NOTE]
   >
   >Met de vervolgkeuzelijst [!UICONTROL Form Validation Rule Actions] kunt u bestaande regels verwijderen of bewerken.

1. Geef de regel een naam, geef deze een optionele beschrijving en voer het foutbericht in dat de bezoekers van het formulier moeten zien. Voer in het vak Regels de domeinen in die u wilt blokkeren, selecteer **[!UICONTROL Activate Rule]** en klik op **[!UICONTROL Create]** .

   ![](assets/global-form-validation-rules-10.png)

>[!NOTE]
>
>Marketo Engage heeft een gedefinieerde lijst van gewezen personen met gratis e-maildomeinen voor consumenten die worden geblokkeerd wanneer onze vooraf geladen regel &#39;Consumer Email Domain Lijst van gewezen personen&#39; wordt gebruikt. [ Mening die lijst hier ](/help/marketo/product-docs/administration/settings/assets/freemaildomains.csv) (om te downloaden, zorg ervoor uw browser bijgewerkt is en downloads kan goedkeuren).

## Toegang per formulier uitschakelen{#how-to-disable-access-per-form}

Zodra deze optie is ingeschakeld, zijn de regels van toepassing op alle formulieren. Als u echter een formulier met specifieke vereisten hebt en u wilt niets negeren, kunt u [!UICONTROL Global Form Validation Rules] uitschakelen in de formulierinstellingen.

1. Klik in het gewenste formulier op **[!UICONTROL Form Settings]** en vervolgens op **[!UICONTROL Settings]** .

   ![](assets/global-form-validation-rules-11.png)

1. Klik op de vervolgkeuzelijst **[!UICONTROL Global Form Validation Rules]** en kies **[!UICONTROL Disabled]** .

   ![](assets/global-form-validation-rules-12.png)

Wanneer u het formulier goedkeurt en plaatst, wordt uw [!UICONTROL Global Form Validation Rules] genegeerd.
