---
title: IptcEnvelopeRecord
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa un registro de sobre IPTC.
type: docs
weight: 2910
url: /es/net/groupdocs.metadata.standards.iptc/iptcenveloperecord/
---
## IptcEnvelopeRecord class

Representa un registro de sobre IPTC.

```csharp
public sealed class IptcEnvelopeRecord : IptcRecord
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [IptcEnvelopeRecord](iptcenveloperecord)() | Inicializa una nueva instancia del[`IptcEnvelopeRecord`](../iptcenveloperecord) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DateSent](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/datesent) { get; set; } | Obtiene o establece la fecha en que el servicio envió el material. |
| [Destination](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/destination) { get; set; } | Obtiene o establece el destino. |
| [Destinations](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/destinations) { get; set; } | Obtiene o establece una matriz de destinos. |
| [FileFormat](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/fileformat) { get; set; } | Obtiene o establece el formato del archivo. |
| [FileFormatVersion](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/fileformatversion) { get; set; } | Obtiene o establece la versión del formato de archivo. Un número que representa la versión particular del formato de archivo especificado en[`FileFormat`](./fileformat) . |
| [Item](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/item) { get; } | Obtiene el[`IptcDataSet`](../iptcdataset) con el número especificado. (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [ModelVersion](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/modelversion) { get; set; } | Obtiene o establece un número que identifica la versión de la información. |
| [ProductID](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/productid) { get; set; } | Obtiene o establece el identificador del producto. |
| [ProductIds](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/productids) { get; set; } | Obtiene o establece los identificadores del producto. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [RecordNumber](../../groupdocs.metadata.standards.iptc/iptcrecord/recordnumber) { get; } | Obtiene el número de registro. |
| [ServiceIdentifier](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/serviceidentifier) { get; set; } | Obtiene o establece el identificador del servicio. |

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
| [ToList](../../groupdocs.metadata.standards.iptc/iptcrecord/tolist)() | Crea una lista a partir del paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos IPTC IIM](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Ver también

* class [IptcRecord](../iptcrecord)
* espacio de nombres [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
