---
title: "&lt;typeindex&gt; | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-standard-libraries"]
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: ["<typeindex>"]
dev_langs: ["C++"]
ms.assetid: a9551137-f74b-4f02-af64-ff00214cea1f
caps.latest.revision: 14
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
---
# &lt;typeindex&gt;
Include the standard header \<typeindex> to define a class and function that support the indexing of objects of class [type_info](../cpp/type-info-class.md).  
  
## Syntax  
  
```cpp  
#include <typeindex>  
```  
  
## Remarks  
 The [hash Structure](../standard-library/hash-structure.md) defines a `hash function` that's suitable for mapping values of type [type_index](../standard-library/type-index-class.md) to a distribution of index values.  
  
 The `type_index` class wraps a pointer to a `type_info` object to assist in indexing.  
  
## See Also  
 [Header Files Reference](../standard-library/cpp-standard-library-header-files.md)   
 [Thread Safety in the C++ Standard Library](../standard-library/thread-safety-in-the-cpp-standard-library.md)   
 [C++ Standard Library Reference](../standard-library/cpp-standard-library-reference.md)



