---
description: Stream Designer - Marketo Docs - Productdocumentatie
title: Stream Designer
exl-id: aa44c7a5-f81b-4029-a1a4-5439bea83847
source-git-commit: adf3a9f156ec5ed823a0647affb87f6c0686d35f
workflow-type: tm+mt
source-wordcount: '596'
ht-degree: 0%

---

# Stream Designer {#stream-designer}

Er zijn _veel_ streamcombinaties die u kunt maken. Dit artikel bevat een voorbeeld waarin de marketeter de sitebezoeker vraagt of hij productvragen heeft. Zo ja, dan kan de bezoeker een afspraak plannen. Zo neen, dan kan de bezoeker zich bij een mailinglijst aansluiten voor toekomstige correspondentie. Het doel is een afspraak te plannen of de e-mail van de bezoeker te verzamelen.

## Streaming Designer-kaarten {#stream-designer-cards}

De stroomontwerper bevat veelvoudige kaarten u kunt toevoegen om het praatjegesprek te vormen.

<table>
 <tr>
  <td><strong>Bericht</strong></td>
  <td>Wordt gebruikt wanneer u een instructie wilt maken zonder reactie nodig (bijvoorbeeld: "Hoi! Alle items zijn vandaag 25% korting met code SAVE25").
</td>
 </tr>
 <tr>
  <td><strong>Vraag</strong></td>
  <td>Gebruik deze optie wanneer u een meerkeuzevraag wilt stellen, waarvan u de beschikbare antwoorden kunt opgeven (bijvoorbeeld: Welk type voertuig interesseert u? Reacties = SUV, Compact, Truck, enz.).</td>
 </tr>
 <tr>
  <td><strong>Gegevens vastleggen</strong></td>
  <td>Gebruik deze optie wanneer u gegevens wilt verzamelen. De drie velden waaruit u kunt kiezen zijn E-mailadres, Telefoonnummer en Tekst (zodat de bezoeker zijn eigen bericht kan schrijven).</td>
 </tr>
 <tr>
  <td><strong>Aanstellingsplanner</strong></td>
  <td>Biedt de bezoeker een kalender met beschikbare datums om een follow-up te plannen. De beschikbaarheid van kalenders weerspiegelt <a href="/help/marketo/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.md#routing">de volgende agent in lijn</a>.</td>
 </tr>
 <tr>
  <td><strong>Doel</strong></td>
  <td>Dit is de enige kaart die bezoekers niet zullen zien. Het is aan u om te bepalen op welk punt een doel binnen de specifieke praatje wordt bereikt (bijvoorbeeld: Als u de e-mail van de bezoeker wilt verzamelen, plaatst u de Goal-kaart onmiddellijk na Info Capture in de stream).</td>
 </tr>
</table>

## Een stream maken {#create-a-stream}

1. Nadat u [heeft uw dialoogvenster gemaakt](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/create-a-dialogue.md){target=&quot;_blank&quot;}, klikt u op de knop **Stream Designer** tab.

   ![](assets/create-a-stream-1.png)

1. Sleep de vraagkaart en zet deze neer.

   ![](assets/create-a-stream-2.png)

1. Geef onder Chatbot Response je vraag hoe je wilt.

   ![](assets/create-a-stream-3.png)

   >[!NOTE]
   >
   >Poke is standaard ingesteld op Aan, waardoor de openingsvraag naast het chatpictogram wordt weergegeven zonder dat de bezoeker erop moet klikken om deze te zien.

1. Voer uw gebruikersreacties in en klik op **Opslaan**.

   ![](assets/create-a-stream-4.png)

1. Voor &quot;ja&quot;willen wij een benoeming plannen, zodat onder die optie belemmering over de kaart van de Planner van de Aanstelling.

   ![](assets/create-a-stream-5.png)

1. Klik in de rechterkolom op **Opslaan**.

   ![](assets/create-a-stream-6.png)

1. Aangezien dat een doel is, sleep de Goal card onder de Planner van de Aanstelling.

   ![](assets/create-a-stream-7.png)

1. Geef uw doel een naam (of kies een bestaand doel) en klik op **Opslaan**.

   ![](assets/create-a-stream-8.png)

1. Voor &quot;Nee&quot; willen we zien of ze zich bij de mailinglijst voegen. Sleep dus onder deze optie over een andere vraagkaart.

   ![](assets/create-a-stream-9.png)

1. Voer uw reactie in en voeg antwoordopties toe voor de bezoeker. Klikken **Opslaan** wanneer gereed.

   ![](assets/create-a-stream-10.png)

   >[!NOTE]
   >
   >U kunt meer reacties toevoegen door te klikken op **Antwoord toevoegen**.

1. Onder het antwoord &quot;Ja&quot; sleept u over de kaart voor het vastleggen van gegevens, zodat u de e-mail van de bezoeker kunt verzamelen.

   ![](assets/create-a-stream-11.png)

1. Klik op de knop **Type** vervolgkeuzelijst en selecteer **E-mail**.

   ![](assets/create-a-stream-12.png)

1. Voer een chatbotbericht en tijdelijke aanduiding in. Controleer of het kenmerk is toegewezen aan het juiste veld in Marketo en klik op **Opslaan**.

   ![](assets/create-a-stream-13.png)

   <table>
    <tr>
     <td><strong>Type</strong></td>
     <td>Het type informatie dat u wilt vastleggen: Telefoon, tekst, e-mail.</td>
    </tr>
    <tr>
     <td><strong>Chatbotbericht</strong></td>
     <td>Het bericht dat de bezoeker ziet hen ertoe aanzetten om de info te verstrekken.</td>
    </tr>
    <tr>
     <td><strong>Plaatsaanduiding</strong></td>
     <td>Voorbeeldtekst waarmee de bezoeker kan zien wat er moet worden ingevoerd.</td>
    </tr>
    <tr>
     <td><strong>Reactie toewijzen aan kenmerk</strong></td>
     <td>Hiermee kunt u de reactie van de bezoeker synchroniseren naar het corresponderende veld in de Persoonlijke record in uw Marketo-abonnement.</td>
    </tr>
   </table>

1. Aangezien het verzamelen van hun e-mail een doel is, sleept u de Goal-kaart onder Info Vastleggen.

   ![](assets/create-a-stream-14.png)

1. Geef uw doel een naam (of kies een bestaand doel) en klik op **Opslaan**.

   ![](assets/create-a-stream-15.png)

1. Vergeet niet een reactie toe te voegen als ze &quot;Nee&quot; zeggen. Sleep een berichtenkaart onder die optie.

   ![](assets/create-a-stream-16.png)

1. Voer uw bericht in en klik op **Opslaan**.

   ![](assets/create-a-stream-17.png)

1. Selecteer **Voorvertoning** schakelen om een voorvertoning van het dialoogvenster weer te geven.

   ![](assets/create-a-stream-18.png)

1. Als u klaar bent om uw dialoogvenster te activeren, klikt u op **Publiceren**.

   ![](assets/create-a-stream-19.png)

>[!NOTE]
>
>Voordat u op Publiceren klikt, moet u controleren of u [doel-URL(&#39;s) ingevoerd](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/audience-criteria.md#target){target=&quot;_blank&quot;}.

>[!MORELIKETHIS]
>
>* [Een dialoogvenster maken](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/create-a-dialogue.md){target=&quot;_blank&quot;}
>* [Criteria voor het publiek](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/audience-criteria.md){target=&quot;_blank&quot;}
>* [Rapporten](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/reports.md){target=&quot;_blank&quot;}

