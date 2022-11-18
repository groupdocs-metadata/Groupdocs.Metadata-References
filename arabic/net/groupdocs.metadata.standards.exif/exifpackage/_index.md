---
title: ExifPackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل حزمة بيانات وصفية EXIF تنسيق ملف صورة قابل للتبديل .
type: docs
weight: 2790
url: /ar/net/groupdocs.metadata.standards.exif/exifpackage/
---
## ExifPackage class

يمثل حزمة بيانات وصفية EXIF (تنسيق ملف صورة قابل للتبديل) .

```csharp
public class ExifPackage : ExifDictionaryBasePackage
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ExifPackage](exifpackage)() | يقوم بتهيئة مثيل جديد لملف[`ExifPackage`](../exifpackage) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Artist](../../groupdocs.metadata.standards.exif/exifpackage/artist) { get; set; } | الحصول على أو تحديد اسم مالك الكاميرا أو المصور أو منشئ الصور. |
| [Copyright](../../groupdocs.metadata.standards.exif/exifpackage/copyright) { get; set; } | الحصول على أو تعيين إشعار حقوق النشر. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [DateTime](../../groupdocs.metadata.standards.exif/exifpackage/datetime) { get; set; } | الحصول على أو تحديد تاريخ ووقت إنشاء الصورة. في معيار EXIF ، هو تاريخ ووقت تغيير الملف. |
| [ExifIfdPackage](../../groupdocs.metadata.standards.exif/exifpackage/exififdpackage) { get; } | يحصل على بيانات EXIF IFD . |
| [GpsPackage](../../groupdocs.metadata.standards.exif/exifpackage/gpspackage) { get; } | يحصل على بيانات GPS . |
| [ImageDescription](../../groupdocs.metadata.standards.exif/exifpackage/imagedescription) { get; set; } | الحصول على أو تعيين سلسلة أحرف تعطي عنوان الصورة . قد يكون تعليقًا مثل "نزهة الشركة 1988" أو ما شابه. |
| [ImageLength](../../groupdocs.metadata.standards.exif/exifpackage/imagelength) { get; set; } | الحصول على أو تحديد عدد صفوف بيانات الصورة. |
| [ImageWidth](../../groupdocs.metadata.standards.exif/exifpackage/imagewidth) { get; set; } | الحصول على أو تعيين عدد أعمدة بيانات الصورة ، يساوي عدد البكسل لكل صف. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | يحصل على علامة TIFF بالمعرف المحدد. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [Make](../../groupdocs.metadata.standards.exif/exifpackage/make) { get; set; } | الحصول على أو تعيين الشركة المصنعة لمعدات التسجيل. هذه هي الشركة المصنعة لـ DSC أو الماسح الضوئي أو جهاز التحويل الرقمي للفيديو أو المعدات الأخرى التي أنشأت الصورة. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [Model](../../groupdocs.metadata.standards.exif/exifpackage/model) { get; set; } | الحصول على أو تحديد اسم الطراز أو رقم الطراز الخاص بالجهاز. هذا هو اسم الطراز أو رقم DSC أو الماسح الضوئي أو جهاز التحويل الرقمي للفيديو أو المعدات الأخرى التي أنشأت الصورة. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [Software](../../groupdocs.metadata.standards.exif/exifpackage/software) { get; set; } | الحصول على أو تحديد اسم وإصدار البرنامج أو البرنامج الثابت للكاميرا أو جهاز إدخال الصورة المستخدم في إنشاء الصورة. |
| [Thumbnail](../../groupdocs.metadata.standards.exif/exifpackage/thumbnail) { get; } | الحصول على الصورة المصغرة ممثلة كمصفوفة من البايت. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يضيف خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | يزيل كل علامات TIFF المخزنة في الحزمة. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | لتحديد ما إذا كانت الحزمة تحتوي على خاصية بيانات التعريف بالاسم المحدد. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | البحث عن خصائص البيانات الوصفية التي تفي بالمسند المحدد. البحث متكرر لذا فهو يؤثر على جميع الحزم المتداخلة أيضًا. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | إرجاع عداد يتكرر خلال المجموعة. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | يزيل الخاصية بالمعرف المحدد. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | يزيل خصائص البيانات الوصفية التي تفي بالتقييم المحدد. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | إزالة خصائص البيانات الوصفية القابلة للكتابة من الحزمة. العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | إضافة أو استبدال العلامة المحددة. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) و[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) إذا كانت خاصية موجودة تحقق القيمة الأصلية ، فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند ، فستتم إضافتها إلى الحزمة. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | إنشاء قائمة من الحزمة . |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |

### ملاحظات

**يتعلم أكثر**

* [العمل مع بيانات EXIF الوصفية](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### أمثلة

يوضح نموذج التعليمات البرمجية هذا كيفية تحديث خصائص EXIF الشائعة.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        // اضبط حزمة EXIF إذا كانت مفقودة
        if (root.ExifPackage == null)
        {
            root.ExifPackage = new ExifPackage();
        }

        root.ExifPackage.Copyright = "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.";
        root.ExifPackage.ImageDescription = "test image";
        root.ExifPackage.Software = "GroupDocs.Metadata";

        // ...

        root.ExifPackage.ExifIfdPackage.BodySerialNumber = "test";
        root.ExifPackage.ExifIfdPackage.CameraOwnerName = "GroupDocs";
        root.ExifPackage.ExifIfdPackage.UserComment = "test comment";

        // ...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### أنظر أيضا

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* مساحة الاسم [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
