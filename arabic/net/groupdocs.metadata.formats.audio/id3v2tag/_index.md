---
title: ID3V2Tag
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل علامة ID3v2 . يرجى العثور على مزيد من المعلومات علىhttps//en.wikipedia.org/wiki/ID3ID3v2https//en.wikipedia.org/wiki/ID3ID3v2 .
type: docs
weight: 490
url: /ar/net/groupdocs.metadata.formats.audio/id3v2tag/
---
## ID3V2Tag class

يمثل علامة ID3v2 . يرجى العثور على مزيد من المعلومات على[https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2) .

```csharp
public sealed class ID3V2Tag : ID3Tag
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ID3V2Tag](id3v2tag)() | يقوم بتهيئة مثيل جديد لملف[`ID3V2Tag`](../id3v2tag) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v2tag/album) { get; set; } | الحصول على أو تحديد عنوان الألبوم / الفيلم / العرض. يتم تمثيل هذه القيمة بواسطة إطار TALB . |
| [Artist](../../groupdocs.metadata.formats.audio/id3v2tag/artist) { get; set; } | الحصول على أو تعيين الفنان (الفنانين) الرائدين / المؤدي (الفنانين) / العازف المنفرد (الفنانين) / المجموعة المؤدية. يتم تمثيل هذه القيمة بواسطة إطار TPE1. |
| [AttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/attachedpictures) { get; set; } | الحصول على أو تعيين الصور المرفقة المرتبطة مباشرة بملف الصوت. يتم تمثيل هذه القيمة بواسطة إطار APIC . |
| [Band](../../groupdocs.metadata.formats.audio/id3v2tag/band) { get; set; } | الحصول على أو تعيين النطاق / الأوركسترا / المرافقة. يتم تمثيل هذه القيمة بواسطة إطار TPE2. |
| [BitsPerMinute](../../groupdocs.metadata.formats.audio/id3v2tag/bitsperminute) { get; set; } | الحصول على أو تحديد عدد النبضات في الدقيقة في الجزء الرئيسي من الصوت. يتم تمثيل هذه القيمة بواسطة إطار TBPM . |
| [Comments](../../groupdocs.metadata.formats.audio/id3v2tag/comments) { get; set; } | الحصول على تعليقات المستخدم أو تعيينها. يتم تمثيل هذه القيمة بإطار COMM . الإطار مخصص لأي نوع من معلومات النص الكامل التي لا تتناسب مع أي إطار آخر. |
| [Composers](../../groupdocs.metadata.formats.audio/id3v2tag/composers) { get; set; } | الحصول على الملحنين أو تعيينهم. يتم فصل الأسماء بالحرف "/". يتم تمثيل هذه القيمة بواسطة إطار TCOM. |
| [ContentType](../../groupdocs.metadata.formats.audio/id3v2tag/contenttype) { get; set; } | الحصول على نوع المحتوى أو تعيينه. يتم تمثيل هذه القيمة بواسطة إطار TCON . |
| [Copyright](../../groupdocs.metadata.formats.audio/id3v2tag/copyright) { get; set; } | الحصول على رسالة حقوق النشر أو تعيينها. يتم تمثيل هذه القيمة بواسطة إطار TCOP . |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [Date](../../groupdocs.metadata.formats.audio/id3v2tag/date) { get; set; } | الحصول على أو تعيين سلسلة رقمية بتنسيق DDMM تحتوي على تاريخ التسجيل. يتكون هذا الحقل دائمًا من أربعة أحرف . يتم تمثيل هذه القيمة بواسطة إطار TDAT. |
| [EncodedBy](../../groupdocs.metadata.formats.audio/id3v2tag/encodedby) { get; set; } | الحصول على أو تحديد اسم الشخص أو المؤسسة التي قامت بتشفير الملف الصوتي. يتم تمثيل هذه القيمة بواسطة إطار TENC. |
| [Isrc](../../groupdocs.metadata.formats.audio/id3v2tag/isrc) { get; set; } | الحصول على أو تعيين رمز التسجيل القياسي الدولي (ISRC) (12 حرفًا) . يتم تمثيل هذه القيمة بواسطة إطار TSRC. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [LengthInMilliseconds](../../groupdocs.metadata.formats.audio/id3v2tag/lengthinmilliseconds) { get; set; } | الحصول على أو تحديد طول الملف الصوتي بالملي ثانية ، ممثلة كسلسلة رقمية. يتم تمثيل هذه القيمة بواسطة إطار TLEN. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [MusicalKey](../../groupdocs.metadata.formats.audio/id3v2tag/musicalkey) { get; set; } | الحصول على أو تعيين المفتاح الموسيقي الذي يبدأ فيه الصوت. يتم تمثيل هذه القيمة بواسطة إطار TKEY . |
| [OriginalAlbum](../../groupdocs.metadata.formats.audio/id3v2tag/originalalbum) { get; set; } | الحصول على أو تحديد عنوان الألبوم / الفيلم / العرض الأصلي. يتم تمثيل هذه القيمة بواسطة إطار TOAL . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [Publisher](../../groupdocs.metadata.formats.audio/id3v2tag/publisher) { get; set; } | الحصول على أو تحديد اسم الملصق أو الناشر. يتم تمثيل هذه القيمة بواسطة إطار TPUB . |
| [SizeInBytes](../../groupdocs.metadata.formats.audio/id3v2tag/sizeinbytes) { get; set; } | الحصول على أو تحديد حجم الملف الصوتي بالبايت ، باستثناء علامة ID3v2 ، الممثلة كسلسلة رقمية. يتم تمثيل هذه القيمة بإطار TSIZ. |
| [SoftwareHardware](../../groupdocs.metadata.formats.audio/id3v2tag/softwarehardware) { get; set; } | الحصول على أو تعيين برنامج تشفير الصوت المستخدم وإعداداته عند ترميز الملف. يتم تمثيل هذه القيمة بواسطة إطار TSSE. |
| [Subtitle](../../groupdocs.metadata.formats.audio/id3v2tag/subtitle) { get; set; } | الحصول على أو تعيين تحسين الترجمة / الوصف. يتم تمثيل هذه القيمة بواسطة إطار TIT3. |
| [TagSize](../../groupdocs.metadata.formats.audio/id3v2tag/tagsize) { get; } | يحصل على حجم العلامة . |
| [Time](../../groupdocs.metadata.formats.audio/id3v2tag/time) { get; set; } | الحصول على أو تعيين سلسلة رقمية بتنسيق HHMM تحتوي على وقت التسجيل. يتكون هذا الحقل دائمًا من أربعة أحرف . يتم تمثيل هذه القيمة بإطار الوقت. |
| [Title](../../groupdocs.metadata.formats.audio/id3v2tag/title) { get; set; } | الحصول على أو تحديد العنوان / اسم الأغنية / وصف المحتوى. يتم تمثيل هذه القيمة بواسطة إطار TIT2. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v2tag/tracknumber) { get; set; } | الحصول على أو تعيين سلسلة رقمية تحتوي على رقم طلب الملف الصوتي في تسجيله الأصلي. يتم تمثيل هذه القيمة بواسطة إطار TRCK . |
| [TrackPlayCounter](../../groupdocs.metadata.formats.audio/id3v2tag/trackplaycounter) { get; } | يحصل على عدد مرات تشغيل الملف. يتم تمثيل هذه القيمة بواسطة إطار PCNT . |
| override [Version](../../groupdocs.metadata.formats.audio/id3v2tag/version) { get; } | يحصل على إصدار ID3 . |
| [Year](../../groupdocs.metadata.formats.audio/id3v2tag/year) { get; set; } | الحصول على أو تعيين سلسلة رقمية مع سنة التسجيل. تتكون هذه الإطارات دائمًا من أربعة أحرف (حتى عام 10000) . يتم تمثيل هذه القيمة بواسطة إطار TYER . |

## طُرق

| اسم | وصف |
| --- | --- |
| [Add](../../groupdocs.metadata.formats.audio/id3v2tag/add)(ID3V2TagFrame) | يضيف إطارًا إلى العلامة . |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يضيف خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [Clear](../../groupdocs.metadata.formats.audio/id3v2tag/clear)(string) | يزيل كل الإطارات بالمعرف المحدد. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | لتحديد ما إذا كانت الحزمة تحتوي على خاصية بيانات التعريف بالاسم المحدد. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | البحث عن خصائص البيانات الوصفية التي تفي بالمسند المحدد. البحث متكرر لذا فهو يؤثر على جميع الحزم المتداخلة أيضًا. |
| [Get](../../groupdocs.metadata.formats.audio/id3v2tag/get)(string) | يحصل على مجموعة من الإطارات بالمعرف المحدد. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | إرجاع عداد يتكرر خلال المجموعة. |
| [Remove](../../groupdocs.metadata.formats.audio/id3v2tag/remove)(ID3V2TagFrame) | يزيل الإطار المحدد من العلامة . |
| [RemoveAttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/removeattachedpictures)() | يزيل كافة الصور المرفقة المخزنة في إطارات APIC . |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | يزيل خصائص البيانات الوصفية التي تفي بالتقييم المحدد. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | إزالة خصائص البيانات الوصفية القابلة للكتابة من الحزمة. العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [Set](../../groupdocs.metadata.formats.audio/id3v2tag/set)(ID3V2TagFrame) | يزيل كل الإطارات التي لها نفس المعرف المحدد ويضيف الإطار الجديد إلى العلامة. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) و[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) إذا كانت خاصية موجودة تحقق القيمة الأصلية ، فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند ، فستتم إضافتها إلى الحزمة. |
| [ToList](../../groupdocs.metadata.formats.audio/id3v2tag/tolist)() | إنشاء قائمة من الحزمة . |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |

### ملاحظات

**يتعلم أكثر**

* [التعامل مع علامة ID3v2](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### أمثلة

يوضح هذا المثال كيفية قراءة علامة ID3v2 في ملف MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V2 != null)
    {
        Console.WriteLine(root.ID3V2.Album);
        Console.WriteLine(root.ID3V2.Artist);
        Console.WriteLine(root.ID3V2.Band);
        Console.WriteLine(root.ID3V2.Title);
        Console.WriteLine(root.ID3V2.Composers);
        Console.WriteLine(root.ID3V2.Copyright);
        Console.WriteLine(root.ID3V2.Publisher);
        Console.WriteLine(root.ID3V2.OriginalAlbum);
        Console.WriteLine(root.ID3V2.MusicalKey);

        if (root.ID3V2.AttachedPictures != null)
        {
            foreach (var attachedPicture in root.ID3V2.AttachedPictures)
            {
                Console.WriteLine(attachedPicture.AttachedPictureType);
                Console.WriteLine(attachedPicture.MimeType);
                Console.WriteLine(attachedPicture.Description);

                // ...
            }
        }

        // ...
    }
}
```

### أنظر أيضا

* class [ID3Tag](../id3tag)
* مساحة الاسم [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
