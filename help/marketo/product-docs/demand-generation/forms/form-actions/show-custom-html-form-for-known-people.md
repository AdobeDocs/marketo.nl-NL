---
unique-page-id: 2359644
description: Aangepast HTML-formulier tonen voor bekende personen - Marketo Docs - Productdocumentatie
title: Aangepast HTML-formulier tonen voor bekende personen
exl-id: 668216ea-7c2b-4204-81a5-56547c3baf1d
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '246'
ht-degree: 0%

---

# Aangepast HTML-formulier tonen voor bekende personen {#show-custom-html-form-for-known-people}

Als een bezoeker is gekookt (bekende persoon die in het verleden een e-mailadres heeft opgegeven), waarom zou u dan moeite doen met het formulier? Geef ze gewoon de downloadknop. Zo gaat het.

1. Ga naar **Marketingactiviteiten**.

   ![](assets/login-marketing-activities-5.png)

1. Onder **Marketingactiviteiten** selecteert u het formulier en klikt u op **Formulier bewerken**.

   ![](assets/image2014-9-15-12-3a24-3a6.png)

1. Onder **Formulierinstellingen**, klikt u op **Instellingen**.

   ![](assets/image2014-9-15-12-3a24-3a36.png)

1. Instellen indien **Bekende bezoeker, tonen**: tot **Aangepaste HTML**.

   ![](assets/image2014-9-15-12-3a24-3a59.png)

1. Klik op de knop ![—](assets/image2014-9-25-14-3a1-3a26.png) om de **Aangepaste HTML** dat zal aan de bekende mensen worden getoond .

   ![](assets/image2014-9-15-12-3a25-3a38.png)

1. Er is wat standaardinhoud, maar u kunt deze aanpassen.

   ![](assets/image2014-9-15-12-3a25-3a49.png)

   Beschikbare tokens:

   | Token | Beschrijving |
   |---|---|
   | `{{lead.FirstName}}` | Hierdoor wordt de voornaam van de persoon weergegeven. |
   | `{{lead.LastName}}` | Hierdoor wordt de achternaam van de persoon weergegeven. |
   | `{{form.Button:default=Download}}` | Hiermee wordt de formulierknop weergegeven. Het gebied na de `=` om de knoptekst te wijzigen. |
   | `{{form.NotYou:default=Not you?}}` | Dit zal een verbinding tonen voor het geval dat de persoon iemand anders is. Het gebied na de `=` om de koppelingstekst te wijzigen. |

   >[!CAUTION]
   >
   >Alleen de vier bovenstaande tokens kunnen worden gebruikt. Een ander token werkt hier niet.

1. Klikken **Voltooien**.

   ![](assets/image2014-9-15-12-3a27-3a25.png)

1. Klikken **Goedkeuren en Sluiten**.

   >[!NOTE]
   >
   >Het formulier moet zijn goedgekeurd voor gebruik op de aanlandingspagina&#39;s.

   ![](assets/image2014-9-15-12-3a27-3a53.png)

   >[!NOTE]
   >
   >Herinneren aan [goedkeuren, concept van bestemmingspagina](/help/marketo/product-docs/demand-generation/landing-pages/understanding-landing-pages/approve-unapprove-or-delete-a-landing-page.md) worden gemaakt door de formulierwijzigingen.

   Stukje cake! Kijk wat een persoon zou zien als hij of zij terugkwam naar de zelfde vorm:

   ![](assets/image2014-9-15-12-3a28-3a12.png)

   >[!TIP]
   >
   >U kunt de klik van de knop naar het element sturen door de pagina voor formulierfollow-up in te stellen op de URL van het bestand.
