---
description: Gebruikers- en licentiebeheer - Marketo Docs - Productdocumentatie
title: Gebruiker- en licentiebeheer
exl-id: 1fee628b-e9f3-46ab-b993-f2d09fe5e183
feature: Interactive Webinars
source-git-commit: b5fb106126e52a8d759e560d21e525e21154a4d6
workflow-type: tm+mt
source-wordcount: '703'
ht-degree: 0%

---

# Gebruiker- en licentiebeheer {#user-and-license-management}

Leer om gebruikers toe te voegen en te verwijderen en uw huidige vergunningen te bekijken.

## Een gebruiker toevoegen {#add-a-user}

1. Ga naar de **Beheerder** gebied.

   ![](assets/user-and-license-management-1.png)

1. Klikken **Interactieve webinars**.

   ![](assets/user-and-license-management-2.png)

1. Klikken **Gebruikers toevoegen/verwijderen**.

   ![](assets/user-and-license-management-3.png)

1. Klik op de vervolgkeuzelijst Beschikbare gebruikers, selecteer de gebruiker(s) die u wilt toevoegen en klik op **OK**.

   ![](assets/user-and-license-management-4.png)

## Een gebruiker verwijderen {#remove-a-user}

1. Ga naar de **Beheerder** gebied.

   ![](assets/user-and-license-management-5.png)

1. Klikken **Interactieve webinars**.

   ![](assets/user-and-license-management-6.png)

1. Klikken **Gebruikers toevoegen/verwijderen**.

   ![](assets/user-and-license-management-7.png)

1. Markeer de gebruiker(s) die u wilt verwijderen en druk op de toets Delete op het toetsenbord. Klikken **OK** wanneer gereed.

   ![](assets/user-and-license-management-8.png)

## Licentiegebruik {#license-usage}

Interactive Webinars biedt specifieke licenties voor het maken van gebeurtenissen die worden aangedreven door Adobe Connect. Telkens wanneer een licentie wordt toegevoegd, wordt er een nieuw gebruiksvak voor de licentie weergegeven. Marketo Admins kan de licenties weergeven (niet bewerken) door de onderstaande stappen uit te voeren. Neem contact op met het accountteam van de Adobe (uw accountmanager) voor extra licenties.

1. Ga naar de **Beheerder** gebied.

   ![](assets/user-and-license-management-9.png)

1. Klikken **Interactieve webinars**.

   ![](assets/user-and-license-management-10.png)

1. Blader omlaag naar de Gebruikskaart(en) voor licenties.

   ![](assets/user-and-license-management-11.png)

<table> 
  <tr>
   <td width="20%"><b>Begindatum</b></td>
   <td>De datum waarop de licentie begint.</td>
  </tr>
  <tr> 
   <td width="20%"><b>Vervaldatum</b></td>
   <td>De vervaldatum van de licentie.</td>
  </tr>
  <tr> 
   <td width="20%"><b>Type</b></td>
   <td>Het type licentie dat is aangeschaft. Er zijn drie typen beschikbaar: licentie voor gedeelde gebeurtenissen, licentie voor gedeelde ruimten, extra opslaglicentie.</td>
  </tr>
  <tr> 
   <td width="20%"><b>Gebeurteniscapaciteit</b></td>
   <td>Het maximumaantal deelnemers dat in een gebeurtenis kan worden opgenomen.</td>
  </tr>
  <tr> 
   <td width="20%"><b>Totaal aantal gebeurtenissen</b></td>
   <td>Het totale aantal gebeurtenissen dat is voorzien van deze licentie.</td>
  </tr>
  <tr> 
   <td width="20%"><b>Verbruikte gebeurtenissen</b></td>
   <td>Het totale aantal voltooide gebeurtenissen.</td>
  </tr>
  <tr> 
   <td width="20%"><b>Opslagcapaciteit</b></td>
   <td>Bedrag van de opslagruimte die beschikbaar is voor het opslaan van opnamen, zekerheden, hero images, documentatie en andere activa.</td>
  </tr>
  </tbody>
