---
title: Ciklo duomenų eksportavimas
description: Eksportuoti produkto ciklo informaciją
ms.date: 11/29/2020
layout: ContentPage
ms.openlocfilehash: 210af0cf60630cbdbf43847641022283aca78366
ms.sourcegitcommit: 272dedcf92e644b57865e78c716f937b66e534c3
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 12/08/2020
ms.locfileid: "1335893"
---
# <a name="lifecycle-data-export"></a><span data-ttu-id="a9afc-103">Ciklo duomenų eksportavimas</span><span class="sxs-lookup"><span data-stu-id="a9afc-103">Lifecycle data export</span></span>

## <a name="export-all-products"></a><span data-ttu-id="a9afc-104">Eksportuoti visus produktus</span><span class="sxs-lookup"><span data-stu-id="a9afc-104">Export all products</span></span>
<span data-ttu-id="a9afc-105">Eksportuokite visų produktų ciklo duomenis spustelint žemiau:</span><span class="sxs-lookup"><span data-stu-id="a9afc-105">Export lifecycle data for all products by clicking below:</span></span>

> [!div class="nextstepaction"]
> [<span data-ttu-id="a9afc-106">Eksportuoti visus produktus</span><span class="sxs-lookup"><span data-stu-id="a9afc-106">Export All Products</span></span>](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export)

## <a name="export-products-by-family-and-group"></a><span data-ttu-id="a9afc-107">Eksportuoti produktus pagal šeimą ir grupę</span><span class="sxs-lookup"><span data-stu-id="a9afc-107">Export products by Family and Group</span></span>
<span data-ttu-id="a9afc-108">Pasirinkite šeimą, tada – grupę, kuri bus eksportuojama.</span><span class="sxs-lookup"><span data-stu-id="a9afc-108">Select a Family and then a Group to export.</span></span> <span data-ttu-id="a9afc-109">Pastaba. Eksportavimas prasidės pasirinkus reikšmę „Grupė“.</span><span class="sxs-lookup"><span data-stu-id="a9afc-109">Note: Export will begin when Group value is selected.</span></span> 

