---
unique-page-id: 2949874
description: Een gebeurtenis maken met GotoWebinar - Marketo Docs - Productdocumentatie
title: Een gebeurtenis maken met GotoWebinar
exl-id: c0f0a202-e416-4523-b7d6-dbcfafc536cd
source-git-commit: 8b0625a7192a80986bc4295726cd13473493ddd7
workflow-type: tm+mt
source-wordcount: '543'
ht-degree: 0%

---

# Een gebeurtenis maken met GotoWebinar {#create-an-event-with-gotowebinar}

>[!PREREQUISITES]
>
>* [GoToWebinar toevoegen als een LaunchPoint-service](/help/marketo/product-docs/administration/additional-integrations/add-gotowebinar-as-a-launchpoint-service.md)
>* [Een nieuw gebeurtenisprogramma maken](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)
>* Stel de juiste [flowhandelingen](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)om betrokkenheid bij te houden


Maak eerst uw webinar in GoToWebinar. Bepaalde instellingen bij het maken van uw GoToWebinar worden gebruikt door Marketo en sommige worden alleen gebruikt door GoToWebinar.

Nadat u een Marketo-gebeurtenis hebt gemaakt en de GoToWebinar hieraan hebt gekoppeld, kunnen de systemen gegevens over registratie en aanwezigheid delen.

Hieronder volgt een lijst met de instellingen die door Marketo worden gebruikt.

## Titel en beschrijving {#title-and-description}

**Webinar Name** - voer de naam voor het webinar in. Deze naam wordt weergegeven in Marketo.

**Beschrijving** (optioneel) - voer de beschrijving van het webinar in. De beschrijving kan in Marketo worden weergegeven.

![](assets/image2015-5-28-15-3a1-3a36.png)

## Datum en tijd {#date-time}

Voer de volgende informatie in voor uw webinar en het wordt via de adapter in Marketo geplaatst. Als u deze gegevens wijzigt, moet u op de koppeling &quot;**Vernieuwen vanaf webinar-provider**&quot; onder **Gebeurtenishandelingen**, zodat Marketo de wijzigingen kan zien.

**Begindatum** - voer uw begindatum in. Dit zal in Marketo kunnen worden bekeken.

**Begintijd** - voer uw begintijd in. Dit zal in Marketo kunnen worden bekeken.

**Eindtijd** - voer je eindtijd in. Dit zal in Marketo kunnen worden bekeken.

**Tijdzone** - selecteer de toepasselijke tijdzone. Het zal in Marketo kunnen worden bekeken.

**Type -** instellen op **Eén sessie**.

![](assets/image2015-5-28-15-3a7-3a1.png)

>[!NOTE]
>
>Marketo biedt momenteel geen ondersteuning voor terugkerende webinars. U moet één sessie instellen tussen elke Marketo Event en GoToWebinar webinar.

>[!TIP]
>
>Als u extra GoToWebinar hulp nodig hebt, gelieve hun te bezoeken [Help-site](https://support.logmeininc.com/gotowebinar).

Laten we nu naar Marketo gaan!

1. Selecteer een gebeurtenis. Klikken **Gebeurtenishandelingen** en kiest u **Gebeurtenisinstellingen**.

   ![](assets/image2015-5-14-14-3a53-3a10.png)

   >[!NOTE]
   >
   >Het kanaaltype van de geselecteerde gebeurtenis moet zijn **webinar**.

1. Kies **GoToWebinar** van de **Gebeurtenispartner** Lijst.

   ![](assets/image2015-5-14-14-3a55-3a20.png)

1. Kies het account.

   ![](assets/rtaimage-2.png)

1. Selecteer het webinar.

   ![](assets/image2015-5-14-14-3a57-3a31.png)

1. Klikken **Opslaan**.

   ![](assets/image2015-5-14-14-3a58-3a54.png)

1. Uitstekend! Nu wordt de gebeurtenis gesynchroniseerd en gepland door **GoToWebinar**.

   ![](assets/image2015-5-14-15-3a0-3a47.png)

   >[!NOTE]
   >
   >De velden die Marketo verzendt, zijn: Voornaam, Achternaam, E-mailadres. Deze velden zijn verplicht en mogen niet leeg zijn.

   >[!TIP]
   >
   >Gebruik de volgende token in uw e-mail om het bevestigingsbericht te vullen met deze unieke URL: `{{member.webinar url}}`. Wanneer de bevestiging-URL wordt verzonden, wordt deze token automatisch omgezet in de unieke bevestiging-URL van de persoon.
   >
   >Stel het bevestigingsbericht in op **Operationeel** om ervoor te zorgen dat personen die zich inschrijven en eventueel worden afgemeld, nog steeds hun bevestigingsinformatie ontvangen.

   ![](assets/goto-webinar.png)

   >[!CAUTION]
   >
   >Vermijd het gebruik van geneste e-mailprogramma&#39;s voor het verzenden van bevestigingsberichten. Gebruik in plaats hiervan de slimme campagne van het gebeurtenisprogramma, zoals hierboven wordt getoond.

   >[!TIP]
   >
   >Het kan tot 48 uur duren voordat de gegevens in Marketo verschijnen. Als u na het wachten nog steeds niets ziet, selecteert u **Vernieuwen vanaf webinar-provider** in het menu Gebeurtenishandelingen in het dialoogvenster **Samenvatting** tabblad van uw gebeurtenis.

Personen die zich aanmelden voor uw webinar, worden via de stap Program Status wijzigen naar uw webinar geduwd wanneer de Nieuwe status is ingesteld op &quot;Geregistreerd&quot;. Geen andere status zal de persoon over duwen. Zorg er ook voor dat u in stap 1 van de statusstroom van het programma Wijzigen en stap 2 in de E-mailflow verzendt.

## Het overzicht weergeven  {#viewing-the-schedule}

Klik in de programmaweergave van het programma op de kalendervermelding voor de gebeurtenis. U kunt het schema aan de rechterkant van het scherm zien.

>[!NOTE]
>
>Als u uw gebeurtenissenschema wilt wijzigen, moet u het webinar op GoToWebinar bewerken.

![](assets/image2015-5-14-15-3a3-3a13.png)
