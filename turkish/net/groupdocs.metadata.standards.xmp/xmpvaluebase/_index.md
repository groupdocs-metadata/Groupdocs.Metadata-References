---
title: XmpValueBase
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Temel XMP değerini temsil eder.
type: docs
weight: 3620
url: /tr/net/groupdocs.metadata.standards.xmp/xmpvaluebase/
---
## XmpValueBase class

Temel XMP değerini temsil eder.

```csharp
public abstract class XmpValueBase : PropertyValue, IXmpType
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [RawValue](../../groupdocs.metadata.common/propertyvalue/rawvalue) { get; } | Ham değeri alır. |
| [Type](../../groupdocs.metadata.common/propertyvalue/type) { get; } | Şunu alır:[`MetadataPropertyType`](../../groupdocs.metadata.common/metadatapropertytype) . |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AcceptValue](../../groupdocs.metadata.common/propertyvalue/acceptvalue)(ValueAcceptor) | Özellik değerini özel kullanarak çıkarır[`ValueAcceptor`](../../groupdocs.metadata.common/valueacceptor) . |
| abstract [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpvaluebase/getxmprepresentation)() | XMP biçiminde dizge içerdiği değeri döndürür. |
| [ToArray&lt;TElement&gt;](../../groupdocs.metadata.common/propertyvalue/toarray)() | Özellik değerini belirtilen türden bir diziye dönüştürür. |
| [ToClass&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/toclass)() | Özellik değerini bir referans türüne dönüştürür. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpvaluebase/tostring)() | Özellik değerini temsil eden bir dize döndürür. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)() | Özellik değerini bir değer türüne dönüştürür. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)(T) | Özellik değerini bir değer türüne dönüştürür. |

### Ayrıca bakınız

* class [PropertyValue](../../groupdocs.metadata.common/propertyvalue)
* interface [IXmpType](../ixmptype)
* ad alanı [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->