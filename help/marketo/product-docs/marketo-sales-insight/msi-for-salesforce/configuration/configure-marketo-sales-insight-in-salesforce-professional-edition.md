---
unique-page-id: 3571743
description: Leer hoe u Marketo Sales Insight configureert in Salesforce Professional Edition.
title: Marketo Sales Insight configureren in Salesforce Professional Edition
exl-id: fae63560-0bb3-46a9-94a3-cc27c1aa363e
feature: Marketo Sales Insights
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '672'
ht-degree: 1%

---

# [!DNL Marketo Sales Insight] configureren in [!DNL Salesforce] Professional Edition {#configure-marketo-sales-insight-in-salesforce-professional-edition}

Configureer Marketo Sales Insight in Salesforce Professional Edition door de volgende stappen uit te voeren.

>[!PREREQUISITES]
>
>* Installeer Marketo in uw [!DNL Salesforce] Professional Edition.
>
>* [ installeer  [!DNL Marketo Sales Insight]  Pakket in  [!DNL Salesforce]  AppExchange ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"}

>[!NOTE]
>
>{de toestemmingen van 0} Admin worden vereist.****

## Sales Insight in Marketo Engage configureren {#configure-sales-insight-in-marketo}

1. Open een nieuw browservenster om de Marketo Sales Insight-gegevens van uw Marketo-account op te halen.

1. Ga naar het **[!UICONTROL Admin]** -gebied en selecteer **[!UICONTROL Sales Insight]** .

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-1-1.png)

1. Klik op **[!UICONTROL Edit API Configuration]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-2-1.png)

1. Voer naar keuze een API-beveiligingssleutel in en klik op **[!UICONTROL Save]** . Gebruik geen en-teken (`&`) in de geheime API-sleutel.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-3-1.png)

   >[!NOTE]
   >
   >De geheime sleutel van uw API is als een wachtwoord voor uw organisatie en zou veilig moeten zijn.

1. Klik op **[!UICONTROL View]** in het deelvenster _[!UICONTROL Rest API Configuration]_om de referenties te vullen.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-4-1.png)

1. Klik op **[!UICONTROL OK]** wanneer er een bevestigingsvenster wordt weergegeven.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-5-1.png)

## Sales Insight configureren in [!DNL Salesforce] {#configure-sales-insight-in-salesforce}

1. Klik in Salesforce op **[!UICONTROL Setup]** .

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-6-1.png)

1. Zoek naar &quot;verre plaats&quot;en selecteer **[!UICONTROL Remote Site Settings]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-7-1.png)

1. Klik op **[!UICONTROL New Remote Site]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-8-1.png)

1. Voer de naam van de externe site in (dit kan iets vergelijkbaars zijn als `MarketoSoapAPI` ). Voer de URL voor de externe site in. Dit is de URL van de Marketo-host in het configuratievenster voor de Soap API in Marketo Engage. Klik op **[!UICONTROL Save]**. U hebt nu externe site-instellingen voor de Soap API gemaakt.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-9-1.png)

1. Klik nogmaals op **[!UICONTROL New Remote Site]** .

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-10-1.png)

1. Voer de naam van de externe site in (dit kan bijvoorbeeld &quot;MarketoRestAPI&quot; zijn). Voer de URL van de externe site in. Dit is de API-URL van het configuratievenster voor de rest van de API in Marketo. Klik op **[!UICONTROL Save]**. U hebt nu externe site-instellingen voor de rest-API gemaakt.

## Toegang tot standaard Salesforce-objecten toestaan voor Insight-gebruikersprofielen {#grant-sales-insight-users-profile-access}

Vanwege beveiligingsverbeteringen in Salesforce kunnen AppExchange-pakketten geen toestemming meer verlenen voor standaardobjecten en moet toegang worden verleend tot de desbetreffende Salesforce-objecten vanuit het profiel van de Salesforce-gebruiker. Verleen de vereiste toestemmingen door deze stappen te volgen.

