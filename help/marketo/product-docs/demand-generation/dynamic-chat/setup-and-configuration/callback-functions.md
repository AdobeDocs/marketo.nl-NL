---
description: Callback-functies - Marketo Docs - Productdocumentatie
title: Callback-functies
feature: Dynamic Chat
exl-id: 5ae7f6cb-5c57-4257-8a1a-992c9602cfaa
source-git-commit: f355022fb7e6f733bb7485229e395b0fe1a9818f
workflow-type: tm+mt
source-wordcount: '616'
ht-degree: 0%

---

# Callback-functies {#callback-functions}

U kunt Dynamic Chat gebruiken widget callback functies om gespreksgebeurtenissen naar om het even welke derdeplatforms te verzenden.

## Aan de slag {#getting-started}

Deze gebeurtenis geeft aan dat de widget Dynamic Chat klaar is voor gebruik en wordt geactiveerd wanneer alle scripts die betrekking hebben op Dynamic Chat in de webpagina worden geladen.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    // code here will execute when chatbot scripts are loaded in a webpage 
}); 
```

## Gespreksgebeurtenissen {#conversation-events}

Deze gebeurtenissen hebben betrekking op een gesprek dat is gericht op een specifieke pagina voor een specifieke bezoeker.

### Gesprek geactiveerd

Een gesprek (bijvoorbeeld een dialoog) dat voor een websitebezoeker is bedoeld, wordt opgelost en het gesprek wordt aan hen getoond.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_TRIGGERED, (event) => { 
 // code here will execute when the chatbot is loaded for a visitor 
    }); 
});  
```

### Gesprek {#conversation-engaged}

Bezoeker heeft de chatbot ingeschakeld (bv. zijn eerste reactie gegeven).

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_ENGAGED, (event) => { 
 // code here will execute when a visitor engages with the chatbot 
     }); 
}); 
```

### Gesprek voltooid {#conversation-completed}

De bezoeker heeft het einde van het gesprek bereikt.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_COMPLETED, (event) => { 
 // code here will execute when a conversation is completed 
     }); 
}); 
```

### Gesloten gesprek

De bezoeker heeft het gesprek gesloten alvorens het eind te bereiken.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_CLOSED, (event) => { 
 // code here will execute when a conversation is closed 
    }); 
}); 
```

De `event` parameter is een voorwerp met meta-gegevens met betrekking tot het gesprek. U hebt toegang tot deze metagegevens via `event.data`.

Hier volgen enkele belangrijke waarden voor metagegevens die u kunt gebruiken:

<table>
<thead>
  <tr>
    <th style="width:75%">Metagegevens</th>
    <th style="width:25%">Attributen</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Naam van gesprek</td>
    <td>payload.name</td>
  </tr>
  <tr>
    <td>Gesprek-ID</td>
    <td>payload.id</td>
  </tr>
  <tr>
    <td>Type gesprek (dialoog/gespreksstroom)</td>
    <td>payload.type</td>
  </tr>
  <tr>
    <td>Type gebruikersinterface (popup/chatbot/inline)</td>
    <td>payload.uiType</td>
  </tr>
  <tr>
    <td>Sessie-id</td>
    <td>payload.sid</td>
  </tr>
</tbody>
</table>

## Invoergebeurtenissen bezoeker

Deze gebeurtenissen worden geactiveerd wanneer een bezoeker die een gesprek voert, zijn contactgegevens verstrekt (bijvoorbeeld een telefoonnummer of e-mailadres). Hieronder staan de gebeurtenissen die onder deze categorie vallen.

### Telefoonnummer {#phone-number}

Deze gebeurtenis wordt teweeggebracht wanneer een bezoeker hun telefoonaantal tijdens het gesprek verstrekt.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_INPUT_PHONE, (event) => { 
 // code here will execute when a visitor provides their phone number 
    }); 
});  
```

### E-mailid {#email-id}

Deze gebeurtenis wordt teweeggebracht wanneer een bezoeker hun e-mailadres tijdens het gesprek verstrekt.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_INPUT_EMAIL, (event) => { 
 // code here will execute when a visitor provides their email address 
    }); 
}); 
```

De `event` parameter is een voorwerp met meta-gegevens met betrekking tot het gesprek. U hebt toegang tot deze metagegevens via `event.data`.

Hier volgen enkele belangrijke waarden voor metagegevens die u kunt gebruiken:

<table>
<thead>
  <tr>
    <th style="width:75%">Metagegevens</th>
    <th style="width:25%">Attributen</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Naam van gesprek</td>
    <td>payload.name</td>
  </tr>
  <tr>
    <td>Gesprek-ID</td>
    <td>payload.id</td>
  </tr>
  <tr>
    <td>Type gesprek (dialoog/gespreksstroom)</td>
    <td>payload.type</td>
  </tr>
  <tr>
    <td>Type gebruikersinterface (popup/chatbot/inline)</td>
    <td>payload.uiType</td>
  </tr>
  <tr>
    <td>Sessie-id</td>
    <td>payload.sid</td>
  </tr>
</tbody>
</table>

## Gebeurtenissen voor het boeken van vergaderingen {#meeting-booking-events}

Deze gebeurtenissen worden geactiveerd wanneer een bezoeker een vergadering met uw bedrijfsvertegenwoordiger opneemt.

Hieronder staan de gebeurtenissen die onder deze categorie vallen.

### Vergadering geboekt {#meeting-booked}

Deze gebeurtenis wordt teweeggebracht wanneer een bezoeker een vergadering op de kalender van een agent boeken.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_MEETING_BOOKED, (event) => { 
 // code here will execute when a meeting is booked 
    }); 
}); 
```

