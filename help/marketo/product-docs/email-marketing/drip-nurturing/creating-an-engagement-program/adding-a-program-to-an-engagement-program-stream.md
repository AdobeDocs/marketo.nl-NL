---
unique-page-id: 10098134
description: Een programma toevoegen aan een betrokkenheidsprogramma-stream - Marketo Docs - Productdocumentatie
title: Een programma toevoegen aan een betrokkenheidsprogramma
exl-id: 44c2ce45-439b-4b29-8130-8cc218e04bbf
feature: Engagement Programs
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '453'
ht-degree: 0%

---

# Een programma toevoegen aan een betrokkenheidsprogramma {#adding-a-program-to-an-engagement-program-stream}

## Waarom een genest programma gebruiken in een betrokkenheidsprogrammastroom? {#why-use-a-nested-program-in-an-engagement-program-stream}

Het is eenvoudig om een e-mail aan een stroom in een betrokkenheidsprogramma toe te voegen, en het werkt prima. Als uw bedrijfsbehoeften echter complexer zijn, kan het zinvol zijn de e-mail in een programma te plaatsen. U kunt bijvoorbeeld het volgende doen:

* Een e-mail verzenden naar een subgroep met personen in de stream
* Verzend *verschillende* e-mails naar subgroepen binnen de stroom
* Pagina&#39;s, formulieren of andere elementen die u wilt uitzetten, opnemen in het programma
* Multitouch-kenmerk inschakelen
* Extra stappen voor doorloop toevoegen, zoals e-mailberichten met waarschuwingen

## Wat gebeurt er als u een programma in een stream gebruikt? {#what-happens-when-you-use-a-program-in-a-stream}

Wanneer u een genest programma gebruikt, is het besluit om een e-mail naar een persoon te verzenden gebaseerd op het lidmaatschap van het programma en de programma-id.

* Als je geen lid bent van een programma, ontvang je eenmaal e-mails die deel uitmaken van het programma
* Als u lid bent van het programma, ontvangt u geen e-mail
* Als u geen lid meer bent maar eerder via dat programma e-mail hebt ontvangen, ontvangt u geen e-mail

Wanneer u een programma in een stream gebruikt, maakt het niet uit of u die specifieke e-mail eerder hebt ontvangen. Zolang e-mail niet vóór *in dat specifieke programma* werd verzonden, kunt u het opnieuw ontvangen.

Het kan lastig zijn om e-mails en programma&#39;s te mengen in een betrokkenheidsprogramma. Wellicht wilt u een van beide gebruiken.

>[!TIP]
>
>Gebruik een filter **[!UICONTROL Member of Engagement Program]** in de slimme lijst.

## Wat gebeurt er met mensen die niet voldoen aan de criteria van de slimme lijst? {#what-happens-to-people-who-dont-meet-the-smart-list-criteria}

Als iemand uit de slimme lijst van slimme campagne van een genesteld programma wordt gefiltreerd, bewegen zij zich niet op het volgende stuk van inhoud tijdens de huidige gietvorm. Zij zullen zich op het volgende stuk van inhoud in de stroom voor de *volgende* gietvorm bewegen.

## Wat bevat een genest programma? {#what-does-a-nested-program-contain}

Een goed ontworpen genest programma bevat e-mails, rapporten en slimme campagnes. Het heeft zin om deze bij elkaar te houden.

De e-mail die u gebruikt, kan in het programma, in een ander programma of zelfs in [!UICONTROL Design Studio] worden weergegeven. Waar het leeft, hangt af van hoe je het wilt gebruiken.

Wijzigingen melden met de e-maillocatie. Als het e-mailbericht bijvoorbeeld in [!UICONTROL Design Studio] staat, worden in het E-mailprestatierapport alle gegevens op één regel weergegeven. De verschillende casts worden gecombineerd. Nochtans, in het Rapport van de Prestaties van de Stroom van de Betrokkenheid, verzendt verschillend wordt getoond afzonderlijk.

>[!CAUTION]
>
>Als je iets opnieuw wilt verzenden, is het het veiligst om een nieuw programma en een slimme campagne te maken.

>[!MORELIKETHIS]
>
>* [ voeg Inhoud aan een Stroom ](/help/marketo/product-docs/email-marketing/drip-nurturing/creating-an-engagement-program/add-content-to-a-stream.md) toe
>* [ Begrijpend Programma&#39;s ](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md)
