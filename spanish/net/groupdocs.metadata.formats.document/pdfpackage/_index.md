---
title: PdfPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa metadatos nativos en un documento PDF.
type: docs
weight: 1030
url: /es/net/groupdocs.metadata.formats.document/pdfpackage/
---
## PdfPackage class

Representa metadatos nativos en un documento PDF.

```csharp
public class PdfPackage : DocumentPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/pdfpackage/author) { get; set; } | Obtiene o establece el autor del documento. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [CreatedDate](../../groupdocs.metadata.formats.document/pdfpackage/createddate) { get; set; } | Obtiene o establece la fecha de creación del documento. |
| [Creator](../../groupdocs.metadata.formats.document/pdfpackage/creator) { get; } | Obtiene el creador del documento. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Keywords](../../groupdocs.metadata.formats.document/pdfpackage/keywords) { get; set; } | Obtiene o establece las palabras clave. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [ModifiedDate](../../groupdocs.metadata.formats.document/pdfpackage/modifieddate) { get; set; } | Obtiene o establece la fecha de la última modificación. |
| [Producer](../../groupdocs.metadata.formats.document/pdfpackage/producer) { get; } | Obtiene el productor del documento. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Subject](../../groupdocs.metadata.formats.document/pdfpackage/subject) { get; set; } | Obtiene o establece el asunto del documento. |
| [Title](../../groupdocs.metadata.formats.document/pdfpackage/title) { get; set; } | Obtiene o establece el título del documento. |
| [TrappedFlag](../../groupdocs.metadata.formats.document/pdfpackage/trappedflag) { get; set; } | Obtiene o establece el indicador atrapado. |

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
| [Set](../../groupdocs.metadata.formats.document/pdfpackage/set)(string, string) | Agrega o reemplaza la propiedad de metadatos con el nombre especificado. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos en documentos PDF](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

### Ejemplos

Este fragmento de código demuestra cómo actualizar las propiedades de metadatos integradas en un documento PDF.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedDate = DateTime.Now;
    root.DocumentProperties.Title = "test title";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputPdf);
}
```

### Ver también

* class [DocumentPackage](../documentpackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
