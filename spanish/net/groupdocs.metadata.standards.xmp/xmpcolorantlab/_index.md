---
title: XmpColorantLab
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa el colorante LAB.
type: docs
weight: 3330
url: /es/net/groupdocs.metadata.standards.xmp/xmpcolorantlab/
---
## XmpColorantLab class

Representa el colorante LAB.

```csharp
public sealed class XmpColorantLab : XmpColorantBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpColorantLab](xmpcolorantlab#constructor)() | Inicializa una nueva instancia del[`XmpColorantLab`](../xmpcolorantlab) clase. |
| [XmpColorantLab](xmpcolorantlab#constructor_1)(sbyte, sbyte, double) | Inicializa una nueva instancia del[`XmpColorantLab`](../xmpcolorantlab) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [A](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/a) { get; set; } | Obtiene o establece el componente A. |
| [B](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/b) { get; set; } | Obtiene o establece el componente B. |
| [ColorType](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/colortype) { get; set; } | Obtiene o establece el tipo de color. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [L](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/l) { get; set; } | Obtiene o establece el componente L. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [Mode](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/mode) { get; } | Obtiene el espacio de color en el que se define el color. Uno de: CMYK, RGB, LAB. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Obtiene los URI de espacio de nombres que se usan en el[`XmpComplexType`](../xmpcomplextype) instancia. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Obtiene los prefijos de espacio de nombres que se utilizan en el[`XmpComplexType`](../xmpcomplextype) instancia. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [SwatchName](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/swatchname) { get; set; } | Obtiene o establece el nombre de la muestra. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | Obtiene el URI del espacio de nombres asociado con el prefijo especificado. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | Devuelve el valor contenido en la cadena en formato XMP. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | Devuelve unString que representa esta instancia. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [MaxL](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/maxl) | Valor máx. componente L. |
| const [MinL](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/minl) | Valor mín. componente L. |

### Ver también

* class [XmpColorantBase](../xmpcolorantbase)
* espacio de nombres [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
