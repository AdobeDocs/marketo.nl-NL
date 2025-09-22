---
unique-page-id: 1900585
description: Bewerkbare secties toevoegen aan e-mailsjablonen v1.0 - Marketo Docs - Productdocumentatie
title: Bewerkbare secties toevoegen aan e-mailsjablonen v1.0
exl-id: f397aa8e-0d0b-4007-91e1-9b9158bd6432
feature: Email Editor
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
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
1. De klasse van **mktEditable** moet worden omvat.
1. De id moet uniek zijn in die HTML.
1. Geen spaties in de id.

>[!CAUTION]
>
>tEditable-instructies kunnen niet worden genest.

Als u wilt leren hoe te om dit in E-mailRedacteur van het Malplaatje v2.0 te doen, controle uit {de syntaxis van het 0} e-mailmalplaatje [.](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-syntax.md)
