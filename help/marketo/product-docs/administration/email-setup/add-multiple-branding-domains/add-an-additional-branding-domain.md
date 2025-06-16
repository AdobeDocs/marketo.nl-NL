---
unique-page-id: 11377395
description: Een extra brandingdomein toevoegen - Marketo Docs - Productdocumentatie
title: Een extra brandingdomein toevoegen
exl-id: df6e5afe-dbb0-4fbe-bf06-79d92a91b986
feature: Email Setup
source-git-commit: df7c5bfc344d5a22632128ef70b2c5c12d2f669d
workflow-type: tm+mt
source-wordcount: '574'
ht-degree: 0%

---

# Een extra brandingdomein toevoegen {#add-an-additional-branding-domain}

Voeg een extra branding domein toe wanneer u veelvoudige merken uit één enkel geval van Marketo in werking stelt en hen elk hun eigen merksporen verbindingen wilt hebben.

>[!PREREQUISITES]
>
>U moet [ de generische volgende verbinding ](/help/marketo/product-docs/administration/email-setup/add-multiple-branding-domains/edit-your-default-branding-domain.md){target="_blank"} met een branded domein vervangen alvorens extra branded domeinen toe te voegen.

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/add-an-additional-branding-domain-1.png)

1. Klik op **[!UICONTROL Email]**.

   ![](assets/add-an-additional-branding-domain-2.png)

1. Klik op **[!UICONTROL Add]** om een extra brandingdomein toe te voegen.

   ![](assets/add-an-additional-branding-domain-3.png)

1. Ga de naam van uw nieuw brandend domein in, selecteer _Primair Domein maken_ en/of _produceert SSL Certificaat_ (zowel facultatief), en klik **[!UICONTROL Save]**.

   ![](assets/add-an-additional-branding-domain-4.png)

>[!NOTE]
>
>* _maak Primair Domein_: Maak dit uw primair domein, en alle bestaande onverzonden e-mails die aan &quot;Gebrek&quot;worden geplaatst en alle nieuw gecreëerde e-mails zullen aan het primaire domein in gebreke blijven. U kunt [ dit op een per-e-mailbasis ](/help/marketo/product-docs/administration/email-setup/add-multiple-branding-domains/overwrite-primary-domain-for-emails.md){target="_blank"} beschrijven.
>
>* _produceer SSL Certificaat_: U kunt een Veilige Laag van Contactdozen (SSL) met de verwezenlijking van het domein tot stand brengen. Het eerste volgende domein zal een éénmalige opstelling van infrastructuur in werking stellen die een paar uren kan vergen. U wordt op de hoogte gesteld wanneer de bewerking is voltooid en u kunt vervolgens het eerste domein instellen. Om SSL aan uw bestaande domeinen toe te voegen, te bereiken gelieve uit [ de Steun van Marketo ](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}.

## Foutberichten {#error-messages}

<table><thead>
  <tr>
    <th>Fout</th>
    <th>Details</th>
  </tr></thead>
<tbody>
  <tr>
    <td><i>Onverwachte fout aangetroffen tijdens het maken van een domein. Neem contact op met de Technische Ondersteuning voor hulp.</i></td>
    <td>Er is een onverwachte fout opgetreden. Gelieve te verzamelen logboeken en foutendetails, en escaleer de kwestie aan <a href="https://nation.marketo.com/t5/support/ct-p/Support" target="_blank"> de Steun van Marketo </a>.</td>
  </tr>
  <tr>
    <td><i>SSL-certificaat is al uitgegeven.</i></td>
    <td>Er bestaat al een SSL-certificaat voor dit aangepaste domein. Er is geen verdere actie nodig tenzij het certificaat is verlopen of opnieuw moet worden uitgegeven.</td>
  </tr>
  <tr>
    <td><i>Domein wordt niet toegewezen aan het standaarddomein.</i></td>
    <td>Het aangepaste domein wordt niet correct toegewezen aan het standaarddomein. Verifieer de instellingen voor domeintoewijzing en zorg ervoor dat de DNS-configuratie naar het juiste standaarddomein wijst.</td>
  </tr>
  <tr>
    <td><i>De instelling Cloudflare is gestart. Probeer het later opnieuw.</i></td>
    <td>Wanneer u het eerste volgende volgende domein voor de instantie creeert, komt een éénmalige infrastructuuropstelling in Wolk voor. Dit bericht geeft aan dat de installatie is gestart en maximaal drie uur kan duren.</td>
  </tr>
  <tr>
    <td><i>De instelling Cloudflare is nog in uitvoering. Probeer het later opnieuw.</i></td>
    <td>zie hierboven</td>
  </tr>
  <tr>
    <td><i>De instelling van Cloudflare is mislukt vanwege een onverwachte fout. Neem contact op met de klantenondersteuning.</i></td>
    <td>De initiële installatie van de cloudritinfrastructuur is mislukt. Gelieve te bereiken uit aan <a href="https://nation.marketo.com/t5/support/ct-p/Support" target="_blank"> Steun van Marketo </a> voor hulp.</td>
  </tr>
</tbody></table>

## Notities {#things-to-note}

* **DNS afbeelding voor domein aan Marketo Engage**: Alvorens domeinen in UI toe te voegen, moet u [ CNAMEs aan een Marketo-Geleverd domein ](https://experienceleague.adobe.com/en/docs/marketo/using/getting-started/initial-setup/setup-steps#customize-your-landing-page-urls-with-a-cname){target="_blank"} in kaart brengen.

* **Aangepaste SSLs**: Als u douane SSL nodig hebt, gelieve a [ kaartje van de Steun ](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} voor te leggen. Gebruik het selectievakje voor zelfbediening niet voor het maken van SSL.

* **Vooraf bestaande SSLs**: Terwijl het toevoegen van een domein, controleert het systeem reeds bestaande SSLs, die manueel kan zijn gecreeerd vroeger. Als u deze validatie tegenkomt, maakt u uw domein zonder SSL-ontwerp te selecteren en maken we er verbinding mee. [ de Steun van het Contact ](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} meer extra details/opties.

* **Eerste-tijd het volgen domein**: De eerste-tijd verwezenlijking van e-mail het volgen verbindingsdomeinen zal handinterventie door [ Steun van Marketo ](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} vergen. Het volgende subdomein wordt gecreeerd onder het zelfde domein toegestaan in UI.

* **Toevoegend certs aan bestaande domeinen**: Het toevoegen van certs aan bestaande domeinen wordt momenteel niet gesteund. Voor reeds bestaande domeinen, of voor gevallen waar u het SSL certificaatvakje gemist hebt, moet u uit aan [ de Steun van Marketo ](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} reiken om het toegevoegde certificaat te krijgen.

* **Schrapping van domeinen**: Het schrappen van een domein schrapt automatisch niet het SSL certificaat op dit ogenblik. Deze kwestie zal in een toekomstige versie worden besproken.

>[!MORELIKETHIS]
>
>[ geeft Uw Standaard brandend Domein ](/help/marketo/product-docs/administration/email-setup/add-multiple-branding-domains/edit-your-default-branding-domain.md){target="_blank"} uit
