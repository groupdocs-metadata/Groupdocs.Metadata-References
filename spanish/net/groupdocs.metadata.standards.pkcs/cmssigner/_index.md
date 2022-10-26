---
title: CmsSigner
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa información de CMS por firmante.
type: docs
weight: 3010
url: /es/net/groupdocs.metadata.standards.pkcs/cmssigner/
---
## CmsSigner class

Representa información de CMS por firmante.

```csharp
public class CmsSigner : CustomPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DigestAlgorithm](../../groupdocs.metadata.standards.pkcs/cmssigner/digestalgorithm) { get; } | Obtiene el algoritmo de resumen del mensaje y cualquier parámetro asociado, utilizado por el firmante. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [SignatureAlgorithm](../../groupdocs.metadata.standards.pkcs/cmssigner/signaturealgorithm) { get; } | Obtiene el algoritmo de firma y los parámetros asociados que utiliza el firmante para generar la firma digital. |
| [SignatureValue](../../groupdocs.metadata.standards.pkcs/cmssigner/signaturevalue) { get; } | Obtiene el resultado de la generación de la firma digital, utilizando el resumen del mensaje y la clave privada del firmante. |
| [SignedAttributes](../../groupdocs.metadata.standards.pkcs/cmssigner/signedattributes) { get; } | Obtiene la colección de atributos que están firmados. |
| [SignerIdentifier](../../groupdocs.metadata.standards.pkcs/cmssigner/signeridentifier) { get; } | Obtiene los datos sin procesar del certificado del firmante (y, por lo tanto, la clave pública del firmante). |
| [SigningTime](../../groupdocs.metadata.standards.pkcs/cmssigner/signingtime) { get; } | Obtiene la hora a la que el firmante (supuestamente) realizó el proceso de firma. |
| [UnsignedAttributes](../../groupdocs.metadata.standards.pkcs/cmssigner/unsignedattributes) { get; } | Obtiene la colección de atributos que no están firmados. |

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

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
