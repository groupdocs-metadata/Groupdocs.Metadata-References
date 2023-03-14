---
title: ToStruct
second_title: GroupDocs.Metadata لمرجع .NET API
description: تحويل قيمة الخاصية إلى نوع قيمة.
type: docs
weight: 80
url: /ar/net/groupdocs.metadata.common/propertyvalue/tostruct/
---
## ToStruct&lt;T&gt;() {#tostruct}

تحويل قيمة الخاصية إلى نوع قيمة.

```csharp
public T? ToStruct<T>()
    where T : struct
```

| معامل | وصف |
| --- | --- |
| T | النوع الدقيق المطلوب التحويل إليه. |

### قيمة الإرجاع

القيمة المحولة أو القيمة الفارغة إذا لم يكن هناك مثل هذا التحويل.

### أنظر أيضا

* class [PropertyValue](../../propertyvalue)
* مساحة الاسم [GroupDocs.Metadata.Common](../../propertyvalue)
* المجسم [GroupDocs.Metadata](../../../)

---

## ToStruct&lt;T&gt;(T) {#tostruct_1}

تحويل قيمة الخاصية إلى نوع قيمة.

```csharp
public T ToStruct<T>(T @default)
    where T : struct
```

| معامل | وصف |
| --- | --- |
| T | النوع الدقيق المطلوب التحويل إليه. |
| default | قيمة يجب استخدامها بشكل افتراضي في حالة فشل التحويل. |

### قيمة الإرجاع

القيمة المحولة أو القيمة الافتراضية المحددة إذا لم يكن هناك مثل هذا التحويل.

### أنظر أيضا

* class [PropertyValue](../../propertyvalue)
* مساحة الاسم [GroupDocs.Metadata.Common](../../propertyvalue)
* المجسم [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->