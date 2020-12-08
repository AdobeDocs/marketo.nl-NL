---
unique-page-id: 1900581
description: Door:sturen aan een Verbinding van de Vriend in E-mail - Marketo Dos - de Documentatie van het Product
title: Doorsturen naar een vriendenkoppeling in e-mails
translation-type: tm+mt
source-git-commit: 1a29614ec938074902af201b2ffc11cfaa625f7a
workflow-type: tm+mt
source-wordcount: '755'
ht-degree: 0%

---


# Doorsturen naar een vriendenkoppeling in e-mails {#forward-to-a-friend-link-in-emails}

Als u de koppeling &quot;Doorsturen naar vriend&quot; toevoegt aan uw e-mails, kunt u personen volgen die via deze koppeling een e-mailbericht hebben ontvangen en deze automatisch toevoegen als een nieuwe persoon als deze nog niet in de database aanwezig is.

Stel bijvoorbeeld dat Keith de koppeling &quot;Doorsturen naar vriend&quot; gebruikt om het e-mailbericht door te sturen naar een onbekende persoon, Mark. Mark wordt automatisch toegevoegd als een nieuwe persoon, krijgt zijn eigen cookie toegewezen en zijn e-mail- en webactiviteiten zijn aan hem gekoppeld. Nochtans, als Keith de voorwaartse knoop in zijn e-mailcliënt gebruikt, wordt Mark verkeerd gekookt als Keith, en zijn activiteit wordt geregistreerd als Keith.

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

## De koppeling toevoegen aan een e-mailsjabloon {#add-the-link-to-an-email-template}

1. Ga naar de **Studio** van het Ontwerp.

   ![](assets/one-8.png)

1. Zoek en selecteer de e-mailsjabloon waaraan u de koppeling wilt toevoegen. Klik op Concept **** bewerken.

   ![](assets/two-7.png)

1. Plak de volgende HTML-code op de plaats waar u de koppeling Doorsturen naar vriend wilt weergeven (als u hulp nodig hebt met dit onderdeel, kunt u contact opnemen met uw webontwikkelaar):

   `<pre data-theme="Confluence"><a href="{{system.forwardToFriendLink}}">Forward to Friend</a></pre>`

   ![](assets/three-7.png)

   >[!TIP]
   >
   >
   >U kunt stijlen aan de koppeling toevoegen om deze er mooier uit te laten zien. Bijvoorbeeld:
   >
   >`<a href="{{system.forwardToFriendLink}}" style="font-family:arial, sans-serif; padding:10px; position:absolute; right:0px;">Forward to Friend</a>`

   >[!CAUTION]
   >
   >We raden u niet aan de **opmaakpositie te gebruiken:relatief** in uw e-mailsjabloon. Het kan problemen veroorzaken met de positie en weergave van het vak &quot;Doorsturen naar vriend&quot;.

1. Klik op Concept **** voorvertonen om te controleren of de sjabloon er naar wens uitziet.

   ![](assets/four-5.png)

   >[!NOTE]
   >
   >**Herinnering**
   >
   >Vergeet niet het sjabloonconcept goed te keuren om de wijzigingen toe te passen.

   Alle e-mails die van die sjabloon gebruikmaken, hebben nu de koppeling Doorsturen naar vriend. Wanneer de e-mailontvanger erop klikt, wordt hij of zij doorgestuurd naar een webversie van het e-mailbericht met het vak &quot;Doorsturen naar een vriend&quot;:
   ![](assets/f2afbox.png)

## De koppeling toevoegen aan een afzonderlijke e-mail {#add-the-link-to-an-individual-email}

U kunt ook de koppeling Doorsturen naar vriend rechtstreeks toevoegen aan een e-mail.

1. Open het e-mailbericht waarin u de koppeling wilt opnemen en dubbelklik in het bewerkbare gebied.

   ![](assets/five-4.png)

1. Plaats de cursor op de positie waar u de koppeling wilt weergeven en klik op de knop **Token** invoegen.

   ![](assets/six-2.png)

