---
description: Salesforce Diagnostics - Marketo Docs - Productdocumentatie
title: Salesforce Diagnostics
exl-id: c449f938-9615-47cb-b232-613ec29068a3
feature: Sales Insight Actions
source-git-commit: 9384d72b335a4b975b190816ea999ad067fddeda
workflow-type: tm+mt
source-wordcount: '1374'
ht-degree: 0%

---

# Salesforce Diagnostics {#salesforce-diagnostics}

Een onderdeel van onze Salesforce-integratie is de pagina Salesforce Diagnostic in de webtoepassing. Deze pagina legt fouten van ontbroken gegevensregistreren aan Salesforce vast. De fouten kunnen nuttig zijn, maar zijn niet altijd leesbaar. Als zodanig maken we een bedriegblad dat de foutmeldingen helpt uit te leggen.

## Toegangsdiagnose {#access-diagnostics}

1. Klik op het tandwielpictogram en kies **Instellingen**.

   ![](assets/salesforce-diagnostics-1.png)

1. Klik onder Integraties op **Diagnostiek**.

   ![](assets/salesforce-diagnostics-2.png)

## Fout tijdens uitnemen van blad {#error-cheat-sheet}

**Fout:** API_CURRENTLY_DISABLED\
**Categorie:** Toegang/validatie\
**Bericht:** API is uitgeschakeld voor deze gebruiker\
**Wat gebeurt er?** Gebruiker heeft geen API-toegang\
**Stappen voor probleemoplossing:** Salesforce Admin moet de gebruiker API Toegang verlenen.

**Fout:** AUTHENTICATION_FAILURE\
**Categorie:** Verificatie\
**Bericht:** invalid_Grant: verificatiefout\
**Wat gebeurt er?** Verificatie mislukt\
**Stappen voor probleemoplossing:** Maak de verbinding met Salesforce los en maak vervolgens opnieuw verbinding.

**Fout:** CANNOT_INSERT_UPDATE_ACTIVATE_ENTITY\
**Categorie:** Toegang/validatie\
**Bericht:** {&quot;errorCode&quot;:&quot;INVALID_SESSION_ID&quot;,&quot;message&quot;:&quot;Session expired or invalid&quot;}\
**Wat gebeurt er?**

1 - Trigger-code zorgt ervoor dat de update mislukt.\
2 - Gebruiker heeft geen schrijfmachtigingen op objectniveau voor het opgegeven object.

**Stappen voor probleemoplossing:**

1 - Controleer de trigger die faalt.\
2 - Hiermee verleent u schrijftoegang aan de gebruiker voor het object OF schakelt u de functie uit die naar het object probeert te schrijven.

