---
unique-page-id: 10093188
description: Marketo Custom Objects - Marketo Docs - Productdocumentatie
title: Aangepaste Marketo-objecten
exl-id: f18b1689-c7bc-4da0-8326-7b29733d527d
feature: Custom Objects
source-git-commit: 7fd4d4e12b348ad4d0d69cd3f62cf441eda258b8
workflow-type: tm+mt
source-wordcount: '689'
ht-degree: 0%

---

# Aangepaste Marketo-objecten {#understanding-marketo-custom-objects}

Gebruik aangepaste objecten om metrische gegevens bij te houden die specifiek zijn voor uw bedrijf.

>[!AVAILABILITY]
>
>Niet alle Marketo Engage-gebruikers hebben deze functionaliteit aangeschaft. Neem contact op met het Adobe-accountteam (uw accountmanager) voor meer informatie.

Gebruik aangepaste objecten als filters en triggers in slimme campagnes. Bijvoorbeeld:

* **Filter**: Verzend e-mails slechts aan eigenaars van een specifiek merk van het voertuig
* **Trekker**: verzend een e-mail wanneer een douanevoorwerp aan een persoon of een bedrijf wordt toegevoegd.

U kunt aangepaste objecten instellen in een een-op-een-relatie of een veel-op-veel-relatie. Bijvoorbeeld:

* **één-aan-vele**: Één persoon bezit verscheidene auto&#39;s
* **vele-aan-vele**: De veelvoudige studenten worden ingeschreven in veelvoudige cursussen van een cursuscatalogus

Een één-op-vele structuur gebruikt één enkel verbindingsgebied om het douanevoorwerp met een persoon of een bedrijf te verbinden.

Vele-aan-vele douanevoorwerpen gebruiken twee verbindingsgebieden, deel van een intermediair voorwerp. Eén koppelingsveld is verbonden met de persoon of het bedrijf en een ander veld is verbonden met het aangepaste object, zoals de cursuscatalogus. Dit tussenliggende object kan aanvullende aangepaste velden bevatten, zoals een cursusniveau of een aanwezigheidsdatum, waarin de aard van de verbinding nader wordt gedefinieerd.

>[!TIP]
>
>Importeer aangepaste objecten met gebruik van door komma&#39;s gescheiden waarden (CSV) in de gebruikersinterface om een gegevensvoorbeeld te testen en te valideren. Vervolgens uploadt u al uw bestanden met een API.

>[!CAUTION]
>
>U kunt aangepaste objecten niet herstellen, dus zorg dat u ze niet meer nodig hebt voordat u ze verwijdert.

## Aangepaste Marketo-objecten openen {#accessing-marketo-custom-objects}

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/understanding-marketo-custom-objects-1.png)

1. Klik op **[!UICONTROL Marketo Custom Objects]**.

   ![](assets/understanding-marketo-custom-objects-2.png)

1. In de weergave Aangepaste objecten van Marketo worden al uw aangepaste objecten rechts weergegeven, maar alleen de goedgekeurde objecten in het hoofdraster.

   ![](assets/understanding-marketo-custom-objects-3.png)

   >[!NOTE]
   >
   >In het raster worden de naam van het object, het aantal records, het aantal velden en de datum van de meest recente update weergegeven.

   >[!TIP]
   >
   >Marketo werkt deze velden automatisch bij, maar u kunt de weergave vernieuwen door op het pictogram in de kolom Records te klikken.

1. Klik op de objectnaam aan de rechterkant om de detailpagina te openen.

   ![](assets/understanding-marketo-custom-objects-4.png)

## Aangepaste objecten weergeven die zijn gekoppeld aan een persoon {#view-custom-objects-associated-to-a-person}

Nadat u de structuur van het douanevoorwerp hebt gecreeerd, wanneer u de specifieke gegevens van het douanevoorwerp uploadt, worden de douanevoorwerpen automatisch geassocieerd aan mensen in het gegevensbestand gebruikend het verbindingsgebied in het douanevoorwerp. U kunt informatie van het lusje [!UICONTROL Custom Objects] op de pagina van persoondetails bekijken.