1. Klik op **[!UICONTROL Setup]**.

1. Zoek in Snel zoeken naar &quot;Profielen&quot;.

1. Klik op **[!UICONTROL Edit]** naast het profiel dat uw Salesforce-gebruikers gebruiken.

1. Schakel onder de sectie Standaard objectmachtigingen de optie Lezen in voor de volgende objecten: Lead, Contact, Account en Opportunity.

1. Klik op **[!UICONTROL Save]**.

## Paginalay-outs aanpassen {#customize-page-layouts}

1. Klik op **[!UICONTROL Setup]**.

   ![](assets/image2015-5-22-14-3a40-3a39-1.png)

1. Zoek naar &quot;paginalay-out&quot;en selecteer **[!UICONTROL Page Layout]** onder **[!UICONTROL Leads]**.

   ![](assets/image2015-5-28-14-3a58-3a39-1.png)

1. Klik op **[!UICONTROL Visualforce Pages]** aan de linkerkant. Sleep **[!UICONTROL Section]** naar de lay-out onder de sectie Aangepaste koppelingen.

   ![](assets/image2014-9-24-17-3a32-3a53.png)

1. Voer &quot;Marketo Sales Insight&quot; in als de **[!UICONTROL Section Name]** . Selecteer **[!UICONTROL 1-Column]** en klik op **[!UICONTROL OK]** .

   ![](assets/image2014-9-24-17-3a33-3a23.png)

1. Sleep **[!UICONTROL Lead]** naar de nieuwe sectie.

   ![](assets/image2014-9-24-17-3a33-3a45.png)

   >[!TIP]
   >
   >De naam van dit vak verandert op basis van het objecttype. Als u bijvoorbeeld de paginalay-out voor Contactpersonen wijzigt, wordt Contactpersoon weergegeven.

1. Dubbelklik op het blok **[!UICONTROL Lead]** dat u zojuist hebt toegevoegd.

   ![](assets/image2014-9-24-17-3a34-3a0.png)

1. Bewerk de hoogte tot 450 pixels en klik op **[!UICONTROL OK]** .

   ![](assets/image2014-9-24-17-3a34-3a26.png)

   >[!NOTE]
   >
   >Controleer **[!UICONTROL Show scrollbars]** als u toegang tot scroll-through activiteiten nodig hebt.

   >[!TIP]
   >
   >De aanbevolen hoogte voor de objecten Accounts en Opportunity is 410 pixels.

1. Klik op **[!UICONTROL Fields]** aan de linkerkant. Zoek en sleep het label **[!UICONTROL Engagement]** vervolgens naar de lay-out **[!UICONTROL Marketo Sales Insight]** .

   ![](assets/image2015-5-22-16-3a32-3a46-1.png)

1. Herhaal de vorige stap voor de volgende velden:

   * [!UICONTROL Engagement]
   * [!UICONTROL Relative Score Value]
   * [!UICONTROL Urgency Value]
   * [!UICONTROL Last Interesting Moment Date]
   * [!UICONTROL Last Interesting Moment Desc]
   * [!UICONTROL Last Interesting Moment Source]
   * [!UICONTROL Last Interesting Moment Type]

1. Klik op **[!UICONTROL Save]** als u klaar bent.

   ![](assets/image2014-9-24-17-3a35-3a6.png)

1. Herhaal stap 5-7 om visueel geforceerde paginagedeelten voor **[!UICONTROL Contact]**, **[!UICONTROL Account]** en **[!UICONTROL Opportunity]** toe te voegen.

1. Herhaal stap 8-10 om de velden Verkoopgegevens voor Insight voor **[!UICONTROL Contact]** toe te voegen. Sla het bestand op nadat u wijzigingen hebt aangebracht.

## Velden van aangepaste personen toewijzen {#map-custom-person-fields}

