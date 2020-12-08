---
unique-page-id: 2359798
description: Aanvullende landingspaginanamen toevoegen - Marketo Docs - Productdocumentatie
title: Aanvullende landingspaginanamen toevoegen
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '244'
ht-degree: 0%

---


# Aanvullende landingspaginanamen toevoegen {#add-additional-landing-page-cnames}

U kunt bestemmingspagina CNAMEs willen toevoegen om verschillende URLs toe te staan om aan uw Marketo te richten landende pagina&#39;s. Als u de onderstaande stappen uitvoert, kunt u meerdere domeinen beheren.

>[!CAUTION]
>
>Cookies kunnen niet worden gedeeld in verschillende domeinen.

>[!TIP]
>
>**Hetzelfde topniveaudomein - Goed! Cookies zijn shared.go**.mijnbedrijf.com > **info**.mijnbedrijf.**comVerschillende domeinen op hoofdniveau - Slecht! Cookies worden niet gedeeld.**
>gaan.**mijnbedrijf**.com > ga.**mijnbedrijf**.com

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## De tekenreeks van uw account zoeken {#find-your-account-string}

1. Ga naar het **beheergebied** en klik op **Pagina&#39;s** landen.

   ![](assets/image2014-9-16-15-3a19-3a54.png)

1. Kopieer de **accounttekenreeks** uit de sectie **Instellingen** .

   ![](assets/image2014-9-16-15-3a20-3a2.png)

1. Noteer dit voor de volgende stap.

## Verzoek verzenden naar IT {#send-request-to-it}

1. Vraag uw afdeling van IT om volgende CNAME te installeren: (Vervang het woord [CNAME] door de CNAME van uw keuze en de TEKENREEKS [van de] ACCOUNT met de tekst van de vorige stap).

   [CNAME].YourCompany.com > [ACCOUNT STRING].mktoweb.com

## Een nieuwe NAAM toevoegen {#add-a-new-cname}

1. Nadat uw IT-afdeling de CNAME heeft gemaakt, gaat u naar **Admin** en klikt u op **Pagina&#39;s** landen.

   ![](assets/image2014-9-16-15-3a20-3a20.png)

1. Klik op **Nieuw** en selecteer **Nieuwe domeinalias**.

   ![](assets/image2014-9-16-15-3a20-3a28.png)

1. Voer uw **domeinalias in.** De **standaardpagina** wordt weergegeven als de bezoeker geen URL plaatst. Voer in dat geval in waar ze naartoe moeten.

   >[!NOTE]
   >
   >Voor de standaardpagina kunt u een openingspagina of een externe URL selecteren, zoals uw openbare website.

   ![](assets/image2014-9-16-15-3a20-3a36.png)

1. Voer de **standaardpagina** in en klik op **Maken**.

   ![](assets/image2014-9-16-15-3a20-3a43.png)

Mooi! Nu weet u wat te doen als u ooit een NAAM wilt toevoegen.
