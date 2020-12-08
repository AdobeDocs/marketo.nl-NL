---
unique-page-id: 2949870
description: Een gebeurtenis maken met ReadyTalk - Marketo Docs - Productdocumentatie
title: Een gebeurtenis maken met ReadyTalk
translation-type: tm+mt
source-git-commit: c8a77dc84c023e05fbb442f575269aac108ffb29
workflow-type: tm+mt
source-wordcount: '444'
ht-degree: 0%

---


# Een gebeurtenis maken met ReadyTalk {#create-an-event-with-readytalk}

>[!PREREQUISITES]
>
>* [ReadyTalk toevoegen als een LaunchPoint-service](/help/marketo/product-docs/administration/additional-integrations/add-readytalk-as-a-launchpoint-service.md)
>* [Een nieuw gebeurtenisprogramma maken](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)
>* Stel de juiste [stroomhandelingen in om de betrokkenheid](http://docs.marketo.com/display/DOCS/Flow+Actions)bij te houden


Stel eerst uw gebeurtenis in het ReadyTalk-conferentiecentrum in. Als u hulp nodig hebt, controleer het Centrum van het Middel [ReadyTalk.](https://www.readytalk.com/resources/readytalk)  Wanneer u het registratietype kiest, selecteert u **preregistreren vóór de vergadering**. Als u *register selecteert op het moment van de vergadering*, legt Marketo **geen** geregistreerde status voor uw volk vast en wordt de status Bijgewoond alleen doorgegeven *nadat* het webinar is gesloten.

Laat **me via e-mail** op de hoogte stellen van nieuwe registraties uitgeschakeld.

![](assets/image2015-5-28-21-3a18-3a39.png)

Als u ReadyTalk gebruikt om bevestigingse-mails te verzenden, moet u ook een beschrijving toevoegen. Sla uw gebeurtenis op in ReadyTalk wanneer u klaar bent.

>[!NOTE]
>
>Als u een door de operator ondersteunde gebeurtenis wilt plannen, klikt u op de koppeling **Request Event Services** aan de linkerkant van het startscherm van het conferentiecentrum om een gebeurtenis met ons Events-team te plannen.

Nu kunt u uw gebeurtenis koppelen aan Marketo.

1. Selecteer de gebeurtenis, klik vervolgens op **Gebeurtenishandelingen** en **Gebeurtenisinstellingen.**

   ![](assets/image2015-5-18-12-3a46-3a47.png)

   >[!NOTE]
   >
   >Het kanaaltype van de geselecteerde gebeurtenis moet **webinar zijn.**

1. Onder de Partner van de **Gebeurtenis,** uitgezochte **ReadyTalk**.

   ![](assets/image2015-5-18-12-3a47-3a59.png)

1. Selecteer bij **Aanmelden** de ReadyTalk-aanmelding.

   ![](assets/image2015-5-18-12-3a48-3a48.png)

1. Selecteer onder **Gebeurtenis** de gebeurtenis die u wilt koppelen en klik op **Opslaan**.

   ![](assets/image2015-5-18-12-3a51-3a35.png)

   Mooi! Uw gebeurtenis is nu gesynchroniseerd.

   >[!NOTE]
   >
   >De velden die Marketo verzendt, zijn: Voornaam, Achternaam, E-mailadres.

   >[!TIP]
   >
   >Gebruik de volgende token in uw e-mail om het bevestigingsbericht te vullen met deze unieke URL: `{{member.webinar url}}`. Wanneer de bevestiging-URL wordt verzonden, wordt deze token automatisch omgezet in de unieke bevestiging-URL van de persoon.
   >
   >Stel het bevestigingsbericht in op Operationeel om ervoor te zorgen dat personen die zich registreren en die mogelijk niet zijn geabonneerd, hun bevestigingsgegevens ontvangen.

   ![](assets/readytalk.png)

   >[!CAUTION]
   >
   >Vermijd het gebruik van geneste e-mailprogramma&#39;s voor het verzenden van bevestigingsberichten. Gebruik in plaats hiervan de slimme campagne van het gebeurtenisprogramma, zoals hierboven wordt getoond.

   >[!TIP]
   >
   >Het kan tot 48 uur duren voordat de gegevens in Marketo verschijnen. Als na het wachten dat lang u nog niets ziet, uitgezocht **verfrist zich van Leverancier** van de Gebeurtenis van het menu van de Acties van de Gebeurtenis in het **Samenvatting** lusje van uw gebeurtenis.

## Het overzicht weergeven  {#viewing-the-schedule}

Klik in de [programmaweergave](http://docs.marketo.com/display/docs/program+schedule+view)van het programma op de kalendervermelding voor de gebeurtenis. U kunt het schema aan de rechterkant van het scherm zien!

![](assets/image2015-5-18-12-9-58.png)

Personen die zich aanmelden voor uw webinar, worden via de stap Program Status wijzigen naar uw webinar geduwd wanneer de Nieuwe status is ingesteld op &quot;Geregistreerd&quot;. Geen andere status zal de persoon over duwen. Zorg er ook voor dat u in stap 1 van de statusstroom van het programma Wijzigen en stap 2 in de E-mailflow verzendt.
