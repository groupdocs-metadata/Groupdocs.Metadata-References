---
title: MsgPackage
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل البيانات الوصفية لرسالة MSG .
type: docs
weight: 1400
url: /ar/net/groupdocs.metadata.formats.email/msgpackage/
---
## MsgPackage class

يمثل البيانات الوصفية لرسالة MSG .

```csharp
public class MsgPackage : EmailPackage
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AttachedFileNames](../../groupdocs.metadata.formats.email/emailpackage/attachedfilenames) { get; } | يحصل على مصفوفة من أسماء الملفات المرفقة. |
| [BlindCarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/blindcarboncopyrecipients) { get; set; } | الحصول على أو تعيين مصفوفة BCC (نسخة كربونية مخفية) لمستلمي رسالة البريد الإلكتروني. |
| [Body](../../groupdocs.metadata.formats.email/msgpackage/body) { get; } | يحصل على نص رسالة البريد الإلكتروني. |
| [CarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/carboncopyrecipients) { get; set; } | الحصول على أو تعيين مجموعة مستلمي CC (نسخة كربونية) لرسالة البريد الإلكتروني. |
| [Categories](../../groupdocs.metadata.formats.email/msgpackage/categories) { get; } | يحصل على مجموعة من الفئات أو الكلمات الرئيسية . |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [DeliveryTime](../../groupdocs.metadata.formats.email/msgpackage/deliverytime) { get; } | الحصول على تاريخ ووقت تسليم الرسالة. |
| [Headers](../../groupdocs.metadata.formats.email/emailpackage/headers) { get; } | يحصل على حزمة بيانات وصفية تحتوي على رؤوس البريد الإلكتروني. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [Recipients](../../groupdocs.metadata.formats.email/emailpackage/recipients) { get; set; } | الحصول على أو تعيين مصفوفة مستلمي البريد الإلكتروني. |
| [Sender](../../groupdocs.metadata.formats.email/emailpackage/sender) { get; } | الحصول على عنوان البريد الإلكتروني الخاص بالمرسل. |
| [Subject](../../groupdocs.metadata.formats.email/emailpackage/subject) { get; set; } | الحصول على موضوع البريد الإلكتروني أو تعيينه. |

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

* [التعامل مع رسائل البريد الإلكتروني المحفوظة](https://docs.groupdocs.com/display/metadatanet/Working+with+saved+Emails)

### أنظر أيضا

* class [EmailPackage](../emailpackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Email](../../groupdocs.metadata.formats.email)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
