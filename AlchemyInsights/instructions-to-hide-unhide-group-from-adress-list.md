---
title: Grubu adres listesinden gizleme/gizleme yönergeleri
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "3161"
ms.openlocfilehash: 02368d6a06df90d76ee1bd5448819e7ffe12c18c
ms.sourcegitcommit: f28dafa0f727870038f72bc904da926daf4ec07b
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 06/05/2020
ms.locfileid: "44580029"
---
# <a name="hide-microsoft-365-group-from-address-list-gal"></a>Microsoft 365 grubunu adres listesinden gizleme (GAL)

Microsoft 365 grubunu Exchange istemcilerinin adres listelerinden (GAL) gizlemek için EXO kabuğunda aşağıdaki komutu kullanın:

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

Microsoft 365 grubunu Exchange istemcilerine görünür olmasını gizlemek için EXO kabuğunda aşağıdaki komutu kullanın:

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`

