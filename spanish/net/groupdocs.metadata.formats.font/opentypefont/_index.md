---
title: OpenTypeFont
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa una única fuente extraída de un archivo.
type: docs
weight: 1460
url: /es/net/groupdocs.metadata.formats.font/opentypefont/
---
## OpenTypeFont class

Representa una única fuente extraída de un archivo.

```csharp
public class OpenTypeFont : CustomPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Created](../../groupdocs.metadata.formats.font/opentypefont/created) { get; } | Obtiene la fecha de creación. |
| [DirectionHint](../../groupdocs.metadata.formats.font/opentypefont/directionhint) { get; } | Obtiene la pista de dirección. |
| [EmbeddingLicensingRights](../../groupdocs.metadata.formats.font/opentypefont/embeddinglicensingrights) { get; } | Obtiene el tipo de derechos de licencia de incrustación. |
| [Flags](../../groupdocs.metadata.formats.font/opentypefont/flags) { get; } | Obtiene las banderas de encabezado. |
| [FontFamilyName](../../groupdocs.metadata.formats.font/opentypefont/fontfamilyname) { get; } | Obtiene el nombre de la familia de fuentes. |
| [FontRevision](../../groupdocs.metadata.formats.font/opentypefont/fontrevision) { get; } | Obtiene la revisión de la fuente. |
| [FontSubfamilyName](../../groupdocs.metadata.formats.font/opentypefont/fontsubfamilyname) { get; } | Obtiene el nombre de la subfamilia de fuentes. |
| [FullFontName](../../groupdocs.metadata.formats.font/opentypefont/fullfontname) { get; } | Obtiene el nombre completo de la fuente. |
| [GlyphBounds](../../groupdocs.metadata.formats.font/opentypefont/glyphbounds) { get; } | Obtiene los límites del glifo. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MajorVersion](../../groupdocs.metadata.formats.font/opentypefont/majorversion) { get; } | Obtiene la versión principal del encabezado. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [MinorVersion](../../groupdocs.metadata.formats.font/opentypefont/minorversion) { get; } | Obtiene la versión secundaria del encabezado. |
| [Modified](../../groupdocs.metadata.formats.font/opentypefont/modified) { get; } | Obtiene la fecha de modificación. |
| [Names](../../groupdocs.metadata.formats.font/opentypefont/names) { get; } | Obtiene los registros de nombre. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [SfntVersion](../../groupdocs.metadata.formats.font/opentypefont/sfntversion) { get; } | Obtiene la cabecera versión SFNT. |
| [Style](../../groupdocs.metadata.formats.font/opentypefont/style) { get; } | Obtiene el estilo de fuente. |
| [TypographicFamily](../../groupdocs.metadata.formats.font/opentypefont/typographicfamily) { get; } | Obtiene la familia tipográfica. |
| [TypographicSubfamily](../../groupdocs.metadata.formats.font/opentypefont/typographicsubfamily) { get; } | Obtiene la subfamilia tipográfica. |
| [Weight](../../groupdocs.metadata.formats.font/opentypefont/weight) { get; } | Obtiene el peso de la fuente. |
| [Width](../../groupdocs.metadata.formats.font/opentypefont/width) { get; } | Obtiene el ancho de fuente. |

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

### Observaciones

**Aprende más**

* [Trabajar con fuentes OpenType](https://docs.groupdocs.com/display/metadatanet/Working+with+OpenType+fonts)

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Font](../../groupdocs.metadata.formats.font)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
