---
description: Nieuwe beheerder verbinden met Marketo - Marketo Docs - Productdocumentatie
title: Nieuwe beheerder verbinden met Marketo
hide: true
hidefromtoc: true
source-git-commit: 0ed5981470998dadd5f42384cd2e9572fec94ef6
workflow-type: tm+mt
source-wordcount: '465'
ht-degree: 0%

---

# Nieuwe beheerder verbinden met Marketo {#connect-new-admin-to-marketo}

Als de andere beheerder al verbinding heeft met Marketo, hoeft deze alleen stap 1 te doen.

Als de tweede beheerder niet als Admin met Marketo is verbonden...

1. De primaire beheerder moet de tweede beheerder loskoppelen van Marketo via Instellingen > Marketo > Gebruikerstoegang

1. Secundaire Admin registreert zich in hun rekening MSC, gaat naar Montages > Marketo en klikt **Verbinden**.

1. De secundaire gebruiker is nu als Admin verbonden met Marketo.

1. Primaire beheerder kan zich nu aanmelden en de verbinding met Marketo verbreken.

>[!NOTE]
>
>De andere gebruikers blijven verbonden zolang gebruiker B als Admin wordt verbonden alvorens Gebruiker A losmaakt.

## Marketo-verbinding bijwerken {#update-your-marketo-connection}

Als u besluit dat u de beheerder die de Marketo-integratie heeft ingesteld, wilt verwijderen, leest u dit artikel voor meer informatie.

De Marketo-integratie wordt gekoppeld aan een gebruiker van een Sales Connect/Actions-beheerder. Dit is doorgaans de beheerder die eerst op de knop &quot;Connect&quot; op de Marketo-verbindingspagina heeft geklikt en de verbinding tot stand heeft gebracht.

Als u de beheerder die de Marketo-verbinding tot stand heeft gebracht, wilt verwijderen, moet eerst een nieuwe verbinding tot stand worden gebracht door een andere beheerder. Hieronder staan de taken die moeten worden voltooid.

Om de instructies te vereenvoudigen, verwijzen we naar de momenteel aangesloten beheerder als Admin A en de beheerder die u een nieuwe verbinding met Marketo wilt maken met als Admin B:

1. Admin A (momenteel aangesloten beheerder) moet de toegang tot de integratie met Marketo verwijderen uit Admin B (nieuwe beheerder).

1. Beheerder B (nieuwe beheerder) een nieuwe verbinding met Marketo laten maken.

1. Koppel Admin A (oorspronkelijk aangesloten beheerder) los.

>[!NOTE]
>
>De oorspronkelijke beheerder die verantwoordelijk is voor de Marketo-integratie, ziet een optie voor het verbreken van de verbinding die u kunt klikken als u naar de Marketo-integratiepagina navigeert. Andere beheerders (die geen verbinding hebben gemaakt) zullen dat niet doen. Bovendien kunnen beheerders aan wie toegang is verleend tot de integratie met Marketo niet op Connect klikken. Daarom moet u eerst de stappen volgen om de toegang tot de integratie te verwijderen.

**Marketo Access verwijderen uit beheerder B**

Admin A (beheerder oorspronkelijk verantwoordelijk voor de verbinding) dient deze stappen te volgen.

1. Navigeer naar instellingen.

1. Klikken **Marketo**.

1. Klikken **Gebruikerstoegang**.

1. Zoek naar admin u de nieuwe verbinding van Marketo voor wilt vestigen.

1. Toegang verwijderen.

**Nieuwe verbinding maken voor beheerder B**

Deze stappen moeten worden gevolgd door Admin B (nieuwe beheerder)

1. Navigeer naar instellingen.

1. Klikken **Marketo**.

1. Klikken **Verbinding verbreken**.

**Marketo-integratie voor Admin A verbreken**

Deze stappen moeten worden gevolgd door Admin A (oorspronkelijk aangesloten beheerder)

1. Navigeer naar instellingen.

1. Klikken **Marketo**.

1. Klikken **Verbinding verbreken**.

Nu een nieuwe beheerder een verbinding met Marketo tot stand heeft gebracht en de oorspronkelijke beheerder is losgekoppeld, kan de oorspronkelijk aangesloten beheerder veilig worden verwijderd uit de instantie Sales Connect/Actions.
