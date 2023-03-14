---
title: SetProperties
second_title: GroupDocs.Metadata لمرجع .NET API
description: تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.AddPropertiesgroupdocs.metadata/metadata/addproperties وUpdatePropertiesgroupdocs.metadata/metadata/updateproperties . إذا كانت خاصية موجودة تحقق القيمة الأصلية  فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند  فستتم إضافتها إلى الحزمة.
type: docs
weight: 120
url: /ar/net/groupdocs.metadata/metadata/setproperties/
---
## Metadata.SetProperties method

تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.[`AddProperties`](../addproperties) و[`UpdateProperties`](../updateproperties) . إذا كانت خاصية موجودة تحقق القيمة الأصلية ، فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند ، فستتم إضافتها إلى الحزمة.

```csharp
public int SetProperties(Func<MetadataProperty, bool> predicate, PropertyValue value)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| predicate | Func`2 | وظيفة لاختبار كل خاصية من خصائص البيانات الوصفية لشرط ما. |
| value | PropertyValue | قيمة جديدة للخصائص التي تمت تصفيتها. |

### قيمة الإرجاع

عدد الخصائص المتأثرة.

### ملاحظات

يرجى ملاحظة أن GroupDocs.Metadata يتحقق ضمنيًا من نوع كل خاصية تمت تصفيتها. من المستحيل تعيين خاصية ذات قيمة ذات نوع غير مناسب .

**يتعلم أكثر**

* [تعيين خصائص البيانات الوصفية](https://docs.groupdocs.com/display/metadatanet/Set+metadata+properties)

### أمثلة

يوضح هذا المثال كيفية تعيين خصائص بيانات وصفية محددة باستخدام معايير مختلفة.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    // قم بتعيين قيمة كل خاصية ترضي المسند:
    // تحتوي الخاصية على تاريخ / وقت إنشاء المستند أو تعديله
    var affected = metadata.SetProperties(
    p => p.Tags.Contains(Tags.Time.Created) || p.Tags.Contains(Tags.Time.Modified),
    new PropertyValue(DateTime.Now));

    Console.WriteLine("Properties set: {0}", affected);

    metadata.Save(Constants.OutputVsdx);
}
```

### أنظر أيضا

* delegate [Func&lt;T,TResult&gt;](../../../groupdocs.metadata.common/func-2)
* class [MetadataProperty](../../../groupdocs.metadata.common/metadataproperty)
* class [PropertyValue](../../../groupdocs.metadata.common/propertyvalue)
* class [Metadata](../../metadata)
* مساحة الاسم [GroupDocs.Metadata](../../metadata)
* المجسم [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->