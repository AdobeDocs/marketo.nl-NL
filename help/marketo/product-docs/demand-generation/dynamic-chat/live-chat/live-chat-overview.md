---
description: Live Chat - Overzicht - Marketo Docs - Productdocumentatie
title: Live Chat-overzicht
feature: Dynamic Chat
exl-id: 44e8b249-b534-4cec-a612-daa184acd266
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '842'
ht-degree: 0%

---

# Live Chat-overzicht {#live-chat-overview}

Met Live Chat kunnen websitebezoekers realtime chatgesprekken voeren met uw verkoopagenten.

>[!NOTE]
>
>Voor de gebruikers van het Dynamic Chat Select-pakket is live chat een proeffunctie met een levenslange limiet van 100 opdrachten. Wanneer deze limiet is bereikt, worden bezoekers die vragen te chatten met een live agent niet verbonden en ontvangen ze in plaats daarvan het algemene fallback-bericht. Neem contact op met uw Adobe-accountvertegenwoordiger om de upgradeopties voor pakketten te bespreken.

## Actieve chatagents toevoegen {#add-live-chat-agents}

Om met levend praatje begonnen te worden, zult u uw levende praatjeagenten als [ gebruikers in Adobe Admin Console ](/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users.md#add-a-chat-user){target="_blank"} moeten toevoegen en hen de [ Levende toestemming van het Praatje ](/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions.md){target="_blank"} geven. Nadat dit wordt gedaan, kunt u a [ levende praatjekaart ](#using-the-live-chat-card) aan een nieuwe of bestaande Dialoog dan toevoegen.

Wanneer de bezoekers om met een agent door uw Dialoog verzoeken te babbelen, zullen de agenten veelvoudige [ berichtopties ](/help/marketo/product-docs/demand-generation/dynamic-chat/live-chat/agent-inbox.md#live-chat-notifications){target="_blank"} hebben. Wanneer zij op het bericht klikken, zullen zij aan hun [ Agent Inbox ](/help/marketo/product-docs/demand-generation/dynamic-chat/live-chat/agent-inbox.md){target="_blank"} worden genomen waar zij met de bezoeker kunnen beginnen te chatten.

>[!NOTE]
>
>De live agent avatar gebruikt de profielafbeelding uit het Adobe-accountprofiel van de agent. Om het beeld bij te werken, volg [ deze stappen ](https://helpx.adobe.com/manage-account/using/edit-adobe-account-personal-profile.html){target="_blank"}.

## Live Chat-kaart gebruiken {#using-the-live-chat-card}

Gebruik de levende praatjekaart in de [ Stream Designer ](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/stream-designer.md){target="_blank"} wanneer u bezoekers met een levende agent wilt chatten.

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
   <td>Alle aangepaste regels worden doorlopen wanneer wordt overwogen waar de bezoeker moet worden geleid. Als de bezoeker niet voor om het even welke douaneregel kwalificeert, krijgen zij het <a href="/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/agent-management.md#live-chat-fallback" target="_blank"> levende bericht van de praatjefallback </a>.</td>
  </tr>
  <tr>
   <td><b>Team</b></td>
   <td>Kies een specifiek team om de chat te ontvangen. Als deze optie wordt gekozen, zal het rond robin binnen dat team worden toegewezen.</td>
  </tr>
 </tbody>
</table>

## Live Chatmeldingen {#live-chat-notifications}

>[!IMPORTANT]
>
>Als u browsermeldingen voor live chat wilt ontvangen, moeten alle actieve chatagents browsermeldingen voor Dynamic Chat inschakelen wanneer hierom wordt gevraagd.

### Meldingen inschakelen {#enabling-notifications}

Live chat-agents zien een banner boven aan het scherm wanneer ze zich aanmelden met de tekst &quot;Schakel browsermeldingen in om live chatmeldingen te ontvangen.&quot; Klik **toelaten**.

![](assets/live-chat-overview-4.png)

Live chat-agents worden vervolgens door de browser gevraagd om meldingen weer te geven. Klik **toestaan**.

![](assets/live-chat-overview-5.png)

Als de agenten browser geen berichten zelfs na het toestaan in browser krijgen, kunnen zij berichten voor browser in de OS berichtmontages moeten toelaten:

[ Stappen voor Mac ](https://support.apple.com/guide/mac-help/change-notifications-settings-mh40583/mac){target="_blank"}

[ Stappen voor Vensters ](https://support.microsoft.com/en-us/windows/change-notification-settings-in-windows-8942c744-6198-fe56-4639-34320cf9444e){target="_blank"}

### Wanneer een Levende Chat aan een Agent wordt verpletterd {#when-a-live-chat-is-routed-to-an-agent}

Wanneer een levende praatje aan een agent wordt verpletterd, zullen zij een blauwe banner over de bovenkant van het scherm zien die hen vragen om goed te keuren, evenals een berichtgeluid helpen gemiste berichten verhinderen.

![](assets/live-chat-overview-3.png)

>[!TIP]
>
>U kunt ook browsermeldingen instellen. Hiermee wordt u gewaarschuwd voor het geval u niet bent aangemeld bij Dynamic Chat.
>
>* Laat browser berichten in [ Google Chrome ](https://support.google.com/chrome/answer/3220216?hl=en&co=GENIE.Platform%3DDesktop){target="_blank"} toe
>* Laat browser berichten in [ Mozilla Firefox ](https://support.mozilla.org/en-US/kb/push-notifications-firefox){target="_blank"} toe

### Mislukte meldingen van handelingen {#failed-action-notifications}

Wanneer een handeling zoals het boeken van een vergadering of een live chat mislukt, worden gebruikers via e-mail op de hoogte gesteld.

![](assets/live-chat-overview-6.png)

### Notities {#things-to-note}

* De agenten hebben 100 seconden om vóór de &quot;Accept praatjetijden uit te antwoorden. Na dat, zullen de bezoekers het [ fallback bericht ](/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/agent-management.md#live-chat-fallback){target="_blank"} ontvangen. Voor de abonnees van Dynamic Chat Prime die de verpletterende optie hebben die aan **wordt geplaatst Team**, zal één meer agent worden geprobeerd alvorens het reservebericht verschijnt.
* Op dit moment geldt een limiet van 10 actieve chats per agent.
* Agent Inbox is enkel voor Levende Chatgesprekken. Als het praatje niet door een agent wordt goedgekeurd, zal het niet in de Agent Inbox verschijnen, aangezien het niet als Levende Chat kwalificeert.
* Het lusje van de Gesprek toont al gesprek, zowel Levend als Geautomatiseerde praatje. Zo als een gesprek niet door de agent wordt goedgekeurd, zal dat in het Lusje van de Gesprek worden vermeld. Er is tot een vertraging van 24 uur in het lusje van de Gesprek, aangezien het geen real time is. Agent Inbox, echter, is realtime.
* Als er geen praatjeactiviteit na 10 minuten (door of de agent of de bezoeker) is, zal de chat onderbreking.
* Als een agent hun profielbeeld (in account.adobe.com) _tijdens_ Levende Chat verandert, zal de bezoeker nog het oude beeld zien tot de praatjeeinden. De bezoeker ziet de nieuwe afbeelding wanneer hij of zij de volgende keer inchatt en de agent krijgt.

>[!MORELIKETHIS]
>
>[ Agent Inbox ](/help/marketo/product-docs/demand-generation/dynamic-chat/live-chat/agent-inbox.md){target="_blank"}
