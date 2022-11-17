---
title: AsfAudioStreamProperty
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل البيانات الوصفية لخاصية دفق الصوت في حاوية وسائط ASF.
type: docs
weight: 2230
url: /ar/net/groupdocs.metadata.formats.video/asfaudiostreamproperty/
---
## AsfAudioStreamProperty class

يمثل البيانات الوصفية لخاصية دفق الصوت في حاوية وسائط ASF.

```csharp
public class AsfAudioStreamProperty : AsfBaseStreamProperty
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AlternateBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/alternatebitrate) { get; } | يحصل على معدل التسرب RAlt ، بالبت في الثانية ، لحاوية متسربة تحتوي على جزء البيانات من الدفق دون تجاوز ، باستثناء كل عبء حزمة بيانات ASF. |
| [AverageBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagebitrate) { get; } | يحصل على متوسط معدل البت . |
| [AverageTimePerFrame](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagetimeperframe) { get; } | الحصول على متوسط المدة الزمنية ، مقاسة بوحدات 100 نانوثانية ، لكل إطار. |
| [Bitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/bitrate) { get; } | يحصل على معدل التسرب R ، بالبت في الثانية ، لحاوية تسرب تحتوي على جزء البيانات من الدفق دون تجاوز ، باستثناء كل عبء حزمة بيانات ASF. |
| [BitsPerSample](../../groupdocs.metadata.formats.video/asfaudiostreamproperty/bitspersample) { get; } | الحصول على عدد وحدات البت لكل عينة من البيانات الأحادية. |
| [Channels](../../groupdocs.metadata.formats.video/asfaudiostreamproperty/channels) { get; } | الحصول على عدد القنوات الصوتية. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [EndTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/endtime) { get; } | يحصل على وقت العرض التقديمي للكائن الأخير بالإضافة إلى مدة التشغيل ، مشيرًا إلى المكان الذي ينتهي فيه دفق الوسائط الرقمية ضمن سياق المخطط الزمني لملف ASF ككل. |
| [Flags](../../groupdocs.metadata.formats.video/asfbasestreamproperty/flags) { get; } | يحصل على الأعلام . |
| [FormatTag](../../groupdocs.metadata.formats.video/asfaudiostreamproperty/formattag) { get; } | الحصول على المعرف الفريد لبرنامج الترميز المستخدم لترميز بيانات الصوت. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [Language](../../groupdocs.metadata.formats.video/asfbasestreamproperty/language) { get; } | يحصل على لغة الدفق . |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [SamplesPerSecond](../../groupdocs.metadata.formats.video/asfaudiostreamproperty/samplespersecond) { get; } | يحصل على قيمة بالهرتز (عدد الدورات في الثانية) التي تمثل معدل أخذ العينات للدفق الصوتي. |
| [StartTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/starttime) { get; } | الحصول على وقت العرض التقديمي للكائن الأول ، مما يشير إلى مكان بدء دفق الوسائط الرقمية ضمن سياق المخطط الزمني لملف ASF ككل. |
| [StreamNumber](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamnumber) { get; } | الحصول على رقم هذا البث . |
| [StreamType](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamtype) { get; } | يحصل على نوع هذا الدفق . |

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

* [العمل مع البيانات الوصفية في ملفات ASF](https://docs.groupdocs.com/display/metadatanet/Working+with+Metadata+in+ASF+Files)

### أنظر أيضا

* class [AsfBaseStreamProperty](../asfbasestreamproperty)
* مساحة الاسم [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