Marketo-persoonvelden moeten worden toegewezen aan Salesforce-contactvelden om ervoor te zorgen dat de conversie goed werkt. Voer de volgende stappen uit om deze toe te wijzen.

1. Klik op **[!UICONTROL Setup]**.

   ![](assets/image2015-5-22-14-3a40-3a39-1.png)

1. Zoek naar &quot;gebieden&quot;in de onderzoeksbar en klik **[!UICONTROL Fields]** onder **[!UICONTROL Leads]**.

   ![](assets/image2015-6-1-9-3a54-3a50-1.png)

1. Klik op **[!UICONTROL Map Lead Fields]**.

   ![](assets/image2015-6-1-9-3a58-3a48-1.png)

1. Klik op de vervolgkeuzelijst rechts voor **[!UICONTROL Engagement]** .

   ![](assets/image2015-6-1-10-3a9-3a53-1.png)

1. Selecteer **[!UICONTROL Contact.Engagement]** in de lijst.

   ![](assets/image2015-6-1-10-3a12-3a11-1.png)

1. Herhaal deze velden en wijs ze ook toe.

   | Aangepast veld voor Marketo-persoon | Aangepast veld Salesforce-contactpersoon |
   |--- |--- |
   | `Engagement` | `Contact.Engagement` |
   | `Relative Score Value` | `Contact.Relative Score Value` |
   | `Urgency Value` | `Contact.Urgency Value` |
   | `Last Interesting Moment Date` | `Contact.Last Interesting Moment Date` |
   | `Last Interesting Moment Desc` | `Contact.Last Interesting Moment Desc` |
   | `Last Interesting Moment Source` | `Contact.Last Interesting Moment Source` |
   | `Last Interesting Moment Type` | `Contact.Last Interesting Moment Type` |

   {style="table-layout:auto"}

1. Klik op **[!UICONTROL Save]** als u klaar bent.

   ![](assets/image2014-9-24-17-3a37-3a17.png)

## Marketo Sales Insight tabblad voor configuratie {#marketo-sales-insight-configuration-tab}

1. Klik in Salesforce op **+** aan het einde van de tabbalk en klik op **[!UICONTROL Marketo Sales Insight Config]** .

1. Kopieer de geloofsbrieven van het Soap API paneel in [ Marketo de pagina van Admin van de Verkoop Insight van de Verkoop ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md#set-up-marketo-sales-insight){target="_blank"} en kleef hen in de Zacht API sectie van de pagina van de Configuratie van Insight van de Verkoop van Salesforce.

1. Kopieer de geloofsbrieven van het **[!UICONTROL Rest API]** paneel in [ Marketo de pagina van Admin van de Verkoop Insight van de Verkoop ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md#set-up-marketo-sales-insight){target="_blank"} en kleef hen in de Rest API sectie van de pagina van de Configuratie van Insight van de Verkoop van Salesforce.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-27.png)

Je kunt de Marketo Sales Insight-velden weergeven voor leads, contactpersonen, accounts en opportunity.

>[!NOTE]
>
>Als de diagnostische test ontbrak, [ toevoegend meer gebieden aan uw paginalay-out ](https://nation.marketo.com/t5/knowledgebase/how-to-repair-marketo-sales-insight-setup-configuration-problems/ta-p/248218){target="_blank"} zou de kwestie kunnen bevestigen.

>[!NOTE]
>
>Voor accounts bevat Sales Insight alle e-mails, maar alleen de meest recente interessante momenten, webactiviteit en scorewijzigingen.

>[!MORELIKETHIS]
>
>* [ Prioriteit, Urgentie, Relatieve Score, en Beste Bets ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.md){target="_blank"}
>* [ voeg het Lusje van Marketo aan  [!DNL Salesforce]](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-marketo-tab-to-salesforce.md){target="_blank"} toe
>* [ voeg de Toegang van Insight van de Verkoop aan Profielen toe ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-sales-insight-access-to-profiles.md){target="_blank"}
