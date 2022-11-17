---
title: MatroskaAudioTrack
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل البيانات الوصفية الصوتية في فيديو Matroska.
type: docs
weight: 2430
url: /ar/net/groupdocs.metadata.formats.video/matroskaaudiotrack/
---
## MatroskaAudioTrack class

يمثل البيانات الوصفية الصوتية في فيديو Matroska.

```csharp
public class MatroskaAudioTrack : MatroskaTrack
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [BitDepth](../../groupdocs.metadata.formats.video/matroskaaudiotrack/bitdepth) { get; } | الحصول على وحدات البت لكل عينة ، والتي تُستخدم في الغالب لـ PCM . |
| [Channels](../../groupdocs.metadata.formats.video/matroskaaudiotrack/channels) { get; } | يحصل على عدد القنوات في المسار . |
| [CodecID](../../groupdocs.metadata.formats.video/matroskatrack/codecid) { get; } | يحصل على معرف مطابق لبرنامج الترميز . |
| [CodecName](../../groupdocs.metadata.formats.video/matroskatrack/codecname) { get; } | الحصول على سلسلة يمكن قراءتها بواسطة الإنسان تحدد برنامج الترميز. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [DefaultDuration](../../groupdocs.metadata.formats.video/matroskatrack/defaultduration) { get; } | الحصول على عدد النانو ثانية (لم يتم قياسه بواسطة[`TimecodeScale`](../matroskasegment/timecodescale) ) لكل إطار . |
| [FlagEnabled](../../groupdocs.metadata.formats.video/matroskatrack/flagenabled) { get; } | يحصل على العلم الممكّن ، صحيح إذا كان المسار صالحًا للاستخدام. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [Language](../../groupdocs.metadata.formats.video/matroskatrack/language) { get; } | الحصول على لغة المسار في نموذج لغات Matroska . يجب تجاهل هذا العنصر إذا كان[`LanguageIetf`](../matroskatrack/languageietf) يتم استخدام العنصر في نفس TrackEntry . |
| [LanguageIetf](../../groupdocs.metadata.formats.video/matroskatrack/languageietf) { get; } | الحصول على لغة المسار وفقًا لـ BCP 47 واستخدام سجل العلامات الفرعية للغة IANA. إذا تم استخدام هذا العنصر ، فعندئذٍ أي عنصر[`Language`](../matroskatrack/language) يجب تجاهل العناصر المستخدمة في نفس TrackEntry . |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [Name](../../groupdocs.metadata.formats.video/matroskatrack/name) { get; } | الحصول على اسم المسار الذي يمكن قراءته بواسطة الإنسان. |
| [OutputSamplingFrequency](../../groupdocs.metadata.formats.video/matroskaaudiotrack/outputsamplingfrequency) { get; } | الحصول على تردد أخذ العينات الناتج الحقيقي بالهرتز (المستخدمة لتقنيات SBR) . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [SamplingFrequency](../../groupdocs.metadata.formats.video/matroskaaudiotrack/samplingfrequency) { get; } | الحصول على تردد أخذ العينات بالهرتز . |
| [TrackNumber](../../groupdocs.metadata.formats.video/matroskatrack/tracknumber) { get; } | الحصول على رقم المسار كما هو مستخدم في Block Header. لا يُنصح باستخدام أكثر من 127 مسارًا ، على الرغم من أن التصميم يسمح بعدد غير محدود . |
| [TrackType](../../groupdocs.metadata.formats.video/matroskatrack/tracktype) { get; } | يحصل على نوع المسار. |
| [TrackUid](../../groupdocs.metadata.formats.video/matroskatrack/trackuid) { get; } | يحصل على المعرّف الفريد لتعريف المسار. يجب الاحتفاظ بهذا المعرّف كما هو عند عمل نسخة دفق مباشرة من المسار إلى ملف آخر. |

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

* [التعامل مع البيانات الوصفية في ملفات Matroska (MKV)](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### أنظر أيضا

* class [MatroskaTrack](../matroskatrack)
* مساحة الاسم [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
