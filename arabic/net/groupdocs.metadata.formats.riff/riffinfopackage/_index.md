---
title: RiffInfoPackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل حزمة البيانات الوصفية التي تحتوي على الخصائص المستخرجة من مقطع معلومات RIFF.
type: docs
weight: 2220
url: /ar/net/groupdocs.metadata.formats.riff/riffinfopackage/
---
## RiffInfoPackage class

يمثل حزمة البيانات الوصفية التي تحتوي على الخصائص المستخرجة من مقطع معلومات RIFF.

```csharp
public sealed class RiffInfoPackage : CustomPackage
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Artist](../../groupdocs.metadata.formats.riff/riffinfopackage/artist) { get; } | يحصل على فنان الموضوع الأصلي للملف. |
| [Comment](../../groupdocs.metadata.formats.riff/riffinfopackage/comment) { get; } | يحصل على تعليق حول الملف او موضوع الملف. |
| [Copyright](../../groupdocs.metadata.formats.riff/riffinfopackage/copyright) { get; } | يحصل على معلومات حقوق النشر للملف. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [CreationDate](../../groupdocs.metadata.formats.riff/riffinfopackage/creationdate) { get; } | يحصل على تاريخ إنشاء موضوع الملف. |
| [Engineer](../../groupdocs.metadata.formats.riff/riffinfopackage/engineer) { get; } | يحصل على اسم المهندس الذي عمل على الملف. |
| [Genre](../../groupdocs.metadata.formats.riff/riffinfopackage/genre) { get; } | يحصل على نوع العمل الأصلي. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [Keywords](../../groupdocs.metadata.formats.riff/riffinfopackage/keywords) { get; } | يحصل على الكلمات الأساسية التي تشير إلى الملف أو موضوع الملف. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [Name](../../groupdocs.metadata.formats.riff/riffinfopackage/name) { get; } | يحصل على عنوان موضوع الملف. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [Software](../../groupdocs.metadata.formats.riff/riffinfopackage/software) { get; } | الحصول على اسم حزمة البرامج المستخدمة لإنشاء الملف. |
| [Source](../../groupdocs.metadata.formats.riff/riffinfopackage/source) { get; } | الحصول على اسم الشخص أو المنظمة التي قدمت الموضوع الأصلي للملف. |
| [Subject](../../groupdocs.metadata.formats.riff/riffinfopackage/subject) { get; } | الحصول على وصف لمحتويات الملف ، مثل "عرض جوي لمدينة سياتل." |
| [Technician](../../groupdocs.metadata.formats.riff/riffinfopackage/technician) { get; } | يحصل على الفني الذي قام برقمنة ملف الموضوع. |

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

### أنظر أيضا

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Riff](../../groupdocs.metadata.formats.riff)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
