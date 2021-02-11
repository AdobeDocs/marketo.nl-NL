---
unique-page-id: 14745730
description: Salesforce Diagnostics - Marketo Docs - Productdocumentatie
title: Salesforce Diagnostics
translation-type: tm+mt
source-git-commit: 1dd80b7de801df78ac7dde39002455063f9979b7
workflow-type: tm+mt
source-wordcount: '1427'
ht-degree: 0%

---


# Salesforce Diagnostics {#salesforce-diagnostics}

Een onderdeel van onze Salesforce-integratie is de pagina Salesforce Diagnostic in de webtoepassing. Deze pagina legt fouten van ontbroken gegevensregistreren aan Salesforce vast. De fouten kunnen nuttig zijn, maar zijn niet altijd leesbaar. Als zodanig maken we een bedriegblad dat de foutberichten helpt verklaren.

**Fout:** API_CURRENTLY_DISABLED\
**Categorie:** Toegang/Validatie\
**Bericht:** API is uitgeschakeld voor deze gebruiker\
**Wat gebeurt er:** gebruiker heeft geen API-toegang\
**Stappen voor probleemoplossing:** Salesforce Admin moet de gebruiker API-toegang verlenen.

<br> 

**Fout:** AUTHENTICATION_FAILURE\
**Categorie:** verificatie\
**Bericht:** ongeldige_subsidie: verificatiefout\
**Wat gebeurt er?** Verificatie is mislukt\
**Stappen voor probleemoplossing:** Verbinding met Salesforce verbreken en vervolgens opnieuw verbinden.

<br> 

**Fout:** CANNOT_INSERT_UPDATE_ACTIVATE_ENTITY\
**Categorie:** Toegang/Validatie\
**Bericht:** {&quot;errorCode&quot;:&quot;INVALID_SESSION_ID&quot;,&quot;message&quot;:&quot;Session expired or invalid&quot;}\
**Wat gebeurt er?**

1 - Trigger-code zorgt ervoor dat de update mislukt.\
2 - Gebruiker heeft geen schrijfmachtigingen op objectniveau voor het opgegeven object.

**Stappen voor probleemoplossing:**

1 - Controleer de trigger die faalt.\
2 - Biedt schrijftoegang aan de gebruiker voor het object OF schakelt de functie uit die naar het object probeert te schrijven.

<br> 

