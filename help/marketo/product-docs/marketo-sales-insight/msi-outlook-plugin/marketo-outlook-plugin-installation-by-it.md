---
unique-page-id: 11382815
description: Installatie van de Plug-in Marketo Outlook door IT - Marketo Docs - Productdocumentatie
title: Installatie van de Plug-in Marketo Outlook door IT
translation-type: tm+mt
source-git-commit: 972cf9769ac751d9abfd5665975703dcd07930f0
workflow-type: tm+mt
source-wordcount: '175'
ht-degree: 0%

---


# Installatie van plug-in Marketo Outlook door IT {#marketo-outlook-plugin-installation-by-it}

Soms vereisen bedrijfsbeleid dat hun Team van IT alle software op hun werknemers&#39; computers installeert. In deze gevallen doet IT dit vaak op afstand met behulp van hun eigen implementatiesoftware. Dit document verstrekt de bevellijnen u als input tijdens het plaatsingsproces zou gebruiken om de outlook stop-in ver te installeren.

>[!PREREQUISITES]
>
>[Stel ](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/install-the-marketo-add-in-for-outlook-with-an-enterprise-key.md) de toets Enterprise in.

Voer de volgende bevellijn als &quot;Systeem&quot;of een Administratieve gebruikersrekening met de /i schakelaar in werking om te installeren.

`<pre>msiexec.exe /i [File Name] /qn REG=[Enterprise Key]</pre>`

>[!NOTE]
>
>**Voorbeeld**
>
>`<pre>msiexec.exe /i MarketoAddInSetup64.msi /qn REG=ABC9-123y-WXYZ-4321</pre>`

Voor het oplossen van problemen, kunt u registreren toelaten om een dossier van het outputlogboek tot stand te brengen.

`<pre>msiexec.exe /i [File Name] /qn /L*v MarketoAddin.log REG=[Enterprise Key]</pre>`

>[!NOTE]
>
>**Voorbeeld**
>
>`<pre>msiexec.exe /i MarketoAddInSetup64.msi /qn /L*v MarketoAddin.log REG=ABC9-123y-WXYZ-4321</pre>`

Als u een locatie voor de logbestanden wilt opgeven, geeft u het bestandspad op de opdrachtregel op.

`<pre>msiexec.exe /i [File Name] /qn /L*v [File Path]MarketoAddin.log REG=[Enterprise Key]</pre>`

>[!NOTE]
>
>**Voorbeeld**
>
>`<pre>msiexec.exe /i MarketoAddInSetup64.msi /qn /L*v C:\temp\MarketoAddin.log REG=ABC9-123y-WXYZ-4321</pre>`

>[!CAUTION]
>
>De opslaglocatie van het logbestand moet bestaan of de installatie wordt afgebroken.

Gelieve te verwijzen naar [de volledige lijst van Microsoft van schakelaars](https://support.microsoft.com/en-us/kb/227091) als u verschillende registrerenniveaus of gebruikersinterfaceniveaus zou willen proberen.

>[!MORELIKETHIS]
>
>[Marketo Outlook-insteekmodule verwijderd door IT](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/marketo-outlook-plugin-uninstall-by-it.md)
