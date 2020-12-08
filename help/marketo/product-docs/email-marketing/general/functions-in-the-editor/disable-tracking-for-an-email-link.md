---
unique-page-id: 1900579
description: Bijhouden uitschakelen voor een e-mailkoppeling - Marketo Docs - Productdocumentatie
title: Bijhouden uitschakelen voor een e-mailkoppeling
translation-type: tm+mt
source-git-commit: c8a77dc84c023e05fbb442f575269aac108ffb29
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 0%

---


# Bijhouden uitschakelen voor een e-mailkoppeling {#disable-tracking-for-an-email-link}

Soms wilt u de URL **voor het bijhouden van** markeertekens niet inschakelen voor een koppeling in een e-mailbericht. Dit is nuttig wanneer de bestemmingspagina geen parameters URL steunt en in een gebroken verbinding kan resulteren.

>[!NOTE]
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](/help/marketo/getting-started/updates-to-marketo-terminology.md)informatie.

1. Selecteer uw e-mail en klik op **Concept** bewerken ****.

   ![](assets/one-7.png)

1. Dubbelklik op de bewerkbare sectie die de koppeling bevat.

   ![](assets/two-6.png)

1. Klik op de betreffende koppeling en klik vervolgens op de knop Koppeling **** invoegen/bewerken.

   ![](assets/three-6.png)

1. Schakel in het pop-upvenster Koppeling bewerken het selectievakje **Koppeling** bijhouden uit.

   ![](assets/four-4.png)

1. U zult merken dat het vak **** Inclusief mkt_token verdwijnt. Klik op **Toepassen**.

   ![](assets/five-3.png)

   >[!TIP]
   >
   >Als u alleen **Include mkt_tok** uitschakelt, kan de koppeling nog wel worden bijgehouden, maar na omleiding bevat de doel-URL niet de parameter van de queryreeks mkt_tok. Deze parameter wordt gebruikt door Marketo Landing Pages en Munchkin om ervoor te zorgen dat de activiteiten van personen correct worden gevolgd (zoals wanneer een persoon zich afmeldt van een e-mail). Gebruik deze functie niet als u geen afwijkend gedrag op uw website ziet omdat de parameter aanwezig is.

1. Klik op **Opslaan**.

   ![](assets/image2014-9-17-22-3a25-3a20.png)

   >[!TIP]
   >
   >Wilt u kliktracking voor een koppeling in een e- **mailsjabloon**uitschakelen? Gebruik deze indeling:
   >`<a class="mktNoTrack" href="http://www.mywebsite.com">This link does not have tracking</a>`\
   >Neem contact op met uw webontwikkelaar als u hulp nodig hebt bij het implementeren van dit programma.

Mooi! U hebt het bijhouden van wijzigingen voor een koppeling nu uitgeschakeld.
