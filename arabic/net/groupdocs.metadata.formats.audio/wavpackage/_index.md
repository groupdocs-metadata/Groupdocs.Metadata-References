---
title: WavPackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل حزمة بيانات وصفية أصلية في ملف صوت WAV.
type: docs
weight: 590
url: /ar/net/groupdocs.metadata.formats.audio/wavpackage/
---
## WavPackage class

يمثل حزمة بيانات وصفية أصلية في ملف صوت WAV.

```csharp
public sealed class WavPackage : CustomPackage
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [WavPackage](wavpackage)() | يقوم بتهيئة مثيل جديد لملف[`WavPackage`](../wavpackage) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AudioFormat](../../groupdocs.metadata.formats.audio/wavpackage/audioformat) { get; } | يحصل على تنسيق الصوت . PCM = 1 (أي التكميم الخطي). تشير القيم بخلاف 1 إلى شكل من أشكال الضغط. |
| [BitsPerSample](../../groupdocs.metadata.formats.audio/wavpackage/bitspersample) { get; } | الحصول على وحدات البت لكل قيمة عينة. |
| [BlockAlign](../../groupdocs.metadata.formats.audio/wavpackage/blockalign) { get; } | الحصول على محاذاة الكتلة . |
| [ByteRate](../../groupdocs.metadata.formats.audio/wavpackage/byterate) { get; } | يحصل على معدل البايت . |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [NumberOfChannels](../../groupdocs.metadata.formats.audio/wavpackage/numberofchannels) { get; } | الحصول على عدد القنوات. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [SampleRate](../../groupdocs.metadata.formats.audio/wavpackage/samplerate) { get; } | يحصل على معدل العينة . |

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

* [معالجة البيانات الوصفية في ملفات WAV](https://docs.groupdocs.com/display/metadatanet/Handling+metadata+in+WAV+files)

### أمثلة

يوضح نموذج التعليمات البرمجية هذا كيفية استخراج المعلومات الصوتية التقنية من ملف WAV.

```csharp
using (Metadata metadata = new Metadata(Constants.InputWav))
{
    var root = metadata.GetRootPackage<WavRootPackage>();
    if (root.WavPackage != null)
    {
        Console.WriteLine(root.WavPackage.AudioFormat);
        Console.WriteLine(root.WavPackage.BitsPerSample);
        Console.WriteLine(root.WavPackage.BlockAlign);
        Console.WriteLine(root.WavPackage.ByteRate);
        Console.WriteLine(root.WavPackage.NumberOfChannels);
        Console.WriteLine(root.WavPackage.SampleRate);
    }
}
```

### أنظر أيضا

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
