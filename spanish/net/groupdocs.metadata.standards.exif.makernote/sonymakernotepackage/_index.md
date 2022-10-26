---
title: SonyMakerNotePackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa los metadatos de SONY MakerNote.
type: docs
weight: 2860
url: /es/net/groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/
---
## SonyMakerNotePackage class

Representa los metadatos de SONY MakerNote.

```csharp
public sealed class SonyMakerNotePackage : MakerNotePackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AFIlluminator](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/afilluminator) { get; } | Obtiene el tipo de iluminador AF. |
| [Brightness](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/brightness) { get; } | Obtiene el brillo. |
| [ColorMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/colormode) { get; } | Obtiene el modo de color. |
| [ColorTemperature](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/colortemperature) { get; } | Obtiene la temperatura de color. |
| [Contrast](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/contrast) { get; } | Obtiene el contraste. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [CreativeStyle](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/creativestyle) { get; } | Obtiene el estilo creativo. |
| [ExposureMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/exposuremode) { get; } | Obtiene el modo de exposición. |
| [FlashLevel](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/flashlevel) { get; } | Obtiene el nivel de flash. |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/focusmode) { get; } | Obtiene el modo de enfoque. |
| [Header](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/header) { get; } | Obtiene el encabezado de MakerNote. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Obtiene la etiqueta TIFF con el id especificado. (2 indexers) |
| [JpegQuality](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/jpegquality) { get; } | Obtiene la calidad JPEG. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Macro](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/macro) { get; } | Obtiene la macro. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [MultiBurstImageHeight](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/multiburstimageheight) { get; } | Obtiene la altura de la imagen de ráfaga múltiple. |
| [MultiBurstImageWidth](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/multiburstimagewidth) { get; } | Obtiene el ancho de la imagen de ráfaga múltiple. |
| [MultiBurstMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/multiburstmode) { get; } | Obtiene un valor que indica si el modo de ráfaga múltiple está activado. |
| [PictureEffect](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/pictureeffect) { get; } | Obtiene el efecto de imagen. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Quality](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/quality) { get; } | Obtiene la calidad de imagen. |
| [Rating](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/rating) { get; } | Obtiene la calificación. |
| [ReleaseMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/releasemode) { get; } | Obtiene el modo de lanzamiento. |
| [Saturation](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/saturation) { get; } | Obtiene la saturación. |
| [Sharpness](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/sharpness) { get; } | Obtiene la nitidez. |
| [SoftSkinEffect](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/softskineffect) { get; } | Consigue el efecto piel suave. |
| [SonyModelID](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/sonymodelid) { get; } | Obtiene el identificador del modelo de Sony. |
| [Teleconverter](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/teleconverter) { get; } | Obtiene el tipo de teleconversor. |
| [WhiteBalance](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/whitebalance) { get; } | Obtiene el balance de blancos. |

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
