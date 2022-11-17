---
title: AviHeader
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل بنية AVIMAINHEADER في فيديو AVI.
type: docs
weight: 2380
url: /ar/net/groupdocs.metadata.formats.video/aviheader/
---
## AviHeader class

يمثل بنية AVIMAINHEADER في فيديو AVI.

```csharp
public sealed class AviHeader : CustomPackage
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [AviHeader](aviheader)() | يقوم بتهيئة مثيل جديد لملف[`AviHeader`](../aviheader) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AviHeaderFlags](../../groupdocs.metadata.formats.video/aviheader/aviheaderflags) { get; } | الحصول على مجموعة أحاديات مكونة من صفر أو أكثر من أعلام AVI . |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [Height](../../groupdocs.metadata.formats.video/aviheader/height) { get; } | يحصل على ارتفاع ملف AVI بالبكسل. |
| [InitialFrames](../../groupdocs.metadata.formats.video/aviheader/initialframes) { get; } | يحصل على الإطار الأولي للملفات المعزولة.  يجب أن تحدد الملفات غير المتشعبة صفرًا. إذا كنت تقوم بإنشاء ملفات متداخلة ، فحدد عدد الإطارات في الملف قبل الإطار الأولي لتسلسل AVI في هذا العضو. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [MaxBytesPerSec](../../groupdocs.metadata.formats.video/aviheader/maxbytespersec) { get; } | يحصل على معدل البيانات الأقصى التقريبي للملف. تشير هذه القيمة إلى عدد البايتات في الثانية التي يجب على النظام معالجتها لتقديم تسلسل AVI كـ المحدد بواسطة المعلمات الأخرى المضمنة في الرأس الرئيسي ومقطع رأس التدفق. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [MicroSecPerFrame](../../groupdocs.metadata.formats.video/aviheader/microsecperframe) { get; } | الحصول على عدد الميكروثانية بين الإطارات. تشير هذه القيمة إلى التوقيت الإجمالي للملف. |
| [PaddingGranularity](../../groupdocs.metadata.formats.video/aviheader/paddinggranularity) { get; } | يحصل على محاذاة البيانات بالبايت. ضع البيانات في مضاعفات هذه القيمة. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [Streams](../../groupdocs.metadata.formats.video/aviheader/streams) { get; } | يحصل على عدد التدفقات في الملف. على سبيل المثال ، يحتوي الملف الذي يحتوي على صوت وفيديو على دفقين. |
| [SuggestedBufferSize](../../groupdocs.metadata.formats.video/aviheader/suggestedbuffersize) { get; } | يحصل على حجم المخزن المؤقت المقترح لقراءة الملف. بشكل عام ، يجب أن يكون هذا الحجم كبيرًا بما يكفي لاحتواء أكبر جزء في الملف. إذا تم التعيين على الصفر ، أو إذا كان صغيرًا جدًا ، فسيتعين على برنامج التشغيل إعادة تخصيص الذاكرة أثناء التشغيل ، مما يؤدي إلى تقليل الأداء. بالنسبة لملف معشق ، يجب أن يكون حجم المخزن المؤقت كبيرًا بما يكفي لقراءة سجل كامل ، وليس مجرد مقطع. |
| [TotalFrames](../../groupdocs.metadata.formats.video/aviheader/totalframes) { get; } | الحصول على العدد الإجمالي لإطارات البيانات في الملف. |
| [Width](../../groupdocs.metadata.formats.video/aviheader/width) { get; } | يحصل على عرض ملف AVI بالبكسل. |

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

* [العمل مع البيانات الوصفية في ملفات AVI](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files)

### أنظر أيضا

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
