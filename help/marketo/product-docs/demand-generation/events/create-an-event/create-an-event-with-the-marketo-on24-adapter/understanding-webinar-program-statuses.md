---
unique-page-id: 10096681
description: Werken met de status van het Webinar-programma - Marketo Docs - Productdocumentatie
title: Werken met de status van het Webinar-programma
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '414'
ht-degree: 0%

---


# Werken met de status van het Webinar-programma {#understanding-webinar-program-statuses}

Programmastatussen vertegenwoordigen de verschillende gebeurtenisstatussen die een persoon doorloopt als lid van de gebeurtenis. Ze zijn gekoppeld aan een kanaaltype. Marketo heeft een ingebouwd kanaaltype met de naam **Webinar**. Statussen kunnen zowel in batch- als triggercampagnes worden gebruikt.

Mensen bewegen lineair door de status van programma&#39;s en gaan niet terug in status. Bijvoorbeeld, kan een persoon met een status van **Bijgewoonde** niet zich naar **Geregistreerd** bewegen.

Hier volgt een korte beschrijving van de programmastatussen die zijn gekoppeld aan het Webinar-kanaal.

>[!TIP]
>
>Als u de status handmatig wilt bijwerken, klikt u op **Vernieuwen van webinar provider** in de vervolgkeuzelijst **Gebeurtenishandelingen** .

![](assets/image2015-12-17-13-3a52-3a39.png)

**Niet in Programma** - Gebruik deze status om personen uit de gebeurtenis te verwijderen.

** Uitgenodigd** - Gebruik deze status om personen aan de gebeurtenis toe te voegen.

**In afwachting van goedkeuring** - Gebruik deze status om het verzenden van een bevestigingsbericht aan je mensen uit te stellen. Zie &quot;Handmatig Registrerende Registranten&quot;in de Updates [van de Registratie van de Gebeurtenis](on24-event-registration-updates.md) ON24 voor meer informatie.

**Wacht op aanbieding** - Gebruik deze status om sommige mensen te laten wachten tot er meer licenties beschikbaar zijn.

**Afgewezen** - Gebruik deze status om de registratie van een persoon voor uw gebeurtenis te weigeren.

**Geregistreerd** - Deze status duwt mensen aan ON24 wanneer u ON24 integratie gebruikt. De status van de persoon wordt bijgewerkt wanneer ON24 reageert dat de persoon is geregistreerd.

**Registratiefout** - Deze status geeft aan dat de gebruiker een fout heeft aangetroffen tijdens het registreren voor de gebeurtenis.

>[!NOTE]
>
>Als er een registratiefout optreedt, kunt u aanvullende informatie voor die persoon opvragen door de kolom Reden van status te bekijken op het tabblad Leden van uw programma. Nadat de fout is opgelost, kunt u de programmastatus van de gebruiker handmatig wijzigen in Geregistreerd binnen Marketo.

**Bijgewoond**- Aan het eind van het webinar, keert ON24 een lijst van mensen terug die bijwoonden. Deze status wordt automatisch naar Marketo getrokken.

**Bijgewoond op bestelling** - De mensen die de gearchiveerde versie van webinar bijwoonden ontvangen deze status.

**No Show** - Aan het einde van het webinar en nadat aanwezigheidsgegevens vanuit ON24 zijn opgehaald, wordt de status van personen die zich hebben geregistreerd maar niet aanwezig zijn, bijgewerkt naar Geen weergave. Het kan overal van 30 minuten tot 3 uren voor ON24 duren om de definitieve aanwezigheidsinformatie voor te bereiden en het ter beschikking te stellen in Marketo.

>[!NOTE]
>
>Marketo kan alleen de status No Show (Geen tonen) krijgen als de mensen zijn geregistreerd *in Marketo*. We kunnen geen No Show vangen die uit On24 gegevensvoer komt.

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Inzicht in Marketo ON24-adaptergebeurtenissen](understanding-marketo-on24-adapter-events.md)

>



