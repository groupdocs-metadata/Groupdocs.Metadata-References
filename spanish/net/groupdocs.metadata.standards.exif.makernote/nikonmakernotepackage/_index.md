---
title: NikonMakerNotePackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa los metadatos de NIKON MakerNote.
type: docs
weight: 2840
url: /es/net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/
---
## NikonMakerNotePackage class

Representa los metadatos de NIKON MakerNote.

```csharp
public sealed class NikonMakerNotePackage : MakerNotePackage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [NikonMakerNotePackage](nikonmakernotepackage)(TiffTag[]) | Inicializa una nueva instancia del[`NikonMakerNotePackage`](../nikonmakernotepackage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ColorMode](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/colormode) { get; } | Obtiene el modo de color. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [FlashSetting](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/flashsetting) { get; } | Obtiene la configuración de flash. |
| [FlashType](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/flashtype) { get; } | Obtiene el tipo de flash. |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/focusmode) { get; } | Obtiene el modo de enfoque. |
| [Iso](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/iso) { get; } | Obtiene la iso. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Obtiene la etiqueta TIFF con el id especificado. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MakerNoteVersion](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/makernoteversion) { get; } | Obtiene la versión de MakerNote. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Quality](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/quality) { get; } | Obtiene la cadena de calidad. |
| [Sharpness](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/sharpness) { get; } | Obtiene la nitidez. |
| [WhiteBalance](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/whitebalance) { get; } | Obtiene el balance de blancos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Elimina todas las etiquetas TIFF almacenadas en el paquete. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Elimina la propiedad con el id especificado. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Agrega o reemplaza la etiqueta especificada. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Crea una lista a partir del paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Ver también

* class [MakerNotePackage](../makernotepackage)
* espacio de nombres [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
