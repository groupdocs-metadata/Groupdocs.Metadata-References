---
title: DublinCorePackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل حزمة بيانات تعريف دبلن كور .
type: docs
weight: 2730
url: /ar/net/groupdocs.metadata.standards.dublincore/dublincorepackage/
---
## DublinCorePackage class

يمثل حزمة بيانات تعريف دبلن كور .

```csharp
public sealed class DublinCorePackage : CustomPackage
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Contributor](../../groupdocs.metadata.standards.dublincore/dublincorepackage/contributor) { get; } | يحصل على العنصر المساهم دبلن Core . |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [Coverage](../../groupdocs.metadata.standards.dublincore/dublincorepackage/coverage) { get; } | يحصل على تغطية عنصر دبلن كور . |
| [Creator](../../groupdocs.metadata.standards.dublincore/dublincorepackage/creator) { get; } | الحصول على عنصر Dublin Core للمنشئ . |
| [Date](../../groupdocs.metadata.standards.dublincore/dublincorepackage/date) { get; } | يحصل على تاريخ عنصر دبلن كور . |
| [Description](../../groupdocs.metadata.standards.dublincore/dublincorepackage/description) { get; } | يحصل على وصف عنصر دبلن كور . |
| [Format](../../groupdocs.metadata.standards.dublincore/dublincorepackage/format) { get; } | يحصل على تنسيق عنصر دبلن كور . |
| [Identifier](../../groupdocs.metadata.standards.dublincore/dublincorepackage/identifier) { get; } | يحصل على معرف عنصر دبلن كور . |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [Language](../../groupdocs.metadata.standards.dublincore/dublincorepackage/language) { get; } | يحصل على عنصر اللغة دبلن كور . |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [Publisher](../../groupdocs.metadata.standards.dublincore/dublincorepackage/publisher) { get; } | يحصل على عنصر دبلن كور للناشر . |
| [Relation](../../groupdocs.metadata.standards.dublincore/dublincorepackage/relation) { get; } | يحصل على علاقة دبلن كور . |
| [Rights](../../groupdocs.metadata.standards.dublincore/dublincorepackage/rights) { get; } | يحصل على عنصر دبلن الأساسي للحقوق . |
| [Source](../../groupdocs.metadata.standards.dublincore/dublincorepackage/source) { get; } | يحصل على عنصر دبلن كور المصدر. |
| [Subject](../../groupdocs.metadata.standards.dublincore/dublincorepackage/subject) { get; } | يحصل على عنصر دبلن كور الموضوع . |
| [Title](../../groupdocs.metadata.standards.dublincore/dublincorepackage/title) { get; } | يحصل على العنوان Dublin Core element . |
| [Type](../../groupdocs.metadata.standards.dublincore/dublincorepackage/type) { get; } | يحصل على نوع عنصر دبلن كور . |

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

### أنظر أيضا

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* مساحة الاسم [GroupDocs.Metadata.Standards.DublinCore](../../groupdocs.metadata.standards.dublincore)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
