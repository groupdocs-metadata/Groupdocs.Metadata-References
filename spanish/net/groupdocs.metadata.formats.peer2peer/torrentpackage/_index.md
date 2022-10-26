---
title: TorrentPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa los metadatos del archivo descriptor de torrent. Encuentre más información enhttps//en.wikipedia.org/wiki/Torrent_filehttps//en.wikipedia.org/wiki/Torrent_file .
type: docs
weight: 2190
url: /es/net/groupdocs.metadata.formats.peer2peer/torrentpackage/
---
## TorrentPackage class

Representa los metadatos del archivo descriptor de torrent. Encuentre más información en[https://en.wikipedia.org/wiki/Torrent_file](https://en.wikipedia.org/wiki/Torrent_file) .

```csharp
public sealed class TorrentPackage : CustomPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Announce](../../groupdocs.metadata.formats.peer2peer/torrentpackage/announce) { get; set; } | Obtiene o establece la URL del rastreador. |
| [Comment](../../groupdocs.metadata.formats.peer2peer/torrentpackage/comment) { get; set; } | Obtiene o establece el comentario del autor. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [CreatedBy](../../groupdocs.metadata.formats.peer2peer/torrentpackage/createdby) { get; set; } | Obtiene o establece el nombre y la versión del programa utilizado para crear el torrent. |
| [CreationDate](../../groupdocs.metadata.formats.peer2peer/torrentpackage/creationdate) { get; set; } | Obtiene o establece la fecha de creación del torrente. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PieceLength](../../groupdocs.metadata.formats.peer2peer/torrentpackage/piecelength) { get; } | Obtiene el número de bytes en cada pieza. Para obtener más información, consulte . |
| [Pieces](../../groupdocs.metadata.formats.peer2peer/torrentpackage/pieces) { get; } | Obtiene una matriz de bytes que consta de la concatenación de todos los valores hash SHA1 de 20 bytes, uno por pieza. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [SharedFiles](../../groupdocs.metadata.formats.peer2peer/torrentpackage/sharedfiles) { get; } | Obtiene una matriz que contiene entradas de información de archivos compartidos. |

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

* [Trabajando con archivos TORRENT](https://docs.groupdocs.com/display/metadatanet/Working+with+TORRENT+files)

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Peer2Peer](../../groupdocs.metadata.formats.peer2peer)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
