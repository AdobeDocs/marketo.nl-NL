---
description: Voordat u naar de nieuwe instantie van het Marketo Engage gaat, moet u een aantal basisstappen uitvoeren voor doorlopend gebruik. Deze stappen omvatten de opstelling van gebruikersrekening, de opstelling van de steunbeheerder, en het intekenen aan aan aan de gang zijnde systeemupdates.
title: Controlelijst voor gebruikersinstellingen
feature: Getting Started
exl-id: c7b068fc-a038-4f9c-a037-72440a1a864e
source-git-commit: a3d9fcfa0381933e1a7e62f19b414bc380f325b5
workflow-type: tm+mt
source-wordcount: '799'
ht-degree: 0%

---

# Controlelijst voor gebruikersinstellingen {#user-setup-checklist}

Nu u alle [eerste installatiestappen](/help/marketo/getting-started/initial-setup/setup-steps.md){target="_blank"}, is het tijd om een aantal basiselementen vast te stellen voor een vloeiend, doorlopend gebruik. Dit zal de basis leggen voor uw reis met Marketo Engage en u helpen het beste van zijn eigenschappen maken. Laten we beginnen!

>[!NOTE]
>
>U kunt deze checklist ook downloaden, [samen met een lijst van beste praktijken](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx) voor uw nieuwe exemplaar, en controleer de stappen aangezien u gaat.

## Marketo Engage over Adobe Identity Management {#marketo-engage-on-adobe-identity-management}

Je nieuwe abonnementen op Marketo&#39;s Engage zijn ingeschakeld voor [Adobe Identity Management System (IMS)](https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html). Ga naar de volgende gebruikersbeheercontrole in Adobe Admin Console.

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Abonnement en productbeheerder van Marketo Engage</td>
    <td><li>Bevestig dat uw Adobe of systeembeheerder u een Adobe-productbeheerrol heeft toegekend.</li>  
    <ul>
    <li>Neem contact op met het accountteam van de Adobe (uw accountmanager) of stuur een e-mail naar <code>customercare@marketo.com</code> of stuur een e-mail naar customercare@marketo.comto om te achterhalen wie op uw bedrijf is <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html">Adobe Admin Console System Admin</a> rechten.</li></ul>
    <li>Accepteer de uitnodiging 'Marketo Engage Product Admin' om uw Adobe ID te activeren. De <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/admin-setup.html?lang=en#create-a-product-profile">welkome e-mail</a> wordt verzonden wanneer de rol in de Adobe Admin Console wordt toegewezen.</li></td>
  </tr>
  <tr>
    <td>Productprofielen</td>
    <td><li>Wijs alle gewenste gebruikers aan het Marketo Engage toe <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/admin-setup#create-a-product-profile">Productprofiel</a> in Adobe Admin Console.</li>
    <ul>
    <li>U kunt gebruikersrollen niet toewijzen in Marketo Engage &gt; Beheer &gt; Gebruikers en rollen voordat u ze aan een productprofiel toevoegt.</li>
    <li>Elk abonnement is een zelfstandig productprofiel. Als een ongewenste gebruiker aan meerdere productprofielen wordt toegevoegd (bijvoorbeeld de productie- en testsandbox), moet u de gebruiker uit alle productprofielen verwijderen. Anders hebben ze nog steeds toegang tot Marketo Engage.</li></ul></td>
  </tr>
  <tr>
    <td>Gebruikers</td>
    <td><li>Een beleid maken voor wanneer <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.html">een gebruiker maken</a>.</li> <li>Maak een beleid voor het verwijderen van gebruikers.</li>
    <li>Bepalen wie moet hebben <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html">Adobe System Admin and Marketo Engage Product Admin permissions.</a> <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user">Gebruikers toevoegen</a> naar het gewenste productprofiel.</li>
    <li>Maak één API-gebruiker voor elke API-gebruikscase.</li></td>
  </tr>
  <tr>
    <td>Gebruikersbeheer-API (indien van toepassing)</td>
    <td><li>Gebruik de <a href="https://www.adobe.io/apis/experienceplatform/umapi-new.html">Adobe-gebruikersbeheer-API</a> om gebruikers uit te nodigen, bij te werken en te verwijderen.</li>
    <li>Gebruik de <a href="https://developer.adobe.com/umapi/">Adobe-gebruikersbeheer-API</a> om rollen toe te voegen of te verwijderen (bijvoorbeeld, Beheerders, Admins van de Steun, Ontwikkelaars).</li>
    </td>
  </tr>
  <tr>
    <td>Beheerder productondersteuning</td>
    <td><li>Naar <a href="https://experienceleague.adobe.com/docs/customer-one/using/home.html#create-a-support-ticket-with-admin-console">een ondersteuningsticket indienen in de Adobe Admin Console</a>, moet u de rol "Beheerder van de Steun van het Product"hebben die door een Beheerder van het Systeem aan de abonnementen wordt toegewezen u beheert. Alleen een systeembeheerder in uw organisatie kan <a href="https://experienceleague.adobe.com/docs/customer-one/using/home.html#assign-the-support-admin-role">toewijzen aan deze rol</a>.</li>
    <li>Mogelijk hebt u van de systeembeheerder een e-mail ontvangen waarin u opgeeft dat u de beheerder van de ondersteuning voor uw abonnement op het Marketo Engage bent. Als dat het geval is, klikt u op <a href="https://experienceleague.adobe.com/en/docs/customer-one/using/home#assign-the-support-admin-role">'Aan de slag'</a> in de e-mail om lid te worden van de organisatie.</li>
    <li>Bepaal de aangewezen contacten (met minstens één reservecontact) en hebben de Beheerder van het Systeem de rol van Admin van de Steun van het Product dienovereenkomstig toewijzen.</li></td>
  </tr>
