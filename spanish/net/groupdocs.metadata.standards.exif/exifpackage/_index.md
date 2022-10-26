---
title: ExifPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa un paquete de metadatos EXIF Formato de archivo de imagen intercambiable.
type: docs
weight: 2790
url: /es/net/groupdocs.metadata.standards.exif/exifpackage/
---
## ExifPackage class

Representa un paquete de metadatos EXIF (Formato de archivo de imagen intercambiable).

```csharp
public class ExifPackage : ExifDictionaryBasePackage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ExifPackage](exifpackage)() | Inicializa una nueva instancia del[`ExifPackage`](../exifpackage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Artist](../../groupdocs.metadata.standards.exif/exifpackage/artist) { get; set; } | Obtiene o establece el nombre del propietario de la cámara, el fotógrafo o el creador de la imagen. |
| [Copyright](../../groupdocs.metadata.standards.exif/exifpackage/copyright) { get; set; } | Obtiene o establece el aviso de copyright. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DateTime](../../groupdocs.metadata.standards.exif/exifpackage/datetime) { get; set; } | Obtiene o establece la fecha y hora de creación de la imagen. En el estándar EXIF, es la fecha y hora en que se modificó el archivo. |
| [ExifIfdPackage](../../groupdocs.metadata.standards.exif/exifpackage/exififdpackage) { get; } | Obtiene los datos EXIF IFD. |
| [GpsPackage](../../groupdocs.metadata.standards.exif/exifpackage/gpspackage) { get; } | Obtiene los datos del GPS. |
| [ImageDescription](../../groupdocs.metadata.standards.exif/exifpackage/imagedescription) { get; set; } | Obtiene o establece una cadena de caracteres que da el título de la imagen. Puede ser un comentario como "picnic de la empresa de 1988" o similar. |
| [ImageLength](../../groupdocs.metadata.standards.exif/exifpackage/imagelength) { get; set; } | Obtiene o establece el número de filas de datos de imagen. |
| [ImageWidth](../../groupdocs.metadata.standards.exif/exifpackage/imagewidth) { get; set; } | Obtiene o establece el número de columnas de datos de imagen, igual al número de píxeles por fila. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Obtiene la etiqueta TIFF con el id especificado. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Make](../../groupdocs.metadata.standards.exif/exifpackage/make) { get; set; } | Obtiene o establece el fabricante del equipo de grabación. Este es el fabricante del DSC, escáner, digitalizador de video u otro equipo que generó la imagen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [Model](../../groupdocs.metadata.standards.exif/exifpackage/model) { get; set; } | Obtiene o establece el nombre o número de modelo del equipo. Este es el nombre o número de modelo del DSC, escáner, digitalizador de video u otro equipo que generó la imagen. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Software](../../groupdocs.metadata.standards.exif/exifpackage/software) { get; set; } | Obtiene o establece el nombre y la versión del software o firmware de la cámara o el dispositivo de entrada de imágenes utilizado para generar la imagen. |
| [Thumbnail](../../groupdocs.metadata.standards.exif/exifpackage/thumbnail) { get; } | Obtiene la miniatura de la imagen representada como una matriz de bytes. |

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

### Ejemplos

Este ejemplo de código muestra cómo actualizar las propiedades EXIF comunes.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        // Establecer el paquete EXIF si falta
        if (root.ExifPackage == null)
        {
            root.ExifPackage = new ExifPackage();
        }

        root.ExifPackage.Copyright = "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.";
        root.ExifPackage.ImageDescription = "test image";
        root.ExifPackage.Software = "GroupDocs.Metadata";

        // ...

        root.ExifPackage.ExifIfdPackage.BodySerialNumber = "test";
        root.ExifPackage.ExifIfdPackage.CameraOwnerName = "GroupDocs";
        root.ExifPackage.ExifIfdPackage.UserComment = "test comment";

        // ...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Ver también

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* espacio de nombres [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
