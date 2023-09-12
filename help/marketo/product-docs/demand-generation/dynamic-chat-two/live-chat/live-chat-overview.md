---
description: Live Chat - Overzicht - Marketo Docs - Productdocumentatie
title: Live Chat-overzicht
hide: true
hidefromtoc: true
feature: Dynamic Chat
source-git-commit: a4fe70e1a95ff382499800049f161d1ad7dec7ab
workflow-type: tm+mt
source-wordcount: '239'
ht-degree: 0%

---

# Live Chat-overzicht {#live-chat-overview}

Live chat gebruiken op de [Stream Designer](/help/marketo/product-docs/demand-generation/dynamic-chat-two/automated-chat/stream-designer.md){target="_blank"} wanneer u bezoekers wilt chatten met een live agent.

## Live Chat-kaart gebruiken {#using-the-live-chat-card}

![](assets/live-chat-overview-1.png)

>[!IMPORTANT]
>
>De live chatkaart moet altijd de laatste kaart in de vertakking zijn. Als de kaart in een willekeurig punt in de tak wordt geplaatst, zou het de bezoeker kunnen verrassen door hen plotseling met een agent te verbinden.

### Aanbevolen procedures {#best-practices}

* Gebruik een vraagkaart vóór de livechatkaart en vraag de bezoeker of ze verbinding willen maken.
* Nadat de bezoeker de verbinding heeft gemaakt, gebruikt u de kaart voor het vastleggen van gegevens om bepaalde gegevens te verzamelen, zoals voornaam/achternaam, e-mailadres, functie, enz. (We raden u aan ten minste een voornaam en een e-mailadres aan te vragen.)

## Opties voor live-chatkaart {#live-chat-card-options}

Als u op de live chatkaart in de stream klikt, kunt u kiezen hoe de bezoeker wordt gerouteerd. Kies uit ronde robin, een agent, douaneregels, of een team.

![](assets/live-chat-overview-2.png)

<table> 
 <tbody> 
  <tr> 
   <td><b>Round Robin</b></td>
   <td>Chats worden toegewezen aan agenten in opeenvolgende orde.</td>
  </tr> 
  <tr> 
   <td><b>Agent</b></td>
   <td>Kies een specifieke agent om de chat te ontvangen.</td>
  </tr>
    <tr> 
   <td><b>Aangepaste regels</b></td>
   <td>Alle aangepaste regels worden doorlopen wanneer wordt overwogen waar de bezoeker moet worden geleid. Als de bezoeker niet in aanmerking komt voor een aangepaste regel, krijgen ze de opdracht <a href="/help/marketo/product-docs/demand-generation/dynamic-chat-two/setup-and-configuration/agent-management.md#live-chat-fallback" target="_blank">live chat fallback-bericht</a>.</td>
  </tr> 
  <tr> 
   <td><b>Team</b></td>
   <td>Kies een specifiek team om de chat te ontvangen. Als deze optie wordt gekozen, zal het rond robin binnen dat team worden toegewezen.</td>
  </tr>
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>[Agent Inbox](/help/marketo/product-docs/demand-generation/dynamic-chat-two/live-chat/agent-inbox.md){target="_blank"}
