---
unique-page-id: 2360368
description: Leer hoe u Marketo Sales Insight configureert in Salesforce Enterprise/Unlimited-edities.
title: Marketo Sales Insight configureren in Salesforce Enterprise/Onbeperkt
exl-id: a33ed396-8d26-403f-b6d8-fe7c55ce76ba
feature: Marketo Sales Insights
source-git-commit: 3cbefabe80778b0502eaecd733b5732fd9003316
workflow-type: tm+mt
source-wordcount: '762'
ht-degree: 1%

---

# Marketo Sales Insight configureren in Salesforce Enterprise/Onbeperkt {#configure-marketo-sales-insight-in-salesforce-enterprise-unlimited}

Configureer Marketo Sales Insight in Salesforce Enterprise/Unlimited-edities door de volgende stappen uit te voeren.

>[!PREREQUISITES]
>
>[Marketo Sales Insight Package installeren in Salesforce AppExchange](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)

>[!NOTE]
>
>**Beheerdersmachtigingen zijn vereist.**

## Verkoopcontrole in Marketo Engage configureren {#configure-sales-insight-in-marketo}

1. Ga naar de **[!UICONTROL Admin]** gebied en selecteer **[!UICONTROL Sales Insight]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-1.png)

1. Klik op **[!UICONTROL Edit API Configuration]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-2.png)

1. Voer een door u gekozen API-beveiligingssleutel in en klik op **[!UICONTROL Save]**. Gebruik GEEN ampersand (`&`) in uw API geheime sleutel.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-3.png)

   >[!NOTE]
   >
   >De geheime sleutel van uw API is als een wachtwoord voor uw organisatie en zou veilig moeten zijn.

1. Als u de referenties wilt vullen, klikt u op **[!UICONTROL View]** in de _[!UICONTROL Rest API Configuration]_&#x200B;deelvenster.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-4.png)

1. Als er een bevestigingsvenster verschijnt, klikt u op **[!UICONTROL OK]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-5.png)

   >[!TIP]
   >
   >Laat dit venster open. U hebt deze informatie later voor configuratie Salesforce nodig.

## Verkoopinzicht configureren in Salesforce {#configure-sales-insight-in-salesforce}

1. Klik in Salesforce op **[!UICONTROL Setup]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-6.png)

1. Zoeken naar &quot;externe site&quot; en selecteren **[!UICONTROL Remote Site Settings]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-7.png)

1. Klik op **[!UICONTROL New Remote Site]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-8.png)

1. Voer de naam van de externe site in (dit kan iets gelijkaardigs zijn `MarketoSoapAPI`). Voer de URL van de externe site in. Dit is de URL van de Marketo-host in het dialoogvenster _[!UICONTROL Soap API Configuration]_&#x200B;in Marketo Engage. Klik op **[!UICONTROL Save]**. U hebt nu externe site-instellingen voor de Soap API gemaakt.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-9.png)

1. Klikken **[!UICONTROL New Remote Site]** opnieuw.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-10.png)

1. Voer de naam van de externe site in (dit kan iets gelijkaardigs zijn `MarketoAPI`). Voer de URL van de externe site in. Dit is de API-URL van _[!UICONTROL Rest API Configuration]_&#x200B;in Marketo Engage. Klik op **[!UICONTROL Save]**. U hebt nu externe site-instellingen voor de rest-API gemaakt.

   >[!NOTE]
   >
   >_U_ kies uw **[!UICONTROL Remote Site Name]** (`MarketoAPI` wordt hier gebruikt). De **[!UICONTROL Remote Site URL]** U vindt dit in het veld Marketo-host van het dialoogvenster API-configuratie bewerken in stap 3 van de sectie &quot;Sales Insight configureren in Marketo&quot;.

## De gebruikers van het Inzicht van de Verkoop van de Toekenning toegang tot standaard voorwerpen van Salesforce {#grant-sales-insight-users-profile-access}

