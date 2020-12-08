---
unique-page-id: 2360219
description: Een aangepaste DKIM-handtekening instellen - Marketo Docs - Productdocumentatie
title: Een aangepaste DKIM-handtekening instellen
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '279'
ht-degree: 0%

---


# Een aangepaste DKIM-handtekening instellen {#set-up-a-custom-dkim-signature}

Om levering van topniveau te verzekeren, ondertekenen wij automatisch al uitgaande post met een gedeelde handtekening van Marketo DKIM.

>[!NOTE]
>
>Mogelijk hebt u de hulp van uw IT-team nodig om enkele stappen in dit artikel te voltooien.

U kunt de DKIM-handtekening aanpassen aan het domein of de domeinen van uw keuze. Zo gaat het.

1. Ga naar de sectie **Beheer** .

   ![](assets/adminhand.png)

   >[!NOTE]
   >
   >
   >Als u een aangepaste DKIM-handtekening op de ouderwetse manier instelt, blijft deze werken en wordt deze hier weergegeven.

1. Klik op **E-mail**, klik vervolgens op het tabblad **DKIM** en **voeg ten slotte Domein** toe.

   ![](assets/image2014-9-18-15-3a39-3a30.png)

1. Voer het domein dat u gebruikt in e-mailberichten voor markeren als Van adres in en klik op **Toevoegen**.

   >[!TIP]
   >
   >
   >Als u een verschillend domein in uw Van Adres gebruikt, zullen wij de Marketo gedeelde handtekening DKIM gebruiken.

   ![](assets/image2014-9-18-15-3a40-3a28.png)

1. Stuur het **hostrecord** en de **TXT-waarde** naar uw IT-afdeling. Vraag hen om het verslag voor u tot stand te brengen en ervoor te zorgen het aan alle nameservers verbonden aan het van domein verspreidt. De DKIM-verificatie van Marketo vereist dat de DKIM-sleutel wordt doorgegeven aan alle nameservers die zijn gekoppeld aan het domein dat DKIM-ondertekend is.

   ![](assets/image2014-9-18-15-3a40-3a44.png)

1. Zodra zij bevestigen hebben zij tot het verslag geleid, kom terug naar Marketo, selecteer uw domein, en klik **Controle DNS**.

   ![](assets/check.png)

   >[!NOTE]
   >
   >**Herinnering**
   >
   >Als de bevestiging ontbreekt en uw IT het verslag correct heeft gecreeerd, kan het een kwestie van DNS propagatie zijn. Probeer het later opnieuw.

   >[!CAUTION]
   >
   >
   >Als u het overeenkomstige DNS-record wijzigt of verwijdert, resulteert dit in beschadigde prestaties. Zorg ervoor dat u de vermelding in Marketo verwijdert voordat u DNS-wijzigingen aanbrengt.

   Dit helpt absoluut bij je e-mailleverbaarheid. U zou bevestiging moeten krijgen dat het verslag daar en correct is.

