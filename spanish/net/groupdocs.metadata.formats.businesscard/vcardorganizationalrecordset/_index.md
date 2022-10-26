---
title: VCardOrganizationalRecordset
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa un conjunto de registros vCard organizativos. Estas propiedades se refieren a la información asociada con características de la organización o unidades organizativas de el objeto que representa la vCard.
type: docs
weight: 750
url: /es/net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/
---
## VCardOrganizationalRecordset class

Representa un conjunto de registros vCard organizativos. Estas propiedades se refieren a la información asociada con características de la organización o unidades organizativas de el objeto que representa la vCard.

```csharp
public class VCardOrganizationalRecordset : VCardRecordset
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AgentObjectRecord](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agentobjectrecord) { get; } | Obtiene la información sobre otra persona que actuará en nombre del objeto vCard. |
| [AgentRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agentrecords) { get; } | Obtiene la información sobre otra persona que actuará en nombre del objeto vCard. |
| [AgentUriRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agenturirecords) { get; } | Obtiene la información sobre otra persona que actuará en nombre del objeto vCard. |
| [BinaryLogos](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/binarylogos) { get; } | Obtiene las imágenes gráficas del logo asociado al objeto. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [LogoBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logobinaryrecords) { get; } | Obtiene las imágenes gráficas del logo asociado al objeto. |
| [LogoRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logorecords) { get; } | Obtiene las imágenes gráficas del logo asociado al objeto. |
| [LogoUriRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logourirecords) { get; } | Obtiene las URIs de las imágenes gráficas del logo asociado al objeto. |
| [MemberRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/memberrecords) { get; } | Obtiene los miembros del grupo que representa esta vCard. |
| [Members](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/members) { get; } | Obtiene los miembros del grupo que representa esta vCard. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [ObjectAgent](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/objectagent) { get; } | Obtiene la información sobre otra persona que actuará en nombre del objeto vCard. |
| [OrganizationNameRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/organizationnamerecords) { get; } | Obtiene los nombres de organización y las unidades asociadas con el objeto. |
| [OrganizationNames](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/organizationnames) { get; } | Obtiene los nombres de organización y las unidades asociadas con el objeto. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [RelationshipRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/relationshiprecords) { get; } | Obtiene las relaciones entre otra entidad y la entidad representada por esta vCard. |
| [Relationships](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/relationships) { get; } | Obtiene las relaciones entre otra entidad y la entidad representada por esta vCard. |
| [RoleRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/rolerecords) { get; } | Obtiene las funciones o partes desempeñadas en una situación particular por el objeto. |
| [Roles](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/roles) { get; } | Obtiene las funciones o partes desempeñadas en una situación particular por el objeto. |
| [TitleRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/titlerecords) { get; } | Obtiene las posiciones o trabajos del objeto. |
| [Titles](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/titles) { get; } | Obtiene las posiciones o trabajos del objeto. |
| [UriAgents](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/uriagents) { get; } | Obtiene la información sobre otra persona que actuará en nombre del objeto vCard. |
| [UriLogos](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/urilogos) { get; } | Obtiene las URIs de las imágenes gráficas del logo asociado al objeto. |

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
