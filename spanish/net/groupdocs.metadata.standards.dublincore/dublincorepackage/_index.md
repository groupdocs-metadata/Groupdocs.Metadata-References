---
title: DublinCorePackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa un paquete de metadatos Dublin Core.
type: docs
weight: 2730
url: /es/net/groupdocs.metadata.standards.dublincore/dublincorepackage/
---
## DublinCorePackage class

Representa un paquete de metadatos Dublin Core.

```csharp
public sealed class DublinCorePackage : CustomPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Contributor](../../groupdocs.metadata.standards.dublincore/dublincorepackage/contributor) { get; } | Obtiene el elemento colaborador Dublin Core. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Coverage](../../groupdocs.metadata.standards.dublincore/dublincorepackage/coverage) { get; } | Obtiene el elemento Dublin Core de cobertura. |
| [Creator](../../groupdocs.metadata.standards.dublincore/dublincorepackage/creator) { get; } | Obtiene el elemento creador Dublin Core. |
| [Date](../../groupdocs.metadata.standards.dublincore/dublincorepackage/date) { get; } | Obtiene la fecha del elemento Dublin Core. |
| [Description](../../groupdocs.metadata.standards.dublincore/dublincorepackage/description) { get; } | Obtiene la descripción del elemento Dublin Core. |
| [Format](../../groupdocs.metadata.standards.dublincore/dublincorepackage/format) { get; } | Obtiene el formato del elemento Dublin Core. |
| [Identifier](../../groupdocs.metadata.standards.dublincore/dublincorepackage/identifier) { get; } | Obtiene el identificador del elemento Dublin Core. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Language](../../groupdocs.metadata.standards.dublincore/dublincorepackage/language) { get; } | Obtiene el idioma del elemento Dublin Core. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Publisher](../../groupdocs.metadata.standards.dublincore/dublincorepackage/publisher) { get; } | Obtiene el elemento Dublin Core del editor. |
| [Relation](../../groupdocs.metadata.standards.dublincore/dublincorepackage/relation) { get; } | Obtiene la relación elemento Dublin Core. |
| [Rights](../../groupdocs.metadata.standards.dublincore/dublincorepackage/rights) { get; } | Obtiene los derechos del elemento Dublin Core. |
| [Source](../../groupdocs.metadata.standards.dublincore/dublincorepackage/source) { get; } | Obtiene el elemento Dublin Core de origen. |
| [Subject](../../groupdocs.metadata.standards.dublincore/dublincorepackage/subject) { get; } | Obtiene el elemento Dublin Core de asunto. |
| [Title](../../groupdocs.metadata.standards.dublincore/dublincorepackage/title) { get; } | Obtiene el título Elemento Dublin Core. |
| [Type](../../groupdocs.metadata.standards.dublincore/dublincorepackage/type) { get; } | Obtiene el tipo de elemento Dublin Core. |

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

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Standards.DublinCore](../../groupdocs.metadata.standards.dublincore)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
