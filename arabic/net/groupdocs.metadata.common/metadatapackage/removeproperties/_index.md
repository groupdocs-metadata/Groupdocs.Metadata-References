---
title: RemoveProperties
second_title: GroupDocs.Metadata لمرجع .NET API
description: يزيل خصائص البيانات الوصفية التي تفي بالتقييم المحدد.
type: docs
weight: 100
url: /ar/net/groupdocs.metadata.common/metadatapackage/removeproperties/
---
## MetadataPackage.RemoveProperties method

يزيل خصائص البيانات الوصفية التي تفي بالتقييم المحدد.

```csharp
public virtual int RemoveProperties(Func<MetadataProperty, bool> predicate)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| predicate | Func`2 | وظيفة لاختبار كل خاصية من خصائص البيانات الوصفية لشرط ما. |

### قيمة الإرجاع

عدد الخصائص المتأثرة.

### ملاحظات

**يتعلم أكثر**

* مزيد من الأمثلة التي توضح استخدامات هذه الطريقة: [إزالة البيانات الوصفية](https://docs.groupdocs.com/display/metadatanet/Removing+metadata)

### أنظر أيضا

* delegate [Func&lt;T,TResult&gt;](../../func-2)
* class [MetadataProperty](../../metadataproperty)
* class [MetadataPackage](../../metadatapackage)
* مساحة الاسم [GroupDocs.Metadata.Common](../../metadatapackage)
* المجسم [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->