---
title: ApePackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa un paquete de metadatos de APE v2. Encuentre más información enhttp//wiki.hydrogenaud.io/index.phptitleAPE_keyhttp//wiki.hydrogenaud.io/index.phptitleAPE_key .
type: docs
weight: 380
url: /es/net/groupdocs.metadata.formats.audio/apepackage/
---
## ApePackage class

Representa un paquete de metadatos de APE v2. Encuentre más información en[http://wiki.hydrogenaud.io/index.php?title=APE_key](http://wiki.hydrogenaud.io/index.php?title=APE_key) .

```csharp
public sealed class ApePackage : CustomPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Abstract](../../groupdocs.metadata.formats.audio/apepackage/abstract) { get; } | Obtiene el enlace abstracto. |
| [Album](../../groupdocs.metadata.formats.audio/apepackage/album) { get; } | Obtiene el álbum. |
| [Artist](../../groupdocs.metadata.formats.audio/apepackage/artist) { get; } | Obtiene el artista. |
| [Bibliography](../../groupdocs.metadata.formats.audio/apepackage/bibliography) { get; } | Obtiene la bibliografía. |
| [Comment](../../groupdocs.metadata.formats.audio/apepackage/comment) { get; } | Obtiene el comentario. |
| [Composer](../../groupdocs.metadata.formats.audio/apepackage/composer) { get; } | Obtiene el compositor. |
| [Conductor](../../groupdocs.metadata.formats.audio/apepackage/conductor) { get; } | Obtiene el conductor. |
| [Copyright](../../groupdocs.metadata.formats.audio/apepackage/copyright) { get; } | Obtiene los derechos de autor. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DebutAlbum](../../groupdocs.metadata.formats.audio/apepackage/debutalbum) { get; } | Obtiene el álbum debut. |
| [File](../../groupdocs.metadata.formats.audio/apepackage/file) { get; } | Obtiene el archivo. |
| [Genre](../../groupdocs.metadata.formats.audio/apepackage/genre) { get; } | Obtiene el género. |
| [Isbn](../../groupdocs.metadata.formats.audio/apepackage/isbn) { get; } | Obtiene el número ISBN con dígito de control. Ver más: https://en.wikipedia.org/wiki/International_Standard_Book_Number. |
| [Isrc](../../groupdocs.metadata.formats.audio/apepackage/isrc) { get; } | Obtiene el Número de registro estándar internacional. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Language](../../groupdocs.metadata.formats.audio/apepackage/language) { get; } | Obtiene el idioma. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [PublicationRight](../../groupdocs.metadata.formats.audio/apepackage/publicationright) { get; } | Acierta la publicación. |
| [Publisher](../../groupdocs.metadata.formats.audio/apepackage/publisher) { get; } | Obtiene el editor. |
| [RecordLocation](../../groupdocs.metadata.formats.audio/apepackage/recordlocation) { get; } | Obtiene la ubicación del registro. |
| [Subtitle](../../groupdocs.metadata.formats.audio/apepackage/subtitle) { get; } | Obtiene el subtítulo. |
| [Title](../../groupdocs.metadata.formats.audio/apepackage/title) { get; } | Obtiene el título. |
| [Track](../../groupdocs.metadata.formats.audio/apepackage/track) { get; } | Obtiene el número de pista. |

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

* [Manejo de la etiqueta APEv2](https://docs.groupdocs.com/display/metadatanet/Handling+the+APEv2+tag)

### Ejemplos

Este ejemplo demuestra cómo leer la etiqueta APEv2 en un archivo MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithApe))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ApeV2 != null)
    {
        Console.WriteLine(root.ApeV2.Album);
        Console.WriteLine(root.ApeV2.Title);
        Console.WriteLine(root.ApeV2.Artist);
        Console.WriteLine(root.ApeV2.Composer);
        Console.WriteLine(root.ApeV2.Copyright);
        Console.WriteLine(root.ApeV2.Genre);
        Console.WriteLine(root.ApeV2.Language);

        // ...
    }
}
```

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
