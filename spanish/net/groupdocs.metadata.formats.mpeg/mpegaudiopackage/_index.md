---
title: MpegAudioPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa metadatos de audio MPEG.
type: docs
weight: 2150
url: /es/net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/
---
## MpegAudioPackage class

Representa metadatos de audio MPEG.

```csharp
public sealed class MpegAudioPackage : CustomPackage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MpegAudioPackage](mpegaudiopackage)() | Inicializa una nueva instancia del[`MpegAudioPackage`](../mpegaudiopackage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bitrate](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/bitrate) { get; } | Obtiene la tasa de bits. |
| [ChannelMode](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/channelmode) { get; } | Obtiene el modo de canal. |
| [Copyright](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/copyright) { get; } | Obtiene el bit de copyright. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Emphasis](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/emphasis) { get; } | Obtiene el énfasis. |
| [Frequency](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/frequency) { get; } | Obtiene la frecuencia. |
| [HeaderPosition](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/headerposition) { get; } | Obtiene el desplazamiento del encabezado. |
| [IsOriginal](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/isoriginal) { get; } | Obtiene el bit original. |
| [IsProtected](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/isprotected) { get; } | Obtiene`verdadero` si está protegido. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Layer](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/layer) { get; } | Obtiene la descripción de la capa. Para un audio MP3 es '3'. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [ModeExtensionBits](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/modeextensionbits) { get; } | Obtiene los bits de extensión de modo. |
| [MpegAudioVersion](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/mpegaudioversion) { get; } | Obtiene la versión de audio MPEG. Puede ser MPEG-1, MPEG-2, etc. |
| [PaddingBit](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/paddingbit) { get; } | Obtiene el bit de relleno. |
| [PrivateBit](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/privatebit) { get; } | Obtiene un valor que indica si [bit privado]. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |

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

### Ejemplos

Este ejemplo demuestra cómo leer metadatos de audio MPEG de un archivo MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    Console.WriteLine(root.MpegAudioPackage.Bitrate);
    Console.WriteLine(root.MpegAudioPackage.ChannelMode);
    Console.WriteLine(root.MpegAudioPackage.Emphasis);
    Console.WriteLine(root.MpegAudioPackage.Frequency);
    Console.WriteLine(root.MpegAudioPackage.HeaderPosition);
    Console.WriteLine(root.MpegAudioPackage.Layer);

    // ...
}
```

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Mpeg](../../groupdocs.metadata.formats.mpeg)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
