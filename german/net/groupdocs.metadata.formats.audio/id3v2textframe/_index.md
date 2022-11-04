---
title: ID3V2TextFrame
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Repräsentiert einen Textrahmen in einemID3V2Tag./id3v2tag . Fast alle Frames die mit dem TZeichen beginnen fallen in diese Kategorie. Es gibt nur eine Ausnahme nämlich den TXXXFrame der durch dargestellt wirdID3V2UserDefinedFrame./id3v2userdefinedframe Klasse.
type: docs
weight: 520
url: /de/net/groupdocs.metadata.formats.audio/id3v2textframe/
---
## ID3V2TextFrame class

Repräsentiert einen Textrahmen in einem[`ID3V2Tag`](../id3v2tag) . Fast alle Frames, die mit dem T-Zeichen beginnen, fallen in diese Kategorie. Es gibt nur eine Ausnahme, nämlich den TXXX-Frame, der durch dargestellt wird[`ID3V2UserDefinedFrame`](../id3v2userdefinedframe) Klasse.

```csharp
public class ID3V2TextFrame : ID3V2TagFrame
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ID3V2TextFrame](id3v2textframe)(string, ID3V2EncodingType, string) | Initialisiert eine neue Instanz von[`ID3V2TextFrame`](../id3v2textframe) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [Data](../../groupdocs.metadata.formats.audio/id3v2tagframe/data) { get; } | Ruft die Rahmendaten ab. |
| [Flags](../../groupdocs.metadata.formats.audio/id3v2tagframe/flags) { get; } | Ruft die Frame-Flags ab. |
| [Id](../../groupdocs.metadata.formats.audio/id3v2tagframe/id) { get; } | Ruft die ID des Frames ab (vier Zeichen, die dem Muster [A-Z0-9] entsprechen). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [Text](../../groupdocs.metadata.formats.audio/id3v2textframe/text) { get; } | Ruft den Textwert ab. |
| [TextEncoding](../../groupdocs.metadata.formats.audio/id3v2textframe/textencoding) { get; } | Ruft die Textcodierung ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Bemerkungen

**Mehr erfahren**

* [Umgang mit dem ID3v2-Tag](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Siehe auch

* class [ID3V2TagFrame](../id3v2tagframe)
* namensraum [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
