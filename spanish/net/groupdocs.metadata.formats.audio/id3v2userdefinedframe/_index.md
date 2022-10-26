---
title: ID3V2UserDefinedFrame
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa una trama TXXX en unID3V2Tag./id3v2tag .
type: docs
weight: 540
url: /es/net/groupdocs.metadata.formats.audio/id3v2userdefinedframe/
---
## ID3V2UserDefinedFrame class

Representa una trama TXXX en un[`ID3V2Tag`](../id3v2tag) .

```csharp
public sealed class ID3V2UserDefinedFrame : ID3V2TagFrame
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ID3V2UserDefinedFrame](id3v2userdefinedframe#constructor_1)(string, string) | Inicializa una nueva instancia del[`ID3V2UserDefinedFrame`](../id3v2userdefinedframe) clase. |
| [ID3V2UserDefinedFrame](id3v2userdefinedframe#constructor)(ID3V2EncodingType, string, string) | Inicializa una nueva instancia del[`ID3V2UserDefinedFrame`](../id3v2userdefinedframe) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Data](../../groupdocs.metadata.formats.audio/id3v2tagframe/data) { get; } | Obtiene los datos del marco. |
| [Description](../../groupdocs.metadata.formats.audio/id3v2userdefinedframe/description) { get; } | Obtiene la descripción. |
| [Encoding](../../groupdocs.metadata.formats.audio/id3v2userdefinedframe/encoding) { get; } | Obtiene la codificación del cuadro. |
| [Flags](../../groupdocs.metadata.formats.audio/id3v2tagframe/flags) { get; } | Obtiene las banderas del marco. |
| [Id](../../groupdocs.metadata.formats.audio/id3v2tagframe/id) { get; } | Obtiene el id del marco (cuatro caracteres que coinciden con el patrón [A-Z0-9]). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Value](../../groupdocs.metadata.formats.audio/id3v2userdefinedframe/value) { get; } | Obtiene el valor. |

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

* [Manejo de la etiqueta ID3v2](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Ver también

* class [ID3V2TagFrame](../id3v2tagframe)
* espacio de nombres [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
