---
description: Nieuwe beheerder verbinden met Marketo - Marketo Docs - Productdocumentatie
title: Nieuwe beheerder verbinden met Marketo
hide: true
hidefromtoc: true
exl-id: ef405bca-a29a-40fc-9efa-eccff5f45956
source-git-commit: 4055b121b416f3fa56abcfa21d370d148d3ab3c4
workflow-type: tm+mt
source-wordcount: '494'
ht-degree: 0%

---

# Nieuwe beheerder verbinden met Marketo {#connect-new-admin-to-marketo}

Als de andere beheerder al verbinding heeft met Marketo, hoeft deze alleen stap 1 te doen.

Als de tweede beheerder niet als Admin met Marketo is verbonden...

1. De primaire beheerder moet de tweede beheerder van Marketo loskoppelen via Instellingen > Marketo > Gebruikerstoegang.

1. De secundaire beheerder meldt zich aan bij hun rekening MSC, gaat naar Montages > Marketo, en klikt **Verbinden**.

1. De secundaire gebruiker is nu als Admin verbonden met Marketo.

1. De primaire beheerder kan zich nu aanmelden en de verbinding met Marketo verbreken.

>[!NOTE]
>
>De andere gebruikers blijven verbonden zolang gebruiker B als Admin wordt verbonden alvorens Gebruiker A losmaakt.

## Marketo-verbinding bijwerken {#update-your-marketo-connection}

Als u besluit dat u de beheerder die de Marketo-integratie heeft ingesteld, wilt verwijderen, raadpleegt u dit artikel voor meer informatie.

De Marketo-integratie wordt gekoppeld aan een gebruiker van Sales Connect/Actions Admin. Dit is doorgaans de beheerder die eerst op de knop &quot;Connect&quot; op de Marketo-verbindingspagina heeft geklikt en de verbinding tot stand heeft gebracht.

Als u de beheerder die de Marketo-verbinding tot stand heeft gebracht, wilt verwijderen, moet eerst een nieuwe verbinding tot stand worden gebracht door een andere Admin-gebruiker. Hieronder staan de taken die moeten worden voltooid.

Om de instructies te vereenvoudigen, verwijzen we naar de momenteel aangesloten beheerder als Admin A en naar de beheerder die u een nieuwe verbinding met Marketo wilt maken met als Admin B:

1. Admin A (momenteel verbonden Admin) zal toegang tot de integratie met Marketo uit Admin B (nieuw Admin) moeten verwijderen.

1. Beheerder B (nieuw beheerder) een nieuwe verbinding met Marketo laten maken.

1. Koppel Admin A (oorspronkelijk aangesloten Admin) los.

>[!NOTE]
>
>De oorspronkelijke beheerder die verantwoordelijk is voor de Marketo-integratie, ziet een optie voor het verbreken van de verbinding die u kunt gebruiken wanneer u naar de Marketo-integratiepagina navigeert. Andere beheerders (die geen verbinding hebben gemaakt) zullen dat niet doen. Bovendien kunnen beheerders aan wie toegang tot de integratie met Marketo is verleend, niet op Connect klikken. Daarom moet u eerst de stappen volgen om de toegang tot de integratie te verwijderen.

**Marketo Access verwijderen uit beheerder B**

Admin A (Admin oorspronkelijk verantwoordelijk voor de verbinding) dient deze stappen te volgen.

1. Klik in de webtoepassing op het tandwielpictogram en selecteer **Instellingen**.

1. Klikken **Marketo**.

1. Klikken **Gebruikerstoegang**.

1. Zoek naar Admin u de nieuwe verbinding van Marketo voor wilt vestigen.

1. Toegang verwijderen.

**Nieuwe verbinding maken voor beheerder B**

Deze stappen moeten worden gevolgd door Admin B (nieuwe beheerder)

1. Klik in de webtoepassing op het tandwielpictogram en selecteer **Instellingen**.

1. Klikken **Marketo**.

1. Klikken **Verbinding verbreken**.

**Marketo-integratie voor Admin A verbreken**

Deze stappen moeten worden gevolgd door Admin A (oorspronkelijk aangesloten Admin).

1. Klik in de webtoepassing op het tandwielpictogram en selecteer **Instellingen**.

1. Klikken **Marketo**.

1. Klikken **Verbinding verbreken**.

Nu een nieuwe beheerder een verbinding met Marketo tot stand heeft gebracht en de oorspronkelijke beheerfunctie is verbroken, kan de oorspronkelijk aangesloten beheerder veilig worden verwijderd uit de instantie Sales Connect/Actions.
