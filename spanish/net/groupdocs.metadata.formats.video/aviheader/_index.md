---
title: AviHeader
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa la estructura AVIMAINHEADER en un video AVI.
type: docs
weight: 2380
url: /es/net/groupdocs.metadata.formats.video/aviheader/
---
## AviHeader class

Representa la estructura AVIMAINHEADER en un video AVI.

```csharp
public sealed class AviHeader : CustomPackage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [AviHeader](aviheader)() | Inicializa una nueva instancia del[`AviHeader`](../aviheader) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AviHeaderFlags](../../groupdocs.metadata.formats.video/aviheader/aviheaderflags) { get; } | Obtiene una combinación bit a bit de cero o más indicadores AVI. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Height](../../groupdocs.metadata.formats.video/aviheader/height) { get; } | Obtiene la altura del archivo AVI en píxeles. |
| [InitialFrames](../../groupdocs.metadata.formats.video/aviheader/initialframes) { get; } | Obtiene el cuadro inicial para archivos intercalados.  Los archivos no intercalados deben especificar cero. Si está creando archivos intercalados, especifique el número de fotogramas en el archivo antes del fotograma inicial de la secuencia AVI en este miembro. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MaxBytesPerSec](../../groupdocs.metadata.formats.video/aviheader/maxbytespersec) { get; } | Obtiene la velocidad de datos máxima aproximada del archivo.  Este valor indica el número de bytes por segundo que el sistema debe manejar para presentar una secuencia AVI como especificado por los otros parámetros contenidos en el encabezado principal y fragmentos de encabezado de flujo. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [MicroSecPerFrame](../../groupdocs.metadata.formats.video/aviheader/microsecperframe) { get; } | Obtiene el número de microsegundos entre fotogramas. Este valor indica el tiempo total para el archivo. |
| [PaddingGranularity](../../groupdocs.metadata.formats.video/aviheader/paddinggranularity) { get; } | Obtiene la alineación de los datos, en bytes. Rellene los datos a múltiplos de este valor. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Streams](../../groupdocs.metadata.formats.video/aviheader/streams) { get; } | Obtiene el número de transmisiones en el archivo. Por ejemplo, un archivo con audio y video tiene dos flujos. |
| [SuggestedBufferSize](../../groupdocs.metadata.formats.video/aviheader/suggestedbuffersize) { get; } | Obtiene el tamaño de búfer sugerido para leer el archivo.  Por lo general, este tamaño debe ser lo suficientemente grande como para contener la parte más grande del archivo. Si se establece en cero, o si es demasiado pequeño, el software de reproducción tendrá que reasignar memoria durante la reproducción, lo que reducirá el rendimiento. Para un archivo intercalado, el tamaño del búfer debe ser lo suficientemente grande para leer un registro completo, y no solo un fragmento. |
| [TotalFrames](../../groupdocs.metadata.formats.video/aviheader/totalframes) { get; } | Obtiene el número total de cuadros de datos en el archivo. |
| [Width](../../groupdocs.metadata.formats.video/aviheader/width) { get; } | Obtiene el ancho del archivo AVI en píxeles. |

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

* [Trabajar con metadatos en archivos AVI](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files)

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
