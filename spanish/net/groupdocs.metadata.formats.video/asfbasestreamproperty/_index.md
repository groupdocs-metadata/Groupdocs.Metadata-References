---
title: AsfBaseStreamProperty
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa los metadatos de propiedad de flujo base en el contenedor de medios ASF.
type: docs
weight: 2250
url: /es/net/groupdocs.metadata.formats.video/asfbasestreamproperty/
---
## AsfBaseStreamProperty class

Representa los metadatos de propiedad de flujo base en el contenedor de medios ASF.

```csharp
public abstract class AsfBaseStreamProperty : CustomPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternateBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/alternatebitrate) { get; } | Obtiene la tasa de fuga RAlt, en bits por segundo, de un depósito con fugas que contiene la porción de datos de la secuencia sin desbordarse, excluyendo toda la sobrecarga del paquete de datos ASF. |
| [AverageBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagebitrate) { get; } | Obtiene la tasa de bits promedio. |
| [AverageTimePerFrame](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagetimeperframe) { get; } | Obtiene la duración promedio, medida en unidades de 100 nanosegundos, de cada cuadro. |
| [Bitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/bitrate) { get; } | Obtiene la tasa de fuga R, en bits por segundo, de un depósito con fugas que contiene la porción de datos de la secuencia sin desbordarse, excluyendo toda la sobrecarga del paquete de datos ASF. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [EndTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/endtime) { get; } | Obtiene el tiempo de presentación del último objeto más la duración de la reproducción, lo que indica dónde termina este flujo de medios digitales dentro del contexto de la línea de tiempo del archivo ASF como un todo. |
| [Flags](../../groupdocs.metadata.formats.video/asfbasestreamproperty/flags) { get; } | Obtiene las banderas. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Language](../../groupdocs.metadata.formats.video/asfbasestreamproperty/language) { get; } | Obtiene el idioma de la transmisión. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [StartTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/starttime) { get; } | Obtiene el tiempo de presentación del primer objeto, indicando dónde comienza este flujo de medios digitales dentro del contexto de la línea de tiempo del archivo ASF como un todo. |
| [StreamNumber](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamnumber) { get; } | Obtiene el número de este stream. |
| [StreamType](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamtype) { get; } | Obtiene el tipo de este flujo. |

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

* [Trabajar con metadatos en archivos ASF](https://docs.groupdocs.com/display/metadatanet/Working+with+Metadata+in+ASF+Files)

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
