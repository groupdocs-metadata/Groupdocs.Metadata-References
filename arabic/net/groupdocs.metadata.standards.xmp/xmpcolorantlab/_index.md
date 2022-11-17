---
title: XmpColorantLab
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل LAB Colorant .
type: docs
weight: 3330
url: /ar/net/groupdocs.metadata.standards.xmp/xmpcolorantlab/
---
## XmpColorantLab class

يمثل LAB Colorant .

```csharp
public sealed class XmpColorantLab : XmpColorantBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [XmpColorantLab](xmpcolorantlab#constructor)() | يقوم بتهيئة مثيل جديد لملف[`XmpColorantLab`](../xmpcolorantlab) فئة . |
| [XmpColorantLab](xmpcolorantlab#constructor_1)(sbyte, sbyte, double) | يقوم بتهيئة مثيل جديد لملف[`XmpColorantLab`](../xmpcolorantlab) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [A](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/a) { get; set; } | الحصول على المكون "أ" أو تعيينه. |
| [B](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/b) { get; set; } | الحصول على أو تعيين المكون B . |
| [ColorType](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/colortype) { get; set; } | الحصول على أو تحديد نوع اللون. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [L](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/l) { get; set; } | الحصول على أو تعيين المكون L. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [Mode](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/mode) { get; } | يحصل على مساحة اللون التي يتم فيها تعريف اللون. واحد من: CMYK ، RGB ، LAB . |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | الحصول على مساحة الاسم URIs المستخدمة في ملف[`XmpComplexType`](../xmpcomplextype) المثال. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | الحصول على بادئات مساحة الاسم المستخدمة في ملف[`XmpComplexType`](../xmpcomplextype) المثال. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [SwatchName](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/swatchname) { get; set; } | الحصول على أو تحديد اسم العينة. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يضيف خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | لتحديد ما إذا كانت الحزمة تحتوي على خاصية بيانات التعريف بالاسم المحدد. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | البحث عن خصائص البيانات الوصفية التي تفي بالمسند المحدد. البحث متكرر لذا فهو يؤثر على جميع الحزم المتداخلة أيضًا. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | إرجاع عداد يتكرر خلال المجموعة. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | الحصول على مساحة الاسم URI المرتبطة بالبادئة المحددة. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | سلسلة إرجاع القيمة المضمنة بتنسيق XMP. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | يزيل خصائص البيانات الوصفية التي تفي بالتقييم المحدد. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | إزالة خصائص البيانات الوصفية القابلة للكتابة من الحزمة. العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) و[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) إذا كانت خاصية موجودة تحقق القيمة الأصلية ، فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند ، فستتم إضافتها إلى الحزمة. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | إرجاع أString الذي يمثل هذا المثال. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [MaxL](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/maxl) | القيمة القصوى للمكون L . |
| const [MinL](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/minl) | قيمة الحد الأدنى للمكون . |

### أنظر أيضا

* class [XmpColorantBase](../xmpcolorantbase)
* مساحة الاسم [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
