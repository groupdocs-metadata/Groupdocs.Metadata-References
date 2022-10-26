---
title: WordProcessingRootPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa el paquete raíz que permite trabajar con metadatos en un documento de procesamiento de texto.
type: docs
weight: 1310
url: /es/net/groupdocs.metadata.formats.document/wordprocessingrootpackage/
---
## WordProcessingRootPackage class

Representa el paquete raíz que permite trabajar con metadatos en un documento de procesamiento de texto.

```csharp
public class WordProcessingRootPackage : DocumentRootPackage<WordProcessingPackage>, IDublinCore
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| virtual [DocumentProperties](../../groupdocs.metadata.formats.document/documentrootpackage-1/documentproperties) { get; } | Obtiene las propiedades de los metadatos nativos presentados en el documento. |
| [DocumentStatistics](../../groupdocs.metadata.formats.document/wordprocessingrootpackage/documentstatistics) { get; } | Obtiene el paquete de estadísticas del documento. |
| [DublinCorePackage](../../groupdocs.metadata.formats.document/wordprocessingrootpackage/dublincorepackage) { get; } | Obtiene el paquete de metadatos Dublin Core extraído del documento. |
| [FileType](../../groupdocs.metadata.formats.document/wordprocessingrootpackage/filetype) { get; } | Obtiene el paquete de metadatos del tipo de archivo. (2 properties) |
| [InspectionPackage](../../groupdocs.metadata.formats.document/wordprocessingrootpackage/inspectionpackage) { get; } | Obtiene un paquete de metadatos que contiene los resultados de la inspección del documento. El paquete contiene información sobre partes del documento que pueden considerarse metadatos en algunos casos. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateDocumentStatistics](../../groupdocs.metadata.formats.document/wordprocessingrootpackage/updatedocumentstatistics)() | Vuelve a calcular el recuento de páginas, párrafos, palabras, líneas, caracteres del documento y actualiza los paquetes de metadatos correspondientes. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos en documentos de WordProcessing](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Ejemplos

Este ejemplo de código demuestra cómo leer las propiedades de metadatos integradas de un documento de WordProcessing.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDocx))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    Console.WriteLine(root.DocumentProperties.Author);
    Console.WriteLine(root.DocumentProperties.CreatedTime);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Category);
    Console.WriteLine(root.DocumentProperties.Keywords);

    // ... 
}
```

### Ver también

* class [DocumentRootPackage&lt;TPackage&gt;](../documentrootpackage-1)
* class [WordProcessingPackage](../wordprocessingpackage)
* interface [IDublinCore](../../groupdocs.metadata.standards.dublincore/idublincore)
* espacio de nombres [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
