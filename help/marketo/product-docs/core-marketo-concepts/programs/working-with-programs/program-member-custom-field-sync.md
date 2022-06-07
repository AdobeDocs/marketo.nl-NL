---
description: Aangepaste velden voor programmalid - Marketo Docs - Productdocumentatie
title: Aangepaste velden voor programmalid
hide: true
hidefromtoc: true
source-git-commit: 09e9ee74c32f81fdc826454266d3e16826a09eae
workflow-type: tm+mt
source-wordcount: '348'
ht-degree: 0%

---

# Aangepaste veldsynchronisatie voor programmalid {#program-member-custom-field-sync}

>[!PREREQUISITES]
>
>Aanmaken van [Aangepaste velden voor programmalid](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-fields.md){target=&quot;_blank&quot;}

>[!NOTE]
>
>Het programmalidobject kan maximaal 20 aangepaste velden hebben. Deze velden zijn beschikbaar voor elk programma.

## Salesforce-velden toewijzen aan aangepaste velden voor programmalid {#map-salesforce-fields-to-program-member-custom-fields}

1. Klik in Marketo op **Beheer**.

   ![](assets/program-member-custom-field-sync-1.png)

1. Klikken **Salesforce** en klik vervolgens op **Bewerken** naast Aangepaste veldsync voor programmalid.

   ![](assets/program-member-custom-field-sync-2.png)

1. Gebruik het zoekvak om de Salesforce-velden te zoeken die u wilt toewijzen. In dit voorbeeld gebruiken we Niet bellen.

   ![](assets/program-member-custom-field-sync-3.png)

1. Klik op de vervolgkeuzelijst.

   ![](assets/program-member-custom-field-sync-4.png)

1. Kies het gewenste aangepaste veld voor Marketo-programmalid dat u wilt toewijzen.

   ![](assets/program-member-custom-field-sync-5.png)

   >[!NOTE]
   >
   >De drop-down zal slechts de Gebieden van de Douane van het Lid van het Programma tonen die het gegevenstype van het gebied Salesforce aanpassen.

1. Voor extra veldtoewijzingen wist u het zoekvak en herhaalt u stap 3 tot en met 5.

1. Klikken **Opslaan** wanneer gereed.

   ![](assets/program-member-custom-field-sync-6.png)

   >[!IMPORTANT]
   >
   >Wijzigingen in de gegevens van de programmaleden in de toegewezen velden worden gesynchroniseerd tussen Marketo en Salesforce.

   >[!NOTE]
   >
   >Als u het gegevenstype van een gebied in Salesforce anders noemt of verandert, zullen wij om het even welke afbeelding van dat gebied met het Gepaste Gebied van het Lid van het Programma verwijderen. U kunt de toewijzing echter na revisie opnieuw toewijzen met het nieuwe veld.

## Salesforce-velden uit aangepaste velden voor programmalid verwijderen {#unmap-salesforce-fields-from-program-member-custom-fields}

Als u een veld ooit wilt vrijmaken om het te vervangen of als u alleen een algemene wijziging wilt aanbrengen, moet u eerst een unmapping uitvoeren. Zo gaat het.

1. Klik in Marketo op **Beheer**.

   ![](assets/program-member-custom-field-sync-7.png)

1. Klikken **Salesforce** en klik vervolgens op **Bewerken** naast Aangepaste veldsync voor programmalid.

   ![](assets/program-member-custom-field-sync-8.png)

1. Gebruik het zoekvak om te zoeken naar de velden waarvan u de toewijzing ongedaan wilt maken. In dit voorbeeld gebruiken we Niet bellen.

   ![](assets/program-member-custom-field-sync-9.png)

   >[!TIP]
   >
   >U kunt de **Toegewezen** Schakel het selectievakje in om alleen toegewezen velden weer te geven.

1. Toewijzing ongedaan maken door op de knop **X** naast het veld.

   ![](assets/program-member-custom-field-sync-10.png)

1. De toewijzing is nu verwijderd. Klikken **Opslaan**.

   ![](assets/program-member-custom-field-sync-11.png)

## Gegevenstypetoewijzing {#data-type-mapping}

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>SFDC-gegevenstype</th>
      <th>Aangepast veldgegevenstype voor programmalid</th>
    </tr>
    <tr>
      <td>Tekst</td>
      <td>String</td>
    </tr>
    <tr>
      <td>Picklist</td>
      <td>String</td>
    </tr>
    <tr>
      <td>Multi-select Picklist</td>
      <td>String</td>
    </tr>
    <tr>
      <td>Telefoonnummer</td>
      <td>String</td>
    </tr>
    <tr>
      <td>E-mail</td>
      <td>String</td>
    </tr>
    <tr>
      <td>Nummer(m)</td>
      <td>Geheel</td>
    </tr>
    <tr>
      <td>Getal (m,n)</td>
      <td>Float</td>
    </tr>
    <tr>
      <td>Selectievakje</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td>URL</td>
      <td>URL</td>
    </tr>
    <tr>
      <td>Datum</td>
      <td>Datum</td>
    </tr>
    <tr>
      <td>Datumtijd</td>
      <td>Datumtijd</td>
    </tr>
    <tr>
      <td>Opzoeken (referentie)</td>
      <td>String</td>
    </tr>
    <tr>
      <td>Base64</td>
      <td>String</td>
    </tr>
  </tbody>
</table>

>[!MORELIKETHIS]
>
>* [Gegevens van programmalid wijzigen](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-member-data.md){target=&quot;_blank&quot;}
>* [Gegevens weergeven op het raster voor programmaleden](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/manage-and-view-members.md){target=&quot;_blank&quot;}

