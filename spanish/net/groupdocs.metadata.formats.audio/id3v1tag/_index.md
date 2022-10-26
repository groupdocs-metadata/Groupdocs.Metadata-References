---
title: ID3V1Tag
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa una etiqueta ID3v1. Encuentre más información enhttps//en.wikipedia.org/wiki/ID3ID3v1https//en.wikipedia.org/wiki/ID3ID3v1 .
type: docs
weight: 410
url: /es/net/groupdocs.metadata.formats.audio/id3v1tag/
---
## ID3V1Tag class

Representa una etiqueta ID3v1. Encuentre más información en[https://en.wikipedia.org/wiki/ID3#ID3v1](https://en.wikipedia.org/wiki/ID3#ID3v1) .

```csharp
public sealed class ID3V1Tag : ID3Tag
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ID3V1Tag](id3v1tag)() | Inicializa una nueva instancia del[`ID3V1Tag`](../id3v1tag) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v1tag/album) { get; set; } | Obtiene o establece el álbum. La longitud máxima es de 30 caracteres. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v1tag/artist) { get; set; } | Obtiene o establece el artista. La longitud máxima es de 30 caracteres. |
| [Comment](../../groupdocs.metadata.formats.audio/id3v1tag/comment) { get; set; } | Obtiene o establece el comentario. La longitud máxima es de 30 caracteres. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [GenreValue](../../groupdocs.metadata.formats.audio/id3v1tag/genrevalue) { get; } | Obtiene o establece el identificador de género. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Title](../../groupdocs.metadata.formats.audio/id3v1tag/title) { get; set; } | Obtiene o establece el título. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v1tag/tracknumber) { get; set; } | Obtiene o establece el número de pista. Presentado en una etiqueta ID3v1.1 solamente. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v1tag/version) { get; } | Obtiene la versión ID3. Puede ser ID3 o ID3v1.1 |
| [Year](../../groupdocs.metadata.formats.audio/id3v1tag/year) { get; set; } | Obtiene o establece el año. La longitud máxima es de 4 caracteres. |

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

La etiqueta ID3(v1) es una pequeña porción de datos adicionales al final de MP3. Encuentre más información en[http://id3.org/ID3v1](http://id3.org/ID3v1) .

**Aprende más**

* [Manejo de la etiqueta ID3v1](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v1+tag)

### Ejemplos

Este ejemplo de código muestra cómo leer la etiqueta ID3v1 en un archivo MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V1))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V1 != null)
    {
        Console.WriteLine(root.ID3V1.Album);
        Console.WriteLine(root.ID3V1.Artist);
        Console.WriteLine(root.ID3V1.Title);
        Console.WriteLine(root.ID3V1.Version);
        Console.WriteLine(root.ID3V1.Comment);

        // ...
    }
}
```

### Ver también

* class [ID3Tag](../id3tag)
* espacio de nombres [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
