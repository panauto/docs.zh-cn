---
title: 类型“<typename>”没有构造函数
ms.date: 07/20/2015
f1_keywords:
- bc30251
- vbc30251
helpviewer_keywords:
- BC30251
ms.assetid: aff3e1df-abe6-4bc0-9abc-a1e70514c561
ms.openlocfilehash: 6a12bc35aeaa6e9e21835ce0a091ee89ea4c326d
ms.sourcegitcommit: 14355b4b2fe5bcf874cac96d0a9e6376b567e4c7
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 01/30/2019
ms.locfileid: "55260360"
---
# <a name="type-typename-has-no-constructors"></a>类型\<类型名称 > 没有构造函数
某个类型不支持对 `Sub New()` 的调用。 一个可能的原因是编译器或二进制文件被损坏。  
  
 **错误 ID:** BC30251  
  
## <a name="to-correct-this-error"></a>更正此错误  
  
1.  如果该类型位于其他项目或一个引用的文件中，则重新安装此项目或文件。  
  
2.  如果该类型位于同一个项目中，则重新编译包含该类型的程序集。  
  
3.  如果错误重复出现，请重新安装 Visual Basic 编译器。  
  
4.  如果仍然出现错误，则收集有关该情况的信息并通知 Microsoft 产品支持服务。  
  
## <a name="see-also"></a>请参阅
- [对象和类](../../../visual-basic/programming-guide/language-features/objects-and-classes/index.md)
- [与我们交流](/visualstudio/ide/talk-to-us)
