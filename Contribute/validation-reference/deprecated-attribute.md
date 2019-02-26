---
title: deprecated-attribute
description: Docs 빌드 문제 deprecated-attribute에 대한 설명 및 해결 방법
author: meganbradley
ms.author: mbradley
ms.topic: error-reference
ms.date: 2/1/2019
ms.prod: non-product-specific
ms.openlocfilehash: 4f9ddc611d401bc7003e1b7d378517d5e374da87
ms.sourcegitcommit: a2c8317ccf8b56371773c84f4960a44787ce8666
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/15/2019
ms.locfileid: "56322686"
---
# <a name="deprecated-attribute"></a><span data-ttu-id="f139a-103">deprecated-attribute</span><span class="sxs-lookup"><span data-stu-id="f139a-103">deprecated-attribute</span></span>

<span data-ttu-id="f139a-104">**서비스 예정!**</span><span class="sxs-lookup"><span data-stu-id="f139a-104">**Coming soon!**</span></span>

[!INCLUDE [suggestion-note](includes/suggestion-note.md)]

## <a name="suggestion"></a><span data-ttu-id="f139a-105">제안</span><span class="sxs-lookup"><span data-stu-id="f139a-105">Suggestion</span></span>

`Deprecated attribute: ms.component. Use ms.subservice instead.`

<span data-ttu-id="f139a-106">`ms.service`를 사용하여 클라우드 서비스를 지정합니다.</span><span class="sxs-lookup"><span data-stu-id="f139a-106">Use `ms.service` to specify cloud services.</span></span> <span data-ttu-id="f139a-107">`ms.service`에 대한 더 자세한 정보를 지정하려면 필요에 따라 `ms.subservice`를 지정하면 됩니다.</span><span class="sxs-lookup"><span data-stu-id="f139a-107">To specify more detailed information about `ms.service`, you can optionally specify `ms.subservice`.</span></span> <span data-ttu-id="f139a-108">`ms.component`를 사용하지 마세요. 이 콘텐츠에 더 이상 사용되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="f139a-108">Don't use `ms.component`; it's deprecated for this content.</span></span>

## <a name="resolution"></a><span data-ttu-id="f139a-109">해결 방법</span><span class="sxs-lookup"><span data-stu-id="f139a-109">Resolution</span></span>

<span data-ttu-id="f139a-110">`ms.service` 값이 문서에 적합한지 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="f139a-110">Confirm that your `ms.service` value is correct for your article.</span></span> <span data-ttu-id="f139a-111">그런 다음, 유효한 `ms.subservice` 값을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="f139a-111">Then choose a valid `ms.subservice` value.</span></span>

<span data-ttu-id="f139a-112">유효한 값은 [이 Microsoft 내부 사이트](https://docsmetadatatool.azurewebsites.net/whitelists)에서 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f139a-112">Valid values can be found on [this Microsoft-internal site](https://docsmetadatatool.azurewebsites.net/whitelists).</span></span>

<!--make sure to add this file to your includes folder and verify the path-->
[!INCLUDE [validation-reference-help](includes/validation-reference-help.md)]