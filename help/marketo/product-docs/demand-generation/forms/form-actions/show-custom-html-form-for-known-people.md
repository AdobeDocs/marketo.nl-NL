---
unique-page-id: 2359644
description: Aangepast HTML-formulier tonen voor bekende personen - Marketo Docs - Productdocumentatie
title: Aangepast HTML-formulier tonen voor bekende personen
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '246'
ht-degree: 0%

---


# Aangepast HTML-formulier tonen voor bekende personen {#show-custom-html-form-for-known-people}

Als een bezoeker is gekookt (bekende persoon die in het verleden een e-mailadres heeft opgegeven), waarom zou u dan moeite doen met het formulier? Geef ze gewoon de downloadknop. Zo gaat het.

1. Ga naar **Marketingactiviteiten**.

   ![](assets/login-marketing-activities-5.png)

1. Selecteer onder **Marketingactiviteiten** uw formulier en klik op **Formulier bewerken**.

   ![](assets/image2014-9-15-12-3a24-3a6.png)

1. Klik onder **Formulierinstellingen** op **Instellingen**.

   ![](assets/image2014-9-15-12-3a24-3a36.png)

1. Stel Indien **bekende bezoeker, Tonen** in: naar **Aangepaste HTML**.

   ![](assets/image2014-9-15-12-3a24-3a59.png)

1. Klik ![—](assets/image2014-9-25-14-3a1-3a26.png) om **Aangepaste HTML** uit te geven die aan bekende mensen zal worden getoond.

   ![](assets/image2014-9-15-12-3a25-3a38.png)

1. Er is wat standaardinhoud, maar u kunt deze aanpassen.

   ![](assets/image2014-9-15-12-3a25-3a49.png)

   Beschikbare tokens:

   | Token | Beschrijving |
   |---|---|
   | `{{lead.FirstName}}` | Hierdoor wordt de voornaam van de persoon weergegeven. |
   | `{{lead.LastName}}` | Hierdoor wordt de achternaam van de persoon weergegeven. |
   | `{{form.Button:default=Download}}` | Hiermee wordt de formulierknop weergegeven. Vervang het gebied na `=` om de knooptekst te veranderen. |
   | `{{form.NotYou:default=Not you?}}` | Dit zal een verbinding tonen voor het geval dat de persoon iemand anders is. Vervang het gebied na `=` om de verbindingstekst te veranderen. |

   >[!CAUTION]
   >
   >Alleen de vier bovenstaande tokens kunnen worden gebruikt. Een ander token werkt hier niet.

1. Klik **Voltooien**.

   ![](assets/image2014-9-15-12-3a27-3a25.png)

1. Klik **Goedkeuren en Sluiten**.

   >[!NOTE]
   >
   >Het formulier moet zijn goedgekeurd voor gebruik op de aanlandingspagina&#39;s.

   ![](assets/image2014-9-15-12-3a27-3a53.png)

   >[!NOTE]
   >
   >Vergeet niet om [het concept van de bestemmingspagina](/help/marketo/product-docs/demand-generation/landing-pages/understanding-landing-pages/approve-unapprove-or-delete-a-landing-page.md) goed te keuren dat door de formulierwijzigingen is gemaakt.

   Stukje cake! Kijk wat een persoon zou zien als hij of zij terugkwam naar de zelfde vorm:

   ![](assets/image2014-9-15-12-3a28-3a12.png)

   >[!TIP]
   >
   >U kunt de klik van de knop naar het element sturen door de pagina voor formulierfollow-up in te stellen op de URL van het bestand.
