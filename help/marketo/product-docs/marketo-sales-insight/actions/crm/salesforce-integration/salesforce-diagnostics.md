---
description: Salesforce Diagnostics - Marketo Docs - Productdocumentatie
title: Salesforce Diagnostics
exl-id: c449f938-9615-47cb-b232-613ec29068a3
feature: Sales Insight Actions
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '1341'
ht-degree: 0%

---

# [!DNL Salesforce] Diagnostiek {#salesforce-diagnostics}

Een deel van onze [!DNL Salesforce] -integratie bestaat uit een [!DNL Salesforce] Diagnostische pagina in de webtoepassing. Deze pagina legt fouten van mislukte gegevensregistratie aan [!DNL Salesforce] vast. De fouten kunnen nuttig zijn, maar zijn niet altijd leesbaar. Als zodanig maken we een bedriegblad dat de foutmeldingen helpt uit te leggen.

## Toegangsdiagnose {#access-diagnostics}

1. Klik op het tandwielpictogram en kies **[!UICONTROL Settings]** .

   ![](assets/salesforce-diagnostics-1.png)

1. Klik onder [!UICONTROL Integrations] op **[!UICONTROL Diagnostics]** .

   ![](assets/salesforce-diagnostics-2.png)

## Fout tijdens uitnemen van blad {#error-cheat-sheet}

**Fout:** API_CURRENTLY_DISABLED\
**Categorie:** Toegang/Bevestiging\
**Bericht:** API is gehandicapt voor deze gebruiker\
**wat gebeurt:** de Gebruiker heeft geen API Toegang\
**Stappen van het Oplossen van problemen:** [!DNL Salesforce] Admin moet de gebruiker API Toegang verlenen.

**Fout:** AUTHENTICATION_FAILURE\
**Categorie:** Authentificatie\
**Bericht:** invalid_Grant: authentificatiefout\
**wat gebeurt:** Ontbroken Authentificatie\
**Stappen van het Oplossen van problemen:** maak van [!DNL Salesforce] los en verbind dan opnieuw.

**Fout:** CANNOT_INSERT_UPDATE_ACTIVATE_ENTITY\
**Categorie:** Toegang/Bevestiging\
**Bericht:** {&quot;errorCode&quot;:&quot;INVALID_SESSION_ID&quot;,&quot;bericht&quot;:&quot;Zitting verlopen of ongeldig&quot;}\
**wat gebeurt:**

1 - Trigger-code zorgt ervoor dat de update mislukt.\
2 - Gebruiker heeft geen schrijfmachtigingen op objectniveau voor het opgegeven object.

**Stappen van het oplossen van problemen:**

1 - Controleer de trigger die faalt.\
2 - Hiermee verleent u schrijftoegang aan de gebruiker voor het object OF schakelt u de functie uit die naar het object probeert te schrijven.

