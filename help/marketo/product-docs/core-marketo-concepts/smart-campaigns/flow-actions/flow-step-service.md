---
description: Flow Step Service - Marketo Docs - Productdocumentatie
title: Stroom Step Service
exl-id: 81367562-8b27-4ec5-8a9b-b02083a2e999
feature: Smart Campaigns
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '1224'
ht-degree: 0%

---

# Stroom Step Service {#flow-step-service}

De Zelfbediening Stappen van de Stroom is een kader en reeks eigenschappen voor creatie, het publiceren, en het integreren van de Webdiensten in de Slimme Campagnes van Adobe Marketo Engage. Deze handleiding is bedoeld voor eindgebruikers van Marketo Engage die services willen installeren en gebruiken die al zijn gemaakt en gepubliceerd. Voor informatie bij het schrijven van en het publiceren van uw eigen dienst, gelieve te verwijzen naar de [[!DNL GitHub]  bewaarplaats voor de Interface van Service Provider &#x200B;](https://github.com/adobe/Marketo-SSFS-Service-Provider-Interface){target="_blank"}. Een proef-van-Concept implementatie van de Lijst van de Opzoeklijst kan [&#x200B; hier &#x200B;](https://github.com/adobe/mkto-flow-lookup){target="_blank"} worden gevonden.

## Onboarding en Managing Services {#onboarding-and-managing-services}

Voor het installeren van een aangepaste flowstap zijn beheerdersmachtigingen in Marketo vereist. Behalve de installatie-URL kunnen alle andere aspecten van een service worden bewerkt nadat de eerste instapprocedure is voltooid. Hieronder wordt u geboord in het scherm met servicegegevens van het raster Serviceproviders.

## Installatie-URL {#installation-url}

Als u wilt beginnen met de installatie, moet u eerst de URL opvragen van het OpenAPI-document dat uw service definieert. Dit moet uw servicebureau kunnen geven. De URL eindigt gewoonlijk in `/openapi.json` . Volledige URL&#39;s zien er ongeveer als volgt uit: `https://www.example.com/OpenAPI.json` . Wanneer u deze URL hebt, gaat u naar het menu [!UICONTROL Service Providers] in de sectie [!UICONTROL Admin] .

Klik op **[!UICONTROL Next]** om naar de sectie Servicereferenties invoeren te gaan.

![](assets/flow-step-service-1.png)

## Voer servicekredieten in {#enter-service-credentials}

Marketo moet over geldige API-referenties beschikken om toegang te krijgen tot de geïnstalleerde service. Deze geloofsbrieven zouden aan u door uw dienstverlener moeten worden verstrekt. De diensten hebben drie verschillende authentificatieopties, zodat kunt u één van drie verschillende herinneringen voor geloofsbrieven zien: **API Sleutel** die slechts één inputgebied heeft, **BasisAuthentificatie** die een gebruikersbenaming en wachtwoord vereist en ook een gebied genoemd Realm, en **OAuth2** gebruikend de _Toestemming van de Cliënt_ toelage vereist, die identiteitskaart van a _Cliënt 9&rbrace; en en en en vereist_ Geheim van de Cliënt _._

Wanneer u uw geloofsbrieven bewaart, zal Marketo proberen om het statuseindpunt van de dienst te roepen om te verifiëren dat zij geldig zijn. Als de opgegeven referenties ongeldig zijn, wordt een fout weergegeven die dit aangeeft.

>[!CAUTION]
>
>Als een Serviceleverancier wordt gemaakt en verwijderd, kunt u de serviceleverancier, API, trigger of filternaam niet opnieuw gebruiken.

## Handleiding aan boord (optioneel) {#onboarding-guide}

Sommige serviceproviders nemen een optionele stap voor de on-boarding Guide. Deze stap omvat alle aanvullende instructies voor het voltooien van de instapservice die specifiek zijn voor die service.

## Veldtoewijzing {#field-mapping}

Om gegevens van een bepaald loodveld te ontvangen of te retourneren, moet dat veld worden toegewezen. Terwijl de afbeelding een vereiste stap tijdens het instappen is, kunt u altijd terugkeren om de afbeeldingen later te veranderen. Er zijn twee soorten afbeeldingen die in afzonderlijke schermen worden gevormd: **Uitgaande Gebieden**, die naar de dienst worden verzonden wanneer Marketo de stroomstap aanhaalt, en **Binnenkomende Gebieden** die gebieden zijn die gegevens van de dienst kunnen ontvangen wanneer het gegevens aan Marketo terugkeert.

>[!NOTE]
>
>Door een uitgaand gebied in kaart te brengen, geeft u Marketo toestemming om gegevens van dat gebied over te brengen met betrekking tot lood die door de bijbehorende dienst worden verwerkt. Zorg ervoor dat u over de juiste wettelijke status en bevoegdheid beschikt om deze gegevens naar uw serviceprovider te verzenden, aangezien deze velden mogelijk informatie bevatten die persoonlijk kan worden geïdentificeerd en die valt onder de wetgeving inzake gegevensbescherming, bescherming en huur.

Optionele veldtoewijzingen kunnen worden uitgeschakeld zonder onderbreking van de service, maar vereiste toewijzingen kunnen niet volledig worden verwijderd of gedeactiveerd.

## Servicedesgestuurde afbeeldingen {#service-driven-mappings}

De diensten die een vaste reeks input en output, als een stap van de gebeurtenisregistratie hebben, gebruiken **dienst-Gedreven Toewijzingen**. Voor dit type van afbeelding, zal de dienstverlener zowel een datatype als een wenk in de vorm van een API naam verstrekken. Als de hint overeenkomt met de API-naam van een bestaand lead-veld, wordt dat veld automatisch ingevuld in de toewijzingssectie. Voor velden zonder overeenkomende hint moet u de toewijzing handmatig invullen in de lijst met velden met het overeenkomende gegevenstype. Toewijzingen die vereist zijn, moeten worden ingevuld om het instappen te voltooien.

![](assets/flow-step-service-2.png)

## Door gebruiker gestuurde toewijzingen {#user-driven-mappings}

De diensten die geen vaste reeks input en output, als datum-formatterende dienst hebben, gebruiken **Gebruiker-Gedreven Toewijzingen**. Dit betekent dat elk inkomend en uitgaand gebied door Admin moet worden gevormd.

![](assets/flow-step-service-3.png)

## Uitgaande velden {#outgoing-fields}

De uitgaande gebieden zijn die die naar de Dienst van de Stap van de Stroom worden verzonden wanneer die stroomstap in een slimme campagne wordt gebruikt.

## Binnenkomende velden {#incoming-fields}

De inkomende gebieden zijn die die de Dienst van de Stap van de Stroom wordt toegestaan om gegevens te schrijven aan.

## Configuratieopties (optioneel) {#configuration-options}

Sommige services hebben optionele of vereiste globale configuratieopties. Als er opties vereist zijn, moet er een waarde worden ingesteld voor alle vereiste opties voordat u het document opslaat of invult. Parameters waarvan de namen cursief zijn, worden als kopteksten verzonden naar de aangeroepen service.

![](assets/flow-step-service-4.png)

## Een service intrekken {#retiring-a-service}

Om overgangen naar nieuwe of alternatieve versies van de dienst te vergemakkelijken, zonder actief gebruik te verstoren, kunnen de diensten van het menu van Dienstverleners worden gepensioneerd. **terugkerend de Dienst** verwijdert de overeenkomstige stroomstap uit het Slimme Pallet van de Stroom van de Campagne, zodat geen nieuwe gebruik van het kan worden gecreeerd. In de meeste gevallen, zou u een vervangingsdienst klaar moeten hebben om bestaande te vervangen wanneer u verkiest om de dienst met pensioen te gaan.

## Servicedespring {#service-deprecation}

Soms zullen de dienstverleners de diensten van de stroomstap als normaal deel van de softwarelevenscyclus moeten verwerpen. Wanneer een dienstverlener dit aankondigt, zullen de Datum en het Bericht van de Verdringing in de het netmening van Dienstverleners worden bevolkt. Als u een service blijft gebruiken die is afgekeurd, kan dit leiden tot een onderbreking van de service als deze niet meer op de verwachte manier reageert of als u geen aanvragen meer accepteert van Marketo Smart Campaigns, dus moet u zorgvuldig letten op alle meldingen over servicedruk die u ontvangt en de juiste stappen nemen om alle stappen van de service die nog in gebruik zijn, af te schaffen of te vervangen.

## Stappen voor Derde en Aangepaste Stroom gebruiken {#using-third-party-and-custom-flow-steps}

Geïnstalleerde stappen in de stroom kunnen grotendeels op dezelfde manier worden gebruikt als standaardstappen in de stroom. Alle die stroomparameters door de dienst worden bepaald worden voorgesteld aan eind - gebruikers.

## Picklisten vernieuwen {#refreshing-picklists}

Marketo vernieuwt elke avond keuzemogelijkheden voor services, maar soms hebt u nieuwe mogelijkheden nodig, zoals het maken van campagnes. U kunt deze eenvoudig vernieuwen vanuit elke gewenste stroomstap met de knop Vernieuwen of door naar het menu [!UICONTROL Admin] > [!UICONTROL Service Providers] te gaan en op [!UICONTROL Refresh Picklist] te klikken zodra u de service hebt geselecteerd.

## Binnenkomende velden controleren {#checking-incoming-fields}

U kunt controleren welke binnenkomende gebieden voor een bepaalde stroomstap door over zijn tooltip pictogram worden gevormd. Dit is nuttig om te bepalen welke gebieden kunnen veranderen wanneer een lood door het stroomt, zodat kunt u keuzen in verdere stappen vormen gebruikend die gebieden.

![](assets/flow-step-service-5.png)

## Binnenkomende velden en wijzigingen in gegevenswaarde {#incoming-fields-and-data-value-changes}

In tegenstelling tot de meeste andere stroomstappen, kunnen degenen die met het kader SSFS worden uitgevoerd gegevens terug naar loodgebieden schrijven die door admin in kaart worden gebracht en die veranderingen registreren als de activiteiten van de Verandering van de Waarde van Gegevens.  Wanneer een stroomstap gegevens op deze manier schrijft, zullen al die veranderingen worden voltooid alvorens de Slimme Campagne zich op om het even welke verdere stappen beweegt, zodat om het even welke geschreven gegevens op in verdere keuzen van de stroomstap kunnen worden vertrouwd.

## Servicelogbestanden en statistieken {#service-logs-and-statistics}

Elke Dienst van de Stap van de Stroom heeft verscheidene types van registreren verbonden aan het helpen gezondheid controleren, en om het even welke problemen oplossen met betrekking tot de integratie.

## Servicestatistieken {#service-statistics}

Het logboek van de statistiek van de Dienst aggregeert de resultaten van aanroepen en callbacks voor elke dienst. Zij worden gegroepeerd door tijd, niveau (brok of verslag), en code, en verstrekken tellingen en het meest recente logboekbericht voor elke ontvangen code. Dit dashboard is vooral bedoeld om de gezondheid van de dienst te controleren.
