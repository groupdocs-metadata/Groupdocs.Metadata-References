---
title: PsdLayer
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa una capa en un archivo PSD.
type: docs
weight: 1900
url: /es/net/groupdocs.metadata.formats.image/psdlayer/
---
## PsdLayer class

Representa una capa en un archivo PSD.

```csharp
public sealed class PsdLayer : CustomPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BitsPerPixel](../../groupdocs.metadata.formats.image/psdlayer/bitsperpixel) { get; } | Obtiene el valor de bits por píxel. |
| [Bottom](../../groupdocs.metadata.formats.image/psdlayer/bottom) { get; } | Obtiene la posición de la capa inferior. |
| [ChannelCount](../../groupdocs.metadata.formats.image/psdlayer/channelcount) { get; } | Obtiene el número de canales. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Flags](../../groupdocs.metadata.formats.image/psdlayer/flags) { get; } | Obtiene las banderas de la capa. |
| [Height](../../groupdocs.metadata.formats.image/psdlayer/height) { get; } | Obtiene la altura. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Left](../../groupdocs.metadata.formats.image/psdlayer/left) { get; } | Obtiene la posición de la capa izquierda. |
| [Length](../../groupdocs.metadata.formats.image/psdlayer/length) { get; } | Obtiene la longitud total de la capa en bytes. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [Name](../../groupdocs.metadata.formats.image/psdlayer/name) { get; } | Obtiene el nombre de la capa. |
| [Opacity](../../groupdocs.metadata.formats.image/psdlayer/opacity) { get; } | Obtiene la opacidad de la capa. 0 = transparente, 255 = opaco. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Right](../../groupdocs.metadata.formats.image/psdlayer/right) { get; } | Obtiene la posición correcta de la capa. |
| [Top](../../groupdocs.metadata.formats.image/psdlayer/top) { get; } | Obtiene la posición de la capa superior. |
| [Width](../../groupdocs.metadata.formats.image/psdlayer/width) { get; } | Obtiene el ancho. |

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

* [Trabajar con metadatos en imágenes PSD](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PSD+images)

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
