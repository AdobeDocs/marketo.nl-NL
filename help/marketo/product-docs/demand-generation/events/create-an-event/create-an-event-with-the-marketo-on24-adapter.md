---
unique-page-id: 10096656
description: Een gebeurtenis maken met de Marketo ON24-adapter - Marketo Docs - Productdocumentatie
title: Een gebeurtenis maken met de Marketo ON24-adapter
exl-id: a240ff72-b12f-4e3a-8e14-94fddb02f944
feature: Events
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '284'
ht-degree: 0%

---

# Een gebeurtenis maken met de Marketo ON24-adapter {#create-an-event-with-the-marketo-on-adapter}

U moet bekend zijn met de bouwstenen en de aanbevolen volgorde voor het maken van Events in Marketo. U zou ook werkende kennis van de volgende concepten van Marketo moeten hebben:

* [ de Programma&#39;s van Marketo ](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md){target="_blank"} evenals Gebeurtenissen, en de verschillen tussen hen
* [ Kanalen ](/help/marketo/product-docs/administration/tags/create-a-program-channel.md){target="_blank"}
* [ Lokale Assets ](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-local-assets-in-a-program.md){target="_blank"}
* [ De Campagnes van het Kind ](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/configure-event-settings-and-sync-marketo-with-your-webinar.md){target="_blank"} en [ Statussen van het Programma ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-status.md){target="_blank"}

>[!NOTE]
>
>Gelieve te verwijzen naar de [ Marketo API documentatie ](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/rest-api){target="_blank"} voor meer informatie over Marketo APIs.

## Vereisten {#prerequisites}

Voor de integratie met Marketo ON24 is het volgende vereist:

* **Abonnement aan webcasts ON24** - als u geen huidig abonnement hebt, direct contact ON24. **NOTA**: ON24 Gehoste Uitgave wordt vereist. ON24 Gebeurtenisbeheer is niet vereist.

* **de rechten van de Beheerder aan ON24** - u zult dit nodig hebben om deze schakelaar te gebruiken en gasten in het systeem te creëren ON24.
* **ON24 verbindingsgeloofsbrieven** - U zult deze informatie in Marketo moeten ingaan om de integratie toe te laten: Gebruikersnaam, Wachtwoord, identiteitskaart van de Cliënt, en Sleutel van de Cliënt. Neem contact op met uw ON24-accountmanager of ON24-support als u hulp nodig hebt met uw gegevens.
* **vorm van de Registratie** - gebruik een vorm van Marketo of een vorm niet-Marketo samen met juiste API om registratiegegevens te verzekeren en registrant info wordt overgegaan tot Marketo.
* **kindcampagne van de Registratie** - een campagne van het registratiekind in uw Gebeurtenis van Marketo moet behoorlijk voor uw integratie van de Partner van de Gebeurtenis worden gecreeerd en worden gevormd om te werken.

## Processtroom {#process-flow}

Ga als volgt te werk om een gebeurtenis te maken met de Marketo On24-adapter:

1. [ creeer Uw Gebeurtenis Webinar in ON24 ](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/create-your-webinar-event-in-on24.md){target="_blank"}
1. [ vorm de Montages van de Gebeurtenis en Synchroniseer Marketo met Uw Webinar ](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/configure-event-settings-and-sync-marketo-with-your-webinar.md){target="_blank"}
1. [ creeer de Campagnes van het Kind en Lokale Assets ](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/create-child-campaigns-and-local-assets.md){target="_blank"}
1. [ test Uw Integratie van de Gebeurtenis ON24 ](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/test-your-on24-event-integration.md){target="_blank"}
1. [ Voorbeeld ON24 de Integratie van de Gebeurtenis ](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md){target="_blank"}
1. [ Begrijpend de Statussen van het Programma Webinar ](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-webinar-program-statuses.md){target="_blank"}
1. [ ON24 de Updates van de Registratie van de Gebeurtenis ](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/on24-event-registration-updates.md){target="_blank"}