Vanwege beveiligingsverbeteringen in Salesforce kunnen pakketten voor AppExchanges geen toestemming meer verlenen voor standaardobjecten en moet toegang worden verleend aan de desbetreffende Salesforce-objecten vanuit het profiel van de Salesforce-gebruiker. Voer de volgende stappen uit om de vereiste machtigingen te verlenen.

1. Klik op **[!UICONTROL Setup]**.

1. Zoek in Snel zoeken naar &quot;Profielen&quot;.

1. Klikken **[!UICONTROL Edit]** naast het profiel dat uw Salesforce-gebruikers gebruiken.

1. Onder de _[!UICONTROL Standard Object Permission]_&#x200B;sectie, inschakelen **[!UICONTROL Read]**&#x200B;toegang voor de volgende objecten: [!UICONTROL Lead], [!UICONTROL Contact], [!UICONTROL Account], en [!UICONTROL Opportunity].

1. Klik op **[!UICONTROL Save]**.

## Paginalay-outs aanpassen {#customize-page-layouts}

1. Klik op **[!UICONTROL Setup]**.

   ![](assets/image2015-5-22-14-3a40-3a39.png)

1. Zoek naar &quot;paginalay-out&quot;en selecteer **[!UICONTROL Page Layout]** krachtens **[!UICONTROL Leads]**.

   ![](assets/image2015-5-28-14-3a58-3a39.png)

1. Klikken **[!UICONTROL Visualforce Pages]** links. Slepen **[!UICONTROL Section]** op de layout onder de _[!UICONTROL Custom Links]_&#x200B;sectie.

   ![](assets/image2014-9-24-17-3a32-3a53.png)

1. Voer &quot;Marketo Sales Insight&quot; in als de **[!UICONTROL Section Name]**, selecteert u **[!UICONTROL 1-Column]** en klik op **[!UICONTROL OK]**.

   ![](assets/image2014-9-24-17-3a33-3a23.png)

1. Slepen en slepen **[!UICONTROL Lead]** in de nieuwe sectie.

   ![](assets/image2014-9-24-17-3a33-3a45.png)

   >[!TIP]
   >
   >De naam van dit vak verandert op basis van het objecttype. Als u bijvoorbeeld de paginalay-out voor Contactpersonen wijzigt, wordt Contactpersoon weergegeven.

1. Dubbelklik op de knop **[!UICONTROL Lead]** blokkeren die u zojuist hebt toegevoegd.

   ![](assets/image2014-9-24-17-3a34-3a0.png)

1. Hoogte bewerken tot **450** pixels en klik op **[!UICONTROL OK]**.

   ![](assets/image2014-9-24-17-3a34-3a26.png)

   >[!NOTE]
   >
   >Controleren **[!UICONTROL Show scrollbars]** als u toegang tot scroll-through activiteiten nodig hebt.

   >[!TIP]
   >
   >De aanbevolen hoogte voor de objecten Accounts en Opportunity is 410 pixels.

1. Klikken **[!UICONTROL Fields]** links. Zoek en sleep vervolgens het gereedschap **[!UICONTROL Urgency]** in de **[!UICONTROL Marketo Sales Insight]** layout.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-18.png)

1. Herhaal bovenstaande stap ook voor deze velden.

   * Laatste interessant moment
   * Datum laatste interessant moment
   * Laatste interessante momentele beschrijving
   * Laatste interessante mompbron
   * Type laatst interessant moment
   * Laatste activiteit per verkoop
   * Laatste betrokkenheid bij verkoop
   * MSI-contact-id
   * Relatieve score
   * Relatieve score
   * Urgentie
   * Urgentiewaarde
   * Weergeven in Marketo

1. Klikken **[!UICONTROL Save]** wanneer gereed.

   ![](assets/image2014-9-24-17-3a35-3a6.png)

1. Herhaal stap 5-7 om Visualforce paginagedeelten en de gebieden van het Inzicht van de Verkoop voor toe te voegen **[!UICONTROL Contact]**, **[!UICONTROL Account]**, en **[!UICONTROL Opportunity]**.

