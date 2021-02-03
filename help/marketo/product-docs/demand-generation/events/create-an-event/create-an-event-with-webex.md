---
unique-page-id: 2949863
description: Een gebeurtenis maken met WebEx - Marketo Docs - Productdocumentatie
title: Een gebeurtenis maken met WebEx
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '927'
ht-degree: 0%

---


# Een gebeurtenis maken met WebEx {#create-an-event-with-webex}

>[!PREREQUISITES]
>
>* [WebEx toevoegen als een LaunchPoint-service](/help/marketo/product-docs/administration/additional-integrations/add-webex-as-a-launchpoint-service.md)
>* [Een nieuw gebeurtenisprogramma maken](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)
>* Stel de juiste [flowhandelingen](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)in om de betrokkenheid bij te houden


Maak eerst een Webex-gebeurtenis in het WebEx-gebeurteniscentrum. Marketo gebruikt alleen specifieke instellingen en velden voor uw integratie, die we binnenkort zullen doorlopen. Andere gebieden die u voor WebEx zou kunnen willen vormen worden verklaard in [WebEx de Gids van de Gebruiker van het Centrum van de Gebeurtenis ](https://www.cisco.com/c/dam/en/us/td/docs/collaboration/meeting_center/wbs298/wx_ec_host_ug.pdf).

## Basisinformatie {#basic-information}

* **Naam gebeurtenis -** Deze naam kan worden weergegeven in Marketo.
* **Selectievakje voor Niet-weergegeven**

   * Het is raadzaam om **geen** een lijst van uw gebeurtenis in te voeren. Zo kunnen alle personen zich registreren via de landingspagina Marketo. Personen die zich via een ander mechanisme dan Marketo registreren, worden in Marketo weergegeven nadat de gebeurtenis is voltooid EN alleen als zij de gebeurtenis hebben bijgewoond.
   * Als u ervoor kiest om de gebeurtenis weer te geven, wordt deze op de pagina Lijst met gebeurtenissen weergegeven voor iedereen die de website van het gebeurteniscentrum bezoekt.

* **Registratie -** Schakel dit selectievakje in als u &quot;required&quot; wilt instellen. U zult een Marketo vorm/het landen pagina gebruiken om registratieinformatie te vangen die aan WebEx zal worden geduwd.
* **Wachtwoord** voor gebeurtenis - (optioneel) Als u dit veld gebruikt, moet u dit in het bevestigingsbericht opnemen.

![](assets/image2015-5-28-13-3a30-3a55.png)

## Datum en tijd {#date-time}

* **Begindatum**  - Voer uw begindatum in. Dit wordt weergegeven in Marketo.

* **Begintijd**  - Voer uw begintijd in. Dit wordt weergegeven in Marketo.

* **Geschatte duur**  - Geef de duur van de gebeurtenis op. Dit wordt weergegeven in Marketo.

* **Tijdzones**  - Voer de toepasselijke tijdzones in. Zij zullen in Marketo kunnen worden bekeken.

![](assets/image2015-5-28-13-3a37-3a39.png)

## Instellingen audioconferentie {#audio-conference-settings}

Deze instellingen bevinden zich alleen in WebEx. Ze worden niet door Marketo gebruikt of kunnen in Marketo worden bekeken, maar ze kunnen wel belangrijk zijn voor je webinar, dus dubbelcontroleer ze!

## Gebeurtenisbeschrijving en -opties {#event-description-options}

De volgende opties worden gebruikt door of kunnen worden weergegeven in Marketo. Andere gebieden verblijven slechts in WebEx.

* **Beschrijving**  - Voer een beschrijving in. Dit zal in Marketo zichtbaar maar niet veranderbaar zijn.
* **Post-event onderzoek**  - Marketo kan niet de informatie over een post-gebeurtenisonderzoek WebEx op dit ogenblik vangen.
* **Doel-URL**  (optioneel) U kunt de URL van een bestemmingspagina invoeren om als doel-URL te dienen om na afloop van de sessie weer te geven.

![](assets/image2015-5-28-13-3a48-3a49.png)

## Deelnemers en registratie {#attendees-registration}

U bestuurt de uitnodigingslijst, het registratieformulier en andere e-mails met een Marketo-gebeurtenis. Andere functionaliteit wordt niet ondersteund door Marketo, zoals:

* **Maximum aantal registranten**  -  **** momenteel niet gesteund gebruikend de integratie Marketo-WebEx.  Handmatige goedkeuring van registranten is beschikbaar met behulp van de status Voortgang in afwachting van goedkeuring in Marketo.

* **Registratie-id vereist**  - Wordt momenteel ondersteund met de integratie Marketo-WebEx. U kunt Marketo gebruiken om het bevestigingsbericht voor uw gebeurtenis te verzenden. Wanneer de persoon zich registreert, ontvangen hij een unieke URL die hij of zij gebruikt om de gebeurtenis in te voeren.

   >[!TIP]
   >
   >Gebruik de volgende token in uw e-mail om het bevestigingsbericht te vullen met deze unieke URL: `{{member.webinar url}}`. Wanneer de bevestiging-URL wordt verzonden, wordt deze token automatisch omgezet in de unieke bevestiging-URL van de persoon.
   >
   >Stel uw bevestigingsbericht in op **Operationeel** om ervoor te zorgen dat personen die zich registreren en mogelijk niet-geabonneerd zijn, nog steeds hun bevestigingsgegevens ontvangen.

* **Registratiewachtwoord**  - (Optioneel) Wordt momenteel niet ondersteund met de integratie Marketo-WebEx.
* **Goedkeuringsregels**  - Wordt momenteel niet ondersteund met de integratie Marketo-WebEx. U kunt echter slimme campagnes in Marketo gebruiken om goedkeuringen te beheren.

![](assets/image2015-5-28-14-3a4-3a41.png)

### Presentatoren en panelleden {#presenters-panelists}

De informatie die in deze sectie wordt gevormd wordt niet overgegaan tot Marketo.

### E-mailberichten {#email-messages}

U gebruikt Marketo om e-mails, bevestigingse-mails en dergelijke naar uw geregistreerde personen te sturen. U hoeft niets in deze sectie te configureren. Schakel de opties voor e-mailberichten in WebEx uit (hef de controle op).

![](assets/image2015-5-28-14-3a9-3a14.png)

>[!NOTE]
>
>De integratie Marketo-WebEx kan het verzenden van bevestigingse-mail van WebEx niet steunen. De bevestiging moet via Marketo worden verzonden. Nadat u de gebeurtenis hebt gepland, ben zeker om de gebeurtenisinformatie aan Marketo te kopiëren om e-mail te bevestigen en e-mail te plaatsen als **Operationeel**.

Nu zijn we klaar om naar Marketo te springen!

1. Selecteer de gebeurtenis die u hebt gemaakt. Open de vervolgkeuzelijst **Gebeurtenishandelingen**. Kies **Gebeurtenisinstellingen.**

   ![](assets/image2015-5-14-16-3a7-3a31.png)

   >[!NOTE]
   >
   >Het kanaaltype van de geselecteerde gebeurtenis moet **webinar** zijn.

1. Selecteer **WebEx** onder **Gebeurtenispartner**.

   ![](assets/image2015-1-30-13-3a58-3a2.png)

1. Kies onder **Aanmelden** uw WebEx-aanmelding.

   ![](assets/image2015-5-18-12-3a2-3a26.png)

1. Kies onder **Gebeurtenis** de zojuist gemaakte WebEx-gebeurtenis. Selecteer vervolgens een optionele back-uppagina en klik op **Opslaan**.

   ![](assets/image2015-5-14-16-3a15-3a55.png)

1. Selecteer een optionele back-uppagina voor uw WebEx-gebeurtenis. Kies een optie in de vervolgkeuzelijst met goedgekeurde Marketo-landingspagina&#39;s of voer de URL in van een landingspagina die niet Marketo is.

   >[!TIP]
   >
   >Stel een back-uppagina in om een lid naar een specifieke pagina te leiden als het vóór de begintijd van de gebeurtenis op de URL van de aangepaste gebeurtenis klikt.

   >[!NOTE]
   >
   >De velden die Marketo verzendt, zijn: Voornaam, Achternaam, E-mailadres.

   ![](assets/webex.png)

   >[!CAUTION]
   >
   >Vermijd het gebruik van geneste e-mailprogramma&#39;s voor het verzenden van bevestigingsberichten. Gebruik in plaats hiervan de slimme campagne van het gebeurtenisprogramma, zoals hierboven wordt getoond.

   >[!TIP]
   >
   >Het kan tot 48 uur duren voordat de gegevens in Marketo verschijnen. Als na het wachten dat lang u nog niets ziet, uitgezocht **verfrist zich van Webinar Leverancier** van het menu van de Acties van de Gebeurtenis in **Samenvatting** lusje van uw gebeurtenis.

Zoet! Uw WebEx-gebeurtenis wordt nu gesynchroniseerd met uw Marketo-gebeurtenis.  Personen die zich aanmelden voor uw webinar, worden via de stap Program Status wijzigen naar uw webinar geduwd wanneer de Nieuwe status is ingesteld op &quot;Geregistreerd&quot;. Geen andere status zal de persoon over duwen. Zorg er ook voor dat u in stap 1 van de statusstroom van het programma Wijzigen en stap 2 in de E-mailflow verzendt.

## Het schema {#viewing-the-schedule} weergeven

Klik in de programmaweergave van het programma op de kalendervermelding voor de gebeurtenis. U kunt het schema aan de rechterkant van het scherm zien!

![](assets/image2015-5-14-16-3a21-3a41.png)

>[!NOTE]
>
>Om uw gebeurtenisprogramma te veranderen zult u webinar op WebEx moeten uitgeven.
