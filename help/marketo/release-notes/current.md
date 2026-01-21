---
description: Huidige aanvullende informatie - Documentatie voor Marketo - Productdocumentatie
title: Huidige Release Notes
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
source-git-commit: 733b85495632eaa31ce7fc08a82fb4948aadf29f
workflow-type: tm+mt
source-wordcount: '728'
ht-degree: 1%

---

# Release Notes: oktober 2025 {#release-notes-oct-25}

Hieronder vind je alle functies die zijn opgenomen in de oktober &#39;25-release. Controleer je Adobe Marketo Engage-editie voor de beschikbaarheid van functies.

De Release Notes, specifiek voor Adobe Dynamic Chat [, zijn hier](/help/marketo/release-notes/dynamic-chat.md){target="_blank"} te vinden.

>[!AVAILABILITY]
>
>Kenmerken die worden aangeduid met een ster (![ster](assets/yellow-star.png)) zijn betaalde add-ons. Neem contact op met uw Marketo Engage-vertegenwoordiger voor meer informatie.

## Standaardreleasecycluskenmerken {#standard-release-cycle-features}

De volgende features vallen onder de standaard releasecyclus en zullen op 31 oktober 2025 **worden uitgebracht**, met een gefaseerde uitrol van de resterende features in de daaropvolgende weken. Uitgavekenmerken en data kunnen veranderen. Controleer naast elke functie de status.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">Functie</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentatie</th>
  </tr>
  <tr>
   <td><strong>E-mailontwerper - Sjabloonimporteur (Bèta):</strong> Importeer e-mailsjablonen uit de klassieke e-maileditor om sjablonen te maken die compatibel zijn met de Nieuwe E-mailontwerper in de Design Studio.</td>
   <td>Verzonden</td>
   <td><a href="/help/marketo/product-docs/email-marketing/email-designer/import-template.md" target="_blank">Sjabloonimport</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>E-mailontwerper - Merkthema's</strong>: Je kunt nu merkthema's definiëren binnen Marketo Engage. Stylingconfiguraties kunnen worden hergebruikt en toegepast op e-mailsjablonen en andere e-mailassets voor merkconsistentie.</td>
   <td>Verzonden</td>
   <td><a href="/help/marketo/product-docs/email-marketing/email-designer/brand-themes.md" target="_blank">Merkthema's</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>Email Designer - Conditional Content</strong>: Pariteitsfunctie voor de nieuwe Email Designer, waarmee je e-mailpersonalisatie kunt bereiken voorbij tokens.</td>
   <td>Verzonden</td>
   <td><a href="/help/marketo/product-docs/email-marketing/email-designer/conditional-content.md" target="_blank">Voorwaardelijke inhoud</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
 <tr>
   <td><strong>E-mailontwerper - Afbeelding-naar-HTML converter</strong>: Upload een compatibel PNG/JPEG-afbeeldingsbestand van een e-mail en dit wordt automatisch omgezet naar HTML voor gebruik in de nieuwe E-mailontwerper.</td>
   <td>Verzonden</td>
   <td><a href="/help/marketo/product-docs/email-marketing/email-designer/image-to-html.md" target="_blank">Afbeeldingen converteren naar HTML-sjablonen</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>E-mailontwerper - E-mailactie</strong> klonen: Je kunt nu een e-mail kloonen naar een andere programmamap in Marketing Activities en bestaande e-mails snel hergebruiken.</td>
   <td>Verzonden</td>
   <td>n.v.t.</td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>Email Designer - A/B Testing</strong>: Pariteitsfunctie voor de nieuwe Email Designer, waarmee je A/B-tests kunt uitvoeren om te zien welke soorten content het beste antwoord krijgen.</td>
   <td>Verzonden</td>
   <td>n.v.t.</td>
  </tr>
  </tbody>
</table>
<br/>

## Aankondigingen {#announcements}

