---
title: MatroskaSegment
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa un elemento SEGMENTINFO que contiene información general sobre el SEGMENTO en un video Matroska.
type: docs
weight: 2490
url: /es/net/groupdocs.metadata.formats.video/matroskasegment/
---
## MatroskaSegment class

Representa un elemento SEGMENTINFO que contiene información general sobre el SEGMENTO en un video Matroska.

```csharp
public class MatroskaSegment : MatroskaBasePackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DateUtc](../../groupdocs.metadata.formats.video/matroskasegment/dateutc) { get; } | Obtiene la fecha y la hora en que la biblioteca o la aplicación muxing creó el segmento. |
| [Duration](../../groupdocs.metadata.formats.video/matroskasegment/duration) { get; } | Obtiene la duración del SEGMENTO. Consulte[`TimecodeScale`](./timecodescale) para más información. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [MuxingApp](../../groupdocs.metadata.formats.video/matroskasegment/muxingapp) { get; } | Obtiene el nombre completo de la aplicación o biblioteca seguido del número de versión. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [ScaledDuration](../../groupdocs.metadata.formats.video/matroskasegment/scaledduration) { get; } | Obtiene la duración escalada del SEGMENTO. |
| [SegmentFilename](../../groupdocs.metadata.formats.video/matroskasegment/segmentfilename) { get; } | Obtiene el nombre de archivo correspondiente a este Segmento. |
| [SegmentUid](../../groupdocs.metadata.formats.video/matroskasegment/segmentuid) { get; } | Obtiene el número único de 128 bits que identifica un SEGMENTO. Obviamente, un archivo solo puede ser referenciado por otro archivo si está presente un SEGMENTUID; sin embargo, la reproducción es posible sin ese UID. |
| [TimecodeScale](../../groupdocs.metadata.formats.video/matroskasegment/timecodescale) { get; } | Obtiene el valor de escala del código de tiempo. Cada código de tiempo escalado en un archivo MATROSKA se multiplica por TIMECODESCALE para obtener el código de tiempo en nanosegundos. ¡Tenga en cuenta que no todos los códigos de tiempo están escalados! |
| [Title](../../groupdocs.metadata.formats.video/matroskasegment/title) { get; } | Obtiene el nombre general del Segmento. |
| [WritingApp](../../groupdocs.metadata.formats.video/matroskasegment/writingapp) { get; } | Obtiene el nombre completo de la aplicación seguido del número de versión. |

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

* class [MatroskaBasePackage](../matroskabasepackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
