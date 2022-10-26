---
title: XmpDublinCorePackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa el esquema Dublin Core.
type: docs
weight: 3120
url: /es/net/groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/
---
## XmpDublinCorePackage class

Representa el esquema Dublin Core.

```csharp
public sealed class XmpDublinCorePackage : XmpPackage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpDublinCorePackage](xmpdublincorepackage)() | Inicializa una nueva instancia del[`XmpDublinCorePackage`](../xmpdublincorepackage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Contributors](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/contributors) { get; set; } | Obtiene o establece una matriz de los contribuyentes. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Coverage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/coverage) { get; set; } | Obtiene o establece la extensión o el ámbito del recurso. |
| [Creators](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/creators) { get; set; } | Obtiene o establece una matriz de los creadores. |
| [Dates](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/dates) { get; set; } | Obtiene o establece una matriz de fechas asociadas con un evento en el ciclo de vida del recurso. |
| [Descriptions](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/descriptions) { get; set; } | Obtiene o establece una matriz de descripciones textuales del contenido del recurso, en varios idiomas. |
| [Format](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/format) { get; set; } | Obtiene o establece el tipo MIME del recurso. |
| [Identifier](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/identifier) { get; set; } | Obtiene o establece un valor de cadena que representa una referencia inequívoca al recurso dentro de un contexto dado. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Languages](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/languages) { get; set; } | Obtiene o establece una matriz de idiomas utilizados en el contenido del recurso. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Obtiene el URI del espacio de nombres. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Obtiene el prefijo xmlns. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Publishers](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/publishers) { get; set; } | Obtiene o establece una matriz de editores que pusieron a disposición el recurso. |
| [Relations](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/relations) { get; set; } | Obtiene o establece una matriz de los recursos relacionados. |
| [Rights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/rights) { get; set; } | Obtiene o establece una matriz de declaraciones de derechos informales, dadas en varios idiomas. |
| [Source](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/source) { get; set; } | Obtiene o establece el recurso relacionado del que se deriva el recurso descrito. |
| [Subjects](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/subjects) { get; set; } | Obtiene o establece una matriz de frases descriptivas o palabras clave que especifican el contenido del recurso. |
| [Titles](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/titles) { get; set; } | Obtiene o establece el título o nombre del recurso, dado en varios idiomas. |
| [Types](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/types) { get; set; } | Obtiene o establece una matriz de valores de cadena que representan la naturaleza o el género del recurso. |
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
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, string) | Establece la propiedad de la cadena. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/set#set_2)(string, XmpArray) | Establece el valor heredado de[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Establece el valor heredado de[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Establece el valor heredado de[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetContributor](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcontributor)(string) | Establece un único contribuyente del recurso. |
| [SetCreator](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcreator)(string) | Establece un solo creador del recurso. |
| [SetDate](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdate)(DateTime) | Establece una única fecha asociada al recurso. |
| [SetDescription](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdescription)(string) | Establece la descripción del recurso, dada en un solo idioma. |
| [SetLanguage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setlanguage)(string) | Establece un único idioma asociado al recurso. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [SetPublisher](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setpublisher)(string) | Establece un único editor del recurso. |
| [SetRelation](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrelation)(string) | Establece un solo recurso relacionado. |
| [SetRights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrights)(string) | Establece los derechos de los recursos, dados en un solo idioma. |
| [SetSubject](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setsubject)(string) | Establece un único asunto del recurso. |
| [SetTitle](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settitle)(string) | Establece el título del recurso, dado en un solo idioma. |
| [SetType](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settype)(string) | Establece un único tipo de recurso. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

Para obtener más información, consulte: http://dublincore.org/documents/usageguide/elements.shtml.

### Ver también

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* espacio de nombres [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
