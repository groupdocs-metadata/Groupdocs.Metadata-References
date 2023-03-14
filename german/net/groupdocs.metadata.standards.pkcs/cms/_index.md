---
title: Cms
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt ein digitales Zeichen dar das mit Cryptographic Message Syntax CMS erstellt wurde  dem IETFStandard für kryptografisch geschützte Nachrichten. CMS basiert auf der Syntax von PKCS 7 spezifiziert in RFC 5652. Siehe bittehttps//tools.ietf.org/html/rfc5652https//tools.ietf.org/html/rfc5652 für weitere Informationen.
type: docs
weight: 2960
url: /de/net/groupdocs.metadata.standards.pkcs/cms/
---
## Cms class

Stellt ein digitales Zeichen dar, das mit Cryptographic Message Syntax (CMS) erstellt wurde – dem IETF-Standard für kryptografisch geschützte Nachrichten. CMS basiert auf der Syntax von PKCS #7, spezifiziert in RFC 5652. Siehe bitte[https://tools.ietf.org/html/rfc5652](https://tools.ietf.org/html/rfc5652) für weitere Informationen.

```csharp
public class Cms : DigitalSignature
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CertificateRawData](../../groupdocs.metadata.standards.signing/digitalsignature/certificaterawdata) { get; } | Ruft die Rohdaten des Zertifikats ab. |
| [Certificates](../../groupdocs.metadata.standards.pkcs/cms/certificates) { get; } | Ruft die Sammlung von Zertifikaten ab. |
| [CertificateSubject](../../groupdocs.metadata.standards.signing/digitalsignature/certificatesubject) { get; } | Ruft den Distinguished Name des Antragstellers von einem Zertifikat ab. |
| [Comments](../../groupdocs.metadata.standards.signing/digitalsignature/comments) { get; } | Ruft den Kommentar zum Signierungszweck ab. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [DigestAlgorithms](../../groupdocs.metadata.standards.pkcs/cms/digestalgorithms) { get; } | Ruft das Array der Message-Digest-Algorithmus-IDs ab. Die Sammlung kann beliebig viele Elemente enthalten, einschließlich null. |
| [EncapsulatedContent](../../groupdocs.metadata.standards.pkcs/cms/encapsulatedcontent) { get; } | Ruft den signierten Inhalt ab, der aus einer Inhaltstypkennung und dem Inhalt selbst besteht. |
| virtual [IsValid](../../groupdocs.metadata.standards.signing/digitalsignature/isvalid) { get; } | Ruft einen Wert ab, der angibt, ob die Signatur gültig ist. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [Signers](../../groupdocs.metadata.standards.pkcs/cms/signers) { get; } | Ruft die Sammlung von Informationspaketen pro Unterzeichner ab. |
| override [SignTime](../../groupdocs.metadata.standards.pkcs/cms/signtime) { get; } | Ruft die Uhrzeit ab, zu der der Unterzeichner (angeblich) den Signiervorgang durchgeführt hat. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Siehe auch

* class [DigitalSignature](../../groupdocs.metadata.standards.signing/digitalsignature)
* namensraum [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
