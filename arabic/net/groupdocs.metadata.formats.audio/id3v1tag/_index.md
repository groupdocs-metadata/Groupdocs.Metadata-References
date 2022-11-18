---
title: ID3V1Tag
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل علامة ID3v1 . يرجى العثور على مزيد من المعلومات علىhttps//en.wikipedia.org/wiki/ID3ID3v1https//en.wikipedia.org/wiki/ID3ID3v1 .
type: docs
weight: 410
url: /ar/net/groupdocs.metadata.formats.audio/id3v1tag/
---
## ID3V1Tag class

يمثل علامة ID3v1 . يرجى العثور على مزيد من المعلومات على[https://en.wikipedia.org/wiki/ID3#ID3v1](https://en.wikipedia.org/wiki/ID3#ID3v1) .

```csharp
public sealed class ID3V1Tag : ID3Tag
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ID3V1Tag](id3v1tag)() | يقوم بتهيئة مثيل جديد لملف[`ID3V1Tag`](../id3v1tag) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v1tag/album) { get; set; } | الحصول على الألبوم أو تحديده. الحد الأقصى للطول هو 30 حرفًا. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v1tag/artist) { get; set; } | الحصول على الفنان أو تعيينه. الحد الأقصى للطول هو 30 حرفًا. |
| [Comment](../../groupdocs.metadata.formats.audio/id3v1tag/comment) { get; set; } | الحصول على التعليق أو تعيينه. الحد الأقصى للطول هو 30 حرفًا. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [GenreValue](../../groupdocs.metadata.formats.audio/id3v1tag/genrevalue) { get; } | الحصول على أو تحديد معرّف النوع. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [Title](../../groupdocs.metadata.formats.audio/id3v1tag/title) { get; set; } | الحصول على العنوان أو تعيينه. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v1tag/tracknumber) { get; set; } | الحصول على رقم المسار أو تحديده. مقدمة في علامة ID3v1.1 فقط. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v1tag/version) { get; } | يحصل على إصدار ID3. يمكن أن يكون ID3 أو ID3v1.1 |
| [Year](../../groupdocs.metadata.formats.audio/id3v1tag/year) { get; set; } | الحصول على السنة أو تحديدها. الحد الأقصى للطول هو 4 أحرف . |

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

علامة ID3 (v1) هي جزء صغير من البيانات الإضافية في نهاية MP3. يرجى العثور على مزيد من المعلومات على[http://id3.org/ID3v1](http://id3.org/ID3v1) .

**يتعلم أكثر**

* [التعامل مع علامة ID3v1](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v1+tag)

### أمثلة

يوضح نموذج التعليمات البرمجية هذا كيفية قراءة علامة ID3v1 في ملف MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V1))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V1 != null)
    {
        Console.WriteLine(root.ID3V1.Album);
        Console.WriteLine(root.ID3V1.Artist);
        Console.WriteLine(root.ID3V1.Title);
        Console.WriteLine(root.ID3V1.Version);
        Console.WriteLine(root.ID3V1.Comment);

        // ...
    }
}
```

### أنظر أيضا

* class [ID3Tag](../id3tag)
* مساحة الاسم [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
