---
title: .NET 문서 참여에 대한 음성 및 톤 지침
description: 지침을 따르지 않는 예와 비교하여 스타일의 예를 통해 음성 및 톤 지침을 알아봅니다.
ms.topic: contributor-guide
ms.prod: non-product-specific
ms.custom: external-contributor-guide
ms.date: 11/07/2018
ms.openlocfilehash: 4108019ac50d703c6dd509eca7a6394cc1c9dc18
ms.sourcegitcommit: ca84e542b081e145052f38967e826f6ef25da1b2
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/12/2019
ms.locfileid: "72288488"
---
# <a name="voice-and-tone-guidelines"></a>음성 및 톤 지침

IT 전문가 및 개발자를 비롯한 다양한 사람들이 .NET을 배우고 정규 작업에 사용하기 위해 설명서를 읽습니다. 목표는 reader가 경험을 하는 데 도움이 되는 훌륭한 설명서를 만드는 것입니다. 지침이 도움을 줍니다. 스타일 가이드에는 다음 권장 사항이 포함되어 있습니다.

이 스타일 가이드를 읽을 때 각 예제를 볼 수 있습니다. .NET용 설명서를 빌드할 때 따라야 할 예제를 제공하기 위해 지침에 따라 이 가이드를 작성했습니다. 대조적인 샘플도 제공되므로 지침을 따르지 않을 때 문서가 어떤 모습인지 확인할 수 있습니다.

## <a name="use-a-conversational-tone"></a>대화체 사용

### <a name="appropriate-style"></a>적절한 스타일

문서가 대화체로 이루어지도록 합니다. 자습서나 설명을 읽을 때 마치 작성자와 대화를 하고 있는 것처럼 느껴야 합니다. 이 경험은 비공식적이고, 대화적이며, 유익해야 합니다. Reader는 마치 작성자가 개념을 설명하는 것을 듣고 있는 것처럼 느껴야 합니다.

### <a name="inappropriate-style"></a>부적절한 스타일

대화식 스타일과 기술적인 항목을 좀 더 학술적으로 다루는 스타일 사이의 대비를 볼 수 있을 것입니다. 이러한 리소스는 매우 유용하지만 작성자는 설명서와는 매우 다른 스타일로 해당 문서를 작성했습니다. 학술지를 읽을 때 매우 다른 톤과 매우 다른 문체를 볼 수 있습니다. 매우 무미건조한 항목에 대한 흥미 없는 계정을 읽고 있다고 느낄 수 있습니다.  

위의 첫 번째 단락은 권장 대화 스타일을 따릅니다. 두 번째는 좀 더 학문적인 스타일입니다. 그 차이를 바로 볼 수 있습니다. 

## <a name="write-in-second-person"></a>2인칭으로 작성

### <a name="appropriate-style"></a>적절한 스타일

reader에게 직접 말하는 것처럼 문서를 작성해야 합니다. 2인칭을 자주 사용해야 합니다(이러한 두 문장에서 했던 것처럼). 2인칭이 항상 ‘너’라는 단어를 사용하는 의미는 아닙니다. reader에게 직접 작성합니다. 명령문을 작성합니다. 배우고 싶은 것을 reader에게 알려주세요.

### <a name="inappropriate-style"></a>부적절한 스타일

작성자는 또한 3인칭으로 작성하는 것을 선택할 수 있습니다. 해당 모델에서 작성자는 reader를 언급할 때 사용할 대명사나 명사를 찾아야 합니다. reader는 종종 이 3인칭 스타일이 매력적이지 않고 읽기에 덜 흥미로울 수 있습니다.

첫 번째 단락은 권장 스타일을 따릅니다. 두 번째는 3인칭을 사용합니다. 2인칭으로 작성하세요. 아마도 읽기가 더 쉽다는 것을 알 수 있을 것입니다.

## <a name="use-active-voice"></a>능동태 사용

능동태로 문서를 작성합니다. 능동태란 해당 문장의 주체가 해당 문장의 동작(동사)을 수행한다는 의미입니다. 문장 주체가 시행되도록 문장을 배열하는 수동태와 대조를 이룹니다. 다음 두 가지 예를 대조해 보세요.

>컴파일러가 소스 코드를 실행 파일로 변환했습니다.

>소스 코드는 컴파일러에 의해 실행 파일로 변환되었습니다.

첫 번째 문장은 능동태를 사용한 것입니다. 두 번째 문장은 수동태로 작성되었습니다. (이러한 두 문장은 각 스타일의 다른 예를 제공합니다).

더 읽기 쉽기 때문에 능동태를 권장합니다. 수동태는 읽기가 더 어려울 수 있습니다.

## <a name="target-a-fifth-grade-reading-level"></a>5등급 읽기 수준 대상

많은 readers는 영어를 모국어로 사용하지 않기 때문에 이 최종 지침을 제공합니다. 자신의 문서로 국제적인 청중에게 다가가고 있습니다. 서로의 영어 어휘가 다를 수 있다는 것을 고려해 주세요.

하지만 기술 전문가를 위해 여전히 작성 중입니다. readers는 프로그래밍 지식과 프로그래밍 용어에 대한 특정 어휘가 있다고 가정할 수 있습니다. 개체 지향 프로그래밍, 클래스 및 개체, 함수 및 메서드는 익숙한 용어입니다. 그러나 문서를 읽는 모든 사람들이 공식적인 컴퓨터 과학 학위를 갖고 있는 것은 아닙니다. 다음을 사용하는 경우 아마도 ‘멱등원(idempotent)’ 같은 용어를 정의해야 할 수 있습니다.

>`Close()` 메서드는 멱등원(idempotent)입니다. 즉, 여러 번 호출할 수 있고 효과는 한 번 호출한 것과 동일합니다.

## <a name="avoid-future-tense"></a>미래시제 방지

영어가 아닌 일부 언어에서 미래시제의 개념이 영어와 동일하지 않습니다. 미래시제를 사용하면 문서를 읽기가 어려워질 수 있습니다. 또한 미래시제를 사용할 때, 분명한 문제는 시기입니다. 따라서 ‘PowerShell을 배우는 것이 좋을 것입니다’라고 말하는 경우라면 reader를 위한 분명한 질문은 언제 배우는 것이 좋을가?라는 것입니다. 대신, “PowerShell 학습이 좋습니다”라고 말합니다.

## <a name="what-is-it---so-what"></a>무엇인가요 - 그래서요?

reader에게 새로운 개념을 소개할 때마다 개념을 정의한 다음, 유용성이 무엇인지 설명해야만 합니다. reader는 혜택(또는 기타)을 이해하기 전에 어떤 것이 무엇인지 이해하는 것이 중요합니다.
