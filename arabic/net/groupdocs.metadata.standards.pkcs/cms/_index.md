---
title: Cms
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل علامة رقمية تم إنشاؤها باستخدام صيغة الرسائل المشفرة CMS  معيار IETF للرسائل المحمية بالتشفير. يعتمد CMS على بنية PKCS  7  المحدد في RFC 5652. يرجى الاطلاعhttps//tools.ietf.org/html/rfc5652https//tools.ietf.org/html/rfc5652 لمزيد من المعلومات.
type: docs
weight: 2960
url: /ar/net/groupdocs.metadata.standards.pkcs/cms/
---
## Cms class

يمثل علامة رقمية تم إنشاؤها باستخدام صيغة الرسائل المشفرة (CMS) - معيار IETF للرسائل المحمية بالتشفير. يعتمد CMS على بنية PKCS # 7 ، المحدد في RFC 5652. يرجى الاطلاع[https://tools.ietf.org/html/rfc5652](https://tools.ietf.org/html/rfc5652) لمزيد من المعلومات.

```csharp
public class Cms : DigitalSignature
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [CertificateRawData](../../groupdocs.metadata.standards.signing/digitalsignature/certificaterawdata) { get; } | يحصل على البيانات الأولية للشهادة . |
| [Certificates](../../groupdocs.metadata.standards.pkcs/cms/certificates) { get; } | الحصول على مجموعة الشهادات . |
| [CertificateSubject](../../groupdocs.metadata.standards.signing/digitalsignature/certificatesubject) { get; } | الحصول على الاسم المميز للموضوع من الشهادة . |
| [Comments](../../groupdocs.metadata.standards.signing/digitalsignature/comments) { get; } | الحصول على تعليق غرض التوقيع. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | الحصول على عدد خصائص البيانات الوصفية. |
| [DigestAlgorithms](../../groupdocs.metadata.standards.pkcs/cms/digestalgorithms) { get; } | يحصل على مصفوفة معرفات خوارزمية ملخص الرسالة. قد يكون هناك أي عدد من العناصر في المجموعة ، بما في ذلك صفر. |
| [EncapsulatedContent](../../groupdocs.metadata.standards.pkcs/cms/encapsulatedcontent) { get; } | الحصول على المحتوى الموقّع ، والذي يتكون من معرف نوع المحتوى والمحتوى نفسه. |
| virtual [IsValid](../../groupdocs.metadata.standards.signing/digitalsignature/isvalid) { get; } | يحصل على قيمة تشير إلى ما إذا كان التوقيع صالحًا. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | يحصل على ملف[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) بالاسم المحدد. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | الحصول على مجموعة من أسماء خصائص البيانات الوصفية. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | الحصول على نوع البيانات الوصفية . |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | يحصل على مجموعة من الواصفات التي تحتوي على معلومات حول الخصائص التي يمكن الوصول إليها من خلال GroupDocs.Metadata search engine . |
| [Signers](../../groupdocs.metadata.standards.pkcs/cms/signers) { get; } | الحصول على مجموعة حزم المعلومات لكل موقع. |
| override [SignTime](../../groupdocs.metadata.standards.pkcs/cms/signtime) { get; } | الحصول على الوقت الذي قام فيه الموقّع (المزعوم) بتنفيذ عملية التوقيع. |

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

* class [DigitalSignature](../../groupdocs.metadata.standards.signing/digitalsignature)
* مساحة الاسم [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
