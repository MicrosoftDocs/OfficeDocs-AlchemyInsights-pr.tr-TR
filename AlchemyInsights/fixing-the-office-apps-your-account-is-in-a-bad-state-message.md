---
title: Microsoft 365 uygulamalarını düzeltme hesabınız hatalı bir durumda
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2558"
- "9000571"
ms.openlocfilehash: ec529291ec9406eba9dc2b0f2cc7a93c77fa3456
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47744565"
---
# <a name="fixing-the-microsoft-365-apps-your-account-is-in-a-bad-state-error"></a><span data-ttu-id="3ef3a-102">Microsoft 365 uygulamalarının "hesabınız hatalı bir durumda</span><span class="sxs-lookup"><span data-stu-id="3ef3a-102">Fixing the Microsoft 365 apps "Your account is in a bad state" error</span></span>

<span data-ttu-id="3ef3a-103">Bu hatayı düzeltmek için etkilenen bilgisayarda aşağıdaki seçenekleri deneyin:</span><span class="sxs-lookup"><span data-stu-id="3ef3a-103">To fix this error, try the following options on the affected computer:</span></span>

- <span data-ttu-id="3ef3a-104">Bir Office uygulamasını açın, **Dosya**  >  **hesabı**'nı  >  **Tüm hesaplarda oturumu Kapat**'ı seçin.</span><span class="sxs-lookup"><span data-stu-id="3ef3a-104">Open an Office app, select **File** > **Account** > **Sign Out of all accounts**.</span></span> <span data-ttu-id="3ef3a-105">Geçerli lisansa sahip bir kullanıcı hesabını kullanarak yeniden oturum açın.</span><span class="sxs-lookup"><span data-stu-id="3ef3a-105">Sign in again using a user account with a valid license.</span></span> <span data-ttu-id="3ef3a-106">Ayrıntılı bilgi için bkz. [Office’te Hesaplar](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span><span class="sxs-lookup"><span data-stu-id="3ef3a-106">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="3ef3a-107">Windows kimlik bilgileri Yöneticisi 'Ni kullanarak [Office kimlik bilgilerini temizleyin](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) .</span><span class="sxs-lookup"><span data-stu-id="3ef3a-107">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br>
  <span data-ttu-id="3ef3a-108">**Not:** Office 2016 için kayıt defteri yolları 16,0 olarak değiştirilmiştir.</span><span class="sxs-lookup"><span data-stu-id="3ef3a-108">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="3ef3a-109">Örneğin, \Software\Microsoft\Office\16.0\Common\Identity</span><span class="sxs-lookup"><span data-stu-id="3ef3a-109">For example, \Software\Microsoft\Office\16.0\Common\Identity</span></span>\
- <span data-ttu-id="3ef3a-110">Office 2013 kullanarak Office 365 ' a bağlanırken hata oluşursa, Office istemcisinde [modern kimlik doğrulamasını etkinleştirin](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication) .</span><span class="sxs-lookup"><span data-stu-id="3ef3a-110">If the error occurs while connecting to Office 365 using Office 2013, [enable modern authentication](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication) for the Office client.</span></span>

<span data-ttu-id="3ef3a-111">Daha fazla bilgi için, [Microsoft 365, Azure veya Intune 'da oturum açmayan tarayıcı olmayan uygulamalarda nasıl sorun giderileceği](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1)bölümüne bakın.</span><span class="sxs-lookup"><span data-stu-id="3ef3a-111">For more information, see [How to troubleshoot non-browser apps that can't sign in to Microsoft  365, Azure, or Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).</span></span>

