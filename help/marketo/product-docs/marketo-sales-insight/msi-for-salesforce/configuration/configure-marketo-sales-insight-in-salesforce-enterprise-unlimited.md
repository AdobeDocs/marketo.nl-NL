---
unique-page-id: 2360368
description: Leer hoe u Marketo Sales Insight configureert in Salesforce Enterprise/Unlimited-edities.
title: Marketo Sales Insight configureren in Salesforce Enterprise/Onbeperkt
exl-id: a33ed396-8d26-403f-b6d8-fe7c55ce76ba
feature: Marketo Sales Insights
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '744'
ht-degree: 1%

---

# [!DNL Marketo Sales Insight] configureren in [!DNL Salesforce] Enterprise/Unlimited {#configure-marketo-sales-insight-in-salesforce-enterprise-unlimited}

Configureer Marketo Sales Insight in Salesforce Enterprise/Unlimited-edities door de volgende stappen uit te voeren.

>[!PREREQUISITES]
>
>[ installeer  [!DNL Marketo Sales Insight]  Pakket in  [!DNL Salesforce]  AppExchange ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)

>[!NOTE]
>
>{de toestemmingen van 0} Admin worden vereist.****

## Sales Insight in Marketo Engage configureren {#configure-sales-insight-in-marketo}

1. Ga naar het gebied **[!UICONTROL Admin]** en selecteer **[!UICONTROL Sales Insight]** als u uw Marketo Sales Insight-gegevens in Marketo Engage wilt opvragen.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-1.png)

1. Klik op **[!UICONTROL Edit API Configuration]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-2.png)

1. Voer naar keuze een API-beveiligingssleutel in en klik op **[!UICONTROL Save]** . Gebruik geen en-teken (`&`) in de geheime API-sleutel.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-3.png)

   >[!NOTE]
   >
   >De geheime sleutel van uw API is als een wachtwoord voor uw organisatie en zou veilig moeten zijn.

1. Klik op **[!UICONTROL View]** in het deelvenster _[!UICONTROL Rest API Configuration]_om de referenties te vullen.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-4.png)

1. Klik op **[!UICONTROL OK]** wanneer er een bevestigingsvenster wordt weergegeven.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-5.png)

   >[!TIP]
   >
   >Laat dit venster open. U hebt deze informatie later nodig voor de Salesforce-configuratie.

## [!DNL Sales Insight] configureren in [!DNL Salesforce] {#configure-sales-insight-in-salesforce}

1. Klik in Salesforce op **[!UICONTROL Setup]** .

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-6.png)

1. Zoek naar &quot;verre plaats&quot;en selecteer **[!UICONTROL Remote Site Settings]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-7.png)

1. Klik op **[!UICONTROL New Remote Site]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-8.png)

1. Voer de naam van de externe site in (dit kan iets vergelijkbaars zijn als `MarketoSoapAPI` ). Voer de URL van de externe site in. Dit is de URL van de Marketo-host in het deelvenster _[!UICONTROL Soap API Configuration]_in Marketo Engage. Klik op **[!UICONTROL Save]**. U hebt nu externe site-instellingen voor de Soap API gemaakt.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-9.png)

1. Klik nogmaals op **[!UICONTROL New Remote Site]** .

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-10.png)

1. Voer de naam van de externe site in (dit kan iets vergelijkbaars zijn als `MarketoAPI` ). Voer de URL van de externe site in. Dit is de API-URL vanuit het deelvenster _[!UICONTROL Rest API Configuration]_in Marketo Engage. Klik op **[!UICONTROL Save]**. U hebt nu externe site-instellingen voor de rest-API gemaakt.

   >[!NOTE]
   >
   >_u_ kiest uw **[!UICONTROL Remote Site Name]** (`MarketoAPI` wordt hier gebruikt). **[!UICONTROL Remote Site URL]** vindt u in het veld Marketo-host van het dialoogvenster API-configuratie bewerken in stap 3 van de sectie &quot;Verkoop Insight in Marketo configureren&quot;.

## Toegang tot standaard Salesforce-objecten toestaan voor Insight-gebruikersprofielen {#grant-sales-insight-users-profile-access}

