---
title: PngInternationalTextChunk
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa datos textuales internacionales extraídos de una imagen PNG.
type: docs
weight: 1840
url: /es/net/groupdocs.metadata.formats.image/pnginternationaltextchunk/
---
## PngInternationalTextChunk class

Representa datos textuales internacionales extraídos de una imagen PNG.

```csharp
public class PngInternationalTextChunk : PngCompressedTextChunk
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CompressionMethod](../../groupdocs.metadata.formats.image/pngcompressedtextchunk/compressionmethod) { get; } | Obtiene el algoritmo utilizado para comprimir los datos del fragmento. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [IsCompressed](../../groupdocs.metadata.formats.image/pnginternationaltextchunk/iscompressed) { get; } | Obtiene un valor que indica si el fragmento está comprimido. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Keyword](../../groupdocs.metadata.formats.image/pngtextchunk/keyword) { get; } | Obtiene la palabra clave que indica el tipo de información representada por el fragmento. |
| [Language](../../groupdocs.metadata.formats.image/pnginternationaltextchunk/language) { get; } | Obtiene el idioma humano utilizado por la palabra clave traducida y el texto. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Text](../../groupdocs.metadata.formats.image/pngtextchunk/text) { get; } | Obtiene la cadena de texto real representada por el fragmento. |
| [TranslatedKeyword](../../groupdocs.metadata.formats.image/pnginternationaltextchunk/translatedkeyword) { get; } | Obtiene la palabra clave traducida que contiene una traducción de la palabra clave al idioma indicado por la propiedad de idioma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Ver también

* class [PngCompressedTextChunk](../pngcompressedtextchunk)
* espacio de nombres [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->