**Fout:** CANNOT_UPDATE_CONVERTED_LEAD\
**Categorie:** Andere\
**Bericht:** kan niet van verwijzingen voorzien omgezet lood\
**wat gebeurt:** wij proberen om aan een omgezette lood tijdens het Meest Recente Registreren van de Activiteit voor Contacten en Leads te registreren. Een paar van deze foto&#39;s werden ook gezien voor toonhoogte.\
**Stappen van het Oplossen van problemen:** te melden gelieve om het even welke instanties van dit aan ons [ ondersteuningsteam ](https://nation.marketo.com/t5/Support/ct-p/Support).

**Fout:** ENTITY_IS_LOCKED\
**Categorie:** Toegang/Bevestiging\
**Bericht:** de entiteit is gesloten voor het uitgeven\
**wat gebeurt:** het verslag is in een goedkeuringsproces waar het van om het even welke extra uitgeeft wordt gesloten tot het of door een persoon wordt goedgekeurd of ontkend die de goedkeuring bezit.\
**Stappen van het Oplossen van problemen:** zie hierboven.

**Fout:** EXPIRED_ACCESS
**Categorie:** Authentificatie
**Bericht:** invalid_Grant: verlopen toegang/verfrist teken
**wat gebeurt:** de toegang of verfrist teken is verlopen. De tekenen verlopen gebaseerd op [ zittingsmontages in  [!DNL Salesforce] ](https://salesforce.stackexchange.com/questions/10759/invalid-grant-expired-access-refresh-token-error-when-authenticating-access-via).
**Stappen van het Oplossen van problemen:** u zult moeten opnieuw voor authentiek verklaren. Koppel de [!DNL Salesforce] -verbinding los en maak opnieuw verbinding.

**Fout:** FAILED_WRITE\
**Categorie:** Onderbreking\
**Bericht:** eind van bereikt dossier\
**wat gebeurt:** De kwestie van Prestaties met [!DNL Salesforce], waarschijnlijk toe te schrijven aan sub-optimale trekkers op de klantenkant.\
**Stappen van het Oplossen van problemen:** probeer logica opnieuw zou dit moeten behandelen. Als het nog steeds niet werkt, werkt u samen met uw [!DNL Salesforce] -beheerder om een problematische trigger op te lossen.

**Fout:** FIELD_CUSTOM_VALIDATION_EXCEPTION
**Categorie:** Toegang/Bevestiging
**Bericht:** varieert van klant aan klant.
**wat gebeurt:** het ontbreken van een regel van de douanebevestiging voor het voorwerp.
**Stappen van het Oplossen van problemen:** controleer de regel van de douanebevestiging die deze fout veroorzaakt. Aangezien dit een aangepaste regel is, moet de fout eenmalig worden behandeld.

**Fout:** FIELD_FILTER_VALIDATION_EXCEPTION\
**Categorie:** Toegang/Bevestiging\
**Bericht:** de Waarde bestaat niet of past filtercriteria niet aan\
**wat gebeurt:** Bestaande slechte gegevens in [!DNL Salesforce] worden afgedwongen op update.\
**Stappen van het Oplossen van problemen:** zie hierboven.

**Fout:** FIELD_INTEGRITY_EXCEPTION\
**Categorie:** Toegang/Bevestiging\
**Bericht:** het bestaande land/gebied erkent niet de staatswaarde voor gebied: Staat/Provinciecode\
**wat gebeurt:** Bestaande slechte gegevens in [!DNL Salesforce] worden afgedwongen op update.\
**Stappen van het Oplossen van problemen:** zie hierboven.

**Fout:** INACTIVE_ORGANIZATION\
**Categorie:** Authentificatie\
**Bericht:** invalid_Grant: inactieve organisatie\
**wat gebeurt:** Uw [!DNL Salesforce] organisatie is niet meer actief.
**Stappen van het Oplossen van problemen:** maak dan los van [!DNL Salesforce] opnieuw aan.

**Fout:** INACTIVE_USER
**Categorie:** Authentificatie
**Bericht:** invalid_Grant: inactieve gebruiker
**wat gebeurt:** de [!DNL Salesforce] gebruiker is niet meer actief
**Stappen van het Oplossen van problemen:** maak dan los van [!DNL Salesforce] opnieuw aan.

**Fout:** INSERT_UPDATE_DELETE_NOT_ALLOWED_DURING_MAINTENANCE\
**Categorie:** Onderbreking\
**Bericht:** (geen extra bericht)\
**wat gebeurt:** [!DNL Salesforce] instantie is op onderhoudswijze.\
**Stappen van het Oplossen van problemen:** wacht tot het systeemonderhoud dan opnieuw probeert registreren wordt gedaan.

**Fout:** INSUFFICIENT_ACCESS_ON_CROSS_REFERENCE_ENTITY
**Categorie:** Toegang/Bevestiging
**Bericht:** ontoereikende toegangsrechten op objecten identiteitskaart
**wat gebeurt:** Geen toegang tot het ouderverslag voor een taak.
**Stappen van het Oplossen van problemen:** zie hierboven.

**Fout:** ONVOLDOENDE_ACCESS_OR_READONLY\
**Categorie:** Toegang/Bevestiging
**Bericht:** ontoereikende toegangsrechten op objecten identiteitskaart
**wat gebeurt:** het meest Recente logboek van de Activiteit kan het specifieke verslag niet uitgeven omdat de gebruiker geen schrijven-aan toegang heeft.\
**Stappen van het Oplossen van problemen:** verstrek de gebruikerstoegang in [!DNL Salesforce] OF maak het Meest recente registreren van de Activiteit voor dat voorwerp voor die gebruiker onbruikbaar.

**Fout:** INVALID_FIELD\
**Categorie:** Onderbreking\
**Bericht:** Net::ReadTimeout\
**wat gebeurt:** Het verzoek is timing uit. Dit is waarschijnlijk het gevolg van te veel trage transacties.\
**Stappen van het Oplossen van problemen:** Herzie bestaande aanpassingen voor potentiële schuldigen aan de latentiekwesties en/of maak het Meest recente registreren van de Activiteit voor één of alle voorwerpen onbruikbaar om de lading te verminderen.

**Fout:** INVALID_FIELD_FOR_INSERT_UPDATE\
**Categorie:** Toegang/Bevestiging\
**Bericht:** Onbekwaam om gebieden tot stand te brengen/bij te werken: MSE_Replied__c. Controleer de beveiligingsinstellingen van dit veld.
**wat gebeurt:** de gebruikers hebben geen toegang tot de de douanegebieden van de Acties van Insight van de Verkoop nodig om de Recentste transactie van het Activiteitenlogboek uit te voeren. Team heeft mogelijk pakket geïnstalleerd, maar heeft de juiste velden voor de gebruikers niet ingeschakeld.\
**Stappen van het Oplossen van problemen:** [!DNL Salesforce] Admin moet toegang tot de douanegebieden verlenen OF het Meest recente logboek van de Activiteit uitzetten.

**Fout:** INVALID_GRANT\
**Categorie:** Authentificatie\
**Bericht:** invalid_Grant: ip beperkt\
**wat gebeurt:** wij proberen om tot uw [!DNL Salesforce] toegang te hebben, maar u hebt op zijn plaats IP Beperkingen die ons verhinderen dit te doen.\
**Stappen van het Oplossen van problemen:** Uw [!DNL Salesforce] Admin zal onze IPs moeten lijsten van gewenste personen. De gebruikers zouden zich moeten uitreiken aan Steun om de IP adressen te krijgen.

**Fout:** INVALID_TYPE\
**Categorie:** Toegang/Bevestiging\
**Bericht:** CreatedDate, (UITGEZOCHT identiteitskaart VAN Taken) VAN Lood WAAR Email=&#39;emailid&#39;^ERROR bij `Row:1:Column:53sObject` het type &quot;Lood&quot;niet wordt gesteund. Als u een aangepast object wilt gebruiken, moet u &#39;__c&#39; achter de naam van de entiteit plaatsen. Gelieve te verwijzen uw WSDL of beschrijf vraag naar de aangewezen namen
**wat gebeurt:** wij proberen om een objecten type van Salesforce te vragen dat de gebruiker geen toegang heeft tot. Dit heeft waarschijnlijk te maken met het feit dat de gebruiker niet de juiste toegang heeft tot het object Lead.\
**Stappen van het Oplossen van problemen:** of verleent Gelezen en Update toegang tot het voorwerp van het Lood in Salesforce, of zet e-mailregistreren en het Meest Recente logboek van de Activiteit uit om verslagen te leiden.

**Fout:** QUERY_TIMEOUT\
**Categorie:** Onderbreking\
**Bericht:** Uw vraagverzoek liep te lang\
**wat gebeurt:** zie hierboven.\
**Stappen van het Oplossen van problemen:** probeer logica opnieuw zou dit moeten behandelen. Als het nog steeds niet werkt, werkt u samen met uw [!DNL Salesforce] -beheerder om een problematische trigger op te lossen.

**Fout:** REQUEST_LIMIT_EXCEEDED\
**Categorie:** Onderbreking\
**Bericht:**
1 - GelijktijdigePerOrgLongTxn-limiet overschreden\
2 - Limiet voor totale verzoeken overschreden\
3 - Gelijktijdig verzoek\
**wat gebeurt:**
1 - Gelijktijdige aanvraaglimiet overschreden, waarschijnlijk als gevolg van inefficiënte triggercode.\
2 - Te veel integraties zetten de org voorbij het rolvenster van 24 uur.\
**Stappen van het oplossen van problemen:**
1 - Controleer de bestaande triggers voor de desbetreffende objecten. U kunt roll-uplogboekregistratie voor een of meer objecten uitschakelen.\
2 - Koop meer API-aanroepen vanuit [!DNL Salesforce] . U kunt roll-uplogboekregistratie voor een of meer objecten uitschakelen.

**Fout:** REQUIRED_FIELD_MISSING\
**Categorie:** Toegang/Bevestiging\
**Bericht:** Vereiste gebieden ontbreken: `[Amount_Committed_Private_Capital__c]`
**wat gebeurt:** dit gebeurt over het algemeen voor het Meest Recente registreren van de Activiteit. Er zijn aangepaste velden ingesteld die verplicht zijn, maar er staan lege waarden in. Dit kan gebeuren als de record is gemaakt met een lege waarde van het aangepaste veld en vervolgens verplicht is gesteld. Vereiste wordt afgedwongen wanneer we proberen de record bij te werken, ook al raken we het aangepaste veld niet aan.\
**Stappen van het Oplossen van problemen:** werk manueel de waarden van de ontbrekende gebieden bij. Je kunt het bericht vervolgens opnieuw proberen via Handelingen van Verkoopmanager Insight.

**Fout:** SERVER_UNAVAILABLE\
**Categorie:** Onderbreking\
**Bericht:** server aan bezet\
**wat gebeurt:** De kwestie van Prestaties met [!DNL Salesforce], waarschijnlijk toe te schrijven aan sub-optimale trekkers door de klant\
**Stappen van het Oplossen van problemen:** probeer logica opnieuw zou dit moeten behandelen. Als het nog steeds niet werkt, kunt u samen met uw [!DNL Salesforce] Admin een problematische trigger oplossen.

**Fout:** TXN_SECURITY_NO_ACCESS\
**Categorie:** Toegang/Bevestiging\
**Bericht:** de verrichting u vroeg wordt niet toegestaan toe te schrijven aan een veiligheidsbeleid in uw organisatie. Neem contact op met de beheerder.
**wat gebeurt:** Één of andere soort veiligheidsbeperking is opstelling - zie https://developer.salesforce.com/forums/?id=&quot;verslagidentiteitskaart&quot;\
**Stappen van het Oplossen van problemen:** Bespreek aan uw [!DNL Salesforce] Admin en zie wat de specifieke beperking zou kunnen zijn.

**Fout:** UNABLE_TO_LOCK_ROW\
**Categorie:** Onderbreking\
**Bericht:** kan exclusieve toegang tot dit verslag of 1 verslagen niet verkrijgen: &quot;verslagidentiteitskaart&quot;\
**wat gebeurt:** Waarschijnlijk is er een trekker die veelvoudige pogingen veroorzaakt om tot het zelfde verslag, misschien in het geval van een groep e-mail toegang te hebben.\
**Stappen van het Oplossen van problemen:** probeer logica opnieuw zou dit moeten behandelen. Als het nog steeds niet werkt, werkt u samen met uw [!DNL Salesforce] -beheerder om een problematische trigger op te lossen.

**Fout:** UNKNOWN_EXCEPTION
**Categorie:** Andere\
**Bericht:** Onbekende uitzondering voorkwam\
**wat gebeurt:** Unhandled uitzondering in [!DNL Salesforce].\
**Stappen van het Oplossen van problemen:** Dossier een geval met [!DNL Salesforce] en kopieer de numerieke waarden in het foutenbericht. Dit is [!DNL Salesforce] -code die een fout niet correct verwerkt.
