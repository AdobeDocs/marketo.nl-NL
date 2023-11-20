---
unique-page-id: 11372975
description: Stap 1 van 3 - voeg Marketo-velden toe aan Salesforce (Professional) - Marketo Docs - Productdocumentatie
title: Stap 1 van 3 - voeg de Gebieden van Marketo aan Salesforce (Beroeps) toe
exl-id: 1b52825e-201d-4b55-8edf-444b1653d591
feature: Salesforce Integration
source-git-commit: 756a38ba87dd5af9ee783e9709056d444d4f415b
workflow-type: tm+mt
source-wordcount: '754'
ht-degree: 1%

---

# Stap 1 van 3: Voeg Marketo-velden toe aan Salesforce (Professional) {#step-of-add-marketo-fields-to-salesforce-professional}

>[!PREREQUISITES]
>
>Uw Salesforce-instantie moet toegang hebben tot de Salesforce API&#39;s om gegevens te synchroniseren tussen Marketo Engage en Salesforce.

Marketo gebruikt een set velden om bepaalde soorten marketinggerelateerde informatie vast te leggen. Volg onderstaande instructies als u deze gegevens in Salesforce wilt bewaren.

1. Maak drie aangepaste velden in Salesforce voor de lead- en contactobjecten: Score, Acquisition Program en Acquisition Date.
1. Wijs deze douanevelden tussen lood en contacten toe zodat bij omzetting in Salesforce, de waarden zich overbrengen.
1. U kunt desgewenst andere aanvullende velden maken (zie de tabel hieronder).

Al deze aangepaste velden zijn optioneel en zijn niet vereist voor synchronisatie tussen Marketo en Salesforce. Als beste praktijken, adviseren wij dat u gebieden voor Score, het Programma van de Aankoop, en de Datum van de Aankoop creeert.

## Marketo-velden toevoegen aan Salesforce {#add-marketo-fields-to-salesforce}

Voeg drie aangepaste velden toe aan de lead- en contactobjecten in de bovenstaande Salesforce-lijst. Zie de tabel met beschikbare velden aan het einde van deze sectie voor meer informatie.

Voer de volgende stappen uit voor elk van de drie aangepaste velden om deze toe te voegen. Beginnen met **[!UICONTROL Score]**.

1. Log in bij Salesforce en klik op **[!UICONTROL Setup]**.

   ![](assets/image2016-5-23-13-3a15-3a21.png)

1. Klik in het menu Build aan de linkerkant op **[!UICONTROL Customize]** en selecteert u **[!UICONTROL Leads]**. Klik op **[!UICONTROL Fields]**.

   ![](assets/image2016-5-23-13-3a20-3a5.png)

1. Klikken **[!UICONTROL New]** in de sectie Aangepaste velden en relaties onder aan de pagina.

   ![](assets/image2016-5-26-14-3a41-3a40.png)

1. Kies het juiste veldtype (voor Score - **[!UICONTROL number]**; overnameprogramma - **[!UICONTROL text]**; overnamedatum - **Datum/tijd**).

   ![](assets/choose-field-type-2-hand.png)

1. Klik op **[!UICONTROL Next]**.

   ![](assets/image2016-5-26-14-3a51-3a14.png)

1. Voer het veldlabel, de lengte en de veldnaam voor het veld in, zoals in de onderstaande tabel wordt weergegeven.

<table> 
 <thead> 
  <tr> 
   <th> 
    <div>
      Veldlabel 
    </div></th> 
   <th> 
    <div>
      Veldnaam 
    </div></th> 
   <th> 
    <div>
      Gegevenstype 
    </div></th> 
   <th> 
    <div>
      Veldkenmerken 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td>Score</td> 
   <td>mkto71_Lead_Score</td> 
   <td>Getal</td> 
   <td>Lengte 10<br>Decimalen 0 </td> 
  </tr> 
  <tr> 
   <td>Aankoopdatum</td> 
   <td>mkto71_Acquisition_Date</td> 
   <td>Datum/tijd</td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td>Overnameprogramma</td> 
   <td>mkto71_Acquisition_Program</td> 
   <td>Tekst</td> 
   <td>Lengte 255</td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>Salesforce voegt __c aan de Namen van het Gebied toe wanneer het hen gebruikt om API Namen tot stand te brengen.

![](assets/image2016-5-26-14-3a55-3a33.png)

>[!NOTE]
>
>Tekst- en nummervelden vereisen een lengte, maar datum-/tijdvelden niet. Een beschrijving is optioneel.

1. Klik op **[!UICONTROL Next]**.

   ![](assets/image2016-5-23-14-3a50-3a5.png)

1. Geef de toegangsinstellingen op en klik op **[!UICONTROL Next]**:

   * Alle rollen instellen op **[!UICONTROL Visible]** en **[!UICONTROL Read-Only]**

   * Wis de **[!UICONTROL Read-Only]** selectievakje voor het profiel van uw synchronisatiegebruiker:

      * Als u een gebruiker met het profiel van een _Systeembeheerder_ als synchronisatiegebruiker, ontruim **[!UICONTROL Read-Only]** selectievakje voor het profiel Systeembeheerder (zoals hieronder weergegeven)

      * Als u een _aangepast profiel_ voor de synchronisatiegebruiker, ontruim **[!UICONTROL Read-Only]** selectievakje voor dat aangepaste profiel

   ![](assets/image2016-6-30-9-3a25-3a4.png)

1. Kies de paginalay-outs die het veld moeten weergeven.

   ![](assets/image2016-5-26-15-3a14-3a45.png)

