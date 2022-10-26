---
title: MatroskaVideoTrack
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa metadatos de video en un video Matroska.
type: docs
weight: 2610
url: /es/net/groupdocs.metadata.formats.video/matroskavideotrack/
---
## MatroskaVideoTrack class

Representa metadatos de video en un video Matroska.

```csharp
public class MatroskaVideoTrack : MatroskaTrack
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlphaMode](../../groupdocs.metadata.formats.video/matroskavideotrack/alphamode) { get; } | Obtiene el modo de video alfa. La presencia de este elemento indica que el elemento BlockAdditional podría contener datos alfa. |
| [CodecID](../../groupdocs.metadata.formats.video/matroskatrack/codecid) { get; } | Obtiene un ID correspondiente al códec. |
| [CodecName](../../groupdocs.metadata.formats.video/matroskatrack/codecname) { get; } | Obtiene una cadena legible por humanos que especifica el códec. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DefaultDuration](../../groupdocs.metadata.formats.video/matroskatrack/defaultduration) { get; } | Obtiene el número de nanosegundos (no escalado mediante[`TimecodeScale`](../matroskasegment/timecodescale) ) por cuadro. |
| [DisplayHeight](../../groupdocs.metadata.formats.video/matroskavideotrack/displayheight) { get; } | Obtiene la altura de los cuadros de video para mostrar. Se aplica al cuadro de video después de recortar (PixelCrop* Elements). |
| [DisplayUnit](../../groupdocs.metadata.formats.video/matroskavideotrack/displayunit) { get; } | Obtiene el cómo[`DisplayWidth`](./displaywidth) y[`DisplayHeight`](./displayheight) se interpretan. |
| [DisplayWidth](../../groupdocs.metadata.formats.video/matroskavideotrack/displaywidth) { get; } | Obtiene el ancho de los cuadros de video para mostrar. Se aplica al cuadro de video después de recortar (PixelCrop* Elements). |
| [FieldOrder](../../groupdocs.metadata.formats.video/matroskavideotrack/fieldorder) { get; } | Obtiene declarar el ordenamiento de los campos del video. Si FlagInterlaced no se establece en 1, este elemento DEBE ignorarse. |
| [FlagEnabled](../../groupdocs.metadata.formats.video/matroskatrack/flagenabled) { get; } | Obtiene el indicador habilitado, verdadero si la pista es utilizable. |
| [FlagInterlaced](../../groupdocs.metadata.formats.video/matroskavideotrack/flaginterlaced) { get; } | Obtiene un indicador para declarar si se sabe que el video es progresivo o entrelazado y, si corresponde, para declarar detalles sobre el entrelazamiento. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Language](../../groupdocs.metadata.formats.video/matroskatrack/language) { get; } | Obtiene el idioma de la pista en el formulario de idiomas Matroska. Este elemento DEBE ignorarse si el[`LanguageIetf`](../matroskatrack/languageietf) El elemento se utiliza en el mismo TrackEntry. |
| [LanguageIetf](../../groupdocs.metadata.formats.video/matroskatrack/languageietf) { get; } | Obtiene el idioma de la pista de acuerdo con BCP 47 y mediante el registro de subetiquetas de idioma de la IANA. Si se usa este Elemento, entonces cualquier[`Language`](../matroskatrack/language) Los elementos utilizados en el mismo TrackEntry DEBEN ser ignorados. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [Name](../../groupdocs.metadata.formats.video/matroskatrack/name) { get; } | Obtiene el nombre de la pista legible por humanos. |
| [PixelCropBottom](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropbottom) { get; } | Obtiene la cantidad de píxeles de video que se eliminarán en la parte inferior de la imagen. |
| [PixelCropLeft](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropleft) { get; } | Obtiene la cantidad de píxeles de video que se eliminarán a la izquierda de la imagen. |
| [PixelCropRight](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropright) { get; } | Obtiene la cantidad de píxeles de video que se eliminarán a la derecha de la imagen. |
| [PixelCropTop](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcroptop) { get; } | Obtiene la cantidad de píxeles de video que se eliminarán en la parte superior de la imagen. |
| [PixelHeight](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelheight) { get; } | Obtiene la altura de los cuadros de video codificados en píxeles. |
| [PixelWidth](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelwidth) { get; } | Obtiene el ancho de los cuadros de video codificados en píxeles. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [StereoMode](../../groupdocs.metadata.formats.video/matroskavideotrack/stereomode) { get; } | Obtiene el modo de video estéreo-3D. |
| [TrackNumber](../../groupdocs.metadata.formats.video/matroskatrack/tracknumber) { get; } | Obtiene el número de pista tal como se usa en el encabezado del bloque. No se recomienda usar más de 127 pistas, aunque el diseño permite un número ilimitado. |
| [TrackType](../../groupdocs.metadata.formats.video/matroskatrack/tracktype) { get; } | Obtiene el tipo de pista. |
| [TrackUid](../../groupdocs.metadata.formats.video/matroskatrack/trackuid) { get; } | Obtiene la identificación única para identificar la pista. Esto DEBE mantenerse igual cuando se hace una copia de transmisión directa de la pista a otro archivo. |

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

* [Trabajar con metadatos en archivos Matroska (MKV)](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### Ver también

* class [MatroskaTrack](../matroskatrack)
* espacio de nombres [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
