---
unique-page-id: 2359644
description: Aangepast HTML-formulier tonen voor bekende personen - Marketo Docs - Productdocumentatie
title: Aangepast HTML-formulier tonen voor bekende personen
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '298'
ht-degree: 0%

---


# Aangepast HTML-formulier tonen voor bekende personen {#show-custom-html-form-for-known-people}

Als een bezoeker is gekookt (bekende persoon die in het verleden een e-mailadres heeft opgegeven), waarom zou u dan moeite doen met het formulier? Geef ze gewoon de downloadknop. Zo gaat het.

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

1. Ga naar **Marketing** **Activiteiten**.

   ![](assets/login-marketing-activities-5.png)

1. Selecteer onder **Marketing** **Activiteiten** het formulier en klik op **Formulier** bewerken ****.

   ![](assets/image2014-9-15-12-3a24-3a6.png)

1. Klik onder **Formulier** - **instellingen** op **Instellingen**.

   ![](assets/image2014-9-15-12-3a24-3a36.png)

1. Instellen indien **bekende** **bezoeker, tonen**: naar **Aangepaste** **HTML**.

   ![](assets/image2014-9-15-12-3a24-3a59.png)

1. Klik op ![—](assets/image2014-9-25-14-3a1-3a26.png) om de **aangepaste** **HTML** te bewerken die aan bekende personen wordt weergegeven.

   ![](assets/image2014-9-15-12-3a25-3a38.png)

1. Er is wat standaardinhoud, maar u kunt deze aanpassen.

   ![](assets/image2014-9-15-12-3a25-3a49.png)

   Beschikbare tokens:

   | Token | Beschrijving |
   |---|---|
   | `{{lead.FirstName}}` | Hierdoor wordt de voornaam van de persoon weergegeven. |
   | `{{lead.LastName}}` | Hierdoor wordt de achternaam van de persoon weergegeven. |
   | `{{form.Button:default=Download}}` | Hiermee wordt de formulierknop weergegeven. Vervang het gebied na de knop `=` om de knoptekst te wijzigen. |
   | `{{form.NotYou:default=Not you?}}` | Dit zal een verbinding tonen voor het geval dat de persoon iemand anders is. Vervang het gebied na de koppeling `=` om de koppelingstekst te wijzigen. |

   >[!CAUTION]
   >
   >Alleen de vier bovenstaande tokens kunnen worden gebruikt. Een ander token werkt hier niet.

1. Klik op **Voltooien**.

   ![](assets/image2014-9-15-12-3a27-3a25.png)

1. Klik op **Goedkeuren en Sluiten**.

   >[!NOTE]
   >
   >Het formulier moet zijn goedgekeurd voor gebruik op de aanlandingspagina&#39;s.

   ![](assets/image2014-9-15-12-3a27-3a53.png)

   >[!NOTE]
   >
   >**Herinnering**
   >
   >
   >Vergeet niet het concept [van de bestemmingspagina dat door de formulierwijzigingen is gemaakt,](../../../../product-docs/demand-generation/landing-pages/understanding-landing-pages/approve-unapprove-or-delete-a-landing-page.md) goed te keuren.

   ![](assets/image2014-9-15-12-3a28-3a12.png)

   >[!TIP]
   >
   >U kunt de klik van de knop naar het element sturen door de pagina voor formulierfollow-up in te stellen op de URL van het bestand.

Stukje cake! Kijk wat een persoon zou zien als hij of zij terugkwam naar de zelfde vorm: