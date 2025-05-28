---
solution: Marketo Engage
product: marketo
title: Personalization Tokens
description: Meer informatie over het gebruik van personalisatietokens in de nieuwe Marketo Engage Email Designer
level: Beginner, Intermediate
hide: true
hidefromtoc: true
source-git-commit: 0abb2a7499541b8efbf3000bcd9fc9c1a79e43e1
workflow-type: tm+mt
source-wordcount: '244'
ht-degree: 0%

---

# Personalization Tokens {#personalization-tokens}

De E-mail Designer heeft een andere indeling dan de klassieke e-maileditor voor tokens voor e-mailpersonalisatie. Deze wijziging is geïmplementeerd om de compatibiliteit met Handlebar-scripts te verbeteren en het maken van e-mail te stroomlijnen.

>[!AVAILABILITY]
>
>Vanaf 23 mei 2025 wordt deze functie batches toegewezen aan Marketo Engage-gebruikers, waarbij één regio per week wordt bijgewerkt. Tijdens de rollout worden eventuele e-mailberichten die met de nieuwe e-mailontwerper zijn gemaakt, automatisch naar de nieuwe indeling gemigreerd. Met deze update zijn alle tokens alleen beschikbaar in het Engels.

## Hoofd-/kleine letters {#primary-use-case}

Deze verbetering komt hoofdzakelijk die die die van [ scripting van de Snelheid ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/email-scripting){target="_blank"} aan het scripting van de Handlebar overgaan ten goede. De nieuwe e-mail Designer ondersteunt alleen de nieuwe token-indeling. Met de bijgewerkte indeling worden spaties verwijderd en wordt een herziene standaardtekststructuur geïntroduceerd, die zorgt voor een vloeiender en efficiëntere scriptingervaring.

## Tokenervaring {#token-experience}

Een blik op de symbolische ervaring, zowel oud als nieuw.

### Oude indeling {#old-format}

In de klassieke e-maileditor kunt u tokens toevoegen met spaties, zoals `lead.Anonymous IP` of `member.registration code` . De opmaak voor standaardtekst was: `{{lead.City:default=fallback}}`

![](assets/personalization-tokens-1.png){width="500" zoomable="yes"}

### Nieuwe indeling {#new-format}

In de e-mailontwerper, moet u aan [ camel geval ](https://developer.mozilla.org/en-US/docs/Glossary/Camel_case) aanpassen, of onderstrepingstekens voor tekenen (b.v., `lead.anonymousIP` of `member.registration_code`). De opmaak voor standaardtekst verandert ook in `{%=lead.city ?: "fallback" %}` .

![](assets/personalization-tokens-2.png){width="600" zoomable="yes"}

## Notities {#things-to-note}

* De verpersoonlijkingsredacteur kenmerkt ook de volgende functies voor gemak om te ontwerpen:

   * Ongedaan maken/Opnieuw
   * Zoeken/Zoeken en vervangen
   * Automatisch aanvullen

* **Alle** tokens die eerder in Marketo Engage worden gesteund worden gesteund in de nieuwe verpersoonlijkingsredacteur.
