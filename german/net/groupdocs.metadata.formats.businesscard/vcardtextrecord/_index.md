---
title: VCardTextRecord
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Repräsentiert die vCardTextdatensatzMetadatenklasse.
type: docs
weight: 810
url: /de/net/groupdocs.metadata.formats.businesscard/vcardtextrecord/
---
## VCardTextRecord class

Repräsentiert die vCard-Textdatensatz-Metadatenklasse.

```csharp
public class VCardTextRecord : VCardRecord
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AltIdParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/altidparameter) { get; } | Ruft den Parameterwert für alternative Darstellungen ab. |
| [AnonymParameters](../../groupdocs.metadata.formats.businesscard/vcardrecord/anonymparameters) { get; } | Ruft die anonymen Parameter ab. |
| [CharsetParameter](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/charsetparameter) { get; } | Ruft den Zeichensatzparameter ab. |
| override [ContentType](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/contenttype) { get; } | Ruft den Inhaltstyp des Datensatzes ab. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [EncodingParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/encodingparameter) { get; } | Ruft den Kodierungsparameterwert ab. |
| [Group](../../groupdocs.metadata.formats.businesscard/vcardrecord/group) { get; } | Ruft den Gruppierungswert ab. |
| [IsQuotedPrintable](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/isquotedprintable) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz eine druckbare Zeichenfolge in Anführungszeichen ist. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [LanguageParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/languageparameter) { get; } | Ruft den Sprachparameterwert ab. |
| [MediaTypeParameter](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/mediatypeparameter) { get; } | Ruft den Medientyp-Parameterwert ab. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [PrefParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/prefparameter) { get; } | Ruft den bevorzugten Parameter ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [TypeName](../../groupdocs.metadata.formats.businesscard/vcardrecord/typename) { get; } | Ruft den Typ des Datensatzes ab. |
| [TypeParameters](../../groupdocs.metadata.formats.businesscard/vcardrecord/typeparameters) { get; } | Ruft die Typparameterwerte ab. |
| [Value](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/value) { get; } | Ruft den Datensatzwert ab. |
| [ValueParameters](../../groupdocs.metadata.formats.businesscard/vcardrecord/valueparameters) { get; } | Ruft die Wertparameter ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [GetReadabilityValue](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/getreadabilityvalue)(string) | Ruft den Lesbarkeitswert ab. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Bemerkungen

**Erfahren Sie mehr**

* [Arbeiten mit vCard-Metadaten](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Siehe auch

* class [VCardRecord](../vcardrecord)
* namensraum [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
