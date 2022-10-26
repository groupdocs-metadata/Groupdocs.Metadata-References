---
title: XmpMediaManagementPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa el espacio de nombres de administración de medios XMP.
type: docs
weight: 3170
url: /es/net/groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/
---
## XmpMediaManagementPackage class

Representa el espacio de nombres de administración de medios XMP.

```csharp
public sealed class XmpMediaManagementPackage : XmpPackage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpMediaManagementPackage](xmpmediamanagementpackage)() | Inicializa una nueva instancia del[`XmpMediaManagementPackage`](../xmpmediamanagementpackage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DerivedFrom](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/derivedfrom) { get; set; } | Obtiene o establece la referencia al recurso del que se deriva. |
| [DocumentID](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/documentid) { get; set; } | Obtiene o establece el identificador común para todas las versiones y representaciones del recurso. |
| [History](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/history) { get; set; } | Obtiene o establece una matriz de acciones de alto nivel que resultaron en este recurso. |
| [Ingredients](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/ingredients) { get; set; } | Obtiene o establece las referencias a los recursos que se incorporaron, por inclusión o referencia, a este recurso. |
| [InstanceID](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/instanceid) { get; set; } | Obtiene o establece el identificador de una encarnación específica de un recurso, actualizado cada vez que se guarda el archivo. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [ManagedFrom](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/managedfrom) { get; set; } | Obtiene o establece la referencia al documento tal como estaba antes de ser administrado. |
| [Manager](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/manager) { get; set; } | Obtiene o establece el nombre del sistema de administración de activos que administra este recurso. |
| [ManagerVariant](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/managervariant) { get; set; } | Obtiene o establece la variante concreta del sistema de gestión de activos. |
| [ManageTo](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/manageto) { get; set; } | Obtiene o establece el URI que identifica el recurso gestionado para el sistema de gestión de activos |
| [ManageUI](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/manageui) { get; set; } | Obtiene o establece el URI que se puede usar para acceder a información sobre el recurso administrado a través de un navegador web. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Obtiene el URI del espacio de nombres. |
| [OriginalDocumentID](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/originaldocumentid) { get; set; } | Obtiene o establece el identificador común del recurso original del que se deriva el recurso actual. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Obtiene el prefijo xmlns. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [RenditionClass](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/renditionclass) { get; set; } | Obtiene o establece el nombre de la clase de representación para este recurso. |
| [RenditionParams](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/renditionparams) { get; set; } | Obtiene o establece el valor que se usa para proporcionar parámetros de representación adicionales que son demasiado complejos o detallados para codificarlos en xmpMM:RenditionClass. |
| [VersionID](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/versionid) { get; set; } | Obtiene o establece el identificador de la versión del documento para este recurso. |
| [Versions](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/versions) { get; set; } | Obtiene o establece el historial de versiones asociado con este recurso. |
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
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Establece el valor heredado de[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Establece el valor heredado de[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Establece el valor heredado de[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Ver también

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* espacio de nombres [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