Vanwege beveiligingsverbeteringen in Salesforce kunnen AppExchange-pakketten geen toestemming meer verlenen voor standaardobjecten en moet toegang worden verleend tot de desbetreffende Salesforce-objecten vanuit het profiel van de Salesforce-gebruiker. Voer de volgende stappen uit om de vereiste machtigingen te verlenen.

1. Klik op **[!UICONTROL Setup]**.

1. Zoek in Snel zoeken naar &quot;Profielen&quot;.

1. Klik op **[!UICONTROL Edit]** naast het profiel dat uw Salesforce-gebruikers gebruiken.

1. Schakel onder de sectie _[!UICONTROL Standard Object Permission]_**[!UICONTROL Read]**toegang in voor de volgende objecten: [!UICONTROL Lead] , [!UICONTROL Contact] , [!UICONTROL Account] en [!UICONTROL Opportunity] .

1. Klik op **[!UICONTROL Save]**.

## Paginalay-outs aanpassen {#customize-page-layouts}

1. Klik op **[!UICONTROL Setup]**.

   ![](assets/image2015-5-22-14-3a40-3a39.png)

1. Zoek naar &quot;paginalay-out&quot;en selecteer **[!UICONTROL Page Layout]** onder **[!UICONTROL Leads]**.

   ![](assets/image2015-5-28-14-3a58-3a39.png)

1. Klik op **[!UICONTROL Visualforce Pages]** aan de linkerkant. Sleep **[!UICONTROL Section]** naar de lay-out onder de sectie _[!UICONTROL Custom Links]_.

   ![](assets/image2014-9-24-17-3a32-3a53.png)

1. Voer &quot;Marketo Sales Insight&quot; in als de **[!UICONTROL Section Name]** , selecteer **[!UICONTROL 1-Column]** en klik op **[!UICONTROL OK]** .

   ![](assets/image2014-9-24-17-3a33-3a23.png)

1. Sleep **[!UICONTROL Lead]** naar de nieuwe sectie.

   ![](assets/image2014-9-24-17-3a33-3a45.png)

   >[!TIP]
   >
   >De naam van dit vak verandert op basis van het objecttype. Als u bijvoorbeeld de paginalay-out voor Contactpersonen wijzigt, wordt Contactpersoon weergegeven.

1. Dubbelklik op het blok **[!UICONTROL Lead]** dat u zojuist hebt toegevoegd.

   ![](assets/image2014-9-24-17-3a34-3a0.png)

1. Bewerk hoogte aan **450** pixel en klik **[!UICONTROL OK]**.

   ![](assets/image2014-9-24-17-3a34-3a26.png)

   >[!NOTE]
   >
   >Controleer **[!UICONTROL Show scrollbars]** als u toegang tot scroll-through activiteiten nodig hebt.

   >[!TIP]
   >
   >De aanbevolen hoogte voor de objecten Accounts en Opportunity is 410 pixels.

1. Klik op **[!UICONTROL Fields]** aan de linkerkant. Zoek en sleep het label **[!UICONTROL Urgency]** vervolgens naar de lay-out **[!UICONTROL Marketo Sales Insight]** .

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-18.png)

1. Herhaal bovenstaande stap ook voor deze velden.

   * Laatste interessant moment
   * Datum laatste interessant moment
   * Laatste interessante momentele beschrijving
   * Laatste interessant moment Source
   * Type laatst interessant moment
   * Laatste activiteit per verkoop
   * Laatste betrokkenheid bij verkoop
   * MSI-contact-id
   * Relatieve score
   * Relatieve score
   * Urgentie
   * Urgentiewaarde
   * Weergeven in Marketo

1. Klik op **[!UICONTROL Save]** als u klaar bent.

   ![](assets/image2014-9-24-17-3a35-3a6.png)

1. Herhaal stap 5-7 om secties op de pagina Visualforce toe te voegen en de velden Insight verkopen voor **[!UICONTROL Contact]** , **[!UICONTROL Account]** en **[!UICONTROL Opportunity]** .

1. Herhaal stap 8-10 om deze verkoopvelden voor Insight voor **[!UICONTROL Contact]** toe te voegen. Sla eventuele wijzigingen op.

   * Laatste interessant moment
   * Datum laatste interessant moment
   * [!UICONTROL Last Interesting Moment Desc]
   * [!UICONTROL Last Interesting Moment Source]
   * [!UICONTROL Last Interesting Moment Type]
   * [!UICONTROL Last Marketo Activity by Sales]
   * [!UICONTROL Last Marketo Engagement by Sales]
   * [!UICONTROL MKTO Lead Score]
   * [!UICONTROL Relative Score]
   * [!UICONTROL Relative Score Value]
   * [!UICONTROL Sales Insight] - Opent contact met de volledige lijstpagina
   * [!UICONTROL Urgency]
   * [!UICONTROL Urgency Value]

