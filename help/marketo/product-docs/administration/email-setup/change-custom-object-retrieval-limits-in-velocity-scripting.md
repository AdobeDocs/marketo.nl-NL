---
description: Aangepaste objectophaallimieten wijzigen in snelheidsscripts - Marketo Docs - Productdocumentatie
title: Limieten voor het ophalen van aangepaste objecten wijzigen in snelheidsscripts
exl-id: ef45205e-421d-4d1d-8c9d-7d627326a90c
source-git-commit: aeaf1f55b81da70ac8415cab265165a3848b5a0e
workflow-type: tm+mt
source-wordcount: '248'
ht-degree: 0%

---

# Limieten voor het ophalen van aangepaste objecten wijzigen in snelheidsscripts {#change-custom-object-retrieval-limits-in-velocity-scripting}

Als u het Script van de Snelheid gebruikt om de gegevens van de Objecten van de Douane in e-mail te tonen, zou deze eigenschap voor u kunnen zijn. Standaard hebt u vanuit het snelheidsscript toegang tot 10 bovenliggende aangepaste objecten. Lees het bestand als u meer wilt openen.

## Wat is Snelheid {#what-is-velocity}

[Apache Snelheid](https://velocity.apache.org/) is een taal die is gebaseerd op Java en die is ontworpen voor sjablonen en scripts voor HTML-inhoud. Marketo staat toe dat het in de context van e-mails wordt gebruikt door het gebruik van [scripttokens](/help/marketo/product-docs/email-marketing/general/using-tokens/create-an-email-script-token.md). Dit biedt onder andere toegang tot gegevens die zijn opgeslagen in aangepaste objecten.

U kunt naar bovenliggende en onderliggende aangepaste objecten verwijzen die rechtstreeks zijn verbonden met de regelafstand, of naar de contactpersoon, maar niet naar aangepaste objecten op het derde niveau. Voor elk aangepast object zijn de 10 meest recente bijgewerkte records per persoon/contactpersoon beschikbaar bij uitvoering en worden deze geordend van de meest recente update (op 0) tot de oudste update (op 9).

## De limiet wijzigen {#how-to-change-the-limit}

1. Ga naar de **Beheer** sectie.

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-1.png)

1. Klikken **E-mail**.

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-2.png)

1. Voer in de tabel Limieten voor ophalen van aangepast object een nieuwe limiet voor ophalen van bovenliggend object in en klik op **Wijzigingen opslaan**.

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-3.png)

>[!NOTE]
>
>De waarde Limiet voor ophalen van bovenliggend element moet tussen 10 en 100 liggen. De limiet voor het ophalen van het kind wordt automatisch voor u ingesteld. Dit wordt gedaan door 1000 door de Bovenliggende Ophaalgrens te verdelen. Als u bijvoorbeeld de Bovenliggende limiet instelt op 50, wordt de Onderliggende limiet ingesteld op 20 (1000:50 = 20).

Zoet! Nu kunt u tot meer douanevoorwerpen van het manuscript van de Snelheid toegang hebben.
