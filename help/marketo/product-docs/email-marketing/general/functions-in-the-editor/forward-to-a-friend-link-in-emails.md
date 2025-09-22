---
unique-page-id: 1900581
description: Doorsturen naar een vriendenlink in e-mails - Marketo Docs - Productdocumentatie
title: Doorsturen naar een vriendenkoppeling in e-mails
exl-id: 7addac65-4207-419f-845c-d6b2d08d299c
feature: Email Editor
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '681'
ht-degree: 0%

---

# Doorsturen naar een vriendenkoppeling in e-mails {#forward-to-a-friend-link-in-emails}

Als u de koppeling &#39;Doorsturen naar vriend&#39; toevoegt aan uw e-mails, kunt u personen volgen die via deze koppeling een e-mailbericht hebben ontvangen en deze automatisch toevoegen als een nieuwe persoon als deze nog niet in de database staat.

Bijvoorbeeld, zeg gebruikt Keith de &quot;Vooruit aan Vriend&quot;verbinding om e-mail naar een onbekende persoon, Mark door te sturen. Mark wordt automatisch toegevoegd als een nieuwe persoon, krijgt zijn eigen cookie toegewezen en zijn e-mail- en webactiviteiten zijn aan hem gekoppeld. Nochtans, als Keith de voorwaartse knoop in zijn e-mailcliënt gebruikt, wordt Mark verkeerd gekookt als Keith, en zijn activiteit wordt geregistreerd als Keith.

## De koppeling toevoegen aan een e-mailsjabloon {#add-the-link-to-an-email-template}

1. Ga naar de **[!UICONTROL Design Studio]** .

   ![](assets/one-8.png)

1. Zoek en selecteer de e-mailsjabloon waaraan u de koppeling wilt toevoegen. Klik op **[!UICONTROL Edit Draft]**.

   ![](assets/two-7.png)

1. Plak de volgende HTML-code op de plaats waar u de koppeling Doorsturen naar vriend wilt weergeven (als u hulp nodig hebt met dit onderdeel, kunt u contact opnemen met uw webontwikkelaar):

   `<a href="{{system.forwardToFriendLink}}">Forward to Friend</a>`

   ![](assets/three-7.png)

   >[!TIP]
   >
   >
   >U kunt stijlen aan de koppeling toevoegen om deze er mooier uit te laten zien. Bijvoorbeeld:
   >
   >`<a href="{{system.forwardToFriendLink}}" style="font-family:arial, sans-serif; padding:10px; position:absolute; right:0px;">Forward to Friend</a>`

   >[!CAUTION]
   >
   >Wij adviseren niet gebruikend het stileren **positie:relative** in uw e-mailmalplaatje. Het kan problemen veroorzaken met de positie en weergave van het vak &#39;Doorsturen naar vriend&#39;.

1. Klik op **[!UICONTROL Preview Draft]** om te controleren of de sjabloon er naar wens uitziet.

   ![](assets/four-5.png)

   >[!NOTE]
   >
   >Vergeet niet het sjabloonconcept goed te keuren om de wijzigingen toe te passen.

   Alle e-mails die van die sjabloon gebruikmaken, hebben nu de koppeling Doorsturen naar vriend. Wanneer de e-mailontvanger erop klikt, wordt hij of zij doorgestuurd naar een webversie van de e-mail met het vak &#39;Doorsturen naar een vriend&#39;:

   ![](assets/f2afbox.png)

## De koppeling toevoegen aan een afzonderlijke e-mail {#add-the-link-to-an-individual-email}

U kunt ook de koppeling Doorsturen naar vriend rechtstreeks toevoegen aan een e-mail.

1. Open het e-mailbericht waarin u de koppeling wilt opnemen en dubbelklik in het bewerkbare gebied.

   ![](assets/five-4.png)

1. Plaats de curseur waar u de verbinding wilt verschijnen en de **Symbolische knoop van het Tussenvoegsel** klikken.

   ![](assets/six-2.png)

