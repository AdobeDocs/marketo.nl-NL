---
unique-page-id: 5472678
description: Een lijst met niet-Latijnse tekens importeren - Marketo Docs - Productdocumentatie
title: Een lijst met niet-Latijnse tekens importeren
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '307'
ht-degree: 0%

---


# Een lijst met niet-Latijnse tekens importeren {#import-a-non-latin-characters-list}

Een bestand importeren dat niet in het Engels staat? De lijst ziet er perfect uit als u deze opent met Excel.

![](assets/image2015-2-10-9-3a34-3a57.png)

Maar wanneer u het in Marketo invoert, zou u kunnen zien dat de niet-Engelse karakters niet correct worden opgepikt.

![](assets/image2015-2-10-9-3a35-3a49.png)

Dit komt doordat het bestand niet correct is opgeslagen zodat Marketo alle niet-Latijnse tekens herkent. Het goede nieuws is dat er een paar eenvoudige stappen zijn die je kunt volgen om het op te lossen.

1. Selecteer **Opslaan als...** in het menu **Bestand** in Excel.

   ![](assets/image2015-2-10-9-3a46-3a44.png)

1. Kies **UTF-16 Unicode-tekst (.txt)** als de optie **Indeling** . Hiermee wordt het bestand gecodeerd op de manier waarop Marketo deze kan weergeven.

   ![](assets/image2015-2-10-9-3a48-3a7.png)

   >[!NOTE]
   >
   >Marketo ondersteunt ook UTF-8, Shift-JIS of EUC-JP.

1. Excel slaat het nieuwe bestand op als een tekstbestand met de extensie .txt. Maar het zet ook alle komma&#39;s in het dossier in lusjes om. We moeten het weer veranderen.

   >[!TIP]
   >
   >U kunt het Dossier van de Tekst openen gebruikend **Blocnote** als u Vensters of **TextEdit** gebruikt als u MAC gebruikt.

   ![](assets/image2015-2-10-9-3a51-3a41.png)

1. Selecteer een tabblad in het document en kopieer het.

   ![](assets/image2015-2-10-9-3a55-3a53.png)

1. Selecteer **Zoeken en vervangen...** in het menu **Bewerken** .

   ![](assets/image2015-2-10-9-3a59-3a8.png)

   >[!TIP]
   >
   >De equivalente actie voor Windows-gebruikers is: **Bewerken > Vervangen...**

1. Plak de tab die u in stap 4 hebt gekopieerd in het eerste (te vervangen) vak en typ een komma in het tweede (te vervangen door) vak. Klik op **Alles**.

   ![](assets/image2015-2-10-10-3a8-3a53.png)

1. En voila, alle komma&#39;s zijn terug en we zijn klaar om te rollen.

   ![](assets/image2015-2-10-10-3a14-3a45.png)

1. Importeer het nieuwe bestand in Marketo en de informatie moet nu correct worden weergegeven.

   ![](assets/image2015-2-10-10-3a16-3a9.png)

   >[!NOTE]
   >
   >Alle datum-/tijdvelden die worden geïmporteerd, worden behandeld als Central Time. Als u datum-/tijdgebieden in een verschillende tijdzone hebt, kunt u een formule van Excel gebruiken om het in Centrale Tijd (Amerika/Chicago) om te zetten.

We weten dat dit vreemd is, maar het werkt. Happy Importing!