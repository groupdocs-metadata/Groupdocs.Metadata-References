---
title: SpreadsheetInspectionPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Contiene información sobre partes de hojas de cálculo que pueden considerarse metadatos en algunos casos.
type: docs
weight: 1190
url: /es/net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/
---
## SpreadsheetInspectionPackage class

Contiene información sobre partes de hojas de cálculo que pueden considerarse metadatos en algunos casos.

```csharp
public sealed class SpreadsheetInspectionPackage : CustomPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Comments](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/comments) { get; } | Obtiene una matriz de los comentarios de los usuarios. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/digitalsignatures) { get; } | Obtiene una matriz de firmas digitales presentadas en el documento. |
| [HiddenSheets](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/hiddensheets) { get; } | Obtiene una matriz de las hojas ocultas. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [ClearComments](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/clearcomments)() | Elimina todos los comentarios de usuario detectados de la hoja de cálculo. |
| [ClearDigitalSignatures](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/cleardigitalsignatures)() | Elimina todas las firmas digitales detectadas de la hoja de cálculo. |
| [ClearHiddenSheets](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/clearhiddensheets)() | Elimina todas las hojas ocultas detectadas de la hoja de cálculo. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| override [Sanitize](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos en hojas de cálculo](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Spreadsheets)

### Ejemplos

Este ejemplo de código muestra cómo eliminar propiedades de inspección de una hoja de cálculo.

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    var root = metadata.GetRootPackage<SpreadsheetRootPackage>();

    root.InspectionPackage.ClearComments();
    root.InspectionPackage.ClearDigitalSignatures();
    root.InspectionPackage.ClearHiddenSheets();

    metadata.Save(Constants.OutputXlsx);
}
```

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
