---
title: VCardIdentificationRecordset
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa un conjunto de registros de identificación vCard. Estos tipos se utilizan para capturar información asociada con la identificación y el nombre de la entidad asociada con la vCard.
type: docs
weight: 740
url: /es/net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/
---
## VCardIdentificationRecordset class

Representa un conjunto de registros de identificación vCard. Estos tipos se utilizan para capturar información asociada con la identificación y el nombre de la entidad asociada con la vCard.

```csharp
public class VCardIdentificationRecordset : VCardRecordset
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AnniversaryDateTimeRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversarydatetimerecord) { get; } | Obtiene la fecha de matrimonio representada como un solo valor de fecha y hora. |
| [AnniversaryRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversaryrecord) { get; } | Obtiene la fecha de matrimonio, o equivalente, del objeto. |
| [AnniversaryTextRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversarytextrecord) { get; } | Obtiene la fecha de matrimonio representada como un solo valor de texto. |
| [BinaryPhotos](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/binaryphotos) { get; } | Obtiene una matriz que contiene la información de la imagen o fotografía representada como datos binarios que anotan algunos aspectos del objeto. |
| [BirthdateDateTimeRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdatedatetimerecord) { get; } | Obtiene la fecha de nacimiento del objeto. |
| [BirthdateRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdaterecords) { get; } | Obtiene una matriz que contiene la fecha de nacimiento del objeto en diferentes representaciones. |
| [BirthdateTextRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdatetextrecords) { get; } | Obtiene una matriz que contiene la fecha de nacimiento del objeto en diferentes representaciones de texto. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DateTimeAnniversary](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/datetimeanniversary) { get; } | Obtiene la fecha de matrimonio representada como un solo valor de fecha y hora. |
| [DateTimeBirthdate](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/datetimebirthdate) { get; } | Obtiene la fecha de nacimiento del objeto. |
| [FormattedNameRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/formattednamerecords) { get; } | Obtiene una matriz que contiene el texto formateado correspondiente al nombre del objeto. |
| [FormattedNames](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/formattednames) { get; } | Obtiene una matriz que contiene el texto formateado correspondiente al nombre del objeto. |
| [Gender](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/gender) { get; } | Obtiene los componentes de la identidad de sexo y género del objeto. |
| [GenderRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/genderrecord) { get; } | Obtiene los componentes de la identidad de sexo y género del objeto. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [Name](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/name) { get; } | Obtiene los componentes del nombre del objeto. |
| [NameRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/namerecord) { get; } | Obtiene los componentes del nombre del objeto. |
| [NicknameRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/nicknamerecords) { get; } | Obtiene una matriz que contiene el texto correspondiente al apodo del objeto. |
| [Nicknames](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/nicknames) { get; } | Obtiene una matriz que contiene el texto correspondiente al apodo del objeto. |
| [PhotoBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photobinaryrecords) { get; } | Obtiene una matriz que contiene la información de la imagen o fotografía representada como datos binarios que anotan algunos aspectos del objeto. |
| [PhotoRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photorecords) { get; } | Obtiene una matriz que contiene la información de la imagen o fotografía que anota algunos aspectos del objeto. |
| [PhotoUriRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photourirecords) { get; } | Obtiene una matriz que contiene la información de la imagen o fotografía representada por URI que anota algunos aspectos del objeto. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [TextAnniversary](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/textanniversary) { get; } | Obtiene la fecha de matrimonio representada como un solo valor de texto. |
| [TextBirthdates](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/textbirthdates) { get; } | Obtiene una matriz que contiene la fecha de nacimiento del objeto en diferentes representaciones de texto. |
| [UriPhotos](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/uriphotos) { get; } | Obtiene una matriz que contiene la información de la imagen o fotografía representada por URI que anota algunos aspectos del objeto. |

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
