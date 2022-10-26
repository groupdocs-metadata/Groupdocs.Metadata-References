---
title: CanonMakerNotePackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa metadatos de CANON MakerNote.
type: docs
weight: 2820
url: /es/net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/
---
## CanonMakerNotePackage class

Representa metadatos de CANON MakerNote.

```csharp
public sealed class CanonMakerNotePackage : MakerNotePackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CameraSettings](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/camerasettings) { get; } | Obtiene la configuración de la cámara. |
| [CanonFileLength](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/canonfilelength) { get; } | Obtiene la longitud del archivo canon. |
| [CanonFirmwareVersion](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/canonfirmwareversion) { get; } | Obtiene la versión de firmware de canon. |
| [CanonImageType](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/canonimagetype) { get; } | Obtiene el tipo de imagen Canon. |
| [CanonModelID](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/canonmodelid) { get; } | Obtiene el identificador del modelo canon. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [FileNumber](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/filenumber) { get; } | Obtiene el número de archivo. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Obtiene la etiqueta TIFF con el id especificado. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [OwnerName](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/ownername) { get; } | Obtiene el nombre del propietario. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [SerialNumber](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/serialnumber) { get; } | Obtiene el número de serie. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Elimina todas las etiquetas TIFF almacenadas en el paquete. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Elimina la propiedad con el id especificado. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Agrega o reemplaza la etiqueta especificada. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Crea una lista a partir del paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Ver también

* class [MakerNotePackage](../makernotepackage)
* espacio de nombres [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
