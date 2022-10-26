---
title: MatroskaAudioTrack
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa metadatos de audio en un video Matroska.
type: docs
weight: 2430
url: /es/net/groupdocs.metadata.formats.video/matroskaaudiotrack/
---
## MatroskaAudioTrack class

Representa metadatos de audio en un video Matroska.

```csharp
public class MatroskaAudioTrack : MatroskaTrack
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BitDepth](../../groupdocs.metadata.formats.video/matroskaaudiotrack/bitdepth) { get; } | Obtiene los bits por muestra, mayormente usados para PCM. |
| [Channels](../../groupdocs.metadata.formats.video/matroskaaudiotrack/channels) { get; } | Obtiene el número de canales en la pista. |
| [CodecID](../../groupdocs.metadata.formats.video/matroskatrack/codecid) { get; } | Obtiene un ID correspondiente al códec. |
| [CodecName](../../groupdocs.metadata.formats.video/matroskatrack/codecname) { get; } | Obtiene una cadena legible por humanos que especifica el códec. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DefaultDuration](../../groupdocs.metadata.formats.video/matroskatrack/defaultduration) { get; } | Obtiene el número de nanosegundos (no escalado mediante[`TimecodeScale`](../matroskasegment/timecodescale) ) por cuadro. |
| [FlagEnabled](../../groupdocs.metadata.formats.video/matroskatrack/flagenabled) { get; } | Obtiene el indicador habilitado, verdadero si la pista es utilizable. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Language](../../groupdocs.metadata.formats.video/matroskatrack/language) { get; } | Obtiene el idioma de la pista en el formulario de idiomas Matroska. Este elemento DEBE ignorarse si el[`LanguageIetf`](../matroskatrack/languageietf) El elemento se utiliza en el mismo TrackEntry. |
| [LanguageIetf](../../groupdocs.metadata.formats.video/matroskatrack/languageietf) { get; } | Obtiene el idioma de la pista de acuerdo con BCP 47 y mediante el registro de subetiquetas de idioma de la IANA. Si se usa este Elemento, entonces cualquier[`Language`](../matroskatrack/language) Los elementos utilizados en el mismo TrackEntry DEBEN ser ignorados. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [Name](../../groupdocs.metadata.formats.video/matroskatrack/name) { get; } | Obtiene el nombre de la pista legible por humanos. |
| [OutputSamplingFrequency](../../groupdocs.metadata.formats.video/matroskaaudiotrack/outputsamplingfrequency) { get; } | Obtiene la frecuencia de muestreo de salida real en Hz (utilizada para técnicas SBR). |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [SamplingFrequency](../../groupdocs.metadata.formats.video/matroskaaudiotrack/samplingfrequency) { get; } | Obtiene la frecuencia de muestreo en Hz. |
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
