---
title: XmpResourceEvent
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa un evento de alto nivel que ocurrió en el procesamiento de un recurso.
type: docs
weight: 3540
url: /es/net/groupdocs.metadata.standards.xmp/xmpresourceevent/
---
## XmpResourceEvent class

Representa un evento de alto nivel que ocurrió en el procesamiento de un recurso.

```csharp
public sealed class XmpResourceEvent : XmpComplexType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpResourceEvent](xmpresourceevent)() | Inicializa una nueva instancia del[`XmpResourceEvent`](../xmpresourceevent) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Action](../../groupdocs.metadata.standards.xmp/xmpresourceevent/action) { get; set; } | Obtiene o establece la acción que ocurrió. |
| [Changed](../../groupdocs.metadata.standards.xmp/xmpresourceevent/changed) { get; set; } | Obtiene o establece una lista delimitada por punto y coma de las partes del recurso que se modificaron desde el historial de eventos anterior. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [InstanceID](../../groupdocs.metadata.standards.xmp/xmpresourceevent/instanceid) { get; set; } | Obtiene o establece el valor de la propiedad xmpMM:InstanceID para el recurso modificado (salida). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Obtiene los URI de espacio de nombres que se usan en el[`XmpComplexType`](../xmpcomplextype) instancia. |
| [Parameters](../../groupdocs.metadata.standards.xmp/xmpresourceevent/parameters) { get; set; } | Obtiene o establece la descripción adicional de la acción. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Obtiene los prefijos de espacio de nombres que se utilizan en el[`XmpComplexType`](../xmpcomplextype) instancia. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [SoftwareAgent](../../groupdocs.metadata.standards.xmp/xmpresourceevent/softwareagent) { get; set; } | Obtiene o establece el agente de software que realizó la acción. |
| [When](../../groupdocs.metadata.standards.xmp/xmpresourceevent/when) { get; set; } | Obtiene o establece la marca de tiempo de cuando ocurrió la acción. |

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
