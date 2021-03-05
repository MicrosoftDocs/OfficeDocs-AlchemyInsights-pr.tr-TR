---
title: MIM Eşitleme hizmetini yapılandırma
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/19/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "8472"
- "9004688"
ms.openlocfilehash: 48e9a0e8c26088b690092bfaedfba641841739f6
ms.sourcegitcommit: 379e132c4d21ecf703d5506484ec96a767fdda39
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 03/04/2021
ms.locfileid: "50482894"
---
# <a name="configure-mim-sync-service"></a><span data-ttu-id="c0b28-102">MIM Eşitleme hizmetini yapılandırma</span><span class="sxs-lookup"><span data-stu-id="c0b28-102">Configure MIM Sync service</span></span>

<span data-ttu-id="c0b28-103">Microsoft Identity Manager (MIM) Eşitleme Hizmeti, MIM'nin bir bileşenidir.</span><span class="sxs-lookup"><span data-stu-id="c0b28-103">Microsoft Identity Manager (MIM) Synchronization Service is a component of MIM.</span></span> <span data-ttu-id="c0b28-104">Birden çok şirket içi dizine ve veritabanına sahip kuruluşlar için bilgileri depolar ve tümleştiren merkezi bir şirket içi hizmettir.</span><span class="sxs-lookup"><span data-stu-id="c0b28-104">It is a centralized on-premises service that stores and integrates information for organizations that have multiple on-premises directories and databases.</span></span> <span data-ttu-id="c0b28-105">Sorun yakın zamanda MIM güncelleştirmesinde ele alındı ise veya aşağıdaki bölümde adı geçen diğer sorunlardan biri ise MIM Eşitleme ile ilgili sorununuzu çözebilirsiniz.</span><span class="sxs-lookup"><span data-stu-id="c0b28-105">You may be able to resolve your problem with MIM Sync if the issue was addressed in a recent update to MIM or is one of the other issues mentioned in the below section.</span></span>

<span data-ttu-id="c0b28-106">**Önerilen adımlar**</span><span class="sxs-lookup"><span data-stu-id="c0b28-106">**Recommended steps**</span></span>

1. <span data-ttu-id="c0b28-107">MIM Eşitleme'nin son güncelleştirmesini kullanırkenn emin olun ve bir güncelleştirmede sorunun çözülmüş olup olmadığını belirlemek için [MIM Sync](https://docs.microsoft.com/microsoft-identity-manager/reference/version-history) sürüm notlarına bakın.</span><span class="sxs-lookup"><span data-stu-id="c0b28-107">Ensure that you are using a recent update of MIM Sync and check the [MIM Sync release notes](https://docs.microsoft.com/microsoft-identity-manager/reference/version-history) to determine if the issue has been resolved in an update.</span></span>
2. <span data-ttu-id="c0b28-108">Sorun Generic LDAP, Generic SQL, Lotus Domino veya Web Services bağlayıcısı ile ilgili ise, genel bağlayıcıların son güncelleştirmesini [kullanırkenn emin olun.](https://docs.microsoft.com/microsoft-identity-manager/reference/microsoft-identity-manager-2016-connector-version-history)</span><span class="sxs-lookup"><span data-stu-id="c0b28-108">If the problem is with the Generic LDAP, Generic SQL, Lotus Domino or Web Services connector, ensure that you are using a recent update of the [generic connectors](https://docs.microsoft.com/microsoft-identity-manager/reference/microsoft-identity-manager-2016-connector-version-history).</span></span>
3. <span data-ttu-id="c0b28-109">MIM Eşitleme çalıştırması hatayla durursa, olası nedenleri belirlemek [için çalıştırma](https://docs.microsoft.com/microsoft-identity-manager/reference/maerrorcodes) hata kodları tablosuna bakın.</span><span class="sxs-lookup"><span data-stu-id="c0b28-109">If an MIM Sync-run stops with an error, consult the table of [run error codes](https://docs.microsoft.com/microsoft-identity-manager/reference/maerrorcodes) to determine the potential causes.</span></span>
4. <span data-ttu-id="c0b28-110">**Uzantı-dll-özel** durumu ile çalıştırma durursa, Bağlayıcı Alanı  Nesnesi özellikler penceresini açmak için bu sözcüklere tıklayın ve Temel neden hakkında daha fazla bilgi görmek için [Uzantı-DLL-Özel](https://social.technet.microsoft.com/wiki/contents/articles/7515.fim-troubleshooting-extension-dll-exception.aspx)Durum'da açıklandığı gibi Yığın **İzleme...'ye** tıklayın.</span><span class="sxs-lookup"><span data-stu-id="c0b28-110">If the run stops with **extension-dll-exception**, then click on those words to open the **Connector Space Object properties** window, and click on **Stack Trace...** to see more information on the underlying cause, as described in [Extension-DLL-Exception](https://social.technet.microsoft.com/wiki/contents/articles/7515.fim-troubleshooting-extension-dll-exception.aspx).</span></span>
5. <span data-ttu-id="c0b28-111">Parola Değişikliği Bildirim Hizmeti (PCNS) bileşeni, parola eşitlemesi sırasında olay günlüğünde **6025** hatasını bildiriyorsa, [PCNS raporlama hatası 6025](https://social.technet.microsoft.com/wiki/contents/articles/4159.pcns-troubleshooting-event-id-6025.aspx)ile ilgili sorun giderme kılavuzunu kontrol edin.</span><span class="sxs-lookup"><span data-stu-id="c0b28-111">If the Password Change Notification Service (PCNS) component reports **error 6025** in the event log during password synchronization, check the guide for troubleshooting [PCNS reporting error 6025](https://social.technet.microsoft.com/wiki/contents/articles/4159.pcns-troubleshooting-event-id-6025.aspx).</span></span>
6. <span data-ttu-id="c0b28-112">FIM Hizmet Yönetimi Aracısı ile tam eşitleme  yavaşsa, TempDB için otomatik büyüme ayarını kontrol edin. Sorun giderme yavaş veya asılı tam eşitlemede açıklandığı [gibi.](https://social.technet.microsoft.com/wiki/contents/articles/14713.troubleshooting-fim-performance-slow-or-hanging-full-synchronization.aspx)</span><span class="sxs-lookup"><span data-stu-id="c0b28-112">If full synchronization with the FIM Service Management Agent is slow, check the **auto grow** setting for TempDB, as described in [Troubleshooting slow or hanging full synchronization](https://social.technet.microsoft.com/wiki/contents/articles/14713.troubleshooting-fim-performance-slow-or-hanging-full-synchronization.aspx).</span></span>
7. <span data-ttu-id="c0b28-113">FIM Hizmet Yönetimi Aracısını kullanarak başarısız oluşturma-yoluyla web-hizmetleriyle durduruldu sunucusu hatasıyla karşılaşıyorsanız, nedenlere genel bakış için [Destek-Bilgi: başarısız oluşturma-web-hizmetleri](https://docs.microsoft.com/archive/blogs/iamsupport/support-info-fimma-failed-creation-via-web-services) hakkında bilgi için bkz.</span><span class="sxs-lookup"><span data-stu-id="c0b28-113">If you are encountering an error of stopped-server with failed-creation-via-web-services using the FIM Service Management Agent, see [Support-Info: failed-creation-via-web-services](https://docs.microsoft.com/archive/blogs/iamsupport/support-info-fimma-failed-creation-via-web-services) for an overview of causes.</span></span>

