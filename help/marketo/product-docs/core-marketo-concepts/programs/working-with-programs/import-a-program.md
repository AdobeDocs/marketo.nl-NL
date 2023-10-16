---
unique-page-id: 1147108
description: Een programma importeren - Marketo Docs - Productdocumentatie
title: Een programma importeren
exl-id: 15e23e38-a24b-45b3-89a9-ffec85649f4a
feature: Programs
source-git-commit: e49860ae611f2f77789bb491aeccbee46a911a2c
workflow-type: tm+mt
source-wordcount: '505'
ht-degree: 0%

---

# Een programma importeren {#import-a-program}

Een programma kan worden geïmporteerd van het ene Marketo-abonnement naar het andere. U kunt bijvoorbeeld een programma maken in een sandbox en dit vervolgens importeren in uw live abonnement. Bovendien kunt u een vooraf gebouwd programma importeren vanuit de [Marketo Program Library](/help/marketo/product-docs/core-marketo-concepts/programs/program-library/program-import-library-overview.md){target="_blank"}.

## Een programma importeren {#importing-a-program}

1. Ga naar **[!UICONTROL Marketing Activities]**.

   ![](assets/import-a-program-1.png)

1. Klik op de knop **[!UICONTROL New]** vervolgkeuzelijst en selecteer **[!UICONTROL Import Program]**.

   ![](assets/import-a-program-2.png)

   >[!NOTE]
   >
   >De Invoer van het programma is slechts beschikbaar voor gebruikers die rollen hebben met toegelaten de toestemming van het Programma van de Invoer. Meer informatie over [gebruikersrollen en machtigingen beheren](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md){target="_blank"}.
   >
   >Als u een sandboxaccount wilt koppelen aan uw live abonnement, neemt u contact op met [Marketo-ondersteuning](https://nation.marketo.com/t5/Support/ct-p/Support){target="_blank"}.

1. Een Marketo selecteren **[!UICONTROL Subscription]** en een invoerprogramma. Klik op **[!UICONTROL Next]**.

   ![](assets/import-a-program-3.png)

1. Geef een **[!UICONTROL Campaign Folder]** voor het geïmporteerde programma. Klik op **[!UICONTROL Next]**.

   ![](assets/import-a-program-4.png)

   >[!NOTE]
   >
   >Controleer of **[!UICONTROL Use default conflict]** Er zijn regels geselecteerd. Conflictregels zijn nodig wanneer u programma&#39;s importeert in een instantie met elementen met dezelfde naam.

1. Kies de gewenste conflictdetails en klik op **[!UICONTROL Next]**.

   ![](assets/import-a-program-5.png)

   >[!NOTE]
   >
   >Het invoeren van een programma dat de Stappen van de Stroom van de Douane, of de Slimme regels van de Lijst gebruikt die van de Dienst van de Stap van de Stroom in een bestemmingsinstantie worden afgeleid waar er meer dan één compatibele dienstverlener is, zal de het invoeren gebruiker worden ertoe aangezet om stappen of regels aan de correcte dienstverlener in de bestemmingsinstantie toe te wijzen.

1. Details voorvertonen en **[!UICONTROL Import]** het programma.

   ![](assets/import-a-program-6.png)

U ontvangt een e-mailbevestiging zodra het importeren is voltooid.

>[!NOTE]
>
>U moet geïmporteerde batchcampagnes opnieuw plannen en triggercampagnes activeren. Het systeem deactiveert automatisch campagnematerialen en activeert campagnes in het geïmporteerde programma.

## Gevolgen voor externe activa tijdens de invoer van het programma {#impact-on-external-assets-during-program-imports}

De programma&#39;s gebruiken externe activa zoals e-mailmalplaatjes, de malplaatjes van de Landing van de Pagina, beelden, vormen, tekenen, en programmamarkeringen. U kunt configureren hoe de sjablonen en programmatags voor de bestemmingspagina worden verwerkt en Marketo beheert de rest automatisch.

**Sjablonen voor e-mail- en landingspagina:** De sjablonen voor e-mail- en landingspagina worden geïmporteerd in de Design Studio. U kunt collisieregels gebruiken om gedrag te vormen wanneer een malplaatje met de zelfde naam bestaat. Met de standaardregel wordt een getal toegevoegd aan een sjabloon als er een bestaat met dezelfde naam. Als u bijvoorbeeld al een sjabloon hebt met de naam &quot;Standaardsjabloon&quot;, krijgt de nieuwe sjabloon de naam &quot;Standaardsjabloon - 1&quot;.

**Openingspagina&#39;s/Forms:** Als een formulier of bestemmingspagina met dezelfde naam bestaat in Design Studio, worden deze nog steeds geïmporteerd, maar met een nummer dat aan de naam wordt toegevoegd (bijvoorbeeld: bestemmingspagina - 1).

**Afbeeldingen:** Afbeeldingen die door Landing Pages worden gebruikt, worden in de ontwerpstudio geïmporteerd tenzij er een met dezelfde naam bestaat.

**Tokens:** Tokens die buiten een programma leven, worden tijdens het importeren omgezet in lokale tokens.

>[!CAUTION]
>
>Afbeeldingstype mijn tokens worden niet ondersteund voor het importeren van programma&#39;s. Als een programma met afbeeldingstype mijn tokens wordt geïmporteerd, _nee_ tokens zullen doorkomen .

**Programmatags:** U kunt collisieregels gebruiken om te controleren hoe de programmamarkeringen die niet in de bestemmingsrekening bestaan zullen worden behandeld. Als u de standaardregel gebruikt, worden de programmacodes gemaakt of kunt u de codes negeren.

>[!CAUTION]
>
>Bij het importeren van een programma worden e-mails/bestemmingspagina&#39;s met [dynamische inhoud](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/understanding-dynamic-content.md){target="_blank"} wordt overgeslagen.
