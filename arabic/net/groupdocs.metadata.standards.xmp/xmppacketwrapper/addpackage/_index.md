---
title: AddPackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يضيف الحزمة .
type: docs
weight: 80
url: /ar/net/groupdocs.metadata.standards.xmp/xmppacketwrapper/addpackage/
---
## XmpPacketWrapper.AddPackage method

يضيف الحزمة .

```csharp
public void AddPackage(XmpPackage package)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| package | XmpPackage | حزمة. |

### أمثلة

يوضح هذا المثال كيفية إضافة حزمة XMP مخصصة إلى ملف بأي تنسيق مدعوم.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IXmp root = metadata.GetRootPackage() as IXmp;
    if (root != null)
    {
        var packet = new XmpPacketWrapper();

        var custom = new XmpPackage("gd", "https://groupdocs.com ") ;
        custom.Set("gd:Copyright", "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.");
        custom.Set("gd:CreationDate", DateTime.Today);
        custom.Set("gd:Company", XmpArray.From(new [] { "Aspose", "GroupDocs" }, XmpArrayType.Ordered));

        packet.AddPackage(custom);
        root.XmpPackage = packet;

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### أنظر أيضا

* class [XmpPackage](../../xmppackage)
* class [XmpPacketWrapper](../../xmppacketwrapper)
* مساحة الاسم [GroupDocs.Metadata.Standards.Xmp](../../xmppacketwrapper)
* المجسم [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->