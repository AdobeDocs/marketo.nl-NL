---
unique-page-id: 2360219
description: Een aangepaste DKIM-handtekening instellen - Marketo Docs - Productdocumentatie
title: Een aangepaste DKIM-handtekening instellen
exl-id: a7c6429e-14ee-439e-9f47-1b25b98d41e7
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '278'
ht-degree: 0%

---

# Een aangepaste DKIM-handtekening instellen {#set-up-a-custom-dkim-signature}

Om ervoor te zorgen dat de producten op topniveau kunnen worden geleverd, ondertekenen we automatisch alle uitgaande berichten met een gedeelde Marketo DKIM-handtekening.

>[!NOTE]
>
>Mogelijk hebt u de hulp van uw IT-team nodig om enkele stappen in dit artikel te voltooien.

U kunt de DKIM-handtekening aanpassen aan het domein of de domeinen van uw keuze. Zo gaat het.

1. Ga naar de **Beheer** sectie.

   ![](assets/adminhand.png)

   >[!NOTE]
   >
   >Als u een aangepaste DKIM-handtekening op de ouderwetse manier instelt, blijft deze werken en wordt deze hier weergegeven.

1. Klikken **E-mail** en de **DKIM** en finally **Domein toevoegen**.

   ![](assets/image2014-9-18-15-3a39-3a30.png)

1. Voer het domein dat u in Marketo-e-mails gebruikt in als Van-adres en klik op **Toevoegen**.

   >[!TIP]
   >
   >Als u een ander domein in uw Van Adres gebruikt, zullen wij de Marketo gedeelde handtekening DKIM gebruiken.

   ![](assets/image2014-9-18-15-3a40-3a28.png)

1. Verzend de **Hostrecord** en **TXT-waarde** aan uw IT. Vraag hen om het verslag voor u tot stand te brengen en ervoor te zorgen het aan alle nameservers verbonden aan het van domein verspreidt. De verificatie van DKIM van Marketo vereist dat de sleutel DKIM aan alle nameservers verbonden aan het domein wordt verspreid die DKIM-ondertekend.

   ![](assets/image2014-9-18-15-3a40-3a44.png)

1. Nadat ze hebben bevestigd dat ze de record hebben gemaakt, keert u terug naar Marketo, selecteert u uw domein en klikt u op **DNS controleren**.

   ![](assets/check.png)

   >[!NOTE]
   >
   >Als de bevestiging ontbreekt en uw IT het verslag correct heeft gecreeerd, kan het een kwestie van DNS propagatie zijn. Probeer het later opnieuw.

   >[!CAUTION]
   >
   >Als u het overeenkomstige DNS-record wijzigt of verwijdert, resulteert dit in beschadigde prestaties. Zorg ervoor dat u de vermelding in Marketo verwijdert voordat u DNS-wijzigingen aanbrengt.

   Dit helpt absoluut bij je e-mailleverbaarheid. U zou bevestiging moeten krijgen dat het verslag daar en correct is.
