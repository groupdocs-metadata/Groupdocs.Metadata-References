---
title: OpenTypeFlags
second_title: GroupDocs.Metadata لمرجع .NET API
description: يمثل أعلام رأس خط OpenType .
type: docs
weight: 1450
url: /ar/net/groupdocs.metadata.formats.font/opentypeflags/
---
## OpenTypeFlags enumeration

يمثل أعلام رأس خط OpenType .

```csharp
[Flags]
public enum OpenTypeFlags : ushort
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| None | `0` | غير محدد ، بلا إشارات . |
| BaselineAtY0 | `1` | خط الأساس للخط عند y = 0. |
| LeftSidebearingAtX0 | `2` | نقطة الاتجاه الجانبي اليسرى عند x = 0 (ذات صلة فقط بأدوات التنقيط TrueType) . |
| DependOnPointSize | `4` | قد تعتمد التعليمات على حجم النقطة. |
| ForceToInteger | `8` | إجبار جزء في المليون على قيم عدد صحيح لجميع الرياضيات الداخلية للقياس ؛ قد تستخدم أحجام كسور جزء في المليون إذا كان هذا البت واضحًا. |
| AlterAdvanceWidth | `10` | قد تغير التعليمات العرض المتقدم (قد لا يتم قياس العرض المتقدم خطيًا) . |
| Lossless | `1000` | بيانات الخط "بدون فقدان" نتيجة تعرضها للتحويل و / أو الضغط الأمثل . |
| Converted | `2000` | تم تحويل الخط (إنتاج مقاييس متوافقة). |
| Optimized | `4000` | تم تحسين الخط لـ ClearType ™ . |
| Resort | `8000` | الخط الأخير . |

### أنظر أيضا

* مساحة الاسم [GroupDocs.Metadata.Formats.Font](../../groupdocs.metadata.formats.font)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->