**Fout:** CANNOT_UPDATE_CONVERTED_LEAD\
**Categorie:** Overige\
**Bericht:** kan niet verwijzen naar omgezette lead\
**Wat gebeurt er:** We proberen ons te aanmelden bij een geconverteerde lead tijdens de meest recente activiteitenregistratie voor contactpersonen en leads. Ook een paar van deze voor toonhoogte.\
**Stappen voor het oplossen van problemen:** Meld om het even welke instanties van dit aan ons  [ondersteuningsteam](https://nation.marketo.com/t5/Support/ct-p/Support).

<br> 

**Fout:** ENTITY_IS_LOCKED\
**Categorie:** Toegang/Validatie\
**Bericht:** de entiteit is vergrendeld voor bewerken\
**Wat er gebeurt:** de registratie bevindt zich in een goedkeuringsproces waarbij het is vergrendeld van aanvullende bewerkingen totdat deze is goedgekeurd of geweigerd door een persoon die eigenaar is van de goedkeuring.\
**Stappen voor probleemoplossing:** Zie hierboven.

<br> 

**Fout:** EXPIRED_ACCESS-
**categorie:** verificatiebericht 
**:** invalid_Grant: verlopen toegang/verfrist symbolische 
**wat gebeurt:** de toegang of verfrist symbolische teken is verlopen. De tokens verlopen gebaseerd op [zittingsmontages in Salesforce](https://salesforce.stackexchange.com/questions/10759/invalid-grant-expired-access-refresh-token-error-when-authenticating-access-via).
**Stappen voor het oplossen van problemen:** U moet opnieuw verifiëren. Maak de verbinding met Salesforce los en maak opnieuw verbinding.

<br> 

**Fout:** FAILED_WRITE\
**categorie:** periodiek\
**Bericht:** einde bestand bereikt\
**Wat gebeurt er:** Prestatieprobleem met Salesforce, waarschijnlijk als gevolg van suboptimale triggers aan de kant van de klant.\
**Stappen voor probleemoplossing:dit moet worden verwerkt door de logica** Opnieuw proberen. Als het nog niet werkt, werk met uw beheerder Salesforce om een problematische trekker problemen op te lossen.

<br> 

**Fout:** FIELD_CUSTOM_VALIDATION_EXCEPTION 
**Categorie:** Toegang/
**Bericht van de Bevestiging:** varieert van klant tot klant.
**Wat gebeurt er? Er** ontbreekt een aangepaste validatieregel voor het object.
**Stappen voor probleemoplossing:** controleer de aangepaste validatieregel die deze fout veroorzaakt. Aangezien dit een aangepaste regel is, moet de fout eenmalig worden behandeld.

<br> 

**Fout:** FIELD_FILTER_VALIDATION_EXCEPTION\
**Categorie:** Toegang/Validatie\
**Bericht:** waarde bestaat niet of komt niet overeen met filtercriteria\
**Wat gebeurt er?** Bestaande slechte gegevens in Salesforce worden afgedwongen bij update.\
**Stappen voor probleemoplossing:** Zie hierboven.

<br> 

**Fout:** FIELD_INTEGRITY_EXCEPTION\
**Categorie:** Toegang/Validatie\
**Bericht:** Het bestaande land/gebied herkent de staatswaarde voor gebied niet: Provincie\
**Wat gebeurt er?** Bestaande slechte gegevens in Salesforce worden afgedwongen bij update.\
**Stappen voor probleemoplossing:** Zie hierboven.

<br> 

**Fout:** INACTIVE_ORGANIZATION\
**Categorie:** verificatie\
**Bericht:** ongeldige_subsidie: inactieve organisatie\
**Wat gebeurt er?** Uw Salesforce-organisatie is niet meer actief.\
**Stappen voor het oplossen van problemen:** maak dan los van Salesforce opnieuw aan.

**Fout:** INACTIVE_USER-
**categorie:** verificatiebericht 
**:** invalid_Grant: inactieve gebruiker 
**wat gebeurt:** De gebruiker Salesforce is niet meer actieve 
**Stappen van het Oplossen van problemen:** losmaken dan opnieuw verbind van Salesforce.

**Fout:** INSERT_UPDATE_DELETE_NOT_ALLOWED_DURING_MAINTENANCE\
**categorie:** periodiek\
**Bericht:** (geen extra bericht)\
**Wat gebeurt er? De** Salesforce-instantie bevindt zich in de onderhoudsmodus.\
**Stappen voor het oplossen van problemen:** Wacht tot het systeemonderhoud is voltooid en probeer het registreren opnieuw.

**Fout:** INSUFFICIENT_ACCESS_ON_CROSS_REFERENCE_ENTITY 
**Categorie:** Toegang/
**Bericht van de Bevestiging:** ontoereikende toegangsrechten op objecten identiteitskaart 
**wat gebeurt:** Geen toegang tot het ouderverslag voor een taak.
**Stappen voor probleemoplossing:** Zie hierboven.

<br> 

**Fout:** INSUFFICIENT_ACCESS_OR_READONLY\
**Categorie:** Toegang/
**Bericht van de Bevestiging:** ontoereikende toegangsrechten op objecten identiteitskaart 
**wat gebeurt:Het** meest Recente registreren van de Activiteit kan niet het specifieke verslag uitgeven omdat de gebruiker geen schrijven-aan toegang heeft.\
**Stappen voor het oplossen van problemen:** verstrek de gebruikerstoegang in Salesforce OF maak het Meest recente registreren van de Activiteit voor dat voorwerp voor die gebruiker onbruikbaar.

**Fout:** INVALID_FIELD\
**categorie:** periodiek\
**Bericht:** Net:ReadTimeout\
**Wat gebeurt er?** Verzoek is time-out. Dit is waarschijnlijk het gevolg van te veel trage transacties.\
**Stappen voor probleemoplossing:bestaande aanpassingen voor mogelijke oorzaken van latentieproblemen** controleren en/of het logbestand met de meest recente activiteit uitschakelen voor een of alle objecten om de belasting te verminderen.

**Fout:** INVALID_FIELD_FOR_INSERT_UPDATE\
**Categorie:** Toegang/Validatie\
**Bericht:** Kan geen velden maken/bijwerken: ToutApp__Tout_Last_Replied__c. Controleer de beveiligingsinstellingen van dit veld.
**Wat gebeurt er:** Gebruikers hebben geen schrijftoegang tot de aangepaste Tout-velden die nodig zijn om de meest recente transactie in het activiteitenlogbestand uit te voeren. Team heeft mogelijk pakket geïnstalleerd, maar heeft de juiste velden voor de gebruikers niet ingeschakeld.\
**De Stappen van het oplossen van problemen:** Salesforce Admin moet toegang tot de douanevelden verlenen OF het Meest recente logboek van de Activiteit uitzetten.

**Fout:** INVALID_GRANT\
**Categorie:** verificatie\
**Bericht:** ongeldige_subsidie: ip beperkt\
**Wat gebeurt er?** We proberen toegang te krijgen tot uw Salesforce, maar u hebt IP-beperkingen die ons beletten dit te doen.\
**De Stappen van het oplossen van problemen:** Uw Admin van Salesforce zal onze IPs moeten lijsten van gewenste personen. De gebruikers zouden zich moeten uitreiken aan Steun om de IP adressen te krijgen.

**Fout:** INVALID_TYPE\
**Categorie:** Toegang/Validatie\
**Bericht:** GemaaktDatum, (UITGEZOCHT identiteitskaart VAN Taken) VAN Lood WAAR E-mail=&#39;emailid&#39;^ERROR bij Rij:1:Kolom:53sObjecttype &quot;Lood&quot;wordt niet gesteund. Als u een aangepast object wilt gebruiken, moet u &#39;__c&#39; achter de naam van de entiteit plaatsen. Gelieve te verwijzen uw WSDL of beschrijf vraag naar de aangewezen namen
**Wat gebeurt er?** We proberen een objecttype van Salesforce te vragen waartoe de gebruiker geen toegang heeft. Dit heeft waarschijnlijk te maken met het feit dat de gebruiker niet de juiste toegang heeft tot het object Lead.\
**De Stappen van het oplossen van problemen:** Of verlenen Gelezen en Update toegang tot het voorwerp van de Lood in Salesforce, of zetten e-mailregistreren en het Meest Recente registreren van de Activiteit uit om verslagen te leiden.

**Fout:** QUERY_TIMEOUT\
**categorie:** periodiek\
**Bericht:** Uw queryverzoek is te lang uitgevoerd\
**Wat gebeurt er?** Zie hierboven.\
**Stappen voor probleemoplossing:dit moet worden verwerkt door de logica** Opnieuw proberen. Als het nog niet werkt, werk met uw Admin van Salesforce om een problematische trekker problemen op te lossen.

**Fout:** REQUEST_LIMIT_EXCEEDED\
**categorie:** periodiek\
**Bericht:**
1 - GelijktijdigePerOrgLongTxn-limiet overschreden\
2 - Limiet voor totale verzoeken overschreden\
3 - Gelijktijdig verzoek\
**Wat gebeurt er:**
1 - Gelijktijdige aanvraaglimiet is overschreden, waarschijnlijk als gevolg van inefficiënte triggercode.\
2 - Te veel integraties zetten de org voorbij het rolvenster van 24 uur.\
**Stappen voor het oplossen van problemen:**
1 - controleer bestaande trekkers op de beïnvloede voorwerpen. U kunt roll-uplogboekregistratie voor een of meer objecten uitschakelen.\
2 - Koop meer API-oproepen van Salesforce. U kunt roll-uplogboekregistratie voor een of meer objecten uitschakelen.

**Fout:** REQUIRED_FIELD_MISSING\
**Categorie:** Toegang/Validatie\
**Bericht:** Vereiste velden ontbreken:  `[Amount_Committed_Private_Capital__c]`
**Wat gebeurt er?** Dit gebeurt gewoonlijk voor het meest recente activiteitenlogboek. Er zijn aangepaste velden ingesteld die verplicht zijn, maar er staan lege waarden in. Dit kan gebeuren als de record is gemaakt met een lege waarde van het aangepaste veld en vervolgens verplicht is gesteld. Vereiste wordt afgedwongen wanneer we proberen de record bij te werken, ook al raken we het aangepaste veld niet aan.\
**Stappen voor het oplossen van problemen:** Werk manueel de waarden van de ontbrekende gebieden bij. U kunt het bericht vervolgens opnieuw proberen vanuit ToutApp.

**Fout:** SERVER_UNAVAILABLE\
**categorie:** periodiek\
**Bericht:** server te druk\
**Wat gebeurt er:** Prestatieprobleem met Salesforce, waarschijnlijk als gevolg van suboptimale triggers door de klant\
**Stappen voor probleemoplossing:dit moet worden verwerkt door de logica** Opnieuw proberen. Als het nog steeds niet werkt, werkt u samen met uw Salesforce Admin om een problematische trigger weg te nemen.

**Fout:** TXN_SECURITY_NO_ACCESS\
**Categorie:** Toegang/Validatie\
**Bericht:** de verrichting u vroeg wordt niet toegestaan toe te schrijven aan een veiligheidsbeleid in uw organisatie. Neem contact op met de beheerder.<br/>
**Wat gebeurt er?:** Er is een soort beveiligingsbeperking ingesteld - zie https://developer.salesforce.com/forums/?id=&quot;record-id&quot;\
**Stappen van het oplossen van problemen:** Bespreek met uw Admin van Salesforce en zie wat de specifieke beperking zou kunnen zijn.

**Fout:** UNABLE_TO_LOCK_ROW\
**categorie:** periodiek\
**Bericht:exclusieve toegang tot deze record of 1 records** kan niet worden verkregen: &quot;record-id&quot;\
**Wat gebeurt er?** Waarschijnlijk is er een trigger die meerdere pogingen tot toegang tot dezelfde record veroorzaakt, mogelijk in het geval van een groepse-mail.\
**Stappen voor probleemoplossing:dit moet worden verwerkt door de logica** Opnieuw proberen. Als het nog niet werkt, werk met uw Admin van Salesforce om een problematische trekker problemen op te lossen.

**Fout:** UNKNOWN_EXCEPTION, 
**categorie:** Overige\
**Bericht:** onbekende uitzondering opgetreden\
**Wat gebeurt er?:** Onverwerkte uitzondering in Salesforce.\
**Stappen voor het oplossen van problemen:** Bestel een geval met Salesforce en kopieer de numerieke waarden in het foutenbericht. Dit is Salesforce-code die een fout niet correct afhandelt.
