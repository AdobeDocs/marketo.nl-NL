---
unique-page-id: 12615800
description: Benoemde accounts importeren - Marketo Docs - Productdocumentatie
title: Benoemde accounts importeren
exl-id: 3f40e567-9256-4efd-beea-4e818770759f
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '479'
ht-degree: 0%

---

# Benoemde accounts importeren {#import-named-accounts}

Beschikt de CSV al over een volledig overzicht van de potentiële doelrekeningen? Importeer ze rechtstreeks in TAM!

1. Klik op de knop **Nieuw** vervolgkeuzelijst en selecteer **Benoemde accounts importeren**.

   ![](assets/inaone.png)

1. Er wordt een nieuw venster geopend. Klikken **Bladeren** Selecteer vervolgens het bestand met benoemde accounts die u wilt importeren.

   ![](assets/inatwo.png)

   >[!TIP]
   >
   >Geef in uw bestand de volgende gegevens op: [als](/help/marketo/product-docs/target-account-management/target/named-accounts/named-account-overview.md#named-account-attributes) zo mogelijk. U kunt alleen cursieve gegevens toevoegen. niets dat Marketo berekent (bijv. Pipeline). Als u benoemde accounts wilt maken op basis van CRM-accounts, exporteert u gewoon de naam van de account en de CRM-id van uw CRM naar een CSV-bestand, gebruikt u de optie Accountnaam en wijst u de CRM-id toe tijdens het importproces. Om een rekening van CRM aan een genoemde rekening behoorlijk te verbinden, moet u de nauwkeurige naam van de rekening verstrekken CRM.

1. U kunt kiezen uit twee deduplicatiemodi: Accountnaam of domeinnaam. In dit voorbeeld kiezen we Account. Klik op de knop **Modi** vervolgkeuzelijst en selecteer **Op accountnaam**.

   ![](assets/inathree.png)

   >[!NOTE]
   >
   >Als u **Op domeinmodus**, moeten zowel de benoemde account als de domeinvelden worden opgenomen.

1. Klik op de knop **Accountlijst** en maak uw selectie.

   ![](assets/inafour.png)

   >[!NOTE]
   >
   >U kunt ook een gloednieuwe accountlijst maken door de naam ervan in de keuzelijst te typen.

1. Als u een bericht over het importeren wilt verzenden, klikt u op de knop **Waarschuwing verzenden naar** en selecteer een Marketo-gebruiker. U _kan_ Voer handmatig een e-mailadres in.

   ![](assets/inafive-2.png)

1. Klikken **Volgende**.

   ![](assets/inasix-2.png)

1. Wijs elk veld toe door te dubbelklikken op het tabblad **Marketo-veld** vervolgkeuzelijst en het desbetreffende veld selecteren. Klikken **Volgende** wanneer gereed.

   ![](assets/inaseven.png)

   Succes!

   ![](assets/inanine.png)

   >[!NOTE]
   >
   >Met Importstatus controleren worden alleen de laatste drie dagen van de activiteit weergegeven.

Scenario&#39;s wanneer u door de Naam van de Rekening dedupliceert:

<table> 
 <tbody> 
  <tr> 
   <td><strong>Record met bestaande naam van benoemde account importeren</strong></td> 
   <td><p>De bestaande record wordt bijgewerkt</p></td> 
  </tr> 
  <tr> 
   <td><strong>Record met nieuwe naam van benoemde account importeren</strong></td> 
   <td>We maken een nieuw record</td> 
  </tr> 
 </tbody> 
</table>

Scenario&#39;s wanneer u door de Naam van het Domein dedupliceert:

<table> 
 <tbody> 
  <tr> 
   <td><strong>Record met een nieuwe accountnaam en een nieuwe domeinnaam importeren</strong></td> 
   <td>Er wordt een nieuwe account met de opgegeven gegevens gemaakt</td> 
  </tr> 
  <tr> 
   <td><strong>Record importeren met een bestaande accountnaam en bestaande domeinnaam</strong></td> 
   <td>We werken het bestaande benoemde account bij</td> 
  </tr> 
   <tr> 
   <td><strong>Record importeren met een nieuwe accountnaam en een bestaande domeinnaam</strong></td> 
   <td>We voegen de nieuwe accountnaam toe aan de bestaande benoemde account die overeenkomt met de domeinnaam en werken andere gegevens bij (bijv. industrie, staat, enz.)</td> 
  </tr> 
  <tr> 
   <td><strong>Record met bestaande naam van benoemde account en nieuwe domeinnaam importeren</strong></td> 
   <td>We voegen de nieuwe domeinnaam toe aan de bestaande benoemde account die overeenkomt met de accountnaam en werken andere gegevens bij (bijv. industrie, staat, enz.)</td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>Wanneer Marketo een account met een naam toevoegt, wordt een regel (achter de schermen) bijgewerkt waarmee we personen kunnen identificeren die deel moeten uitmaken van het account met de naam. Voorbeeld: als u &quot;IBM&quot; bijwerkt naar &quot;IBM, VS&quot;, worden personen met een van beide bedrijfsnaam gekoppeld aan het benoemde account.

Als Marketo records vindt die we als duplicaten zien, zullen we alleen de eerste verwerken.
