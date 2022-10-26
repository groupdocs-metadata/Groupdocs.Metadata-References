---
title: XmpPagedTextPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa el paquete de texto paginado XMP.
type: docs
weight: 3180
url: /es/net/groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/
---
## XmpPagedTextPackage class

Representa el paquete de texto paginado XMP.

```csharp
public sealed class XmpPagedTextPackage : XmpPackage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpPagedTextPackage](xmppagedtextpackage)() | Inicializa una nueva instancia del[`XmpPagedTextPackage`](../xmppagedtextpackage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Colorants](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/colorants) { get; set; } | Obtiene o establece una matriz ordenada de colorantes (muestras) que se utilizan en el documento (incluido cualquiera de los documentos contenidos). |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Fonts](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/fonts) { get; set; } | Obtiene o establece una matriz desordenada de fuentes que se utilizan en el documento (incluidas las de los documentos contenidos). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MaxPageSize](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/maxpagesize) { get; set; } | Obtiene o establece el tamaño de la página más grande del documento (incluidas las de los documentos contenidos). |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Obtiene el URI del espacio de nombres. |
| [NumberOfPages](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/numberofpages) { get; set; } | Obtiene o establece el número de páginas del documento. |
| [PlateNames](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/platenames) { get; set; } | Obtiene o establece una matriz ordenada de nombres de placas que se necesitan para imprimir el documento (incluido cualquiera de los documentos contenidos). |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Obtiene el prefijo xmlns. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Obtiene el espacio de nombres XML. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Elimina todas las propiedades XMP. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Convierte el valor XMP a la representación XML. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Elimina la propiedad con el nombre especificado. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Establece la propiedad booleana. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | ConjuntosDateTime propiedad. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Establece doble propiedad. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Establece propiedad de número entero. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/set#set_7)(string, string) | Establece la propiedad de la cadena. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/set#set_2)(string, XmpArray) | Establece el valor heredado de[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Establece el valor heredado de[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Establece el valor heredado de[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Ver también

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* espacio de nombres [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
