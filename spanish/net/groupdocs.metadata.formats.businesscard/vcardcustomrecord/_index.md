---
title: VCardCustomRecord
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa la clase de metadatos de registros personalizados vCard.
type: docs
weight: 680
url: /es/net/groupdocs.metadata.formats.businesscard/vcardcustomrecord/
---
## VCardCustomRecord class

Representa la clase de metadatos de registros personalizados vCard.

```csharp
public class VCardCustomRecord : VCardRecord
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AltIdParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/altidparameter) { get; } | Obtiene el valor del parámetro de representaciones alternativas. |
| [AnonymParameters](../../groupdocs.metadata.formats.businesscard/vcardrecord/anonymparameters) { get; } | Obtiene los parámetros anónimos. |
| override [ContentType](../../groupdocs.metadata.formats.businesscard/vcardcustomrecord/contenttype) { get; } | Obtiene el tipo de contenido del registro. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [EncodingParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/encodingparameter) { get; } | Obtiene el valor del parámetro de codificación. |
| [Group](../../groupdocs.metadata.formats.businesscard/vcardrecord/group) { get; } | Obtiene el valor de agrupación. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [LanguageParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/languageparameter) { get; } | Obtiene el valor del parámetro de idioma. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PrefParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/prefparameter) { get; } | Obtiene el parámetro preferido. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [TypeName](../../groupdocs.metadata.formats.businesscard/vcardrecord/typename) { get; } | Obtiene el tipo de registro. |
| [TypeParameters](../../groupdocs.metadata.formats.businesscard/vcardrecord/typeparameters) { get; } | Obtiene los valores del parámetro de tipo. |
| [Value](../../groupdocs.metadata.formats.businesscard/vcardcustomrecord/value) { get; } | Obtiene el valor del registro. |
| [ValueParameters](../../groupdocs.metadata.formats.businesscard/vcardrecord/valueparameters) { get; } | Obtiene el valor de los parámetros. |

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

* [Trabajar con metadatos vCard](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Ver también

* class [VCardRecord](../vcardrecord)
* espacio de nombres [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
