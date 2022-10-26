---
title: VCardCard
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa una sola tarjeta extraída de un archivo VCard.
type: docs
weight: 650
url: /es/net/groupdocs.metadata.formats.businesscard/vcardcard/
---
## VCardCard class

Representa una sola tarjeta extraída de un archivo VCard.

```csharp
public class VCardCard : VCardRecordset
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CalendarRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/calendarrecordset) { get; } | Obtiene los registros del calendario. |
| [CommunicationRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/communicationrecordset) { get; } | Obtiene los registros de comunicación. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DeliveryAddressingRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/deliveryaddressingrecordset) { get; } | Obtiene los registros de direcciones de entrega. |
| [ExplanatoryRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/explanatoryrecordset) { get; } | Obtiene los registros explicativos. |
| [ExtensionRecords](../../groupdocs.metadata.formats.businesscard/vcardcard/extensionrecords) { get; } | Obtiene los registros de la extensión privada. |
| [GeneralRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/generalrecordset) { get; } | Obtiene los registros generales. |
| [GeographicalRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/geographicalrecordset) { get; } | Obtiene los registros geográficos. |
| [IdentificationRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/identificationrecordset) { get; } | Obtiene los registros de identificación. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [OrganizationalRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/organizationalrecordset) { get; } | Obtiene los registros de la organización. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [SecurityRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/securityrecordset) { get; } | Obtiene los registros de seguridad. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| [FilterByGroup](../../groupdocs.metadata.formats.businesscard/vcardcard/filterbygroup)(string) | Filtra todos los registros de vCard por el nombre del grupo pasado como parámetro. Para obtener más información, consulte el método. |
| [FilterHomeTags](../../groupdocs.metadata.formats.businesscard/vcardcard/filterhometags)() | Filtra todos los registros vCard marcados con la etiqueta HOME. |
| [FilterPreferred](../../groupdocs.metadata.formats.businesscard/vcardcard/filterpreferred)() | Filtra los registros preferidos. |
| [FilterWorkTags](../../groupdocs.metadata.formats.businesscard/vcardcard/filterworktags)() | Filtra todos los registros vCard marcados con la etiqueta WORK. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetAvailableGroups](../../groupdocs.metadata.formats.businesscard/vcardcard/getavailablegroups)() | Obtiene los nombres de grupo disponibles. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos vCard](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Ejemplos

Este ejemplo muestra cómo usar los filtros de propiedad vCard.

```csharp
public static void Run()
{
    using (Metadata metadata = new Metadata(Constants.InputVcf))
    {
        var root = metadata.GetRootPackage<VCardRootPackage>();

        foreach (var vCard in root.VCardPackage.Cards)
        {
            // Imprimir los números de teléfono y correos electrónicos de trabajo preferidos
            var filtered = vCard.FilterWorkTags().FilterPreferred();
            PrintArray(filtered.CommunicationRecordset.Telephones);
            PrintArray(filtered.CommunicationRecordset.Emails);
        }
    }
}

private static void PrintArray(string[] values)
{
    if (values != null)
    {
        foreach (string value in values)
        {
            Console.WriteLine(value);
        }
    }
}
```

### Ver también

* class [VCardRecordset](../vcardrecordset)
* espacio de nombres [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
