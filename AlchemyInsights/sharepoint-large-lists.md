---
title: SharePoint büyük listeleri
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "407"
- "530001"
ms.assetid: ee07bf74-7aeb-4c47-8f5d-f496d6c09d79
ms.openlocfilehash: 1bc891a912c6753ea6c85d7d4b2a5d802080bd5c
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47720153"
---
# <a name="work-with-large-lists-and-libraries-in-sharepoint"></a><span data-ttu-id="95f21-102">SharePoint 'te büyük listelerle ve kitaplıklarla çalışma</span><span class="sxs-lookup"><span data-stu-id="95f21-102">Work with large lists and libraries in SharePoint</span></span>

<span data-ttu-id="95f21-103">SharePoint listeleri ve kitaplıkları 30.000.000 öğe içerebilir, ancak 5.000 ' den fazla öğe varsa, bunlarla çalışmayı denediğinizde bir liste görünümü eşik hatası görebilirsiniz.</span><span class="sxs-lookup"><span data-stu-id="95f21-103">SharePoint lists and libraries can contain up to 30 million items, but when they have more than 5,000 items, you might see a List View Threshold error when you try to work with them.</span></span> <span data-ttu-id="95f21-104">Bu eşik hizmetin performansını korumak için belirlenmiştir.</span><span class="sxs-lookup"><span data-stu-id="95f21-104">This threshold is in place to maintain performance of the service.</span></span> <span data-ttu-id="95f21-105">Değiştirilemez.</span><span class="sxs-lookup"><span data-stu-id="95f21-105">It can't be changed.</span></span> <span data-ttu-id="95f21-106">Bu eşiğe vurmamak için:</span><span class="sxs-lookup"><span data-stu-id="95f21-106">To avoid hitting this threshold:</span></span>

<span data-ttu-id="95f21-107">**Modern kullanın**</span><span class="sxs-lookup"><span data-stu-id="95f21-107">**Use modern**</span></span>

<span data-ttu-id="95f21-108">Modern deneyimde çok sayıda öğenin olduğu görünümler.</span><span class="sxs-lookup"><span data-stu-id="95f21-108">Views showing many items work best in the modern experience.</span></span> <span data-ttu-id="95f21-109">Klasik deneyimte görebileceğiniz hataları önlemek için [modern deneyimi kullanın](https://support.office.com/article/66dac24b-4177-4775-bf50-3d267318caa9) .</span><span class="sxs-lookup"><span data-stu-id="95f21-109">[Use the modern experience](https://support.office.com/article/66dac24b-4177-4775-bf50-3d267318caa9) to avoid errors you might see in the classic experience.</span></span>

<span data-ttu-id="95f21-110">**Dizin ekleme**</span><span class="sxs-lookup"><span data-stu-id="95f21-110">**Add indexes**</span></span>

<span data-ttu-id="95f21-111">Dizini olmayan bir sütuna filtre uyguladığınızda veya bunları sıraladığınızda, bir hata iletisi görebilirsiniz.</span><span class="sxs-lookup"><span data-stu-id="95f21-111">When you filter or sort by a column that doesn't have an index, you might see an error message.</span></span> <span data-ttu-id="95f21-112">Ayarlar menüsündeki **liste ayarlarından** ve ardından **Dizine alınan sütunlara**el ile [Dizin ekleyin](https://support.office.com/article/f3f00554-b7dc-44d1-a2ed-d477eac463b0) .</span><span class="sxs-lookup"><span data-stu-id="95f21-112">[Add an index](https://support.office.com/article/f3f00554-b7dc-44d1-a2ed-d477eac463b0) manually from **List Settings** in the settings menu, then **Indexed Columns**.</span></span>

<span data-ttu-id="95f21-113">**Liste görünümünü düzenleme**</span><span class="sxs-lookup"><span data-stu-id="95f21-113">**Edit the list view**</span></span>

<span data-ttu-id="95f21-114">Büyük bir listeyle çalışırken hata oluşursa, [liste görünümünüzü düzenleyin](https://support.office.com/article/15916903-e79a-423f-b4e2-02d37e1ff372).</span><span class="sxs-lookup"><span data-stu-id="95f21-114">If an error occurs when working with a large list, [edit your list view](https://support.office.com/article/15916903-e79a-423f-b4e2-02d37e1ff372).</span></span>

<span data-ttu-id="95f21-115">Aşağıdaki dört değişiklik liste görünümü eşik hatalarını kaldıracak.</span><span class="sxs-lookup"><span data-stu-id="95f21-115">The following four changes will remove list view threshold errors.</span></span> <span data-ttu-id="95f21-116">Tüm hataları kaldırmak için dört değişikliği de yapın.</span><span class="sxs-lookup"><span data-stu-id="95f21-116">Make all four changes to remove all errors.</span></span> <span data-ttu-id="95f21-117">Hala hatalar alıyorsanız, [büyük listeleri ve kitaplıkları Yönet](https://support.office.com/article/B8588DAE-9387-48C2-9248-C24122F07C59)'i işaretleyin.</span><span class="sxs-lookup"><span data-stu-id="95f21-117">If you are still getting errors, check [Manage large lists and libraries](https://support.office.com/article/B8588DAE-9387-48C2-9248-C24122F07C59).</span></span>

1. <span data-ttu-id="95f21-118">**İlk olarak sütunda** **yok** 'u seçin ve **sonra sütuna göre sıralayın**.</span><span class="sxs-lookup"><span data-stu-id="95f21-118">Select **None** from both **First sort by the column** and **Then sort by the column**.</span></span>
2. <span data-ttu-id="95f21-119">**İlk grubundan** **hiçbiri** 'ni seçin ve **ardından sütuna göre gruplandırın**.</span><span class="sxs-lookup"><span data-stu-id="95f21-119">Select **None** from both **First group by the column** and **Then group by the column**.</span></span>
3. <span data-ttu-id="95f21-120">**Toplamlar** bölümündeki tüm sütunlarda **yok 'u** seçin.</span><span class="sxs-lookup"><span data-stu-id="95f21-120">Select **None** for all columns in the **Totals** section.</span></span>
4. <span data-ttu-id="95f21-121">**Sütunlar** bölümünden görüntülenmek üzere bir sütun dışındaki tüm seçimleri kaldırın.</span><span class="sxs-lookup"><span data-stu-id="95f21-121">Deselect all but one column for display from the **Columns** section.</span></span>

