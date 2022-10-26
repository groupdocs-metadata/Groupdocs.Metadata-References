---
title: IptcRecordSet
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa una colección de registros IPTC.
type: docs
weight: 2940
url: /es/net/groupdocs.metadata.standards.iptc/iptcrecordset/
---
## IptcRecordSet class

Representa una colección de registros IPTC.

```csharp
public sealed class IptcRecordSet : CustomPackage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [IptcRecordSet](iptcrecordset#constructor)() | Inicializa una nueva instancia del[`IptcRecordSet`](../iptcrecordset) clase. |
| [IptcRecordSet](iptcrecordset#constructor_1)(IptcDataSet[]) | Inicializa una nueva instancia del[`IptcRecordSet`](../iptcrecordset) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ApplicationRecord](../../groupdocs.metadata.standards.iptc/iptcrecordset/applicationrecord) { get; set; } | Obtiene o establece el Registro de la aplicación. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [EnvelopeRecord](../../groupdocs.metadata.standards.iptc/iptcrecordset/enveloperecord) { get; set; } | Obtiene o establece el Registro de Sobre. |
| [Item](../../groupdocs.metadata.standards.iptc/iptcrecordset/item) { get; } | Obtiene el[`IptcRecord`](../iptcrecord) con el número especificado. (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../groupdocs.metadata.standards.iptc/iptcrecordset/add)(IptcDataSet) | Agrega el conjunto de datos especificado al registro apropiado. El conjunto de datos se considera repetible si ya existe un conjunto de datos con el número especificado. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Clear](../../groupdocs.metadata.standards.iptc/iptcrecordset/clear)() | Elimina todos los registros de la colección. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [Remove](../../groupdocs.metadata.standards.iptc/iptcrecordset/remove#remove)(byte) | Elimina el registro con el número de registro especificado. |
| [Remove](../../groupdocs.metadata.standards.iptc/iptcrecordset/remove#remove_1)(byte, byte) | Elimina el conjunto de datos con el registro y el número de conjunto de datos especificados. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Set](../../groupdocs.metadata.standards.iptc/iptcrecordset/set)(IptcDataSet) | Agrega o actualiza el conjunto de datos especificado en el registro correspondiente. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [ToDataSetList](../../groupdocs.metadata.standards.iptc/iptcrecordset/todatasetlist)() | Crea una lista de conjuntos de datos del paquete. |
| [ToList](../../groupdocs.metadata.standards.iptc/iptcrecordset/tolist)() | Crea una lista a partir del paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos IPTC IIM](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Ejemplos

Este ejemplo de código muestra las propiedades básicas de metadatos de IPTC para actualizar.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IIptc root = metadata.GetRootPackage() as IIptc;
    if (root != null)
    {
        // Establecer el paquete IPTC si falta
        if (root.IptcPackage == null)
        {
            root.IptcPackage = new IptcRecordSet();
        }

        if (root.IptcPackage.EnvelopeRecord == null)
        {
            root.IptcPackage.EnvelopeRecord = new IptcEnvelopeRecord();
        }

        root.IptcPackage.EnvelopeRecord.DateSent = DateTime.Now;
        root.IptcPackage.EnvelopeRecord.ProductID = Guid.NewGuid().ToString();

        // ...

        if (root.IptcPackage.ApplicationRecord == null)
        {
            root.IptcPackage.ApplicationRecord = new IptcApplicationRecord();
        }

        root.IptcPackage.ApplicationRecord.ByLine = "GroupDocs";
        root.IptcPackage.ApplicationRecord.Headline = "test";
        root.IptcPackage.ApplicationRecord.ByLineTitle = "code sample";
        root.IptcPackage.ApplicationRecord.ReleaseDate = DateTime.Today;

        // ...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
