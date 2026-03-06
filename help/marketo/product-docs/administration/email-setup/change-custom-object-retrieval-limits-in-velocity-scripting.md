---
description: Verhoog of verminder de grens van de de objecten van de ouder douaneobjecten voor  [!DNL Velocity]  manuscript in e-mail (10 tot 100).
title: Ophaallimieten voor aangepaste objecten wijzigen in  [!DNL Velocity Scripting]
exl-id: ef45205e-421d-4d1d-8c9d-7d627326a90c
feature: Email Setup
source-git-commit: e894ece3a643113fd3e1d8df9f8addefea5553f5
workflow-type: tm+mt
source-wordcount: '232'
ht-degree: 0%

---

# Ophaallimieten voor aangepaste objecten wijzigen in [!DNL Velocity Scripting] {#change-custom-object-retrieval-limits-in-velocity-scripting}

Als u [!DNL Velocity Script] gebruikt om aangepaste objectgegevens in e-mails weer te geven, is deze functie mogelijk voor u. Standaard hebt u vanuit het snelheidsscript toegang tot 10 bovenliggende aangepaste objecten. Lees het bestand als u meer toegang nodig hebt.

## Wat is [!DNL Velocity] {#what-is-velocity}

[[!DNL Apache Velocity] &#x200B;](https://velocity.apache.org/) is een taal die op [!DNL Java] wordt voortgebouwd voor het malplaatjes en het scripting van de inhoud van HTML. Marketo staat het toe om in de context van E-mail door het gebruik van [&#x200B; scripting tokens &#x200B;](/help/marketo/product-docs/email-marketing/general/using-tokens/create-an-email-script-token.md) worden gebruikt. Dit biedt onder andere toegang tot gegevens die zijn opgeslagen in aangepaste objecten.

U kunt naar bovenliggende en onderliggende aangepaste objecten verwijzen die rechtstreeks zijn verbonden met de regelafstand, of naar de contactpersoon, maar niet naar aangepaste objecten op het derde niveau. Voor elk aangepast object zijn de 10 meest recente bijgewerkte records per persoon/contactpersoon beschikbaar bij uitvoering en worden deze geordend van de meest recente update (op 0) tot de oudste update (op 9).

## De limiet wijzigen {#how-to-change-the-limit}

1. Ga naar de sectie **[!UICONTROL Admin]** .

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-1.png)

1. Klik op **[!UICONTROL Email]**.

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-2.png)

1. Voer in de tabel [!UICONTROL Custom Object Retrieval Limits] een nieuwe [!UICONTROL Parent Retrieval Limit] in en klik op **[!UICONTROL Save Changes]** .

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-3.png)

>[!NOTE]
>
>De waarde [!UICONTROL Parent Retrieval Limit] moet een waarde tussen 10 en 100 hebben. De eigenschap [!UICONTROL Child Retrieval Limit] wordt automatisch voor u ingesteld. Dit wordt gedaan door 1000 door [!UICONTROL Parent Retrieval Limit] te verdelen. Als u bijvoorbeeld de Bovenliggende limiet instelt op 50, wordt de Onderliggende limiet 20 (1000:50 = 20).

Mooi! U kunt nu meer aangepaste objecten openen vanuit [!DNL Velocity script] .
