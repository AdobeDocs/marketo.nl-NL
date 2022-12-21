---
unique-page-id: 2359646
description: Progressieve profilering van formulieren configureren - Marketo Docs - Productdocumentatie
title: Progressieve profilering van formulieren configureren
exl-id: 72afe3dc-0688-45ec-ab70-4dc9accf4fc8
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '332'
ht-degree: 0%

---

# Progressieve profilering van formulieren configureren {#configure-form-progressive-profiling}

Korte formulieren zijn goed! Wanneer iemand terugkeert naar een formulier, kunt u nieuwe velden presenteren en het profiel van de bezoeker geleidelijk invullen. Zo gaat het.

>[!NOTE]
>
>Voor een correcte werking van deze functie moet de optie Vooraf invullen van formulier zijn ingeschakeld voor zichtbare velden, en [uitgeschakeld](/help/marketo/product-docs/demand-generation/forms/form-fields/disable-pre-fill-for-a-form-field.md) voor verborgen velden.

1. Ga naar **Marketingactiviteiten**.

   ![](assets/ma-1.png)

1. Selecteer het formulier en klik op **Formulier bewerken**.

   ![](assets/image2014-9-15-12-3a31-3a20.png)

1. Onder **Formulierinstellingen**, klikt u op **Instellingen**.

   ![](assets/image2014-9-15-12-3a31-3a29.png)

1. Set **Progressieve profielen** tot **Ingeschakeld**.

   ![](assets/image2014-9-15-12-3a31-3a47.png)

1. Oké, nu configureren we het. Ga naar **Velddetails**.

   ![](assets/image2014-9-15-12-3a31-3a55.png)

1. Sleep alle velden die deel uitmaken van de progressieve profielset.

   ![](assets/image2014-9-15-12-3a32-3a3.png)

1. Wanneer u alle velden verplaatst, moet het er ongeveer als volgt uitzien:

   ![](assets/image2014-9-15-12-3a32-3a12.png)

   >[!NOTE]
   >
   >De velden buiten de **Progressieve profielen** wordt altijd in het formulier weergegeven, zelfs als deze zijn ingevuld.

1. Selecteer **Progressieve profielen** doos.

   ![](assets/image2014-9-15-12-3a32-3a19.png)

   >[!CAUTION]
   >
   >Wees voorzichtig wanneer u vereiste velden gebruikt in Progressieve profielen. Deze velden kunnen nog steeds leeg blijven als de bezoeker een nieuw e-mailadres invoert (waarmee een nieuwe persoon wordt gemaakt) nadat hij eerder gegevens voor de andere velden heeft verzonden, zoals deze op het laatste formulier worden onderdrukt.

1. Kies nu hoeveel lege velden u wilt zien in het menu **Progressieve profielen** op een bepaald tijdstip.

   ![](assets/image2014-9-15-12-3a32-3a26.png)

   >[!NOTE]
   >
   >Als u **Getal** **van** **Leeg** **Velden** als 1 ziet de bezoeker de volgende keer dat hij dit formulier ziet:
   >
   >* Voornaam (leeg)
   >* Achternaam (leeg)
   >* E-mailadres (leeg)
   >* Telefoonnummer (leeg)

   >
   >Ervan uitgaande dat ze elk veld invullen, zien ze de tweede keer dat ze bezoeken:
   >
   >* Voornaam (vooraf ingevuld)
   >* Achternaam (vooraf ingevuld)
   >* E-mailadres (vooraf ingevuld)
   >* Mobiel telefoonnummer (leeg)

   >
   >Ervan uitgaande dat ze het nummer van de mobiele telefoon invullen, zien ze de derde keer dat ze de site bezoeken:
   >
   >* Voornaam (vooraf ingevuld)
   >* Achternaam (vooraf ingevuld)
   >* E-mailadres (vooraf ingevuld)
   >* Land (leeg)


1. Klikken **Voltooien**.

   ![](assets/image2014-9-15-12-3a33-3a35.png)

1. Klikken **Goedkeuren en Sluiten**.

   ![](assets/image2014-9-15-12-3a33-3a45.png)

Mooi werk! Het werk dat u zojuist hebt gedaan, zal vruchten afwerpen.

Experimenteer met deze functie en test het. Het is geavanceerd, maar je kunt je formulieren op deze manier heel dynamisch maken.
