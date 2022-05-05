---
description: Stap 1 van 3 - voeg Marketo-velden toe aan Veeva CRM - Marketo Docs - Productdocumentatie
title: Stap 1 van 3 - Voeg Marketo-velden toe aan Veeva CRM
exl-id: a9a59e76-a7a4-4391-8169-922bd6acfb6d
source-git-commit: 2ce44b7c44517a6fdb3f616a3d69b25158ea4ec9
workflow-type: tm+mt
source-wordcount: '533'
ht-degree: 0%

---

# Stap 1 van 3: Marketo-velden toevoegen aan Veeva CRM {#step-1-of-3-add-marketo-fields-to-veeva-crm}

>[!PREREQUISITES]
>
>Uw Veeva CRM-instantie moet toegang hebben tot de Salesforce API&#39;s om gegevens te synchroniseren tussen Marketo Engage en Veeva CRM.

Marketo Engage gebruikt een reeks velden om bepaalde soorten marketinggerelateerde informatie vast te leggen. Volg onderstaande instructies als u deze gegevens in Veeva CRM wilt gebruiken.

`1.` Maak een aangepast veld in Veeva CRM op de contactobjecten: Score

`2.` U kunt desgewenst aanvullende velden maken (zie de tabel hieronder).

Al deze aangepaste velden zijn optioneel en zijn niet vereist voor het synchroniseren van Marketo Engage en Veeva CRM.

## Marketo-velden toevoegen aan Veeva CRM {#add-marketo-fields-to-veeva-crm}

Voeg drie aangepaste velden toe aan de lead- en contactobjecten in de bovenstaande lijst voor Veeva CRM. Zie de tabel met beschikbare velden aan het einde van deze sectie voor meer informatie.

Voer de volgende stappen voor het gebied van de Score uit om het toe te voegen.

1. Meld u aan bij de Veeva CRM en klik op **Instellen**.

   ![](assets/step-1-of-3-add-marketo-fields-1.png)

1. Klik op Objecten en velden en selecteer Objectbeheer.

   ![](assets/step-1-of-3-add-marketo-fields-2.png)

1. Zoek in de zoekbalk naar Contactpersoon.

   ![](assets/step-1-of-3-add-marketo-fields-3.png)

1. Klik op het object Contact.

1. Selecteer Velden en relaties.

1. Klikken **Nieuw**.

   ![](assets/step-1-of-3-add-marketo-fields-4.png)

1. Kies het juiste veldtype (voor Score — getal).

   ![](assets/step-1-of-3-add-marketo-fields-5.png)

1. Klikken **Volgende**.

   ![](assets/step-1-of-3-add-marketo-fields-6.png)

1. Voer het veldlabel, de lengte en de veldnaam voor het veld in, zoals in de onderstaande tabel wordt weergegeven.

<table>
 <tbody>
  <tr>
   <th>Veldlabel
   <th>Veldnaam
   <th>Gegevenstype
   <th>Veldkenmerken
  </tr>
  <tr>
   <td>Score</td>
   <td>mkto71_Lead_Score</td>
   <td>Getal</td>
   <td>Lengte 10<br/>
Decimalen 0</td>
  </tr>
 </tbody>
</table>

>[!NOTE]
>
>Veeva CRM voegt __c aan de Namen van het Gebied toe wanneer het hen gebruikt om API Namen tot stand te brengen.

![](assets/step-1-of-3-add-marketo-fields-7.png)

>[!NOTE]
>
>Tekst- en nummervelden vereisen een lengte, maar datum-/tijdvelden niet. Een beschrijving is optioneel.

1. Klikken **Volgende**.

   ![](assets/step-1-of-3-add-marketo-fields-8.png)

1. Geef de toegangsinstellingen op en klik op **Volgende**.

1. Stel alle rollen in op Zichtbaar en Alleen-lezen.

1. Schakel het selectievakje Alleen-lezen uit voor het profiel van de synchronisatiegebruiker:

* Als u een gebruiker hebt met het profiel van een systeembeheerder als synchronisatiegebruiker, schakelt u het selectievakje Alleen-lezen voor het beheerprofiel van het systeem uit (zoals hieronder wordt weergegeven).
* Als u een aangepast profiel voor de synchronisatiegebruiker hebt gemaakt, schakelt u het selectievakje Alleen-lezen voor dat aangepaste profiel uit.

   ![](assets/step-1-of-3-add-marketo-fields-9.png)

1. Kies de paginalay-outs die het veld moeten weergeven.

1. Klikken **Opslaan en nieuw** om terug te gaan en elk van de andere twee douanegebieden tot stand te brengen.

1. Klikken **Opslaan** als u klaar bent met alle drie.

   ![](assets/step-1-of-3-add-marketo-fields-10.png)

>[!NOTE]
>
>Door het veld aan het object Contact toe te voegen, worden deze ook toegevoegd aan de account van de persoon.

OPTIONEEL: Gebruik de bovenstaande procedure voor extra aangepaste velden uit de onderstaande tabel.

<table>
 <tbody>
  <tr>
   <th>Veldlabel
   <th>Veldnaam
   <th>Gegevenstype
   <th>Veldkenmerken
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
>Waarden in de velden die automatisch door Marketo worden toegewezen, zijn niet onmiddellijk beschikbaar in Veeva CRM wanneer het nieuwe veld is gemaakt. Marketo synchroniseert de gegevens met Veeva CRM bij de volgende update van de record op beide systemen (d.w.z. een update van een van de velden die synchroon is tussen Marketo en Veeva CRM).
