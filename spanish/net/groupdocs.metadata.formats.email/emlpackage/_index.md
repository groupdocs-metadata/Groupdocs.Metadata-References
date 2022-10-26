---
title: EmlPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa metadatos de mensajes EML.
type: docs
weight: 1380
url: /es/net/groupdocs.metadata.formats.email/emlpackage/
---
## EmlPackage class

Representa metadatos de mensajes EML.

```csharp
public class EmlPackage : EmailPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AttachedFileNames](../../groupdocs.metadata.formats.email/emailpackage/attachedfilenames) { get; } | Obtiene una matriz de los nombres de los archivos adjuntos. |
| [BlindCarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/blindcarboncopyrecipients) { get; set; } | Obtiene o establece la matriz de destinatarios BCC (copia oculta) del mensaje de correo electrónico. |
| [CarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/carboncopyrecipients) { get; set; } | Obtiene o establece la matriz de destinatarios CC (copia carbón) del mensaje de correo electrónico. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Headers](../../groupdocs.metadata.formats.email/emailpackage/headers) { get; } | Obtiene un paquete de metadatos que contiene los encabezados de correo electrónico. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Recipients](../../groupdocs.metadata.formats.email/emailpackage/recipients) { get; set; } | Obtiene o establece la matriz de destinatarios de correo electrónico. |
| [Sender](../../groupdocs.metadata.formats.email/emailpackage/sender) { get; } | Obtiene la dirección de correo electrónico del remitente. |
| [Subject](../../groupdocs.metadata.formats.email/emailpackage/subject) { get; set; } | Obtiene o establece el asunto del correo electrónico. |

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
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con correos electrónicos guardados](https://docs.groupdocs.com/display/metadatanet/Working+with+saved+Emails)

### Ver también

* class [EmailPackage](../emailpackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Email](../../groupdocs.metadata.formats.email)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
