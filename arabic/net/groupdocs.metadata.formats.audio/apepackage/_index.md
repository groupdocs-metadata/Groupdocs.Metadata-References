---
title: ApePackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل حزمة بيانات تعريف APE v2 . الرجاء العثور على مزيد من المعلومات علىhttp//wiki.hydrogenaud.io/index.phptitleAPE_keyhttp//wiki.hydrogenaud.io/index.phptitleAPE_key .
type: docs
weight: 380
url: /ar/net/groupdocs.metadata.formats.audio/apepackage/
---
## ApePackage class

يمثل حزمة بيانات تعريف APE v2 . الرجاء العثور على مزيد من المعلومات على[http://wiki.hydrogenaud.io/index.php؟title=APE_key](http://wiki.hydrogenaud.io/index.php?title=APE_key) .

```csharp
public sealed class ApePackage : CustomPackage
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Abstract](../../groupdocs.metadata.formats.audio/apepackage/abstract) { get; } | يحصل على رابط الملخص . |
| [Album](../../groupdocs.metadata.formats.audio/apepackage/album) { get; } | يحصل على الألبوم. |
| [Artist](../../groupdocs.metadata.formats.audio/apepackage/artist) { get; } | يحصل على الفنان . |
| [Bibliography](../../groupdocs.metadata.formats.audio/apepackage/bibliography) { get; } | يحصل على قائمة المراجع . |
| [Comment](../../groupdocs.metadata.formats.audio/apepackage/comment) { get; } | يحصل على التعليق . |
| [Composer](../../groupdocs.metadata.formats.audio/apepackage/composer) { get; } | الحصول على الملحن . |
| [Conductor](../../groupdocs.metadata.formats.audio/apepackage/conductor) { get; } | يحصل على الموصل. |
| [Copyright](../../groupdocs.metadata.formats.audio/apepackage/copyright) { get; } | يحصل على حقوق النشر. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [DebutAlbum](../../groupdocs.metadata.formats.audio/apepackage/debutalbum) { get; } | يحصل على الألبوم الأول . |
| [File](../../groupdocs.metadata.formats.audio/apepackage/file) { get; } | يحصل على الملف. |
| [Genre](../../groupdocs.metadata.formats.audio/apepackage/genre) { get; } | يحصل على النوع. |
| [Isbn](../../groupdocs.metadata.formats.audio/apepackage/isbn) { get; } | الحصول على رقم ISBN برقم تحقق. شاهد المزيد: https://en.wikipedia.org/wiki/International_Standard_Book_Number. |
| [Isrc](../../groupdocs.metadata.formats.audio/apepackage/isrc) { get; } | الحصول على رقم التسجيل القياسي الدولي . |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [Language](../../groupdocs.metadata.formats.audio/apepackage/language) { get; } | يحصل على اللغة . |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [PublicationRight](../../groupdocs.metadata.formats.audio/apepackage/publicationright) { get; } | يحصل على النشر الصحيح . |
| [Publisher](../../groupdocs.metadata.formats.audio/apepackage/publisher) { get; } | يحصل على الناشر. |
| [RecordLocation](../../groupdocs.metadata.formats.audio/apepackage/recordlocation) { get; } | يحصل على موقع السجل . |
| [Subtitle](../../groupdocs.metadata.formats.audio/apepackage/subtitle) { get; } | الحصول على الترجمة . |
| [Title](../../groupdocs.metadata.formats.audio/apepackage/title) { get; } | يحصل على العنوان. |
| [Track](../../groupdocs.metadata.formats.audio/apepackage/track) { get; } | يحصل على رقم المسار . |

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

* [التعامل مع علامة APEv2](https://docs.groupdocs.com/display/metadatanet/Handling+the+APEv2+tag)

### أمثلة

يوضح هذا المثال كيفية قراءة علامة APEv2 في ملف MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithApe))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ApeV2 != null)
    {
        Console.WriteLine(root.ApeV2.Album);
        Console.WriteLine(root.ApeV2.Title);
        Console.WriteLine(root.ApeV2.Artist);
        Console.WriteLine(root.ApeV2.Composer);
        Console.WriteLine(root.ApeV2.Copyright);
        Console.WriteLine(root.ApeV2.Genre);
        Console.WriteLine(root.ApeV2.Language);

        // ...
    }
}
```

### أنظر أيضا

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
