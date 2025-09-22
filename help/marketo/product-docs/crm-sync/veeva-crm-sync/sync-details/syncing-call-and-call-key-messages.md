---
description: Het synchroniseren van Vraag en de Zeer belangrijke Berichten van de Vraag - de Documenten van Marketo - de Documentatie van het Product
title: Het synchroniseren van Vraag en Vraag Zeer belangrijke Berichten
exl-id: a8df5b77-e594-4e06-8194-1758a3582cda
feature: Veeva CRM
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '477'
ht-degree: 0%

---

# Het synchroniseren van Vraag en Vraag Zeer belangrijke Berichten {#syncing-call-and-call-key-messages}

De Vraag en de Zeer belangrijke Voorwerpen van het Bericht van de Vraag in [!DNL Veeva] CRM worden gesynchroniseerd door gebrek in Marketo Engage. Marketo synchroniseert gegevens die tot 6 maanden oud zijn, gebaseerd op Vraag Gemaakt Datum.

>[!NOTE]
>
>Marketo behoudt vraaggegevens tot zes maanden vanaf de datum van de Vraag.

**wat zijn de trekkers/de filters met betrekking tot Vraag en het Zeer belangrijke Bericht van de Vraag?**

Triggers:

* Toegevoegd aan Vraag
* Verwijderd uit Vraag
* Toegevoegd aan het Zeer belangrijke Bericht van de Vraag
* Verwijderd uit Zeer belangrijk Bericht van de Vraag
* Bijgewerkte Vraag
* Bijgewerkt Zeer belangrijk Bericht van de Vraag

Filters:

* Heeft oproep
* Heeft Bericht met oproepsleutel

De volgende gebieden op Vraag en de Zeer belangrijke berichten van de Vraag worden gesynchroniseerd en kunnen als beperkingen en trekkers worden gebruikt.

<table>
  <colgroup>
    <col>
    <col>
    <col>
    <col>
    <col>
  </colgroup>
  <thead>
    <tr>
      <th>
        Object
      </th>
      <th>
        Veldlabel
      </th>
      <th>
        Beschrijving
      </th>
      <th>
        Veldnaam
      </th>
      <th>
        Gegevenstype
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Bellen</td>
      <td>Accountant</td>
      <td>Lookup aan de rekening waaraan de vraag wordt geassocieerd.</td>
      <td>Account_vod_c</td>
      <td>Opzoeken (account)</td>
    </tr>
    <tr>
      <td>Bellen</td>
      <td>Type oproep</td>
      <td>Type van vraag die systeem wordt gehandhaafd gebaseerd op het type en de inhoud van de vraag. Dit veld wordt gebruikt voor rapportagedoeleinden. Geldige waarden zijn: Alleen detail, Details met voorbeeld, Groepdetails, Groepdetails met voorbeeld, Alleen voorbeeld. Deze waarden moeten niet worden gewijzigd, maar de vertalingen voor deze picklists kunnen worden gewijzigd. De aanwezigen hebben het zelfde vraagtype zoals de kopbalvraag. Voor een vraag van de Groep met 3 beroeps, hebben alle 4 verslagen het vraagtype van "het Detail van de Groep"</td>
      <td>Call_Type_vod_c</td>
      <td>Picklist</td>
    </tr>
    <tr>
     <td>Bellen</td>
      <td>Contact</td>
      <td>Lookup aan het contact (als om het even welk) dat de vraag met wordt geassocieerd.</td>
      <td>Contact_vod_c</td>
      <td>Opzoeken (contactpersoon)</td>
    </tr>
    <tr>
      <td>Bellen</td>
      <td>Datum</td>
      <td>De datum van de vraag toen het voor het eerst werd bewaard of werd voorgelegd. Dit veld wordt met een trigger ingesteld op de huidige datum als noch de datum, noch het datetime-veld wordt opgegeven.</td>
      <td>Call_Date_vod_c</td>
      <td>Datum</td>
    </tr>
    <tr>
      <td>Bellen</td>
      <td>Is de Ouderlijke Vraag?</td>
      <td>Het Gebied van de formule om te bepalen als het verslag van de Vraag de Ouderlijke Vraag of een verslag van de Vraag van de Deelnemer is. 1 wijst erop dat het verslag de Ouderlijke Vraag is. 0 wijst erop dat het een Vraag van de Deelnemer is.</td>
      <td>Is_Parent_Call_vod_c</td>
      <td>Formule (getal)</td>
    </tr>
    <tr>
      <td>Bellen</td>
      <td>Status</td>
      <td>Status van de oproep — Gepland, Opgeslagen of Verzonden. Gebruik de vertaalwerkbank om de weergavewaarden te wijzigen. De trekkers op vraag kijken naar dit gebied om te zien of de vraag (voorgelegd) gesloten is. Deze waarde wordt ingesteld voor de gebruiker wanneer op de knop Opslaan of Verzenden wordt gedrukt.</td>
      <td>Status_vod_c</td>
      <td>Picklist</td>
    </tr>
    <tr>
      <td>Bellen</td>
      <td>Recordtype</td>
      <td> </td>
      <td>RecordTypeId</td>
      <td>Recordtype</td>
    </tr>
    <tr>
      <td>Bericht met oproepsleutel</td>
      <td>Bellen</td>
      <td>Opzoeken naar de oproep. Elk zeer belangrijk bericht wordt geassocieerd met een vraag.</td>
      <td>Call2_vod__c</td>
      <td>Hoofd-Detail (Vraag)</td>
    </tr>
    <tr>
      <td>Bericht met oproepsleutel</td>
      <td>Categorie</td>
      <td>Registreert de berichtcategorie van het bericht. Wordt voornamelijk gebruikt voor rapportage.</td>
      <td>Categorie_vod__c</td>
      <td>Picklist</td>
    </tr>
    <tr>
      <td>Bericht met oproepsleutel</td>
      <td>CLM-presentatienaam</td>
      <td>Gestempelde CLM-presentatienaam</td>
      <td>Clm_Presentation_Name_vod_c</td>
      <td>Tekst (80)</td>
    </tr>
    <tr>
      <td>Bericht met oproepsleutel</td>
      <td>Naam van sleutelbericht</td>
      <td>Berichtnaam stempelsleutel</td>
      <td>Key_Message_Name_vod_c</td>
      <td>Tekst (80)</td>
    </tr>
    <tr>
      <td>Bericht met oproepsleutel</td>
      <td>Productnaam</td>
      <td> </td>
      <td>Product_Naam__c</td>
      <td>Formule (tekst)</td>
    </tr>
    <tr>
      <td>Bericht met oproepsleutel</td>
      <td>Reactie </a>
      </td>
      <td>Picklist van reactie op het bericht. Bewerk de keuzelijst om de reactiewaarden te wijzigen.</td>
      <td>Reactie_vod__c</td>
      <td>Picklist</td>
    </tr>
  </tbody>
</table>
