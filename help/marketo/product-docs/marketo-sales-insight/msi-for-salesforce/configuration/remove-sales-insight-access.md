---
description: Verkoop Insight Access verwijderen - Marketo Docs - Productdocumentatie
title: Insight-toegang voor verkoop verwijderen
exl-id: 3cda112a-524e-469b-a222-c0192b2f5301
feature: Marketo Sales Insights
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '329'
ht-degree: 1%

---

# Toegang [!DNL Sales Insight] verwijderen {#remove-sales-insight-access}

Gebruik de volgende stappen om de toegang tot [!DNL Sales Insight] -functies in [!DNL Salesforce] te verwijderen. Van toepassing op [!DNL Salesforce] Klassieke en Bliksem.

## Overzicht {#overview}

Toestemming voor de objecten hieronder, apex-klassen en pagina&#39;s met visuele kracht is vereist om toegang te krijgen tot alle [!DNL Sales Insight] -functies. Als u deze verwijdert, wordt de toegang tot [!DNL Sales Insight] verwijderd.

**de Montages van Objecten**

<table>
 <tbody>
 <tr>
   <td>BestBetsCache</td>
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td>
  </tr>
  <tr>
   <td>[!DNL Best Bets] Details weergeven</td>
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td>
  </tr>
  <tr>
   <td>[!DNL Best Bets] Weergaven</td>
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td>
  </tr>
  <tr>
   <td>EmailActivityCache</td>
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td>
  </tr>
  <tr>
   <td>GetMethodArgus</td>
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td>
  </tr>
  <tr>
   <td>GroupedWebActivityCache</td>
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td>
  </tr>
  <tr>
   <td>InterestingMomentsCache</td>
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td>
  </tr>
  <tr>
   <td>[!DNL Marketo Sales Insight] Config</td>
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td>
  </tr>
  <tr>
   <td>ScoringCache</td>
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td>
  </tr>
  <tr>
   <td>Waarden</td>
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td>
  </tr>
  <tr>
   <td>WebActivityCache</td>
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td>
  </tr>
 </tbody>
</table>

* Toegang tot Apex-klasse: 159 Apex-klassen die beginnen met &quot;mkto_si&quot;
* Visualforce Page Access: 64 Visualforce-pagina&#39;s die beginnen met &quot;mkto_si&quot;
* Definities voor aangepaste instellingen: mkto_si.Marketo Settings &amp; mkto_si.User Preferences

## Toegang tot [!DNL Sales Insight] verwijderen {#removing-access-to-sales-insight}

1. Meld u aan bij uw [!DNL Salesforce] -account.

1. Klik op **[!UICONTROL Setup]**.

   ![](assets/remove-sales-insight-access-1.png)

1. Klik onder [!UICONTROL Administrator] op **[!UICONTROL Manage Users]** en vervolgens op **[!UICONTROL Profiles]** .

1. Klik op het profiel dat u wilt bijwerken en klik vervolgens op **[!UICONTROL Edit]** .

1. Schuif omlaag naar &quot;[!UICONTROL Custom Tab Settings]&quot; onder [!UICONTROL Tab Settings] .

1. Selecteer de optie &quot;[!UICONTROL Tab Hidden]&quot; in de vervolgkeuzelijst voor [!DNL Marketo Sales Insight] Configuratie en MSI [!DNL Marketo Sales] in het Postvak UIT.

   ![](assets/remove-sales-insight-access-2.png)

   ![](assets/remove-sales-insight-access-3.png)

1. Schuif omlaag naar &quot;[!UICONTROL Custom Object Permissions]&quot;.

1. Verwijder de toegang &quot;Lezen, Maken, Bewerken, Verwijderen&quot; uit de volgende objecten:

   * BestBetsCache
   * [!DNL Best Bets] Details weergeven
   * [!DNL Best Bets] Weergaven
   * EmailActivityCache
   * GetMethodArgus
   * GroupedWebActivityCache
   * InterestingMomentsCache
   * [!DNL Marketo Sales Insight] Config
   * ScoringCache
   * Waarden
   * WebActivityCache

1. Schuif omlaag naar de sectie &quot;[!UICONTROL Enabled Apex Class Access]&quot;. Klik op **[!UICONTROL Edit]**.

1. Selecteer in de sectie &quot;[!UICONTROL Enabled Apex Classes]&quot; alle klassen die met &quot;mkto_si&quot; beginnen. Dit zou tot 159 klassen moeten toevoegen.

1. Klik op **[!UICONTROL Remove]** en vervolgens op **[!UICONTROL Save]** .

   ![](assets/remove-sales-insight-access-4.png)

1. Schuif omlaag naar de sectie &quot;[!UICONTROL Enabled Visualforce Page Access]&quot;. Klik op **[!UICONTROL Edit]**.

1. Selecteer in de sectie &quot;[!UICONTROL Enabled Visualforce Pages]&quot; alle pagina&#39;s die met &quot;mkto_si&quot; beginnen. Dit zou tot 64 pagina&#39;s moeten optellen.

1. Klik op **[!UICONTROL Remove]** en vervolgens op **[!UICONTROL Save]** .

   ![](assets/remove-sales-insight-access-5.png)

1. Schuif omlaag naar de sectie &quot;[!UICONTROL Enabled Custom Setting Definitions Access]&quot;. Klik op **[!UICONTROL Edit]**.

1. Selecteer &quot;Marketo Sales Insight.mkto_si.Marketo Settings&quot; en &quot;Marketo Sales Insight.mkto_si.User Preferences&quot;.

1. Klik op **[!UICONTROL Remove]** en vervolgens op **[!UICONTROL Save]** .

   ![](assets/remove-sales-insight-access-6.png)

Dat is het! U hebt de toegang tot [!DNL Sales Insight] verwijderd. Herhaal dezelfde stappen voor elk ander profiel waarvoor u toegang wilt verwijderen.
