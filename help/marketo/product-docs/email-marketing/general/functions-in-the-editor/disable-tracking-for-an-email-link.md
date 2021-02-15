---
unique-page-id: 1900579
description: Bijhouden uitschakelen voor een e-mailkoppeling - Marketo Docs - Productdocumentatie
title: Bijhouden uitschakelen voor een e-mailkoppeling
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '213'
ht-degree: 0%

---


# Tracering uitschakelen voor een e-mailkoppeling {#disable-tracking-for-an-email-link}

Soms wilt u **Marketo Tracking URL** op een koppeling in een e-mail niet inschakelen. Dit is handig wanneer de doelpagina geen URL-parameters ondersteunt en een verbroken koppeling tot gevolg kan hebben.

1. Selecteer uw e-mail en klik **Concept** uitgeven.

   ![](assets/one-7.png)

1. Dubbelklik op de bewerkbare sectie die de koppeling bevat.

   ![](assets/two-6.png)

1. Klik op de betreffende koppeling en klik vervolgens op de knop **Koppeling invoegen/bewerken**.

   ![](assets/three-6.png)

1. Schakel in het pop-upvenster Koppeling bewerken het selectievakje **Koppeling bijhouden** uit.

   ![](assets/four-4.png)

1. De **Include mkt_tok box** verdwijnt. Klik **Toepassen**.

   ![](assets/five-3.png)

   >[!TIP]
   >
   >Als u alleen **Inclusief mkt_tok** uitschakelt, kan de koppeling nog wel worden bijgehouden, maar na omleiding bevat de doel-URL niet de parameter van de queryreeks mkt_tok. Deze parameter wordt gebruikt door Marketo Landing Pages en Munchkin om ervoor te zorgen dat de activiteiten van personen correct worden gevolgd (zoals wanneer een persoon zich afmeldt van een e-mail). Gebruik deze functie niet als u geen afwijkend gedrag op uw website ziet omdat de parameter aanwezig is.

1. Klik **Opslaan**.

   ![](assets/image2014-9-17-22-3a25-3a20.png)

   >[!TIP]
   >
   >Wilt u kliktracking voor een koppeling in een e-mail **template** uitschakelen? Gebruik deze indeling:
   >`<a class="mktNoTrack" href="https://www.mywebsite.com">This link does not have tracking</a>`\
   >Neem contact op met uw webontwikkelaar als u hulp nodig hebt bij het implementeren van dit programma.

Mooi! U hebt het bijhouden van wijzigingen voor een koppeling nu uitgeschakeld.
