---
title: VCardCommunicationRecordset
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل مجموعة من سجلات الاتصالات vCard . تصف هذه الخصائص معلومات حول كيفية الاتصال بالكائن الذي تمثله vCard .
type: docs
weight: 660
url: /ar/net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/
---
## VCardCommunicationRecordset class

يمثل مجموعة من سجلات الاتصالات vCard . تصف هذه الخصائص معلومات حول كيفية الاتصال بالكائن الذي تمثله vCard .

```csharp
public class VCardCommunicationRecordset : VCardRecordset
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [EmailRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/emailrecords) { get; } | الحصول على عناوين البريد الإلكتروني للتواصل مع الكائن. |
| [Emails](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/emails) { get; } | الحصول على عناوين البريد الإلكتروني للتواصل مع الكائن. |
| [ImppEntries](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/imppentries) { get; } | الحصول على محددات مواقع المعلومات (URI) للمراسلة الفورية واتصالات بروتوكول التواجد مع الكائن. |
| [ImppRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/impprecords) { get; } | الحصول على محددات مواقع المعلومات (URI) للمراسلة الفورية واتصالات بروتوكول التواجد مع الكائن. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [LanguageRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/languagerecords) { get; } | يحصل على اللغات التي يمكن استخدامها للاتصال بالكائن . |
| [Languages](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/languages) { get; } | يحصل على اللغات التي يمكن استخدامها للاتصال بالكائن . |
| [Mailer](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/mailer) { get; } | يحصل على نوع برنامج البريد الإلكتروني الذي يستخدمه الفرد المرتبط بـ vCard . |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [TelephoneRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/telephonerecords) { get; } | الحصول على أرقام الهاتف للاتصال الهاتفي مع الكائن. |
| [Telephones](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/telephones) { get; } | الحصول على أرقام الهاتف للاتصال الهاتفي مع الكائن. |

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

* [العمل مع بيانات تعريف vCard](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### أنظر أيضا

* class [VCardRecordset](../vcardrecordset)
* مساحة الاسم [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