**Fout:** CANNOT_UPDATE_CONVERTED_LEAD\
**Categorie:** Overige\
**Bericht:** kan niet verwijzen naar omgezette lead\
**Wat gebeurt er?** We proberen ons aan te melden bij een geconverteerde lead tijdens de meest recente activiteitenregistratie voor contactpersonen en leads. Een paar van deze foto&#39;s werden ook gezien voor toonhoogte.\
**Stappen voor probleemoplossing:** Meld eventuele gevallen hiervan aan onze [ondersteuningsteam](https://nation.marketo.com/t5/Support/ct-p/Support).

**Fout:** ENTITY_IS_LOCKED\
**Categorie:** Toegang/validatie\
**Bericht:** de entiteit is vergrendeld voor bewerking\
**Wat gebeurt er?** Het dossier is in een goedkeuringsproces waar het van om het even welke extra uitgeeft wordt gesloten tot het of door een persoon wordt goedgekeurd of wordt ontkend die de goedkeuring bezit.\
**Stappen voor probleemoplossing:** Zie hierboven.

**Fout:** EXPIRED_ACCESS
**Categorie:** Verificatie
**Bericht:** invalid_Grant: verlopen toegangs-/vernieuwingstoken
**Wat gebeurt er?** De toegangs- of vernieuwingstoken is verlopen. Tokens verlopen op basis van [sessie-instellingen in Salesforce](https://salesforce.stackexchange.com/questions/10759/invalid-grant-expired-access-refresh-token-error-when-authenticating-access-via).
**Stappen voor probleemoplossing:** U moet opnieuw verifiëren. Koppel de Salesforce-verbinding los en maak opnieuw verbinding.

**Fout:** FAILED_WRITE\
**Categorie:** Intermitterend\
**Bericht:** bestandseinde bereikt\
**Wat gebeurt er?** Prestatieproblemen met Salesforce, waarschijnlijk als gevolg van suboptimale triggers aan de kant van de klant.\
**Stappen voor probleemoplossing:** Dit moet worden verwerkt in logica voor opnieuw proberen. Als het nog niet werkt, werk met uw beheerder Salesforce om een problematische trekker problemen op te lossen.

**Fout:** FIELD_CUSTOM_VALIDATION_EXCEPTION
**Categorie:** Toegang/validatie
**Bericht:** Dit varieert van klant tot klant.
**Wat gebeurt er?** Aangepaste validatieregel voor het object ontbreekt.
**Stappen voor probleemoplossing:** Controleer de aangepaste validatieregel die deze fout veroorzaakt. Aangezien dit een aangepaste regel is, moet de fout eenmalig worden behandeld.

**Fout:** FIELD_FILTER_VALIDATION_EXCEPTION\
**Categorie:** Toegang/validatie\
**Bericht:** Waarde bestaat niet of komt niet overeen met filtercriteria\
**Wat gebeurt er?** Bestaande onjuiste gegevens in Salesforce die worden afgedwongen bij update.\
**Stappen voor probleemoplossing:** Zie hierboven.

**Fout:** FIELD_INTEGRITY_EXCEPTION\
**Categorie:** Toegang/validatie\
**Bericht:** Het bestaande land/gebied herkent de waarde van de staat voor veld: Staat/Provinciecode\
**Wat gebeurt er?** Bestaande onjuiste gegevens in Salesforce die worden afgedwongen bij update.\
**Stappen voor probleemoplossing:** Zie hierboven.

**Fout:** INACTIVE_ORGANIZATION\
**Categorie:** Verificatie\
**Bericht:** invalid_Grant: inactieve organisatie\
**Wat gebeurt er?** Uw Salesforce-organisatie is niet meer actief.
**Stappen voor probleemoplossing:** Verbreek de verbinding met Salesforce.

**Fout:** INACTIVE_USER
**Categorie:** Verificatie
**Bericht:** invalid_Grant: inactieve gebruiker
**Wat gebeurt er?** De Salesforce-gebruiker is niet meer actief
**Stappen voor probleemoplossing:** Verbreek de verbinding met Salesforce.

**Fout:** INSERT_UPDATE_DELETE_NOT_ALLOWED_DURING_MAINTENANCE\
**Categorie:** Intermitterend\
**Bericht:** (geen extra bericht)\
**Wat gebeurt er?** De Salesforce-instantie bevindt zich in de onderhoudsmodus.\
**Stappen voor probleemoplossing:** Wacht tot het systeemonderhoud is voltooid en probeer het opnieuw.

**Fout:** INSUFFICIENT_ACCESS_ON_CROSS_REFERENCE_ENTITY
**Categorie:** Toegang/validatie
**Bericht:** onvoldoende toegangsrechten voor object-id
**Wat gebeurt er?** Geen toegang tot de bovenliggende record voor een taak.
**Stappen voor probleemoplossing:** Zie hierboven.

**Fout:** INSUFFICIENT_ACCESS_OR_READONLY\
**Categorie:** Toegang/validatie
**Bericht:** onvoldoende toegangsrechten voor object-id
**Wat gebeurt er?** Recentste logboekregistratie van activiteiten kan de specifieke record niet bewerken omdat de gebruiker geen schrijftoegang heeft.\
**Stappen voor probleemoplossing:** Verleen de gebruikerstoegang in Salesforce OF maakt het Meest recente registreren van de Activiteit voor dat voorwerp voor die gebruiker onbruikbaar.

**Fout:** INVALID_FIELD\
**Categorie:** Intermitterend\
**Bericht:** Net::ReadTimeout\
**Wat gebeurt er?** Verzoek is timing out. Dit is waarschijnlijk het gevolg van te veel trage transacties.\
**Stappen voor probleemoplossing:** Bekijk bestaande aanpassingen voor mogelijke oorzaken van latentieproblemen en/of schakel het logboekbestand met de meest recente activiteit voor een of alle objecten uit om de belasting te verminderen.

**Fout:** INVALID_FIELD_FOR_INSERT_UPDATE\
**Categorie:** Toegang/validatie\
**Bericht:** Kan geen velden maken/bijwerken: MSE_Replied__c. Controleer de beveiligingsinstellingen van dit veld.
**Wat gebeurt er?** De gebruikers hebben geen schrijftoegang tot de de douanegebieden van de Acties van het Inzicht van de Verkoop nodig om de Recentste transactie van het Activiteitenlogboek uit te voeren. Team heeft mogelijk pakket geïnstalleerd, maar heeft de juiste velden voor de gebruikers niet ingeschakeld.\
**Stappen voor probleemoplossing:** Salesforce Admin moet toegang tot de douanevelden verlenen OF het Meest recente registreren van de Activiteit uitzetten.

**Fout:** INVALID_GRANT\
**Categorie:** Verificatie\
**Bericht:** invalid_Grant: ip restricted\
**Wat gebeurt er?** Wij proberen om tot uw Salesforce toegang te hebben, maar u hebt IP Beperkingen op zijn plaats die ons verhinderen dit te doen.\
**Stappen voor probleemoplossing:** Uw Admin van Salesforce zal onze IPs moeten lijsten van gewenste personen. De gebruikers zouden zich moeten uitreiken aan Steun om de IP adressen te krijgen.

**Fout:** INVALID_TYPE\
**Categorie:** Toegang/validatie\
**Bericht:** Gemaakt op, (SELECTEER Id UIT Taken) VAN regel WAAR E-mail=&#39;emailid&#39;^ERROR op `Row:1:Column:53sObject` Het type Lead wordt niet ondersteund. Als u een aangepast object wilt gebruiken, moet u &#39;__c&#39; achter de naam van de entiteit plaatsen. Gelieve te verwijzen uw WSDL of beschrijf vraag naar de aangewezen namen
**Wat gebeurt er?** Wij proberen om een objecten type van Salesforce te vragen dat de gebruiker geen toegang tot heeft. Dit heeft waarschijnlijk te maken met het feit dat de gebruiker niet de juiste toegang heeft tot het object Lead.\
**Stappen voor probleemoplossing:** Of verleent Gelezen en Update toegang tot het voorwerp van de Lood in Salesforce, of zet e-mailregistreren en het Meest Recente registreren van de Activiteit uit om verslagen te leiden.

**Fout:** QUERY_TIMEOUT\
**Categorie:** Intermitterend\
**Bericht:** Uw queryverzoek is te lang uitgevoerd\
**Wat gebeurt er?** Zie hierboven.\
**Stappen voor probleemoplossing:** Dit moet worden verwerkt in logica voor opnieuw proberen. Als het nog niet werkt, werk met uw Admin van Salesforce om een problematische trekker problemen op te lossen.

**Fout:** REQUEST_LIMIT_EXCEEDED\
**Categorie:** Intermitterend\
**Bericht:**
1 - GelijktijdigePerOrgLongTxn-limiet overschreden\
2 - Limiet voor totale verzoeken overschreden\
3 - Gelijktijdig verzoek\
**Wat gebeurt er?**
1 - Gelijktijdige aanvraaglimiet overschreden, waarschijnlijk als gevolg van inefficiënte triggercode.\
2 - Te veel integraties zetten de org voorbij het rolvenster van 24 uur.\
**Stappen voor probleemoplossing:**
1 - Controleer de bestaande triggers voor de desbetreffende objecten. U kunt roll-uplogboekregistratie voor een of meer objecten uitschakelen.\
2 - Koop meer API-oproepen van Salesforce. U kunt roll-uplogboekregistratie voor een of meer objecten uitschakelen.

**Fout:** REQUIRED_FIELD_MISSING\
**Categorie:** Toegang/validatie\
**Bericht:** Vereiste velden ontbreken: `[Amount_Committed_Private_Capital__c]`
**Wat gebeurt er?** Dit gebeurt over het algemeen voor het Meest Recente registreren van de Activiteit. Er zijn aangepaste velden ingesteld die verplicht zijn, maar er staan lege waarden in. Dit kan gebeuren als de record is gemaakt met een lege waarde van het aangepaste veld en vervolgens verplicht is gesteld. Vereiste wordt afgedwongen wanneer we proberen de record bij te werken, ook al raken we het aangepaste veld niet aan.\
**Stappen voor probleemoplossing:** De waarden van de ontbrekende velden handmatig bijwerken. U kunt het bericht dan van de Acties van het Inzicht van de Verkoop opnieuw proberen.

**Fout:** SERVER_UNAVAILABLE\
**Categorie:** Intermitterend\
**Bericht:** server is bezet\
**Wat gebeurt er?** Prestatieprobleem met Salesforce, waarschijnlijk als gevolg van suboptimale triggers door de klant\
**Stappen voor probleemoplossing:** Dit moet worden verwerkt in logica voor opnieuw proberen. Als het nog steeds niet werkt, werkt u samen met uw Salesforce Admin om een problematische trigger weg te nemen.

**Fout:** TXN_SECURITY_NO_ACCESS\
**Categorie:** Toegang/validatie\
**Bericht:** De gewenste bewerking is niet toegestaan vanwege een beveiligingsbeleid in uw organisatie. Neem contact op met de beheerder.
**Wat gebeurt er?** Er is een soort beveiligingsbeperking ingesteld - zie https://developer.salesforce.com/forums/?id=&quot;record-id&quot;\
**Stappen voor probleemoplossing:** Bespreek met uw Salesforce Admin wat de specifieke beperking zou kunnen zijn.

**Fout:** UNABLE_TO_LOCK_ROW\
**Categorie:** Intermitterend\
**Bericht:** kan geen exclusieve toegang verkrijgen tot deze record of 1 records: &quot;record-id&quot;\
**Wat gebeurt er?** Waarschijnlijk is er een trigger die meerdere pogingen veroorzaakt om toegang te krijgen tot dezelfde record, mogelijk in het geval van een groepse-e-mail.\
**Stappen voor probleemoplossing:** Dit moet worden verwerkt in logica voor opnieuw proberen. Als het nog niet werkt, werk met uw Admin van Salesforce om een problematische trekker problemen op te lossen.

**Fout:** UNKNOWN_EXCEPTION
**Categorie:** Overige\
**Bericht:** Onbekende uitzondering opgetreden\
**Wat gebeurt er?** Onverwerkte uitzondering in Salesforce.\
**Stappen voor probleemoplossing:** Bestel een case met Salesforce en kopieer de numerieke waarden in het foutbericht. Dit is Salesforce-code die een fout niet correct afhandelt.
