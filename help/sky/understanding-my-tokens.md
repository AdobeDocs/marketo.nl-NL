---
title: understanding-my-tokens
description: Mijn tokens begrijpen
exl-id: d56748e2-d742-45dd-96a8-dd80e30d9d8b
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '327'
ht-degree: 0%

---

# Mijn tokens begrijpen

<br> 

Mijn tokens zijn aangepaste variabelen die u kunt maken en gebruiken in uw programma&#39;s of campagnemappen. Ze zien er zo uit: `{{_my.Name of Token_}}`

## Voorbeelden

* `{{my.Event Date}}`
* `{{my.Webinar Speaker}}`

Als u Mijn tokens wilt openen, selecteert u uw programma- of campagnemap en gaat u naar het tabblad [!UICONTROL My Tokens]. Sleep een token naar het canvas [!UICONTROL Local Tokens].

![Afbeelding één](/help/sky/assets/my-tokens/understanding-my-tokens/understanding-my-tokens-1.png)

>[!CAUTION]
>
>Namen van Mijn tokens kunnen niet worden gewijzigd nadat ze zijn opgeslagen. Kies daarom zorgvuldig.

>[!NOTE]
>
>Mijn Tokens zullen niet oplossen wanneer het verzenden van een e-mail van het Inzicht van de Verkoop op of de Dynamiek van Microsoft of Salesforce; alleen standaardtokens worden gevuld (Lead, Company, enz.). Standaardwaarden voor tokens werken echter wel.

>[!NOTE]
>
>Koppelingstokens werken niet in e-mails met alleen tekst.

## Nesten van tokens

Wanneer u een nieuw token maakt, kan hiernaar worden verwezen door andere objecten in de structuur. U kunt algemene variabelen op lagere niveaus in de boomstructuur overschrijven. Er is een naamgevingsstructuur voor de plaats waar het token is gemaakt voor eenvoudig beheer.

* **Lokaal token:** het token is rechtstreeks in dat programma of die map gemaakt.
* **[Overschreven token:](/help/sky/override-an-inherited-my-token.md)** het token is overgeërfd, maar er is een uitzondering gemaakt in dit programma of deze map.
* **Overgenomen token:** het token is ergens in een programma of map op een hoger niveau in de structuur gemaakt.

Deze drie typen vindt u op het tabblad **[!UICONTROL My Tokens]** in uw programma- of campagnemap.

![Afbeelding twee](/help/sky/assets/my-tokens/understanding-my-tokens/understanding-my-tokens-2.png)

Het verplaatsen van programma&#39;s en mappen heeft ook invloed op tokens. Controleer altijd of verwijzingen niet worden verbroken tijdens het verplaatsen.

>[!NOTE]
>
>Als de e-mail die vanuit een betrokkenheidsprogramma wordt verzonden een onderliggende e-mail van een standaardprogramma is (dus niet lokaal naar uw betrokkenheidsprogramma), worden alle My Tokens die in de e-mail worden gebruikt, opgelost vanuit het standaardprogramma waarin de onderliggende e-mail zich bevindt.

## Gebruik van token

Selecteer een token en klik vervolgens op het gebruikspictogram in de rechterbovenhoek om een lijst met elementen weer te geven die dat token bevatten.

![Afbeelding drie](/help/sky/assets/my-tokens/understanding-my-tokens/understanding-my-tokens-3.png)

![Afbeelding vier](/help/sky/assets/my-tokens/understanding-my-tokens/understanding-my-tokens-4.png)

**Diep duiken**

Meer informatie over de My Tokens:

* [CRM-campagne](/help/sky/my-token-crm-campaign.md)
* [Datum](/help/sky/my-token-date.md)
* [Kalenderbestand](/help/sky/my-token-calendar-file.md)
* [Afbeelding](/help/sky/my-token-image.md)
* [Koppeling](/help/sky/my-token-link.md)
* [Getal](/help/sky/my-token-number.md)
* [RTF](/help/sky/my-token-rich-text.md)
* [Score](/help/sky/my-token-score.md)
* [E-mailscript](/help/sky/my-token-email-script.md)
* [Tekst](/help/sky/my-token-text.md)
