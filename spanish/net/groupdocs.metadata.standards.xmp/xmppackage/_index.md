---
title: XmpPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa la abstracción base para el paquete XMP.
type: docs
weight: 3490
url: /es/net/groupdocs.metadata.standards.xmp/xmppackage/
---
## XmpPackage class

Representa la abstracción base para el paquete XMP.

```csharp
public class XmpPackage : XmpMetadataContainer
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpPackage](xmppackage)(string, string) | Inicializa una nueva instancia del[`XmpPackage`](../xmppackage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Obtiene el URI del espacio de nombres. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Obtiene el prefijo xmlns. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Obtiene el espacio de nombres XML. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Elimina todas las propiedades XMP. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Convierte el valor XMP a la representación XML. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Elimina la propiedad con el nombre especificado. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set)(string, bool) | Establece la propiedad booleana. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_6)(string, DateTime) | ConjuntosDateTime propiedad. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_1)(string, double) | Establece doble propiedad. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_5)(string, int) | Establece propiedad de número entero. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_7)(string, string) | Establece la propiedad de la cadena. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_2)(string, XmpArray) | Establece el valor heredado de[`XmpArray`](../xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_3)(string, XmpComplexType) | Establece el valor heredado de[`XmpComplexType`](../xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_4)(string, XmpValueBase) | Establece el valor heredado de[`XmpValueBase`](../xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos XMP](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Ejemplos

Este ejemplo demuestra cómo agregar un paquete XMP personalizado a un archivo de cualquier formato compatible.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IXmp root = metadata.GetRootPackage() as IXmp;
    if (root != null)
    {
        var packet = new XmpPacketWrapper();

        var custom = new XmpPackage("gd", "https://groupdocs.com");
        custom.Set("gd:Copyright", "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.");
        custom.Set("gd:CreationDate", DateTime.Today);
        custom.Set("gd:Company", XmpArray.From(new [] { "Aspose", "GroupDocs" }, XmpArrayType.Ordered));

        packet.AddPackage(custom);
        root.XmpPackage = packet;

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Ver también

* class [XmpMetadataContainer](../xmpmetadatacontainer)
* espacio de nombres [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
