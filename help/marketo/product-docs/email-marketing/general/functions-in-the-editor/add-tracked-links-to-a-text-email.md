---
unique-page-id: 1900589
description: Bijgehouden koppelingen toevoegen aan een tekste-mail - Marketo Docs - Productdocumentatie
title: Bijgehouden koppelingen toevoegen aan een tekste-mail
exl-id: 10b4e029-de23-4054-83f7-b68fea68c838
feature: Email Editor
source-git-commit: b3bc6a7ec14a513e4b294852d066f9e3d0f74ef8
workflow-type: tm+mt
source-wordcount: '157'
ht-degree: 0%

---

# Bijgehouden koppelingen toevoegen aan een tekste-mail {#add-tracked-links-to-a-text-email}

>[!PREREQUISITES]
>
>* [ creeer slechts een Tekst E-mail ](/help/marketo/product-docs/email-marketing/general/creating-an-email/create-a-text-only-email.md)
>* [ geeft Elementen in E-mail ](/help/marketo/product-docs/email-marketing/general/email-editor-2/edit-elements-in-an-email.md) uit

E-mailkoppelingen naar tekst kunnen worden bijgehouden in Marketo. Laten we eens kijken hoe het werkt.

1. Selecteer uw e-mail en klik **uitgeven Ontwerp**.

![](assets/one-9.png)

1. Dubbelklik op het bewerkbare gebied waaraan u de koppeling wilt toevoegen.

   ![](assets/two-8.png)

1. Voer de URL met dubbele haakjes in, zoals in: `[[www.domain.com/path/page.html]]` .

   ![](assets/three-8.png)

   >[!CAUTION]
   >
   >Als een e-mail meer dan 365 dagen geleden **werd verzonden en** niemand op om het even welk van zijn verbindingen in de afgelopen 180 dagen heeft geklikt, drukt Marketo Engage de route aan URL van ons gegevensbestand, dat de verbinding zal veroorzaken om te breken. Als u de koppeling permanent wilt maken, kunt u deze niet bijhouden.

1. Sluit de editor af en vergeet niet het concept goed te keuren.

   ![](assets/four-6.png)

>[!NOTE]
>
>De functionaliteit van de klasse marketNoTok werkt niet met traceerbare koppelingen in tekste-mails. Alleen voor HTML-e-mails.
