---
title: IptcApplicationRecord
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa un registro de aplicación IPTC.
type: docs
weight: 2880
url: /es/net/groupdocs.metadata.standards.iptc/iptcapplicationrecord/
---
## IptcApplicationRecord class

Representa un registro de aplicación IPTC.

```csharp
public sealed class IptcApplicationRecord : IptcRecord
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [IptcApplicationRecord](iptcapplicationrecord)() | Inicializa una nueva instancia del[`IptcApplicationRecord`](../iptcapplicationrecord) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AllKeywords](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/allkeywords) { get; set; } | Obtiene o establece las palabras clave. |
| [ByLine](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/byline) { get; set; } | Obtiene o establece el nombre del creador del objeto, por ejemplo, escritor, fotógrafo o artista gráfico. |
| [ByLines](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylines) { get; set; } | Obtiene o establece los nombres de los creadores del objeto, por ejemplo, escritor, fotógrafo o artista gráfico. |
| [ByLineTitle](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylinetitle) { get; set; } | Obtiene o establece el título del creador o creadores del objeto. |
| [ByLineTitles](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylinetitles) { get; set; } | Obtiene o establece los títulos del creador o creadores del objeto. |
| [CaptionAbstract](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/captionabstract) { get; set; } | Obtiene o establece una descripción textual del objeto, especialmente cuando el objeto no es texto. |
| [City](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/city) { get; set; } | Obtiene o establece la ciudad. |
| [Contact](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contact) { get; set; } | Obtiene o establece información sobre la persona u organización que puede proporcionar más antecedentes sobre el objeto. |
| [Contacts](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contacts) { get; set; } | Obtiene o establece información sobre la persona u organización que puede proporcionar más antecedentes sobre el objeto. |
| [ContentLocationCode](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationcode) { get; set; } | Obtiene o establece el código de ubicación del contenido. |
| [ContentLocationCodes](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationcodes) { get; set; } | Obtiene o establece los códigos de ubicación del contenido. |
| [ContentLocationName](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationname) { get; set; } | Obtiene o establece el nombre de la ubicación del contenido. |
| [ContentLocationNames](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationnames) { get; set; } | Obtiene o establece los nombres de ubicación del contenido. |
| [CopyrightNotice](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/copyrightnotice) { get; set; } | Obtiene o establece el aviso de copyright. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Credit](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/credit) { get; set; } | Obtiene o establece información sobre el proveedor del objeto, no necesariamente el propietario/creador. |
| [DateCreated](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/datecreated) { get; set; } | Obtiene o establece la fecha en que se creó el contenido intelectual del objeto. |
| [Headline](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/headline) { get; set; } | Obtiene o establece una entrada publicable que proporciona una sinopsis del contenido del objeto. |
| [Item](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/item) { get; } | Obtiene el[`IptcDataSet`](../iptcdataset) con el número especificado. (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Keywords](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/keywords) { get; set; } | Obtiene o establece las palabras clave. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [ProgramVersion](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/programversion) { get; set; } | Obtiene o establece la versión del programa. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [RecordNumber](../../groupdocs.metadata.standards.iptc/iptcrecord/recordnumber) { get; } | Obtiene el número de registro. |
| [ReferenceDate](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/referencedate) { get; set; } | Obtiene o establece la fecha de un sobre anterior al que hace referencia el objeto actual. |
| [ReferenceDates](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/referencedates) { get; } | Obtiene las fechas de un sobre anterior al que hace referencia el objeto actual. |
| [ReleaseDate](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/releasedate) { get; set; } | Obtiene o establece la fecha de lanzamiento. |

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
