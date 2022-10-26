---
title: ZipFile
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa metadatos asociados con un archivo o directorio archivado.
type: docs
weight: 350
url: /es/net/groupdocs.metadata.formats.archive/zipfile/
---
## ZipFile class

Representa metadatos asociados con un archivo o directorio archivado.

```csharp
public sealed class ZipFile : CustomPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CompressedSize](../../groupdocs.metadata.formats.archive/zipfile/compressedsize) { get; } | Obtiene el tamaño comprimido en bytes. |
| [CompressionMethod](../../groupdocs.metadata.formats.archive/zipfile/compressionmethod) { get; } | Obtiene el método de compresión. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Flags](../../groupdocs.metadata.formats.archive/zipfile/flags) { get; } | Obtiene las banderas de entrada ZIP. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [ModificationDateTime](../../groupdocs.metadata.formats.archive/zipfile/modificationdatetime) { get; } | Obtiene la fecha y hora de la última modificación. |
| [Name](../../groupdocs.metadata.formats.archive/zipfile/name) { get; } | Obtiene el nombre de la entrada. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [RawName](../../groupdocs.metadata.formats.archive/zipfile/rawname) { get; } | Obtiene una matriz de bytes que representa el nombre de la entrada. |
| [UncompressedSize](../../groupdocs.metadata.formats.archive/zipfile/uncompressedsize) { get; } | Obtiene el tamaño sin comprimir en bytes. |

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

* [Trabajar con archivos ZIP](https://docs.groupdocs.com/display/metadatanet/Working+with+ZIP+archives)

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Archive](../../groupdocs.metadata.formats.archive)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
