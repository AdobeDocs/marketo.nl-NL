---
description: Nieuwe beheerder verbinden met Marketo - Marketo Docs - Productdocumentatie
title: Nieuwe beheerder verbinden met Marketo
exl-id: ef405bca-a29a-40fc-9efa-eccff5f45956
feature: Sales Insight Actions
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '478'
ht-degree: 0%

---

# Nieuwe beheerder verbinden met Marketo {#connect-new-admin-to-marketo}

Als de andere beheerder al verbinding heeft met Marketo, hoeft hij of zij alleen stap 1 te doen.

Als de tweede beheerder niet als Admin met Marketo is verbonden...

1. De primaire beheerder moet de tweede beheerder van Marketo loskoppelen via [!UICONTROL Settings] > Marketo > [!UICONTROL User Access] .

1. De secundaire beheerder meldt zich aan bij zijn rekening MSC, gaat [!UICONTROL Settings] > Marketo, en klikt **[!UICONTROL Connect]**.

1. De secundaire gebruiker is nu als Admin verbonden met Marketo.

1. De primaire beheerder kan zich nu aanmelden en de verbinding met Marketo verbreken.

>[!NOTE]
>
>De andere gebruikers blijven verbonden zolang gebruiker B als Admin wordt verbonden alvorens Gebruiker A losmaakt.

## Marketo-verbinding bijwerken {#update-your-marketo-connection}

Als u besluit dat u de beheerder die de Marketo-integratie heeft ingesteld, wilt verwijderen, raadpleegt u dit artikel voor meer informatie.

De Marketo-integratie wordt gekoppeld aan een [!DNL Sales Connect] /Actions Admin-gebruiker. Dit is doorgaans de beheerder die eerst op de knop **[!UICONTROL Connect]** op de Marketo-verbindingspagina heeft geklikt en de verbinding tot stand heeft gebracht.

Als u de beheerder die de Marketo-verbinding tot stand heeft gebracht, wilt verwijderen, moet eerst een nieuwe verbinding worden gemaakt door een andere Admin-gebruiker. Hieronder staan de taken die moeten worden voltooid.

Om de instructies te vereenvoudigen, verwijzen we naar de momenteel aangesloten beheerder als Admin A en naar de beheerder die u een nieuwe verbinding met Marketo wilt maken met als Admin B:

1. Admin A (momenteel verbonden Admin) zal toegang tot de integratie met Marketo uit Admin B (nieuw Admin) moeten verwijderen.

1. Beheerder B (nieuw beheerder) een nieuwe verbinding met Marketo laten maken.

1. Koppel Admin A (oorspronkelijk aangesloten Admin) los.

>[!NOTE]
>
>De oorspronkelijke beheerder die verantwoordelijk is voor de Marketo-integratie, ziet een optie voor het verbreken van de verbinding die u kunt gebruiken wanneer u naar de Marketo-integratiepagina navigeert. Andere beheerders (die geen verbinding hebben gemaakt) zullen dat niet doen. Bovendien kunnen beheerders aan wie toegang tot de integratie met Marketo is verleend, niet op Connect klikken. Daarom moet u eerst de stappen volgen om de toegang tot de integratie te verwijderen.

**verwijdert de Toegang van Marketo uit Admin B**

Admin A (Admin oorspronkelijk verantwoordelijk voor de verbinding) dient deze stappen te volgen.

1. Klik in de webtoepassing op het tandwielpictogram en selecteer **[!UICONTROL Settings]** .

1. Klik **Marketo**.

1. Klik op **[!UICONTROL User Access]**.

1. Zoek naar Admin u de nieuwe verbinding van Marketo voor wilt vestigen.

1. Toegang verwijderen.

**Vestig Nieuwe Verbinding voor Admin B**

Deze stappen moeten worden gevolgd door Admin B (nieuwe beheerder)

1. Klik in de webtoepassing op het tandwielpictogram en selecteer **[!UICONTROL Settings]** .

1. Klik **Marketo**.

1. Klik op **[!UICONTROL Disconnect]**.

**maak de Integratie van Marketo voor Admin A** los

Deze stappen moeten worden gevolgd door Admin A (oorspronkelijk aangesloten Admin).

1. Klik in de webtoepassing op het tandwielpictogram en selecteer **[!UICONTROL Settings]** .

1. Klik **Marketo**.

1. Klik op **[!UICONTROL Disconnect]**.

Nu een nieuwe Admin een verbinding met Marketo tot stand heeft gebracht en de oorspronkelijke Admin-verbinding is verbroken, kan de oorspronkelijk aangesloten Admin veilig worden verwijderd uit de [!DNL Sales Connect] /Actions-instantie.
