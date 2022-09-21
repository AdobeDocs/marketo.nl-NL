---
unique-page-id: 10096683
description: ON24 Updates voor gebeurtenisregistratie - Marketo Docs - Productdocumentatie
title: ON24 Updates voor gebeurtenisregistratie
exl-id: 1d194ef2-b6ca-4e2d-b476-beb5bccd3c5f
source-git-commit: 0c6c119f5be6e2ac3db7d99f7e8623d8aaa3555c
workflow-type: tm+mt
source-wordcount: '284'
ht-degree: 0%

---

# ON24 Updates voor gebeurtenisregistratie {#on-event-registration-updates}

## Registranten handmatig goedkeuren {#manually-approving-registrants}

U kunt uw geregistreerde personen handmatig goedkeuren voordat u ze een bevestigingsbericht stuurt. Om dit te doen, zult u uw campagnes moeten vormen om deze extra stap te behandelen:

1. Voor de campagne voor registratieactivering:

   * Stel in de slimme lijst de trigger in op **Formulier wordt ingevuld**.
   * Stel in de Stroom de status in Progressie in op **In behandeling**.

1. Ga naar de gebeurtenis en klik op de knop **Leden** tab. Op dit tabblad worden alle personen weergegeven die het formulier hebben ingevuld. Hun status moet worden ingesteld op **In behandeling**.
1. Gebruik het filter boven aan het raster om alleen de personen met de status **In behandeling**.
1. Selecteer de personen die u wilt registreren (houd Shift ingedrukt en klik, houd Ctrl ingedrukt en klik of selecteer Alles).
1. Klik in het menu op **Status wijzigen**. Selecteren **Geregistreerd**, **Geweigerd** of een andere toepasselijke status.

## Personen met een registratiefout afhandelen {#handling-people-with-a-registration-error}

Als een persoon uiteindelijk niet wordt geregistreerd maar eerder aan de Fout van de Registratie van de status wordt geplaatst, is het niet te laat om terug te krijgen.

1. Van het lusje van Leden, filter de lijst van mensen met de status **Registratiefout**.
1. Controleer voordat u verdergaat of u het probleem hebt vastgesteld en opgelost met integratie (controleer of er geen fouten zijn opgetreden onder **Gebeurtenispartners** in Admin).
1. Nadat het probleem is opgelost, selecteert u alle personen met de status Registratiefout en wijzigt u hun status in **Geregistreerd**. Dit zal proberen om hen opnieuw bij ON24 te registreren.

## Lidstatus bijwerken vanuit ON24 {#updating-member-status-from-on}

Marketo haalt de aanwezigheidsinformatie elke nacht automatisch om 11 uur &#39;s middags in de Stille Oceaan. Als u de aanwezigheidsgegevens handmatig wilt bijwerken, klikt u op **Vernieuwen vanaf webinar-provider** krachtens **Gebeurtenishandelingen**.

>[!MORELIKETHIS]
>
>[Marketo ON24-adaptergebeurtenissen](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target=&quot;_blank&quot;}
