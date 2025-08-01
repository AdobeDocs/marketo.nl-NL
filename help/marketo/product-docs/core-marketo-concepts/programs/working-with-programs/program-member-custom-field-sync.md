---
description: Aangepaste veldsynchronisatie voor programmalid - Marketo Docs - Productdocumentatie
title: Aangepaste veldsynchronisatie voor programmalid
exl-id: 7facfc79-a411-4ad9-b847-2002763af5bb
feature: Programs
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '331'
ht-degree: 0%

---

# Aangepaste veldsynchronisatie voor programmalid {#program-member-custom-field-sync}

>[!PREREQUISITES]
>
>* Creatie van [ Gebieden van de Douane van het Lid van het Programma ](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-fields.md){target="_blank"}
>* [ Synchronisatie a  [!DNL Salesforce]  Campagne met een Programma ](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/sync-an-sfdc-campaign-with-a-program.md){target="_blank"}

>[!NOTE]
>
>Het programmalidobject kan maximaal 20 aangepaste velden hebben. Deze velden zijn beschikbaar voor elk programma.

## Salesforce-velden toewijzen aan aangepaste velden voor programmalid {#map-salesforce-fields-to-program-member-custom-fields}

1. Klik in Marketo op **[!UICONTROL Admin]** .

   ![](assets/program-member-custom-field-sync-1.png)

1. Klik op **[!DNL Salesforce]** en klik vervolgens op **[!UICONTROL Edit]** naast Aangepaste veldsync voor programmalid.

   ![](assets/program-member-custom-field-sync-2.png)

1. Gebruik het zoekvak om de [!DNL Salesforce] -velden te zoeken die u wilt toewijzen. In dit voorbeeld gebruiken we Niet bellen.

   ![](assets/program-member-custom-field-sync-3.png)

1. Klik op de vervolgkeuzelijst.

   ![](assets/program-member-custom-field-sync-4.png)

1. Kies de gewenste Marketo [!UICONTROL Program Member Custom Field] die u wilt toewijzen.

   ![](assets/program-member-custom-field-sync-5.png)

   >[!NOTE]
   >
   >In de vervolgkeuzelijst wordt alleen [!UICONTROL Program Member Custom Fields] weergegeven die overeenkomt met het gegevenstype van het veld [!DNL Salesforce] .

1. Voor extra veldtoewijzingen wist u het zoekvak en herhaalt u stap 3 tot en met 5.

1. Klik op **[!UICONTROL Save]** als u klaar bent.

   ![](assets/program-member-custom-field-sync-6.png)

   >[!IMPORTANT]
   >
   >Wijzigingen in de gegevens van de programmaleden in de toegewezen velden worden gesynchroniseerd tussen Marketo en [!DNL Salesforce] .

   >[!NOTE]
   >
   >Als u de naam van een veld wijzigt of het gegevenstype van een veld wijzigt in [!DNL Salesforce] , wordt elke toewijzing van dat veld verwijderd met de instructie [!UICONTROL Program Member Custom Field] . Maar u kunt deze na revisie opnieuw toewijzen met het nieuwe veld.

## De kaart van Salesforce-velden van aangepaste velden voor programmaleden opheffen {#unmap-salesforce-fields-from-program-member-custom-fields}

Als u een veld ooit wilt vrijmaken om het te vervangen of als u alleen een algemene wijziging wilt aanbrengen, moet u eerst een unmapping uitvoeren. Zo gaat het.

1. Klik in Marketo op **[!UICONTROL Admin]** .

   ![](assets/program-member-custom-field-sync-7.png)

1. Klik op **[!DNL Salesforce]** en klik vervolgens op **[!UICONTROL Edit]** naast Aangepaste veldsync voor programmalid.

   ![](assets/program-member-custom-field-sync-8.png)

1. Gebruik het zoekvak om te zoeken naar de velden waarvan u de toewijzing ongedaan wilt maken. In dit voorbeeld gebruiken we Niet bellen.

   ![](assets/program-member-custom-field-sync-9.png)

   >[!TIP]
   >
   >U kunt het selectievakje **[!UICONTROL Mapped]** inschakelen om alleen toegewezen velden weer te geven.

1. Unmap door **X** naast het gebied te klikken.

   ![](assets/program-member-custom-field-sync-10.png)

1. De toewijzing is nu verwijderd. Klik op **[!UICONTROL Save]**.

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
>* [ Gegevens van het Lid van het Programma van de Verandering ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-member-data.md){target="_blank"}
>* [ gegevens van de Mening over het net van het Lid van het Programma ](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/manage-and-view-members.md){target="_blank"}
>* [ de Synchronisatie van SFDC - de Synchronisatie van de Campagne ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-campaign-sync.md){target="_blank"}
