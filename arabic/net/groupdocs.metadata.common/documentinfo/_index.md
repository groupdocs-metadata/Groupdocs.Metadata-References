---
title: DocumentInfo
second_title: GroupDocs.Metadata لمرجع .NET API
description: يوفر معلومات عامة حول المستند الذي تم تحميله.
type: docs
weight: 30
url: /ar/net/groupdocs.metadata.common/documentinfo/
---
## DocumentInfo class

يوفر معلومات عامة حول المستند الذي تم تحميله.

```csharp
public class DocumentInfo : IDocumentInfo
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [FileType](../../groupdocs.metadata.common/documentinfo/filetype) { get; } | يحصل على نوع الملف للمستند الذي تم تحميله. |
| [IsEncrypted](../../groupdocs.metadata.common/documentinfo/isencrypted) { get; } | يحصل على قيمة تشير إلى ما إذا كان المستند مشفرًا ويتطلب كلمة مرور للفتح. |
| [PageCount](../../groupdocs.metadata.common/documentinfo/pagecount) { get; } | الحصول على عدد الصفحات (الشرائح ، أوراق العمل ، إلخ) في المستند الذي تم تحميله. |
| [Pages](../../groupdocs.metadata.common/documentinfo/pages) { get; } | الحصول على مجموعة من الكائنات تمثل معلومات شائعة حول صفحات المستند (شرائح ، أوراق عمل ، إلخ) . |
| [Size](../../groupdocs.metadata.common/documentinfo/size) { get; } | الحصول على حجم المستند الذي تم تحميله بالبايت. |

### ملاحظات

**يتعلم أكثر**

* [الحصول على معلومات الوثيقة](https://docs.groupdocs.com/display/metadatanet/Get+document+info)

### أمثلة

يوضح هذا المثال كيفية استخراج معلومات التنسيق الأساسية من ملف.

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    if (metadata.FileFormat != FileFormat.Unknown)
    {
        IDocumentInfo info = metadata.GetDocumentInfo();

        Console.WriteLine("File format: {0}", info.FileType.FileFormat);
        Console.WriteLine("File extension: {0}", info.FileType.Extension);
        Console.WriteLine("MIME Type: {0}", info.FileType.MimeType);
        Console.WriteLine("Number of pages: {0}", info.PageCount);
        Console.WriteLine("Document size: {0} bytes", info.Size);
        Console.WriteLine("Is document encrypted: {0}", info.IsEncrypted);
    }
}
```

### أنظر أيضا

* interface [IDocumentInfo](../idocumentinfo)
* مساحة الاسم [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
