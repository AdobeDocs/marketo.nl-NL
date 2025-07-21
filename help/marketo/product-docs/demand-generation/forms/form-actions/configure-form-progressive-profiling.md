---
unique-page-id: 2359646
description: Progressieve profilering van formulieren configureren - Marketo Docs - Productdocumentatie
title: Progressieve profilering van formulieren configureren
exl-id: 72afe3dc-0688-45ec-ab70-4dc9accf4fc8
feature: Forms
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '307'
ht-degree: 0%

---

# Progressieve profilering van formulieren configureren {#configure-form-progressive-profiling}

Korte formulieren zijn goed! Wanneer iemand terugkeert naar een formulier, kunt u nieuwe velden presenteren en het profiel van de bezoeker geleidelijk invullen. Zo gaat het.

>[!NOTE]
>
>Voor deze eigenschap om behoorlijk te werken, zorg ervoor de Vorm pre-Vulling voor zichtbare gebieden wordt toegelaten, en [ gehandicapt ](/help/marketo/product-docs/demand-generation/forms/form-fields/disable-pre-fill-for-a-form-field.md) voor verborgen gebieden.

1. Ga naar **[!UICONTROL Marketing Activities]** .

   ![](assets/ma-1.png)

1. Selecteer het formulier en klik op **[!UICONTROL Edit Form]** .

   ![](assets/image2014-9-15-12-3a31-3a20.png)

1. Klik onder **[!UICONTROL Form Settings]** op **[!UICONTROL Settings]** .

   ![](assets/image2014-9-15-12-3a31-3a29.png)

1. Stel **[!UICONTROL Progressive Profiling]** in op **[!UICONTROL Enabled]** .

   ![](assets/image2014-9-15-12-3a31-3a47.png)

1. Oké, nu configureren we het. Ga naar **[!UICONTROL Field Details]** .

   ![](assets/image2014-9-15-12-3a31-3a55.png)

1. Sleep alle velden die deel uitmaken van de progressieve profielset.

   ![](assets/image2014-9-15-12-3a32-3a3.png)

1. Wanneer u alle velden verplaatst, moet het er ongeveer als volgt uitzien:

   ![](assets/image2014-9-15-12-3a32-3a12.png)

   >[!NOTE]
   >
   >De velden buiten het vak **[!UICONTROL Progressive Profiling]** worden altijd in het formulier weergegeven, zelfs als ze zijn ingevuld.

1. Selecteer het vak **[!UICONTROL Progressive Profiling]** .

   ![](assets/image2014-9-15-12-3a32-3a19.png)

   >[!CAUTION]
   >
   >Wees voorzichtig wanneer u vereiste velden gebruikt in [!UICONTROL Progressive Profiling] . Deze velden kunnen nog steeds leeg blijven als de bezoeker een nieuw e-mailadres invoert (waarmee een nieuwe persoon wordt gemaakt) nadat hij eerder gegevens voor de andere velden heeft verzonden, zoals deze op het laatste formulier worden onderdrukt.

1. Kies nu hoeveel lege gebieden u mensen van het **Progressieve Profilerende** vakje op een bepaald ogenblik wilt zien.

   ![](assets/image2014-9-15-12-3a32-3a26.png)

   >[!NOTE]
   >
   >Als u **[!UICONTROL Number of Blank Fields]** als 1 kiest, ziet de bezoeker de volgende keer dat deze het formulier ziet:
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

1. Klik op **[!UICONTROL Finish]**.

   ![](assets/image2014-9-15-12-3a33-3a35.png)

1. Klik op **[!UICONTROL Approve and Close]**.

   ![](assets/image2014-9-15-12-3a33-3a45.png)

Mooi werk! Het werk dat u zojuist hebt gedaan, zal vruchten afwerpen.

Experimenteer met deze functie en test het. Het is geavanceerd, maar je kunt je formulieren op deze manier heel dynamisch maken.
