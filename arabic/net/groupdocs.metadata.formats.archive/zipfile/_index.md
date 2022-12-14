---
title: ZipFile
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل البيانات الوصفية المرتبطة بملف أو دليل مؤرشف.
type: docs
weight: 350
url: /ar/net/groupdocs.metadata.formats.archive/zipfile/
---
## ZipFile class

يمثل البيانات الوصفية المرتبطة بملف أو دليل مؤرشف.

```csharp
public sealed class ZipFile : CustomPackage
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [CompressedSize](../../groupdocs.metadata.formats.archive/zipfile/compressedsize) { get; } | الحصول على الحجم المضغوط بالبايت. |
| [CompressionMethod](../../groupdocs.metadata.formats.archive/zipfile/compressionmethod) { get; } | يحصل على طريقة الضغط . |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [Flags](../../groupdocs.metadata.formats.archive/zipfile/flags) { get; } | يحصل على أعلام إدخال ZIP . |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [ModificationDateTime](../../groupdocs.metadata.formats.archive/zipfile/modificationdatetime) { get; } | الحصول على تاريخ ووقت التعديل الأخير. |
| [Name](../../groupdocs.metadata.formats.archive/zipfile/name) { get; } | يحصل على اسم الإدخال . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [RawName](../../groupdocs.metadata.formats.archive/zipfile/rawname) { get; } | الحصول على صفيف من البايت يمثل اسم الإدخال. |
| [UncompressedSize](../../groupdocs.metadata.formats.archive/zipfile/uncompressedsize) { get; } | الحصول على الحجم غير المضغوط بالبايت. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يضيف خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | لتحديد ما إذا كانت الحزمة تحتوي على خاصية بيانات التعريف بالاسم المحدد. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | البحث عن خصائص البيانات الوصفية التي تفي بالمسند المحدد. البحث متكرر لذا فهو يؤثر على جميع الحزم المتداخلة أيضًا. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | إرجاع عداد يتكرر خلال المجموعة. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | يزيل خصائص البيانات الوصفية التي تفي بالتقييم المحدد. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | إزالة خصائص البيانات الوصفية القابلة للكتابة من الحزمة. العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) و[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) إذا كانت خاصية موجودة تحقق القيمة الأصلية ، فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند ، فستتم إضافتها إلى الحزمة. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |

### ملاحظات

**يتعلم أكثر**

* [العمل مع أرشيفات ZIP](https://docs.groupdocs.com/display/metadatanet/Working+with+ZIP+archives)

### أنظر أيضا

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Archive](../../groupdocs.metadata.formats.archive)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
