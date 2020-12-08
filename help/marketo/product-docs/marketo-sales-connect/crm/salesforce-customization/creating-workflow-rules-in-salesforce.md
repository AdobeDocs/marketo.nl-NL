---
unique-page-id: 14745823
description: Workflowregels maken in Salesforce - Marketo Docs - Productdocumentatie
title: Workflowregels maken in Salesforce
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '470'
ht-degree: 0%

---


# Workflowregels maken in Salesforce {#creating-workflow-rules-in-salesforce}

Als tegelijkertijd Marketo Sales Insight (MSI) en Marketo Sales Connect (MSC) worden gebruikt, wordt de functie Best Bets van MSI in Salesforce niet bijgewerkt. Alle andere MSI-functies werken zoals gewoonlijk (interessante momenten in het iFrame weergeven, e-mail verzenden, aan campagnes toevoegen, enz.). Dit artikel biedt een oplossing om Best Bets weer te laten werken.

>[!NOTE]
>
>Dit beïnvloedt slechts klanten die **zowel** MSI als MSE gebruiken, en die de Beste eigenschap van Betten in MSI willen gebruiken. Als u geen Best Bets nodig hebt/gebruikt, kunt u dit negeren.

## Aan de slag {#getting-started}

De oplossing omvat het maken van nieuwe workflowregels om waarden van nieuwe MSE-velden te kopiëren naar de oude MSI-velden. U zult vier werkschemaregels voor het voorwerp van het Contact en de zelfde vier werkschemaregels voor het voorwerp van de Lood in uw eigen instantie moeten creëren Salesforce. Dit kan u vereisen om de Admin van CRM rechten (afhankelijk van uw rol en opstelling in CRM) te hebben.

Hieronder vindt u de aanbevolen namen van de workflowregels en een beschrijving van de workflowregels. Deze zijn van toepassing op het object Contact en lead:

<table> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td>Interessant momebeschrijving bijwerken</td> 
   <td><p>Kopiëren van: Last Marketo Engagement<br>DescCopy naar: Laatste interessante momentele beschrijving</p></td> 
  </tr> 
  <tr> 
   <td>Het veld Interessentype van moment bijwerken</td> 
   <td><p>Kopiëren van: Laatste<br>kopie marktobetrokkenheid bij: Type laatst interessant moment</p></td> 
  </tr> 
  <tr> 
   <td>Veld voor interessante momentenbron bijwerken</td> 
   <td><p>Kopiëren van: Last Marketo Engagement<br>SourceCopy to: Laatste interessante mompbron</p></td> 
  </tr> 
  <tr> 
   <td>Veld voor datum van interessant moment bijwerken</td> 
   <td><p>Kopiëren van: Laatste Marketo Engagement<br>DateCopy naar: Datum laatste interessant moment</p></td> 
  </tr> 
 </tbody> 
</table>

## Instructies {#instructions}

1. Nadat u op **Setup** hebt geklikt, zoekt u naar **Workflow** en selecteert u **Workflowregels**.

   ![](assets/one-1.png)

1. Selecteer **Nieuwe regel**.

   ![](assets/two-1.png)

1. Klik op de vervolgkeuzelijst Object en selecteer **Lead** en klik vervolgens op **Volgende**.

   ![](assets/three-1.png)

1. Voer &quot;Interessent-momentveld bijwerken&quot; in als naam voor de regel. Selecteer het **gemaakte keuzerondje en telkens wanneer het wordt bewerkt**. In de drop-down van de Criteria van de Regel evalueert de uitgezochte **formule tot waar**. Zoek naar en selecteer de ISCHANGED functie. Markeer vervolgens de standaardveldwaarde en klik op Veld **** invoegen.

   ![](assets/four-1.png)

1. Kies in het pop-upvenster Veld invoegen de optie **Laatste markering voor betrokkenheid bij** betrokkenheid en klik op **Invoegen**.

   ![](assets/five-1.png)

1. Klik op **Opslaan en Volgende**.

   ![](assets/6.png)

1. Selecteer in de vervolgkeuzelijst Workflowactie toevoegen de optie **Nieuwe veldupdate**.

   ![](assets/seven.png)

1. Voer in het veld Naam het veld &quot;Interesten momentbeschrijving bijwerken&quot; in (de unieke naam wordt automatisch gegenereerd). Kies in het veld Veld voor bijwerken de optie **Laatste interessante momentbeschrijving**. Selecteer een formule **gebruiken om een keuzerondje voor een nieuwe waarde** in te stellen en klik vervolgens op **Formule-editor** tonen.

   ![](assets/eight.png)

1. Klik op de knop Veld **** invoegen.

   ![](assets/9a.png)

1. Selecteer **Laatste markering voor betrokkenheid** en klik op **Invoegen**. Klik op de volgende pagina op **Opslaan**.

   ![](assets/nine.png)

1. Klik op **Gereed**.

   ![](assets/twelve.png)

1. Klik op **Activeren** om de workflowregel in te schakelen.

   ![](assets/thirteen.png)

   Na de laatste stap kunt u de workflowregel klonen voor de andere velden die worden vermeld in de sectie Aan de slag: Desc, Type, Bron, Datum. Nadat u de vier workflowregels in het object Contact hebt voltooid, herhaalt u hetzelfde voor het object Lead.

