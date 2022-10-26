---
title: CadPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa metadatos CAD diseño asistido por computadora.
type: docs
weight: 840
url: /es/net/groupdocs.metadata.formats.cad/cadpackage/
---
## CadPackage class

Representa metadatos CAD (diseño asistido por computadora).

```csharp
public sealed class CadPackage : CustomPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AcadVersion](../../groupdocs.metadata.formats.cad/cadpackage/acadversion) { get; } | Obtiene el número de versión de la base de datos de dibujo de AutoCAD. |
| [Author](../../groupdocs.metadata.formats.cad/cadpackage/author) { get; } | Obtiene el autor del dibujo. |
| [Comments](../../groupdocs.metadata.formats.cad/cadpackage/comments) { get; } | Obtiene los comentarios del usuario. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [CreatedDateTime](../../groupdocs.metadata.formats.cad/cadpackage/createddatetime) { get; } | Obtiene la fecha y hora en que se creó el dibujo. |
| [CustomProperties](../../groupdocs.metadata.formats.cad/cadpackage/customproperties) { get; } | Obtiene el paquete que contiene propiedades de metadatos personalizadas. |
| [Height](../../groupdocs.metadata.formats.cad/cadpackage/height) { get; } | Obtiene la altura del dibujo. |
| [HyperlinkBase](../../groupdocs.metadata.formats.cad/cadpackage/hyperlinkbase) { get; } | Obtiene la base del hipervínculo. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Keywords](../../groupdocs.metadata.formats.cad/cadpackage/keywords) { get; } | Obtiene las palabras clave. |
| [LastSavedBy](../../groupdocs.metadata.formats.cad/cadpackage/lastsavedby) { get; } | Obtiene el nombre del último editor. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [ModifiedDateTime](../../groupdocs.metadata.formats.cad/cadpackage/modifieddatetime) { get; } | Obtiene la fecha y hora en que se modificó el dibujo. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [RevisionNumber](../../groupdocs.metadata.formats.cad/cadpackage/revisionnumber) { get; } | Obtiene el número de revisión. |
| [Subject](../../groupdocs.metadata.formats.cad/cadpackage/subject) { get; } | Obtiene el asunto. |
| [Title](../../groupdocs.metadata.formats.cad/cadpackage/title) { get; } | Obtiene el título. |
| [Width](../../groupdocs.metadata.formats.cad/cadpackage/width) { get; } | Obtiene el ancho del dibujo. |

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

* [Trabajar con metadatos CAD](https://docs.groupdocs.com/display/metadatanet/Working+with+CAD+metadata)

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Cad](../../groupdocs.metadata.formats.cad)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
