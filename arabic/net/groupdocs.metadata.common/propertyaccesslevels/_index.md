---
title: PropertyAccessLevels
second_title: GroupDocs.Metadata لمرجع .NET API
description: يحدد مستويات الوصول لخصائص البيانات الوصفية.
type: docs
weight: 180
url: /ar/net/groupdocs.metadata.common/propertyaccesslevels/
---
## PropertyAccessLevels enumeration

يحدد مستويات الوصول لخصائص البيانات الوصفية.

```csharp
[Flags]
public enum PropertyAccessLevels
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| Read | `0` | الخاصية للقراءة فقط . |
| Update | `1` | من الممكن تحديث الخاصية باستخدام امتداد[`UpdateProperties`](../metadatapackage/updateproperties) طريقة . |
| Remove | `2` | يمكن إزالة الخاصية من خلال ملف[`RemoveProperties`](../metadatapackage/removeproperties) طريقة . |
| Add | `4` | من الممكن تحديث الخاصية باستخدام امتداد[`AddProperties`](../metadatapackage/addproperties) طريقة . |
| Full | `7` | يمنح حق الوصول الكامل إلى العقار . |
| AddOrUpdate | `5` | يسمح بإضافة وتحديث الخاصية. جميع العمليات الأخرى مقيدة. |

### أنظر أيضا

* مساحة الاسم [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* المجسم [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
