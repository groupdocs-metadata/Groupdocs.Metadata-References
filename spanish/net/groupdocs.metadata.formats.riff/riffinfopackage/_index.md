---
title: RiffInfoPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa el paquete de metadatos que contiene las propiedades extraídas del fragmento RIFF INFO.
type: docs
weight: 2220
url: /es/net/groupdocs.metadata.formats.riff/riffinfopackage/
---
## RiffInfoPackage class

Representa el paquete de metadatos que contiene las propiedades extraídas del fragmento RIFF INFO.

```csharp
public sealed class RiffInfoPackage : CustomPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Artist](../../groupdocs.metadata.formats.riff/riffinfopackage/artist) { get; } | Obtiene el artista del tema original del archivo. |
| [Comment](../../groupdocs.metadata.formats.riff/riffinfopackage/comment) { get; } | Obtiene el comentario sobre el archivo o el asunto del archivo. |
| [Copyright](../../groupdocs.metadata.formats.riff/riffinfopackage/copyright) { get; } | Obtiene la información de copyright del archivo. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [CreationDate](../../groupdocs.metadata.formats.riff/riffinfopackage/creationdate) { get; } | Obtiene la fecha en que se creó el asunto del archivo. |
| [Engineer](../../groupdocs.metadata.formats.riff/riffinfopackage/engineer) { get; } | Obtiene el nombre del ingeniero que trabajó en el archivo. |
| [Genre](../../groupdocs.metadata.formats.riff/riffinfopackage/genre) { get; } | Obtiene el género de la obra original. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Keywords](../../groupdocs.metadata.formats.riff/riffinfopackage/keywords) { get; } | Obtiene las palabras clave que hacen referencia al archivo o asunto del archivo. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [Name](../../groupdocs.metadata.formats.riff/riffinfopackage/name) { get; } | Obtiene el título del asunto del archivo. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Software](../../groupdocs.metadata.formats.riff/riffinfopackage/software) { get; } | Obtiene el nombre del paquete de software utilizado para crear el archivo. |
| [Source](../../groupdocs.metadata.formats.riff/riffinfopackage/source) { get; } | Obtiene el nombre de la persona u organización que suministró el asunto original del archivo. |
| [Subject](../../groupdocs.metadata.formats.riff/riffinfopackage/subject) { get; } | Obtiene una descripción del contenido del archivo, como "Vista aérea de Seattle". |
| [Technician](../../groupdocs.metadata.formats.riff/riffinfopackage/technician) { get; } | Obtiene el técnico que digitalizó el archivo del asunto. |

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
* espacio de nombres [GroupDocs.Metadata.Formats.Riff](../../groupdocs.metadata.formats.riff)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
