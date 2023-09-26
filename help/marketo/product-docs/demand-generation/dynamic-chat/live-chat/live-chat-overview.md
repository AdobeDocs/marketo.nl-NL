---
description: Live Chat - Overzicht - Marketo Docs - Productdocumentatie
title: Live Chat-overzicht
feature: Dynamic Chat
source-git-commit: 8b2eed5e28c46ea9c467fd25dd732c1654a09bed
workflow-type: tm+mt
source-wordcount: '322'
ht-degree: 0%

---

# Live Chat-overzicht {#live-chat-overview}

Met Live Chat kunnen websitebezoekers realtime chatgesprekken voeren met uw verkoopagenten.

## Actieve chatagents toevoegen {#add-live-chat-agents}

Om met levende praatje te beginnen, zult u uw levende praatjeagenten moeten toevoegen als [gebruikers in de Adobe Admin Console](/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users.md#add-a-chat-user){target="_blank"} and give them the [Live Chat permission](/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions.md){target="_blank"}. Nadat dit wordt gedaan, kunt u dan toevoegen [live chatkaart](#using-the-live-chat-card) naar een nieuwe of bestaande dialoog.

Wanneer bezoekers vragen om met een agent door uw Dialoog te chatten, zullen de agenten veelvoudige [meldingsopties](/help/marketo/product-docs/demand-generation/dynamic-chat/live-chat/agent-inbox.md#live-chat-notifications){target="_blank"}. When they click on the notification, they'll be taken to their [Agent Inbox](/help/marketo/product-docs/demand-generation/dynamic-chat/live-chat/agent-inbox.md){target="_blank"} waar ze met de bezoeker kunnen beginnen te praten .

## Live Chat-kaart gebruiken {#using-the-live-chat-card}

Live chat gebruiken op de [Stream Designer](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/stream-designer.md){target="_blank"} wanneer u bezoekers wilt chatten met een live agent.

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
   <td>Alle aangepaste regels worden doorlopen wanneer wordt overwogen waar de bezoeker moet worden geleid. Als de bezoeker niet in aanmerking komt voor een aangepaste regel, krijgen ze de opdracht <a href="/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/agent-management.md#live-chat-fallback" target="_blank">live chat fallback-bericht</a>.</td>
  </tr> 
  <tr> 
   <td><b>Team</b></td>
   <td>Kies een specifiek team om de chat te ontvangen. Als deze optie wordt gekozen, zal het rond robin binnen dat team worden toegewezen.</td>
  </tr>
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>[Agent Inbox](/help/marketo/product-docs/demand-generation/dynamic-chat/live-chat/agent-inbox.md){target="_blank"}
