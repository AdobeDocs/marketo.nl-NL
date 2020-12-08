---
unique-page-id: 14352514
description: Hoe Verkoop Connect de-duplicatie van e-mail - Marketo Docs - Productdocumentatie behandelt
title: Hoe Verkoop Connect het uit-duwen van e-mail behandelt
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '104'
ht-degree: 0%

---


# Hoe Verkoop Connect het uit-duwen van e-mail behandelt {#how-sales-connect-handles-email-de-duping}

Wanneer u een CSV [-bestand](http://docs.marketo.com/x/VADb) uploadt naar Sales Connect, voegen we alles samen zoals contactpersonen in de CSV voordat het importeren plaatsvindt.

Dit doen we op basis van hetzelfde e-mailadres. Dus als er twee identieke e-mailadressen zijn, voegen we deze samen tot één contactpersoon.

Als u later probeert om manueel het zelfde contact toe te voegen/te uploaden, zullen wij niet het samenvoegen.

Als u probeert om een contact toe te voegen dat reeds in uw gegevensbestand is, zullen wij u verhinderen het toe te voegen.

