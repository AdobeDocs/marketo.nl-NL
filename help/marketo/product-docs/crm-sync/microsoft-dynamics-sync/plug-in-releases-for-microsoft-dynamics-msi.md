---
unique-page-id: 10099102
description: Plug-inreleases voor Microsoft Dynamics MSI - Marketo Docs - Productdocumentatie
title: Plug-inreleases voor Microsoft Dynamics MSI
exl-id: 830f7dc3-07fd-429b-b0fd-290ffdda88e6
feature: Microsoft Dynamics
source-git-commit: 821d69736b1cbeac0c80718c58a7a3c471387545
workflow-type: tm+mt
source-wordcount: '309'
ht-degree: 7%

---

# Plug-inreleases voor Microsoft Dynamics MSI {#plug-in-releases-for-microsoft-dynamics-msi}

Wanneer u voor het eerst synchroniseert met Microsoft Dynamics, downloadt en installeert u de nieuwste versie van de plug-ins voor Marketo Sales Insight (MSI). Deze plug-ins worden regelmatig door het Marketo Engage bijgewerkt, zodat u naar dezelfde locatie kunt terugkeren om de nieuwe versie te downloaden.

Als u de Marketo-oplossing voor native CRM-synchronisatie gebruikt voor Dynamics, [de nieuwste plug-in downloaden](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md){target="_blank"} corresponding to your Dynamics release. For those who have a custom sync and have purchased Marketo Sales Insight, the [package is here](https://mktg-cdn.marketo.com/community/MarketoSalesInsight_NonNative.zip){target="_blank"}.

>[!NOTE]
>
>Deze versies werken voor zowel on-premise als online versies van Dynamiek.

## Een upgrade uitvoeren van uw MSI-oplossing {#upgrading-your-msi-solution}

1. De nieuwste versie van de oplossing importeren _over de bestaande versie_ van uw Dynamics CRM door op **[!UICONTROL Import]** in Dynamiek.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-1.png)

>[!NOTE]
>
>Voorbeeld: als uw Dynamics CRM versie 2.0.0.20 heeft en de nieuwste versie 2.0.0.21, zou u importeren _over_ versie 2.0.0.20.

1. Klik op **[!UICONTROL Next]**.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-2.png)

1. Selecteren **[!UICONTROL Stage for Upgrade]** en **[!UICONTROL Maintain customizations]** en klik vervolgens op **[!UICONTROL Import]**.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-3.png)

1. Klik op **[!UICONTROL Next]**.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-4.png)

1. Na een succesvolle invoer zult u twee oplossingen MSI zien: MarketoSalesInsight en MarketoSalesInsight_Upgrade. Selecteer de oudere oplossing en klik op Upgrade van oplossing toepassen.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-5.png)

En dat is het! Na de verbetering zult u slechts één Oplossing MSI zien.

## Versie-updates {#version-updates}

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th colspan="1">Releasedatum</th> 
   <th colspan="1">Versie</th> 
   <th colspan="1">Notities</th> 
  </tr> 
  <tr> 
   <td colspan="1">02/03/22</td> 
   <td colspan="1">2.0.0.27</td> 
   <td colspan="1">Accountlay-out voor inzichten: interessante momenten, Score-wijzigingen, webactiviteiten, e-mailactiviteiten</td> 
  </tr>
  <tr> 
   <td colspan="1">01/05/22</td> 
   <td colspan="1">2.0.0.26</td> 
   <td colspan="1">Programmaadoptiescore voor verzenden van e-mail</td> 
  </tr>
  <tr> 
   <td colspan="1">10/28/21</td> 
   <td colspan="1">2.0.0.25</td> 
   <td colspan="1">Metriek van de Score van de Aanneming van het product, nieuw Globaal Dashboard (de Activiteit van het Web, E-mail, Beste Bets)</td> 
  </tr>
  <tr> 
   <td colspan="1">02/10/21</td> 
   <td colspan="1">2.0.0.22</td> 
   <td colspan="1">Auto controle toegelaten en documentatieveranderingen op oplossing MSI verwijderen</td> 
  </tr>
  <tr> 
   <td colspan="1">10/01/20</td> 
   <td colspan="1">2.0.0.21</td> 
   <td colspan="1">Bug Fix: Het toewijzen van toegang tot MSI API configuratiegebieden voor gebruikers met de rol van het Inzicht van de Verkoop</td> 
  </tr> 
  <tr> 
   <td colspan="1">07/20/20</td> 
   <td colspan="1">2.0.0.20</td> 
   <td colspan="1">Opgeloste fout: een validatiebericht toevoegen voor niet-gesynchroniseerde records</td> 
  </tr> 
  <tr> 
   <td colspan="1">06/12/20</td> 
   <td colspan="1">2.0.0.19</td> 
   <td colspan="1">Opgeloste fout: MSI-wachtwoord verbergen in MSD API-configuratie</td> 
  </tr> 
  <tr> 
   <td colspan="1">05/26/20</td> 
   <td colspan="1">2.0.0.18</td> 
   <td colspan="1">Foutopsporing: de validatie van de MSI-rol-id wijzigen voor het weergeven van MSI-knoppen</td> 
  </tr> 
  <tr> 
   <td colspan="1">05/21/20</td> 
   <td colspan="1">2.0.0.17</td> 
   <td colspan="1">Foutopsporing: het veld Eigenaar verbergen opheffen en velden niet-verplicht maken</td> 
  </tr> 
  <tr> 
   <td colspan="1">04/28/20</td> 
   <td colspan="1">2.0.0.16</td> 
   <td colspan="1">Bugfixatie: koppelingsafhankelijkheid verwijderen van MSD CRM sitemap-instelling</td> 
  </tr> 
 </tbody> 
</table>
