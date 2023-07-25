---
description: "Limieten voor het ophalen van aangepaste objecten wijzigen in [!DNL Velocity Scripting] - Marketo Docs - Productdocumentatie"
title: "Limieten voor het ophalen van aangepaste objecten wijzigen in [!DNL Velocity Scripting]"
exl-id: ef45205e-421d-4d1d-8c9d-7d627326a90c
feature: Email Setup
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '215'
ht-degree: 0%

---

# Limieten voor het ophalen van aangepaste objecten wijzigen in [!DNL Velocity Scripting] {#change-custom-object-retrieval-limits-in-velocity-scripting}

Als u [!DNL Velocity Script] Als u gegevens over aangepaste objecten in e-mails wilt weergeven, is deze functie mogelijk voor u bedoeld. Standaard hebt u vanuit het snelheidsscript toegang tot 10 bovenliggende aangepaste objecten. Lees het bestand als u meer wilt openen.

## Wat is [!DNL Velocity] {#what-is-velocity}

[[!DNL Apache Velocity]](https://velocity.apache.org/) is een taal die is gebaseerd op [!DNL Java] ontworpen voor sjablonen en scripts voor HTML-inhoud. Marketo staat toe dat het in de context van e-mails wordt gebruikt door het gebruik van [scripttokens](/help/marketo/product-docs/email-marketing/general/using-tokens/create-an-email-script-token.md). Dit biedt onder andere toegang tot gegevens die zijn opgeslagen in aangepaste objecten.

U kunt naar bovenliggende en onderliggende aangepaste objecten verwijzen die rechtstreeks zijn verbonden met de regelafstand, of naar de contactpersoon, maar niet naar aangepaste objecten op het derde niveau. Voor elk aangepast object zijn de 10 meest recente bijgewerkte records per persoon/contactpersoon beschikbaar bij uitvoering en worden deze geordend van de meest recente update (op 0) tot de oudste update (op 9).

## De limiet wijzigen {#how-to-change-the-limit}

1. Ga naar de **[!UICONTROL Admin]** sectie.

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-1.png)

1. Klik op **[!UICONTROL Email]**.

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-2.png)

1. In de [!UICONTROL Custom Object Retrieval Limits] tabel, voer een nieuwe [!UICONTROL Parent Retrieval Limit] en klik op **[!UICONTROL Save Changes]**.

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-3.png)

>[!NOTE]
>
>De [!UICONTROL Parent Retrieval Limit] waarde moet tussen 10 en 100 liggen. De [!UICONTROL Child Retrieval Limit] wordt automatisch voor u ingesteld. Dit wordt gedaan door 1000 door te delen [!UICONTROL Parent Retrieval Limit]. Als u bijvoorbeeld de Bovenliggende limiet instelt op 50, wordt de Onderliggende limiet ingesteld op 20 (1000:50 = 20).

Mooi! U kunt nu meer aangepaste objecten openen vanuit [!DNL Velocity script].
