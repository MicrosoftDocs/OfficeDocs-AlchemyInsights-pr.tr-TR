---
title: Microsoft Edge'e (Chromium) Google Chrome uzantıları bağlantı noktası
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/03/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004032"
- "7102"
- "8297"
- "9004617"
ms.openlocfilehash: 1c71d74d01c1e38e4c7789aea2c0b43701b3a5de
ms.sourcegitcommit: 7b2e5078dd65f11af6650e692a7ea48e91f544e0
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 04/02/2021
ms.locfileid: "51505304"
---
# <a name="port-google-chrome-extensions-to-microsoft-edge-chromium"></a>Microsoft Edge'e (Chromium) Google Chrome uzantıları bağlantı noktası

Google Chrome uzantılarını [Microsoft Edge'e (Chromium) kolayca](https://docs.microsoft.com/microsoft-edge/extensions-chromium/developer-guide/port-chrome-extension)taşınabilir. Çoğu durumda, bu uzantıları Microsoft Edge'de çalıştırmak için yalnızca az değişiklik gereklidir.

Google Chrome tarafından desteklenen uzantı API'leri ve bildirim anahtarları Microsoft Edge ile kodla uyumludur. Bununla birlikte, Microsoft Edge API'ler chrome.obm, chrome.identity.getAccounts, chrome.identity.getAuthToken ve chrome.instanceID uzantılarını desteklemez.