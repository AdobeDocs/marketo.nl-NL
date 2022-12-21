---
unique-page-id: 17728023
description: Een gebeurtenis maken met Zoomen - Marketo Docs - Productdocumentatie
title: Een gebeurtenis met zoomen maken
exl-id: 6a2aec58-902c-4e40-ab59-9cc33ec83cea
source-git-commit: 8b0625a7192a80986bc4295726cd13473493ddd7
workflow-type: tm+mt
source-wordcount: '560'
ht-degree: 0%

---

# Een gebeurtenis met zoomen maken {#create-an-event-with-zoom}

>[!PREREQUISITES]
>
>* [Zoomen toevoegen als een opstartpuntservice](/help/marketo/product-docs/administration/additional-integrations/add-zoom-as-a-launchpoint-service.md)
>* [Een nieuw gebeurtenisprogramma maken](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)
>* Stel de juiste [flowhandelingen](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)om betrokkenheid bij te houden


Maak eerst uw webinar in Zoomen. Bepaalde instellingen bij het maken van zoomen worden gebruikt door Marketo en sommige worden alleen gebruikt door Zoomen.

Nadat u een Marketo-gebeurtenis hebt gemaakt en een zoomwebinar hebt gekoppeld, kunnen de systemen gegevens over registratie en aanwezigheid delen. Voor hulp bij het maken van een webinar raadpleegt u  [Aan de slag met zoomwebinars](https://support.zoom.us/hc/en-us/articles/200917029-Getting-Started-With-Webinar).

Voer de volgende informatie in voor uw webinar en het wordt via de adapter in Marketo geplaatst. Als u wijzigingen aanbrengt aan deze gegevens, moet u onder Gebeurtenishandelingen op de koppeling &quot;Vernieuwen van webinar-provider&quot; klikken om de wijzigingen te kunnen zien.

**Titel en beschrijving**

* **Webinar Name** - Voer de naam voor het webinar in. Deze naam wordt weergegeven in Marketo.

* **Beschrijving** (optioneel) - Voer de beschrijving van het webinar in. De beschrijving kan in Marketo worden weergegeven.

**Datum en tijd**

* **Begindatum** - Voer uw begindatum in. Dit zal in Marketo kunnen worden bekeken.

* **Begintijd** - Voer uw begintijd in. Dit zal in Marketo kunnen worden bekeken.

* **Duur** - Voer de duur in. De begin- en eindtijd kunnen in Marketo worden weergegeven.

* **Tijdzone** - Selecteer de toepasselijke tijdzone. Dit zal in Marketo kunnen worden bekeken.

* **Webinar terugkeren**- Niet ingeschakeld houden.

* **Registratie** - Schakel dit selectievakje in om registratie verplicht te stellen. U gebruikt een Marketo-formulier/landingspagina om registratiegegevens vast te leggen die naar Zoomen worden geduwd.

>[!NOTE]
>
>Marketo biedt momenteel geen ondersteuning voor terugkerende webinars. U moet één sessie instellen tussen elke Marketo-gebeurtenis en het zoomwebinar.

![](assets/overview2.png)

>[!TIP]
>
>Er zijn extra gebieden die u in Gezoem zult vormen die NIET de integratie zullen beïnvloeden. Raadpleeg de [Zoom Webinar Help Center](https://support.zoom.us/hc/en-us/sections/200324965-Video-Webinar) voor aanvullende informatie over deze velden.

Laten we nu naar Marketo gaan!

1. Selecteer een gebeurtenis. Klikken **Gebeurtenishandelingen** en kiest u **Gebeurtenisinstellingen**.

   ![](assets/image2015-5-14-14-3a53-3a10-1.png)

   >[!NOTE]
   >
   >Het kanaaltype van de geselecteerde gebeurtenis moet zijn **webinar**.

1. Kies **Zoomen** van de **Gebeurtenis** **Partner** Lijst.

   ![](assets/eventsettings1.png)

1. Kies het account Zoomen waaraan u de gebeurtenis wilt koppelen.

   ![](assets/selectaccount.png)

1. Selecteer het webinar.

   ![](assets/selectevent.png)

1. Klikken **Opslaan**.

   ![](assets/eventsettingssave.png)

   Uitstekend! De gebeurtenis wordt nu gesynchroniseerd en gepland door Zoomen.

   >[!NOTE]
   >
   >De velden die Marketo verzendt, zijn: Voornaam, Achternaam, E-mailadres.

   >[!TIP]
   >
   >Gebruik de volgende token in uw e-mail om het bevestigingsbericht te vullen met deze unieke URL: `{{member.webinar url}}`. Wanneer de bevestiging-URL wordt verzonden, wordt deze token automatisch omgezet in de unieke bevestiging-URL van de persoon.
   >
   >Stel het bevestigingsbericht in op **Operationeel** om ervoor te zorgen dat personen die zich inschrijven en eventueel worden afgemeld, nog steeds hun bevestigingsinformatie ontvangen.

   Personen die zich aanmelden voor uw webinar worden via **Programmastatus wijzigen** De stap van de stroom wanneer de Nieuwe Status aan &quot;Geregistreerd wordt geplaatst.&quot; Geen andere status zal de persoon over duwen. Zorg er ook voor dat u **Programmastatus wijzigen** stap nr. 1 van de stroom, en **E-mail verzenden** Stroom nr. 2.

   ![](assets/goto-webinar-1.png)

   >[!CAUTION]
   >
   >Vermijd het gebruik van geneste e-mailprogramma&#39;s voor het verzenden van bevestigingsberichten. Gebruik in plaats hiervan de slimme campagne van het gebeurtenisprogramma, zoals hierboven wordt getoond.

   >[!TIP]
   >
   >Het kan tot 48 uur duren voordat de gegevens in Marketo verschijnen. Als u na het wachten nog steeds niets ziet, selecteert u **Vernieuwen vanaf webinar-provider** in het menu Gebeurtenishandelingen in het dialoogvenster **Samenvatting** tabblad van uw gebeurtenis.
