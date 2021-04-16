---
title: Microsoft 365 uygulamalarını düzeltme Hesabınız kötü durumda
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2558"
- "9000571"
ms.openlocfilehash: 4654b49289a455c1e6641f47fae573d2fcebc717
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51812556"
---
# <a name="fixing-the-microsoft-365-apps-your-account-is-in-a-bad-state-error"></a><span data-ttu-id="21064-102">Microsoft 365 uygulamaları "Hesabınız kötü durumda" hatasını düzeltme</span><span class="sxs-lookup"><span data-stu-id="21064-102">Fixing the Microsoft 365 apps "Your account is in a bad state" error</span></span>

<span data-ttu-id="21064-103">Bu hatayı düzeltmek için, etkilenen bilgisayarda aşağıdaki seçenekleri deneyin:</span><span class="sxs-lookup"><span data-stu-id="21064-103">To fix this error, try the following options on the affected computer:</span></span>

- <span data-ttu-id="21064-104">Bir Office uygulamasını açın, Tüm  >  **hesapların Dosya Hesabı** Oturum  >  **Açma'sını seçin.**</span><span class="sxs-lookup"><span data-stu-id="21064-104">Open an Office app, select **File** > **Account** > **Sign Out of all accounts**.</span></span> <span data-ttu-id="21064-105">Geçerli bir lisansa sahip bir kullanıcı hesabı kullanarak yeniden oturum açın.</span><span class="sxs-lookup"><span data-stu-id="21064-105">Sign in again using a user account with a valid license.</span></span> <span data-ttu-id="21064-106">Ayrıntılı bilgi için bkz. [Office’te Hesaplar](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span><span class="sxs-lookup"><span data-stu-id="21064-106">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="21064-107">Windows [Kimlik Bilgileri Yöneticisi'ni](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) kullanarak Office kimlik bilgilerini temizleme.</span><span class="sxs-lookup"><span data-stu-id="21064-107">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br>
  <span data-ttu-id="21064-108">**Not:** Office 2016'nın kayıt defteri yolları 16.0 olarak değişti.</span><span class="sxs-lookup"><span data-stu-id="21064-108">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="21064-109">Örneğin, \Software\Microsoft\Office\16.0\Common\Identity</span><span class="sxs-lookup"><span data-stu-id="21064-109">For example, \Software\Microsoft\Office\16.0\Common\Identity</span></span>\
- <span data-ttu-id="21064-110">Office 2013'ü kullanarak Office 365'e bağlanırken hata oluşursa, Office istemcisi için [modern kimlik](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication) doğrulamayı etkinleştirin.</span><span class="sxs-lookup"><span data-stu-id="21064-110">If the error occurs while connecting to Office 365 using Office 2013, [enable modern authentication](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication) for the Office client.</span></span>

<span data-ttu-id="21064-111">Daha fazla bilgi için [bkz. Microsoft 365, Azure veya Intune'da](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1)oturum alamayan tarayıcı olmayan uygulamaların sorunlarını giderme.</span><span class="sxs-lookup"><span data-stu-id="21064-111">For more information, see [How to troubleshoot non-browser apps that can't sign in to Microsoft  365, Azure, or Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).</span></span>

