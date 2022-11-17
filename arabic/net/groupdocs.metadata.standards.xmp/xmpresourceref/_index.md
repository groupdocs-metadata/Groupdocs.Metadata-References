---
title: XmpResourceRef
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل مرجعًا متعدد الأجزاء لمورد. يُستخدم للإشارة إلى الإصدارات السابقة  والأصول الأصلية لعمليات التسليم  والنسخ الأصلية للمستندات المشتقة  وما إلى ذلك.
type: docs
weight: 3550
url: /ar/net/groupdocs.metadata.standards.xmp/xmpresourceref/
---
## XmpResourceRef class

يمثل مرجعًا متعدد الأجزاء لمورد. يُستخدم للإشارة إلى الإصدارات السابقة ، والأصول الأصلية لعمليات التسليم ، والنسخ الأصلية للمستندات المشتقة ، وما إلى ذلك.

```csharp
public sealed class XmpResourceRef : XmpComplexType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [XmpResourceRef](xmpresourceref)() | يقوم بتهيئة مثيل جديد لملف[`XmpResourceRef`](../xmpresourceref) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AlternatePaths](../../groupdocs.metadata.standards.xmp/xmpresourceref/alternatepaths) { get; set; } | الحصول على أو تعيين مسارات الملفات الاحتياطية للمورد المشار إليه أو عناوين URL. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [DocumentID](../../groupdocs.metadata.standards.xmp/xmpresourceref/documentid) { get; set; } | الحصول على أو تعيين قيمة xmpMM: خاصية DocumentID من المورد المشار إليه. |
| [FilePath](../../groupdocs.metadata.standards.xmp/xmpresourceref/filepath) { get; set; } | الحصول على أو تحديد مسار ملف المورد المشار إليه أو عنوان URL. |
| [InstanceID](../../groupdocs.metadata.standards.xmp/xmpresourceref/instanceid) { get; set; } | الحصول على أو تعيين قيمة xmpMM: خاصية معرف المثيل من المورد المشار إليه. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [LastModifyDate](../../groupdocs.metadata.standards.xmp/xmpresourceref/lastmodifydate) { get; set; } | الحصول على قيمة stEvt أو تعيينها: متى تمت كتابة الملف لآخر مرة. |
| [Manager](../../groupdocs.metadata.standards.xmp/xmpresourceref/manager) { get; set; } | الحصول على أو تعيين xmpMM للمورد المشار إليه: Manager. |
| [ManagerVariant](../../groupdocs.metadata.standards.xmp/xmpresourceref/managervariant) { get; set; } | الحصول على أو تعيين xmpMM للمورد المشار إليه: Manager. |
| [ManageTo](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageto) { get; set; } | الحصول على أو تعيين xmpMM للمورد المشار إليه: ManageTo. |
| [ManageUI](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageui) { get; set; } | الحصول على أو تعيين xmpMM للمورد المشار إليه: ManageUI. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | الحصول على مساحة الاسم URIs المستخدمة في ملف[`XmpComplexType`](../xmpcomplextype) المثال. |
| [PartMapping](../../groupdocs.metadata.standards.xmp/xmpresourceref/partmapping) { get; set; } | الحصول على أو تعيين الاسم أو URI لوظيفة التعيين المستخدمة لتعيين fromPart إلى الجزء toPart . |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | الحصول على بادئات مساحة الاسم المستخدمة في ملف[`XmpComplexType`](../xmpcomplextype) المثال. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [RenditionClass](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionclass) { get; set; } | الحصول على أو تعيين قيمة xmpMM: خاصية RenditionClass من المورد المشار إليه. |
| [RenditionParams](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionparams) { get; set; } | الحصول على أو تعيين قيمة خاصية xmpMM: RenditionParams من المورد المشار إليه. |
| [VersionID](../../groupdocs.metadata.standards.xmp/xmpresourceref/versionid) { get; set; } | الحصول على أو تعيين قيمة خاصية xmpMM: RenditionParams من المورد المشار إليه. |

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

### أنظر أيضا

* class [XmpComplexType](../xmpcomplextype)
* مساحة الاسم [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