</tbody>
</table>

## Dynamic Chat bij Adobe Identity Management Setup {#dynamic-chat-on-adobe-identity-management}

Te gebruiken [Dynamic Chat](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.html), het native gespreksautomatiseringskanaal in Marketo Engage, ga met de opstelling van de gebruikerstoestemming te werk na de hieronder stappen in [Adobe Admin Console](https://adminconsole.adobe.com/){target="_blank"}.

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Abonnement en productbeheerder van Dynamic Chat (indien van toepassing)</td>
    <td><li>Bevestig dat uw Adobe of systeembeheerder u een Adobe-productbeheerrol heeft toegekend.</li> 
    <ul><li>Neem contact op met het accountteam van de Adobe (uw accountmanager) of stuur een e-mail naar <code>customercare@marketo.com</code> om te weten te komen wie op uw organisatie <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html">Adobe Admin Console System Admin</a> rechten.</li></ul>
    <li>Accepteer de <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html">'Dynamic Chat Product Admin'</a> uitnodigen. De <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html">welkome e-mail</a> wordt verzonden wanneer de Dynamic Chat in uw instantie van het Marketo Engage wordt toegelaten en u als Admin van het Systeem wordt aangewezen.</li></td>
  </tr>
  <tr>
    <td>Productprofielen</td>
    <td><li>Wijs alle gewenste gebruikers toe aan het productprofiel van de Dynamic Chat in Adobe Admin Console.</li> 
    <ul>
    <li>Als een ongewenste gebruiker aan meerdere productprofielen wordt toegevoegd, moet u de gebruiker uit alle productprofielen verwijderen. Anders hebben ze nog steeds toegang tot Dynamic Chat.</li>
    <li>U kunt <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions#edit-existing-permissions">Productprofielen bewerken in Dynamic Chat</a> en maak een aangepast profiel met een aangepaste set van <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions#list-of-permissions">rechten beschikbaar binnen uw abonnement</a>.</li></td>
  </tr>
  <tr>
    <td>Gebruikers</td>
    <td><li>Creeer een beleid wanneer om een praatjegebruiker toe te voegen en te verwijderen.</li>
    <li>Een beleid maken voor wie <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup#access-admin-console">Machtigingen voor productbeheer Adoben Dynamic Chat.</a></li>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users#add-a-chat-user">Gebruikers toevoegen aan het gewenste productprofiel</a>.</li></td>
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
    <td><li><a href="https://status.adobe.com/cloud/experience_cloud">Abonneren op Adobe Marketo Engage Status-updates</a>.</li></td>
  </tr>
  <tr>
    <td>Meldingen</td>
    <td><li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/miscellaneous/understanding-notifications#subscribe-to-notifications">Abonneren op beheerdersmeldingen</a> voor kritieke kwesties zoals fouten in uw Slimme Campagnes, en kritieke kwesties die met de synchronisatie van CRM worden gevonden.</li></td>
  </tr>
</tbody>
</table>

<p>

Nu je Marketo Engage-account klaar is voor gebruik, kun je onze [Beste praktijken voor een Nieuwe Instantie van het Marketo Engage](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/where-to-start.md){target="_blank"} om optimaal te profiteren van uw investering en zichzelf op te zetten voor succes op de lange termijn.
