---
title: "IDiaEnumSymbols::get_Count | Microsoft Docs"
ms.custom: ""
ms.date: 11/15/2016
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-debug"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "IDiaEnumSymbols::get_Count method"
ms.assetid: fdaae6d7-e67b-4262-84c9-fbae381e8297
caps.latest.revision: 10
author: "mikejo5000"
ms.author: "mikejo"
manager: "ghogen"
---
# IDiaEnumSymbols::get_Count
[!INCLUDE[vs2017banner](../../includes/vs2017banner.md)]

Retrieves the number of symbols.  
  
## Syntax  
  
```cpp#  
HRESULT get_Count (   
   LONG* pRetVal  
);  
```  
  
#### Parameters  
 pRetVal  
 [out] Returns the number of symbols.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## See Also  
 [IDiaEnumSymbols](../../debugger/debug-interface-access/idiaenumsymbols.md)   
 [IDiaEnumSymbols::Item](../../debugger/debug-interface-access/idiaenumsymbols-item.md)



