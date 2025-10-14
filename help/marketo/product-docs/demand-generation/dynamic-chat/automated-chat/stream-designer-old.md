---
description: Stream Designer - Marketo Docs - Productdocumentatie
title: Stream Designer
hide: true
hidefromtoc: true
feature: Dynamic Chat
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '1103'
ht-degree: 0%

---

# Stream Designer {#stream-designer}

Er zijn _vele_ mogelijke stroomcombinaties. Dit artikel bevat een voorbeeld waarin de marketeter de sitebezoeker vraagt of hij productvragen heeft. Zo ja, dan kan de bezoeker een afspraak plannen. Zo neen, dan kan de bezoeker zich bij een mailinglijst aansluiten voor toekomstige correspondentie. Ze krijgen ook een gratis PDF aangeboden. Het uiteindelijke doel is of een afspraak te plannen of de e-mail van de bezoeker te verzamelen.

>[!PREREQUISITES]
>
>Alvorens u de kaart van het Document kunt gebruiken, moet u het eerst [&#x200B; opstelling &#x200B;](/help/marketo/product-docs/demand-generation/dynamic-chat/integrations/adobe-pdf-embed-api.md){target="_blank"} in uw rekening van Adobe.

## Designer-kaarten streamen {#stream-designer-cards}

De stroom Designer bevat veelvoudige kaarten u kunt toevoegen om het praatjegesprek te vormen.

<table>
 <tr>
  <td style="width:25%"><strong>Bericht</strong></td>
  <td>Wordt gebruikt wanneer u een instructie wilt maken zonder dat er een reactie nodig is (bijvoorbeeld: "Hallo! Alle items zijn vandaag 25% korting met code SAVE25").
</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Vraag</strong></td>
  <td>Wordt gebruikt wanneer u een meerkeuzevraag wilt stellen, waarvoor u de beschikbare antwoorden kunt opgeven (bijvoorbeeld: Welk type voertuig bent u geïnteresseerd? Reacties = SUV, Compact, Truck, enz.).</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Document</strong></td>
  <td>Hiermee kunt u PDF-documenten insluiten in dialoogvensters en de activiteit van bezoekers in de documentbetrokkenheid bijhouden (hoeveel pagina's zijn weergegeven, of het document is gedownload en/of welke zoektermen zijn gebruikt).</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Gegevens vastleggen</strong></td>
  <td>Wordt gebruikt wanneer u gegevens wilt verzamelen (bijvoorbeeld naam, e-mailadres, functie, enz.). Nadat u hebt bepaald op welk veld de reactie moet worden toegeschreven, kunt u kiezen of de bezoeker zijn reactie laat typen of opties in een keuzelijst selecteert die u bepaalt (tip: de laatste kan helpen met de schoonheid van de database). U kunt er ook voor kiezen om de gegevens die u momenteel voor hen hebt vermeld, te overschrijven met hun antwoord, of de vraag volledig over te slaan als u al een waarde voor hen hebt.</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Vergaderingreservering</strong></td>
  <td>Biedt de bezoeker een kalender met beschikbare datums om een vergadering te plannen. Kies de kalenderbeschikbaarheid via ronde lijn, een specifieke agent, of het gebruiken van douaneregels. Klik <b> voeg Attribuut </b> toe als u de naam of e-mailadres van de agent wilt vangen en het aan het de persoonverslag van de praatjebezoeker voor toekomstig het vragen (uiteinde: creeer a <a href="/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md" target="_blank"> douanegebied </a> om de informatie van de agent aan in kaart te brengen zoals om een standaard gebied van Marketo Engage niet te beschrijven) toe.</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Doel</strong></td>
  <td>Dit is de enige kaart die bezoekers niet zullen zien. Het is aan u om te bepalen op welk punt een doel binnen de specifieke praatje wordt bereikt (bijvoorbeeld: als het verzamelen van de e-mail van de bezoeker uw doel is, plaats de Goal kaart onmiddellijk na Info vangt in de stroom).</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Actie*</strong></td>
  <td>Gelijkaardig aan verborgen gebieden in een vorm, met de actiekaart kunt u om het even welk lood of bedrijfattribuut (dat a <a href="/help/marketo/product-docs/administration/field-management/custom-field-type-glossary.md#string"> type van koordgegevens </a>) met impliciete waarden bevolken die u tegen een loodverslag zou willen vangen. U kunt de actiekaart op elk punt in het gesprek toevoegen en respectieve attributen met een waarde of inheemse tokens bijwerken die automatisch de respectieve waarde bevolken.
  <p><i>* Voor de actiekaart is Dynamic Chat Prime vereist. Neem contact op met het Adobe-accountteam (uw accountmanager) voor meer informatie.</i></td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Live Chat</strong></td>
  <td>Gebruik de live chatkaart wanneer bezoekers met een live agent willen chatten.
  <li>De live chatkaart moet de laatste kaart in de vertakking zijn.</li>
  <li>Bezoekers worden naar een agent geleid zodra ze deze kaart in de stream bereiken. Het wordt daarom aanbevolen om aan deze kaart een vraagkaart toe te voegen waarin bezoekers wordt gevraagd of ze met een liveagent willen chatten.</li></td>
 </tr>
</table>

## Designer-pictogrammen streamen {#stream-designer-icons}

Rechtsboven in de Stream Designer ziet u een handvol pictogrammen. Dit is wat ze doen.

<table>
 <tr>
  <td style="width:10%"><img src="assets/stream-designer-1.png"></td>
  <td>Inzoomen, grotere kaarten maken</td>
 </tr>
 <tr>
  <td style="width:10%"><img src="assets/stream-designer-2.png"></td>
  <td>Uitzoomen, kleinere kaarten maken</td>
 </tr>
 <tr>
  <td style="width:10%"><img src="assets/stream-designer-3.png"></td>
  <td>Hiermee opent u een venster waarin u uw chat kunt testen (druk op dezelfde knop om te sluiten)</td>
 </tr>
 <tr>
  <td style="width:10%"><img src="assets/stream-designer-4.png"></td>
  <td>Hiermee kunt u zoeken naar kaarttypen of inhoud in uw stream</td>
 </tr>
 <tr>
  <td style="width:10%"><img src="assets/stream-designer-5.png"></td>
  <td>Hiermee rangschikt u alle kaarten in uw stream</td>
 </tr>
</table>

## Een stream maken {#create-a-stream}

U kunt stromen voor Dialogen tot stand brengen of [&#x200B; Conversational Forms &#x200B;](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/conversational-flow-overview.md){target="_blank"}. In dit voorbeeld maken we er een voor een dialoogvenster.

1. Nadat u [&#x200B; uw Dialoog &#x200B;](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/create-a-dialogue.md){target="_blank"} hebt gecreeerd, klik het **[!UICONTROL Stream Designer]** lusje.

   ![](assets/stream-designer-6.png)

1. Sleep de [!UICONTROL Question] -kaart en zet deze neer.

   ![](assets/stream-designer-7.png)

1. Geef onder [!UICONTROL Chatbot Response] aan hoe u wilt.

   ![](assets/stream-designer-8.png)

   >[!TIP]
   >
   >U kunt de ervaring voor bekende chatsbezoekers aanpassen door tokens te gebruiken (bijvoorbeeld: Hello `{{lead.leadFirstName:""}}`). Klik gewoon op het pictogram voor het accolade rechts en maak een selectie. Voeg een standaardwaarde tussen de quoates toe als u anonieme bezoekers iets soortgelijks wilt laten zien (bijvoorbeeld: Hello `{{lead.leadFirstName:"there"}}`).

   >[!NOTE]
   >
   >Poke is standaard ingesteld op Aan, waardoor de openingsvraag naast het chatpictogram wordt weergegeven zonder dat de bezoeker erop moet klikken om deze te zien. Poke is slechts beschikbaar op de eerste kaart in het gesprek.

1. Voer uw gebruikersreacties in en klik op **[!UICONTROL Save]** .

   ![](assets/stream-designer-9.png)

   >[!NOTE]
   >
   >**[!UICONTROL Edit Stored Values]** is een optionele stap voor gebruikers die een andere waarde in de database willen opslaan dan de waarde die bezoekers in de chatbot krijgen weergegeven voor toegewezen kenmerken in de vraagkaart (bezoekers zien bijvoorbeeld &#39;Zoekmachine optimaliseren&#39;, en slaan die waarde op als &#39;SEO&#39;.)

1. Voor &quot;ja&quot;willen wij een benoeming plannen, zodat onder die optie belemmering over de kaart van de Planner van de Benoeming.

   ![](assets/stream-designer-10.png)

1. Klik in de kolom aan de rechterkant op **[!UICONTROL Save]** .

   ![](assets/stream-designer-11.png)

1. Aangezien dat een doel is, sleept u de [!UICONTROL Goal] -kaart onder de Planner voor benoemingen.

   ![](assets/stream-designer-12.png)

1. Geef uw doel een naam (of kies een bestaand doel) en klik op **[!UICONTROL Save]** .

   ![](assets/stream-designer-13.png)

1. Voor &quot;Nee&quot; willen we zien of ze zich bij de mailinglijst voegen. Sleep dus onder deze optie over een andere [!UICONTROL Question] -kaart.

   ![](assets/stream-designer-14.png)

1. Voer uw reactie in en voeg antwoordopties toe voor de bezoeker. Klik op **[!UICONTROL Save]** als u klaar bent.

   ![](assets/stream-designer-15.png)

   >[!NOTE]
   >
   >U kunt meer reacties toevoegen door op **[!UICONTROL Add Response]** te klikken.

1. Onder het antwoord &quot;Ja&quot; sleept u over de kaart voor het vastleggen van gegevens, zodat u de e-mail van de bezoeker kunt verzamelen.

   ![](assets/stream-designer-16.png)

1. Klik op de vervolgkeuzelijst **[!UICONTROL Type]** en selecteer **[!UICONTROL Email]** .

   ![](assets/stream-designer-17.png)

1. Voer een chatbotbericht en tijdelijke aanduiding in. Controleer of het kenmerk is toegewezen aan het desbetreffende veld in Marketo Engage en klik op **[!UICONTROL Save]** .

   ![](assets/stream-designer-18.png)

   <table>
    <tr>
     <td style="width:30%"><strong>Type</strong></td>
     <td>Het type informatie dat u wilt vastleggen: Telefoon, Tekst, E-mail.</td>
    </tr>
    <tr>
     <td style="width:30%"><strong>Chatbotbericht</strong></td>
     <td>Het bericht dat de bezoeker ziet hen ertoe aanzetten om de info te verstrekken.</td>
    </tr>
    <tr>
     <td style="width:30%"><strong>Plaatsaanduiding</strong></td>
     <td>Voorbeeldtekst waarmee de bezoeker kan zien wat er moet worden ingevoerd.</td>
    </tr>
    <tr>
     <td style="width:30%"><strong>Reactie toewijzen aan kenmerk</strong></td>
     <td>Hiermee kunt u de reactie van de bezoeker synchroniseren naar het corresponderende veld in de Person-record in uw Marketo Engage-abonnement.</td>
    </tr>
   </table>

1. Aangezien het verzamelen van hun e-mail een doel is, sleept u de [!UICONTROL Goal] -kaart onder Info Vastleggen.

   ![](assets/stream-designer-19.png)

1. Geef uw doel een naam (of kies een bestaand doel) en klik op **[!UICONTROL Save]** .

   ![](assets/stream-designer-20.png)

1. Vergeet niet een reactie toe te voegen als ze &quot;Nee&quot; zeggen. Een optie is om een berichtkaart hieronder te slepen en &quot;Toch bedankt&quot; te zeggen. In dit voorbeeld geven we ze een gratis PDF-document.

   ![](assets/stream-designer-21.png)

1. In dit voorbeeld maken we een nieuw document. Geef deze een naam, voer de URL in naar de PDF die u al hebt gehost en klik op **[!UICONTROL Save]** .

   ![](assets/stream-designer-22.png)

1. Selecteer de schakeloptie **[!UICONTROL Preview]** om een voorvertoning van het dialoogvenster weer te geven.

   ![](assets/stream-designer-23.png)

1. Klik op **[!UICONTROL Publish]** als u klaar bent om uw dialoogvenster te activeren.

   ![](assets/stream-designer-24.png)

>[!NOTE]
>
>Alvorens [!UICONTROL Publish] te klikken, herinner me om ervoor te zorgen u [&#x200B; uw doel URL(s) &#x200B;](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/audience-criteria.md#target){target="_blank"} hebt ingegaan.

>[!MORELIKETHIS]
>
>* [&#x200B; creeer een Dialoog &#x200B;](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/create-a-dialogue.md){target="_blank"}
>* [&#x200B; Criteria van de Publiek &#x200B;](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/audience-criteria.md){target="_blank"}
>* [&#x200B; Adobe PDF bed API &#x200B;](/help/marketo/product-docs/demand-generation/dynamic-chat/integrations/adobe-pdf-embed-api.md){target="_blank"} in
