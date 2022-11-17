---
title: XmpCameraRawPackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل مخطط Camera Raw.
type: docs
weight: 3100
url: /ar/net/groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/
---
## XmpCameraRawPackage class

يمثل مخطط Camera Raw.

```csharp
public sealed class XmpCameraRawPackage : XmpPackage
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [XmpCameraRawPackage](xmpcamerarawpackage)() | يقوم بتهيئة مثيل جديد لملف[`XmpCameraRawPackage`](../xmpcamerarawpackage) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AutoBrightness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autobrightness) { get; set; } | الحصول على قيمة السطوع التلقائي أو تعيينها. عندما يكون صحيحًا ،[`Brightness`](./brightness) يتم ضبطه تلقائيًا. |
| [AutoContrast](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autocontrast) { get; set; } | الحصول على قيمة AutoContrast أو تعيينها. عندما يكون صحيحًا ، يتم ضبط "التباين" تلقائيًا . |
| [AutoExposure](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autoexposure) { get; set; } | الحصول على قيمة AutoExposure أو تعيينها. عندما يكون صحيحًا ، يتم ضبط "التعرض" تلقائيًا . |
| [AutoShadows](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autoshadows) { get; set; } | الحصول على أو تعيين قيمة AutoShadows. عندما يكون صحيحًا ، يتم ضبط "الظلال" تلقائيًا . |
| [BlueHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/bluehue) { get; set; } | الحصول على قيمة BlueHue أو تعيينها. لاغية إذا كانت غير محددة. |
| [BlueSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/bluesaturation) { get; set; } | الحصول على BlueSaturation أو تعيينه. لاغية إذا كانت غير محددة. |
| [Brightness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/brightness) { get; set; } | الحصول على قيمة السطوع أو تعيينها. لاغية إذا كانت غير محددة. |
| [CameraProfile](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cameraprofile) { get; set; } | الحصول على أو تحديد قيمة CameraProfile . |
| [ChromaticAberrationB](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/chromaticaberrationb) { get; set; } | الحصول على أو تعيين إعداد "الانحراف اللوني وإصلاح هامش أزرق / أصفر". لاغية إذا كانت غير محددة. |
| [ChromaticAberrationR](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/chromaticaberrationr) { get; set; } | الحصول على أو تعيين إعداد "الانحراف اللوني وإصلاح الأحمر / السماوي الهامش". لاغية إذا كانت غير محددة. |
| [ColorNoiseReduction](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/colornoisereduction) { get; set; } | الحصول على أو تعيين إعداد تقليل ضوضاء اللون. النطاق 0 إلى 100. |
| [Contrast](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/contrast) { get; set; } | الحصول على إعداد التباين أو تعيينه. النطاق -50 إلى 100. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [CropAngle](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropangle) { get; set; } | الحصول على إعداد CropAngle أو تعيينه. عندما يكون HasCrop صحيحًا ، تكون زاوية مستطيل الاقتصاص. |
| [CropBottom](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropbottom) { get; set; } | الحصول على إعداد CropBottom أو تعيينه. عندما يكون HasCrop صحيحًا ، يكون الجزء السفلي من مستطيل الاقتصاص. |
| [CropHeight](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropheight) { get; set; } | الحصول على أو تحديد ارتفاع الصورة التي تم اقتصاصها الناتجة بتنسيق[`CropUnits`](./cropunits) الوحدات . |
| [CropLeft](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropleft) { get; set; } | الحصول على إعداد CropLeft أو تعيينه. عندما يكون HasCrop صحيحًا ، يسار مستطيل الاقتصاص. |
| [CropRight](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropright) { get; set; } | الحصول على إعداد CropRight أو تعيينه. عندما يكون HasCrop صحيحًا ، يمين مستطيل الاقتصاص. |
| [CropTop](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/croptop) { get; set; } | الحصول على إعداد CropTop أو تعيينه. عندما يكون HasCrop صحيحًا ، يكون الجزء العلوي من مستطيل الاقتصاص. |
| [CropUnits](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropunits) { get; set; } | الحصول على أو تعيين وحدات لـ[`CropWidth`](./cropwidth) و[`CropHeight`](./cropheight) . |
| [CropWidth](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropwidth) { get; set; } | الحصول على أو تحديد عرض الصورة التي تم اقتصاصها الناتجة بتنسيق[`CropUnits`](./cropunits) الوحدات . |
| [Exposure](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/exposure) { get; set; } | الحصول على إعداد التعرض أو تعيينه. |
| [GreenHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/greenhue) { get; set; } | الحصول على أو ضبط إعداد Green Hue. النطاق -100 إلى 100. |
| [GreenSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/greensaturation) { get; set; } | الحصول على أو ضبط إعداد Green Saturation. النطاق -100 إلى 100. |
| [HasCrop](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/hascrop) { get; set; } | الحصول على قيمة HasCrop أو تعيينها. عندما تكون الصورة صحيحة ، تحتوي الصورة على مستطيل اقتصاص. |
| [HasSettings](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/hassettings) { get; set; } | الحصول على قيمة HasSettings أو تعيينها. عندما يكون صحيحًا ، فإن إعدادات خام الكاميرا غير الافتراضية. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [LuminanceSmoothing](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/luminancesmoothing) { get; set; } | الحصول على إعداد LuminanceSmoothing أو تعيينه. النطاق 0 إلى 100. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | يحصل على مساحة الاسم URI. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | يحصل على بادئة xmlns . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [RawFileName](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/rawfilename) { get; set; } | الحصول على أو تحديد اسم الملف لملف خام (ليس مسارًا كاملاً) . |
| [RedHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/redhue) { get; set; } | الحصول على إعداد Red Hue أو تعيينه. النطاق -100 إلى 100. |
| [RedSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/redsaturation) { get; set; } | الحصول على أو ضبط إعداد Red Saturation. النطاق -100 إلى 100. |
| [Saturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/saturation) { get; set; } | الحصول على إعداد التشبع أو تعيينه. النطاق -100 إلى 100. |
| [Shadows](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/shadows) { get; set; } | الحصول على إعداد الظلال أو تعيينه. النطاق 0 إلى 100. |
| [ShadowTint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/shadowtint) { get; set; } | الحصول على إعداد ShadowTint أو تعيينه. النطاق -100 إلى 100. |
| [Sharpness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/sharpness) { get; set; } | الحصول على إعداد الحدة أو تعيينه. النطاق 0 إلى 100. |
| [Temperature](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/temperature) { get; set; } | الحصول على أو ضبط إعداد درجة الحرارة. النطاق 2000 إلى 50000. |
| [Tint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/tint) { get; set; } | الحصول على إعداد الصبغة أو تعيينه. النطاق -150 إلى 150. |
| [Version](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/version) { get; set; } | الحصول على إصدار مكون Camera Raw الإضافي أو تعيينه. |
| [VignetteAmount](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/vignetteamount) { get; set; } | الحصول على أو تعيين إعداد مبلغ نقوش الصورة النصفية. النطاق -100 إلى 100. |
| [VignetteMidpoint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/vignettemidpoint) { get; set; } | الحصول على إعداد Vignetting Midpoint أو تعيينه. النطاق 0 إلى 100. |
| [WhiteBalance](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/whitebalance) { get; } | يحصل على إعداد توازن اللون الأبيض. يستخدم[`SetWhiteBalance`](./setwhitebalance) لتعيين قيمة توازن اللون الأبيض. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | الحصول على مساحة اسم XML . |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يضيف خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | يزيل كافة خصائص XMP . |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | لتحديد ما إذا كانت الحزمة تحتوي على خاصية بيانات التعريف بالاسم المحدد. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | البحث عن خصائص البيانات الوصفية التي تفي بالمسند المحدد. البحث متكرر لذا فهو يؤثر على جميع الحزم المتداخلة أيضًا. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | إرجاع عداد يتكرر خلال المجموعة. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | تحويل قيمة XMP إلى تمثيل XML. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | يزيل الخاصية بالاسم المحدد . |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | يزيل خصائص البيانات الوصفية التي تفي بالتقييم المحدد. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | إزالة خصائص البيانات الوصفية القابلة للكتابة من الحزمة. العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | تعيين الخاصية المنطقية . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | مجموعات DateTime الملكية . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | يعين خاصية مزدوجة. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | يعين خاصية العدد الصحيح . |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/set#set_7)(string, string) | يضيف خاصية السلسلة . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | يعيّن القيمة الموروثة من[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | يعيّن القيمة الموروثة من[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | يعيّن القيمة الموروثة من[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) و[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) إذا كانت خاصية موجودة تحقق القيمة الأصلية ، فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند ، فستتم إضافتها إلى الحزمة. |
| [SetWhiteBalance](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/setwhitebalance)(XmpWhiteBalance) | يضبط توازن اللون الأبيض. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |

### أنظر أيضا

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* مساحة الاسم [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
