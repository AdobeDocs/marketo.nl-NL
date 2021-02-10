---
unique-page-id: 1900585
description: Bewerkbare secties toevoegen aan e-mailsjablonen v1.0 - Marketo Docs - Productdocumentatie
title: Bewerkbare secties toevoegen aan e-mailsjablonen v1.0
translation-type: tm+mt
source-git-commit: 0f0217a88929661798015b51a26259a973f9f6ea
workflow-type: tm+mt
source-wordcount: '100'
ht-degree: 0%

---


# Bewerkbare secties toevoegen aan e-mailsjablonen v1.0 {#add-editable-sections-to-email-templates-v1.0}

Als u een sjabloon maakt in de E-mailsjablooneditor v1.0, kunt u elke sectie bewerkbaar maken door er een speciale `<div>` omheen te plaatsen.

>[!NOTE]
>
>**Voorbeeld**
>
>`<pre> <div class="mktEditable" id="UNIQUE_ID">This part is editable</div></pre>`

Regels:

1. De HTML moet altijd geldig zijn.
1. De klasse **mktEditable** moet worden opgenomen.
1. De id moet uniek zijn in die HTML.
1. Geen spaties in de id.

>[!CAUTION]
>
>tEditable-instructies kunnen niet worden genest.

Als u wilt leren hoe u dit in E-mailsjablooneditor v2.0 doet, checkt u [e-mailsjabloonsyntaxis](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-syntax.md) uit.
