---
title: WordProcessingInspectionPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Contiene información sobre partes del documento que pueden considerarse metadatos en algunos casos.
type: docs
weight: 1270
url: /es/net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/
---
## WordProcessingInspectionPackage class

Contiene información sobre partes del documento que pueden considerarse metadatos en algunos casos.

```csharp
public sealed class WordProcessingInspectionPackage : CustomPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Comments](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/comments) { get; } | Obtiene una matriz de los comentarios de los usuarios. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/digitalsignatures) { get; } | Obtiene una matriz de firmas digitales presentadas en el documento. |
| [Fields](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/fields) { get; } | Obtiene una matriz de campos de documento. |
| [HiddenText](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/hiddentext) { get; } | Obtiene una matriz de fragmentos de texto ocultos extraídos del documento. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Revisions](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/revisions) { get; } | Obtiene una matriz de firmas digitales presentadas en el documento. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AcceptAllRevisions](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/acceptallrevisions)() | Acepta todas las revisiones detectadas en el documento. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [ClearComments](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clearcomments)() | Elimina todos los comentarios de usuario detectados del documento. |
| [ClearFields](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clearfields)() | Elimina todos los campos detectados del documento. |
| [ClearHiddenText](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clearhiddentext)() | Elimina todos los fragmentos de texto ocultos del documento. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [RejectAllRevisions](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/rejectallrevisions)() | Rechaza todas las revisiones detectadas en el documento. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| override [Sanitize](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos en documentos de WordProcessing](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Ejemplos

Este ejemplo de código muestra cómo actualizar las propiedades de inspección en un documento de WordProcessing.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDoc))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    root.InspectionPackage.ClearComments();
    root.InspectionPackage.AcceptAllRevisions();
    root.InspectionPackage.ClearFields();
    root.InspectionPackage.ClearHiddenText();

    metadata.Save(Constants.OutputDoc);
}
```

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
