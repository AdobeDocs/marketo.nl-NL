---
description: Productverbruiksdashboards - Marketo-documenten - productdocumentatie
title: Productverbruiksdashboards
hide: true
hidefromtoc: true
feature: Administration
source-git-commit: f3bc58c0d65e8110c5366269fdb4abf817370aee
workflow-type: tm+mt
source-wordcount: '652'
ht-degree: 0%

---

# Productverbruiksdashboards {#product-usage-dashboards}

Met de Marketo Engage-productgebruiksdashboards kunt u het product- en platformgebruik bekijken tegen bepaalde limieten of achterstand bij het doorvoeren van gegevens, het gebruik tegen dagelijkse quota en belangrijke meetgegevens voor een abonnement. Infrastructuur wordt toegewezen om prestatiegrenzen te verstrekken die voor de Niveaus van het Product voor bijzondere attributen worden bepaald. Sommige van deze limieten, zoals API-gebruik, worden aangeschaft als onderdeel van uw pakket of productreeks.

## Toegang verkrijgen {#how-to-access}

1. In Marketo Engage, klik **Admin**.

   ![](assets/product-usage-dashboards-1.png)

1. In de boom op de linkerzijde, scrol neer en selecteer **dashboards van het Gebruik van het Product**.

   ![](assets/product-usage-dashboards-2.png)

## Activiteitenverbruiksdashboard {#activity-usage-dashboard}

### Gemiddelde wekelijkse activiteiten {#average-weekly-activities}

Het dashboard voor het wekelijkse activiteitenverbruik biedt een wekelijkse telling van de typen activiteiten over een schuivende periode van 52 weken. Gemaakte wekelijkse activiteiten zijn een goede indicator van hoeveel marketing je doet in Marketo Engage. De activiteiten dienen als een proxy voor de verschillende systeemprocessen en traceerbare gebeurtenissen die in Marketo plaatsvinden.

De Types van activiteit omvatten zowel tellingen van activiteiten die worden gevangen wanneer mensen die met marketing gebeurtenissen in wisselwerking staan evenals op systeem-gebaseerde activiteiten die door de Acties van de Stroom worden teweeggebracht. Voorbeelden van door personen geïnitieerde activiteiten zijn wanneer iemand een e-mail opent of op een koppeling in een e-mail klikt. Een voorbeeld van systeemgebaseerde activiteiten die door een Flow-actie worden geactiveerd, is &quot;Verzenden naar SFDC&quot; wanneer de trigger wordt gestart. Als u een aantal activiteitstypen voor een bepaalde week wilt weergeven, houdt u de muis boven een week en bekijkt u de telling.

![](assets/product-usage-dashboards-3.png){width="800" zoomable="yes"}

#### Veelgestelde vragen {#faq}

**Welke Types van Activiteit worden geteld?**

Het is afhankelijk van welke activiteiten in de pijplijn zijn opgenomen.

**is zowel gekend als anonieme lood/persoonactiviteit inbegrepen?**

Alleen bekende mensen/leads.

**hoe vaak worden de gegevens verfrist?**

Het aantal activiteiten wordt elke ochtend vernieuwd.

## Uitsplitsing naar activiteit {#activity-breakdown}

Hier krijgen we tellingen over activiteiten in de afgelopen zeven dagen op basis van betekenisvolle segmenten van de gegevens. Groepeer activiteiten op basis van de meest voorkomende soorten activiteiten die in de afgelopen zeven dagen zijn waargenomen. Dit kunnen categorieën zijn zoals &quot;Gegevenswaarde wijzigen&quot;, &quot;Toevoegen aan lijst&quot; of &quot;E-mail verzenden&quot;. Dit laat u zien welke soorten activiteiten het vaakst in het systeem gebeuren. Het gebruik van Type activiteit is een belangrijke indicator om de groei te bepalen, of als optimalisaties nodig zijn om het gebruik te verminderen.

>[!NOTE]
>
>* Alle hieronder onderverdelingen zijn een &quot;het rollen zeven-dag&quot;som en **niet** omvatten de huidige dag. Denk er dus aan als &quot;gisteren + zes dagen daarvoor&quot;.
>
>* Op het dashboard worden alleen de bovenste 20 activiteitstypen weergegeven, terwijl de rest wordt gesorteerd in de categorie &quot;Overige&quot;.

![](assets/product-usage-dashboards-4.png){width="800" zoomable="yes"}

Activiteitengebruik is een belangrijke indicator van hoeveel marketing wordt uitgevoerd, en helpt de groei te visualiseren ten opzichte van het vastgestelde niveau van het product waarvoor een contract is gesloten. De dashboards kunnen ook als gids worden gebruikt om te bepalen hoeveel optimalisering kan/moet worden gedaan door de gebieden te verminderen die worden bijgewerkt.

### Op type {#by-type}

Groepeer activiteiten op basis van de meest voorkomende soorten activiteiten die in de afgelopen zeven dagen zijn waargenomen. Dit kan categorieën zoals _de Waarde van Gegevens van de Verandering_ omvatten, _toevoegen aan Lijst_, of _verzenden E-mail_. Dit laat u zien welke soorten activiteiten het vaakst in Marketo Engage plaatsvinden.

### Op kenmerk Gegevenswaarde wijzigen {#by-change-data-value-attribute}

_de Waarde van Gegevens van de Verandering_ is het gemeenschappelijkste activiteitstype. Hiermee wordt aangegeven wanneer een informatie over een persoon/lead-record wordt bijgewerkt. Hier groeperen wij door de gebieden die het vaakst worden veranderd zodat kunt u bepalen welke informatie voor uw marketing verrichtingen nuttig is, als er mogelijkheden zijn om platformgebruik te optimaliseren, etc.

### Op campagne {#by-campaign}

Groepering waardoor campagnes de meeste activiteiten produceren. Dit biedt insight de mogelijkheid om te zien of je met name &#39;lawaaierige&#39; campagnes hebt die meer activiteit creëren dan nodig is. Snel leren over campagnes die buiten bedrijf moeten worden gesteld, of campagnes die meer werk doen dan bedoeld.

### Op Source (KOMEND) {#by-source}

Groep door de bron van de activiteiten (_de Synchronisatie van CRM_, _de Actie van de Stroom van de Campagne_, _API uploadt_, _het Bestaan van de Vorm van de Pagina Vulling_, enz.). Dit helpt u begrijpen als de meeste van uw activiteiten door marketing acties, CRM syncs, of door de mensen/de leiders zelf worden veroorzaakt.
