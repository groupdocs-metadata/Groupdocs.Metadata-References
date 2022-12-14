---
title: DetectBarcodeTypes
second_title: GroupDocs.Metadata لمرجع .NET API
description: استخراج أنواع الباركود المعروضة في الصورة.
type: docs
weight: 60
url: /ar/net/groupdocs.metadata.formats.image/jpegrootpackage/detectbarcodetypes/
---
## JpegRootPackage.DetectBarcodeTypes method

استخراج أنواع الباركود المعروضة في الصورة.

```csharp
public string[] DetectBarcodeTypes()
```

### قيمة الإرجاع

مصفوفة من أنواع الباركود .

### ملاحظات

**يتعلم أكثر**

* [العمل مع البيانات الأولية في صور JPEG](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG+images)

### أمثلة

يوضح مقتطف الشفرة هذا كيفية اكتشاف الرموز الشريطية في صورة JPEG.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithBarcodes))
{
    var root = metadata.GetRootPackage<JpegRootPackage>();

    var barcodeTypes = root.DetectBarcodeTypes();

    foreach (var barcodeType in barcodeTypes)
    {
        Console.WriteLine(barcodeType);
    }
}
```

### أنظر أيضا

* class [JpegRootPackage](../../jpegrootpackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Image](../../jpegrootpackage)
* المجسم [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
