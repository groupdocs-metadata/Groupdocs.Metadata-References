---
title: RemoveProperties
second_title: GroupDocs.Metadata لمرجع .NET API
description: يزيل خصائص البيانات الوصفية التي تفي بالتقييم المحدد.
type: docs
weight: 90
url: /ar/net/groupdocs.metadata/metadata/removeproperties/
---
## Metadata.RemoveProperties method

يزيل خصائص البيانات الوصفية التي تفي بالتقييم المحدد.

```csharp
public int RemoveProperties(Func<MetadataProperty, bool> predicate)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| predicate | Func`2 | وظيفة لاختبار كل خاصية من خصائص البيانات الوصفية لشرط ما. |

### قيمة الإرجاع

عدد الخصائص المتأثرة.

### ملاحظات

**يتعلم أكثر**

* مزيد من الأمثلة التي توضح استخدامات هذه الطريقة: [إزالة البيانات الوصفية](https://docs.groupdocs.com/display/metadatanet/Removing+metadata)

### أمثلة

يوضح هذا المثال كيفية إزالة خصائص بيانات وصفية معينة باستخدام معايير مختلفة.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDocx))
{
    // إزالة جميع الخصائص التي ترضي المسند:
    // تحتوي الخاصية على اسم مؤلف المستند أو
    // يشير إلى آخر محرر أو
    // قيمة الخاصية عبارة عن سلسلة تحتوي على السلسلة الفرعية "John" (لإزالة أي إشارات إلى John من البيانات الوصفية المكتشفة)
    var affected = metadata.RemoveProperties(
            p => p.Tags.Contains(Tags.Person.Creator) ||
            p.Tags.Contains(Tags.Person.Editor) ||
            p.Value.Type == MetadataPropertyType.String && p.Value.ToString().Contains("John"));

    Console.WriteLine("Properties removed: {0}", affected);

    metadata.Save(Constants.OutputDocx);
}
```

### أنظر أيضا

* delegate [Func&lt;T,TResult&gt;](../../../groupdocs.metadata.common/func-2)
* class [MetadataProperty](../../../groupdocs.metadata.common/metadataproperty)
* class [Metadata](../../metadata)
* مساحة الاسم [GroupDocs.Metadata](../../metadata)
* المجسم [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->