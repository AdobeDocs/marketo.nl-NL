---
description: Bulksgewijs verkoop-e-mail verzenden in Salesforce - Marketo Docs - Productdocumentatie
title: 'Onthoud: Verkoop-e-mail verzenden in Salesforce gebruiken'
exl-id: 4886109d-c2b8-4186-922b-8a15cf1e742e
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '596'
ht-degree: 0%

---

# Onthoud: Verkoop-e-mail verzenden in Salesforce gebruiken {#using-bulk-send-sales-email-in-salesforce}

Leer hoe je bulke-mailberichten in Salesforce kunt verzenden om je uitgaande communicatie te schalen met Verkoopacties.

>[!NOTE]
>
>Salesforce past een limiet van 200 records toe die tegelijk kunnen worden geselecteerd.

>[!PREREQUISITES]
>
>Zorg ervoor u het [ recentste pakket van Insight van de Verkoop ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md){target="_blank"} aan uw instantie van Salesforce hebt geïnstalleerd en de [ knopen van de Actie ](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/add-action-buttons-to-salesforce-list-view.md){target="_blank"} op uw contact en de mening van de loodlijst in Salesforce gevormd.

## Bulksgewijze e-mail verzenden in Salesforce Lightning {#sending-bulk-email-in-salesforce-lightning}

1. In Salesforce, navigeer aan de het huispagina van Leads/Contacten door **te klikken leidt/Contacten** tabel.

   ![](assets/using-bulk-send-sales-email-in-salesforce-1.png)

1. Selecteer in de vervolgkeuzelijst Weergave de gewenste weergave van leads/contactpersonen die u wilt e-mailen.

   >[!TIP]
   >
   >U kunt een nieuwe mening tot stand brengen door het cogapictogram op het recht te klikken en **Nieuw** te selecteren. Nadat u de weergave een nieuwe naam hebt gegeven en deze hebt opgeslagen, kunt u op het filterpictogram aan de rechterkant klikken om naar de gewenste set leads/contactpersonen die u wilt e-mailen, te gaan.

1. Kies de gewenste lood of contactlijst en klik **verzendt Verkoop E-mail** knoop.

   ![](assets/using-bulk-send-sales-email-in-salesforce-2.png)

1. U wordt naar het samenstellingsvenster Handelingen genavigeerd, met de personen die u hebt geselecteerd.

1. Selecteer de sjabloon die u wilt invoegen in de werkbalk van het samenstellingenvenster of schrijf een aangepaste e-mail.

   >[!TIP]
   >
   >Het gebruik [ Vastgezette Categorieën ](/help/marketo/product-docs/marketo-sales-insight/actions/email/using-the-compose-window/using-a-template-in-the-compose-window.md#pinning-template-categories-in-the-compose-window){target="_blank"} om gemakkelijkere toegang tot uw favoriete e-mailmalplaatjes te verlenen.

   **OPTIONELE STAP**: Voorproef om het even welke Dynamische verpersoonlijking van Gebieden door de **Dynamische knoop van de Voorproef van Gebieden** te klikken.

   >[!TIP]
   >
   >Als u een sjabloon wilt aanpassen voor alle ontvangers en u klikt op de optie Alle ontvangers in de zijbalk Samenstellen bulk, kunt u alle gewenste e-mails tegelijk bewerken. Als u een wijziging wilt aanbrengen in een specifiek e-mailbericht, klikt u op de naam of het e-mailbericht van de ontvanger in het zijpaneel Samenstellen bulk. Houd er rekening mee dat als u wijzigingen aanbrengt in een afzonderlijke e-mail en vervolgens wijzigingen aanbrengt terwijl u Alle ontvangers selecteert, de wijzigingen die u aanbrengt in Alle ontvangers de wijzigingen overschrijven die in de afzonderlijke e-mail zijn aangebracht.

1. Selecteer **verzenden** om e-mail onmiddellijk te verzenden, of **Plaats Programma** om een datum en een tijd voor e-mail te plaatsen die moet worden verzonden.

   ![](assets/using-bulk-send-sales-email-in-salesforce-3.png)

## Bulkmail verzenden in Salesforce Classic {#sending-bulk-email-in-salesforce-classic}

1. In Salesforce, klik **Leads/Contacten** tabel.

1. In de drop-down Mening, selecteer de gewenste mening van Leads/Contacten u wilt e-mailen en **klikken gaat**.

   ![](assets/using-bulk-send-sales-email-in-salesforce-4.png)

   >[!TIP]
   >
   >U kunt een nieuwe mening tot stand brengen door tot de Nieuwe Mening te klikken en de beschikbare filters te vormen om onderaan de lijst te versmallen van wie u aan een Campagne van de Verkoop toevoegt.

1. Kies de gewenste lood of contactenlijst en klik **verzendt Verkoop E-mail** knoop.

   ![](assets/using-bulk-send-sales-email-in-salesforce-5.png)

1. U zult aan het Acties samenstellen venster met de ontvangers worden genavigeerd u in samenstelt venster selecteerde.

1. Selecteer de sjabloon die u wilt invoegen in de werkbalk van het samenstellingenvenster of schrijf een aangepaste e-mail.

   ![](assets/using-bulk-send-sales-email-in-salesforce-6.png)

   >[!TIP]
   >
   >Het gebruik [ Vastgezette Categorieën ](/help/marketo/product-docs/marketo-sales-insight/actions/email/using-the-compose-window/using-a-template-in-the-compose-window.md#pinning-template-categories-in-the-compose-window){target="_blank"} om gemakkelijkere toegang tot uw favoriete e-mailmalplaatjes te verlenen.

   **OPTIONELE STAP**: Voorproef om het even welke Dynamische verpersoonlijking van Gebieden door de **Dynamische knoop van de Voorproef van Gebieden** te klikken.

   >[!TIP]
   >
   >Als u een sjabloon wilt aanpassen voor alle ontvangers en u klikt op de optie Alle ontvangers in de zijbalk Samenstellen bulk, kunt u alle gewenste e-mails tegelijk bewerken. Als u een wijziging wilt aanbrengen in een specifiek e-mailbericht, klikt u op de naam of het e-mailbericht van de ontvanger in het zijpaneel Samenstellen bulk. Houd er rekening mee dat als u wijzigingen aanbrengt in een afzonderlijke e-mail en vervolgens wijzigingen aanbrengt terwijl u Alle ontvangers selecteert, de wijzigingen die u aanbrengt in Alle ontvangers de wijzigingen overschrijven die in de afzonderlijke e-mail zijn aangebracht.

1. Selecteer **verzenden** om e-mail onmiddellijk te verzenden, of **Plaats Programma** om een datum en een tijd voor e-mail te plaatsen die moet worden verzonden.
