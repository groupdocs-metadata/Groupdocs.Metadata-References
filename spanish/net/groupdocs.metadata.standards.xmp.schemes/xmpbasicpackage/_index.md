---
title: XmpBasicPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa el espacio de nombres básico de XMP.
type: docs
weight: 3090
url: /es/net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/
---
## XmpBasicPackage class

Representa el espacio de nombres básico de XMP.

```csharp
public sealed class XmpBasicPackage : XmpPackage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpBasicPackage](xmpbasicpackage)() | Inicializa una nueva instancia del[`XmpBasicPackage`](../xmpbasicpackage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BaseUrl](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/baseurl) { get; set; } | Obtiene o establece la URL base para las URL relativas en el contenido del documento. Si este documento contiene vínculos de Internet y esos vínculos son relativos, son relativos a esta URL base. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [CreateDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/createdate) { get; set; } | Obtiene o establece la fecha y la hora en que se creó el recurso. |
| [CreatorTool](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/creatortool) { get; set; } | Obtiene o establece el nombre de la herramienta utilizada para crear el recurso. |
| [Identifiers](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/identifiers) { get; set; } | Obtiene o establece una matriz desordenada de cadenas de texto que identifican sin ambigüedad el recurso dentro de un contexto determinado. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Label](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/label) { get; set; } | Obtiene o establece una palabra o frase corta que identifica el recurso como miembro de una colección definida por el usuario. |
| [MetadataDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/metadatadate) { get; set; } | Obtiene o establece la fecha y la hora en que se modificaron por última vez los metadatos de este recurso. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [ModifyDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/modifydate) { get; set; } | Obtiene o establece la fecha y la hora en que se modificó por última vez el recurso. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Obtiene el URI del espacio de nombres. |
| [Nickname](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/nickname) { get; set; } | Obtiene o establece un nombre corto e informal para el recurso. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Obtiene el prefijo xmlns. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Rating](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/rating) { get; set; } | Obtiene o establece una clasificación asignada por el usuario para este archivo. El valor debe ser -1 o estar en el rango [0..5], donde -1 indica "rechazado" y 0 indica "sin clasificar". |
| [Thumbnails](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/thumbnails) { get; set; } | Obtiene o establece una matriz de imágenes en miniatura para el archivo, que pueden diferir en características como el tamaño o la codificación de la imagen. |
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
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/set#set_7)(string, string) | Agrega propiedad de cadena. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Establece el valor heredado de[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Establece el valor heredado de[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Establece el valor heredado de[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [RatingMax](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingmax) | Valor máximo de calificación. |
| const [RatingMin](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingmin) | Valor mínimo de calificación. |
| const [RatingRejected](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingrejected) | Valor de calificación rechazada. |

### Ver también

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* espacio de nombres [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
