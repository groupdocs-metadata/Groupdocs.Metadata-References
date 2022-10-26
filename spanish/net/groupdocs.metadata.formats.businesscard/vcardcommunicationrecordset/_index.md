---
title: VCardCommunicationRecordset
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa un conjunto de registros de vCard de comunicación. Estas propiedades describen información sobre cómo comunicarse con el objeto que representa la vCard.
type: docs
weight: 660
url: /es/net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/
---
## VCardCommunicationRecordset class

Representa un conjunto de registros de vCard de comunicación. Estas propiedades describen información sobre cómo comunicarse con el objeto que representa la vCard.

```csharp
public class VCardCommunicationRecordset : VCardRecordset
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [EmailRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/emailrecords) { get; } | Obtiene las direcciones de correo electrónico para la comunicación con el objeto. |
| [Emails](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/emails) { get; } | Obtiene las direcciones de correo electrónico para la comunicación con el objeto. |
| [ImppEntries](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/imppentries) { get; } | Obtiene las URI para la mensajería instantánea y las comunicaciones del protocolo de presencia con el objeto. |
| [ImppRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/impprecords) { get; } | Obtiene las URI para la mensajería instantánea y las comunicaciones del protocolo de presencia con el objeto. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [LanguageRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/languagerecords) { get; } | Obtiene los idiomas que se pueden usar para contactar con el objeto. |
| [Languages](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/languages) { get; } | Obtiene los idiomas que se pueden usar para contactar con el objeto. |
| [Mailer](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/mailer) { get; } | Obtiene el tipo de software de correo electrónico que utiliza la persona asociada con la vCard. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [TelephoneRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/telephonerecords) { get; } | Obtiene los números de teléfono para la comunicación telefónica con el objeto. |
| [Telephones](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/telephones) { get; } | Obtiene los números de teléfono para la comunicación telefónica con el objeto. |

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

* class [VCardRecordset](../vcardrecordset)
* espacio de nombres [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
