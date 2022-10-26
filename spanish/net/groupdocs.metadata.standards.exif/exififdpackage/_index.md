---
title: ExifIfdPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa el directorio de archivos de imágenes Exif. Exif IFD es un conjunto de etiquetas para registrar información de atributos específicos de Exif.
type: docs
weight: 2780
url: /es/net/groupdocs.metadata.standards.exif/exififdpackage/
---
## ExifIfdPackage class

Representa el directorio de archivos de imágenes Exif. Exif IFD es un conjunto de etiquetas para registrar información de atributos específicos de Exif.

```csharp
public sealed class ExifIfdPackage : ExifDictionaryBasePackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BodySerialNumber](../../groupdocs.metadata.standards.exif/exififdpackage/bodyserialnumber) { get; set; } | Obtiene o establece el número de serie del cuerpo de la cámara. |
| [CameraOwnerName](../../groupdocs.metadata.standards.exif/exififdpackage/cameraownername) { get; set; } | Obtiene o establece el nombre del propietario de la cámara. |
| [CfaPattern](../../groupdocs.metadata.standards.exif/exififdpackage/cfapattern) { get; set; } | Obtiene o establece el patrón geométrico de matriz de filtro de color (CFA) del sensor de imagen cuando se utiliza un sensor de área de color de un chip. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Obtiene la etiqueta TIFF con el id especificado. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [UserComment](../../groupdocs.metadata.standards.exif/exififdpackage/usercomment) { get; set; } | Obtiene o establece el comentario del usuario. |

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

### Observaciones

**Aprende más**

* [Trabajar con metadatos EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Ver también

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* espacio de nombres [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
