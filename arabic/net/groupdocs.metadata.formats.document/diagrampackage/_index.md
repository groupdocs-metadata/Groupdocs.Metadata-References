---
title: DiagramPackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل حزمة بيانات وصفية أصلية بتنسيق مخطط.
type: docs
weight: 890
url: /ar/net/groupdocs.metadata.formats.document/diagrampackage/
---
## DiagramPackage class

يمثل حزمة بيانات وصفية أصلية بتنسيق مخطط.

```csharp
public class DiagramPackage : DocumentPackage
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AlternateNames](../../groupdocs.metadata.formats.document/diagrampackage/alternatenames) { get; set; } | الحصول على أو تحديد الأسماء البديلة للمستند. يمكن تحديثه بتنسيقات VDX و VSX فقط. |
| [BuildNumberCreated](../../groupdocs.metadata.formats.document/diagrampackage/buildnumbercreated) { get; } | الحصول على رقم البنية الكامل للمثيل المستخدم لإنشاء المستند. |
| [BuildNumberEdited](../../groupdocs.metadata.formats.document/diagrampackage/buildnumberedited) { get; } | الحصول على رقم البنية للمثيل الأخير الذي تم استخدامه لتحرير المستند. |
| [Category](../../groupdocs.metadata.formats.document/diagrampackage/category) { get; set; } | الحصول على النص الوصفي لنوع الرسم أو تعيينه ، مثل مخطط انسيابي أو تخطيط المكتب . يمكن أيضًا إدخال هذا النص في واجهة مستخدم Microsoft Visio في مربع الفئة في مربع الحوار "خصائص". |
| [Company](../../groupdocs.metadata.formats.document/diagrampackage/company) { get; set; } | الحصول على أو تعيين المعلومات التي أدخلها المستخدم والتي تحدد الشركة التي تقوم بإنشاء الرسم أو الشركة التي يتم إنشاء الرسم من أجلها . الحد الأقصى للطول هو 63 حرفًا . |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [Creator](../../groupdocs.metadata.formats.document/diagrampackage/creator) { get; set; } | الحصول على أو تعيين الشخص الذي قام بإنشاء الملف أو آخر تحديث له. الحد الأقصى للطول هو 63 حرفًا .. |
| [Description](../../groupdocs.metadata.formats.document/diagrampackage/description) { get; set; } | الحصول على سلسلة نصية وصفية للمستند أو تعيينها. استخدم هذا العنصر لتخزين معلومات مهمة حول المستند ، مثل الغرض منه أو التغييرات الأخيرة أو التغييرات المعلقة. الحد الأقصى هو 191 حرفًا. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/diagrampackage/hyperlinkbase) { get; set; } | الحصول على المسار الذي سيتم استخدامه للارتباطات التشعبية النسبية أو تعيينه (الارتباطات التشعبية التي تم وصف موقع الملف المرتبط لها فيما يتعلق بمخطط Microsoft Visio التخطيطي) . بشكل افتراضي ، يكون مسار الارتباط التشعبي متعلقًا بالمستند الحالي ما لم يتم تحديد مسار مختلف في هذا العنصر . الحد الأقصى للطول هو 256 حرفًا . |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [Keywords](../../groupdocs.metadata.formats.document/diagrampackage/keywords) { get; set; } | الحصول على أو تعيين سلسلة نصية تحدد الموضوعات أو المعلومات المهمة الأخرى حول الملف ، مثل اسم المشروع أو اسم العميل أو رقم الإصدار. أقصى طول للسلسلة هو 63 حرفًا. |
| [Language](../../groupdocs.metadata.formats.document/diagrampackage/language) { get; set; } | الحصول على لغة المستند أو تعيينها . يمكن تحديثها بتنسيقات VSD و VSDX فقط. |
| [Manager](../../groupdocs.metadata.formats.document/diagrampackage/manager) { get; set; } | الحصول على أو تعيين سلسلة نصية أدخلها المستخدم تحدد الشخص المسؤول عن المشروع أو القسم . الحد الأقصى للطول هو 63 حرفًا . |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [PreviewPicture](../../groupdocs.metadata.formats.document/diagrampackage/previewpicture) { get; set; } | الحصول على صورة المعاينة أو تعيينها. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [Subject](../../groupdocs.metadata.formats.document/diagrampackage/subject) { get; set; } | الحصول على أو تعيين سلسلة نصية محددة بواسطة المستخدم تصف محتويات المستند. الحد الأقصى للطول هو 63 حرفًا . |
| [Template](../../groupdocs.metadata.formats.document/diagrampackage/template) { get; set; } | الحصول على أو تعيين قيمة سلسلة تحدد اسم ملف القالب الذي تم إنشاء المستند منه. |
| [TimeCreated](../../groupdocs.metadata.formats.document/diagrampackage/timecreated) { get; set; } | الحصول على أو تحديد قيمة التاريخ والوقت للإشارة إلى وقت إنشاء المستند. |
| [TimeEdited](../../groupdocs.metadata.formats.document/diagrampackage/timeedited) { get; } | الحصول على قيمة التاريخ والوقت للإشارة إلى تاريخ آخر تحرير للمستند. |
| [TimePrinted](../../groupdocs.metadata.formats.document/diagrampackage/timeprinted) { get; } | الحصول على قيمة التاريخ والوقت التي تشير إلى تاريخ آخر طباعة للمستند. |
| [TimeSaved](../../groupdocs.metadata.formats.document/diagrampackage/timesaved) { get; } | الحصول على قيمة التاريخ والوقت للإشارة إلى آخر مرة تم فيها حفظ المستند. |
| [Title](../../groupdocs.metadata.formats.document/diagrampackage/title) { get; set; } | الحصول على أو تعيين سلسلة نصية محددة بواسطة المستخدم تعمل كعنوان وصفي للمستند. الحد الأقصى للطول هو 63 حرفًا . |

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
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set)(string, bool) | إضافة أو استبدال خاصية البيانات الوصفية بالاسم المحدد. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_2)(string, DateTime) | إضافة أو استبدال خاصية البيانات الوصفية بالاسم المحدد. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_1)(string, double) | إضافة أو استبدال خاصية البيانات الوصفية بالاسم المحدد. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_3)(string, string) | إضافة أو استبدال خاصية البيانات الوصفية بالاسم المحدد. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) و[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) إذا كانت خاصية موجودة تحقق القيمة الأصلية ، فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند ، فستتم إضافتها إلى الحزمة. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |

### ملاحظات

**يتعلم أكثر**

* [العمل مع البيانات الوصفية في الرسوم البيانية](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### أمثلة

يوضح نموذج التعليمات البرمجية هذا كيفية استخراج خصائص البيانات الوصفية المضمنة من رسم تخطيطي.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.DocumentProperties.Creator);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.TimeCreated);
    Console.WriteLine(root.DocumentProperties.Category);

    // ... 
}
```

### أنظر أيضا

* class [DocumentPackage](../documentpackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
