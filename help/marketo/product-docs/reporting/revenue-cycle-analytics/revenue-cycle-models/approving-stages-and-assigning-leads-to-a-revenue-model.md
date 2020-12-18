---
unique-page-id: 4718683
description: Het goedkeuren van Stages en het toewijzen van Leidingen aan een Model van de Inkomsten - Marketo DOS - de Documentatie van het Product
title: Het goedkeuren van Stages en het toewijzen van Leidingen aan een model van de Inkomsten
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '307'
ht-degree: 0%

---


# Bezig met goedkeuren van Fases en toewijzen van leads aan een inkomstenmodel {#approving-stages-and-assigning-leads-to-a-revenue-model}

U kunt uw **Inkomsten** **Model** in gebruik nemen door bestaande leads toe te voegen, waardoor toewijzingsregels voor nieuwe leads worden gemaakt.

## Fases {#approving-stages} goedkeuren

Wij keuren de stadia van uw model goed alvorens u om het even welke lood toevoegt.

1. Ga naar het gebied **Analytics **a1/> ****

   ![](assets/image2015-4-28-17-3a8-3a8.png)

1. Selecteer het model waarvan de stadia u wilt goedkeuren.

   ![](assets/image2015-4-28-17-3a10-3a3.png)

1. Selecteer **Goedkeuren** **Fases** onder **Modelhandelingen**.

   ![](assets/image2015-4-28-17-3a12-3a37.png)

1. U zult met een alarm worden begroet; Klik **Leads toewijzen**.

   ![](assets/image2015-4-28-17-3a5-3a39.png)

Uitstekend! Laten we verder gaan en die leads toewijzen.

## Bestaande leads {#assigning-existing-leads} toewijzen

[Creeer een Slimme ](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) Lijst om de lood voor één stadium van uw model in uw gegevensbestand van de Lood te identificeren.

1. Zodra u [uw Slimme Lijst](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) hebt gecreeerd, klik **Leads** tabel.

   ![](assets/image2015-4-29-11-3a37-3a30.png)

1. Klik **Selecteer allen** om de lood te selecteren.

   ![](assets/image2015-4-29-11-3a39-3a39.png)

1. Open de vervolgkeuzelijst **Lead Actions** en selecteer **Special**. Klik **Opbrengstwerkgebied wijzigen**.

   ![](assets/image2015-4-29-11-3a40-3a38.png)

1. Selecteer het juiste **Model** en het juiste **werkgebied**. Klik **Nu uitvoeren**.

   ![](assets/image2015-4-29-11-3a43-3a41.png)

1. Herhaal deze bewerking totdat alle leads zijn toegewezen aan de verschillende stadia van uw model.

Geweldig! Om te specificeren hoe de nieuwe lood aan stadia worden toegewezen, creeer toewijzingsregels.

>[!NOTE]
>
>Als uw model in de Goedgekeurde staat van Stages is, zult u geen gebeurtenissen van het Stadium van de Opbrengst van de Verandering in de de activiteitenlogboeken van de lood zien. Als uw model volledig is goedgekeurd, wordt deze stap overgeslagen als u een lood in het zelfde stadium beweegt het momenteel in is.

## Nieuwe leads: Toewijzingsregels maken {#new-leads-create-assignment-rules}

1. Klik nogmaals op** Marketo Home** en selecteer **Analytics**.

   ![](assets/image2015-4-28-17-3a8-3a8.png)

1. `Click your model in the tree, then the`**`Model Actions`**`menu, selecting`**`Assignment Rules`** `.`

   ![](assets/image2015-4-29-11-3a52-3a17.png)

1. `If your assignment rules contain more than just one default choice click **Stage, **make your selection, then click`**`Add Choice`**`.`

   ![](assets/image2015-4-29-12-3a5-3a46.png)

## Voorbeeld van toewijzingsregel {#example-assignment-rule}

Creeer een regel van de Score van de Lood om de nieuwe lood met een minimumscore aan een aangewezen stap toe te wijzen.

1. Selecteer onder **If** **Loodscore**. Kies vervolgens **ten minste**.
` ![](assets/image2015-4-29-13-3a27-3a8.png)

   `

1. Typ **40** in het veld en selecteer **Verkoopregel** als werkgebied. Klik **Opslaan** om te voltooien.

   ![](assets/image2015-4-29-14-3a4-3a23.png)

>[!MORELIKETHIS]
>
>Om uw model goed te keuren, lees onze hulppagina op ** [Goedkeuring en Unapproval a Model](approve-unapprove-a-revenue-model.md)**.

