---
title: ImageResourcePackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: الحصول على حزمة البيانات الأولية لمورد صورة Photoshop . كتل موارد الصورة هي وحدة البناء الأساسية لتنسيق ملف Photoshop الأصلي.
type: docs
weight: 20
url: /ar/net/groupdocs.metadata.formats.image/psdrootpackage/imageresourcepackage/
---
## PsdRootPackage.ImageResourcePackage property

الحصول على حزمة البيانات الأولية لمورد صورة Photoshop . كتل موارد الصورة هي وحدة البناء الأساسية لتنسيق ملف Photoshop الأصلي.

```csharp
public ImageResourcePackage ImageResourcePackage { get; }
```

### Property_Value

حزمة بيانات تعريف مصدر الصورة .

### ملاحظات

**يتعلم أكثر**

* [العمل مع البيانات الوصفية في صور PSD](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PSD+images)

### أمثلة

يوضح نموذج التعليمات البرمجية أدناه كيفية استخراج مجموعات موارد الصورة (اللبنات الأساسية لتنسيق ملف Photoshop) من صورة PSD.

```csharp
using (Metadata metadata = new Metadata(Constants.PsdWithIrb))
{
    var root = metadata.GetRootPackage<PsdRootPackage>();

    if (root.ImageResourcePackage != null)
    {
        foreach (var block in root.ImageResourcePackage.ToList())
        {
            Console.WriteLine(block.Signature);
            Console.WriteLine(block.ID);
            Console.WriteLine(block.Name);
            Console.WriteLine(block.Data);
        }
    }
}
```

### أنظر أيضا

* class [ImageResourcePackage](../../imageresourcepackage)
* class [PsdRootPackage](../../psdrootpackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Image](../../psdrootpackage)
* المجسم [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->