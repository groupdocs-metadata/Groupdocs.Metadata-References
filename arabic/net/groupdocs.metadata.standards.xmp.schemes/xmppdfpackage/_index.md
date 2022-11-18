---
title: XmpPdfPackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يحدد الخصائص المستخدمة مع مستندات Adobe PDF .
type: docs
weight: 3190
url: /ar/net/groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/
---
## XmpPdfPackage class

يحدد الخصائص المستخدمة مع مستندات Adobe PDF .

```csharp
public sealed class XmpPdfPackage : XmpPackage
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [XmpPdfPackage](xmppdfpackage)() | يقوم بتهيئة مثيل جديد لملف[`XmpPdfPackage`](../xmppdfpackage) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [IsTrapped](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/istrapped) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان المستند قد تم احتجازه. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [Keywords](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/keywords) { get; set; } | الحصول على الكلمات الأساسية أو تعيينها. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | يحصل على مساحة الاسم URI. |
| [PdfVersion](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/pdfversion) { get; set; } | الحصول على أو تحديد إصدار ملف PDF. على سبيل المثال ، 1.0 و 1.3 وما إلى ذلك . |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | يحصل على بادئة xmlns . |
| [Producer](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/producer) { get; set; } | الحصول على أو تحديد اسم الأداة التي أنشأت مستند PDF. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
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
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/set#set_7)(string, string) | تعيين خاصية السلسلة . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | يعيّن القيمة الموروثة من[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | يعيّن القيمة الموروثة من[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | يعيّن القيمة الموروثة من[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) و[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) إذا كانت خاصية موجودة تحقق القيمة الأصلية ، فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند ، فستتم إضافتها إلى الحزمة. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |

### أنظر أيضا

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* مساحة الاسم [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
