---
unique-page-id: 3571890
description: Aangepaste veldgroepen inschakelen voor modelprestatieanalyse (leadads) - Marketo Docs - productdocumentatie
title: Aangepaste veldgroepen inschakelen voor analyse van modelprestaties (lead)
exl-id: 417fd74f-d8f5-477b-b633-0fdfdd68b22b
feature: Reporting, Revenue Cycle Analytics
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '325'
ht-degree: 0%

---

# Aangepaste veldgroepen inschakelen voor analyse van modelprestaties (lead) {#enable-custom-field-groups-for-model-performance-analysis-leads}

>[!PREREQUISITES]
>
>Categoriseer standaard- of aangepaste velden in groepen voor rapportage via de veldOrganizer in Marketo. Voor details, zie [ de Groepen van het Gebied van de Douane via de Organisator van het Gebied ](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/field-organizers/create-custom-field-groups-using-the-field-organizer.md) creëren.

<table> 
 <tbody> 
  <tr> 
   <td colspan="3" rowspan="1"><p align="center"><strong>Hoe beïnvloedt het toelaten van een Groep van het Gebied van de Douane Veelvoudige Analyse Gebieden in de Ontdekkingsreiziger van de Cyclus van de Ontvangsten?</strong></p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p><strong>Wat gebeurt er wanneer?</strong></p></td> 
   <td colspan="1" rowspan="1"><p><strong>Hoe het het beïnvloedt de <span class="uicontrol"> ModelAnalyse van Prestaties (leidt tot) </span> Gebied</strong></p></td> 
   <td colspan="1" rowspan="1"><p><strong>Hoe het de Analyse van de Lood, de Analyse van de Campagne, en de Gebieden van de Analyse van de Kans beïnvloedt</strong></p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p><strong>Wat gebeurt wanneer u een groep van het douaneveld toelaat verbonden aan een standaardlood of bedrijfgebied?</strong></p></td> 
   <td colspan="1" rowspan="1"><p>De groep van het douanegebied wordt toegelaten voor het melden in het <span class="uicontrol"> ModelAnalyse van Prestaties (Lood) </span> Gebied</p></td> 
   <td colspan="1" rowspan="1"><p>Geen effect</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p><strong>Wat gebeurt wanneer u een groep van het douanegebied toelaat verbonden aan een douanepersoon of bedrijfgebied?</strong></p></td> 
   <td colspan="1" rowspan="1"><p>De groep van het douanegebied wordt toegelaten voor het melden in het <span class="uicontrol"> ModelAnalyse van Prestaties (Lood) </span> Gebied</p></td> 
   <td colspan="1" rowspan="1"><p>Het douanegebied zelf wordt toegelaten voor rapportering in de Gebieden van de Analyse van de Lood, van de Analyse van de Campagne, en van de Analyse van de Kans.</p><p><strong> NOTA:</strong> de gebiedsgroepen van de Douane worden NIET gesteund op deze analysegebieden, zodat tonen de groepsverenigingen niet in de Ontdekkingsreiziger van de Cyclus van de Opbrengst— <em> slechts </em> het douanegebied.</p></td> 
  </tr> 
 </tbody> 
</table>

Voer de volgende stappen uit om een aangepaste veldgroep voor rapportage in het [!UICONTROL Model Performance Analysis (Leads)] -gebied in te schakelen.

1. Klik op **[!UICONTROL Admin]**.

   ![](assets/one-1.png)

1. Klik op **[!UICONTROL Revenue Cycle Analytics]**.

   ![](assets/two-1.png)

1. Klik op **[!UICONTROL None]** naast een lege veldgroep. Als u al drie veldgroepen hebt ingeschakeld en u wilt bewerken, klikt u op de naam van de veldgroep die u wilt wijzigen.

   ![](assets/three.png)

1. Klik op de vervolgkeuzelijst **[!UICONTROL Field]** en selecteer de gewenste.

   ![](assets/four-1.png)

   >[!NOTE]
   >
   >In dit voorbeeld is een aangepaste veldgroep ingeschakeld voor een standaardveld (Frame). Daarom werd alleen het [!UICONTROL Model Performance Analysis (Leads)] -gebied beïnvloed. Als een aangepaste veldgroep voor een aangepaste persoon of een aangepast bedrijfsveld was ingeschakeld, zou de ingeschakelde groep worden weergegeven in de [!UICONTROL Model Performance Analysis (Leads)] -sectie van het tabblad Overzicht van synchronisatie en zou het aantal aangepaste velden voor de analyse van leads, campagnes en opportuniteit met één toenemen.

1. Klik op **[!UICONTROL Save]**.

   ![](assets/five-1.png)