1. Selecteer het **`{{system.forwardToFriendLink}}`** token.

   ![](assets/seven-1.png)

   >[!NOTE]
   >
   >Dit token is de URL van de webversie van de e-mail met het vak &quot;Doorsturen naar vriend&quot;.

1. Schrijf uit wat u wilt dat de weergavetekst van de koppeling is (bijvoorbeeld &quot;Doorsturen naar een vriend&quot;).

   ![](assets/seven-1.png)

1. Knip het **`{{system.forwardToFriendLink}}`** token met Ctrl+X (Windows) of Cmd+X (Mac). Markeer &quot;Doorsturen naar een vriend&quot; en klik op de knop Koppeling **** invoegen/bewerken.

   ![](assets/eight-1.png)

1. Plak de **`{{system.forwardToFriendLink}}`** token in het vak **URL** met Ctrl/Cmd+V en klik vervolgens op** Invoegen**.

   ![](assets/nine.png)

1. Sla de bewerking op en bekijk een voorvertoning van de nieuwe koppeling.

   ![](assets/ten-1.png)

   >[!NOTE]
   >
   >Nieuwe personen die worden toegevoegd via een e-mailbericht &quot;Doorsturen naar een vriend&quot;, worden standaard niet meer geabonneerd op marketingberichten.

## Doorgestuurde activiteiten weergeven {#view-forwarding-activity}

U kunt zien wie de e-mails in het activiteitenlog van de persoon heeft doorgestuurd en ontvangen.

1. Ga naar de **`Database`**.

   ![](assets/db.png)

1. Dubbelklik op de persoon waarvoor u activiteit wilt weergeven.

   ![](assets/fourteen.png)

1. Ga naar het tabblad **Activiteitenlog** . Dubbelklik op **Doorsturen naar e-mail** vriend of Doorsturen naar e-mail **** vriend om details weer te geven.

   ![](assets/fifteen.png)

   >[!NOTE]
   >
   >**Definitie**
   >
   >
   >Voor Doorsturen naar e-mail vriend is de persoon-id de persoon die het e-mailbericht heeft doorgestuurd.
   >
   >
   >Voor Doorsturen naar e-mail vriend is de persoon-id de persoon die het e-mailbericht heeft ontvangen.

   ![](assets/sixteen.png)

1. Als u een persoon op ID wilt weergeven, kopieert en plakt u de** Person ID** naar het einde van de URL (het begin van de URL hangt af van uw Marketo-instantie):

   `<pre data-theme="Confluence">...marketo.com/Database/loadPersonDetail?personId=</pre>`

   >[!NOTE]
   >
   >We maken de **Person-id** klikbaar en koppelen deze rechtstreeks aan de persoon in een volgende patch.

   ![](assets/seventeen.png)

   >[!NOTE]
   >
   >Als de vriend die voorwaarts ontvangt een onbekende persoon is, wordt een nieuwe persoon gecreeerd met &quot;door:sturen aan Vriend&quot;duidelijk als **Bron** van de persoon.\
   >Als de e-mail een lokaal middel van een programma is, wordt het programma gemarkeerd als het **Overnameprogramma** van de persoon.

## Trigger of filter die de Door:sturen Activiteit gebruiken {#trigger-or-filter-using-forwarding-activity}

Er zijn zes triggers/filters die u kunt gebruiken om flowhandelingen te activeren of om personen te filteren door de activiteit &quot;Doorsturen naar vriend&quot; te verzenden en ontvangen.

Als u op &#39;forward&#39; zoekt in de slimme lijst van een slimme campagne, vindt u de beschikbare triggers en filters.

![](assets/nineteen.png)

## Test door naar vriend {#test-forward-to-friend}

Als u &quot;Doorsturen naar vriend&quot; wilt testen, stuurt u uzelf een e-mail met de koppeling Volgende. Zorg ervoor dat u het formulier verzendt via de stap E-mail **** verzenden, *niet* via Test-e-mail **** verzenden.
