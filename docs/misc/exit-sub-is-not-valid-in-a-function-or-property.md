---
title: "&#39;Exit Sub&#39; is not valid in a Function or Property | Microsoft Docs"
ms.custom: ""
ms.date: "2015-07-20"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-visual-basic"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "bc30065"
  - "vbc30065"
helpviewer_keywords: 
  - "BC30065"
ms.assetid: d6426861-ba64-4dca-9100-262c6c058bd9
caps.latest.revision: 8
author: "stevehoag"
ms.author: "shoag"
manager: "wpickett"
translation.priority.ht: 
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "ru-ru"
  - "zh-cn"
  - "zh-tw"
translation.priority.mt: 
  - "cs-cz"
  - "pl-pl"
  - "pt-br"
  - "tr-tr"
---
# &#39;Exit Sub&#39; is not valid in a Function or Property
`Exit Sub` appears in a `Function` procedure or a `Property` procedure. An `Exit` statement must match the block in which it occurs.  
  
 **Error ID:** BC30065  
  
### To correct this error  
  
-   Replace the `Exit Sub` with the `Exit Function` or `Exit Property` statement as appropriate.  
  
## See Also  
 [Sub Procedures](/dotnet/visual-basic/language-reference/procedures/sub-procedures)   
 [Function Procedures](/dotnet/visual-basic/language-reference/procedures/function-procedures)   
 [Property Procedures](/dotnet/visual-basic/language-reference/procedures/property-procedures)