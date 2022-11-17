---
title: WordProcessingPackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل حزمة بيانات وصفية أصلية في مستند معالجة كلمات.
type: docs
weight: 1280
url: /ar/net/groupdocs.metadata.formats.document/wordprocessingpackage/
---
## WordProcessingPackage class

يمثل حزمة بيانات وصفية أصلية في مستند معالجة كلمات.

```csharp
public class WordProcessingPackage : DocumentPackage
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/wordprocessingpackage/author) { get; set; } | الحصول على مؤلف المستند أو تعيينه. |
| [BytesInDocument](../../groupdocs.metadata.formats.document/wordprocessingpackage/bytesindocument) { get; } | الحصول على تقدير لعدد البايت في المستند. |
| [Category](../../groupdocs.metadata.formats.document/wordprocessingpackage/category) { get; set; } | الحصول على الفئة أو تعيينها . |
| [Comments](../../groupdocs.metadata.formats.document/wordprocessingpackage/comments) { get; set; } | الحصول على التعليقات أو تعيينها. |
| [Company](../../groupdocs.metadata.formats.document/wordprocessingpackage/company) { get; set; } | الحصول على الشركة أو تعيينها . |
| [ContentStatus](../../groupdocs.metadata.formats.document/wordprocessingpackage/contentstatus) { get; set; } | الحصول على حالة المحتوى أو تعيينها. |
| [ContentType](../../groupdocs.metadata.formats.document/wordprocessingpackage/contenttype) { get; set; } | الحصول على أو تحديد نوع محتوى المستند. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [CreatedTime](../../groupdocs.metadata.formats.document/wordprocessingpackage/createdtime) { get; set; } | الحصول على أو تعيين تاريخ إنشاء المستند. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/wordprocessingpackage/hyperlinkbase) { get; set; } | الحصول على قاعدة الارتباط التشعبي أو تعيينها. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [Keywords](../../groupdocs.metadata.formats.document/wordprocessingpackage/keywords) { get; set; } | الحصول على الكلمات الأساسية أو تعيينها. |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/wordprocessingpackage/lastprinteddate) { get; set; } | الحصول على آخر تاريخ مطبوع أو تعيينه. |
| [LastSavedBy](../../groupdocs.metadata.formats.document/wordprocessingpackage/lastsavedby) { get; set; } | الحصول على أو تحديد اسم آخر مؤلف . |
| [LastSavedTime](../../groupdocs.metadata.formats.document/wordprocessingpackage/lastsavedtime) { get; set; } | الحصول على أو تحديد وقت آخر حفظ. |
| [LinksUpToDate](../../groupdocs.metadata.formats.document/wordprocessingpackage/linksuptodate) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الارتباطات التشعبية في المستند محدثة أم لا. |
| [Manager](../../groupdocs.metadata.formats.document/wordprocessingpackage/manager) { get; set; } | الحصول على المدير أو تعيينه . |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [NameOfApplication](../../groupdocs.metadata.formats.document/wordprocessingpackage/nameofapplication) { get; } | يحصل على اسم التطبيق. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [RevisionNumber](../../groupdocs.metadata.formats.document/wordprocessingpackage/revisionnumber) { get; set; } | الحصول على رقم المراجعة أو تعيينه. |
| [Subject](../../groupdocs.metadata.formats.document/wordprocessingpackage/subject) { get; set; } | الحصول على الموضوع أو تعيينه . |
| [Template](../../groupdocs.metadata.formats.document/wordprocessingpackage/template) { get; set; } | الحصول على القالب أو تعيينه . |
| [Title](../../groupdocs.metadata.formats.document/wordprocessingpackage/title) { get; set; } | الحصول على عنوان المستند أو تحديده. |
| [TitlesOfParts](../../groupdocs.metadata.formats.document/wordprocessingpackage/titlesofparts) { get; } | الحصول على عناوين أجزاء المستند. للقراءة فقط. |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/wordprocessingpackage/totaleditingtime) { get; set; } | الحصول على أو تحديد إجمالي وقت التحرير بالدقائق. |
| [Version](../../groupdocs.metadata.formats.document/wordprocessingpackage/version) { get; } | يحصل على رقم إصدار التطبيق الذي أنشأ المستند. |

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
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set)(string, bool) | إضافة أو استبدال خاصية البيانات الوصفية بالاسم المحدد. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_3)(string, DateTime) | إضافة أو استبدال خاصية البيانات الوصفية بالاسم المحدد. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_1)(string, double) | إضافة أو استبدال خاصية البيانات الوصفية بالاسم المحدد. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_2)(string, int) | إضافة أو استبدال خاصية البيانات الوصفية بالاسم المحدد. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_4)(string, string) | إضافة أو استبدال خاصية البيانات الوصفية بالاسم المحدد. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) و[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) إذا كانت خاصية موجودة تحقق القيمة الأصلية ، فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند ، فستتم إضافتها إلى الحزمة. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |

### ملاحظات

**يتعلم أكثر**

* [التعامل مع البيانات الوصفية في مستندات WordProcessing](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### أمثلة

يوضح نموذج التعليمات البرمجية هذا كيفية تحديث خصائص بيانات التعريف المضمنة في مستند معالجة Word.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDoc))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputDoc);
}
```

### أنظر أيضا

* class [DocumentPackage](../documentpackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
