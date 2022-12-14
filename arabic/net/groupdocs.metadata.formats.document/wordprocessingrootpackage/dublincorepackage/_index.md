---
title: DublinCorePackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: الحصول على حزمة بيانات تعريف دبلن كور المستخرجة من المستند.
type: docs
weight: 20
url: /ar/net/groupdocs.metadata.formats.document/wordprocessingrootpackage/dublincorepackage/
---
## WordProcessingRootPackage.DublinCorePackage property

الحصول على حزمة بيانات تعريف دبلن كور المستخرجة من المستند.

```csharp
public DublinCorePackage DublinCorePackage { get; }
```

### Property_Value

حزمة بيانات تعريف Dublin Core المستخرجة من المستند.

### ملاحظات

**يتعلم أكثر**

* [التعامل مع البيانات الوصفية في مستندات WordProcessing](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### أمثلة

يوضح هذا المثال كيفية استخراج بيانات تعريف دبلن كور من مستند معالجة Word.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDocx))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    if (root.DublinCorePackage != null)
    {
        Console.WriteLine(root.DublinCorePackage.Format);
        Console.WriteLine(root.DublinCorePackage.Contributor);
        Console.WriteLine(root.DublinCorePackage.Coverage);
        Console.WriteLine(root.DublinCorePackage.Creator);
        Console.WriteLine(root.DublinCorePackage.Source);
        Console.WriteLine(root.DublinCorePackage.Description);

        // ...
    }
}
```

### أنظر أيضا

* class [DublinCorePackage](../../../groupdocs.metadata.standards.dublincore/dublincorepackage)
* class [WordProcessingRootPackage](../../wordprocessingrootpackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Document](../../wordprocessingrootpackage)
* المجسم [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
