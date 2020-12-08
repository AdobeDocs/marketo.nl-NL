---
unique-page-id: 10098134
description: Een programma toevoegen aan een betrokkenheidsprogramma Stream - Marketo Docs - Productdocumentatie
title: Een programma toevoegen aan een betrokkenheidsprogramma
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '463'
ht-degree: 0%

---


# Een programma toevoegen aan een betrokkenheidsprogramma {#adding-a-program-to-an-engagement-program-stream}

## Waarom een genest programma gebruiken in een betrokkenheidsprogrammastroom? {#why-use-a-nested-program-in-an-engagement-program-stream}

Het is eenvoudig om een e-mail aan een stroom in een betrokkenheidsprogramma toe te voegen, en het werkt prima. Als uw bedrijfsbehoeften echter complexer zijn, kan het zinvol zijn de e-mail in een programma te plaatsen. U kunt bijvoorbeeld het volgende doen:

* Een e-mail verzenden naar een subgroep met personen in de stream
* Verstuur *verschillende* e-mailberichten naar subgroepen binnen de stream
* Pagina&#39;s, formulieren of andere elementen die u wilt uitzetten, opnemen in het programma
* Multitouch-kenmerk inschakelen
* Extra stroomstappen toevoegen, zoals e-mailberichten met waarschuwingen

## Wat gebeurt er als u een programma in een stream gebruikt? {#what-happens-when-you-use-a-program-in-a-stream}

Wanneer u een genest programma gebruikt, is het besluit om een e-mail naar een persoon te verzenden gebaseerd op het lidmaatschap van het programma en de programma-id.

* Als je geen lid bent van een programma, ontvang je eenmaal e-mails die deel uitmaken van het programma
* Als u lid bent van het programma, ontvangt u geen e-mail
* Als u geen lid meer bent maar eerder via dat programma e-mail hebt ontvangen, ontvangt u geen e-mail

Wanneer u een programma in een stream gebruikt, maakt het niet uit of u die specifieke e-mail eerder hebt ontvangen. Zolang het e-mailbericht niet eerder is verzonden *in dat specifieke programma*, kunt u het opnieuw ontvangen.

Het kan lastige emails en programma&#39;s in een betrokkenheidsprogramma mengen. Wellicht wilt u een van beide gebruiken.

>[!TIP]
>
>Gebruik een filter **Lid van het Programma** van de Aansluiting in uw slimme lijst.

## Wat gebeurt er met mensen die niet voldoen aan de criteria van de slimme lijst? {#what-happens-to-people-who-dont-meet-the-smart-list-criteria}

Als iemand uit de slimme lijst van slimme campagne van een genesteld programma wordt gefiltreerd, bewegen zij zich niet op het volgende stuk van inhoud tijdens de huidige gietvorm. Zij zullen zich op het volgende stuk van inhoud in de stroom voor de *volgende* gietvorm bewegen.

## Wat bevat een genest programma? {#what-does-a-nested-program-contain}

Een goed ontworpen genest programma bevat e-mails, rapporten en slimme campagnes. Het heeft zin om deze bij elkaar te houden.

De e-mail u gebruikt kan in het programma, in een verschillend programma, of zelfs in de Studio van het Ontwerp leven. Waar het leeft, hangt af van hoe je het wilt gebruiken.

Wijzigingen melden met de e-maillocatie. Zo, bijvoorbeeld, als e-mail in de Studio van het Ontwerp, in het E-mailprestatiesrapport is, worden alle metriek getoond in één lijn - de verschillende gietvormen worden gecombineerd. Nochtans, in het Rapport van de Prestaties van de Stroom van de Betrokkenheid, verzendt verschillend wordt getoond afzonderlijk.

>[!CAUTION]
>
>Als je iets opnieuw wilt verzenden, is het het veiligst om een nieuw programma en een slimme campagne te maken.

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Inhoud toevoegen aan een stream](add-content-to-a-stream.md)
>* [Programma&#39;s begrijpen](../../../../product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md)

>



