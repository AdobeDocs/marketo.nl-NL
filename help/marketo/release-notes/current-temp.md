---
description: Huidige aanvullende informatie - Documentatie voor Marketo - Productdocumentatie
title: Opmerkingen bij de huidige release
hide: true
hidefromtoc: true
feature: Release Information
exl-id: 0ca5e844-c30b-4c86-a23d-d8f2c1bdddf5
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '494'
ht-degree: 2%

---

# Opmerkingen bij de release: september 2025 {#release-notes-sep-25}

Hieronder vindt u alle functies die zijn inbegrepen in de release van 25 september. Raadpleeg de Adobe Marketo Engage-editie voor informatie over de beschikbaarheid van functies.

De Nota&#39;s van de Versie specifiek voor Adobe Dynamic Chat [&#x200B; kunnen hier &#x200B;](/help/marketo/release-notes/dynamic-chat.md){target="_blank"} worden gevonden.

>[!AVAILABILITY]
>
>De eigenschappen die door een ster (![&#x200B; worden aangegeven ster &#x200B;](assets/yellow-star.png)) worden betaald toe:voegen-ons. Neem contact op met je Marketo Engage-vertegenwoordiger voor meer informatie.

## Standaardfuncties van releasecyclus {#standard-release-cycle-features}

De volgende eigenschappen vallen onder de standaardversiecyclus en zullen beginnen om op **worden vrijgegeven 19 september, 2025**, met een gefaseerde implementatie van resterende eigenschappen in de verdere weken. De functies en datums van de release kunnen worden gewijzigd. Controleer de status naast elke functie.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">Functie</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentatie</th>
  </tr>
  <tr>
   <td><strong> Op bestelling Webinar het Behouden van de Activiteit </strong>: De interactieve gebruikers van Webinars hebben nu de gegevens van het Webinar Dashboard beschikbaar voor meer dan 30 dagen (eerder was het slechts tot 30 dagen van de dag van webinar).</td>
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
  </tbody>
</table>
<br/>

## Aankondigingen {#announcements}

* **Omschakeling terug naar Scripting van de Snelheid in nieuwe E-mail Designer**: Adobe Marketo Engage gaf een eigenschap genoemd _Voorwaardelijke Inhoud_ voor nieuwe E-mail Designer dit afgelopen Juni vrij. De functie werd aangestuurd door Handlebar-scripting in plaats van Velocity-scripting, in een poging om een beetje meer flexibiliteit in uw dynamische inhoud te bieden. Maar toen we ontdekten dat het ervoor zorgde dat sommige tokens onjuist werden opgelost, besloten we het tijdelijk uit te schakelen. [&#x200B; leer meer &#x200B;](https://nation.marketo.com/t5/product-blogs/update-on-email-scripting-in-the-new-email-designer/ba-p/358179){target="_blank"}

* **Eind van het Leven van de Identiteit van Marketo Engage**: In Augustus 2025, begon Adobe fasing-out steun voor de Identiteit van Marketo Engage (het programma openen via `login.marketo.com`). Om onderbroken toegang tot Marketo Engage te verhinderen, moet u overgang aan [&#x200B; Identiteit van Adobe &#x200B;](https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview){target="_blank"} uiterlijk 30 September, 2025.

   * _IP de Afschrijving van Beperkingen_: Steun voor [&#x200B; Beperkende Marketo Logins die op IP &#x200B;](https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/administration/settings/restrict-marketo-logins-based-on-ip){target="_blank"} worden gebaseerd eindigde op 30 juli, 2025. De functie blijft actief totdat de overgang naar Adobe Identity is voltooid. Binnenkort wordt er een nieuwe functie voor toegangsbeheer op basis van locatie beschikbaar voor Adobe Identity in de Adobe Admin Console.

   * _Enige Sign-On (SSO) Verdringing_: Steun voor [&#x200B; Identiteit SSO van Marketo &#x200B;](https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal){target="_blank"} geëindigd op 30 Juli, 2025. De functie blijft actief totdat de overgang naar Adobe Identity is voltooid. Single Sign-On voor Adobe Identity in de Adobe Admin Console moet afzonderlijk worden geconfigureerd. Voor opstellingsstappen, zie [&#x200B; de identiteit van de Opstelling en Enige Sign-On &#x200B;](https://helpx.adobe.com/nl/enterprise/using/set-up-identity.html){target="_blank"}.

* **Verdringing van _door:sturen aan een 2&rbrace; Eigenschap van de Vriend_: Op 29 september, 2025,** door:sturen aan een 5&rbrace; eigenschap van de Vriend &lbrace;in Marketo Engage 2.0 e-mails (de erfenis e-mailredacteur) zal volledig verouderd voor alle abonnementen zijn. __ Dit is van invloed op de token &#39;Doorsturen naar een vriend&#39; en de koppeling &#39;Doorsturen naar een vriend&#39; in e-mailberichten die al zijn of zullen worden verzonden met de token. [Meer informatie](https://nation.marketo.com/t5/product-blogs/deprecation-of-forward-to-a-friend/ba-p/358045#M2889){target="_blank"}

* **Rest API &quot;access_token&quot;de Afschrijving van de Parameter**: De `access_token` vraagparameter die wordt gebruikt om de vraag van Marketo REST API voor authentiek te verklaren wordt afgekeurd en zal niet beschikbaar na 31 Januari, 2026 zijn. Alle nieuwe en bestaande integratie zouden vraag REST API gebruikend de kopbal van de &quot;Vergunning&quot;voor authentiek moeten verklaren, [&#x200B; zoals hier beschreven &#x200B;](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **SOAP API Verdringing**: Steun voor Marketo SOAP API zal op 31 Januari, 2026 eindigen. De diensten die SOAP API mogelijkheden gebruiken zouden aan [&#x200B; REST API &#x200B;](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/rest-api){target="_blank"} moeten worden gemigreerd.
