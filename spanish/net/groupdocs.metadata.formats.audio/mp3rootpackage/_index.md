---
title: MP3RootPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa el paquete raíz que permite trabajar con metadatos en un audio MP3.
type: docs
weight: 580
url: /es/net/groupdocs.metadata.formats.audio/mp3rootpackage/
---
## MP3RootPackage class

Representa el paquete raíz que permite trabajar con metadatos en un audio MP3.

```csharp
public class MP3RootPackage : RootMetadataPackage, IXmp
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ApeV2](../../groupdocs.metadata.formats.audio/mp3rootpackage/apev2) { get; } | Obtiene los metadatos de APE v2. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Obtiene el paquete de metadatos del tipo de archivo. |
| [ID3V1](../../groupdocs.metadata.formats.audio/mp3rootpackage/id3v1) { get; set; } | Obtiene o establece la etiqueta de metadatos ID3v1. Encuentre más información en[http://id3.org/ID3v1](http://id3.org/ID3v1) . |
| [ID3V2](../../groupdocs.metadata.formats.audio/mp3rootpackage/id3v2) { get; set; } | Obtiene o establece la etiqueta de metadatos ID3v2. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Lyrics3V2](../../groupdocs.metadata.formats.audio/mp3rootpackage/lyrics3v2) { get; set; } | Obtiene o establece la etiqueta de metadatos Lyrics3v2. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [MpegAudioPackage](../../groupdocs.metadata.formats.audio/mp3rootpackage/mpegaudiopackage) { get; } | Obtiene el paquete de metadatos de audio MPEG. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [XmpPackage](../../groupdocs.metadata.formats.audio/mp3rootpackage/xmppackage) { get; set; } | Obtiene o establece el paquete de metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [RemoveApeV2](../../groupdocs.metadata.formats.audio/mp3rootpackage/removeapev2)() | Elimina la etiqueta de audio APEv2. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| override [Sanitize](../../groupdocs.metadata.formats.audio/mp3rootpackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos MP3](https://docs.groupdocs.com/display/metadatanet/Working+with+MP3+metadata)
* [Trabajar con metadatos XMP](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Ver también

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* espacio de nombres [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
