---
unique-page-id: 2360219
description: Een aangepaste DKIM-handtekening instellen - Marketo Docs - Productdocumentatie
title: Een aangepaste DKIM-handtekening instellen
exl-id: a7c6429e-14ee-439e-9f47-1b25b98d41e7
feature: Deliverability
source-git-commit: 47bc93665a7efa0d64cd4d5f34b868895d407527
workflow-type: tm+mt
source-wordcount: '345'
ht-degree: 0%

---

# Een aangepaste DKIM-handtekening instellen {#set-up-a-custom-dkim-signature}

Om ervoor te zorgen dat de producten op topniveau kunnen worden geleverd, ondertekenen we automatisch alle uitgaande berichten met een gedeelde Marketo DKIM-handtekening.

>[!NOTE]
>
>Mogelijk hebt u de hulp van uw IT-team nodig om enkele stappen in dit artikel te voltooien.

U kunt de DKIM-handtekening aanpassen aan het domein of de domeinen van uw keuze. Zo gaat het.

1. Ga naar de **Beheerder** sectie.

   ![](assets/set-up-a-custom-dkim-signature-1.png)

   >[!NOTE]
   >
   >Als u een aangepaste DKIM-handtekening op de ouderwetse manier instelt, blijft deze werken en wordt deze hier weergegeven.

1. Klikken **E-mail**.

   ![](assets/set-up-a-custom-dkim-signature-2.png)

1. Klik op de knop **SPF/DKIM** dan **Domein toevoegen**.

   ![](assets/set-up-a-custom-dkim-signature-3.png)

1. Voer het domein dat u gebruikt in Marketo-e-mails in als Van-adres. Kies een kiezer en een sleutelgrootte. Klikken **Toevoegen** wanneer gereed.

   ![](assets/set-up-a-custom-dkim-signature-4.png)

   >[!TIP]
   >
   >* We raden een sleutellengte van 2048 aan.
   >* Als u een ander domein in uw Van Adres gebruikt, zullen wij de Marketo gedeelde handtekening DKIM gebruiken.

   <table> 
   <tr>
   <td width="20%"><b>Kiezer</b></td>
   <td>Een unieke tekenreeks/id die wordt gebruikt om het openbare-sleutelgedeelte van het DKIM-record te zoeken. Het kan een willekeurige tekenreeks zijn, of een unieke id om het doel van die DKIM-sleutel/-record te scheiden en te identificeren.</td>
   </tr>
   <tr> 
   <td width="20%"><b>Grootte sleutel</b></td>
   <td>Het beveiligingsniveau waarmee uw DKIM-handtekening moet worden gecodeerd.</td>
   </tr>
   </tbody>
   </table>

   <p>

1. Verzend de **Hostrecord** en **TXT-waarde** aan uw IT. Vraag hen om het verslag voor u tot stand te brengen en ervoor te zorgen het aan alle nameservers verbonden aan het van domein verspreidt. De verificatie van DKIM van Marketo vereist dat de sleutel DKIM aan alle nameservers verbonden aan het domein wordt verspreid die DKIM-ondertekend.

   ![](assets/set-up-a-custom-dkim-signature-5.png)

1. Nadat ze hebben bevestigd dat ze de record hebben gemaakt, keert u terug naar Marketo, selecteert u uw domein en klikt u op **DNS controleren**.

   ![](assets/set-up-a-custom-dkim-signature-6.png)

   >[!NOTE]
   >
   >Als de bevestiging ontbreekt en uw IT het verslag correct heeft gecreeerd, kan het een kwestie van DNS propagatie zijn. Probeer het later opnieuw.

   >[!CAUTION]
   >
   >Als u het overeenkomstige DNS-record wijzigt of verwijdert, resulteert dit in beschadigde prestaties. Zorg ervoor dat u de vermelding in Marketo verwijdert voordat u DNS-wijzigingen aanbrengt.

   Dit helpt absoluut bij je e-mailleverbaarheid. U zou bevestiging moeten krijgen dat het verslag daar en correct is.
