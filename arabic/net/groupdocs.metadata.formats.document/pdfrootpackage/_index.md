---
title: PdfRootPackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل الحزمة الجذرية التي تسمح بالعمل مع البيانات الوصفية في مستند PDF.
type: docs
weight: 1040
url: /ar/net/groupdocs.metadata.formats.document/pdfrootpackage/
---
## PdfRootPackage class

يمثل الحزمة الجذرية التي تسمح بالعمل مع البيانات الوصفية في مستند PDF.

```csharp
public class PdfRootPackage : DocumentRootPackage<PdfPackage>, IXmp
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| virtual [DocumentProperties](../../groupdocs.metadata.formats.document/documentrootpackage-1/documentproperties) { get; } | الحصول على خصائص البيانات الوصفية الأصلية المعروضة في المستند. |
| [DocumentStatistics](../../groupdocs.metadata.formats.document/pdfrootpackage/documentstatistics) { get; } | الحصول على حزمة إحصائيات المستند . |
| [FileType](../../groupdocs.metadata.formats.document/pdfrootpackage/filetype) { get; } | يحصل على حزمة البيانات الوصفية لنوع الملف. (2 properties) |
| [InspectionPackage](../../groupdocs.metadata.formats.document/pdfrootpackage/inspectionpackage) { get; } | يحصل على حزمة بيانات وصفية تحتوي على نتائج استقصاء للمستند . تحتوي الحزمة على معلومات حول أجزاء المستند التي يمكن اعتبارها بيانات وصفية في بعض الحالات. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [XmpPackage](../../groupdocs.metadata.formats.document/pdfrootpackage/xmppackage) { get; set; } | الحصول على حزمة بيانات تعريف XMP أو تعيينها. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يضيف خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | لتحديد ما إذا كانت الحزمة تحتوي على خاصية بيانات التعريف بالاسم المحدد. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | البحث عن خصائص البيانات الوصفية التي تفي بالمسند المحدد. البحث متكرر لذا فهو يؤثر على جميع الحزم المتداخلة أيضًا. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | إرجاع عداد يتكرر خلال المجموعة. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | يزيل خصائص البيانات الوصفية التي تفي بالتقييم المحدد. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | إزالة خصائص البيانات الوصفية القابلة للكتابة من الحزمة. العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) و[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) إذا كانت خاصية موجودة تحقق القيمة الأصلية ، فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند ، فستتم إضافتها إلى الحزمة. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |

### ملاحظات

**يتعلم أكثر**

* [العمل مع البيانات الوصفية في مستندات PDF](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)
* [العمل مع بيانات تعريف XMP](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### أمثلة

يوضح نموذج التعليمات البرمجية هذا كيفية استخراج خصائص البيانات الوصفية المضمنة من مستند PDF.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    Console.WriteLine(root.DocumentProperties.Author);
    Console.WriteLine(root.DocumentProperties.CreatedDate);
    Console.WriteLine(root.DocumentProperties.Subject);
    Console.WriteLine(root.DocumentProperties.Producer);
    Console.WriteLine(root.DocumentProperties.Keywords);

    // ... 
}
```

### أنظر أيضا

* class [DocumentRootPackage&lt;TPackage&gt;](../documentrootpackage-1)
* class [PdfPackage](../pdfpackage)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* مساحة الاسم [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
