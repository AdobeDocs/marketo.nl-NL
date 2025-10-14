---
description: Insight-machtigingsset voor verkoop toevoegen - Marketo-documenten - productdocumentatie
title: Insight-machtigingsset voor verkoop toevoegen
exl-id: b93ddf2e-0f7b-41e0-ba88-7363f5e34970
feature: Marketo Sales Insights
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '335'
ht-degree: 1%

---

# [!DNL Sales Insight] Machtigingsset toevoegen {#add-sales-insight-permission-set}

Ga als volgt te werk om toegang toe te voegen tot [!DNL Sales Insight] -functies in [!DNL Salesforce] . Van toepassing op [!DNL Salesforce] Klassiek en Lightening

>[!PREREQUISITES]
>
>[&#x200B; werk uw  [!DNL Sales Insight] [!DNL Salesforce] pakket &#x200B;](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md){target="_blank"} aan versie 1.8000 of hoger bij om deze eigenschap te gebruiken.

>[!IMPORTANT]
>
>Als u eerder [!DNL Sales Insight] toegang tot alle profielen en/of uitgevoerd [!DNL Sales Insight] voor al uw gebruikers hebt gegeven, moet u [&#x200B; de toegang van het profielniveau &#x200B;](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/remove-sales-insight-access.md){target="_blank"} verwijderen om deze rechtenset te gebruiken.

## Overzicht {#overview}

De machtiging Marketo App maakt deel uit van het pakket [!DNL Sales Insight] [!DNL Salesforce] . Dit omvat toegang tot de hieronder vermelde objecten, apex-klassen en pagina&#39;s voor visuele kracht. Deze zijn vereist voor toegang tot alle functies van [!DNL Sales Insight] .

**de Montages van Objecten**

<table>
 <tbody>
 <tr>
   <td>BestBetsCache</td>
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td>
  </tr>
  <tr>
   <td>Gegevens beste biets</td>
   <td>Alles lezen, maken, bewerken, verwijderen, bekijken, wijzigen</td>
  </tr>
  <tr>
   <td>Weergaven beste ets</td>
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
   <td>Marketo [!DNL Sales Insight] Config</td>
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

## Marketo App Permission Set toevoegen aan gebruikers {#adding-marketo-app-permission-set-to-users}

1. Meld u aan bij uw [!DNL Salesforce] -account.

1. Klik op **[!UICONTROL Setup]**.

   ![](assets/add-sales-insight-permission-set-1.png)

1. Klik onder Beheerder om **[!UICONTROL Manage Users]** ongedaan te maken en klik vervolgens op **[!UICONTROL Users]** .

   ![](assets/add-sales-insight-permission-set-2.png)

1. Selecteer onder Alle gebruikers de gebruiker tot wie u toegang wilt verlenen en klik vervolgens op **[!UICONTROL Permission Set Assignments]** .

   ![](assets/add-sales-insight-permission-set-3.png)

1. Klik op **[!UICONTROL Edit Assignments]**.

   ![](assets/add-sales-insight-permission-set-4.png)

1. Selecteer **[!UICONTROL Marketo App Access]** uit de beschikbare rechtensets en vervolgens **[!UICONTROL Add]** . Klik op **[!UICONTROL Save]**.

   ![](assets/add-sales-insight-permission-set-5.png)

1. Wanneer u nu naar beneden schuift op de pagina Gebruikersdetails, ziet u &quot;Marketo App Access&quot; onder Toewijzingen machtigingsset.

   ![](assets/add-sales-insight-permission-set-6.png)

>[!NOTE]
>
>Gebruikers die geen toegang hebben tot [!DNL Sales Insight], krijgen het volgende bericht te zien: &quot;U hebt onvoldoende rechten om dit tabblad te openen.&quot;

Dat is het! U hebt [!DNL Sales Insight] -toegang toegevoegd. Herhaal dezelfde stappen voor elk ander profiel waarvoor u toegang wilt toevoegen.
