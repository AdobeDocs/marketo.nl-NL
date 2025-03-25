---
unique-page-id: 1900579
description: Bijhouden uitschakelen voor een e-mailkoppeling - Marketo Docs - Productdocumentatie
title: Bijhouden uitschakelen voor een e-mailkoppeling
exl-id: 841ef605-1664-4457-bc83-50bbe5d44853
feature: Email Editor
source-git-commit: b3bc6a7ec14a513e4b294852d066f9e3d0f74ef8
workflow-type: tm+mt
source-wordcount: '266'
ht-degree: 0%

---

# Bijhouden uitschakelen voor een e-mailkoppeling {#disable-tracking-for-an-email-link}

Soms wilt u niet **het Volgen URL van Marketo** op een verbinding in e-mail toelaten. Dit is handig wanneer de doelpagina geen URL-parameters ondersteunt en een verbroken koppeling tot gevolg kan hebben.

Ook, als een e-mail meer dan 365 dagen geleden **werd verzonden en** niemand op om het even welk van zijn verbindingen in de afgelopen 180 dagen heeft geklikt, drukt Marketo Engage de route aan URL van ons gegevensbestand, dat de verbinding zal veroorzaken om te breken. Dus als u de koppeling permanent wilt maken, moet u het bijhouden van koppelingen uitschakelen.

1. Selecteer uw e-mail en klik **uitgeven Ontwerp**.

   ![](assets/one-7.png)

1. Dubbelklik op de bewerkbare sectie die de koppeling bevat.

   ![](assets/two-6.png)

1. Klik de verbinding in kwestie, dan klik het **Tussenvoegsel/geef de knoop van de Verbinding** uit.

   ![](assets/three-6.png)

1. In Edit Verbinding pop-up, uncheck het **checkbox van de Verbinding van het Spoor**.

   ![](assets/four-4.png)

1. U zult **omvatten mkt_tok doos** verdwijnen. Klik **toepassen**.

   ![](assets/five-3.png)

   >[!TIP]
   >
   >Unchecking enkel **omvat mkt_tok** nog zal de verbinding toestaan om worden gevolgd, maar na omleiding, zal bestemmingsURL niet de parameter van het mkt_tok vraagkoord omvatten. Deze parameter wordt gebruikt door Marketo Landing Pages en Munchkin om ervoor te zorgen dat de activiteiten van personen correct worden gevolgd (zoals wanneer een persoon zich afmeldt van een e-mail). Gebruik deze functie niet als u geen afwijkend gedrag op uw website ziet omdat de parameter aanwezig is.

1. Klik **sparen**.

   ![](assets/image2014-9-17-22-3a25-3a20.png)

   >[!TIP]
   >
   >Wilt u klik-volgen voor een verbinding in een e-mail **malplaatje** onbruikbaar maken? Gebruik deze indeling:
   >`<a class="mktNoTrack" href="https://www.mywebsite.com">This link does not have tracking</a>`\
   >Neem contact op met uw webontwikkelaar als u hulp nodig hebt bij het implementeren van dit programma.

Mooi! U hebt het bijhouden van wijzigingen voor een koppeling nu uitgeschakeld.