* **Salesforce CRM-integratie-upgrade**: Een nieuwe versie van de native CRM-integratie zal worden uitgerold op actieve sandboxes waar de native connector is ingeschakeld gedurende zeven dagen, vanaf 13 november 2025. Krijg alle details in [deze Nation-post](https://nation.marketo.com/t5/product-blogs/salesforce-crm-integration-upgrade/ba-p/358702){target="_blank"}

* **REST API Double Slash Uitdienst**: Op 16 september 2025 is Adobe overgestapt op een modernere hostinginfrastructuur voor REST API-URL&#39;s, die gebruikmaakt van nieuwere technologie en extra beveiliging en schaalbaarheid. Als je abonnement API&#39;s gebruikt met een dubbele forward slash (//) in de URL, lees [dan dit Nation-bericht](https://nation.marketo.com/t5/product-blogs/rest-api-double-slash-deprecation/ba-p/358616){target="_blank"} voor de volgende stappen.

* **Terug naar Velocity Scripting in de nieuwe Email Designer**: Adobe Marketo Engage bracht afgelopen juni een functie uit genaamd Conditional Content _voor_ de nieuwe Email Designer. De functie werd aangedreven door Handlebar-scripting in plaats van Velocity-scripting, in een poging om wat meer flexibiliteit te bieden in je dynamische content. Maar toen we ontdekten dat sommige tokens verkeerd werden opgelost, besloten we het tijdelijk uit te schakelen. [Meer informatie](https://nation.marketo.com/t5/product-blogs/update-on-email-scripting-in-the-new-email-designer/ba-p/358179){target="_blank"}

* **Marketo Engage Identity Einde van de Levensduur**: In augustus 2025 begon Adobe met het uitfaseren van de ondersteuning voor Marketo Engage Identity (inloggen via `login.marketo.com`). Om onderbroken toegang tot Marketo Engage te voorkomen, moet u uiterlijk 30 september 2025 overstappen op [Adobe Identity](https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview){target="_blank"} .

   * _Afschreeuwing_ van IP-beperkingen: Ondersteuning voor [het beperken van Marketo-inlogs op basis van IP](https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/administration/settings/restrict-marketo-logins-based-on-ip){target="_blank"} eindigde op 30 juli 2025. De functie blijft operationeel totdat de overgang naar Adobe Identity is voltooid. Een nieuwe locatiegebaseerde toegangscontrolefunctie voor Adobe Identity in de Adobe Admin Console komt binnenkort.

   * _Single Sign-On (SSO) deprecation:_ Ondersteuning voor [Marketo Identity SSO](https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal){target="_blank"} eindigde op 30 juli 2025. De functie blijft operationeel totdat de overgang naar Adobe Identity is voltooid. Single Sign-On voor Adobe Identity in de Adobe Admin Console moet apart worden geconfigureerd. Voor installatiestappen, zie [Identiteit instellen en Single Sign-On](https://helpx.adobe.com/nl/enterprise/using/set-up-identity.html){target="_blank"}.

* **Afschreeuwing van de functie Doorsturen naar _een Vriend:_ Op 29 september 2025 werd de** functie Doorsturen naar een Vriend _in de Marketo Engage 2.0 e-mails (de oude e-maileditor) volledig afgeschaft voor alle abonnementen._ Dit had invloed op de &#39;Forward to a Friend&#39;-token en &#39;Forward to a Friend&#39;-links in e-mails die al waren of gepland stonden om met het token te worden verzonden. [Meer informatie](https://nation.marketo.com/t5/product-blogs/deprecation-of-forward-to-a-friend/ba-p/358045#M2889){target="_blank"}

* **Rest API &#39;access_token&#39; Parameter Deprecation:** De `access_token` queryparameter die wordt gebruikt om Marketo REST API-aanroepen te authenticeren, wordt verouderd en zal na 31 maart 2026 niet meer beschikbaar zijn. Alle nieuwe en bestaande integraties moeten REST API-aanroepen authenticeren met behulp van de &#39;Authorization&#39;-header, [zoals hier](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/authentication){target="_blank"} beschreven.

* **SOAP API Veroudering**: Ondersteuning voor de Marketo SOAP API eindigt op 31 maart 2026. Diensten die gebruikmaken van SOAP API-mogelijkheden moeten worden gemigrerd naar de [REST API.](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}
