---
unique-page-id: 10096683
description: ON24 Updates voor gebeurtenisregistratie - Marketo Docs - Productdocumentatie
title: ON24 Updates voor gebeurtenisregistratie
exl-id: 1d194ef2-b6ca-4e2d-b476-beb5bccd3c5f
feature: Events
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '247'
ht-degree: 0%

---

# ON24 Updates voor gebeurtenisregistratie {#on-event-registration-updates}

## Registranten handmatig goedkeuren {#manually-approving-registrants}

U kunt uw geregistreerde personen handmatig goedkeuren voordat u ze een bevestigingsbericht stuurt. Om dit te doen, zult u uw campagnes moeten vormen om deze extra stap te behandelen:

1. Voor de campagne voor registratieactivering:

   * Stel in de [!UICONTROL Smart List] de trigger in op **[!UICONTROL Fills Out Form]** .
   * Stel in de stroom de waarde [!UICONTROL Status in Progression] in op **[!UICONTROL Pending Approval]** .

1. Ga naar de gebeurtenis en klik op de tab **[!UICONTROL Members]** . Op dit tabblad worden alle personen weergegeven die het formulier hebben ingevuld. Hun status zou aan **[!UICONTROL Pending Approval]** moeten worden geplaatst.
1. Gebruik het filter boven aan het raster om alleen de personen met de status **[!UICONTROL Pending Approval]** weer te geven.
1. Selecteer de personen die u wilt registreren (houd Shift ingedrukt en klik, houd Ctrl ingedrukt en klik of selecteer Alles).
1. Klik in het menu op **[!UICONTROL Change Status]** . Selecteer **[!UICONTROL Registered]**, **[!UICONTROL Rejected]** of een andere toepasselijke status.

## Personen met een registratiefout afhandelen {#handling-people-with-a-registration-error}

Als een persoon uiteindelijk niet wordt geregistreerd, maar wordt ingesteld op de status [!UICONTROL Registration Error] , is het niet te laat om te herstellen.

1. Filtreer op het tabblad [!UICONTROL Members] de lijst met personen met de status **[!UICONTROL Registration Error]** .
1. Voordat u verdergaat, moet u controleren of het probleem met integratie is vastgesteld en opgelost (controleer of er zich onder **[!UICONTROL Event Partners]** in Beheer geen fouten voordoen).
1. Nadat het probleem is opgelost, selecteert u alle personen met de status [!UICONTROL Registration Error] en wijzigt u hun status in **[!UICONTROL Registered]** . Dit zal proberen om hen opnieuw bij ON24 te registreren.

## Lidstatus bijwerken vanuit ON24 {#updating-member-status-from-on}

Marketo haalt de aanwezigheidsinformatie elke nacht automatisch om 11 uur &#39;s middags in de Stille Oceaan. Als u de aanwezigheidsgegevens handmatig wilt bijwerken, klikt u op **[!UICONTROL Refresh from Webinar Provider]** onder **[!UICONTROL Event Actions]** .

>[!MORELIKETHIS]
>
>[ Begrip Marketo ON24 adaptergebeurtenissen ](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target="_blank"}
