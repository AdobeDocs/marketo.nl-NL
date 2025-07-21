---
unique-page-id: 14746177
description: Abonnement op opzeggen herschrijven - Marketo Docs - Productdocumentatie
title: Abonnement opzeggen
exl-id: 1c451ff7-c56f-477e-b287-898c359aedcf
feature: Marketo Sales Connect
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 0%

---

# Een [!UICONTROL Unsubscribe] opnieuw toewijzen {#resubscribing-an-unsubscribe}

Soms willen mensen ervoor kiezen om e-mails te ontvangen. Dit is hoe je afmeldingsberichten weer mailbaar kunt maken.

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

>[!CAUTION]
>
>Voordat u iemand opnieuw abonneert, moet u kunnen aantonen dat de vergunning voor het opnieuw inschrijven van deze personen is gedocumenteerd en in overeenstemming is met alle toepasselijke wetten.

>[!NOTE]
>
>Als u de synchronisatie van uw abonnement hebt uitgeschakeld, moet u het abonnement opzeggen uit ToutApp verwijderen en de optie Weigeren [!DNL Salesforce] uitschakelen om de persoonrecord niet opnieuw te synchroniseren.

1. Ga naar de [ Webtoepassing ](https://toutapp.com/login) en klik **[!UICONTROL People]**.

1. Selecteer de persoon om de weergave van de persoondetails te openen.

   ![](assets/two.png)

1. Klik op de drie stippen in de weergave met persoonlijke details en selecteer **[!UICONTROL Remove Unsubscribe]** .

   ![](assets/three.png)

1. Selecteer de reden waarom de persoon weer wordt ingeschakeld om e-mails te ontvangen en klik vervolgens op **[!UICONTROL Remove Unsubscribe]** .

   ![](assets/four.png)

>[!NOTE]
>
>Als u de synchronisatie voor afmelden hebt ingeschakeld, moet u ook de optie om te weigeren uitschakelen in de record in Salesforce. Als deze optie niet is ingeschakeld, wordt de abonnement van de persoon in [!DNL Sales Connect] iedere avond opnieuw opgezegd, omdat deze detecteert dat de persoon is uitgeschakeld in [!DNL Salesforce] . Als een van de records de optie Weigeren/afmelden heeft, markeert de synchronisatie de gekoppelde record als zodanig.