1. Klikken **[!UICONTROL Save & New]** om terug te gaan en elk van de andere twee douanegebieden tot stand te brengen. Klikken **[!UICONTROL Save]** samen met jullie zijn alle drie klaar.

   ![](assets/image2016-5-23-15-3a8-3a43.png)

1. Klik in het menu Build aan de linkerkant op **[!UICONTROL Customize]** en selecteert u **[!UICONTROL Contacts]**. Klik op **[!UICONTROL Fields]**.
1. Voer stap 3 door 10 voor de gebieden van de Score, van de Verwervingsdatum, en van het Programma van de Verwerving op het contactvoorwerp uit, enkel zoals u voor het loodvoorwerp deed.
1. U kunt de bovenstaande procedure ook gebruiken voor extra aangepaste velden uit deze tabel.

<table> 
 <tbody> 
  <tr> 
   <th>Veldlabel</th> 
   <th>Veldnaam</th> 
   <th>Gegevenstype</th> 
   <th>Veldkenmerken</th> 
  </tr> 
  <tr> 
   <td>Id van overnameprogramma</td> 
   <td>mkto71_Acquisition_Program_Id</td> 
   <td>Getal</td> 
   <td>Lengte 18<br>Decimalen 0 </td> 
  </tr> 
  <tr> 
   <td>Oorspronkelijke verwijzing</td> 
   <td>mkto71_Original_Referrer</td> 
   <td>Tekst</td> 
   <td>Lengte 255</td> 
  </tr> 
  <tr> 
   <td>Originele zoekengine</td> 
   <td>mkto71_Original_Search_Engine</td> 
   <td>Tekst</td> 
   <td>Lengte 255</td> 
  </tr> 
  <tr> 
   <td>Oorspronkelijke zoekterm</td> 
   <td>mkto71_Original_Search_Phrase</td> 
   <td>Tekst</td> 
   <td>Lengte 255</td> 
  </tr> 
  <tr> 
   <td>Originele broninformatie</td> 
   <td>mkto71_Original_Source_Info</td> 
   <td>Tekst</td> 
   <td>Lengte 255</td> 
  </tr> 
  <tr> 
   <td>Oorspronkelijk brontype</td> 
   <td>mkto71_Original_Source_Type</td> 
   <td>Tekst</td> 
   <td>Lengte 255</td> 
  </tr> 
  <tr> 
   <td>Overgenomen stad</td> 
   <td>mkto71_Inferred_City</td> 
   <td>Tekst</td> 
   <td>Lengte 255</td> 
  </tr> 
  <tr> 
   <td>Afgeleid bedrijf</td> 
   <td>mkto71_Inferred_Company</td> 
   <td>Tekst</td> 
   <td>Lengte 255</td> 
  </tr> 
  <tr> 
   <td>Afgeleid land</td> 
   <td>mkto71_Inferred_Country</td> 
   <td>Tekst</td> 
   <td>Lengte 255</td> 
  </tr> 
  <tr> 
   <td>Overgenomen metropolitaans gebied</td> 
   <td>mkto71_Inferred_Metropolitan_Area</td> 
   <td>Tekst</td> 
   <td>Lengte 255</td> 
  </tr> 
  <tr> 
   <td>Gebiedscode afgeleide telefoon</td> 
   <td>mkto71_Inferred_Phone_Area_Code</td> 
   <td>Tekst</td> 
   <td>Lengte 255</td> 
  </tr> 
  <tr> 
   <td>Postcode</td> 
   <td>mkto71_Inferred_Postal_Code</td> 
   <td>Tekst</td> 
   <td>Lengte 255</td> 
  </tr> 
  <tr> 
   <td>Gebied van de betrokken staat</td> 
   <td>mkto71_Inferred_State_Region</td> 
   <td>Tekst</td> 
   <td>Lengte 255</td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>Waarden in de velden die automatisch door Marketo worden toegewezen, zijn niet onmiddellijk beschikbaar in Salesforce wanneer het nieuwe veld is gemaakt. Marketo synchroniseert de gegevens met Salesforce bij de volgende update van de record op beide systemen (een update van een van de velden die synchroon is tussen Marketo en Salesforce).

## Aangepaste velden toewijzen voor conversies  {#map-custom-fields-for-conversions}

Een aangepast veld op het hoofdobject in Salesforce moet worden toegewezen aan een contactveld op het contactobject, zodat gegevens worden overgedragen wanneer een conversie plaatsvindt.

1. Klik in de rechterbovenhoek op **[!UICONTROL Setup]**.

   ![](assets/image2016-5-26-16-3a34-3a0.png)

1. Typ &quot;[!UICONTROL fields]&quot; in de zoekopdracht van Nav zonder op Enter te drukken. Velden worden onder verschillende objecten weergegeven. Klik **[!UICONTROL Fields]** onder Leads.

   ![](assets/image2016-5-26-16-3a36-3a32.png)

1. Ga naar de sectie Aangepaste velden en relaties voor lead en klik op **[!UICONTROL Map Lead Fields]**.

   ![](assets/image2016-5-26-16-3a39-3a29.png)

1. Klik op de vervolgkeuzelijst naast het veld dat u wilt toewijzen.

   ![](assets/image2016-5-26-16-3a49-3a53.png)

1. Selecteer het overeenkomende aangepaste veld voor de contactpersoon.

   ![](assets/image2016-5-26-16-3a56-3a23.png)

1. Herhaal bovenstaande stappen voor alle andere velden die u hebt gemaakt.

1. Klikken **[!UICONTROL Save]** als je klaar bent.

Gemakkelijk genoeg, toch?

>[!MORELIKETHIS]
>
>[Stap 2 van 3: Een Salesforce-gebruiker voor Marketo maken (Professional)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-2-of-3-create-a-salesforce-user-for-marketo-professional.md){target="_blank"}