1. Selecteer het token **`{{system.forwardToFriendLink}}`** .

   ![](assets/seven-1.png)

   >[!NOTE]
   >
   >Dit token is de URL van de webversie van de e-mail met het vak &#39;Doorsturen naar vriend&#39;.

1. Schrijf uit wat u wilt dat de weergavetekst van de koppeling is (bijvoorbeeld &quot;Doorsturen naar een vriend&quot;).

   ![](assets/seven-1.png)

1. Knip het token **`{{system.forwardToFriendLink}}`** met Ctrl+X (Windows) of Cmd+X (Mac). Markeer &quot;door:sturen aan een vriend&quot;en klik **Tussenvoegsel/geef Verbinding** knoop uit.

   ![](assets/eight-1.png)

1. Plak het **`{{system.forwardToFriendLink}}`** teken in het **URL** vakje gebruikend Ctrl/Cmd+V, dan klik **[!UICONTROL Insert]**.

   ![](assets/nine.png)

1. Sla de bewerking op en bekijk een voorvertoning van de nieuwe koppeling.

   ![](assets/ten-1.png)

   >[!NOTE]
   >
   >Nieuwe personen die worden toegevoegd via een e-mailbericht &#39;Doorsturen naar een vriend&#39;, worden standaard niet meer geabonneerd op marketingberichten.

## Doorgestuurde activiteiten weergeven {#view-forwarding-activity}

U kunt zien wie de e-mails in het activiteitenlog van de persoon heeft doorgestuurd en ontvangen.

1. Ga naar de **[!UICONTROL Database]** .

   ![](assets/db.png)

1. Dubbelklik op de persoon waarvoor u activiteit wilt weergeven.

   ![](assets/fourteen.png)

1. Ga naar de tab **[!UICONTROL Activity Log]** . Dubbelklik op **[!UICONTROL Received Forward to Friend Email]** of **[!UICONTROL Sent Forward to Friend Email]** om details weer te geven.

   ![](assets/fifteen.png)

   >[!NOTE]
   >
   >**Definitie**
   >
   >Voor Doorsturen naar e-mail vriend is de persoon-id de persoon die het e-mailbericht heeft doorgestuurd.
   >
   >Voor Doorsturen naar e-mail vriend is de persoon-id de persoon die het e-mailbericht heeft ontvangen.

   ![](assets/sixteen.png)

1. Om een persoon door identiteitskaart te bekijken, kopieer en plak **identiteitskaart van de Persoon** aan het eind van URL (het begin van URL zal van uw instantie van Marketo afhangen):

   `...marketo.com/Database/loadPersonDetail?personId=`

   >[!NOTE]
   >
   >We maken de **[!UICONTROL Person ID]** klikbaar en koppelen deze rechtstreeks aan de persoon in een volgende patch.

   ![](assets/seventeen.png)

   >[!NOTE]
   >
   >Als de vriend die voorwaarts ontvangen een onbekende persoon is, wordt een nieuwe persoon gecreeerd met &quot;Vooruit aan Vriend&quot;duidelijk zoals de persoon **Source**.
   >Als e-mail een lokaal bezit van een programma is, is het programma duidelijk als het van de persoon **Verwerving Programma**.

## Trigger of filter die de Door:sturen Activiteit gebruiken {#trigger-or-filter-using-forwarding-activity}

Er zijn zes triggers/filters die u kunt gebruiken om flowhandelingen te activeren of om mensen te filteren door de activiteit &#39;Doorsturen naar vriend&#39; te verzenden en ontvangen.

Als u op &#39;forward&#39; zoekt in de slimme lijst van een slimme campagne, vindt u de beschikbare triggers en filters.

![](assets/nineteen.png)

## Test door naar vriend {#test-forward-to-friend}

Als u &#39;Doorsturen naar vriend&#39; wilt testen, stuurt u uzelf een e-mail met de koppeling Volgende. Zorg ervoor u het door **verzendt verzendt e-mail** stroomstap, *niet* door **verzendt e-mail van de Test**.
