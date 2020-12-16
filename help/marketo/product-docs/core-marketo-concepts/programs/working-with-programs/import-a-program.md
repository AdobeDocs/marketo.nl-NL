---
unique-page-id: 1147108
description: Een programma importeren - Marketo Docs - Productdocumentatie
title: Een programma importeren
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '912'
ht-degree: 0%

---


# Een programma importeren {#import-a-program}

Een programma kan van één abonnement van Marketo in een andere worden ingevoerd. U kunt bijvoorbeeld een programma maken in een sandbox en dit vervolgens importeren in uw live abonnement. U kunt ook een vooraf gebouwd programma importeren vanuit de Marketo-programmabibliotheek.

## Een programma importeren {#import-a-program-1}

1. Ga naar **marketingactiviteiten.**

   ![](assets/ma.png)

1. Klik **Nieuw **drop-down. Selecteer **Importprogramma**.

   ![](assets/image2014-9-17-12-3a15-3a4.png)

   >[!NOTE]
   >
   >De Invoer van het programma is slechts beschikbaar voor gebruikers die rollen hebben met toegelaten de toestemming van het Programma van de Invoer. Meer informatie over het [beheren van gebruikersrollen en machtigingen](../../../../product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md).
   >
   >
   >Als u een sandboxaccount wilt koppelen aan uw live abonnement, neemt u contact op met de [Marketo-ondersteuning](http://www.marketo.com/services/support/).

1. Selecteer een Marketo- **abonnement** en een programma dat u wilt importeren. Klik op **Volgende**.

   ![](assets/image2014-9-17-12-3a20-3a13.png)

1. Geef een **campagnemap** op voor het geïmporteerde programma. Klik op **Volgende.**

   ![](assets/image2014-9-17-12-3a20-3a44.png)

   >[!NOTE]
   >
   >Zorg ervoor ** ****Gebruik de standaard collisieregels** wordt geselecteerd. Conflictregels zijn nodig wanneer u programma&#39;s importeert in een instantie met elementen met dezelfde naam.

1. Geef een voorvertoning weer van de details en **importeer** het programma.

   ![](assets/image2014-9-17-12-3a21-3a36.png)

   In een dialoogvenster wordt de voortgang van het importeren van het programma weergegeven.

   ![](assets/image2014-9-17-12-3a21-3a51.png)

U ontvangt een e-mailbevestiging nadat het importeren is voltooid.

>[!NOTE]
>
>U moet geïmporteerde batchcampagnes opnieuw plannen en triggercampagnes activeren. Het systeem deactiveert automatisch campagnematerialen en activeert campagnes in het geïmporteerde programma.

## Pre-Built Programma&#39;s identificeren in de Marketo Program Library {#identify-pre-built-programs-in-the-marketo-program-library}

De Marketo-programmabibliotheek bevat vooraf gebouwde, geteste programma&#39;s die u kunt importeren in uw abonnement. Beschikbare programma&#39;s zijn:

1. **Standaard druppelcursus.** Verstuurt een reeks e-mailberichten gescheiden door wachtstappen.
1. **Gegevensbeheer.** Behoudt gegevensintegriteit met behulp van slimme campagnes.
1. **E-mail met bestemmingspagina.** Verzendt een eerste e-mail met een voorstel, zoals &quot;download dit Witboek.&quot; Wordt vervolgd met een e-mail voor bevestiging of herinnering. Bevat een openingspagina met een formulier.
1. **E-mail met status voor progressie.** Verstuurt een mailexplosie met een trackable verbinding voor de persoon om te klikken. Werkt de progressiestatus voor elke persoon bij - Verzonden, Geopend, Gepliceerd etc.
1. **Interesserende momenten.** Creeert interessante momenten voor uw verkoopteam om hen in de lijn te houden.
1. **Openingspagina met Autoresponder.** Gebruik downloadbare inhoud om nieuwe mensen te krijgen en te voeden. Inclusief openingspagina&#39;s en formulieren.
1. **Levenscyclus 2.** Gebruikt score om een persoon van nieuw aan marketing gekwalificeerd te bewegen.
1. **Mobiele e-mailsjabloon.** Een responsieve e-mailsjabloon die is getest op iPhone en Android. Bepaalde versies van Android-, MS Outlook-, Exchange- en apps van derden, zoals Gmail en Yahoo! Mobiele apps voor e-mail bieden geen ondersteuning voor de CSS die vereist is voor responsieve sjablonen. We raden je aan te testen voordat je e-mailberichten verzendt.
1. **Programma Import Sweepstakes.** Zoek naar een programma voor degenen die de programmabibliotheek proberen! Goedkeuren van de e-mails en de bestemmingspagina en activeren de slimme campagne. Geef vervolgens de goedgekeurde bestemmingspagina weer, vul het formulier in en u bent ingegaan!
1. **Beschikbare verkoopcampagnes.** Geeft uw verkoopvertegenwoordigers een manier om Marketo slimme campagnes van een Dashboard in uw CRM uit te voeren.
1. **Scoring - Spark Edition.** Demografische en gedragsscoring die in één enkel scoreveld is vastgelegd. Bevat meer dan twee dozijn scoring-campagnes.
1. **Muziek - Standaard en selecteer edities.** Demografische en gedragsscoring is vastgelegd in afzonderlijke scoringvelden. Bevat meer dan twee dozijn scoring-campagnes.
1. **Synchroniseer Nieuwe personen met CRM.** De campagne die nieuwe mensen aan uw systeem van CRM synchroniseert. Het wijst een persoonstatus toe zodat het als niet verkoopklaar wordt erkend.
1. **Webinar met de Adapter van de Gebeurtenis.** Een volledige reeks e-mailberichten - zoals uitnodigingen en herinneringen - plus landingspagina&#39;s met formulieren en campagnes om mensen door het programma te bewegen. Dit programma krijgt updates over registratie, aanwezigheid, enz. van online gebeurtenisleveranciers zoals WebEx.
1. **Webinar zonder gebeurtenisadapter.** Hetzelfde als hierboven, maar met handmatige registratieprocedures, aanwezigheid enz.
1. **Scoreprogramma** voor Sirius-besluiten. Dit programma is opgezet ter ondersteuning van het standaardmodel voor Sirius-besluiten met score, inclusief de impliciete en expliciete scores en de gematrixeerde personentaak. Bekijk [deze](http://docs.marketo.com/display/docs/assets/sirius-decisions-scoring-program-overview.pdf)PDF voor meer informatie.

>[!CAUTION]
>
>U moet twee aangepaste velden maken (&quot;Demografische score&quot; en &quot;Gedragsscore&quot;) voordat u het programma Scores - Standaard &amp; Select Editions importeert.

## Gevolgen voor externe activa tijdens programmainvoer {#impact-on-external-assets-during-program-imports}

De programma&#39;s gebruiken externe activa zoals e-mailmalplaatjes, landende paginasjablonen, beelden, vormen, tekenen, en programmalabels. U hebt de capaciteit om te vormen hoe het landen paginasjablonen en programmamarkeringen worden behandeld, en Marketo beheert automatisch de rest.

**E-mailsjablonen: **E-mailsjablonen worden automatisch geïmporteerd en gemaakt, tenzij er een sjabloon met dezelfde naam bestaat.

**Templates voor bestemmingspagina: **Sjablonen voor de landingspagina worden geïmporteerd in de ontwerpstudio. U kunt collisieregels gebruiken om gedrag te vormen wanneer een malplaatje met de zelfde naam bestaat. Gebruikend de standaardregel, zal een aantal aan een het landen paginamalplaatje worden toegevoegd als één met de zelfde naam bestaat. Er wordt bijvoorbeeld een sjabloon voor een landingspagina met de naam Standaardsjabloon 1 gemaakt als er een sjabloon met de naam Standaardsjabloon bestaat.

**Afbeeldingen: **Afbeeldingen die door bestemmingspagina&#39;s worden gebruikt, worden ingevoerd in de ontwerpstudio tenzij er één met dezelfde naam bestaat.

**Tokens: **Tokens die buiten een programma wonen zullen in lokale tokens tijdens het de invoerproces worden omgezet.

>[!CAUTION]
>
>Afbeeldingstype mijn tokens worden niet ondersteund voor het importeren van programma&#39;s. Als een programma met beeldtype mijn tokens wordt ingevoerd, **no **tokens zal door komen.

**Programmatags: **U kunt collisieregels gebruiken om te controleren hoe de programmamarkeringen die niet in de bestemmingsrekening bestaan zullen worden behandeld. Als u de standaardregel gebruikt, worden de programmacodes gemaakt of kunt u de codes negeren.  **Forms: **Externe formulieren worden automatisch in de ontwerpstudio geïmporteerd, tenzij er een met dezelfde naam bestaat.

>[!CAUTION]
>
>Tijdens het importeren van een programma worden bestemmingspagina&#39;s/e-mails met [dynamische inhoud](http://docs.marketo.com/x/yRAt) overgeslagen.

## Een video bekijken {#watch-a-video}

`<iframe width="630" height="470" src="//play.vidyard.com/KgvZssZ9WRkZgDsY1yZfms.html?v=3.1.1" frameborder="0" allowfullscreen></iframe>`