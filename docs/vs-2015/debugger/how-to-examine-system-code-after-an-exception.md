---
title: "How to: Examine System Code After an Exception | Microsoft Docs"
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
  - "FSharp"
  - "VB"
  - "CSharp"
  - "C++"
helpviewer_keywords: 
  - "debugging, exceptions"
  - "exceptions, debugging"
ms.assetid: a38ad49b-7cf3-483d-91c4-eb3116eba50c
caps.latest.revision: 18
author: "mikejo5000"
ms.author: "mikejo"
manager: "ghogen"
---
# How to: Examine System Code After an Exception
[!INCLUDE[vs2017banner](../includes/vs2017banner.md)]

When an exception occurs, you might have to examine code inside a system call to determine the cause of the exception. The following procedure explains how to do this if you do not have symbols loaded for the system code or if Just My Code is enabled.  
  
### To examine system code following an exception  
  
1.  In the **Call Stack** window, right-click, then click **Show External Code**.  
  
     If Just My Code is not enabled, this option is not available on the shortcut menu and system code is shown by default.  
  
2.  Right-click the external code frames that now appear in the **Call Stack** window.  
  
3.  Point to **Load Symbols From** and then click **Microsoft Symbol Servers**.  
  
    1.  If Just My Code was enabled, a dialog box appears. It states that Just My Code has now been disabled. This is necessary for stepping into system calls.  
  
    2.  The **Downloading public symbols** dialog box appears. It will disappear when downloading finishes.  
  
4.  You can now examine the system code in the **Call Stack** window and other windows. For example, you can double-click a call stack frame to view the code in a source or **Disassembly** window.  
  
## See Also  
 [Managing Exceptions with the Debugger](../debugger/managing-exceptions-with-the-debugger.md)





