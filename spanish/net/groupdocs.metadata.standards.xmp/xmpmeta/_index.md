---
title: XmpMeta
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa xmpmeta. Opcional. El propósito de este elemento es identificar los metadatos XMP dentro del texto XML general que podría contener otros usos no XMP de RDF.
type: docs
weight: 3460
url: /es/net/groupdocs.metadata.standards.xmp/xmpmeta/
---
## XmpMeta class

Representa xmpmeta. Opcional. El propósito de este elemento es identificar los metadatos XMP dentro del texto XML general que podría contener otros usos no XMP de RDF.

```csharp
public sealed class XmpMeta : XmpElementBase, IXmpType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpMeta](xmpmeta)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AdobeXmpToolkit](../../groupdocs.metadata.standards.xmp/xmpmeta/adobexmptoolkit) { get; } | Obtiene la versión del kit de herramientas Adobe XMP. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [ClearAttributes](../../groupdocs.metadata.standards.xmp/xmpelementbase/clearattributes)() | Elimina todos los atributos. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| [ContainsAttribute](../../groupdocs.metadata.standards.xmp/xmpelementbase/containsattribute)(string) | Determina si el elemento contiene un atributo específico. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetAttribute](../../groupdocs.metadata.standards.xmp/xmpelementbase/getattribute)(string) | Obtiene el atributo. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpmeta/getxmprepresentation)() | Convierte el valor XMP a la representación xml. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| override [SetAttribute](../../groupdocs.metadata.standards.xmp/xmpmeta/setattribute)(string, string) | Agrega un atributo. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Ver también

* class [XmpElementBase](../xmpelementbase)
* interface [IXmpType](../ixmptype)
* espacio de nombres [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
