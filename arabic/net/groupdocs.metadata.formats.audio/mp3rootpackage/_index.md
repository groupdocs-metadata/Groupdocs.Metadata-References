---
title: MP3RootPackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل الحزمة الجذرية التي تسمح بالعمل مع البيانات الوصفية في ملف صوتي MP3.
type: docs
weight: 580
url: /ar/net/groupdocs.metadata.formats.audio/mp3rootpackage/
---
## MP3RootPackage class

يمثل الحزمة الجذرية التي تسمح بالعمل مع البيانات الوصفية في ملف صوتي MP3.

```csharp
public class MP3RootPackage : RootMetadataPackage, IXmp
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [ApeV2](../../groupdocs.metadata.formats.audio/mp3rootpackage/apev2) { get; } | يحصل على البيانات الوصفية لـ APE v2. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | يحصل على حزمة البيانات الوصفية لنوع الملف. |
| [ID3V1](../../groupdocs.metadata.formats.audio/mp3rootpackage/id3v1) { get; set; } | الحصول على أو تعيين علامة البيانات الوصفية ID3v1 . يرجى العثور على مزيد من المعلومات على[http://id3.org/ID3v1](http://id3.org/ID3v1) . |
| [ID3V2](../../groupdocs.metadata.formats.audio/mp3rootpackage/id3v2) { get; set; } | الحصول على علامة البيانات الوصفية ID3v2 أو تعيينها. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [Lyrics3V2](../../groupdocs.metadata.formats.audio/mp3rootpackage/lyrics3v2) { get; set; } | الحصول على علامة البيانات الوصفية لـ Lyrics3v2 أو تعيينها. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [MpegAudioPackage](../../groupdocs.metadata.formats.audio/mp3rootpackage/mpegaudiopackage) { get; } | يحصل على حزمة البيانات الوصفية الصوتية MPEG . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [XmpPackage](../../groupdocs.metadata.formats.audio/mp3rootpackage/xmppackage) { get; set; } | الحصول على حزمة بيانات تعريف XMP أو تعيينها. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يضيف خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | لتحديد ما إذا كانت الحزمة تحتوي على خاصية بيانات التعريف بالاسم المحدد. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | البحث عن خصائص البيانات الوصفية التي تفي بالمسند المحدد. البحث متكرر لذا فهو يؤثر على جميع الحزم المتداخلة أيضًا. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | إرجاع عداد يتكرر خلال المجموعة. |
| [RemoveApeV2](../../groupdocs.metadata.formats.audio/mp3rootpackage/removeapev2)() | يزيل علامة الصوت APEv2 . |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | يزيل خصائص البيانات الوصفية التي تفي بالتقييم المحدد. |
| override [Sanitize](../../groupdocs.metadata.formats.audio/mp3rootpackage/sanitize)() | إزالة خصائص البيانات الوصفية القابلة للكتابة من الحزمة. العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) و[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) إذا كانت خاصية موجودة تحقق القيمة الأصلية ، فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند ، فستتم إضافتها إلى الحزمة. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |

### ملاحظات

**يتعلم أكثر**

* [العمل مع بيانات تعريف MP3](https://docs.groupdocs.com/display/metadatanet/Working+with+MP3+metadata)
* [العمل مع بيانات تعريف XMP](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### أنظر أيضا

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* مساحة الاسم [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