1. Herhaal stap 8-10 om deze velden van het Inzicht van de Verkoop toe te voegen voor **[!UICONTROL Contact]**. Sla eventuele wijzigingen op.

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
   * [!UICONTROL Sales Insight] - Opent contact volledige lijstpagina
   * [!UICONTROL Urgency]
   * [!UICONTROL Urgency Value]

## Aangepaste persoonlijke velden toewijzen {#map-custom-person-fields}

Marketo-persoonvelden moeten worden toegewezen aan Salesforce-contactvelden om ervoor te zorgen dat de conversie goed werkt. Voer de volgende stappen uit om deze toe te wijzen.

1. Klik op **[!UICONTROL Setup]**.

   ![](assets/image2015-5-22-14-3a40-3a39.png)

1. Zoek naar &quot;gebieden&quot;in de onderzoeksbar en klik **[!UICONTROL Fields]** krachtens **[!UICONTROL Leads]**.

   ![](assets/image2015-6-1-9-3a54-3a50.png)

1. Klik op **[!UICONTROL Map Lead Fields]**.

   ![](assets/image2015-6-1-9-3a58-3a48.png)

1. Klik op het vervolgkeuzemenu rechts voor **[!UICONTROL Engagement]**.

   ![](assets/image2015-6-1-10-3a9-3a53.png)

1. Selecteren **[!UICONTROL Contact.Engagement]** in de lijst.

   ![](assets/image2015-6-1-10-3a12-3a11.png)

1. U kunt deze velden ook herhalen en toewijzen.

   | Aangepast veld voor Marketo-persoon | Aangepast veld voor Salesforce-contact |
   |--- |--- |
   | `Engagement` | `Contact.Engagement` |
   | `Relative Score Value` | `Contact.Relative Score Value` |
   | `Urgency Value` | `Contact.Urgency Value` |
   | `Last Interesting Moment Date` | `Contact.Last Interesting Moment Date` |
   | `Last Interesting Moment Desc` | `Contact.Last Interesting Moment Desc` |
   | `Last Interesting Moment Source` | `Contact.Last Interesting Moment Source` |
   | `Last Interesting Moment Type` | `Contact.Last Interesting Moment Type` |

1. Klikken **[!UICONTROL Save]** als je klaar bent.

## Het tabblad Marketo Sales Insight-configuratie {#marketo-sales-insight-configuration-tab}

1. Klik in Salesforce op de knop **+** aan het einde van de tabbalk en klik op **[!UICONTROL Marketo Sales Insight Config]**.

1. Kopieer de referenties vanuit het deelvenster Soap API in [Admin-pagina Marketo Sales Insight](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md#set-up-marketo-sales-insight){target="_blank"} en plak ze in de sectie Soap API van de pagina Configuratie van het Inzicht van de Verkoop Salesforce.

1. Kopieer de referenties vanuit het deelvenster Rest API in [Admin-pagina Marketo Sales Insight](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md#set-up-marketo-sales-insight){target="_blank"} en plak hen in de Rest API sectie van de pagina van de Configuratie van het Inzicht van de Verkoop Salesforce.

   ![](assets/configure-marketo-sales-insight-in-salesforce-enterprise-edition-25.png)

U zou de gebieden van het Inzicht van de Verkoop van Marketo voor Leads, Contacten, Rekeningen, en Kansen moeten kunnen zien.

>[!NOTE]
>
>Indien de diagnostische test mislukt, [toevoegen van meer velden aan uw pagina-indeling](https://nation.marketo.com:443/t5/knowledgebase/how-to-repair-marketo-sales-insight-setup-configuration-problems/ta-p/248218){target="_blank"} kan het probleem verhelpen.

>[!NOTE]
>
>Voor accounts omvat Verkoopinzicht alle e-mailberichten, maar alleen de meest recente interessante momenten, webactiviteit en scorewijzigingen.

>[!MORELIKETHIS]
>
>* [Prioriteit, Urgentie, Relatieve Score en Beste Bets](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.md)
>* [Marketo Tab toevoegen aan Salesforce](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-marketo-tab-to-salesforce.md)
>* [Toegang tot verkoopinzicht toevoegen aan profielen](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-sales-insight-access-to-profiles.md){target="_blank"}
