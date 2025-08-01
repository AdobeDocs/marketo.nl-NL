---
unique-page-id: 1900579
description: Bijhouden uitschakelen voor een e-mailkoppeling - Marketo Docs - Productdocumentatie
title: Bijhouden uitschakelen voor een e-mailkoppeling
exl-id: 841ef605-1664-4457-bc83-50bbe5d44853
feature: Email Editor
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '280'
ht-degree: 0%

---

# Bijhouden uitschakelen voor een e-mailkoppeling {#disable-tracking-for-an-email-link}

Soms wilt u niet **het Volgen URL van Marketo** op een verbinding in e-mail toelaten. Dit is handig wanneer de doelpagina geen URL-parameters ondersteunt en een verbroken koppeling tot gevolg kan hebben.

Ook, als een e-mail meer dan 365 dagen geleden **werd verzonden en** niemand op om het even welk van zijn verbindingen in de afgelopen 180 dagen heeft geklikt, drukt Marketo Engage de route aan URL van ons gegevensbestand, dat de verbinding zal veroorzaken om te breken. Dus als u de koppeling permanent wilt maken, moet u het bijhouden van koppelingen uitschakelen.

1. Selecteer uw e-mail en klik op **[!UICONTROL Edit Draft]** .

   ![](assets/one-7.png)

1. Dubbelklik op de bewerkbare sectie die de koppeling bevat.

   ![](assets/two-6.png)

1. Klik de verbinding in kwestie, dan klik het **Tussenvoegsel/geef de knoop van de Verbinding** uit.

   ![](assets/three-6.png)

1. Schakel in het pop-upvenster Koppeling bewerken het selectievakje **[!UICONTROL Track Link]** uit.

   ![](assets/four-4.png)

1. U zult merken dat **[!UICONTROL Include mkt_tok]doos** verdwijnt. Klik op **[!UICONTROL Apply]**.

   ![](assets/five-3.png)

   >[!TIP]
   >
   >Unchecking enkel **omvat mkt_tok** nog zal de verbinding toestaan om worden gevolgd, maar na omleiding, zal bestemmingsURL niet de parameter van het mkt_tok vraagkoord omvatten. Deze parameter wordt gebruikt door Marketo Landing Pages en Munchkin om ervoor te zorgen dat de activiteiten van personen correct worden gevolgd (zoals wanneer een persoon zich afmeldt van een e-mail). Gebruik deze functie niet als u geen afwijkend gedrag op uw website ziet omdat de parameter aanwezig is.

1. Klik op **[!UICONTROL Save]**.

   ![](assets/image2014-9-17-22-3a25-3a20.png)

   >[!CAUTION]
   >
   >Als u klik-het volgen voor een verbinding in een E-mailMalplaatje, of de [ tekstversie ](/help/marketo/product-docs/email-marketing/general/creating-an-email/edit-the-text-version-of-an-email.md){target="_blank"} van een e-mail wilt onbruikbaar maken, voeg `mktNoTrack` bij het *begin* van het koord, niet het eind, zoals in dit voorbeeld toe: `<a class="mktNoTrack" href="https://www.mywebsite.com">This link does not have tracking</a>`. Anders kan de koppeling verdwijnen. Neem contact op met uw webontwikkelaar als u hulp nodig hebt bij het implementeren van de bovenstaande code.
