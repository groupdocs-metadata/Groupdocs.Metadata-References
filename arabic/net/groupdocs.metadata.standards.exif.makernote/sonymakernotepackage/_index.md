---
title: SonyMakerNotePackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل SONY MakerNote البيانات الوصفية.
type: docs
weight: 2860
url: /ar/net/groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/
---
## SonyMakerNotePackage class

يمثل SONY MakerNote البيانات الوصفية.

```csharp
public sealed class SonyMakerNotePackage : MakerNotePackage
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AFIlluminator](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/afilluminator) { get; } | يحصل على نوع إضاءة AF . |
| [Brightness](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/brightness) { get; } | يحصل على السطوع. |
| [ColorMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/colormode) { get; } | يحصل على وضع اللون. |
| [ColorTemperature](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/colortemperature) { get; } | يحصل على درجة حرارة اللون. |
| [Contrast](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/contrast) { get; } | الحصول على التباين . |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [CreativeStyle](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/creativestyle) { get; } | يحصل على النمط الإبداعي . |
| [ExposureMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/exposuremode) { get; } | يحصل على وضع التعريض . |
| [FlashLevel](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/flashlevel) { get; } | يحصل على مستوى الفلاش . |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/focusmode) { get; } | يحصل على وضع التركيز . |
| [Header](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/header) { get; } | الحصول على رأس MakerNote . |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | يحصل على علامة TIFF بالمعرف المحدد. (2 indexers) |
| [JpegQuality](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/jpegquality) { get; } | الحصول على جودة JPEG . |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [Macro](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/macro) { get; } | يحصل على الماكرو . |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [MultiBurstImageHeight](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/multiburstimageheight) { get; } | الحصول على ارتفاع الصورة متعددة اللقطات. |
| [MultiBurstImageWidth](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/multiburstimagewidth) { get; } | الحصول على عرض الصورة متعددة الدفقات. |
| [MultiBurstMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/multiburstmode) { get; } | يحصل على قيمة تشير إلى ما إذا كان وضع الدفق المتعدد قيد التشغيل. |
| [PictureEffect](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/pictureeffect) { get; } | يحصل على تأثير الصورة . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [Quality](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/quality) { get; } | الحصول على جودة الصورة. |
| [Rating](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/rating) { get; } | يحصل على التصنيف. |
| [ReleaseMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/releasemode) { get; } | يحصل على وضع الإصدار. |
| [Saturation](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/saturation) { get; } | يحصل على التشبع. |
| [Sharpness](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/sharpness) { get; } | يحصل على الحدة . |
| [SoftSkinEffect](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/softskineffect) { get; } | يحصل على تأثير البشرة الناعم . |
| [SonyModelID](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/sonymodelid) { get; } | الحصول على معرف طراز سوني . |
| [Teleconverter](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/teleconverter) { get; } | يحصل على نوع محول التقريب . |
| [WhiteBalance](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/whitebalance) { get; } | يحصل على توازن اللون الأبيض. |

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

### أنظر أيضا

* class [MakerNotePackage](../makernotepackage)
* مساحة الاسم [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
