---
title: Jpeg2000RootPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa el paquete raíz destinado a trabajar con metadatos en una imagen JPEG2000.
type: docs
weight: 1800
url: /es/net/groupdocs.metadata.formats.image/jpeg2000rootpackage/
---
## Jpeg2000RootPackage class

Representa el paquete raíz destinado a trabajar con metadatos en una imagen JPEG2000.

```csharp
public class Jpeg2000RootPackage : ImageRootPackage, IExif, IXmp
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [ExifPackage](../../groupdocs.metadata.formats.image/jpeg2000rootpackage/exifpackage) { get; set; } | Obtiene o establece el paquete de metadatos EXIF. |
| [FileType](../../groupdocs.metadata.formats.image/imagerootpackage/filetype) { get; } | Obtiene el paquete de metadatos del tipo de archivo. (2 properties) |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Jpeg2000Package](../../groupdocs.metadata.formats.image/jpeg2000rootpackage/jpeg2000package) { get; } | Obtiene el paquete de metadatos nativos JPEG2000. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [XmpPackage](../../groupdocs.metadata.formats.image/jpeg2000rootpackage/xmppackage) { get; set; } | Obtiene o establece el paquete de metadatos XMP. |

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

* [Trabajar con metadatos en imágenes JPEG2000](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG2000+images)
* [Trabajar con metadatos XMP](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Ver también

* class [ImageRootPackage](../imagerootpackage)
* interface [IExif](../../groupdocs.metadata.standards.exif/iexif)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* espacio de nombres [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->