---
unique-page-id: 11382829
description: Marketo  [!DNL Outlook]  Insteekmodule die door IT - Marketo Docs - Documentatie van het Product wordt verwijderd
title: Marketo  [!DNL Outlook]  Insteekmodule Uninstall door IT
exl-id: 678684da-3e99-462f-9950-504df1c1bb1e
feature: Marketo Sales Insights
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '114'
ht-degree: 0%

---

# Marketo [!DNL Outlook] -insteekmodule verwijderd door IT {#marketo-outlook-plugin-uninstall-by-it}

Hieronder wordt beschreven hoe IT de Marketo [!DNL Outlook] -plug-in extern kan verwijderen.

Voer de volgende bevellijn als zoals &quot;Systeem&quot;of een Administratieve gebruikersrekening met de /x schakelaar in werking om te desinstalleren.

`<pre>msiexec.exe /x [File Name] /qn </pre>`

>[!NOTE]
>
>**Voorbeeld**
>
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn </pre>`

Voor het oplossen van problemen kunt u registreren toelaten om een dossier van het outputlogboek tot stand te brengen.

`<pre>msiexec.exe /x [File Name] /qn /L*v MarketoAddinUninstall.log</pre>`

>[!NOTE]
>
>**Voorbeeld**
>
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn /L*v MarketoAddinUninstall.log</pre>`

Als u een locatie voor de logbestanden wilt opgeven, geeft u het bestandspad op de opdrachtregel op.

`<pre>msiexec.exe /x [File Name] /qn /L*v [File Path]MarketoAddinUninstall.log</pre>`

>[!NOTE]
>
>**Voorbeeld**
>
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn /L*v C:\temp\MarketoAddinUninstall.log</pre>`

>[!CAUTION]
>
>Als u de insteekmodule verwijdert, wordt [!DNL Outlook] op de computer van de gebruiker geforceerd gesloten.

Gelieve te verwijzen [ volledige lijst van de Microsoft van schakelaars ](https://support.microsoft.com/en-us/office/command-line-switches-for-microsoft-office-products-079164cd-4ef5-4178-b235-441737deb3a6) als u verschillende registrerenniveaus of gebruikersinterfaceniveaus zou willen proberen.
