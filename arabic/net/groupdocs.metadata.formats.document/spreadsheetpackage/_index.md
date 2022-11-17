---
title: SpreadsheetPackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل حزمة بيانات وصفية أصلية في جدول بيانات.
type: docs
weight: 1200
url: /ar/net/groupdocs.metadata.formats.document/spreadsheetpackage/
---
## SpreadsheetPackage class

يمثل حزمة بيانات وصفية أصلية في جدول بيانات.

```csharp
public class SpreadsheetPackage : DocumentPackage
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/spreadsheetpackage/author) { get; set; } | الحصول على أو تعيين مؤلف المستند. |
| [Category](../../groupdocs.metadata.formats.document/spreadsheetpackage/category) { get; set; } | الحصول على الفئة أو تعيينها . |
| [Comments](../../groupdocs.metadata.formats.document/spreadsheetpackage/comments) { get; set; } | الحصول على التعليقات أو تعيينها. |
| [Company](../../groupdocs.metadata.formats.document/spreadsheetpackage/company) { get; set; } | الحصول على الشركة أو تعيينها . |
| [ContentStatus](../../groupdocs.metadata.formats.document/spreadsheetpackage/contentstatus) { get; set; } | الحصول على حالة المحتوى أو تعيينها. |
| [ContentType](../../groupdocs.metadata.formats.document/spreadsheetpackage/contenttype) { get; set; } | الحصول على نوع المحتوى أو تعيينه. |
| [ContentTypeProperties](../../groupdocs.metadata.formats.document/spreadsheetpackage/contenttypeproperties) { get; } | يحصل على حزمة البيانات الوصفية التي تحتوي على خصائص نوع المحتوى. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [CreatedTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/createdtime) { get; set; } | الحصول على أو تعيين تاريخ إنشاء المستند. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/spreadsheetpackage/hyperlinkbase) { get; set; } | الحصول على قاعدة الارتباط التشعبي أو تعيينها. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [Keywords](../../groupdocs.metadata.formats.document/spreadsheetpackage/keywords) { get; set; } | الحصول على الكلمات الأساسية أو تعيينها. |
| [Language](../../groupdocs.metadata.formats.document/spreadsheetpackage/language) { get; set; } | الحصول على لغة المستند أو تعيينها . |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastprinteddate) { get; set; } | الحصول على آخر تاريخ مطبوع بالتوقيت العالمي المنسق أو تعيينه. |
| [LastSavedBy](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastsavedby) { get; set; } | الحصول على أو تحديد اسم آخر مؤلف . |
| [LastSavedTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastsavedtime) { get; set; } | الحصول على أو تحديد وقت آخر حفظ بالتوقيت العالمي المنسق . |
| [Manager](../../groupdocs.metadata.formats.document/spreadsheetpackage/manager) { get; set; } | الحصول على المدير أو تعيينه . |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [NameOfApplication](../../groupdocs.metadata.formats.document/spreadsheetpackage/nameofapplication) { get; set; } | الحصول على أو تحديد اسم التطبيق. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [Revision](../../groupdocs.metadata.formats.document/spreadsheetpackage/revision) { get; set; } | الحصول على أو تحديد رقم مراجعة المستند. |
| [Subject](../../groupdocs.metadata.formats.document/spreadsheetpackage/subject) { get; set; } | الحصول على الموضوع أو تعيينه . |
| [Template](../../groupdocs.metadata.formats.document/spreadsheetpackage/template) { get; set; } | الحصول على أو تحديد اسم قالب المستند. |
| [Title](../../groupdocs.metadata.formats.document/spreadsheetpackage/title) { get; set; } | الحصول على عنوان المستند أو تحديده. |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/totaleditingtime) { get; set; } | الحصول على أو تحديد إجمالي وقت التحرير بالدقائق. |
| [Version](../../groupdocs.metadata.formats.document/spreadsheetpackage/version) { get; set; } | الحصول على أو تحديد رقم إصدار التطبيق الذي أنشأ المستند. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يضيف خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | يزيل كافة خصائص البيانات الوصفية القابلة للكتابة من الحزمة. |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | يزيل كافة خصائص البيانات الوصفية المضمنة. |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | يزيل كافة خصائص البيانات الوصفية المخصصة . |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | لتحديد ما إذا كانت الحزمة تحتوي على خاصية بيانات التعريف بالاسم المحدد. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | البحث عن خصائص البيانات الوصفية التي تفي بالمسند المحدد. البحث متكرر لذا فهو يؤثر على جميع الحزم المتداخلة أيضًا. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | إرجاع عداد يتكرر خلال المجموعة. |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | يزيل خاصية بيانات التعريف القابلة للكتابة بالاسم المحدد. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | يزيل خصائص البيانات الوصفية التي تفي بالتقييم المحدد. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | إزالة خصائص البيانات الوصفية القابلة للكتابة من الحزمة. العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set)(string, bool) | إضافة أو استبدال خاصية البيانات الوصفية بالاسم المحدد. |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_3)(string, DateTime) | إضافة أو استبدال خاصية البيانات الوصفية بالاسم المحدد. |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_1)(string, double) | إضافة أو استبدال خاصية البيانات الوصفية بالاسم المحدد. |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_2)(string, int) | إضافة أو استبدال خاصية البيانات الوصفية بالاسم المحدد. |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_4)(string, string) | إضافة أو استبدال خاصية البيانات الوصفية بالاسم المحدد. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) و[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) إذا كانت خاصية موجودة تحقق القيمة الأصلية ، فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند ، فستتم إضافتها إلى الحزمة. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |

### ملاحظات

**يتعلم أكثر**

* [العمل مع البيانات الوصفية في جداول البيانات](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Spreadsheets)

### أمثلة

يوضح هذا المثال كيفية تحديث خصائص البيانات الوصفية المضمنة في جدول بيانات.

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    var root = metadata.GetRootPackage<SpreadsheetRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputXlsx);
}
```

### أنظر أيضا

* class [DocumentPackage](../documentpackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
