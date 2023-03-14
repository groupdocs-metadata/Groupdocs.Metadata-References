---
title: ValueInterpreter
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Meta veri özellik değerlerini yorumlamak için gereken işlemleri tanımlar.
type: docs
weight: 260
url: /tr/net/groupdocs.metadata.common/valueinterpreter/
---
## ValueInterpreter class

Meta veri özellik değerlerini yorumlamak için gereken işlemleri tanımlar.

```csharp
public abstract class ValueInterpreter
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| abstract [InterpretedValueType](../../groupdocs.metadata.common/valueinterpreter/interpretedvaluetype) { get; } | Yorumlanan değerin türünü alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [ToInterpretedValue](../../groupdocs.metadata.common/valueinterpreter/tointerpretedvalue)(PropertyValue) | Sağlanan özellik değerini yorumlar. |
| [ToSourceValue](../../groupdocs.metadata.common/valueinterpreter/tosourcevalue)(PropertyValue) | Yorumlanmış bir değeri orijinal biçimine geri dönüştürür. |

### Ayrıca bakınız

* ad alanı [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->