---
title: Sanitize
second_title: GroupDocs.Metadata لمرجع .NET API
description: يزيل خصائص البيانات الوصفية القابلة للكتابة من جميع الحزم المكتشفة أو الحزم الكاملة إن أمكن. العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.
type: docs
weight: 100
url: /ar/net/groupdocs.metadata/metadata/sanitize/
---
## Metadata.Sanitize method

يزيل خصائص البيانات الوصفية القابلة للكتابة من جميع الحزم المكتشفة أو الحزم الكاملة إن أمكن. العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.

```csharp
public int Sanitize()
```

### قيمة الإرجاع

عدد الخصائص المتأثرة.

### ملاحظات

**يتعلم أكثر**

* [البيانات الوصفية النظيفة](https://docs.groupdocs.com/display/metadatanet/Clean+metadata)

### أمثلة

يوضح هذا المثال كيفية إزالة كافة حزم / خصائص البيانات الوصفية المكتشفة من ملف.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPdf))
{
    // إزالة حزم البيانات الوصفية المكتشفة
    var affected = metadata.Sanitize();
    Console.WriteLine("Properties removed: {0}", affected);

    metadata.Save(Constants.OutputPdf);
}
```

### أنظر أيضا

* class [Metadata](../../metadata)
* مساحة الاسم [GroupDocs.Metadata](../../metadata)
* المجسم [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
