---
description: Routering - Marketo Docs - Productdocumentatie
title: Routering
feature: Dynamic Chat
exl-id: 93d1a96d-c101-4a1c-898c-dcadb5cdce85
source-git-commit: 38274b4859ae38c018ee73d4f1715fdf6a78e815
workflow-type: tm+mt
source-wordcount: '268'
ht-degree: 0%

---

# Routering {#routing}

In Dynamic Chat geboekte vergaderingen kunnen op twee manieren worden gerouteerd. Afgeronde lijn of een aangepaste lijn.

Ronde lijn: vergaderingen worden opeenvolgend toegewezen aan agenten. Dus als u vijf agenten hebt en agent drie nam de laatste vergadering, agent vier zal volgende krijgen, gevolgd door agent vijf, dan terug naar agent één.

Aangepaste regel: u kunt specifieke agenten kiezen om vergaderingen te ontvangen op basis van kenmerken die u selecteert.

>[!NOTE]
>
>Het Verpletteren van de rekening wordt gegeven de hoogste prioriteit. Wanneer een bezoeker het punt in het gesprek bereikt om of een vergadering te boeken of een levende praatje in werking te stellen, [Account routeren](#account-routing) wordt eerst gecontroleerd alvorens andere verpletterende opties worden overwogen.

## Een aangepaste regel maken {#create-a-custom-rule}

In dit voorbeeld sturen wij alle vergaderingen van de afgeleide staten van CA, OF, en WA naar agent John.

1. Klik onder Configuratie op **Routeringsregels**.

   ![](assets/routing-1.png)

1. Klik op de knop **Aangepaste regels** tab.

   ![](assets/routing-2.png)

1. Klikken **Regel maken**.

   ![](assets/routing-3.png)

1. Geef uw regel een naam. U kunt desgewenst een beschrijving toevoegen en het prioriteitsniveau instellen. Klikken **Volgende**.

   ![](assets/routing-4.png)

1. Kies de gewenste agent(s).

   ![](assets/routing-5.png)

1. Sleep over de gewenste kenmerken.

   ![](assets/routing-6.png)

1. Zoek en selecteer de gewenste waarde(n).

   ![](assets/routing-7.png)

1. Wanneer alle gewenste waarden zijn geselecteerd, klikt u op **Opslaan**.

   ![](assets/routing-8.png)

## Account routeren {#account-routing}

Identificeer en upload uw doelaccount en de respectievelijke verkoopeigenaren en routeer bezoekers die van deze accounts komen rechtstreeks naar de respectievelijke accounteigenaar.

![](assets/routing-9.png)

### Een account toevoegen {#add-an-account}

In dit voorbeeld, zullen wij alle werknemers van Lego rechtstreeks aan agent Steven leiden.

1. In de Rekening die tabel verplettert, klikt u op **+ Account toevoegen**.

   ![](assets/routing-10.png)

   >[!TIP]
   >
   >U kunt meerdere accounts tegelijk maken door op **Accountlijst uploaden** en het uploaden van een CSV.

1. Ga de naam van het bedrijf, domein in, en selecteer de gewenste agent.

   ![](assets/routing-11.png)
