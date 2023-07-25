---
unique-page-id: 14745823
description: Workflowregels maken in Salesforce - Marketo Docs - Productdocumentatie
title: Workflowregels maken in Salesforce
exl-id: 0cfce178-453b-4949-96aa-c327278a267d
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '470'
ht-degree: 0%

---

# Workflowregels maken in Salesforce {#creating-workflow-rules-in-salesforce}

Als tegelijkertijd Marketo Sales Insight (MSI) en Marketo Sales Connect (MSC) worden gebruikt, wordt de functie Best Bets voor MSI in Salesforce niet bijgewerkt. Alle andere MSI-functies werken zoals gewoonlijk (interessante momenten in het iFrame weergeven, e-mail verzenden, aan campagnes toevoegen, enz.). Dit artikel biedt een oplossing om Best Bets weer te laten werken.

>[!NOTE]
>
>Dit is alleen van invloed op klanten die **beide** MSI en MSE, en die de Beste eigenschap van Bets in MSI willen gebruiken. Als u geen Best Bets nodig hebt/gebruikt, kunt u dit negeren.

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
   <td><p>Kopiëren van: Laatste Marketo Engagement Desc<br>Kopiëren naar: Laatste interessante momentele beschrijving</p></td> 
  </tr> 
  <tr> 
   <td>Het veld Interessentype van moment bijwerken</td> 
   <td><p>Kopiëren van: Laatste Marketo-servicetype<br>Kopiëren naar: Type laatst interessant moment</p></td> 
  </tr> 
  <tr> 
   <td>Veld voor interessante momentenbron bijwerken</td> 
   <td><p>Kopiëren van: Laatste Marketo-betrokkenheidsbron<br>Kopiëren naar: Laatste interessante mompbron</p></td> 
  </tr> 
  <tr> 
   <td>Veld voor datum van interessant moment bijwerken</td> 
   <td><p>Kopiëren van: Laatste Marketo-betrokkenheidsdatum<br>Kopiëren naar: Datum laatste interessant moment</p></td> 
  </tr> 
 </tbody> 
</table>

## Instructies {#instructions}

1. Na klikken **Instellen**, zoeken naar **Workflow** en selecteert u **Workflowregels**.

   ![](assets/one-1.png)

1. Selecteren **Nieuwe regel**.

   ![](assets/two-1.png)

1. Klik op de vervolgkeuzelijst Object en selecteer **Lood** en klik vervolgens op **Volgende**.

   ![](assets/three-1.png)

1. Voer &quot;Interessent-momentveld bijwerken&quot; in als naam voor de regel. Het keuzerondje selecteren **en telkens wanneer deze wordt bewerkt**. Selecteer in de vervolgkeuzelijst Regelcriteria de optie **formule levert true op**. Zoek naar en selecteer de ISCHANGED functie. Markeer vervolgens de standaardwaarde van het veld en klik op **Veld invoegen**.

   ![](assets/four-1.png)

1. Kies in het pop-upvenster Veld invoegen de optie **Laatste Marketo Engagement Desc** en klik op **Invoegen**.

   ![](assets/five-1.png)

1. Klikken **Opslaan en volgende**.

   ![](assets/6.png)

1. Selecteer in de vervolgkeuzelijst Workflowactie toevoegen de optie **Nieuwe veldupdate**.

   ![](assets/seven.png)

1. Voer in het veld Naam het veld &quot;Interesten momentbeschrijving bijwerken&quot; in (de unieke naam wordt automatisch gegenereerd). Kies in het veld dat u wilt bijwerken in de vervolgkeuzelijst de optie **Laatste interessante momentele beschrijving**. Selecteer **Een formule gebruiken om een nieuwe waarde in te stellen** keuzerondje, klik vervolgens op **Formule-editor weergeven**.

   ![](assets/eight.png)

1. Klik op de knop **Veld invoegen** knop.

   ![](assets/9a.png)

1. Selecteren **Laatste Marketo Engagement Desc** en klik op **Invoegen**. Klik op de volgende pagina op **Opslaan**.

   ![](assets/nine.png)

1. Klikken **Gereed**.

   ![](assets/twelve.png)

1. Klikken **Activeren** om de workflowregel in te schakelen.

   ![](assets/thirteen.png)

   Na de laatste stap kunt u de workflowregel klonen voor de andere velden die worden vermeld in de sectie Aan de slag: Desc, Type, Bron, Datum. Nadat u de vier workflowregels in het object Contact hebt voltooid, herhaalt u hetzelfde voor het object Lead.
