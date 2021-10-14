---
unique-page-id: 11386358
description: Marketo Sandbox - Marketo Docs - Productdocumentatie
title: Marketo-sandbox
exl-id: c040fac6-2290-4de5-b27d-2c7cb28f6e30
source-git-commit: 84a285974de3bbcdf33e24befae323d3d82ef239
workflow-type: tm+mt
source-wordcount: '327'
ht-degree: 0%

---

# Marketo-sandbox {#marketo-sandbox}

Een Marketo-sandbox is een extra instantie die wordt gebruikt voor testdoeleinden voordat deze wordt geïmplementeerd in de productieomgeving.

>[!AVAILABILITY]
>
>Niet alle klanten hebben deze functie aangeschaft. Neem voor meer informatie contact op met de succesmanager van de klant.

Een Marketo-sandbox kan niet worden gesynchroniseerd met uw normale CRM-server als deze al is gesynchroniseerd met uw productieexemplaar. Gebruik de sandbox van uw CRM voor de synchronisatie en voer dezelfde stappen uit als de oorspronkelijke synchronisatie.

## Informatie over sandboxen {#things-to-know-about-sandboxes}

* Zodra uw zandbak van de Manager van het Succes van de Klant uw zandbak opstelling heeft en u de uitnodiging verzendt, moet u een verschillend e-mailadres aan login gebruiken dan uw de productieinstantie van Marketo.
* Als u gebruikers wilt toevoegen, is het proces hetzelfde als het toevoegen van gebruikers in productie](/help/marketo/product-docs/administration/users-and-roles/managing-marketo-users.md#create-users). [ Ze moeten opnieuw een ander e-mailadres gebruiken als ze al een Marketo-aanmelding hebben.
* De Marketo-sandbox is leeg, maar heeft dezelfde functies als de productie-instantie.
* Als u een programma in uw zandbak creeert en het naar productie wilt verplaatsen, kunt u [programmainvoer](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/import-a-program.md) uitvoeren.
* Sandboxen worden vertraagd, zodat productieinstanties niet nadelig worden beïnvloed door testomgevingen. U kunt maximaal 20 e-mails per campagne verzenden.

>[!CAUTION]
>
>Sandboxvernieuwing voor Marketo Dynamics Sync wordt momenteel niet ondersteund. Als u uw zandbak van CRM van de Dynamica moet verfrissen, zal een nieuwe zandbak van Marketo worden vereist. Neem contact op met de succesmanager van de klant voor meer informatie.

## Instantie kopiëren {#instance-copy}

U kunt een ondersteuningsgeval indienen waarin u een eenmalige instantie-kopie aanvraagt om de sandbox te vullen. De instantie-kopie zal _echter niet alles_ overbrengen. Raadpleeg [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support) voor meer informatie.

>[!NOTE]
>
>* Instantiekopie wordt **niet** ondersteund als de broninstantie is geïntegreerd met Microsoft Dynamics.
>* Als u uw inheemse CRM verandert, zou een nieuw geval van Marketo nodig zijn, en een instantieexemplaar aan de nieuwe instantie van Marketo zou niet mogelijk zijn. Werk in plaats daarvan met Marketo Support om de functionaliteit van het importprogramma te verkennen.

