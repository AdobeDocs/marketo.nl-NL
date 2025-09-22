---
description: Veldvragen - Marketo Docs - Productdocumentatie
title: Veldvragen
exl-id: c138b627-f853-4d35-b022-cc517d6b86d4
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '160'
ht-degree: 0%

---

# Veldvragen {#field-prompts}

Met veldaanwijzingen kunt u een tekstreeks toevoegen aan e-mailberichten die moeten worden verwijderd of vervangen voordat de e-mail kan worden verzonden. Dit is een goede manier om gebruikers eraan te herinneren extra verpersoonlijking toe te voegen.

Typ de gewenste tekst om een veldprompt toe te voegen. Plaats een uitroepteken in de afbeelding en omring deze met accolades (zie hieronder).

**Voorbeelden:**

`{{! Introduce yourself}}`

`{{! Insert name of Account Executive}}`

`{{! Add sentence that references their industry and role}}`

<p>Gebruikers moeten deze tekst vervangen door hun eigen personalisatie voordat de e-mail kan worden verzonden.

![](assets/field-prompts-1.png)

>[!NOTE]
>
>Wanneer het gebruiken van herinneringen met de Campagnes van de Verkoop, is het best om hen met hande-mailstappen te gebruiken. Met deze stappen wijst u een gebruiker een herinneringstaak toe om de e-mail te verzenden, zodat hij of zij de herinneringen kan vervangen door aangepaste tekst. Automatische e-mailstappen in verkoopcampagnes proberen automatisch te verzenden, zonder dat de gebruiker de herinneringen kan vervangen. Prompts die niet worden vervangen, zullen ertoe leiden dat de e-mails niet worden verzonden.
