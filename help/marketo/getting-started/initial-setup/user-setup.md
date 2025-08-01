---
description: Voordat u aan de slag gaat met uw nieuwe Marketo Engage-instantie, moet u een aantal basisstappen voltooien voor doorlopend gebruik. Deze stappen omvatten het instellen van een gebruikersaccount, het instellen van de ondersteuningsbeheerder en het abonneren op doorlopende systeemupdates.
short-description: Nadat u de eerste installatiestappen hebt voltooid, leert u hoe u de basiselementen kunt instellen voor een vloeiend doorlopend gebruik.
title: Controlelijst voor gebruikersinstellingen
feature: Getting Started
exl-id: c7b068fc-a038-4f9c-a037-72440a1a864e
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '823'
ht-degree: 6%

---

# Controlelijst voor gebruikersinstellingen {#user-setup-checklist}

Nu u alle [ aanvankelijke opstellingsstappen ](/help/marketo/getting-started/initial-setup/setup-steps.md){target="_blank"} hebt voltooid, is het tijd om sommige stichtingselementen te vestigen om vlot aan de gang zijnde gebruik te verzekeren. Dit zal de basis leggen voor uw reis met Marketo Engage en u helpen om optimaal gebruik te maken van zijn functies. Laten we beginnen!

>[!NOTE]
>
>U kunt deze controlelijst, [ samen met een lijst van beste praktijken ](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx) voor uw nieuwe instantie ook downloaden, en de stappen controleren aangezien u gaat.

## Marketo Engage op Adobe Identity Management {#marketo-engage-on-adobe-identity-management}

Uw nieuwe abonnementen van Marketo Engage worden in kaart gebracht aan [ Adobe Identity Management Systeem (IMS) ](https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html?lang=nl-NL). Ga naar de volgende gebruikersbeheercontrole in Adobe Admin Console.

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Abonnement en Marketo Engage-productbeheerder</td>
    <td><li>Bevestig dat uw Adobe Org System Admin een Adobe-rol voor productbeheer heeft toegekend.</li>
    <ul>
    <li>Contacteer het team van de Rekening van Adobe (uw Manager van de Rekening) of verzend een e-mail naar <code>marketocares@marketo.com</code> om te weten wie bij uw organisatie <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html?lang=nl-NL"> Admin van het Systeem van Adobe Admin Console </a> voorrechten heeft.</li></ul>
    <li>Accepteer de uitnodiging voor 'Marketo Engage-productbeheer' om uw Adobe ID te activeren. <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/admin-setup.html?lang=nl-NL#create-a-product-profile"> welkome e-mail </a> wordt verzonden wanneer de rol in Adobe Admin Console wordt toegewezen.</li></td>
  </tr>
  <tr>
    <td>Productprofielen</td>
    <td><li>Wijs alle gewenste gebruikers aan het Profiel van het Product van Marketo Engage <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/admin-setup#create-a-product-profile"> </a> in Adobe Admin Console toe.</li>
    <ul>
    <li>U kunt gebruikersrollen niet toewijzen in Marketo Engage &gt; Beheer &gt; Gebruikers en rollen voordat u ze aan een productprofiel toevoegt.</li>
    <li>Elk abonnement is een zelfstandig productprofiel. Als een ongewenste gebruiker aan meerdere productprofielen wordt toegevoegd (bijvoorbeeld de productie- en testsandbox), moet u de gebruiker uit alle productprofielen verwijderen. Anders hebben ze nog steeds toegang tot Marketo Engage.</li></ul></td>
  </tr>
  <tr>
    <td>Gebruikers</td>
    <td><li>Creeer een beleid wanneer om <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.html?lang=nl-NL"> een gebruiker </a> tot stand te brengen.</li> <li>Maak een beleid voor het verwijderen van gebruikers.</li>
    <p><img src="assets/note-icon.png" alt="notitiepictogram"> NOTA: U moet een Admin van het Systeem zijn om gebruikers te verwijderen.
    <li>Bepaal wie <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html?lang=nl-NL"> Admin van het Systeem van Adobe en de toestemmingen van Admin van het Product van Marketo Engage zou moeten hebben.</a> <li><a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user"> voeg gebruikers </a> aan het gewenste Profiel van het Product toe.</li>
    <li>Maak één API-gebruiker voor elke API-gebruikscase.</li></td>
  </tr>
  <tr>
    <td>Gebruikersbeheer-API (indien van toepassing)</td>
    <td><li>Gebruik <a href="https://www.adobe.io/apis/experienceplatform/umapi-new.html"> Adobe API van het Gebruikersbeheer </a> om, gebruikers uit te nodigen bij te werken en te schrappen.</li>
    <li>Gebruik <a href="https://developer.adobe.com/umapi/"> Adobe API van het Gebruikersbeheer </a> om rollen (b.v., Beheerders, Admins van de Steun, Ontwikkelaars) toe te voegen of te verwijderen.</li>
    </td>
  </tr>
  <tr>
    <td>Beheerder productondersteuning</td>
    <td><li>Om <a href="https://experienceleague.adobe.com/docs/customer-one/using/home.html?lang=nl-NL#create-a-support-ticket-with-admin-console"> een steunkaartje in Adobe Admin Console </a> voor te leggen, moet u de rol van de Beheerder van de Steun van het Product hebben die door een Beheerder van het Systeem aan de abonnementen wordt toegewezen u beheert. Slechts kan een Beheerder van het Systeem in uw organisatie <a href="https://experienceleague.adobe.com/docs/customer-one/using/home.html?lang=nl-NL#assign-the-support-admin-role"> u aan deze rol </a> toewijzen.</li>
    <li>Mogelijk hebt u van de systeembeheerder een e-mail ontvangen waarin u opgeeft dat u de beheerder van de ondersteuning voor uw Marketo Engage-abonnement bent. Als zo, klik <a href="https://experienceleague.adobe.com/nl/docs/customer-one/using/home#assign-the-support-admin-role"> "krijgen Begonnen"</a> in e-mail om zich bij de organisatie aan te sluiten.</li>
    <li>Bepaal de aangewezen contacten (met minstens één reservecontact) en hebben de Beheerder van het Systeem de rol van Admin van de Steun van het Product dienovereenkomstig toewijzen.</li></td>
  </tr>
