---
title: Office ve OneDrive'ı Windows Sanal Masaüstü'ne yükleme
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/5/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9004219"
- "10871"
ms.openlocfilehash: fb38f46cced928e33e16e8e83ad740dd83aea622
ms.sourcegitcommit: 254b25150fa326628084d08479b0e7dd8b7d479a
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 04/05/2021
ms.locfileid: "51596030"
---
# <a name="install-office-and-onedrive-on-windows-virtual-desktop"></a>Office ve OneDrive'ı Windows Sanal Masaüstü'ne yükleme

1. [Asıl VHD görüntüsünü hazırlama ve özelleştirme.](https://docs.microsoft.com/azure/virtual-desktop/set-up-customize-master-image) Henüz oluşturulmamış bir sanal makine (VM) oluşturun.

1. [Office'i paylaşılan bilgisayar etkinleştirme modunda yükleyin.](https://docs.microsoft.com/azure/virtual-desktop/install-office-on-wvd-master-image#install-office-in-shared-computer-activation-mode) Paylaşılan bilgisayar etkinleştirmesi, birden çok kullanıcının Office'e erişmelerine olanak sağlar.

1. [OneDrive'ı makine başına modda yükleyin.](https://docs.microsoft.com/azure/virtual-desktop/install-office-on-wvd-master-image#install-onedrive-in-per-machine-mode) Normalde, OneDrive kullanıcı başına yüklenir, ancak burada her makineye yüklenmiş olması gerekir.