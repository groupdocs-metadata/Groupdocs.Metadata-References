---
title: IptcPackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: الحصول على حزمة بيانات تعريف IPTC أو تعيينها.
type: docs
weight: 20
url: /ar/net/groupdocs.metadata.formats.image/tiffrootpackage/iptcpackage/
---
## TiffRootPackage.IptcPackage property

الحصول على حزمة بيانات تعريف IPTC أو تعيينها.

```csharp
public IptcRecordSet IptcPackage { get; set; }
```

### Property_Value

حزمة بيانات تعريف IPTC .

### ملاحظات

**يتعلم أكثر**

* [العمل مع البيانات الوصفية IPTC IIM](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### أمثلة

يوضح هذا المثال كيفية استخراج خصائص بيانات تعريف IPTC الأساسية من صورة TIFF.

```csharp
using (Metadata metadata = new Metadata(Constants.TiffWithIptc))
{
    var root = metadata.GetRootPackage<TiffRootPackage>();
    if (root.IptcPackage != null)
    {
        if (root.IptcPackage.EnvelopeRecord != null)
        {
            Console.WriteLine(root.IptcPackage.EnvelopeRecord.DateSent);
            Console.WriteLine(root.IptcPackage.EnvelopeRecord.Destination);
            Console.WriteLine(root.IptcPackage.EnvelopeRecord.FileFormat);
            Console.WriteLine(root.IptcPackage.EnvelopeRecord.FileFormatVersion);

            // ...
        }

        if (root.IptcPackage.ApplicationRecord != null)
        {
            Console.WriteLine(root.IptcPackage.ApplicationRecord.Headline);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.ByLine);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.ByLineTitle);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.CaptionAbstract);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.City);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.DateCreated);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.ReleaseDate);

            // ...
        }
    }
}
```

### أنظر أيضا

* class [IptcRecordSet](../../../groupdocs.metadata.standards.iptc/iptcrecordset)
* class [TiffRootPackage](../../tiffrootpackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Image](../../tiffrootpackage)
* المجسم [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
