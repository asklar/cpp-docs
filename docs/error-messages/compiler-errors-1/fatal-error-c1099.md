---
title: "Fatal Error C1099 | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-tools"]
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: ["C1099"]
dev_langs: ["C++"]
helpviewer_keywords: ["C1099"]
ms.assetid: c050b074-a06a-4026-9e10-569029cc0739
caps.latest.revision: 6
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
---
# Fatal Error C1099
Edit and Continue engine terminating compile  
  
 Edit and Continue loaded a precompiled header file in preparation for compiling code changes, but subsequent actions (such as code changes prior to the precompiled header `#include` statement or stopping the debugger) prevented Edit and Continue from finishing the compile with that process. You do not need to take any action to fix this error.