---
unique-page-id: 14352514
description: Hoe Sales Connect de-duplicatie van e-mail afhandelt - Marketo Docs - Productdocumentatie
title: Hoe Verkoop Connect het uit-duwen van e-mail behandelt
exl-id: 1f57d943-8439-4653-a4e7-6dac65b3312d
feature: Marketo Sales Connect
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '96'
ht-degree: 0%

---

# Hoe [!DNL Sales Connect] het dedupliceren van e-mail afhandelt {#how-sales-connect-handles-email-de-duping}

Wanneer u [ een CSV ](/help/marketo/product-docs/marketo-sales-connect/people/managing-contacts/import-contacts-via-csv.md) dossier in [!DNL Sales Connect] uploadt, voegen wij allen als contacten in CSV samen alvorens de invoer plaatsvindt.

Dit doen we op basis van hetzelfde e-mailadres. Dus als er twee identieke e-mailadressen zijn, voegen we deze samen tot één contactpersoon.

Als u later probeert om manueel het zelfde contact toe te voegen/te uploaden, zullen wij niet het samenvoegen.

Als u probeert om een contact toe te voegen dat reeds in uw gegevensbestand is, zullen wij u verhinderen het toe te voegen.
