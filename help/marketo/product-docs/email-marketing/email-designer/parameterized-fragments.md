---
solution: Marketo Engage
product: marketo
title: Geparametereerde fragmenten
description: Leer hoe u fragmenten kunt aanpassen door sommige van de velden bewerkbaar te maken.
feature: Email Editor
role: User
level: Beginner, Intermediate
hide: true
hidefromtoc: true
source-git-commit: 76d854176c3c462596596689b43d3567517fee63
workflow-type: tm+mt
source-wordcount: '637'
ht-degree: 0%

---

# Geparametereerde fragmenten {#parameterized-fragments}

Wanneer fragmenten in een e-mailsjabloon of e-mailsjabloon worden gebruikt, zijn ze standaard vergrendeld vanwege overerving. Dit betekent dat alle wijzigingen die in een fragment worden aangebracht, automatisch worden doorgegeven aan alle elementen waar het fragment wordt gebruikt. Met aanpasbare fragmenten kunnen specifieke velden in een fragment als bewerkbaar worden gedefinieerd wanneer het fragment aan een e-mail- of e-mailsjabloon wordt toegevoegd. Stel dat u een fragment hebt met een banner, tekst of knop. U kunt bepaalde velden, zoals de URL van het afbeeldingsdoel of knopdoel, instellen als bewerkbaar. Hierdoor kunnen gebruikers deze elementen wijzigen wanneer ze het fragment opnemen in hun e-mailsjabloon, zodat ze een op maat gemaakte ervaring hebben zonder dat dit van invloed is op het oorspronkelijke fragment.

Door geparametereerde fragmenten te gebruiken, kunt u uw inhoud efficiënt beheren en personaliseren zonder volledig nieuwe inhoudsblokken te creëren of de overerving van het originele fragment te verstoren. Dit zorgt ervoor dat de wijzigingen die op fragmentniveau zijn aangebracht, nog steeds worden doorgegeven, terwijl de vereiste aanpassing op sjabloonniveau voor e-mail/e-mail mogelijk is.

Fragmenten met zowel visuele als expressies kunnen worden gemarkeerd als aanpasbaar. Raadpleeg de onderstaande secties voor gedetailleerde instructies over hoe u met elk type fragment kunt doorgaan.

SCREENSHOT - GIF?

—HIER GESTOPT BEWERKEN—

## Bewerkbare velden toevoegen aan visuele fragmenten {#visual}

Voer de volgende stappen uit om gedeelten van een visueel fragment bewerkbaar te maken:

>[!NOTE]
>
>Bewerkbare gebieden kunnen aan **beeld** worden toegevoegd, **tekst** en **knoop** componenten. Voor **HTML** componenten, worden de editable gebieden toegevoegd gebruikend de verpersoonlijkingsredacteur, gelijkend op uitdrukkingsfragmenten. [ Leer hoe te om editable gebied in de componenten van HTML en uitdrukkingsfragmenten toe te voegen ](#expression)

1. Open het scherm voor de editie van de fragmentinhoud.

1. Selecteer de component in het fragment waar u bewerkbare velden wilt configureren.

1. Het deelvenster Eigenschappen van component wordt aan de rechterkant geopend. Selecteer de **Bewerkbare gebieden** lusje dan knevel **toelaten uitgave** optie.

1. Alle velden die voor de geselecteerde component kunnen worden bewerkt, worden in het deelvenster weergegeven. Welke velden beschikbaar zijn voor bewerking, is afhankelijk van het geselecteerde componenttype.

   In het onderstaande voorbeeld kunnen we de URL van de knop &quot;Klik hier&quot; bewerken.

   ![](assets/fragment-param-enable.png){width="800" zoomable="yes"}

1. Klik het **Overzicht** om alle editable gebieden en hun standaardwaarden te controleren.

   In dit voorbeeld wordt het veld URL van de knop weergegeven met de standaardwaarde die in de component is gedefinieerd. Deze waarde kan door gebruikers worden aangepast nadat ze het fragment aan hun inhoud hebben toegevoegd.

   ![](assets/fragment-param-preview.png){width="800" zoomable="yes"}

1. Sla de wijzigingen op als u klaar bent om het fragment bij te werken.

1. Nadat u het fragment in een e-mail hebt toegevoegd, kunnen gebruikers alle bewerkbare velden aanpassen die in het fragment zijn geconfigureerd.

## Bewerkbare velden toevoegen in HTML-componenten en expressiefragmenten {#expression}

Als u delen van een HTML-component of een expressiefragment bewerkbaar wilt maken, moet u een specifieke syntaxis gebruiken in de expressie-editor. Dit impliceert het verklaren van a **variabele** met een standaardwaarde die de gebruikers na het toevoegen van het fragment aan hun inhoud kunnen met voeten treden.

Stel dat u een fragment wilt maken om het toe te voegen aan uw e-mails en gebruikers de mogelijkheid wilt geven een specifieke kleur aan te passen die op verschillende locaties wordt gebruikt, zoals de achtergrondkleuren van frames of knoppen. Wanneer het creëren van uw fragment, moet u een variabele met a **unieke identiteitskaart**, bijvoorbeeld &quot;kleur&quot;verklaren, en het roepen bij de gewenste plaatsen in de fragmentinhoud roepen waar u deze kleur wilt toepassen. Wanneer gebruikers het fragment aan hun inhoud toevoegen, kunnen ze de kleur aanpassen die wordt gebruikt op de plaats waar naar de variabele wordt verwezen.

Voor HTML-componenten kunnen alleen specifieke elementen bewerkbare velden worden. Vouw de onderstaande sectie uit voor meer informatie.

+++Bewerkbare elementen in HTML-componenten:

De onderstaande elementen kunnen bewerkbare velden in een HTML-component worden:

* Een deel van tekst
* Een volledige URL voor koppeling of afbeelding (werkt niet met een gedeelte van een URL)
* Volledige CSS-eigenschap (werkt niet met een gedeeltelijke eigenschap)

In de onderstaande code kan bijvoorbeeld elk rood gemarkeerd element een eigenschap worden:

![](assets/fragment-html.png){width="500" zoomable="yes"}

+++
