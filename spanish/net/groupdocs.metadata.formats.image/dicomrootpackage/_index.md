---
title: DicomRootPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa el paquete raíz destinado a trabajar con metadatos en una imagen DICOM.
type: docs
weight: 1680
url: /es/net/groupdocs.metadata.formats.image/dicomrootpackage/
---
## DicomRootPackage class

Representa el paquete raíz destinado a trabajar con metadatos en una imagen DICOM.

```csharp
public class DicomRootPackage : ImageRootPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DicomPackage](../../groupdocs.metadata.formats.image/dicomrootpackage/dicompackage) { get; } | Obtiene el paquete de metadatos nativos DICOM. |
| [FileType](../../groupdocs.metadata.formats.image/imagerootpackage/filetype) { get; } | Obtiene el paquete de metadatos del tipo de archivo. (2 properties) |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |

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

* [Trabajar con metadatos DICOM](https://docs.groupdocs.com/display/metadatanet/Working+with+DICOM+metadata)

### Ejemplos

Este ejemplo demuestra cómo leer las propiedades de metadatos específicas del formato DICOM.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDicom))
{
    var root = metadata.GetRootPackage<DicomRootPackage>();
    if (root.DicomPackage != null)
    {
        Console.WriteLine(root.DicomPackage.BitsAllocated);
        Console.WriteLine(root.DicomPackage.LengthValue);
        Console.WriteLine(root.DicomPackage.DicomFound);
        Console.WriteLine(root.DicomPackage.HeaderOffset);
        Console.WriteLine(root.DicomPackage.NumberOfFrames);

        // ...
    }
}
```

### Ver también

* class [ImageRootPackage](../imagerootpackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
