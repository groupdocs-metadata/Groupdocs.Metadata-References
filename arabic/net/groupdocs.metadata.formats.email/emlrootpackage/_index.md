---
title: EmlRootPackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل الحزمة الجذرية التي تسمح بالعمل مع البيانات الوصفية في رسالة بريد إلكتروني EML.
type: docs
weight: 1390
url: /ar/net/groupdocs.metadata.formats.email/emlrootpackage/
---
## EmlRootPackage class

يمثل الحزمة الجذرية التي تسمح بالعمل مع البيانات الوصفية في رسالة بريد إلكتروني EML.

```csharp
public class EmlRootPackage : EmailRootPackage
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [EmailPackage](../../groupdocs.metadata.formats.email/emlrootpackage/emailpackage) { get; } | الحصول على حزمة البيانات الوصفية لـ EML . (2 properties) |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | يحصل على حزمة البيانات الوصفية لنوع الملف. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يضيف خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [ClearAttachments](../../groupdocs.metadata.formats.email/emailrootpackage/clearattachments)() | يزيل جميع المرفقات من رسالة البريد الإلكتروني. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | لتحديد ما إذا كانت الحزمة تحتوي على خاصية بيانات التعريف بالاسم المحدد. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | البحث عن خصائص البيانات الوصفية التي تفي بالمسند المحدد. البحث متكرر لذا فهو يؤثر على جميع الحزم المتداخلة أيضًا. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | إرجاع عداد يتكرر خلال المجموعة. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | يزيل خصائص البيانات الوصفية التي تفي بالتقييم المحدد. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | إزالة خصائص البيانات الوصفية القابلة للكتابة من الحزمة. العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | تعيين خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا.[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) و[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) إذا كانت خاصية موجودة تحقق القيمة الأصلية ، فسيتم تحديث قيمتها. إذا كانت هناك خاصية معروفة مفقودة في الحزمة التي ترضي المسند ، فستتم إضافتها إلى الحزمة. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | يقوم بتحديث خصائص البيانات الوصفية المعروفة التي تفي بالمسند المحدد . العملية متكررة لذا فهي تؤثر على جميع الحزم المتداخلة أيضًا. |

### ملاحظات

**يتعلم أكثر**

* [التعامل مع رسائل البريد الإلكتروني المحفوظة](https://docs.groupdocs.com/display/metadatanet/Working+with+saved+Emails)

### أمثلة

يوضح نموذج التعليمات البرمجية هذا كيفية استخراج البيانات الوصفية من رسالة EML.

```csharp
using (Metadata metadata = new Metadata(Constants.InputEml))
{
    var root = metadata.GetRootPackage<EmlRootPackage>();

    Console.WriteLine(root.EmailPackage.Sender);
    Console.WriteLine(root.EmailPackage.Subject);
    foreach (string recipient in root.EmailPackage.Recipients)
    {
        Console.WriteLine(recipient);
    }

    foreach (var attachedFileName in root.EmailPackage.AttachedFileNames)
    {
        Console.WriteLine(attachedFileName);
    }

    foreach (var header in root.EmailPackage.Headers)
    {
        Console.WriteLine("{0} = {1}", header.Name, header.Value);
    }

    // ...
}
```

### أنظر أيضا

* class [EmailRootPackage](../emailrootpackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Email](../../groupdocs.metadata.formats.email)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
