---
description: Abonnementsoverzicht - Marketo Docs - Productdocumentatie
title: Overzicht van abonnement opzeggen
exl-id: 7598efa9-9686-4dd0-840b-f8b6de4ab2be
feature: Sales Insight Actions
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '328'
ht-degree: 0%

---

# Overzicht van abonnement opzeggen {#unsubscribe-overview}

Het wordt steeds belangrijker voor organisaties om zich aan de wetten van de e-mailprivacy te houden. Om dit te helpen, hebben we een aantal verbeteringen aangebracht in onze ervaring voor afmelden.

* Koppelingen voor abonnementen worden geplaatst op alle e-mails die vanuit [!DNL Marketo Sales] en [!DNL Salesforce] worden verzonden (dit geldt niet voor aangepaste e-mails die vanuit [!DNL Outlook] of Gmail worden verzonden)
* Admins kunnen unsubscribe overseinen voor hun volledig team uitgeven
* Afmeldingsgegevens worden opgeslagen in PDV
* U kunt uw abonnement handmatig opzeggen: klik op Koppeling, [!DNL Salesforce] Synchroniseren en Stuiteren
* Nieuwe bestemmingspagina voor afmelding van koppeling

## Abonnement op bestemmingspagina van koppeling opzeggen {#unsubscribe-link-landing-page}

Wanneer iemand op de koppeling voor afmelden klikt, wordt hij of zij doorgestuurd naar een bestemmingspagina waar hij of zij kan selecteren van welke persoon hij of zij afmeldt en waarom.

![](assets/unsubscribe-overview-1.png)

Deze informatie wordt opgeslagen in de weergave met persoonlijke details voor weergave op een later tijdstip.

## Groep afmelden {#unsubscribe-group}

Alle geabonneerde personen op één locatie bekijken en beheren.

![](assets/unsubscribe-overview-2.png)

Gebruik de zoekbalk om geabonneerde personen op te zoeken.

![](assets/unsubscribe-overview-3.png)

Als u een beheerder bent, kunt u naar de groep gaan unsubscribe om door [!UICONTROL Account Unsubscribes] te filtreren en alle unsubscribes te zien die in uw personengegevensbestand zijn verzameld.

![](assets/unsubscribe-overview-4.png)

## Historiekaart afmelden {#unsubscribe-history-card}

Met de [!UICONTROL Unsubscribe History] -kaart krijgen beheerders en gebruikers contextafhankelijke informatie over de geschiedenis van hun contactpersonen. Navigeer daar door naar het tabblad [!UICONTROL People] te gaan en een persoon te selecteren. Deze bevindt zich onder aan het tabblad [!UICONTROL About] in de weergave Details persoon.

>[!NOTE]
>
>Er zal slechts een [!UICONTROL Unsubscribe History] kaart zijn als de persoon _resubscribed_ op één of ander punt heeft.

![](assets/unsubscribe-overview-5.png)

<table> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>[!UICONTROL Date]</strong></td> 
   <td><p>Hier wordt de datum weergegeven waarop het abonnement is opgezegd of opnieuw is geabonneerd.</p></td> 
  </tr> 
  <tr> 
   <td><strong>[!UICONTROL Details]</strong></td> 
   <td><p>Opnieuw abonneren: een [!DNL Sales Connect] -beheerder heeft het abonnement handmatig uit de contactrecord verwijderd. Het kan ook enkele details weergeven met betrekking tot waarom de contactpersoon niet is geabonneerd.</p><p>Abonnement opzeggen: de contactpersoon is afgemeld.</p></td> 
  </tr> 
  <tr> 
   <td><strong>[!UICONTROL Source]</strong></td> 
   <td><p>[!DNL Salesforce] Sync: Unsubscribe is vastgelegd via een synchronisatie uit [!DNL Salesforce] .</p><p>Handmatig: de gebruiker heeft op de knop Abonnement opzeggen geklikt om te weigeren.</p><p>Klik op Koppeling: de ontvanger van een e-mail heeft op de koppeling voor het opzeggen van het abonnement geklikt.</p><p>"Naam beheerder": de naam van een beheerder wordt weergegeven wanneer de handeling opnieuw contactpersonen moet abonneren. Gebruikers weten wie het abonnement heeft verwijderd.</p></td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>[ pas Unsubscribe Bericht van de Verbinding ](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/customize-unsubscribe-link-message.md) aan
