---
title: CadRootPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa el paquete raíz que permite trabajar con metadatos en un dibujo CAD.
type: docs
weight: 850
url: /es/net/groupdocs.metadata.formats.cad/cadrootpackage/
---
## CadRootPackage class

Representa el paquete raíz que permite trabajar con metadatos en un dibujo CAD.

```csharp
public abstract class CadRootPackage : RootMetadataPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CadPackage](../../groupdocs.metadata.formats.cad/cadrootpackage/cadpackage) { get; } | Obtiene el paquete de metadatos de CAD. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Obtiene el paquete de metadatos del tipo de archivo. |
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
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos CAD](https://docs.groupdocs.com/display/metadatanet/Working+with+CAD+metadata)

### Ejemplos

Este ejemplo de código muestra cómo leer los metadatos de un dibujo CAD.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDxf))
{
    var root = metadata.GetRootPackage<CadRootPackage>();

    Console.WriteLine(root.CadPackage.AcadVersion);
    Console.WriteLine(root.CadPackage.Author);
    Console.WriteLine(root.CadPackage.Comments);
    Console.WriteLine(root.CadPackage.CreatedDateTime);
    Console.WriteLine(root.CadPackage.HyperlinkBase);
    Console.WriteLine(root.CadPackage.Keywords);
    Console.WriteLine(root.CadPackage.LastSavedBy);
    Console.WriteLine(root.CadPackage.Title);

    // ...
}
```

### Ver también

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Cad](../../groupdocs.metadata.formats.cad)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
