---
description: Aangepaste objectophaallimieten wijzigen in snelheidsscripts - Marketo Docs - Productdocumentatie
title: Limieten voor het ophalen van aangepaste objecten wijzigen in snelheidsscripts
translation-type: tm+mt
source-git-commit: cfefff241b34571b9778cbd827f45d1b468d121e
workflow-type: tm+mt
source-wordcount: '248'
ht-degree: 0%

---


# Aangepaste objectophaallimieten wijzigen in snelheidsscript {#change-custom-object-retrieval-limits-in-velocity-scripting}

Als u het Script van de Snelheid gebruikt om de gegevens van de Objecten van de Douane in e-mail te tonen, zou deze eigenschap voor u kunnen zijn. Standaard hebt u vanuit het snelheidsscript toegang tot 10 bovenliggende aangepaste objecten. Lees het bestand als u meer wilt openen.

## Wat is snelheid {#what-is-velocity}

[Apache Velocity](https://velocity.apache.org/) is een taal die is gebaseerd op Java en die is ontworpen voor sjablonen en scripts voor HTML-inhoud. Marketo maakt het mogelijk om te worden gebruikt in de context van e-mails via het gebruik van [scripting tokens](/help/marketo/product-docs/email-marketing/general/using-tokens/create-an-email-script-token.md). Dit biedt onder andere toegang tot gegevens die zijn opgeslagen in aangepaste objecten.

U kunt naar bovenliggende en onderliggende aangepaste objecten verwijzen die rechtstreeks zijn verbonden met de regelafstand, of naar de contactpersoon, maar niet naar aangepaste objecten op het derde niveau. Voor elk aangepast object zijn de 10 meest recente bijgewerkte records per persoon/contactpersoon beschikbaar bij uitvoering en worden deze geordend van de meest recente update (op 0) tot de oudste update (op 9).

## Hoe te om de Grens {#how-to-change-the-limit} te veranderen

1. Ga naar **Admin** sectie.

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-1.png)

1. Klik **E-mail**.

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-2.png)

1. Voer in de tabel Aangepaste objectophaallimieten een nieuwe bovenliggende ophaallimiet in en klik op **Wijzigingen opslaan**.

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-3.png)

>[!NOTE]
>
>De waarde Limiet voor ophalen van bovenliggend element moet tussen 10 en 100 liggen. De limiet voor het ophalen van het kind wordt automatisch voor u ingesteld. Dit wordt gedaan door 1000 door de Bovenliggende Ophaalgrens te verdelen. Als u bijvoorbeeld de Bovenliggende limiet instelt op 50, wordt de Onderliggende limiet ingesteld op 20 (1000:50 = 20).

Zoet! Nu kunt u tot meer douanevoorwerpen van het manuscript van de Snelheid toegang hebben.
