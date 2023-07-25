---
unique-page-id: 1900579
description: Bijhouden uitschakelen voor een e-mailkoppeling - Marketo Docs - Productdocumentatie
title: Bijhouden uitschakelen voor een e-mailkoppeling
exl-id: 841ef605-1664-4457-bc83-50bbe5d44853
feature: Email Editor
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '213'
ht-degree: 0%

---

# Bijhouden uitschakelen voor een e-mailkoppeling {#disable-tracking-for-an-email-link}

Soms wilt u het **URL voor bijhouden van Marketo** op een koppeling in een e-mail. Dit is handig wanneer de doelpagina geen URL-parameters ondersteunt en een verbroken koppeling tot gevolg kan hebben.

1. Selecteer uw e-mail en klik op **Concept bewerken**.

   ![](assets/one-7.png)

1. Dubbelklik op de bewerkbare sectie die de koppeling bevat.

   ![](assets/two-6.png)

1. Klik op de betreffende koppeling en klik vervolgens op de knop **Koppeling invoegen/bewerken** knop.

   ![](assets/three-6.png)

1. Schakel in het pop-upvenster Koppeling bewerken de optie **Koppeling bijhouden** selectievakje.

   ![](assets/four-4.png)

1. U zult de **Inclusief vak Markt_tok** verdwijnt. Klikken **Toepassen**.

   ![](assets/five-3.png)

   >[!TIP]
   >
   >Uitlijnen ongedaan maken **Inclusief mkt_tok** zal nog toestaan dat de verbinding wordt gevolgd, maar na omleiding, zal bestemmingsURL niet de parameter van het mkt_tok vraagkoord omvatten. Deze parameter wordt gebruikt door Marketo Landing Pages en Munchkin om ervoor te zorgen dat de activiteiten van personen correct worden gevolgd (zoals wanneer een persoon zich afmeldt van een e-mail). Gebruik deze functie niet als u geen afwijkend gedrag op uw website ziet omdat de parameter aanwezig is.

1. Klikken **Opslaan**.

   ![](assets/image2014-9-17-22-3a25-3a20.png)

   >[!TIP]
   >
   >Klikcontrole voor een koppeling in een e-mail uitschakelen **template**? Gebruik deze indeling:
   >`<a class="mktNoTrack" href="https://www.mywebsite.com">This link does not have tracking</a>`\
   >Neem contact op met uw webontwikkelaar als u hulp nodig hebt bij het implementeren van dit programma.

Mooi! U hebt het bijhouden van wijzigingen voor een koppeling nu uitgeschakeld.
