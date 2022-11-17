---
title: OpenTypeFont
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل خطًا واحدًا مستخرجًا من ملف.
type: docs
weight: 1460
url: /ar/net/groupdocs.metadata.formats.font/opentypefont/
---
## OpenTypeFont class

يمثل خطًا واحدًا مستخرجًا من ملف.

```csharp
public class OpenTypeFont : CustomPackage
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [Created](../../groupdocs.metadata.formats.font/opentypefont/created) { get; } | يحصل على تاريخ الإنشاء. |
| [DirectionHint](../../groupdocs.metadata.formats.font/opentypefont/directionhint) { get; } | يحصل على تلميح الاتجاه. |
| [EmbeddingLicensingRights](../../groupdocs.metadata.formats.font/opentypefont/embeddinglicensingrights) { get; } | يحصل على نوع حقوق ترخيص التضمين . |
| [Flags](../../groupdocs.metadata.formats.font/opentypefont/flags) { get; } | يحصل على أعلام الرأس . |
| [FontFamilyName](../../groupdocs.metadata.formats.font/opentypefont/fontfamilyname) { get; } | يحصل على اسم عائلة الخط. |
| [FontRevision](../../groupdocs.metadata.formats.font/opentypefont/fontrevision) { get; } | يحصل على مراجعة الخط. |
| [FontSubfamilyName](../../groupdocs.metadata.formats.font/opentypefont/fontsubfamilyname) { get; } | يحصل على اسم العائلة الفرعية للخط. |
| [FullFontName](../../groupdocs.metadata.formats.font/opentypefont/fullfontname) { get; } | الحصول على الاسم الكامل للخط. |
| [GlyphBounds](../../groupdocs.metadata.formats.font/opentypefont/glyphbounds) { get; } | يحصل على حدود الصورة الرمزية . |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [MajorVersion](../../groupdocs.metadata.formats.font/opentypefont/majorversion) { get; } | الحصول على إصدار العنوان الرئيسي . |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [MinorVersion](../../groupdocs.metadata.formats.font/opentypefont/minorversion) { get; } | يحصل على نسخة الرأس الثانوية. |
| [Modified](../../groupdocs.metadata.formats.font/opentypefont/modified) { get; } | يحصل على التاريخ المعدل . |
| [Names](../../groupdocs.metadata.formats.font/opentypefont/names) { get; } | يحصل على سجلات الاسم . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [SfntVersion](../../groupdocs.metadata.formats.font/opentypefont/sfntversion) { get; } | يحصل على نسخة رأس SFNT . |
| [Style](../../groupdocs.metadata.formats.font/opentypefont/style) { get; } | يحصل على نمط الخط . |
| [TypographicFamily](../../groupdocs.metadata.formats.font/opentypefont/typographicfamily) { get; } | يحصل على عائلة الطباعة . |
| [TypographicSubfamily](../../groupdocs.metadata.formats.font/opentypefont/typographicsubfamily) { get; } | يحصل على العائلة الفرعية المطبعية. |
| [Weight](../../groupdocs.metadata.formats.font/opentypefont/weight) { get; } | الحصول على وزن الخط. |
| [Width](../../groupdocs.metadata.formats.font/opentypefont/width) { get; } | يحصل على عرض الخط . |

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

* [العمل مع خطوط OpenType](https://docs.groupdocs.com/display/metadatanet/Working+with+OpenType+fonts)

### أنظر أيضا

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Font](../../groupdocs.metadata.formats.font)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