</table>

**Notities**

* Het type &quot;Aanvullende opslagvergunning&quot; biedt alleen opslag, dus de waarde in elk veld _naast_ Opslagcapaciteit wordt gewoon weergegeven als &quot;-&quot;.

* Het type &#39;Licentie voor gedeelde ruimte&#39; heeft onbeperkte gebeurtenissen en &#39;Aanvullende opslaglicentie&#39; biedt alleen opslagruimte, zodat het veld Totaal aantal gebeurtenissen voor deze licenties eenvoudig wordt weergegeven als &#39;-&#39;.

* Telkens wanneer een gebeurtenis wordt gecreeerd, zal het als &quot;verbruikt&quot;van zijn respectieve vergunning (tenzij het een Gedeelde Vergunning van de Ruimte is) tellen. De voorkeur wordt gegeven aan &quot;Shared Event License&quot; als er zowel &quot;Shared Event License&quot; als &quot;Shared Room License&quot; met dezelfde capaciteit zijn. Als de gebeurtenis niet is afgeleverd en als het gebeurtenisprogramma voor de geplande tijd wordt verwijderd, wordt het aantal gebeurtenissen verhoogd door een gebeurtenis van de verbruikte gebeurtenissen af te trekken.

* Zodra een licentie is uitgeput, blijft de tegel op het scherm Interactieve webinars in de Admin-sectie met &quot;Totaal aantal gebeurtenissen&quot; en &quot;Verbruikte gebeurtenissen&quot; met dezelfde waarde staan. Alleen wanneer de licentie verloopt, wordt deze van het scherm verwijderd.

## Toegang tot gebruikers {#user-access}

Interactieve webinars hebben de functionaliteit om het gebruik te regelen door gebruikers van het Marketo Engage machtigingen te geven om interactieve webinars te maken en te leveren. Een interactieve webinar-gebruiker (of niet-gebruiker) kan echter nog wel lees- en bewerktoegang hebben tot programma&#39;s voor interactieve webinars die door andere gebruikers zijn gemaakt.

Marketo-gebruikers aan wie interactieve webinars is toegestaan en die eigenaar zijn van een bepaald Interactief Webinars-gebeurtenisprogramma, kunnen alle interactieve webinar-functies met betrekking tot dat programma uitvoeren. Dit omvat: het creëren van, de toegang tot van, het wijzigen van, het klonen van, het bewegen van, en het schrappen van dat programma. Nochtans, zodra die gebruiker niet meer een Interactieve webinar gebruiker is, zou de eigenaar van het programma tot het programma kunnen toegang hebben en bewegen, maar geen andere functies uitvoeren.

Marketo-gebruikers die interactieve webinars hebben ontvangen en die _niet_ eigenaars van een bepaald Interactive Webinars Event Program zouden beperkte functies kunnen uitoefenen op die programma&#39;s. Marketo-gebruikers zonder beheerdersrechten hebben wel toegang tot het programma en kunnen het klonen, maar kunnen geen andere functies uitvoeren als ze over toegangsrechten voor interactieve webinars beschikken. Marketo Admin-gebruikers _zal_ alle functies kunnen uitvoeren, zoals toegang tot, het wijzigen van, het klonen van, het bewegen van, en het schrappen van dat programma (zolang zij toestemmingen voor Interactieve Webinars hebben). Als deze machtiging is ingetrokken voor Marketo Admin- en niet-Admin-gebruikers, hebben zij alleen toegang tot het Interactive Webinar Event Program en kunnen zij geen andere functies meer uitvoeren.

De beperking van actieffuncties wordt aangegeven met een grijze actieknop en een aanwijsbericht. Enkele voorbeelden van de grijze actieknoppen zijn &#39;Design Your Webinar&#39; of &#39;Enter Your Webinar&#39;. Voor niet-activeerbare functies zou een bericht worden verstrekt die de beperkingen benadrukt. Zie het onderstaande voorbeeld:

![](assets/user-and-license-management-12.png)
