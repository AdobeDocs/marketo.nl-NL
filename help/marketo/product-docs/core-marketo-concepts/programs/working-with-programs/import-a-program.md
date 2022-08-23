---
unique-page-id: 1147108
description: Een programma importeren - Marketo Docs - Productdocumentatie
title: Een programma importeren
exl-id: 15e23e38-a24b-45b3-89a9-ffec85649f4a
source-git-commit: cc66f4ff2e3e0e6ddfabab91215e3ad31f3b9226
workflow-type: tm+mt
source-wordcount: '949'
ht-degree: 0%

---

# Een programma importeren {#import-a-program}

Een programma kan worden geïmporteerd van het ene Marketo-abonnement naar het andere. U kunt bijvoorbeeld een programma maken in een sandbox en dit vervolgens importeren in uw live abonnement. Bovendien kunt u een vooraf gebouwd programma importeren uit de Marketo Program Library.

## Een programma importeren {#importing-a-program}

1. Ga naar **Marketingactiviteiten.**

   ![](assets/import-a-program-1.png)

1. Klikken **Nieuw** vervolgkeuzelijst. Selecteren **Importprogramma**.

   ![](assets/import-a-program-2.png)

   >[!NOTE]
   >
   >De Invoer van het programma is slechts beschikbaar voor gebruikers die rollen hebben met toegelaten de toestemming van het Programma van de Invoer. Meer informatie over [het beheren van gebruikersrollen en toestemmingen](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md).
   >
   >Als u een sandboxaccount wilt koppelen aan uw live abonnement, neemt u contact op met [Marketo-ondersteuning](https://nation.marketo.com/t5/Support/ct-p/Support).

1. Een Marketo selecteren **Abonnement** en een invoerprogramma. Klikken **Volgende**.

   ![](assets/import-a-program-3.png)

1. Geef een **Campagnemap** voor het geïmporteerde programma. Klikken **Volgende.**

   ![](assets/import-a-program-4.png)

   >[!NOTE]
   >
   >Controleer of **Standaardconflict gebruiken** Er zijn regels geselecteerd. Conflictregels zijn nodig wanneer u programma&#39;s importeert in een instantie met elementen met dezelfde naam.

1. Kies de gewenste conflictdetails en klik op **Volgende**.

   ![](assets/import-a-program-5.png)

   >[!NOTE]
   >
   >Het invoeren van een programma dat de Stappen van de Stroom van de Douane, of de Slimme regels van de Lijst gebruikt die van de Dienst van de Stap van de Stroom in een bestemmingsinstantie worden afgeleid waar er meer dan één compatibele dienstverlener is, zal de het invoeren gebruiker worden ertoe aangezet om stappen of regels aan de correcte dienstverlener in de bestemmingsinstantie toe te wijzen.

1. Details voorvertonen en **Importeren** het programma.

   ![](assets/import-a-program-6.png)

U ontvangt een e-mailbevestiging zodra het importeren is voltooid.

>[!NOTE]
>
>U moet geïmporteerde batchcampagnes opnieuw plannen en triggercampagnes activeren. Het systeem deactiveert automatisch campagnematerialen en activeert campagnes in het geïmporteerde programma.

## Pre-Built-programma&#39;s identificeren in de Marketo Program Library {#identify-pre-built-programs-in-the-marketo-program-library}

De Marketo Program Library bevat vooraf gebouwde, geteste programma&#39;s die u kunt importeren in uw abonnement. Beschikbare programma&#39;s zijn:

1. **Standaard druppelcursus.** Verstuurt een reeks e-mailberichten gescheiden door wachtstappen.
1. **Gegevensbeheer.** Behoudt gegevensintegriteit met behulp van slimme campagnes.
1. **E-mail met bestemmingspagina.** Verzendt een eerste e-mail met een voorstel, zoals &quot;download dit Witboek.&quot; Wordt vervolgd met een e-mail voor bevestiging of herinnering. Bevat een openingspagina met een formulier.
1. **E-mail met status voor progressie.** Verstuurt een mailexplosie met een trackable verbinding voor de persoon om te klikken. Werkt de progressiestatus voor elke persoon bij - Verzonden, Geopend, Gepliceerd etc.
1. **Interesserende momenten.** Creeert interessante momenten voor uw verkoopteam om hen in de lijn te houden.
1. **Openingspagina met Autoresponder.** Gebruik downloadbare inhoud om nieuwe mensen te krijgen en te voeden. Inclusief openingspagina&#39;s en formulieren.
1. **Levenscyclus 2.** Gebruikt score om een persoon van nieuw aan marketing gekwalificeerd te bewegen.
1. **Mobiele e-mailsjabloon.** Een responsieve e-mailsjabloon die is getest op iPhone en Android. Bepaalde versies van Android-, MS Outlook-, Exchange- en apps van derden, zoals Gmail en Yahoo! Mobiele apps voor e-mail bieden geen ondersteuning voor de CSS die vereist is voor responsieve sjablonen. We raden je aan te testen voordat je e-mailberichten verzendt.
1. **Programma Import Sweepstakes.** Zoek naar een programma voor degenen die de programmabibliotheek proberen! Goedkeuren van de e-mails en de bestemmingspagina en activeren de slimme campagne. Geef vervolgens de goedgekeurde bestemmingspagina weer, vul het formulier in en u bent ingegaan!
1. **Beschikbare verkoopcampagnes.** Biedt uw verkopers een manier om slimme campagnes van Marketo van een Dashboard in uw CRM uit te voeren.
1. **Scoring - Spark Edition.** Demografische en gedragsscoring die in één enkel scoreveld is vastgelegd. Bevat meer dan twee dozijn scoring-campagnes.
1. **Muziek - Standaard en selecteer edities.** Demografische en gedragsscoring is vastgelegd in afzonderlijke scoringvelden. Bevat meer dan twee dozijn scoring-campagnes.
1. **Synchroniseer Nieuwe personen met CRM.** De campagne die nieuwe mensen aan uw systeem van CRM synchroniseert. Het wijst een persoonstatus toe zodat het als niet verkoopklaar wordt erkend.
1. **Webinar met de Adapter van de Gebeurtenis.** Een volledige reeks e-mailberichten - zoals uitnodigingen en herinneringen - plus landingspagina&#39;s met formulieren en campagnes om mensen door het programma te bewegen. Dit programma krijgt updates over registratie, aanwezigheid, enz. van online gebeurtenisleveranciers zoals WebEx.
1. **Webinar zonder gebeurtenisadapter.** Hetzelfde als hierboven, maar met handmatige registratieprocedures, aanwezigheid enz.
1. **Scoreprogramma Sirius-besluiten**. Dit programma is opgezet ter ondersteuning van het standaardmodel voor Sirius-besluiten met score, inclusief de impliciete en expliciete scores en de gematrixeerde personentaak.

>[!CAUTION]
>
>U moet twee aangepaste velden maken (&quot;Demografische score&quot; en &quot;Gedragsscore&quot;) voordat u het programma Scores - Standaard &amp; Select Editions importeert.

## Gevolgen voor externe activa tijdens programmainvoer {#impact-on-external-assets-during-program-imports}

De programma&#39;s gebruiken externe activa zoals e-mailmalplaatjes, landende paginasjablonen, beelden, vormen, tekenen, en programmalabels. U kunt configureren hoe sjablonen voor landingspagina&#39;s en programmacodes worden verwerkt, en Marketo beheert automatisch de rest.

**Sjablonen voor e-mail- en landingspagina:** De sjablonen voor e-mail- en landingspagina worden geïmporteerd in de Design Studio. U kunt collisieregels gebruiken om gedrag te vormen wanneer een malplaatje met de zelfde naam bestaat. Met de standaardregel wordt een getal toegevoegd aan een sjabloon als er een bestaat met dezelfde naam. Als u bijvoorbeeld al een sjabloon hebt met de naam &quot;Standaardsjabloon&quot;, krijgt de nieuwe sjabloon de naam &quot;Standaardsjabloon - 1&quot;.

**Openingspagina&#39;s/Forms:** Als een formulier of landingspagina met dezelfde naam bestaat in Design Studio, worden deze nog steeds geïmporteerd, maar wordt er een nummer aan de naam toegevoegd (bijvoorbeeld: Openingspagina - 1).

**Afbeeldingen:** Afbeeldingen die door bestemmingspagina&#39;s worden gebruikt, worden in de ontwerpstudio geïmporteerd, tenzij er een met dezelfde naam bestaat.

**Tokens:** Tokens die buiten een programma leven, worden tijdens het importeren omgezet in lokale tokens.

>[!CAUTION]
>
>Afbeeldingstype mijn tokens worden niet ondersteund voor het importeren van programma&#39;s. Als een programma met afbeeldingstype mijn tokens wordt geïmporteerd, **nee** tokens zullen doorkomen .

**Programmatags:** U kunt collisieregels gebruiken om te controleren hoe de programmamarkeringen die niet in de bestemmingsrekening bestaan zullen worden behandeld. Als u de standaardregel gebruikt, worden de programmacodes gemaakt of kunt u de codes negeren.

>[!CAUTION]
>
>Bij het importeren van een programma worden pagina&#39;s met e-mails/landingen die [dynamische inhoud](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/understanding-dynamic-content.md) wordt overgeslagen.
