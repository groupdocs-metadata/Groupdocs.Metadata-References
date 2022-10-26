---
title: PdfInspectionPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Contiene información sobre partes del documento PDF que pueden considerarse metadatos en algunos casos.
type: docs
weight: 1020
url: /es/net/groupdocs.metadata.formats.document/pdfinspectionpackage/
---
## PdfInspectionPackage class

Contiene información sobre partes del documento PDF que pueden considerarse metadatos en algunos casos.

```csharp
public sealed class PdfInspectionPackage : CustomPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Annotations](../../groupdocs.metadata.formats.document/pdfinspectionpackage/annotations) { get; } | Obtiene una matriz de las anotaciones. |
| [Attachments](../../groupdocs.metadata.formats.document/pdfinspectionpackage/attachments) { get; } | Obtiene una matriz de archivos adjuntos. |
| [Bookmarks](../../groupdocs.metadata.formats.document/pdfinspectionpackage/bookmarks) { get; } | Obtiene una matriz de marcadores. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/pdfinspectionpackage/digitalsignatures) { get; } | Obtiene una matriz de firmas digitales. |
| [Fields](../../groupdocs.metadata.formats.document/pdfinspectionpackage/fields) { get; } | Obtiene una matriz de los campos del formulario. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [ClearAnnotations](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearannotations)() | Elimina todas las anotaciones detectadas del documento. |
| [ClearAttachments](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearattachments)() | Elimina todos los archivos adjuntos detectados del documento. |
| [ClearBookmarks](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearbookmarks)() | Elimina todos los marcadores detectados del documento. |
| [ClearDigitalSignatures](../../groupdocs.metadata.formats.document/pdfinspectionpackage/cleardigitalsignatures)() | Elimina todas las firmas digitales detectadas del documento. |
| [ClearFields](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearfields)() | Elimina todos los campos de formulario detectados del documento. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/pdfinspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| override [Sanitize](../../groupdocs.metadata.formats.document/pdfinspectionpackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos en documentos PDF](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

### Ejemplos

Este ejemplo de código demuestra cómo eliminar las propiedades de inspección en un documento PDF.

```csharp
using (Metadata metadata = new Metadata(Constants.SignedPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    root.InspectionPackage.ClearAnnotations();
    root.InspectionPackage.ClearAttachments();
    root.InspectionPackage.ClearFields();
    root.InspectionPackage.ClearBookmarks();
    root.InspectionPackage.ClearDigitalSignatures();

    metadata.Save(Constants.OutputPdf);
}
```

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
