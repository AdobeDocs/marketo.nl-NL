---
title: priority-override-for-trigger-campagnes
description: Prioriteit overschrijven voor triggercampagnes
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '301'
ht-degree: 0%

---


# Prioriteit overschrijven voor triggercampagnes

<br> 

Beheerders kunnen de vastgestelde prioriteit van Marketo voor triggercampagnes negeren om prioriteiten in te stellen die beter aansluiten op bedrijfsdoelstellingen.

>[!NOTE]
>
>Deze functie is alleen beschikbaar voor triggercampagnes en voor gebruikers aan wie de machtiging &quot;Prioriteit triggercampagne bewerken&quot; is verleend.

>[!CAUTION]
>
>Het wordt sterk geadviseerd dat u deze eigenschap op een beperkte reeks zaken kritieke campagnes (25 is het geadviseerde maximum) gebruikt. Het losjes gebruiken van de eigenschap op een grote reeks kan algemene campagneuitvoering negatief beïnvloeden.

## Prioriteit overschrijven

1. Klik in de triggercampagne op het **[!UICONTROL Schedule]** tabblad en klik vervolgens op **[!UICONTROL Override Priority]**.

   ![Afbeelding één](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-1.png)

1. Kies een nieuw prioriteitsniveau in het keuzemenu. Klik **[!UICONTROL Confirm]**.

   ![Afbeelding twee](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-2.png)

   ![Afbeelding drie](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-3.png)

>[!NOTE]
>
>* U kunt de standaardprioriteit van uw campagne in het [!UICONTROL Campaign Queue] hieronder bekijken [!UICONTROL Marketing Activities]. Om het uitvoeringspercentage te verhogen, raden we u aan uw campagneprioriteit op één niveau hoger in te stellen dan het standaardniveau.
>* De door de gebruiker ingestelde prioriteit geldt alleen voor nieuwe personen die in aanmerking komen voor de campagne. Dit heeft geen invloed op personen die al in de wachtrij staan.


## Prioriteit opnieuw instellen

1. Als u de prioriteit van de campagne weer wilt instellen op de standaardinstelling van het systeem, gaat u naar de **[!UICONTROL Schedule]** tab in de triggercampagne en klikt u **[!UICONTROL Reset Priority]**.

   ![Afbeelding vier](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-4.png)

1. Klik **[!UICONTROL Reset]** om te bevestigen.

   ![Afbeelding vijf](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-5.png)

>[!NOTE]
>
>Prioritaire overschrijvingen en voorinstellingen worden vastgelegd in Audittrail. U kunt het [audittrail](https://docs.marketo.com/x/GZ2t) door het [!UICONTROL Admin] gebied in de Klassieke ervaring bekijken.

## Toegang bij voorrang overschrijven van subsidie

>[!CAUTION]
>
>Alleen beheerders of gebruikers met beheerdersverantwoordelijkheden hebben voorrang op de toegang tot de campagne.

1. Klik in het [!UICONTROL Admin] gebied op **[!UICONTROL Users & Roles]**.

   ![Afbeelding zes](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-6.png)

1. Klik op het **[!UICONTROL Roles]** tabblad, selecteer de gebruiker aan wie u toegang wilt verlenen en klik vervolgens op **[!UICONTROL Edit Role]**.

   ![Afbeelding zeven](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-7.png)

1. Onder [!UICONTROL Access Marketing Activities], controleer **[!UICONTROL Edit Trigger Campaign Priority]**. Klik **[!UICONTROL Save]**.

   ![Afbeelding acht](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-8.png)

## Campagneprioriteit weergeven in Marketo Classic

U kunt de prioriteit van de campagne in de [!DNL Classic] ervaring bekijken door het **[!UICONTROL Schedule]** lusje binnen een trekkercampagne te klikken.

![Afbeelding negen](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-9.png)

>[!NOTE]
>
>De prioriteit in de [!DNL Classic] ervaring is alleen gezichtspunt. Het veranderen of het terugstellen van campagneprioriteit is slechts beschikbaar door Marketo Sky.
