---
description: Een gebeurtenis maken met Webex - Marketo Docs - Productdocumentatie
title: Een gebeurtenis maken met Webex
hide: true
hidefromtoc: true
feature: Events
source-git-commit: 286e1b7b563be70e932206adec6f80b4877b7953
workflow-type: tm+mt
source-wordcount: '616'
ht-degree: 0%

---

# Een gebeurtenis maken met Webex {#create-an-event-with-webex}

>[!PREREQUISITES]
>
>* [Webex toevoegen als een LaunchPoint-service](/help/marketo/product-docs/administration/additional-integrations/add-webex-as-a-launchpoint-service.md)
>* [Een nieuw gebeurtenisprogramma maken](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)
>* Stel de juiste [flowhandelingen](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md) om betrokkenheid bij te houden

## Webinar plannen {#schedule-a-webinar}

Maak eerst een webinar in [Webex](https://www.webex.com/){target="_blank"}. Marketo Engage only uses specific settings and fields for your integration, which we'll go through shortly. For additional information, please see the [Webex Webinars Help Documentation](https://help.webex.com/en-us/landing/ld-7srxjs-WebexWebinars/Webex-Webinars){target="_blank"}.

>[!NOTE]
>
>U kiest uw voorkeursinstellingen in Webex, maar alleen de volgende gegevens kunnen in het Marketo Engage worden weergegeven: naam webinar, begin-/einddatum en -tijd, tijdzone en beschrijving.

### Basisinformatie {#basic-information}

![](assets/create-an-event-with-webex-1.png)

* **Onderwerp**: Dit is uw naam van de gebeurtenis en deze wordt weergegeven in Marketo.
* **Datum en tijd**: De begin-/einddatum, de begin-/eindtijd, de duur en de tijdzone kunnen allemaal worden weergegeven in Marketo.
* **Maximumaantal deelnemers**: Het maximumaantal deelnemers bepaalt welke Webex-functies worden ondersteund.
* **Webcast-weergave voor deelnemers**: Controleer dit om uw webinar live te laten streamen naar alle deelnemers.
* **Panelisten**: Nodig specifieke mensen uit om panelleden te zijn op uw webinar.
* **Webinar agenda**: Vul deze optie in als u context wilt opgeven in de e-mailuitnodiging die naar panelleden wordt verzonden.

### Beveiliging {#security}

![](assets/create-an-event-with-webex-2.png)

* **Webinar-wachtwoord**: (optioneel) Als u dit veld gebruikt, moet u het in het bevestigingsbericht opnemen.
* **Wachtwoord voor panellijst**: (optioneel) Als u dit veld gebruikt, moet u het in de Webinar-agenda opnemen.
* **Account vereisen**: Alleen deelnemers met een Webex-account.

### Opties voor audioverbinding {#audio-connection-options}

![](assets/create-an-event-with-webex-3.png)

* **Type audioverbinding**: Kies hoe webinar deelnemers zich aansluiten bij het audiogedeelte van uw webinar.
* **Invoer- en exittoon**: Selecteer het geluid dat u wilt gebruiken wanneer iemand het webinar binnengaat of verlaat (telefoonaudioverbinding vereist).
* **Dempen, panellid**: Kies de gewenste instellingen voor dempen in het deelvenster.

### Geavanceerde opties {#advanced-options}

![](assets/create-an-event-with-webex-4.png)

* **Automatisch opnemen**: Controleer dit om uw webinar automatisch te laten registreren.
* **Praktijksessie**: Controleer dit om een praktijksessie te laten starten wanneer het webinar begint.
* **Brainstormsessies**: Met brainstormsessies kunt u vooraf panelleden en aanwezigen toewijzen voordat het webinar wordt gestart, of ze toestaan om deel te nemen tijdens het webinar.
* **Webinar-reeksen**: Door toe te voegen aan een webinar serie kunnen mensen je webinar zien of het openbaar is of niet.
* **Registratie**: Deelnemers moeten zich registreren en toestemming van de gastheer ontvangen voordat ze kunnen deelnemen.
* **E-mailherinnering**: Kies een e-mailherinnering die loopt van 15 minuten voordat het webinar maximaal twee dagen start.
* **Webinar-opties**: Bepaal welke functies beschikbaar zijn voor deelnemers in het webinar.
* **Machtigingen voor deelnemers**: De bevoegdheden van deelnemers bepalen de acties die beschikbaar zijn voor webinaire deelnemers.

>[!NOTE]
>
>De Marketo-Webex-integratie biedt geen ondersteuning voor het verzenden van bevestigingse-mails vanuit Webex. De bevestiging moet via Marketo worden verzonden. Nadat u de gebeurtenis hebt gepland, kopieert u de gebeurtenisinformatie naar het bevestigingsbericht van Marketo en stelt u het e-mailbericht in als _Operationeel_.

Nu zijn we klaar om in Marketo Engage te springen!

## Uw gebeurtenis synchroniseren met Marketo Engage {#sync-your-event-with-marketo-engage}

1. Zoek in Marketo naar het gebeurtenisprogramma dat u hebt gemaakt en selecteer dit programma. In de **Gebeurtenishandelingen** vervolgkeuzelijst, selecteert u **Gebeurtenisinstellingen**.

   ![](assets/create-an-event-with-webex-5.png)

   >[!NOTE]
   >
   >Het kanaaltype van de geselecteerde gebeurtenis moet zijn **webinar**.

1. In de **Gebeurtenispartner** vervolgkeuzelijst, selecteert u **Webex Webinars**.

   ![](assets/create-an-event-with-webex-6.png)

1. In de **Aanmelden** en kiest u uw Webex-aanmelding.

   ![](assets/create-an-event-with-webex-7.png)

1. In de **Gebeurtenis** kiest u uw Webex-gebeurtenis.

   ![](assets/create-an-event-with-webex-8.png)

1. Uw webinar details zullen bevolken. Klikken **Opslaan**.

   ![](assets/create-an-event-with-webex-9.png)

Uw Webex-gebeurtenis wordt nu gesynchroniseerd met uw Marketo-gebeurtenis. Personen die zich aanmelden voor uw webinar worden via _Programmastatus wijzigen_ De stap van de stroom wanneer de Nieuwe Status aan &quot;Geregistreerd wordt geplaatst.&quot; Geen andere status zal de persoon over duwen. Zorg ervoor dat u _Programmastatus wijzigen_ stap nr. 1 van de stroom, en _E-mail verzenden_ Stroom nr. 2.

## Notities {#things-to-note}

* Vermijd het gebruik van geneste e-mailprogramma&#39;s voor het verzenden van bevestigingsberichten. Gebruik in plaats hiervan de slimme campagne van het gebeurtenisprogramma.

* Het kan tot 48 uur duren voordat gegevens in Marketo worden weergegeven. Als u na het wachten nog steeds niets ziet, klikt u op **Vernieuwen vanaf webinar-provider** in de **Gebeurtenishandelingen** vervolgkeuzelijst **Samenvatting** van uw gebeurtenisprogramma.