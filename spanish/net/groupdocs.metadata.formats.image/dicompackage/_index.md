---
title: DicomPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa metadatos DICOM nativos.
type: docs
weight: 1670
url: /es/net/groupdocs.metadata.formats.image/dicompackage/
---
## DicomPackage class

Representa metadatos DICOM nativos.

```csharp
public sealed class DicomPackage : CustomPackage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DicomPackage](dicompackage)() | Inicializa una nueva instancia del[`Metadata`](../../groupdocs.metadata/metadata) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BitsAllocated](../../groupdocs.metadata.formats.image/dicompackage/bitsallocated) { get; } | Obtiene el valor de los bits asignados. |
| [Blues](../../groupdocs.metadata.formats.image/dicompackage/blues) { get; } | Obtiene la matriz de colores del blue. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DicomInfo](../../groupdocs.metadata.formats.image/dicompackage/dicominfo) { get; } | Obtiene la información del encabezado del archivo DICOM. |
| [Greens](../../groupdocs.metadata.formats.image/dicompackage/greens) { get; } | Obtiene la matriz de colores del green. |
| [HeaderBytes](../../groupdocs.metadata.formats.image/dicompackage/headerbytes) { get; } | Obtiene la información del encabezado por bytes. |
| [HeaderOffset](../../groupdocs.metadata.formats.image/dicompackage/headeroffset) { get; } | Obtiene el desplazamiento del encabezado. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [NumberOfFrames](../../groupdocs.metadata.formats.image/dicompackage/numberofframes) { get; } | Obtiene el número de fotogramas. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Reds](../../groupdocs.metadata.formats.image/dicompackage/reds) { get; } | Obtiene la matriz de colores del rojo. |

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

* [Trabajar con metadatos DICOM](https://docs.groupdocs.com/display/metadatanet/Working+with+DICOM+metadata)

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
