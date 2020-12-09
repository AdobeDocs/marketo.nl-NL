---
unique-page-id: 10096683
description: ON24 Updates voor gebeurtenisregistratie - Marketo Docs - Productdocumentatie
title: ON24 Updates voor gebeurtenisregistratie
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '282'
ht-degree: 0%

---


# ON24 Updates voor gebeurtenisregistratie {#on-event-registration-updates}

## Registranten handmatig goedkeuren {#manually-approving-registrants}

U kunt uw geregistreerde personen handmatig goedkeuren voordat u ze een bevestigingsbericht stuurt. Om dit te doen, zult u uw campagnes moeten vormen om deze extra stap te behandelen:

1. Voor de campagne voor registratieactivering:

   * Stel in de slimme lijst de trigger in op Formulier **** invullen.
   * In de Stroom, plaats de Status in Progressie aan **In afwachting van Goedkeuring**.

1. Ga naar de gebeurtenis en klik op het tabblad **Leden** . Op dit tabblad worden alle personen weergegeven die het formulier hebben ingevuld. Hun status moet worden ingesteld op **In afwachting van goedkeuring**.
1. Gebruik het filter bij de bovenkant van het net om slechts de mensen te bekijken met een status van in **afwachting van Goedkeuring**.
1. Selecteer de personen die u wilt registreren (houd Shift ingedrukt en klik, houd Ctrl ingedrukt en klik of selecteer Alles).
1. Klik in het menu op **Status** wijzigen. Selecteer **Geregistreerd**, **Geweigerd**, of een andere toepasselijke status.

## Personen met een registratiefout afhandelen {#handling-people-with-a-registration-error}

Als een persoon uiteindelijk niet wordt geregistreerd maar eerder aan de Fout van de Registratie van de status wordt geplaatst, is het niet te laat om terug te krijgen.

1. Van het lusje van Leden, filter de lijst van mensen met de fout **van de** Registratie van de status.
1. Alvorens verder te gaan, zorg ervoor u de kwestie met integratie hebt bepaald en opgelost (controle om ervoor te zorgen er geen fouten onder de Partners **van de** Gebeurtenis in Admin zijn).
1. Nadat het probleem is opgelost, selecteert u alle personen met de status Registratiefout en wijzigt u hun status in **Geregistreerd**. Dit zal proberen om hen opnieuw bij ON24 te registreren.

## Lidstatus bijwerken vanuit ON24 {#updating-member-status-from-on}

Marketo haalt automatisch de aanwezigheidsinformatie elke avond om 11.00 uur in de Stille Oceaan. Klik op **Vernieuwen van webinar-provider** onder **Gebeurtenishandelingen** om aanwezigheidsgegevens handmatig bij te werken.

>[!MORELIKETHIS]
>
>* [Inzicht in Marketo ON24-adaptergebeurtenissen](understanding-marketo-on24-adapter-events.md)

>