## Aangepaste persoonlijke velden toewijzen {#map-custom-person-fields}

Marketo-persoonvelden moeten worden toegewezen aan Salesforce-contactvelden om ervoor te zorgen dat de conversie goed werkt. Voer de volgende stappen uit om deze toe te wijzen.

1. Klik op **[!UICONTROL Setup]**.

   ![](assets/image2015-5-22-14-3a40-3a39.png)

1. Zoek naar &quot;gebieden&quot;in de onderzoeksbar en klik **[!UICONTROL Fields]** onder **[!UICONTROL Leads]**.

   ![](assets/image2015-6-1-9-3a54-3a50.png)

1. Klik op **[!UICONTROL Map Lead Fields]**.

   ![](assets/image2015-6-1-9-3a58-3a48.png)

1. Klik op de vervolgkeuzelijst rechts voor **[!UICONTROL Engagement]** .

   ![](assets/image2015-6-1-10-3a9-3a53.png)

1. Selecteer **[!UICONTROL Contact.Engagement]** in de lijst.

   ![](assets/image2015-6-1-10-3a12-3a11.png)

1. U kunt deze velden ook herhalen en toewijzen.

   | Aangepast veld voor Marketo-persoon | Aangepast veld Salesforce-contactpersoon |
   |--- |--- |
   | `Engagement` | `Contact.Engagement` |
   | `Relative Score Value` | `Contact.Relative Score Value` |
   | `Urgency Value` | `Contact.Urgency Value` |
   | `Last Interesting Moment Date` | `Contact.Last Interesting Moment Date` |
   | `Last Interesting Moment Desc` | `Contact.Last Interesting Moment Desc` |
   | `Last Interesting Moment Source` | `Contact.Last Interesting Moment Source` |
   | `Last Interesting Moment Type` | `Contact.Last Interesting Moment Type` |

1. Klik op **[!UICONTROL Save]** wanneer u klaar bent.

## Marketo Sales Insight tabblad voor configuratie {#marketo-sales-insight-configuration-tab}

1. Klik in Salesforce op **+** aan het einde van de tabbalk en klik op **[!UICONTROL Marketo Sales Insight Config]** .

1. Kopieer de geloofsbrieven van het Soap API paneel in [ Marketo de pagina van Admin van de Verkoop Insight ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md#set-up-marketo-sales-insight){target="_blank"} en kleef hen in de sectie van Soap API van de [!DNL Salesforce] [!DNL Sales Insight] pagina van de Configuratie.

1. Kopieer de geloofsbrieven van het Rest API paneel in [ Marketo de pagina van Admin van de Verkoop Insight ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md#set-up-marketo-sales-insight){target="_blank"} en kleef hen in de Rest API sectie van de [!DNL Salesforce] [!DNL Sales Insight] pagina van de Configuratie.

   ![](assets/configure-marketo-sales-insight-in-salesforce-enterprise-edition-25.png)

Je kunt de Marketo Sales Insight-velden weergeven voor leads, contactpersonen, accounts en opportunity.

>[!NOTE]
>
>Als de diagnostische test ontbrak, [ toevoegend meer gebieden aan uw paginalay-out ](https://nation.marketo.com:443/t5/knowledgebase/how-to-repair-marketo-sales-insight-setup-configuration-problems/ta-p/248218){target="_blank"} zou de kwestie kunnen bevestigen.

>[!NOTE]
>
>Voor accounts bevat Sales Insight alle e-mails, maar alleen de meest recente interessante momenten, webactiviteit en scorewijzigingen.

>[!MORELIKETHIS]
>
>* [ Prioriteit, Urgentie, Relatieve Score, en Beste Bets ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.md)
>* [ voeg het Lusje van Marketo aan  [!DNL Salesforce]](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-marketo-tab-to-salesforce.md) toe
>* [ voeg de Toegang van Insight van de Verkoop aan Profielen toe ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-sales-insight-access-to-profiles.md){target="_blank"}
