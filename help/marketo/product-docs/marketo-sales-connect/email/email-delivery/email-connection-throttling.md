---
description: E-mailverbindingsmogelijkheden - Marketo Docs - Productdocumentatie
title: Throtting van e-mailverbinding
exl-id: 093f5459-1bbb-45dd-8590-71ea4e1168d4
feature: Marketo Sales Connect
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '374'
ht-degree: 1%

---

# Throtting van e-mailverbinding {#email-connection-throttling}

Door uw [!DNL Sales Connect] -account te integreren om via [!DNL Exchange] of Gmail-providers te verzenden, biedt u een gestroomlijnde installatie en optimaliseert u de e-mailleverbaarheid voor 1 :1 -verkoopcommunicatie. Om systemen echter gezond te houden en accounts veilig te houden, dwingen Gmail en Exchange beperkingen in het verzenden van e-mail af. Deze limieten kunnen naar eigen goeddunken worden verhoogd of verlaagd.

## Overzicht {#overview}

Met e-mailverbindingsthrottling kunnen [!DNL Sales Connect] -beheerders de verzendsnelheid van e-mailberichten configureren wanneer ze Gmail of [!DNL Exchange] als leveringskanaal gebruiken, zodat de snelheid waarmee e-mails worden doorgegeven aan de leverancier van het leveringskanaal de afgedwongen limieten niet overschrijdt.

Wanneer de limieten consequent worden overschreden, kan dit soms worden beschouwd als verdacht gedrag van de leverancier van het leveringskanaal, waardoor e-mails mislukken en soms zelfs een account wordt uitgeschakeld.

**Nota&#39;s/Hoogtepunten**

* Automatisch ingeschakeld wanneer een gebruiker verbinding maakt met Gmail of [!DNL Exchange]
* Kan worden aangepast als u de instellingen wilt verhogen of verlagen ten opzichte van de aanbevelingen
* Vertraagt alleen e-mailberichten die via Gmail of [!DNL Exchange] worden verzonden, niet voor een aangepast leveringskanaal
* De vertraging bij het verzenden van de e-mailverbinding zorgt ervoor dat elke afzonderlijke gebruiker een e-mail ontvangt omdat elke gebruiker een eigen verbinding heeft met zijn e-mailprovider

**het Vormen van uw Verdraaide Montages van de Verbinding E-mail**

1. Klik op het tandwielpictogram en selecteer **[!UICONTROL Settings]** .

   ![](assets/email-connection-throttling-1.png)

1. Klik op **[!UICONTROL General]**.

   ![](assets/email-connection-throttling-2.png)

1. Voer in de geheugenkaart voor de verbinding via e-mail de gewenste batchgrootte in van de e-mailberichten die naar de leverancier van het e-mailkanaal worden verzonden.

   ![](assets/email-connection-throttling-3.png)

1. Stel de hoeveelheid tijd in die moet worden gewacht voordat elke batch wordt verzonden. In dit voorbeeld kiezen we 25 e-mails om de 45 seconden.

   ![](assets/email-connection-throttling-4.png)

1. Klik op **[!UICONTROL Save]**.

   ![](assets/email-connection-throttling-5.png)

Als de wijzigingen zijn opgeslagen, worden de e-mails van alle gebruikers batchgewijs naar hun aangesloten Gmail- of [!DNL Exchange] -account verzonden voor levering.

## Limieten voor e-mailproviders {#email-provider-limits}

**[!DNL Outlook 365]**

Zakelijk/Enterprise

* 10.000 per dag
* 30 per minuut
* 500 ontvangers per e-mail

Meer informatie [ kan hier ](https://docs.microsoft.com/en-us/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits?redirectedfrom=MSDN#RecipientLimits) worden gevonden.

**Gmail**

* 2000 per dag (500 voor proefaccounts en accounts met vlag)
* 2 e-mails per seconde (API-limiet)
* 2.000 ontvangers per bericht (maximaal 500 voor externe ontvangers)

Meer informatie [ kan hier ](https://support.google.com/a/answer/166852?hl=en) worden gevonden.

**[!DNL Microsoft Exchange Server (2010, 2013)]**

De grenzen worden geplaatst door de afdeling van IT van de organisatie aangezien de server door de organisatie wordt ontvangen. Neem contact op met de netwerk- of systeembeheerder voor aanvullende informatie.

>[!MORELIKETHIS]
>
>* [ Overzicht van het Kanaal van de Levering ](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/delivery-channel-overview.md)
>* [ E-mailVerbinding voor de Gebruikers van Gmail ](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md)
>* [ E-mailVerbinding voor  [!DNL Outlook]  Gebruikers ](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md)
