---
unique-page-id: 1147031
description: Persoon verwijderen uit SFDC - Marketo Docs - Productdocumentatie
title: Persoon verwijderen uit SFDC
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 0%

---


# Persoon verwijderen uit SFDC {#delete-person-from-sfdc}

Als u een specifieke reeks lood uit Salesforce moet verwijderen maar hen als mensen in Marketo verlaat, kunt u de Persoon van de Schrapping van SFDC stroomactie gebruiken.

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

>[!NOTE]
>
>Alleen beschikbaar bij integratie met Salesforce.

1. Klik in de database op de persoon die u uit Salesforce wilt verwijderen. Klik vervolgens op Handelingen **** persoon en selecteer **Salesforce**.

   ![](assets/person-actions-salesforce.png)

1. Selecteer Person **verwijderen uit SFDC**.

   ![](assets/delete-person-from-sfdc.png)

1. Zorg ervoor dat de instelling **Verwijderen in markeerteken** **false** is en klik vervolgens op **Nu** uitvoeren.

   ![](assets/run-action-delete-lead-from-sfdc.png)

   Na de looppas van de stroomstap, zal uw persoon niet meer een lood in Salesforce zijn maar zal in Marketo blijven.

   >[!CAUTION]
   >
   >Als u **Delete in Marketo** instelt op **true** en de mensen van Marketo en de leads van Salesforce verwijdert, zijn ze voor altijd verdwenen. Dit kan niet ongedaan worden gemaakt.

