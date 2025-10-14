---
unique-page-id: 10096677
description: Test uw ON24-gebeurtenisintegratie - Marketo Docs - productdocumentatie
title: ON24-gebeurtenisintegratie testen
exl-id: 8326b81e-abf7-4615-9a0b-b0a579be8bb8
feature: Events
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '183'
ht-degree: 0%

---

# ON24-gebeurtenisintegratie testen {#test-your-on-event-integration}

Zorg ervoor dat u de integratie van uw gebeurtenis grondig test.

## Aanbevolen testsequentie voordat u de eerste campagne uitvoert {#recommended-test-sequence-before-running-your-first-campaign}

1. Vul het registratieformulier van de gebeurtenis in en gebruik een geldig e-mailadres om het te testen.
1. Bevestig de testnaam met a **Geregistreerde** status in het net van het Lidmaatschap van uw gebeurtenis van Marketo toont.
1. Bevestig de testnaam ook als **Geregistreerde** in ON24 toont.
1. Bevestig dat het geldige e-mailadres dat u hebt gebruikt om de testnaam te registreren, een bevestigingsbericht naar de gebeurtenis heeft ontvangen en dat de unieke URL in de e-mail is opgelost.

   >[!NOTE]
   >
   >U moet de token `{{member.webinar url}}` gebruiken in het bevestigingsbericht om de unieke URL weer te geven in het e-mailbericht van elke registrant.

## Na de gebeurtenis {#after-the-event}

Hieronder wordt beschreven hoe gegevens worden bijgewerkt nadat de gebeurtenis heeft plaatsgevonden:

* Marketo haalt de gegevens van deelnemers elke nacht op uit ON24.
* Zodra de gegevens van de aanwezige synchroniseren tussen Marketo en ON24, werkt Marketo de lidmaatschapsstatus bij in [!UICONTROL Attended], [!UICONTROL Attended On-demand], of [!UICONTROL No Show]. Op het tabblad **[!UICONTROL Summary]** van de gebeurtenis wordt de status van de gebeurtenis bijgewerkt naar **[!UICONTROL Event Complete]** .

>[!MORELIKETHIS]
>
>* [&#x200B; Voorbeeld ON24 de Integratie van de Gebeurtenis &#x200B;](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md){target="_blank"}
>* [&#x200B; Begrip Marketo ON24 adaptergebeurtenissen &#x200B;](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target="_blank"}
