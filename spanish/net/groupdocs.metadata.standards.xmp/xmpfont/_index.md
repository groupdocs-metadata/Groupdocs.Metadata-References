---
title: XmpFont
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Una estructura que contiene las características de una fuente utilizada en un documento.
type: docs
weight: 3400
url: /es/net/groupdocs.metadata.standards.xmp/xmpfont/
---
## XmpFont class

Una estructura que contiene las características de una fuente utilizada en un documento.

```csharp
public sealed class XmpFont : XmpComplexType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpFont](xmpfont#constructor)() | Inicializa una nueva instancia del[`XmpFont`](../xmpfont) clase. |
| [XmpFont](xmpfont#constructor_1)(string) | Inicializa una nueva instancia del[`XmpFont`](../xmpfont) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ChildFontFiles](../../groupdocs.metadata.standards.xmp/xmpfont/childfontfiles) { get; set; } | Obtiene o establece la lista de nombres de archivo para las fuentes que componen una fuente compuesta. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [FontFace](../../groupdocs.metadata.standards.xmp/xmpfont/fontface) { get; set; } | Obtiene o establece el nombre de la fuente. |
| [FontFamily](../../groupdocs.metadata.standards.xmp/xmpfont/fontfamily) { get; set; } | Obtiene o establece el nombre de la familia de fuentes. |
| [FontFileName](../../groupdocs.metadata.standards.xmp/xmpfont/fontfilename) { get; set; } | Obtiene o establece el nombre del archivo de fuente (no una ruta completa). |
| [FontName](../../groupdocs.metadata.standards.xmp/xmpfont/fontname) { get; set; } | Obtiene o establece el nombre PostScript de la fuente. |
| [FontType](../../groupdocs.metadata.standards.xmp/xmpfont/fonttype) { get; set; } | Obtiene o establece el tipo de fuente. |
| [IsComposite](../../groupdocs.metadata.standards.xmp/xmpfont/iscomposite) { get; set; } | Obtiene o establece un valor que indica si la fuente es compuesta. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Obtiene los URI de espacio de nombres que se usan en el[`XmpComplexType`](../xmpcomplextype) instancia. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Obtiene los prefijos de espacio de nombres que se utilizan en el[`XmpComplexType`](../xmpcomplextype) instancia. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Version](../../groupdocs.metadata.standards.xmp/xmpfont/version) { get; set; } | Obtiene o establece la versión de la fuente. |

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

### Ver también

* class [XmpComplexType](../xmpcomplextype)
* espacio de nombres [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
