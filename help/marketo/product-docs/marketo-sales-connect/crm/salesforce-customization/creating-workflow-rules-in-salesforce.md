---
unique-page-id: 14745823
description: Workflowregels maken in Salesforce - Marketo Docs - Productdocumentatie
title: Workflowregels maken in Salesforce
translation-type: tm+mt
source-git-commit: 1dd80b7de801df78ac7dde39002455063f9979b7
workflow-type: tm+mt
source-wordcount: '470'
ht-degree: 0%

---


# Workflowregels maken in Salesforce {#creating-workflow-rules-in-salesforce}

Als tegelijkertijd Marketo Sales Insight (MSI) en Marketo Sales Connect (MSC) worden gebruikt, wordt de functie Best Bets van MSI in Salesforce niet bijgewerkt. Alle andere MSI-functies werken zoals gewoonlijk (interessante momenten in het iFrame weergeven, e-mail verzenden, aan campagnes toevoegen, enz.). Dit artikel biedt een oplossing om Best Bets weer te laten werken.

>[!NOTE]
>
>Dit beïnvloedt slechts klanten die **zowel** MSI en MSE gebruiken, en die de Beste eigenschap van Bets in MSI willen gebruiken. Als u geen Best Bets nodig hebt/gebruikt, kunt u dit negeren.

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
   <td><p>Kopiëren van: Laatste markeerteken voor betrokkenheid<br>Kopiëren naar: Laatste interessante momentele beschrijving</p></td> 
  </tr> 
  <tr> 
   <td>Het veld Interessentype van moment bijwerken</td> 
   <td><p>Kopiëren van: Laatste type betrokkenheid markeerteken<br>Kopiëren naar: Type laatst interessant moment</p></td> 
  </tr> 
  <tr> 
   <td>Veld voor interessante momentenbron bijwerken</td> 
   <td><p>Kopiëren van: Laatste Marketo Engagement Source<br>Kopiëren naar: Laatste interessante mompbron</p></td> 
  </tr> 
  <tr> 
   <td>Veld voor datum van interessant moment bijwerken</td> 
   <td><p>Kopiëren van: Laatste datum van betrokkenheid marktoverzicht<br>Kopiëren naar: Datum laatste interessant moment</p></td> 
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

1. Voer &quot;Interessent-momentveld bijwerken&quot; in als naam voor de regel. Selecteer het gemaakte keuzerondje **en elke keer dat het wordt bewerkt**. Selecteer **formule in de vervolgkeuzelijst Regelcriteria om het resultaat waar te maken**. Zoek naar en selecteer de ISCHANGED functie. Markeer vervolgens de standaardwaarde van het veld en klik op **Veld invoegen**.

   ![](assets/four-1.png)

1. Kies **Laatste markering voor betrokkenheid bij aanbieding** in het pop-upmenu Veld invoegen en klik op **Invoegen**.

   ![](assets/five-1.png)

1. Klik **Opslaan &amp; Volgende**.

   ![](assets/6.png)

1. Selecteer **Nieuwe veldupdate** in de vervolgkeuzelijst Workflowactie toevoegen.

   ![](assets/seven.png)

1. Voer in het veld Naam het veld &quot;Interesten momentbeschrijving bijwerken&quot; in (de unieke naam wordt automatisch gegenereerd). Kies **Laatste interessante momentbeschrijving** in het veld voor bijwerken. Selecteer **Gebruik een formule om nieuwe waarde** radioknoop te plaatsen, dan klik **toon de Redacteur van de Formule**.

   ![](assets/eight.png)

1. Klik op de knop **Veld invoegen**.

   ![](assets/9a.png)

1. Selecteer **Laatste markeerteken voor betrokkenheid** en klik op **Invoegen**. Voor de volgende pagina, klik **sparen**.

   ![](assets/nine.png)

1. Klik **Done**.

   ![](assets/twelve.png)

1. Klik **Activeer** om de workflowregel in te schakelen.

   ![](assets/thirteen.png)

   Na de laatste stap kunt u de workflowregel klonen voor de andere velden die worden vermeld in de sectie Aan de slag: Desc, Type, Bron, Datum. Nadat u de vier workflowregels in het object Contact hebt voltooid, herhaalt u hetzelfde voor het object Lead.
