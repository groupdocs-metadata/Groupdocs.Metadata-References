---
title: XmpResourceRef
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa una referencia de varias partes a un recurso. Se utiliza para indicar versiones anteriores originales de copias originales de documentos derivados etc.
type: docs
weight: 3550
url: /es/net/groupdocs.metadata.standards.xmp/xmpresourceref/
---
## XmpResourceRef class

Representa una referencia de varias partes a un recurso. Se utiliza para indicar versiones anteriores, originales de copias, originales de documentos derivados, etc.

```csharp
public sealed class XmpResourceRef : XmpComplexType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpResourceRef](xmpresourceref)() | Inicializa una nueva instancia del[`XmpResourceRef`](../xmpresourceref) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternatePaths](../../groupdocs.metadata.standards.xmp/xmpresourceref/alternatepaths) { get; set; } | Obtiene o establece las direcciones URL o las rutas de archivo de respaldo del recurso al que se hace referencia. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DocumentID](../../groupdocs.metadata.standards.xmp/xmpresourceref/documentid) { get; set; } | Obtiene o establece el valor de la propiedad xmpMM:DocumentID del recurso al que se hace referencia. |
| [FilePath](../../groupdocs.metadata.standards.xmp/xmpresourceref/filepath) { get; set; } | Obtiene o establece la URL o la ruta del archivo del recurso al que se hace referencia. |
| [InstanceID](../../groupdocs.metadata.standards.xmp/xmpresourceref/instanceid) { get; set; } | Obtiene o establece el valor de la propiedad xmpMM:InstanceID del recurso al que se hace referencia. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [LastModifyDate](../../groupdocs.metadata.standards.xmp/xmpresourceref/lastmodifydate) { get; set; } | Obtiene o establece el valor de stEvt:cuando fue la última vez que se escribió el archivo. |
| [Manager](../../groupdocs.metadata.standards.xmp/xmpresourceref/manager) { get; set; } | Obtiene o establece el xmpMM:Manager del recurso al que se hace referencia. |
| [ManagerVariant](../../groupdocs.metadata.standards.xmp/xmpresourceref/managervariant) { get; set; } | Obtiene o establece el xmpMM:Manager del recurso al que se hace referencia. |
| [ManageTo](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageto) { get; set; } | Obtiene o establece el xmpMM:ManageTo del recurso al que se hace referencia. |
| [ManageUI](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageui) { get; set; } | Obtiene o establece el xmpMM:ManageUI. del recurso al que se hace referencia |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Obtiene los URI de espacio de nombres que se usan en el[`XmpComplexType`](../xmpcomplextype) instancia. |
| [PartMapping](../../groupdocs.metadata.standards.xmp/xmpresourceref/partmapping) { get; set; } | Obtiene o establece el nombre o URI de una función de asignación utilizada para asignar fromPart a toPart. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Obtiene los prefijos de espacio de nombres que se utilizan en el[`XmpComplexType`](../xmpcomplextype) instancia. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [RenditionClass](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionclass) { get; set; } | Obtiene o establece el valor de la propiedad xmpMM:RenditionClass del recurso al que se hace referencia. |
| [RenditionParams](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionparams) { get; set; } | Obtiene o establece el valor de la propiedad xmpMM:RenditionParams del recurso al que se hace referencia. |
| [VersionID](../../groupdocs.metadata.standards.xmp/xmpresourceref/versionid) { get; set; } | Obtiene o establece el valor de la propiedad xmpMM:RenditionParams del recurso al que se hace referencia. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | Obtiene el URI del espacio de nombres asociado con el prefijo especificado. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | Devuelve el valor contenido en la cadena en formato XMP. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | Devuelve unString que representa esta instancia. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Ver también

* class [XmpComplexType](../xmpcomplextype)
* espacio de nombres [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
