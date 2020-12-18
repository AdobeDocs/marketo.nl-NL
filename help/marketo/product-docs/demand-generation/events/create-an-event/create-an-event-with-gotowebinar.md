---
unique-page-id: 2949874
description: Een gebeurtenis maken met GotoWebinar - Marketo Docs - Productdocumentatie
title: Een gebeurtenis maken met GotoWebinar
translation-type: tm+mt
source-git-commit: c8a77dc84c023e05fbb442f575269aac108ffb29
workflow-type: tm+mt
source-wordcount: '600'
ht-degree: 0%

---


# Een gebeurtenis maken met GotoWebinar {#create-an-event-with-gotowebinar}

>[!PREREQUISITES]
>
>* [GoToWebinar toevoegen als een LaunchPoint-service](/help/marketo/product-docs/administration/additional-integrations/add-gotowebinar-as-a-launchpoint-service.md)
>* [Een nieuw gebeurtenisprogramma maken](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)
>* Stel de juiste [flowhandelingen](http://docs.marketo.com/display/DOCS/Flow+Actions)in om de betrokkenheid bij te houden


Maak eerst uw webinar in GoToWebinar. Bepaalde instellingen bij het maken van uw GoToWebinar worden gebruikt door Marketo en sommige worden alleen gebruikt door GoToWebinar.

Nadat u een Marketo-gebeurtenis hebt gemaakt en de GoToWebinar hieraan hebt gekoppeld, kunnen de systemen gegevens over registratie en aanwezigheid delen. Zie de [GoToWebinar User Guide](http://docs.marketo.com/display/docs/assets/gotowebinar-user-guide.pdf) voor hulp bij het maken van een GoToWebinar.

Hieronder ziet u een lijst met de instellingen die Marketo gebruikt.

## Titel en beschrijving {#title-and-description}

**Webinar Naam**  - ga de naam voor webinar in. Deze naam wordt weergegeven in Marketo.

**Beschrijving**  (optioneel) - voer de beschrijving van het webinar in. De beschrijving is &#39;viewable in Marketo.

![](assets/image2015-5-28-15-3a1-3a36.png)

## Datum en tijd {#date-time}

`Enter the following information for your webinar and it will be pulled into Marketo via the`-adapter. Als u om het even welke veranderingen in deze informatie aanbrengt, moet u de verbinding &quot;**verfrissen van Webinar Leverancier**&quot;onder **Gebeurtenisacties**, opdat Marketo de veranderingen ziet.

**Begindatum**  - voer uw begindatum in. Dit wordt weergegeven in Marketo.

**Begintijd** : voer uw begintijd in. Dit wordt weergegeven in Marketo.

**Eindtijd**  - voer uw eindtijd in. Dit wordt weergegeven in Marketo.

**Tijdzone**  - selecteer de toepasselijke tijdzone. Het zal in Marketo kunnen worden bekeken.

**Type -** set aan  **Eén sessie**.

![](assets/image2015-5-28-15-3a7-3a1.png)

>[!NOTE]
>
>Marketo biedt momenteel geen ondersteuning voor terugkerende webinars. U moet één sessie instellen tussen elke Marketo-gebeurtenis en GoToWebinar-webinar.

>[!TIP]
>
>Er zijn extra gebieden die u in GoToWebinar zult vormen die NIET de integratie zullen beïnvloeden. Raadpleeg de [GoToWebinar User Guide](http://docs.marketo.com/display/docs/assets/gotowebinar-user-guide.pdf) voor aanvullende informatie over deze velden, omdat deze niet in dit artikel worden behandeld. Als u extra hulp GoToWebinar nodig hebt, gelieve hun [Hulp Plaats](http://support.logmeininc.com/gotowebinar) te bezoeken.

Laten we nu naar Marketo springen!

1. Selecteer een gebeurtenis. Klik **Gebeurtenishandelingen** en kies **Gebeurtenisinstellingen**.

   ![](assets/image2015-5-14-14-3a53-3a10.png)

   >[!NOTE]
   >
   >Het kanaaltype van de geselecteerde gebeurtenis moet **webinar** zijn.

1. Kies **GoToWebinar** uit **Event** **Partner** Lijst.

   ![](assets/image2015-5-14-14-3a55-3a20.png)

1. Kies het account.

   ![](assets/rtaimage-2.png)

1. Selecteer het webinar.

   ![](assets/image2015-5-14-14-3a57-3a31.png)

1. Klik **Opslaan**.

   ![](assets/image2015-5-14-14-3a58-3a54.png)

1. Uitstekend! De gebeurtenis wordt nu gesynchroniseerd en gepland door **GoToWebinar**.

   ![](assets/image2015-5-14-15-3a0-3a47.png)

   >[!NOTE]
   >
   >De velden die Marketo verzendt, zijn: Voornaam, Achternaam, E-mailadres. Deze velden zijn verplicht en mogen niet leeg zijn.

   >[!TIP]
   >
   >Gebruik de volgende token in uw e-mail om het bevestigingsbericht te vullen met deze unieke URL: `{{member.webinar url}}`. Wanneer de bevestiging-URL wordt verzonden, wordt deze token automatisch omgezet in de unieke bevestiging-URL van de persoon.
   >
   >Stel uw bevestigingsbericht in op **Operationeel** om ervoor te zorgen dat personen die zich registreren en mogelijk niet-geabonneerd zijn, nog steeds hun bevestigingsgegevens ontvangen.

   ![](assets/goto-webinar.png)

   >[!CAUTION]
   >
   >Vermijd het gebruik van geneste e-mailprogramma&#39;s voor het verzenden van bevestigingsberichten. Gebruik in plaats hiervan de slimme campagne van het gebeurtenisprogramma, zoals hierboven wordt getoond.

   >[!TIP]
   >
   >Het kan tot 48 uur duren voordat de gegevens in Marketo verschijnen. Als na het wachten dat lang u nog niets ziet, uitgezocht **verfrist zich van Webinar Leverancier** van het menu van de Acties van de Gebeurtenis in **Samenvatting** lusje van uw gebeurtenis.

Personen die zich aanmelden voor uw webinar, worden via de stap Program Status wijzigen naar uw webinar geduwd wanneer de Nieuwe status is ingesteld op &quot;Geregistreerd&quot;. Geen andere status zal de persoon over duwen. Zorg er ook voor dat u in stap 1 van de statusstroom van het programma Wijzigen en stap 2 in de E-mailflow verzendt.

## Het schema {#viewing-the-schedule} weergeven

In [programmamening ](http://docs.marketo.com/display/docs/program+schedule+view), klik de kalenderingang voor uw gebeurtenis. U kunt het schema aan de rechterkant van het scherm zien.

>[!NOTE]
>
>Als u uw gebeurtenissenschema wilt wijzigen, moet u het webinar op GoToWebinar bewerken.

![](assets/image2015-5-14-15-3a3-3a13.png)