</tbody>
</table>

## Dynamic Chat op Adobe Identity Management Setup {#dynamic-chat-on-adobe-identity-management}

Om [ Dynamic Chat ](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.html?lang=nl-NL) te gebruiken, gaat het inheemse kanaal van de gespreksautomatisering in Marketo Engage, met de opstelling van de gebruikerstoestemming na de stappen hieronder in [ Adobe Admin Console ](https://adminconsole.adobe.com/){target="_blank"} te werk.

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Abonnement en Dynamic Chat-productbeheerder (indien van toepassing)</td>
    <td><li>Bevestig dat uw Adobe Org System Admin een Adobe-rol voor productbeheer heeft toegekend.</li>
    <ul><li>Contacteer het team van de Rekening van Adobe (uw Manager van de Rekening) of verzend een e-mail naar <code>marketocares@marketo.com</code> om te weten wie bij uw organisatie <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html?lang=nl-NL"> Admin van het Systeem van Adobe Admin Console </a> voorrechten heeft.</li></ul>
    <li>Accepteer de uitnodiging <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html?lang=nl-NL">'Dynamic Chat Product Admin' </a> . <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html?lang=nl-NL"> welkome e-mail </a> wordt verzonden wanneer Dynamic Chat in uw instantie van Marketo Engage wordt toegelaten en u als Admin van het Systeem wordt aangewezen.</li></td>
  </tr>
  <tr>
    <td>Productprofielen</td>
    <td><li>Wijs alle gewenste gebruikers toe aan het productprofiel van Dynamic Chat in Adobe Admin Console.</li>
    <ul>
    <li>Als een ongewenste gebruiker aan meerdere productprofielen wordt toegevoegd, moet u de gebruiker uit alle productprofielen verwijderen. Anders hebben ze nog steeds toegang tot Dynamic Chat.</li>
    <li>U kunt <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions#edit-existing-permissions"> Profielen van het Product in Dynamic Chat </a> uitgeven en een douaneprofiel met een douanereeks <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions#list-of-permissions"> toestemmingen tot stand brengen beschikbaar binnen uw abonnement </a>.</li></td>
  </tr>
  <tr>
    <td>Gebruikers</td>
    <td><li>Creeer een beleid wanneer om een praatjegebruiker toe te voegen en te verwijderen.</li>
    <li>Creeer een beleid op wie {de toestemmingen van Admin van het Product van 0} Adobe Dynamic Chat zou moeten hebben.<a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup#access-admin-console"></a></li>
    <li><a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users#add-a-chat-user"> voegt gebruikers aan het gewenste Profiel van het Product </a> toe.</li></td>
  </tr>
</tbody>
</table>

## Aan de slag met systeemupdates en communicatie {#system-updates}

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Adobe Marketo-statusupdates</td>
    <td><li><a href="https://status.adobe.com/cloud/experience_cloud"> maak een abonnement op de updates van de Status van Adobe Marketo Engage </a>.</li></td>
  </tr>
  <tr>
    <td>Meldingen</td>
    <td><li><a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/core-marketo-concepts/miscellaneous/understanding-notifications#subscribe-to-notifications"> abonneert aan admin berichten </a> voor kritieke kwesties zoals fouten in uw Slimme Campagnes, en kritieke kwesties die met de synchronisatie van CRM worden gevonden.</li></td>
  </tr>
</tbody>
</table>

<p>

Nu uw rekening van Marketo Engage klaar is om te gaan, te herzien gelieve onze [ Beste praktijken voor een Nieuwe sectie van de Instantie van Marketo Engage ](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/where-to-start.md){target="_blank"} om het meeste uit uw investering te krijgen en opstelling zelf op lange termijn succes.
