---
unique-page-id: 12615800
description: Benoemde accounts importeren - Marketo Docs - Productdocumentatie
title: Benoemde accounts importeren
translation-type: tm+mt
source-git-commit: 9f88e7cebc5e9d0d4491d65d332ccfdd9a31c395
workflow-type: tm+mt
source-wordcount: '479'
ht-degree: 0%

---


# Benoemde accounts {#import-named-accounts} importeren

Beschikt de CSV al over een volledig overzicht van de potentiële doelrekeningen? Importeer ze rechtstreeks in TAM!

1. Klik op de vervolgkeuzelijst **Nieuw** en selecteer **Benoemde accounts importeren**.

   ![](assets/inaone.png)

1. Er wordt een nieuw venster geopend. Klik **Bladeren**, dan selecteer het dossier van genoemde rekeningen u wilt invoeren.

   ![](assets/inatwo.png)

   >[!TIP]
   >
   >Geef in uw bestand [zoveel mogelijk informatie](/help/marketo/product-docs/target-account-management/target/named-accounts/named-account-overview.md#named-account-attributes) op. U kunt alleen cursieve gegevens toevoegen. niets Marketo berekent (d.w.z. Pipeline). Als u benoemde accounts wilt maken op basis van CRM-accounts, exporteert u gewoon de naam van de account en de CRM-id van uw CRM naar een CSV-bestand, gebruikt u de optie Accountnaam en wijst u de CRM-id toe tijdens het importproces. Om een rekening van CRM aan een genoemde rekening behoorlijk te verbinden, moet u de nauwkeurige naam van de rekening verstrekken CRM.

1. U kunt kiezen uit twee deduplicatiemodi: Accountnaam of domeinnaam. In dit voorbeeld kiezen we Account. Klik op de vervolgkeuzelijst **Modi** en selecteer **Op accountnaam**.

   ![](assets/inathree.png)

   >[!NOTE]
   >
   >Als u **Op de Wijze van het Domein** kiest, zowel moeten de genoemde rekening als de domeingebieden worden omvat.

1. Klik op de vervolgkeuzelijst **Accountlijst** en maak uw selectie om aan te geven aan welke account u een accountlijst wilt toevoegen.

   ![](assets/inafour.png)

   >[!NOTE]
   >
   >U kunt ook een gloednieuwe accountlijst maken door de naam ervan in de keuzelijst te typen.

1. Als u een bericht over het importeren wilt verzenden, klikt u op de vervolgkeuzelijst **Waarschuwing verzenden naar** en selecteert u een gebruiker van Marketo. U _kunt niet_ manueel een e-mailadres ingaan.

   ![](assets/inafive-2.png)

1. Klik **Volgende**.

   ![](assets/inasix-2.png)

1. Wijs elk veld toe door te dubbelklikken op het vervolgkeuzemenu **Marketo-veld** en het desbetreffende veld te selecteren. Klik **Volgende** wanneer gereed.

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
>Wanneer Marketo een benoemde account toevoegt, wordt (achter de schermen) een regel bijgewerkt waarmee we personen kunnen identificeren die deel moeten uitmaken van de benoemde account. Voorbeeld: als u &quot;IBM&quot; bijwerkt naar &quot;IBM, USA&quot;, worden personen met een van beide bedrijfsnaam aan de Named Account gekoppeld.

Als Marketo records vindt die we als duplicaten zien, verwerken we alleen de eerste.
