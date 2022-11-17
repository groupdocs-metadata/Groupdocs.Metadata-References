---
title: XmpDublinCorePackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل مخطط دبلن كور .
type: docs
weight: 3120
url: /ar/net/groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/
---
## XmpDublinCorePackage class

يمثل مخطط دبلن كور .

```csharp
public sealed class XmpDublinCorePackage : XmpPackage
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [XmpDublinCorePackage](xmpdublincorepackage)() | يقوم بتهيئة مثيل جديد لملف[`XmpDublinCorePackage`](../xmpdublincorepackage) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Contributors](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/contributors) { get; set; } | الحصول على مصفوفة من المساهمين أو تعيينها. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [Coverage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/coverage) { get; set; } | الحصول على أو تحديد مدى أو نطاق المورد. |
| [Creators](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/creators) { get; set; } | الحصول على أو تعيين مصفوفة من المبدعين. |
| [Dates](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/dates) { get; set; } | الحصول على أو تعيين مصفوفة من التواريخ المرتبطة بحدث في دورة حياة المورد. |
| [Descriptions](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/descriptions) { get; set; } | الحصول على أو تعيين مجموعة من الأوصاف النصية لمحتوى المصدر ، معطى بلغات مختلفة. |
| [Format](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/format) { get; set; } | الحصول على أو تعيين نوع MIME للمورد. |
| [Identifier](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/identifier) { get; set; } | الحصول على أو تعيين قيمة سلسلة تمثل مرجعًا لا لبس فيه للمورد ضمن سياق معين. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [Languages](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/languages) { get; set; } | الحصول على أو تعيين مجموعة من اللغات المستخدمة في محتوى المصدر. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | يحصل على مساحة الاسم URI. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | يحصل على بادئة xmlns . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [Publishers](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/publishers) { get; set; } | الحصول على أو تعيين مجموعة من الناشرين الذين أتاحوا المورد. |
| [Relations](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/relations) { get; set; } | الحصول على أو تعيين مصفوفة من الموارد ذات الصلة. |
| [Rights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/rights) { get; set; } | الحصول على مجموعة من بيانات الحقوق غير الرسمية أو تعيينها بلغات مختلفة. |
| [Source](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/source) { get; set; } | الحصول على أو تعيين المورد ذي الصلة الذي تم اشتقاق المورد الموصوف منه. |
| [Subjects](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/subjects) { get; set; } | الحصول على أو تعيين مجموعة من العبارات الوصفية أو الكلمات الأساسية التي تحدد محتوى المورد. |
| [Titles](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/titles) { get; set; } | الحصول على أو تحديد عنوان أو اسم المورد ، معطى بلغات مختلفة. |
| [Types](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/types) { get; set; } | الحصول على أو تعيين مجموعة من قيم السلسلة التي تمثل طبيعة أو نوع المورد. |
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
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, string) | تعيين خاصية السلسلة . |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/set#set_2)(string, XmpArray) | يعيّن القيمة الموروثة من[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | يعيّن القيمة الموروثة من[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | يعيّن القيمة الموروثة من[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetContributor](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcontributor)(string) | يعين مساهمًا واحدًا للمورد. |
| [SetCreator](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcreator)(string) | يعين منشئ واحد للمورد. |
| [SetDate](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdate)(DateTime) | يحدد تاريخًا واحدًا مرتبطًا بالمورد. |
| [SetDescription](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdescription)(string) | يعين وصف المورد الوارد بلغة واحدة. |
| [SetLanguage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setlanguage)(string) | يعين لغة واحدة مرتبطة بالمورد. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) و[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) إذا كانت خاصية موجودة تحقق القيمة الأصلية ، فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند ، فستتم إضافتها إلى الحزمة. |
| [SetPublisher](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setpublisher)(string) | يعين ناشرًا منفردًا للمورد. |
| [SetRelation](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrelation)(string) | يعين موردًا واحدًا ذا صلة . |
| [SetRights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrights)(string) | يعين حقوق المورد ، المعطاة بلغة واحدة. |
| [SetSubject](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setsubject)(string) | يعين موضوعًا واحدًا للمورد. |
| [SetTitle](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settitle)(string) | يعين عنوان المورد الوارد بلغة واحدة. |
| [SetType](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settype)(string) | يعين نوعًا واحدًا من المورد. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |

### ملاحظات

لمزيد من المعلومات راجع: http://dublincore.org/documents/usageguide/elements.shtml.

### أنظر أيضا

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* مساحة الاسم [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
