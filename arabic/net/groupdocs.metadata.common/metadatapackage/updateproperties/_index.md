---
title: UpdateProperties
second_title: GroupDocs.Metadata لمرجع .NET API
description: يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.
type: docs
weight: 130
url: /ar/net/groupdocs.metadata.common/metadatapackage/updateproperties/
---
## MetadataPackage.UpdateProperties method

يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.

```csharp
public int UpdateProperties(Func<MetadataProperty, bool> predicate, PropertyValue value)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| predicate | Func`2 | وظيفة لاختبار كل خاصية من خصائص البيانات الوصفية لشرط ما. |
| value | PropertyValue | قيمة جديدة للخصائص التي تمت تصفيتها. |

### قيمة الإرجاع

عدد الخصائص المتأثرة.

### ملاحظات

يرجى ملاحظة أن GroupDocs.Metadata يتحقق ضمنيًا من نوع كل خاصية تمت تصفيتها. من المستحيل تحديث خاصية ذات قيمة ذات نوع غير مناسب .

**يتعلم أكثر**

* مزيد من الأمثلة التي توضح استخدامات هذه الطريقة: [تحديث البيانات الوصفية](https://docs.groupdocs.com/display/metadatanet/Updating+metadata)

### أنظر أيضا

* delegate [Func&lt;T,TResult&gt;](../../func-2)
* class [MetadataProperty](../../metadataproperty)
* class [PropertyValue](../../propertyvalue)
* class [MetadataPackage](../../metadatapackage)
* مساحة الاسم [GroupDocs.Metadata.Common](../../metadatapackage)
* المجسم [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
