---
unique-page-id: 2360297
description: Leer hoe te om Marketo logins toe te staan of te blokkeren door IP adres.
title: Marketo-aanmeldingen beperken op basis van IP
exl-id: 5d9d0b88-b4bc-4e1b-b70c-2c2e7b4269f5
feature: Administration
source-git-commit: e894ece3a643113fd3e1d8df9f8addefea5553f5
workflow-type: tm+mt
source-wordcount: '221'
ht-degree: 0%

---

# Marketo-aanmeldingen beperken op basis van IP {#restrict-marketo-logins-based-on-ip}

U kunt gebruikers beperken of toestaan om tot Marketo toegang te hebben die op hun IP adressen wordt gebaseerd. Zo gaat het.

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

>[!IMPORTANT]
>
>Adobe Admin Console (AAC) steunt [&#x200B; op IP-Gebaseerd toegangsbeheer &#x200B;](https://helpx.adobe.com/enterprise/using/ip-based-access.html){target="_blank"}. Om een vlotte overgang te verzekeren, zullen de bestaande beperkingen van Marketo Engage IP actief zijn met inbegrip van de gebruikers van Adobe ID door Q1 2027 in abonnementen waar deze eigenschap wordt toegelaten.
>
>* U kunt op AAC IP-Gebaseerde toegang op om het even welk ogenblik vormen.
>* Zowel de beperkingen van AAC als van Marketo Engage kunnen gelijktijdig lopen. Gebruik dezelfde IP-lijst van gewenste personen voor compatibiliteit.
>
>Na het eerste kwartaal van 2027 worden de Marketo Engage IP-beperkingen opgeheven. Op IP-Gebaseerde toegang zal uitsluitend door AAC worden beheerd en moet worden gevormd om login beperkingen af te dwingen. Een definitieve overgangsdatum wordt later bekendgemaakt.

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/restrict-marketo-logins-based-on-ip-1.png)

1. Klik op **[!UICONTROL Login Settings]**.

   ![](assets/restrict-marketo-logins-based-on-ip-2.png)

1. Klik op **[!UICONTROL Edit IP Restrictions]**.

   ![](assets/restrict-marketo-logins-based-on-ip-3.png)

1. Kies of u **&#x200B;**&#x200B;**specifieke adressen van het Blok wilt** toestaan of, ingaan het adres(sen), dan klikken **[!UICONTROL Save]**.

   >[!NOTE]
   >
   >**Definitie**
   >
   >* **[!UICONTROL Allowed IP addresses]**: Toegestane IP-adressen toevoegen is inclusief. Het zal alle IP gespecificeerde adressen omvatten en zal alles anders uitsluiten.
   >* **[!UICONTROL Block IP addresses]**: hiermee wordt voorkomen dat specifieke IP&#39;s toegang krijgen tot Marketo.
   >* **[!UICONTROL Disable IP Restrictions]**: Als u dit inschakelt, werken er geen/alle beperkingsregels meer. Gebruik dit voor testdoeleinden.

   >[!NOTE]
   >
   >U kunt meerdere beperkingen toevoegen, maar deze kunnen ALLES zijn toegestaan of ALLES geblokkeerd. Je kunt niet mixen en overeenkomen met toegestaan en geblokkeerd.

   ![](assets/restrict-marketo-logins-based-on-ip-4.png)
