---
title: MatroskaRootPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa el paquete raíz que permite trabajar con metadatos en un video Matroska.
type: docs
weight: 2480
url: /es/net/groupdocs.metadata.formats.video/matroskarootpackage/
---
## MatroskaRootPackage class

Representa el paquete raíz que permite trabajar con metadatos en un video Matroska.

```csharp
public class MatroskaRootPackage : RootMetadataPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Obtiene el paquete de metadatos del tipo de archivo. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MatroskaPackage](../../groupdocs.metadata.formats.video/matroskarootpackage/matroskapackage) { get; } | Obtiene el paquete de metadatos de Matroska. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos en archivos Matroska (MKV)](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### Ejemplos

Este ejemplo demuestra cómo extraer subtítulos de un video MKV.

```csharp
using (Metadata metadata = new Metadata(Constants.MkvWithSubtitles))
{
    var root = metadata.GetRootPackage<MatroskaRootPackage>();

    foreach (var subtitleTrack in root.MatroskaPackage.SubtitleTracks)
    {
        Console.WriteLine(subtitleTrack.LanguageIetf ?? subtitleTrack.Language);
        foreach (MatroskaSubtitle subtitle in subtitleTrack.Subtitles)
        {
            Console.WriteLine("Timecode={0}, Duration={1}", subtitle.Timecode, subtitle.Duration);
            Console.WriteLine(subtitle.Text);
        }
    }
}
```

### Ver también

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
