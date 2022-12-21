---
unique-page-id: 1900581
description: Doorsturen naar een vriendenlink in e-mails - Marketo Docs - Productdocumentatie
title: Doorsturen naar een vriendenkoppeling in e-mails
exl-id: 7addac65-4207-419f-845c-d6b2d08d299c
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '703'
ht-degree: 0%

---

# Doorsturen naar een vriendenkoppeling in e-mails {#forward-to-a-friend-link-in-emails}

Als u de koppeling &quot;Doorsturen naar vriend&quot; toevoegt aan uw e-mails, kunt u personen volgen die via deze koppeling een e-mailbericht hebben ontvangen en deze automatisch toevoegen als een nieuwe persoon als deze nog niet in de database aanwezig is.

Stel bijvoorbeeld dat Keith de koppeling &quot;Doorsturen naar vriend&quot; gebruikt om het e-mailbericht door te sturen naar een onbekende persoon, Mark. Mark wordt automatisch toegevoegd als een nieuwe persoon, krijgt zijn eigen cookie toegewezen en zijn e-mail- en webactiviteiten zijn aan hem gekoppeld. Nochtans, als Keith de voorwaartse knoop in zijn e-mailcliënt gebruikt, wordt Mark verkeerd gekookt als Keith, en zijn activiteit wordt geregistreerd als Keith.

## De koppeling toevoegen aan een e-mailsjabloon {#add-the-link-to-an-email-template}

1. Ga naar de **Design Studio**.

   ![](assets/one-8.png)

1. Zoek en selecteer de e-mailsjabloon waaraan u de koppeling wilt toevoegen. Klikken **Concept bewerken**.

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
   >We raden u niet aan de stijl te gebruiken **positie:relatief** in uw e-mailsjabloon. Het kan problemen veroorzaken met de positie en weergave van het vak &quot;Doorsturen naar vriend&quot;.

1. Klikken **Concept voorvertonen** om ervoor te zorgen dat de sjabloon er naar wens uitziet.

   ![](assets/four-5.png)

   >[!NOTE]
   >
   >Vergeet niet het sjabloonconcept goed te keuren om de wijzigingen toe te passen.

   Alle e-mails die van die sjabloon gebruikmaken, hebben nu de koppeling Doorsturen naar vriend. Wanneer de e-mailontvanger erop klikt, wordt hij of zij doorgestuurd naar een webversie van het e-mailbericht met het vak &quot;Doorsturen naar een vriend&quot;:

   ![](assets/f2afbox.png)

## De koppeling toevoegen aan een afzonderlijke e-mail {#add-the-link-to-an-individual-email}

U kunt ook de koppeling Doorsturen naar vriend rechtstreeks toevoegen aan een e-mail.

1. Open het e-mailbericht waarin u de koppeling wilt opnemen en dubbelklik in het bewerkbare gebied.

   ![](assets/five-4.png)

1. Plaats de cursor op de gewenste locatie voor de koppeling en klik op de knop **Token invoegen** knop.

   ![](assets/six-2.png)

1. Selecteer **`{{system.forwardToFriendLink}}`** token.

   ![](assets/seven-1.png)

   >[!NOTE]
   >
   >Dit token is de URL van de webversie van de e-mail met het vak &quot;Doorsturen naar vriend&quot;.

1. Schrijf uit wat u wilt dat de weergavetekst van de koppeling is (bijvoorbeeld &quot;Doorsturen naar een vriend&quot;).

   ![](assets/seven-1.png)

1. Knip de **`{{system.forwardToFriendLink}}`** gebruiken met Ctrl+X (Windows) of Cmd+X (Mac). Markeer &quot;Doorsturen naar een vriend&quot; en klik op de knop **Koppeling invoegen/bewerken** knop.

   ![](assets/eight-1.png)

1. Plak de **`{{system.forwardToFriendLink}}`** token in de **URL** gebruiken met Ctrl/Cmd+V en vervolgens op **Invoegen**.

   ![](assets/nine.png)

1. Sla de bewerking op en bekijk een voorvertoning van de nieuwe koppeling.

   ![](assets/ten-1.png)

   >[!NOTE]
   >
   >Nieuwe personen die worden toegevoegd via een e-mailbericht &quot;Doorsturen naar een vriend&quot;, worden standaard niet meer geabonneerd op marketingberichten.

## Doorgestuurde activiteiten weergeven {#view-forwarding-activity}

U kunt zien wie de e-mails heeft doorgestuurd en ontvangen in het activiteitenlog van de persoon.

1. Ga naar de **`Database`**.

   ![](assets/db.png)

1. Dubbelklik op de persoon waarvoor u activiteit wilt weergeven.

   ![](assets/fourteen.png)

1. Ga naar de **Activiteitenlogboek** tab. Dubbelklikken **E-mail doorgestuurd naar vriend** of **Verzonden naar e-mail voor vriend** voor meer informatie.

   ![](assets/fifteen.png)

   >[!NOTE]
   >
   >**Definitie**
   >
   >Voor Doorsturen naar e-mail vriend is de persoon-id de persoon die het e-mailbericht heeft doorgestuurd.
   >
   >Voor Doorsturen naar e-mail vriend is de persoon-id de persoon die het e-mailbericht heeft ontvangen.

   ![](assets/sixteen.png)

1. Als u een persoon op ID wilt weergeven, kopieert en plakt u de **Persoon-id** aan het einde van de URL (het begin van de opgegeven URL is afhankelijk van uw Marketo-exemplaar):

   `<pre data-theme="Confluence">...marketo.com/Database/loadPersonDetail?personId=</pre>`

   >[!NOTE]
   >
   >Wij zullen de **Persoon-id** klikbaar en verbind rechtstreeks met de persoon in een aanstaande flard.

   ![](assets/seventeen.png)

   >[!NOTE]
   >
   >Als de vriend die de voorwaartse persoon ontvangt een onbekende persoon is, wordt een nieuwe persoon gecreeerd met &quot;Vooruit aan Vriend&quot;gemerkt als persoon **Bron**.
   >Als de e-mail een lokaal middel van een programma is, wordt het programma gemarkeerd als het **Overnameprogramma**.

## Trigger of filter die de Door:sturen Activiteit gebruiken {#trigger-or-filter-using-forwarding-activity}

Er zijn zes triggers/filters die u kunt gebruiken om flowhandelingen te activeren of om personen te filteren door de activiteit &quot;Doorsturen naar vriend&quot; te verzenden en ontvangen.

Als u op &#39;forward&#39; zoekt in de slimme lijst van een slimme campagne, vindt u de beschikbare triggers en filters.

![](assets/nineteen.png)

## Test door naar vriend {#test-forward-to-friend}

Als u &quot;Doorsturen naar vriend&quot; wilt testen, stuurt u uzelf een e-mail met de koppeling Volgende. Zorg ervoor dat u het object via de **E-mail verzenden** stroomstap, *niet* doorheen **Test-e-mail verzenden**.
