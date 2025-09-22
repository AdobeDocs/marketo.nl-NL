---
unique-page-id: 10096681
description: Werken met de status van het Webinar-programma - Marketo Docs - Productdocumentatie
title: Werken met de status van het Webinar-programma
exl-id: ef0b1b94-a612-4aa8-9b4a-aa7ef0e2abaa
feature: Events
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '414'
ht-degree: 0%

---

# Werken met de status van het Webinar-programma {#understanding-webinar-program-statuses}

Programmastatussen vertegenwoordigen de verschillende gebeurtenisstatussen die een persoon doorloopt als lid van de gebeurtenis. Ze zijn gekoppeld aan een kanaaltype. Marketo heeft een ingebouwd kanaaltype genoemd **Webinar**. Statussen kunnen zowel in batch- als triggercampagnes worden gebruikt.

Mensen bewegen lineair door de status van programma&#39;s en gaan niet terug in status. Bijvoorbeeld, kan een persoon met een status van **Bijgewoonde** niet zich terug naar **Geregistreerde** bewegen.

Hier volgt een korte beschrijving van de programmastatussen die zijn gekoppeld aan het Webinar-kanaal.

>[!TIP]
>
>Om statussen manueel bij te werken, verfrist de klik **zich van Webinar Leverancier** in de **3} drop-down Acties van de Gebeurtenis.**

![](assets/image2015-12-17-13-3a52-3a39.png)

**niet in Programma** - gebruik deze status om mensen uit de gebeurtenis te verwijderen.

**Uitgenodigd** - gebruik deze status om mensen aan de gebeurtenis toe te voegen.

**in afwachting van Goedkeuring** - gebruik deze status om op het verzenden van uw mensen een bevestigingsbericht uit te houden. Zie &quot;Handmatig Registrerend Registranten&quot;in [ ON24 de Updates van de Registratie van de Gebeurtenis ](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/on24-event-registration-updates.md){target="_blank"} voor meer informatie.

**wacht op Lijst** - gebruik deze status om sommige mensen te houden die tot extra plaatsen beschikbaar worden wachten.

**Verworpen** - gebruik deze status om de registratie van een persoon aan uw Gebeurtenis te verwerpen.

**Geregistreerd** - Deze status duwt mensen aan ON24 wanneer u de integratie ON24 gebruikt. De status van de persoon wordt bijgewerkt wanneer ON24 reageert dat de persoon is geregistreerd.

**Fout van de Registratie** - Deze status wijst erop dat de gebruiker een fout toen het proberen om voor de Gebeurtenis te registreren tegenkwam.

>[!NOTE]
>
>Als er een registratiefout optreedt, kunt u aanvullende informatie voor die persoon opvragen door de kolom Reden van status te bekijken op het tabblad Leden van uw programma. Nadat de fout is opgelost, kunt u de status van het gebruikersprogramma handmatig wijzigen in Geregistreerd in Marketo.

**bijgewoond** - aan het eind van webinar, keert ON24 een lijst van mensen terug die bijwoonden. Deze status wordt automatisch naar Marketo opgehaald.

**bijgewoond op bestelling** - De Mensen die de gearchiveerde versie van webinar bijwoonden ontvangen deze status.

**Geen Show** - bij de conclusie van webinar en nadat de aanwezigheidsgegevens binnen van ON24 worden getrokken, wordt de status van mensen die registreerden maar niet bijwoonden bijgewerkt aan Geen Show. Het kan overal van 30 minuten tot 3 uren voor ON24 duren om de definitieve aanwezigheidsinformatie voor te bereiden en het ter beschikking te stellen in Marketo.

>[!NOTE]
>
>Opdat Marketo de status van de Show van Nr trekt, moeten de mensen *in Marketo* geregistreerd zijn. We kunnen geen No Show vangen die uit On24 gegevensvoer komt.

>[!MORELIKETHIS]
>
>[ Begrip Marketo ON24 adaptergebeurtenissen ](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target="_blank"}
