---
unique-page-id: 17727995
description: E-mail CC - Marketo-documenten - Productdocumentatie
title: E-mail CC
exl-id: 00550e98-916d-4e66-91f8-7394c242a29b
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '547'
ht-degree: 0%

---

# E-mail CC {#email-cc}

Met e-mail CC kunnen via Marketo opgegeven e-mails worden verzonden met CC-ontvangers.

Deze functie is beschikbaar voor alle e-mailmiddelen van Marketo, ongeacht hoe de e-mail is verzonden (batch- of triggercampagne). De ontvanger van de CC ontvangt een exacte kopie van de e-mail die naar de gekozen Marketo-persoon is verzonden. Als zodanig, om het even welke betrokkenheidsactiviteit (opent, klikt, enz.) wordt geregistreerd naar het activiteitenlogboek van de Marketo-persoon in de regel Aan van de e-mail. De leveringsactiviteit (verzonden, geleverd, hard bounce, enz.) _andere dan &quot;zachte stuit&quot;_ zal **niet** registreren, aangezien Marketo geen leveringsgebeurtenissen voor de Marketo Person van de ontvangers van CC kan onderscheiden.&quot; Marketo maakt slechts maximaal 100.000 mensen tegelijk CC. Als uw slimme lijst meer dan 100 kB is en het noodzakelijk is iedereen op het wordt CCd, adviseren wij omhoog het breken van uw lijst.

>[!NOTE]
>
>E-mail CC is niet ontworpen voor gebruik met A/B-tests. U kunt het hoe dan ook gebruiken als u wilt, maar aangezien het technisch niet wordt gesteund, zou de Steun van Marketo niet bij het oplossen van problemen kunnen helpen.

## E-mail CC instellen {#set-up-email-cc}

1. Klik in Mijn Marketo op **Beheer**.

   ![](assets/one.png)

1. Selecteer in de boomstructuur de optie **E-mail**.

   ![](assets/two.png)

1. Klikken **E-mailCC-instellingen bewerken**.

   ![](assets/three.png)

1. Selecteer maximaal 25 Marketo Lead- of Company-velden (van het type &quot;E-mail&quot;) om beschikbaar te maken voor gebruik als CC-adressen in e-mails. Klikken **Opslaan** wanneer gereed.

   ![](assets/four.png)

## E-mail CC gebruiken {#using-email-cc}

1. Selecteer uw e-mail en klik op **Concept bewerken**.

   ![](assets/five.png)

1. Klikken **E-mailinstellingen**.

   ![](assets/six.png)

1. Selecteer maximaal vijf velden die u wilt gebruiken voor CC-personen. In dit voorbeeld willen we alleen Lead Owner CC&#39;d. Klikken **Opslaan** wanneer gereed.

   ![](assets/seven.png)

   Zo eenvoudig is het! In het bovenstaande voorbeeld is de eigenaar van de lead van de ontvangers die u hebt gekozen CC&#39;d.

   >[!NOTE]
   >
   >Als een ongeldig e-mailadres in een CC-veld staat, wordt het overgeslagen.

   Voor een snelle identificatie toont de weergave E-mailoverzicht u of en welke velden voor e-mail-CC zijn geselecteerd.

   ![](assets/eight.png)

   Als het e-mailbericht is goedgekeurd maar de Marketo Admin een of meer CC-velden uitschakelt voordat het e-mailbericht wordt verzonden, **deze personen ontvangen geen e-mail**. In dat geval worden in de weergave E-mailoverzicht alle velden weergegeven die na goedkeuring zijn uitgeschakeld maar vooraf zijn verzonden:

   ![](assets/removal.png)

   >[!NOTE]
   >
   >De bovenstaande fout wordt ook weergegeven in het gedeelte E-mailinstellingen van het e-mailconcept.

## Na de verzending {#after-the-send}

* Als een ontvanger van CC op een bijgehouden koppeling in de e-mail klikt, wordt de muisklik (net als alle andere betrokkenheidsactiviteiten) gekoppeld aan de hoofdontvanger van de e-mail. Bovendien kunnen ze door klikken naar een pagina met Marketo&#39;s webtrackingcode (munchkin.js), waardoor ze als de hoofdontvanger worden gekopieerd.

>[!TIP]
>
>U kunt kiezen uit [sommige of alle koppelingen voor het bijhouden van koppelingen uitschakelen](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/disable-tracking-for-an-email-link.md) in een e-mail.

* Nadat een e-mailcampagne is uitgevoerd, bevat Verzenden e-mailactiviteit een lijst met alle CC-adressen die zijn opgenomen voor elke ontvanger van de mailing. Als om het even welke adressen van CC wegens afmelden werden overgeslagen, zal het ook in de activiteit worden genoteerd.
* Koppelingen en pagina&#39;s waarop u zich niet meer abonneert, functioneren normaal in e-mailberichten van CC. Op deze manier kunnen CC-ontvangers hun abonnement desgewenst opzeggen (conform de anti-spamregels) en wordt een record van deze actie opgeslagen in de Marketo-database.
* Personen die als niet-geabonneerd in uw Marketo-database worden vermeld, worden **niet** e-mails ontvangen via CC.
