---
title: Cms
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa un signo digital creado con la sintaxis de mensajes criptográficos CMS el estándar de IETF para mensajes protegidos criptográficamente. CMS se basa en la sintaxis de PKCS 7 especificada en RFC 5652. Consultehttps//tools.ietf.org/html/rfc5652https//tools.ietf.org/html/rfc5652 para más información.
type: docs
weight: 2960
url: /es/net/groupdocs.metadata.standards.pkcs/cms/
---
## Cms class

Representa un signo digital creado con la sintaxis de mensajes criptográficos (CMS), el estándar de IETF para mensajes protegidos criptográficamente. CMS se basa en la sintaxis de PKCS #7, especificada en RFC 5652. Consulte[https://tools.ietf.org/html/rfc5652](https://tools.ietf.org/html/rfc5652) para más información.

```csharp
public class Cms : DigitalSignature
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CertificateRawData](../../groupdocs.metadata.standards.signing/digitalsignature/certificaterawdata) { get; } | Obtiene los datos sin procesar del certificado. |
| [Certificates](../../groupdocs.metadata.standards.pkcs/cms/certificates) { get; } | Obtiene la colección de certificados. |
| [CertificateSubject](../../groupdocs.metadata.standards.signing/digitalsignature/certificatesubject) { get; } | Obtiene el nombre distinguido del sujeto de un certificado. |
| [Comments](../../groupdocs.metadata.standards.signing/digitalsignature/comments) { get; } | Obtiene el comentario de propósito de firma. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DigestAlgorithms](../../groupdocs.metadata.standards.pkcs/cms/digestalgorithms) { get; } | Obtiene la matriz de identificadores de algoritmo de resumen de mensaje. Puede haber cualquier número de elementos en la colección, incluido cero. |
| [EncapsulatedContent](../../groupdocs.metadata.standards.pkcs/cms/encapsulatedcontent) { get; } | Obtiene el contenido firmado, que consta de un identificador de tipo de contenido y el propio contenido. |
| virtual [IsValid](../../groupdocs.metadata.standards.signing/digitalsignature/isvalid) { get; } | Obtiene un valor que indica si la firma es válida. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Signers](../../groupdocs.metadata.standards.pkcs/cms/signers) { get; } | Obtiene la recopilación de paquetes de información por firmante. |
| override [SignTime](../../groupdocs.metadata.standards.pkcs/cms/signtime) { get; } | Obtiene la hora a la que el firmante (supuestamente) realizó el proceso de firma. |

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

### Ver también

* class [DigitalSignature](../../groupdocs.metadata.standards.signing/digitalsignature)
* espacio de nombres [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
