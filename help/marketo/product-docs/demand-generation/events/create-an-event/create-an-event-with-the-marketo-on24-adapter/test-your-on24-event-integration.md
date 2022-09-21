---
unique-page-id: 10096677
description: Test uw ON24-gebeurtenisintegratie - Marketo Docs - productdocumentatie
title: ON24-gebeurtenisintegratie testen
exl-id: 8326b81e-abf7-4615-9a0b-b0a579be8bb8
source-git-commit: 0c6c119f5be6e2ac3db7d99f7e8623d8aaa3555c
workflow-type: tm+mt
source-wordcount: '195'
ht-degree: 0%

---

# ON24-gebeurtenisintegratie testen {#test-your-on-event-integration}

Zorg ervoor dat u de integratie van uw gebeurtenis grondig test.

## Aanbevolen testsequentie voordat u de eerste campagne uitvoert {#recommended-test-sequence-before-running-your-first-campaign}

1. Vul het registratieformulier van de gebeurtenis in en gebruik een geldig e-mailadres om het te testen.
1. Bevestig dat de testnaam wordt weergegeven met een **Geregistreerd** status in het Membership-raster van uw Marketo-gebeurtenis.
1. Bevestig ook de testnaam toont zoals **Geregistreerd** in ON24.
1. Bevestig dat het geldige e-mailadres dat u hebt gebruikt om de testnaam te registreren, een bevestigingsbericht naar de gebeurtenis heeft ontvangen en dat de unieke URL in de e-mail is opgelost.

   >[!NOTE]
   >
   >U moet de opdracht `{{member.webinar url}}` in uw bevestigingsbericht om de unieke URL in de e-mail van elke registrant weer te geven.

## Na de gebeurtenis {#after-the-event}

Hieronder wordt beschreven hoe gegevens worden bijgewerkt nadat de gebeurtenis heeft plaatsgevonden:

* Marketo haalt de gegevens van deelnemers elke nacht op uit ON24.
* Zodra de gegevens van de deelnemer tussen Marketo en ON24 zijn gesynchroniseerd, werkt Marketo de lidmaatschapsstatus bij aan Bijgewoond, Bijgewoond, Op bestelling, of Geen Show. In de **Samenvatting** tabblad, wordt de status van de gebeurtenis bijgewerkt naar **Gebeurtenis voltooid**.

>[!MORELIKETHIS]
>
>* [Voorbeeld ON24-gebeurtenisintegratie](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md){target=&quot;_blank&quot;}
>* [Marketo ON24-adaptergebeurtenissen](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target=&quot;_blank&quot;}

