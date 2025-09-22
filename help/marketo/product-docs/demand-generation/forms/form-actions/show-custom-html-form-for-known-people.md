---
unique-page-id: 2359644
description: Aangepast HTML-formulier voor bekende personen tonen - Marketo Docs - Productdocumentatie
title: Aangepast HTML-formulier tonen voor bekende personen
exl-id: 668216ea-7c2b-4204-81a5-56547c3baf1d
feature: Forms
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '234'
ht-degree: 1%

---

# Aangepast HTML-formulier tonen voor bekende personen {#show-custom-html-form-for-known-people}

Als een bezoeker in het verleden zijn volledige naam en e-mailadres heeft opgegeven en u niet wilt dat deze het hele formulier ophalen, leert u hoe u ze een aangepaste HTML kunt tonen (bijvoorbeeld alleen een downloadknop).

1. Ga naar **[!UICONTROL Marketing Activities]** .

   ![](assets/login-marketing-activities-5.png)

1. Selecteer het formulier onder **[!UICONTROL Marketing Activities]** en klik op **[!UICONTROL Edit Form]** .

   ![](assets/image2014-9-15-12-3a24-3a6.png)

1. Klik onder **[!UICONTROL Form Settings]** op **[!UICONTROL Settings]** .

   ![](assets/image2014-9-15-12-3a24-3a36.png)

1. Stel if **[!UICONTROL Known Visitor, Show]** in op **[!UICONTROL Custom HTML]** .

   ![](assets/image2014-9-15-12-3a24-3a59.png)

1. Klik ![ - ](assets/image2014-9-25-14-3a1-3a26.png) om **[!UICONTROL Custom HTML]** uit te geven dat aan bekende mensen zal worden getoond.

   ![](assets/image2014-9-15-12-3a25-3a38.png)

1. Er is wat standaardinhoud, maar u kunt deze aanpassen.

   ![](assets/image2014-9-15-12-3a25-3a49.png)

   Beschikbare tokens:

   | Token | Beschrijving |
   |---|---|
   | `{{lead.FirstName}}` | Hierdoor wordt de voornaam van de persoon weergegeven. |
   | `{{lead.LastName}}` | Hierdoor wordt de achternaam van de persoon weergegeven. |
   | `{{form.Button:default=Download}}` | Hiermee wordt de formulierknop weergegeven. Vervang het gebied na `=` om de knoptekst te wijzigen. |
   | `{{form.NotYou:default=Not you?}}` | Dit zal een verbinding tonen voor het geval de persoon anders is. Vervang het gebied na de `=` om de koppelingstekst te wijzigen. |

   >[!CAUTION]
   >
   >Alleen de vier bovenstaande tokens kunnen worden gebruikt. Een ander token werkt hier niet.

1. Klik op **[!UICONTROL Finish]**.

   ![](assets/image2014-9-15-12-3a27-3a25.png)

1. Klik op **[!UICONTROL Approve and Close]**.

   >[!NOTE]
   >
   >Het formulier moet zijn goedgekeurd voor gebruik op de aanvoerpagina&#39;s.

   ![](assets/image2014-9-15-12-3a27-3a53.png)

   >[!NOTE]
   >
   >Herinner me [ goedkeuren het het landen paginaconcept ](/help/marketo/product-docs/demand-generation/landing-pages/understanding-landing-pages/approve-unapprove-or-delete-a-landing-page.md) door de vormveranderingen wordt gecreeerd.

   Stukje cake! Kijk wat een persoon zou zien als hij of zij terugkwam naar de zelfde vorm:

   ![](assets/image2014-9-15-12-3a28-3a12.png)

   >[!TIP]
   >
   >U kunt de klik van de knop naar het element sturen door de pagina voor formulierfollow-up in te stellen op de URL van het bestand.