> [!div class="op_multi_selector" title1="Šeima" title2="Grupė"]
> - [(.NET | Visi)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='.NET'))
> - [(.NET | .NET)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='.NET',group='.NET'))
> - [(„Azure“ | Visi)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure'))
> - [(„Azure“ | Dirbtinis intelektas)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='AI'))
> - [(„Azure“ | „Azure“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='Azure'))
> - [(„Azure“ | Duomenų bazės)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='Databases'))
> - [(„Azure“ | Kita)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='Other'))
> - [(„Dynamics“ | Visi)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics'))
> - [(„Dynamics“ | „Dynamics“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics'))
> - [(„Dynamics“ | „Dynamics 365“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20365'))
> - [(„Dynamics“ | „Dynamics AX“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20AX'))
> - [(„Dynamics“ | „Dynamics C5“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20C5'))
> - [(„Dynamics“ | „Dynamics CRM“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20CRM'))
> - [(„Dynamics“ | „Dynamics GP“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20GP'))
> - [(„Dynamics“ | „Dynamics NAV“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20NAV'))
> - [(„Dynamics“ | „Dynamics POS“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20POS'))
> - [(„Dynamics“ | „Dynamics RMS“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20RMS'))
> - [(„Dynamics“ | „Dynamics SL“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20SL'))
> - [(„Dynamics“ | Kita)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Other'))
> - [(„Expression“ | Visi)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Expression'))
> - [(„Expression“ | „Expression“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Expression',group='Expression'))
> - [(„Microsoft 365“ | Visi)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20365'))
> - [(„Microsoft 365“ | „Enterprise Mobility + Security“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20365',group='Enterprise%20Mobility%20%2B%20Security'))
> - [(„Microsoft 365“ | Tapatybės valdymas)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20365',group='Identity%20Management'))
> - [(„Microsoft Connected Services Framework“ | Visi)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Connected%20Services%20Framework'))
> - [(„Microsoft Connected Services Framework“ | „Connected Services Framework“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Connected%20Services%20Framework',group='Connected%20Services%20Framework'))
> - [(„Microsoft Customer Care Framework“ | Visi)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Customer%20Care%20Framework'))
> - [(„Microsoft Customer Care Framework“ | „Customer Care Framework“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Customer%20Care%20Framework',group='Customer%20Care%20Framework'))
> - [(„Microsoft Edge“ | Visi)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Edge'))
> - [(„Microsoft Edge“ | „Edge“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Edge',group='Edge'))
> - [(„Microsoft Internet Explorer“ | Visi)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Internet%20Explorer'))
> - [(„Microsoft Internet Explorer“ | „Internet Explorer“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Internet%20Explorer',group='Internet%20Explorer'))
> - [(„Microsoft Office“ | Visi)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office'))
> - [(„Microsoft Office“ | Klientas)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office',group='Client'))
> - [(„Microsoft Office“ | Sauga)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office',group='Security'))
> - [(„Microsoft Office“ | Serveris)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office',group='Server'))
> - [(„Microsoft“ serveriai | Visi)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers'))
> - [(„Microsoft“ serveriai | „BizTalk Server“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='BizTalk%20Server'))
> - [(„Microsoft“ serveriai | „Commerce Server“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Commerce%20Server'))
> - [(„Microsoft“ serveriai | „Content Management Server“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Content%20Management%20Server'))
> - [(„Microsoft“ serveriai | „Host Integration Server“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Host%20Integration%20Server'))
> - [(„Microsoft“ serveriai | „Intelligent Application Gateway“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Intelligent%20Application%20Gateway'))
> - [(„Microsoft“ serveriai | Saugumas)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Security'))
> - [(„Microsoft“ sistemos centras | Visi)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20System%20Center'))
> - [(„Microsoft“ sistemos centras | Sistemos centras)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20System%20Center',group='System%20Center'))
> - [(„Silverlight“ | Visi)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Silverlight'))
> - [(„Silverlight“ | „Silverlight“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Silverlight',group='Silverlight'))
> - [(„SQL Server“ | Visi)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='SQL%20Server'))
> - [(„SQL Server“ | „Power BI“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='SQL%20Server',group='Power%20BI'))
> - [(„SQL Server“ | „SQL Server“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='SQL%20Server',group='SQL%20Server'))
> - [(„Visual Studio“ | Visi) ](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Visual%20Studio'))
> - [(„Visual Studio“ | „Visual Studio“)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Visual%20Studio',group='Visual%20Studio'))
> - [(„Windows“ | Visi)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows'))
> - [(„Windows“ | Klientas)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Client'))
> - [(„Windows“ | „IoT“](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='IoT'))
> - [(„Windows“ | Mobilusis)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Mobile'))
> - [(„Windows“ | Sauga)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Security'))
> - [(„Windows“ | Serveris)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Server'))

## <a name="export-products-by-end-of-support-date"></a><span data-ttu-id="a9afc-170">Eksportuoti produktus pagal palaikymo pabaigos datą</span><span class="sxs-lookup"><span data-stu-id="a9afc-170">Export products by end of support date</span></span>
<span data-ttu-id="a9afc-171">Pasirinkite metus, kad pamatytumėte produktus, kurių palaikymo pabaiga artėja.</span><span class="sxs-lookup"><span data-stu-id="a9afc-171">Select a year to see products reaching the end of support.</span></span> <span data-ttu-id="a9afc-172">Pastaba. Eksportavimas prasidės pasirinkus reikšmę „Metai“.</span><span class="sxs-lookup"><span data-stu-id="a9afc-172">Note: Export will begin when Year value is selected.</span></span>

> [!div class="op_single_selector"]
> - [Kiti 12 mėnesių](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportMonths=12))
> - [Kiti 6 mėnesiai](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportMonths=6))
> - [2015](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2015))
> - [2016](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2016))
> - [2017](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2017))
> - [2018](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2018))
> - [2019](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2019))
> - [2020](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2020))
> - [2021](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2021))
> - [2022](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2022))
> - [2023](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2023))
> - [2024](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2024))
> - [2025](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2025))
> - [2026](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2026))
> - [2027](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2027))
> - [2028](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2028))
> - [2029](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2029))
> - [2030](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2030))
