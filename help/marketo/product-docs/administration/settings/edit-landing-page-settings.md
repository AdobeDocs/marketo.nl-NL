---
unique-page-id: 2359918
description: Instellingen voor openingspagina bewerken - Marketo Docs - Productdocumentatie
title: Instellingen openingspagina bewerken
exl-id: 019b4651-3a66-46f9-8722-66af30194380
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '256'
ht-degree: 0%

---

# Instellingen openingspagina bewerken {#edit-landing-page-settings}

U kunt de domeinnaam en de fallback-pagina bewerken, het vooraf invullen van het formulier in- of uitschakelen, misbruik van de bestemmingspagina voorkomen en nog veel meer. Zo gaat het.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Onder **Beheer**, klikt u op **Openingspagina&#39;s**.

   ![](assets/image2014-9-10-9-3a47-3a40.png)

1. In de **Openingspagina&#39;s** sectie, klikt u op **Bewerken**.

   ![](assets/image2014-9-10-9-3a47-3a12.png)

1. Voer uw domein- en paginagegevens in.

   | Term | Definitie |
   |---|---|
   | Domeinnaam voor bestemmingspagina&#39;s | Dit is uw NAAM. Een CNAME is het eerste deel van URL u mensen voor het landen van pagina&#39;s geeft. Bijvoorbeeld in `https://go.yourCompany.com`, het woord &quot;go&quot; is de CNAME. Je kan meerdere, maar de meeste mensen gebruiken gewoon het ene. |
   | Pagina voor alternatieven | Dit is waar je naartoe moet als de landingspagina niet bestaat of omlaag is. Meer informatie over [terugvalpagina&#39;s](/help/marketo/product-docs/administration/settings/set-a-fallback-page.md). |
   | Homepage | Voer de URL van uw bedrijfssite in. |

   ![](assets/three.png)

1. Controleer de **Vooraf ingevuld formulier** Schakel het selectievakje in om formulieren de mogelijkheid te bieden om vooraf gegevens in te vullen voor bekende (gekoelde) personen. Schakel de optie uit om te blokkeren.

   ![](assets/four.png)

1. Als u wilt voorkomen dat een kwaadaardige site uw inhoud lijkt te hosten, controleert u de **Marketo-pagina&#39;s niet insluiten in externe webpagina&#39;s** selectievakje.

   ![](assets/five.png)

   >[!NOTE]
   >
   >Als u de voorvoegsel wilt `<script>` -tag wordt weergegeven aan het einde van de `<head>` tag in de code, controleer de **Vooraf ingevulde script aan einde van kop injecteren** doos. Laat deze optie uitgeschakeld als u deze aan het begin wilt weergeven.
   >
   >Controleren **Standaardfavicon-koppelingen verwijderen** om te voorkomen dat Marketo een favicon-koppeling invoegt in de code.

1. Nadat u de selecties hebt gemaakt, klikt u op **Opslaan.**

   ![](assets/six.png)

   Geweldig werk! De bestemmingspagina&#39;s hebben nu de juiste informatie en moeten meteen aan het werk gaan.
