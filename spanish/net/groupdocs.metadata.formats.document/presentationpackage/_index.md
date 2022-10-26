---
title: PresentationPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa un paquete de metadatos nativos en una presentación.
type: docs
weight: 1090
url: /es/net/groupdocs.metadata.formats.document/presentationpackage/
---
## PresentationPackage class

Representa un paquete de metadatos nativos en una presentación.

```csharp
public class PresentationPackage : DocumentPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ApplicationTemplate](../../groupdocs.metadata.formats.document/presentationpackage/applicationtemplate) { get; set; } | Obtiene o establece la plantilla de la aplicación. |
| [Author](../../groupdocs.metadata.formats.document/presentationpackage/author) { get; set; } | Obtiene o establece el autor del documento. |
| [Category](../../groupdocs.metadata.formats.document/presentationpackage/category) { get; set; } | Obtiene o establece la categoría. |
| [Comments](../../groupdocs.metadata.formats.document/presentationpackage/comments) { get; set; } | Obtiene o establece los comentarios. |
| [Company](../../groupdocs.metadata.formats.document/presentationpackage/company) { get; set; } | Obtiene o establece la empresa. |
| [ContentStatus](../../groupdocs.metadata.formats.document/presentationpackage/contentstatus) { get; set; } | Obtiene o establece el estado del contenido. Solo se puede actualizar en un documento PPTX. |
| [ContentType](../../groupdocs.metadata.formats.document/presentationpackage/contenttype) { get; set; } | Obtiene o establece el tipo de contenido. Solo se puede actualizar en un documento PPTX. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [CreatedTime](../../groupdocs.metadata.formats.document/presentationpackage/createdtime) { get; set; } | Obtiene o establece la fecha de creación del documento. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/presentationpackage/hyperlinkbase) { get; set; } | Obtiene o establece la base del hipervínculo. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Keywords](../../groupdocs.metadata.formats.document/presentationpackage/keywords) { get; set; } | Obtiene o establece las palabras clave. |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/presentationpackage/lastprinteddate) { get; set; } | Obtiene o establece la última fecha impresa. |
| [LastSavedBy](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedby) { get; set; } | Obtiene o establece el nombre del último autor. |
| [LastSavedTime](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedtime) { get; } | Obtiene la fecha y hora en que se modificó la presentación por última vez. |
| [Manager](../../groupdocs.metadata.formats.document/presentationpackage/manager) { get; set; } | Obtiene o establece el administrador. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [NameOfApplication](../../groupdocs.metadata.formats.document/presentationpackage/nameofapplication) { get; } | Obtiene el nombre de la aplicación que creó el documento. |
| [PresentationFormat](../../groupdocs.metadata.formats.document/presentationpackage/presentationformat) { get; } | Obtiene el formato de presentación. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [RevisionNumber](../../groupdocs.metadata.formats.document/presentationpackage/revisionnumber) { get; set; } | Obtiene o establece el número de revisión. |
| [SharedDoc](../../groupdocs.metadata.formats.document/presentationpackage/shareddoc) { get; set; } | Obtiene o establece un valor que indica si la presentación se comparte entre varias personas. Solo se puede actualizar en un documento PPTX. |
| [Subject](../../groupdocs.metadata.formats.document/presentationpackage/subject) { get; set; } | Obtiene o establece el asunto. |
| [Title](../../groupdocs.metadata.formats.document/presentationpackage/title) { get; set; } | Obtiene o establece el título del documento. |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/presentationpackage/totaleditingtime) { get; set; } | Obtiene o establece el tiempo total de edición del documento. |
| [Version](../../groupdocs.metadata.formats.document/presentationpackage/version) { get; } | Obtiene la versión de la aplicación. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | Elimina todas las propiedades de metadatos de escritura del paquete. |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | Elimina todas las propiedades de metadatos integradas. |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | Elimina todas las propiedades de metadatos personalizados. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | Elimina una propiedad de metadatos de escritura por el nombre especificado. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set)(string, bool) | Agrega o reemplaza la propiedad de metadatos con el nombre especificado. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_3)(string, DateTime) | Agrega o reemplaza la propiedad de metadatos con el nombre especificado. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_1)(string, double) | Agrega o reemplaza la propiedad de metadatos con el nombre especificado. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_2)(string, int) | Agrega o reemplaza la propiedad de metadatos con el nombre especificado. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_4)(string, string) | Agrega o reemplaza la propiedad de metadatos con el nombre especificado. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos en Presentaciones](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Presentations)

### Ejemplos

Este ejemplo demuestra cómo actualizar las propiedades de metadatos integradas en una presentación.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPptx))
{
    var root = metadata.GetRootPackage<PresentationRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputPptx);
}
```

### Ver también

* class [DocumentPackage](../documentpackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