De `event` parameter is een voorwerp met meta-gegevens met betrekking tot het gesprek. U hebt toegang tot deze metagegevens via `event.data`.

Hier volgen enkele belangrijke waarden voor metagegevens die u kunt gebruiken:

<table>
<thead>
  <tr>
    <th style="width:75%">Metagegevens</th>
    <th style="width:25%">Attributen</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Naam van gesprek</td>
    <td>payload.name</td>
  </tr>
  <tr>
    <td>Gesprek-ID</td>
    <td>payload.id</td>
  </tr>
  <tr>
    <td>Type gesprek (dialoog/gespreksstroom)</td>
    <td>payload.type</td>
  </tr>
  <tr>
    <td>Type gebruikersinterface (popup/chatbot/inline)</td>
    <td>payload.uiType</td>
  </tr>
  <tr>
    <td>Sessie-id</td>
    <td>payload.sid</td>
  </tr>
  <tr>
    <td>Naam agent</td>
    <td>payload.agentName</td>
  </tr>
  <tr>
    <td>Agent-id</td>
    <td>payload.agentID</td>
  </tr>
  <tr>
    <td>Vergaderinggegevens</td>
    <td>payload.meetingInfo</td>
  </tr>
</tbody>
</table>

## Live Chat-gebeurtenissen {#live-chat-events}

Deze gebeurtenissen worden geactiveerd wanneer een bezoeker verbinding maakt met een live agent tijdens zijn contact met de chatbot.

Hieronder staan de gebeurtenissen die onder deze categorie vallen.

### Live Chat aangevraagd {#live-chat-requested}

Deze gebeurtenis wordt teweeggebracht wanneer een bezoeker de optie selecteert om met een levende agent te babbelen en een beschikbare agent wordt opgelost.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_LIVE_CHAT_REQUESTED, (event) => { 
 // code here will execute when a visitor requests a live chat 
    }); 
}); 
```

### Live chat gestart {#live-chat-initiated}

Deze gebeurtenis wordt teweeggebracht wanneer een bezoeker de optie selecteert om met een levende agent te babbelen en een agent het praatje goedkeurt.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_LIVE_CHAT_INITIATED, (event) => { 
 // code here will execute after a live agent accepts the chat 
    }); 
}); 
```

### Live Chat beëindigd {#live-chat-ended}

Deze gebeurtenis wordt teweeggebracht wanneer een gesprek tussen een bezoeker en de levende agent beëindigt.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_LIVE_CHAT_ENDED, (event) => { 
 // code here will execute when a live chat is ended 
    }); 
}); 
```

### Time-out live chat {#live-chat-timeout}

Deze gebeurtenis wordt geactiveerd wanneer een live chatsgesprek wordt beëindigd omdat de bezoeker stopt met reageren, of ze zijn gestopt.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_LIVE_CHAT_REQUEST_TIMEOUT, (event) => { 
 // code here will execute when a visitor abandons a live chat 
    }); 
}); 
```

De `event` parameter is een voorwerp met meta-gegevens met betrekking tot het gesprek. U hebt toegang tot deze metagegevens via `event.data`.

Hier volgen enkele belangrijke waarden voor metagegevens die u kunt gebruiken:

<table>
<thead>
  <tr>
    <th style="width:75%">Metagegevens</th>
    <th style="width:25%">Attributen</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Naam van gesprek</td>
    <td>payload.name</td>
  </tr>
  <tr>
    <td>Gesprek-ID</td>
    <td>payload.id</td>
  </tr>
  <tr>
    <td>Type gesprek (dialoog/gespreksstroom)</td>
    <td>payload.type</td>
  </tr>
  <tr>
    <td>Type gebruikersinterface (popup/chatbot/inline)</td>
    <td>payload.uiType</td>
  </tr>
  <tr>
    <td>Sessie-id</td>
    <td>payload.sid</td>
  </tr>
  <tr>
    <td>Naam agent</td>
    <td>payload.agentName</td>
  </tr>
  <tr>
    <td>Agent-id</td>
    <td>payload.agentID</td>
  </tr>
</tbody>
</table>

Als u een van deze gebeurtenissen naar een analyseplatform zoals Adobe Analytics of Googles Analytics wilt verzenden, moet u de respectievelijke traceringsaanroep binnen deze Dynamic Chat-gebeurtenissen toevoegen. Het zou er ongeveer zo uitzien als het onderstaande voorbeeld.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_TRIGGERED, (event) => { 
 // Enter Adobe Analytics or Google Analytics function here 
    ga('send', 'event', { 
      eventCategory: Dynamic Chat Conversations', 
      eventAction: 'Conversation Triggered', 
      eventLabel: event.data.payload.id, 
    }); 
    }); 
}); 
```
