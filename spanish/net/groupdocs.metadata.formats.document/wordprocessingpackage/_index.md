---
title: WordProcessingPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa un paquete de metadatos nativos en un documento de procesamiento de textos.
type: docs
weight: 1280
url: /es/net/groupdocs.metadata.formats.document/wordprocessingpackage/
---
## WordProcessingPackage class

Representa un paquete de metadatos nativos en un documento de procesamiento de textos.

```csharp
public class WordProcessingPackage : DocumentPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/wordprocessingpackage/author) { get; set; } | Obtiene o establece el autor del documento. |
| [BytesInDocument](../../groupdocs.metadata.formats.document/wordprocessingpackage/bytesindocument) { get; } | Obtiene una estimación del número de bytes en el documento. |
| [Category](../../groupdocs.metadata.formats.document/wordprocessingpackage/category) { get; set; } | Obtiene o establece la categoría. |
| [Comments](../../groupdocs.metadata.formats.document/wordprocessingpackage/comments) { get; set; } | Obtiene o establece los comentarios. |
| [Company](../../groupdocs.metadata.formats.document/wordprocessingpackage/company) { get; set; } | Obtiene o establece la empresa. |
| [ContentStatus](../../groupdocs.metadata.formats.document/wordprocessingpackage/contentstatus) { get; set; } | Obtiene o establece el estado del contenido. |
| [ContentType](../../groupdocs.metadata.formats.document/wordprocessingpackage/contenttype) { get; set; } | Obtiene o establece el tipo de contenido del documento. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [CreatedTime](../../groupdocs.metadata.formats.document/wordprocessingpackage/createdtime) { get; set; } | Obtiene o establece la fecha de creación del documento. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/wordprocessingpackage/hyperlinkbase) { get; set; } | Obtiene o establece la base del hipervínculo. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Keywords](../../groupdocs.metadata.formats.document/wordprocessingpackage/keywords) { get; set; } | Obtiene o establece las palabras clave. |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/wordprocessingpackage/lastprinteddate) { get; set; } | Obtiene o establece la última fecha impresa. |
| [LastSavedBy](../../groupdocs.metadata.formats.document/wordprocessingpackage/lastsavedby) { get; set; } | Obtiene o establece el nombre del último autor. |
| [LastSavedTime](../../groupdocs.metadata.formats.document/wordprocessingpackage/lastsavedtime) { get; set; } | Obtiene o establece la hora del último guardado. |
| [LinksUpToDate](../../groupdocs.metadata.formats.document/wordprocessingpackage/linksuptodate) { get; set; } | Obtiene o establece un valor que indica si los hipervínculos del documento están actualizados. |
| [Manager](../../groupdocs.metadata.formats.document/wordprocessingpackage/manager) { get; set; } | Obtiene o establece el administrador. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [NameOfApplication](../../groupdocs.metadata.formats.document/wordprocessingpackage/nameofapplication) { get; } | Obtiene el nombre de la aplicación. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [RevisionNumber](../../groupdocs.metadata.formats.document/wordprocessingpackage/revisionnumber) { get; set; } | Obtiene o establece el número de revisión. |
| [Subject](../../groupdocs.metadata.formats.document/wordprocessingpackage/subject) { get; set; } | Obtiene o establece el asunto. |
| [Template](../../groupdocs.metadata.formats.document/wordprocessingpackage/template) { get; set; } | Obtiene o establece la plantilla. |
| [Title](../../groupdocs.metadata.formats.document/wordprocessingpackage/title) { get; set; } | Obtiene o establece el título del documento. |
| [TitlesOfParts](../../groupdocs.metadata.formats.document/wordprocessingpackage/titlesofparts) { get; } | Obtiene los títulos de las partes del documento. Solo lectura. |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/wordprocessingpackage/totaleditingtime) { get; set; } | Obtiene o establece el tiempo total de edición en minutos. |
| [Version](../../groupdocs.metadata.formats.document/wordprocessingpackage/version) { get; } | Obtiene el número de versión de la aplicación que creó el documento. |

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
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set)(string, bool) | Agrega o reemplaza la propiedad de metadatos con el nombre especificado. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_3)(string, DateTime) | Agrega o reemplaza la propiedad de metadatos con el nombre especificado. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_1)(string, double) | Agrega o reemplaza la propiedad de metadatos con el nombre especificado. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_2)(string, int) | Agrega o reemplaza la propiedad de metadatos con el nombre especificado. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_4)(string, string) | Agrega o reemplaza la propiedad de metadatos con el nombre especificado. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos en documentos de WordProcessing](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Ejemplos

Este ejemplo de código muestra cómo actualizar las propiedades de metadatos integradas en un documento de WordProcessing.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDoc))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputDoc);
}
```

### Ver también

* class [DocumentPackage](../documentpackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
