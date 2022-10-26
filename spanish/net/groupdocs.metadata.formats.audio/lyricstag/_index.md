---
title: LyricsTag
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa los metadatos de Lyrics3 v2.00. Encuentre más información enhttp//id3.org/Lyrics3v2 .
type: docs
weight: 570
url: /es/net/groupdocs.metadata.formats.audio/lyricstag/
---
## LyricsTag class

Representa los metadatos de Lyrics3 v2.00. Encuentre más información enhttp://id3.org/Lyrics3v2 .

```csharp
public sealed class LyricsTag : CustomPackage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LyricsTag](lyricstag)() | Inicializa una nueva instancia del[`LyricsTag`](../lyricstag) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AdditionalInfo](../../groupdocs.metadata.formats.audio/lyricstag/additionalinfo) { get; set; } | Obtiene o establece la información adicional. Este valor está representado por el campo INF. |
| [Album](../../groupdocs.metadata.formats.audio/lyricstag/album) { get; set; } | Obtiene o establece el nombre del álbum. Este valor está representado por el campo EAL. |
| [Artist](../../groupdocs.metadata.formats.audio/lyricstag/artist) { get; set; } | Obtiene o establece el nombre del artista. Este valor está representado por el campo EAR. |
| [Author](../../groupdocs.metadata.formats.audio/lyricstag/author) { get; set; } | Obtiene o establece el autor. Este valor está representado por el campo AUT. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Lyrics](../../groupdocs.metadata.formats.audio/lyricstag/lyrics) { get; set; } | Obtiene o establece la letra. Este valor está representado por el campo LYR. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Track](../../groupdocs.metadata.formats.audio/lyricstag/track) { get; set; } | Obtiene o establece el título de la pista. Este valor está representado por el campo ETT. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Get](../../groupdocs.metadata.formats.audio/lyricstag/get)(string) | Obtiene el valor del campo con el id especificado. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [Remove](../../groupdocs.metadata.formats.audio/lyricstag/remove)(string) | Elimina el campo con el id especificado. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Set](../../groupdocs.metadata.formats.audio/lyricstag/set)(LyricsField) | Agrega o reemplaza el campo Lyrics3 especificado. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [ToList](../../groupdocs.metadata.formats.audio/lyricstag/tolist)() | Crea una lista a partir del paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

Lyrics3 v2.00 usa campos para representar información. Los datos en un campo pueden consistir en caracteres ASCII en el rango de 01 a 254 según el estándar. Como el mapa de caracteres ASCII solo se define de 00 a 128 ISO-8859- 1 podría suponerse. Los campos numéricos tienen 5 o 6 caracteres, según la ubicación, y se rellenan con ceros.

**Aprende más**

* [Manejo de la etiqueta Letras](https://docs.groupdocs.com/display/metadatanet/Handling+the+Lyrics+tag)

### Ejemplos

Este ejemplo de código muestra cómo leer la etiqueta Letras de un archivo MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithLyrics))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.Lyrics3V2 != null)
    {
        Console.WriteLine(root.Lyrics3V2.Lyrics);
        Console.WriteLine(root.Lyrics3V2.Album);
        Console.WriteLine(root.Lyrics3V2.Artist);
        Console.WriteLine(root.Lyrics3V2.Track);

        // ...

        // Alternativamente, puede recorrer una lista completa de campos de etiqueta
        foreach (var field in root.Lyrics3V2.ToList())
        {
            Console.WriteLine("{0} = {1}", field.ID, field.Data);
        }
    }
}
```

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
