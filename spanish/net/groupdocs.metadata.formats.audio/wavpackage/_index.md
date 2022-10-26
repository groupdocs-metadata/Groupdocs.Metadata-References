---
title: WavPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa un paquete de metadatos nativos en un archivo de audio WAV.
type: docs
weight: 590
url: /es/net/groupdocs.metadata.formats.audio/wavpackage/
---
## WavPackage class

Representa un paquete de metadatos nativos en un archivo de audio WAV.

```csharp
public sealed class WavPackage : CustomPackage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WavPackage](wavpackage)() | Inicializa una nueva instancia del[`WavPackage`](../wavpackage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AudioFormat](../../groupdocs.metadata.formats.audio/wavpackage/audioformat) { get; } | Obtiene el formato de audio. PCM = 1 (es decir, cuantización lineal). Los valores distintos de 1 indican algún tipo de compresión. |
| [BitsPerSample](../../groupdocs.metadata.formats.audio/wavpackage/bitspersample) { get; } | Obtiene los bits por valor de muestra. |
| [BlockAlign](../../groupdocs.metadata.formats.audio/wavpackage/blockalign) { get; } | Obtiene la alineación del bloque. |
| [ByteRate](../../groupdocs.metadata.formats.audio/wavpackage/byterate) { get; } | Obtiene la tasa de bytes. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [NumberOfChannels](../../groupdocs.metadata.formats.audio/wavpackage/numberofchannels) { get; } | Obtiene el número de canales. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [SampleRate](../../groupdocs.metadata.formats.audio/wavpackage/samplerate) { get; } | Obtiene la frecuencia de muestreo. |

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

* [Manejo de metadatos en archivos WAV](https://docs.groupdocs.com/display/metadatanet/Handling+metadata+in+WAV+files)

### Ejemplos

Este ejemplo de código muestra cómo extraer información técnica de audio de un archivo WAV.

```csharp
using (Metadata metadata = new Metadata(Constants.InputWav))
{
    var root = metadata.GetRootPackage<WavRootPackage>();
    if (root.WavPackage != null)
    {
        Console.WriteLine(root.WavPackage.AudioFormat);
        Console.WriteLine(root.WavPackage.BitsPerSample);
        Console.WriteLine(root.WavPackage.BlockAlign);
        Console.WriteLine(root.WavPackage.ByteRate);
        Console.WriteLine(root.WavPackage.NumberOfChannels);
        Console.WriteLine(root.WavPackage.SampleRate);
    }
}
```

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