1. Ga naar **[!UICONTROL Database]** .

   ![](assets/understanding-marketo-custom-objects-5.png)

1. Open de database en klik op de tab **[!UICONTROL People]** . Dubbelklik op de record voor een persoon die u aan een aangepast object hebt gekoppeld.

   ![](assets/understanding-marketo-custom-objects-6.png)

1. Klik op de pagina met persoonlijke details op de tab **[!UICONTROL Custom Objects]** . Selecteer het object in de vervolgkeuzelijst.

   ![](assets/understanding-marketo-custom-objects-7.png)

1. Nu kunt u een lijst weergeven van alle aangepaste objecten van dat type die aan die persoon zijn gekoppeld.

   ![](assets/understanding-marketo-custom-objects-8.png)

   >[!NOTE]
   >
   >In een persoonrecord kan op het tabblad Aangepast object maximaal 100 records worden weergegeven, gesorteerd op ID in aflopende volgorde.

## Aangepaste objecten gebruiken met bedrijven {#using-custom-objects-with-companies}

Een douanevoorwerp dat met het bedrijf verbonden is werkt het best als u bedrijven van CRM synchroniseert of als u uitdrukkelijk bedrijven creeert gebruikend API. Wij adviseren ook dat u identiteitskaart van het Bedrijf als verbindingsgebied gebruikt.

Als u veelvoudige mensen in Marketo hebt die verslagen in CRM of Marketo-slechts verslagen zijn, zal een douanevoorwerp verbonden aan een bedrijf niet met meer dan één individueel verslag worden geassocieerd. Dit komt omdat een bedrijf met veelvoudige mensen eronder het wordt gesteund slechts wanneer de bedrijven van CRM worden gesynchroniseerd of als u een API gebruikt om bedrijven uitdrukkelijk tot stand te brengen.

Aangepaste objecten kunnen alleen rechtstreeks aan één record worden gekoppeld. Dit betekent dat wanneer uw type van douaneobjecten door bedrijfgebied wordt verbonden, u zou moeten ervoor zorgen dat uw persoonverslagen aan een bedrijf of gebruikend contactomzetting in uw CRM worden geassocieerd, of gebruikend het externalCompanyId gebied, als u bedrijven beheert die REST APIs van Marketo gebruiken. Voor persoonrecords die niet expliciet aan bedrijfsrecords zijn gekoppeld, worden aangepaste objecten die met bedrijf zijn gekoppeld, willekeurig gekoppeld aan één record, zelfs als de waarde van het bedrijfsveld door veel personen wordt gedeeld.

Zie [ de Gegevens van de Objecten van de Douane van de Invoer ](/help/marketo/product-docs/administration/marketo-custom-objects/import-custom-object-data.md) voor meer informatie.

>[!MORELIKETHIS]
>
>* [ creeer de Douane Objecten van Marketo ](/help/marketo/product-docs/administration/marketo-custom-objects/create-marketo-custom-objects.md)
>* [ keur een Voorwerp van de Douane ](/help/marketo/product-docs/administration/marketo-custom-objects/approve-a-custom-object.md) goed
>* [ geef uit en schrap een Voorwerp van de Douane van Marketo ](/help/marketo/product-docs/administration/marketo-custom-objects/edit-and-delete-a-marketo-custom-object.md)
>* [ voeg de Gebieden van de Objecten van Marketo toe ](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-fields.md)
>* [ geef uit en schrap de Gebieden van de Objecten van de Douane van Marketo ](/help/marketo/product-docs/administration/marketo-custom-objects/edit-and-delete-marketo-custom-object-fields.md) uit
>* [ de Gegevens van de Objecten van de Invoer van de Douane ](/help/marketo/product-docs/administration/marketo-custom-objects/import-custom-object-data.md)
