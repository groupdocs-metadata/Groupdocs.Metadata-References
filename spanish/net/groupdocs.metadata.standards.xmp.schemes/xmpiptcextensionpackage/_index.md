---
title: XmpIptcExtensionPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa el paquete XMP de la extensión IPTC.
type: docs
weight: 3150
url: /es/net/groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/
---
## XmpIptcExtensionPackage class

Representa el paquete XMP de la extensión IPTC.

```csharp
public sealed class XmpIptcExtensionPackage : XmpPackage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpIptcExtensionPackage](xmpiptcextensionpackage)() | Inicializa una nueva instancia del[`XmpIptcExtensionPackage`](../xmpiptcextensionpackage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AdditionalModelInformation](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/additionalmodelinformation) { get; set; } | Obtiene o establece la información sobre el origen étnico y otras facetas de los modelos en una imagen publicada por el modelo. |
| [AgesOfModels](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/agesofmodels) { get; set; } | Obtiene o establece las edades de los modelos humanos en el momento en que se tomó esta imagen en una imagen publicada del modelo. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DigitalImageGuid](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/digitalimageguid) { get; set; } | Obtiene o establece el identificador único global para esta imagen digital. |
| [DigitalSourceType](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/digitalsourcetype) { get; set; } | Obtiene o establece el tipo de fuente de esta imagen digital. |
| [Event](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/event) { get; set; } | Obtiene o establece la descripción del evento específico en el que se tomó la foto. |
| [IptcLastEdited](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/iptclastedited) { get; set; } | Obtiene o establece la fecha y, opcionalmente, la hora en que se editó por última vez cualquiera de los campos de metadatos de la foto IPTC. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MaxAvailableHeight](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/maxavailableheight) { get; set; } | Obtiene o establece la altura máxima disponible en píxeles de la foto original de la que se deriva esta foto al reducir el tamaño. |
| [MaxAvailableWidth](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/maxavailablewidth) { get; set; } | Obtiene o establece el ancho máximo disponible en píxeles de la foto original de la que se deriva esta foto al reducir el tamaño. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Obtiene el URI del espacio de nombres. |
| [OrganisationInImageCodes](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/organisationinimagecodes) { get; set; } | Obtiene o establece códigos de un vocabulario controlado para identificar las organizaciones o empresas que aparecen en la imagen. |
| [OrganisationInImageNames](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/organisationinimagenames) { get; set; } | Obtiene o establece los nombres de las organizaciones o empresas que aparecen en la imagen. |
| [PersonsInImage](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/personsinimage) { get; set; } | Obtiene o establece los nombres de las personas de las que trata el contenido del elemento. |
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
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Establece la propiedad booleana. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | ConjuntosDateTime propiedad. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Establece doble propiedad. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Establece propiedad de número entero. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/set#set_7)(string, string) | Establece la propiedad de la cadena. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/set#set_2)(string, XmpArray) | Establece el valor heredado de[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Establece el valor heredado de[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Establece el valor heredado de[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Ver también

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* espacio de nombres [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
