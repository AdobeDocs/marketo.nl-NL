---
description: Melding - Websocketverbinding - Marketo Docs - Productdocumentatie
title: Melding - Websocketverbinding
hide: true
hidefromtoc: true
exl-id: 00c754f8-3850-4209-803d-5cdb108dc6dc
source-git-commit: eb3e7983f7521d025dff1f5d79b8caeaeb0f622c
workflow-type: tm+mt
source-wordcount: '114'
ht-degree: 0%

---

# Melding: Websocketverbinding {#notification-websocket-connection}

Dit document is bestemd voor gebruikers van Marketo&#39;s Engage die de volgende melding hebben ontvangen in hun Marketo-exemplaar: `"We were unable to establish a websocket connection to <some-server.adobe.net>. We are ending support of the servers you are currently connected to. Please work with your IT Team to allowlist required Marketo Engage and Adobe domains and ports to prevent access disruptions."`

Als u of uw organisatie restrictieve firewall of proxyserverinstellingen gebruikt, moet u of uw netwerkbeheerder bepaalde domeinen en IP-adresbereiken lijsten van gewenste personen om ervoor te zorgen dat Adobe Marketo Engage naar behoren werkt.

Marketo Support is niet ingesteld als hulp bij de implementatie van de onderstaande protocollen. Als u hulp nodig hebt, kunt u dit document delen met uw IT-team. Als deze webtoegang beperken via een lijst van gewenste personen, vraagt u de volgende domeinen (inclusief het sterretje) toe te voegen om alle Marketo-bronnen en -websockets toe te staan:

* `*.marketo.com`
* `*.marketodesigner.com`
* `*.mktoweb.com`
* `*.experience.adobe.com`
* `*.adobe.net`
