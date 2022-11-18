---
title: LyricsTag
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل Lyrics3 v2.00 metadata. يرجى العثور على مزيد من المعلومات علىhttp//id3.org/Lyrics3v2 .
type: docs
weight: 570
url: /ar/net/groupdocs.metadata.formats.audio/lyricstag/
---
## LyricsTag class

يمثل Lyrics3 v2.00 metadata. يرجى العثور على مزيد من المعلومات علىhttp://id3.org/Lyrics3v2 .

```csharp
public sealed class LyricsTag : CustomPackage
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [LyricsTag](lyricstag)() | يقوم بتهيئة مثيل جديد لملف[`LyricsTag`](../lyricstag) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AdditionalInfo](../../groupdocs.metadata.formats.audio/lyricstag/additionalinfo) { get; set; } | الحصول على المعلومات الإضافية أو تعيينها. يتم تمثيل هذه القيمة بواسطة حقل INF. |
| [Album](../../groupdocs.metadata.formats.audio/lyricstag/album) { get; set; } | الحصول على اسم الألبوم أو تحديده. يتم تمثيل هذه القيمة بواسطة حقل EAL . |
| [Artist](../../groupdocs.metadata.formats.audio/lyricstag/artist) { get; set; } | الحصول على أو تحديد اسم الفنان. يتم تمثيل هذه القيمة بواسطة حقل EAR . |
| [Author](../../groupdocs.metadata.formats.audio/lyricstag/author) { get; set; } | الحصول على المؤلف أو تعيينه. يتم تمثيل هذه القيمة بواسطة حقل AUT . |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [Lyrics](../../groupdocs.metadata.formats.audio/lyricstag/lyrics) { get; set; } | الحصول على أو تعيين كلمات الأغاني . يتم تمثيل هذه القيمة بواسطة حقل LYR. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [Track](../../groupdocs.metadata.formats.audio/lyricstag/track) { get; set; } | الحصول على عنوان المسار أو تعيينه. يتم تمثيل هذه القيمة بواسطة حقل ETT . |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يضيف خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | لتحديد ما إذا كانت الحزمة تحتوي على خاصية بيانات التعريف بالاسم المحدد. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | البحث عن خصائص البيانات الوصفية التي تفي بالمسند المحدد. البحث متكرر لذا فهو يؤثر على جميع الحزم المتداخلة أيضًا. |
| [Get](../../groupdocs.metadata.formats.audio/lyricstag/get)(string) | يحصل على قيمة الحقل بالمعرف المحدد. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | إرجاع عداد يتكرر خلال المجموعة. |
| [Remove](../../groupdocs.metadata.formats.audio/lyricstag/remove)(string) | يزيل الحقل بالمعرف المحدد. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | يزيل خصائص البيانات الوصفية التي تفي بالتقييم المحدد. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | إزالة خصائص البيانات الوصفية القابلة للكتابة من الحزمة. العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [Set](../../groupdocs.metadata.formats.audio/lyricstag/set)(LyricsField) | إضافة أو استبدال حقل Lyrics3 المحدد. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) و[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) إذا كانت خاصية موجودة تحقق القيمة الأصلية ، فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند ، فستتم إضافتها إلى الحزمة. |
| [ToList](../../groupdocs.metadata.formats.audio/lyricstag/tolist)() | إنشاء قائمة من الحزمة . |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |

### ملاحظات

تستخدم Lyrics3 v2.00 الحقول لتمثيل المعلومات. يمكن أن تتكون البيانات في الحقل من أحرف ASCII في النطاق من 01 إلى 254 وفقًا للمعيار . نظرًا لأن مخطط أحرف ASCII محدد فقط من 00 إلى 128 ISO-8859- 1 قد يفترض. تتكون الحقول الرقمية من 5 أو 6 أحرف ، اعتمادًا على الموقع ، ومبطنة بالأصفار.

**يتعلم أكثر**

* [التعامل مع علامة الأغاني](https://docs.groupdocs.com/display/metadatanet/Handling+the+Lyrics+tag)

### أمثلة

يوضح نموذج التعليمات البرمجية هذا كيفية قراءة علامة Lyrics من ملف MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithLyrics))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.Lyrics3V2 != null)
    {
        Console.WriteLine(root.Lyrics3V2.Lyrics);
        Console.WriteLine(root.Lyrics3V2.Album);
        Console.WriteLine(root.Lyrics3V2.Artist);
        Console.WriteLine(root.Lyrics3V2.Track);

        // ...

        // بدلاً من ذلك ، يمكنك إجراء حلقة عبر قائمة كاملة بحقول العلامات
        foreach (var field in root.Lyrics3V2.ToList())
        {
            Console.WriteLine("{0} = {1}", field.ID, field.Data);
        }
    }
}
```

### أنظر أيضا

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
