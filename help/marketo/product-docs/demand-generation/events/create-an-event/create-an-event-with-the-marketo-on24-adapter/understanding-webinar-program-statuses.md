---
unique-page-id: 10096681
description: Werken met de status van het Webinar-programma - Marketo Docs - Productdocumentatie
title: Werken met de status van het Webinar-programma
exl-id: ef0b1b94-a612-4aa8-9b4a-aa7ef0e2abaa
feature: Events
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '412'
ht-degree: 0%

---

# Werken met de status van het Webinar-programma {#understanding-webinar-program-statuses}

Programmastatussen vertegenwoordigen de verschillende gebeurtenisstatussen die een persoon doorloopt als lid van de gebeurtenis. Ze zijn gekoppeld aan een kanaaltype. Marketo heeft een ingebouwd kanaaltype, genaamd **Webinar**. Statussen kunnen zowel in batch- als triggercampagnes worden gebruikt.

Mensen bewegen lineair door de status van programma&#39;s en gaan niet terug in status. Bijvoorbeeld een persoon met een status van **Bijgewoond** kan niet teruggaan naar **Geregistreerd**.

Hier volgt een korte beschrijving van de programmastatussen die zijn gekoppeld aan het Webinar-kanaal.

>[!TIP]
>
>Als u de status handmatig wilt bijwerken, klikt u op  **Vernieuwen vanaf webinar-provider** in de **Gebeurtenishandelingen** vervolgkeuzelijst.

![](assets/image2015-12-17-13-3a52-3a39.png)

**Niet in programma** - Gebruik deze status om personen uit de gebeurtenis te verwijderen.

**Uitgenodigd** - Gebruik deze status om personen aan de gebeurtenis toe te voegen.

**In behandeling** - Gebruik deze status om het verzenden van een bevestigingsbericht aan je mensen uit te stellen. Zie &quot;Handmatig geregistreerde personen goedkeuren&quot; in [ON24 Updates voor gebeurtenisregistratie](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/on24-event-registration-updates.md){target="_blank"} voor meer informatie .

**Wacht op aanbieding** - Gebruik deze status om sommige mensen te laten wachten tot er meer licenties beschikbaar zijn.

**Geweigerd** - Gebruik deze status om de registratie van een persoon voor uw gebeurtenis te weigeren.

**Geregistreerd** - Deze status leidt mensen naar ON24 wanneer u de ON24-integratie gebruikt. De status van de persoon wordt bijgewerkt wanneer ON24 reageert dat de persoon is geregistreerd.

**Registratiefout** - Deze status geeft aan dat de gebruiker een fout heeft aangetroffen bij het registreren voor de gebeurtenis.

>[!NOTE]
>
>Als er een registratiefout optreedt, kunt u aanvullende informatie voor die persoon opvragen door de kolom Reden van status te bekijken op het tabblad Leden van uw programma. Nadat de fout is opgelost, kunt u de status van het gebruikersprogramma handmatig wijzigen in Geregistreerd in Marketo.

**Bijgewoond** - Aan het einde van het webinar geeft ON24 een lijst met personen die aanwezig waren. Deze status wordt automatisch naar Marketo opgehaald.

**Bijgewoond op bestelling** - Personen die de gearchiveerde versie van het webinar hebben bijgewoond, ontvangen deze status.

**Geen weergave** - Aan het einde van het webinar en nadat de aanwezigheidsgegevens uit ON24 zijn verzameld, wordt de status van personen die zich hebben geregistreerd maar niet aanwezig waren, bijgewerkt naar Geen show. Het kan overal van 30 minuten tot 3 uren voor ON24 duren om de definitieve aanwezigheidsinformatie voor te bereiden en het ter beschikking te stellen in Marketo.

>[!NOTE]
>
>Marketo kan de status No Show alleen gebruiken als de personen zijn geregistreerd *in Marketo*. We kunnen geen No Show vangen die uit On24 gegevensvoer komt.

>[!MORELIKETHIS]
>
>[Marketo ON24-adaptergebeurtenissen](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target="_blank"}
