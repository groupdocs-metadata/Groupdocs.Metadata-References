---
title: VCardSecurityRecordset
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa un conjunto de registros de Security vCard. Estas propiedades están relacionadas con la seguridad de las vías de comunicación o el acceso a la vCard.
type: docs
weight: 800
url: /es/net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/
---
## VCardSecurityRecordset class

Representa un conjunto de registros de Security vCard. Estas propiedades están relacionadas con la seguridad de las vías de comunicación o el acceso a la vCard.

```csharp
public class VCardSecurityRecordset : VCardRecordset
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AccessClassification](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/accessclassification) { get; } | Obtiene la sensibilidad de la información en la vCard. |
| [BinaryPublicKeys](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/binarypublickeys) { get; } | Obtiene las claves públicas o certificados de autenticación asociados al objeto. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [PublicKeyBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/publickeybinaryrecords) { get; } | Obtiene las claves públicas o certificados de autenticación asociados al objeto. |
| [PublicKeyRecords](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/publickeyrecords) { get; } | Obtiene las claves públicas o certificados de autenticación asociados al objeto. |
| [PublicKeyUriRecords](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/publickeyurirecords) { get; } | Obtiene las claves públicas o certificados de autenticación asociados al objeto. |
| [UriPublicKeys](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/uripublickeys) { get; } | Obtiene las claves públicas o certificados de autenticación asociados al objeto. |

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
