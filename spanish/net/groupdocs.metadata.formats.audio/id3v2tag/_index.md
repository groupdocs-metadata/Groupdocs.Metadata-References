---
title: ID3V2Tag
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa una etiqueta ID3v2. Encuentre más información enhttps//en.wikipedia.org/wiki/ID3ID3v2https//en.wikipedia.org/wiki/ID3ID3v2 .
type: docs
weight: 490
url: /es/net/groupdocs.metadata.formats.audio/id3v2tag/
---
## ID3V2Tag class

Representa una etiqueta ID3v2. Encuentre más información en[https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2) .

```csharp
public sealed class ID3V2Tag : ID3Tag
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ID3V2Tag](id3v2tag)() | Inicializa una nueva instancia del[`ID3V2Tag`](../id3v2tag) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v2tag/album) { get; set; } | Obtiene o establece el título del álbum/película/programa. Este valor está representado por el cuadro TALB. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v2tag/artist) { get; set; } | Obtiene o establece el(los) artista(s) principal(es)/intérprete(s) principal(es)/solista(s)/grupo de interpretación. Este valor está representado por el cuadro TPE1. |
| [AttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/attachedpictures) { get; set; } | Obtiene o establece las imágenes adjuntas directamente relacionadas con el archivo de audio. Este valor está representado por el marco APIC. |
| [Band](../../groupdocs.metadata.formats.audio/id3v2tag/band) { get; set; } | Obtiene o establece la Banda/Orquesta/Acompañamiento. Este valor está representado por el marco TPE2. |
| [BitsPerMinute](../../groupdocs.metadata.formats.audio/id3v2tag/bitsperminute) { get; set; } | Obtiene o establece el número de pulsaciones por minuto en la parte principal del audio. Este valor está representado por el marco TBPM. |
| [Comments](../../groupdocs.metadata.formats.audio/id3v2tag/comments) { get; set; } | Obtiene o establece los comentarios del usuario. Este valor está representado por el marco COMM. El marco está diseñado para cualquier tipo de información de texto completo que no cabe en ningún otro marco. |
| [Composers](../../groupdocs.metadata.formats.audio/id3v2tag/composers) { get; set; } | Obtiene o establece los compositores. Los nombres se separan con el carácter "/". Este valor está representado por el marco TCOM. |
| [ContentType](../../groupdocs.metadata.formats.audio/id3v2tag/contenttype) { get; set; } | Obtiene o establece el tipo de contenido. Este valor está representado por el marco TCON. |
| [Copyright](../../groupdocs.metadata.formats.audio/id3v2tag/copyright) { get; set; } | Obtiene o establece el mensaje de copyright. Este valor está representado por el marco TCOP. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Date](../../groupdocs.metadata.formats.audio/id3v2tag/date) { get; set; } | Obtiene o establece una cadena numérica en formato DDMM que contiene la fecha de la grabación. Este campo siempre tiene cuatro caracteres. Este valor está representado por el marco TDAT. |
| [EncodedBy](../../groupdocs.metadata.formats.audio/id3v2tag/encodedby) { get; set; } | Obtiene o establece el nombre de la persona u organización que codificó el archivo de audio. Este valor está representado por el cuadro TENC. |
| [Isrc](../../groupdocs.metadata.formats.audio/id3v2tag/isrc) { get; set; } | Obtiene o establece el Código de grabación estándar internacional (ISRC) (12 caracteres). Este valor está representado por el marco TSRC. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [LengthInMilliseconds](../../groupdocs.metadata.formats.audio/id3v2tag/lengthinmilliseconds) { get; set; } | Obtiene o establece la duración del archivo de audio en milisegundos, representada como una cadena numérica. Este valor está representado por el marco TLEN. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [MusicalKey](../../groupdocs.metadata.formats.audio/id3v2tag/musicalkey) { get; set; } | Obtiene o establece la clave musical en la que comienza el sonido. Este valor está representado por el cuadro TKEY. |
| [OriginalAlbum](../../groupdocs.metadata.formats.audio/id3v2tag/originalalbum) { get; set; } | Obtiene o establece el título original del álbum/película/programa. Este valor está representado por el cuadro TOAL. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Publisher](../../groupdocs.metadata.formats.audio/id3v2tag/publisher) { get; set; } | Obtiene o establece el nombre de la etiqueta o editorial. Este valor está representado por el marco TPUB. |
| [SizeInBytes](../../groupdocs.metadata.formats.audio/id3v2tag/sizeinbytes) { get; set; } | Obtiene o establece el tamaño del archivo de audio en bytes, excluyendo la etiqueta ID3v2, representada como una cadena numérica. Este valor está representado por el marco TSIZ. |
| [SoftwareHardware](../../groupdocs.metadata.formats.audio/id3v2tag/softwarehardware) { get; set; } | Obtiene o establece el codificador de audio usado y su configuración cuando se codificó el archivo. Este valor está representado por el marco TSSE. |
| [Subtitle](../../groupdocs.metadata.formats.audio/id3v2tag/subtitle) { get; set; } | Obtiene o establece el refinamiento de Subtítulo/Descripción. Este valor está representado por el marco TIT3. |
| [TagSize](../../groupdocs.metadata.formats.audio/id3v2tag/tagsize) { get; } | Obtiene el tamaño de la etiqueta. |
| [Time](../../groupdocs.metadata.formats.audio/id3v2tag/time) { get; set; } | Obtiene o establece una cadena numérica en formato HHMM que contiene la hora de la grabación. Este campo siempre tiene cuatro caracteres. Este valor está representado por el marco TIME. |
| [Title](../../groupdocs.metadata.formats.audio/id3v2tag/title) { get; set; } | Obtiene o establece el Título/Nombre de la canción/Descripción del contenido. Este valor está representado por el cuadro TIT2. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v2tag/tracknumber) { get; set; } | Obtiene o establece una cadena numérica que contiene el número de orden del archivo de audio en su grabación original. Este valor está representado por el cuadro TRCK. |
| [TrackPlayCounter](../../groupdocs.metadata.formats.audio/id3v2tag/trackplaycounter) { get; } | Obtiene el número de veces que se ha reproducido el archivo. Este valor está representado por el marco PCNT. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v2tag/version) { get; } | Obtiene la versión ID3. |
| [Year](../../groupdocs.metadata.formats.audio/id3v2tag/year) { get; set; } | Obtiene o establece una cadena numérica con un año de la grabación. Este marco siempre tiene cuatro caracteres (hasta el año 10000). Este valor está representado por el marco TYER. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../groupdocs.metadata.formats.audio/id3v2tag/add)(ID3V2TagFrame) | Agrega un marco a la etiqueta. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Clear](../../groupdocs.metadata.formats.audio/id3v2tag/clear)(string) | Elimina todos los fotogramas con el id especificado. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Get](../../groupdocs.metadata.formats.audio/id3v2tag/get)(string) | Obtiene una matriz de fotogramas con el id especificado. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [Remove](../../groupdocs.metadata.formats.audio/id3v2tag/remove)(ID3V2TagFrame) | Elimina el marco especificado de la etiqueta. |
| [RemoveAttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/removeattachedpictures)() | Elimina todas las imágenes adjuntas almacenadas en marcos APIC. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Set](../../groupdocs.metadata.formats.audio/id3v2tag/set)(ID3V2TagFrame) | Elimina todos los marcos que tengan el mismo id que el especificado y agrega el nuevo marco a la etiqueta. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [ToList](../../groupdocs.metadata.formats.audio/id3v2tag/tolist)() | Crea una lista a partir del paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Manejo de la etiqueta ID3v2](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Ejemplos

Este ejemplo muestra cómo leer la etiqueta ID3v2 en un archivo MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V2 != null)
    {
        Console.WriteLine(root.ID3V2.Album);
        Console.WriteLine(root.ID3V2.Artist);
        Console.WriteLine(root.ID3V2.Band);
        Console.WriteLine(root.ID3V2.Title);
        Console.WriteLine(root.ID3V2.Composers);
        Console.WriteLine(root.ID3V2.Copyright);
        Console.WriteLine(root.ID3V2.Publisher);
        Console.WriteLine(root.ID3V2.OriginalAlbum);
        Console.WriteLine(root.ID3V2.MusicalKey);

        if (root.ID3V2.AttachedPictures != null)
        {
            foreach (var attachedPicture in root.ID3V2.AttachedPictures)
            {
                Console.WriteLine(attachedPicture.AttachedPictureType);
                Console.WriteLine(attachedPicture.MimeType);
                Console.WriteLine(attachedPicture.Description);

                // ...
            }
        }

        // ...
    }
}
```

### Ver también

* class [ID3Tag](../id3tag)
* espacio de nombres [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
