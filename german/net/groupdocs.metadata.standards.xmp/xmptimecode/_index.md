---
title: XmpTimecode
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt einen TimecodeWert in einem Video dar.
type: docs
weight: 3600
url: /de/net/groupdocs.metadata.standards.xmp/xmptimecode/
---
## XmpTimecode class

Stellt einen Timecode-Wert in einem Video dar.

```csharp
public sealed class XmpTimecode : XmpComplexType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [XmpTimecode](xmptimecode#constructor)() | Initialisiert eine neue Instanz von[`XmpTimecode`](../xmptimecode) Klasse. |
| [XmpTimecode](xmptimecode#constructor_1)(XmpTimeFormat, string) | Initialisiert eine neue Instanz von[`XmpTimecode`](../xmptimecode) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Ruft die Namespace-URIs ab, die in verwendet werden[`XmpComplexType`](../xmpcomplextype) Instanz. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Ruft die Namespace-Präfixe ab, die in verwendet werden[`XmpComplexType`](../xmpcomplextype) Instanz. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [TimeFormat](../../groupdocs.metadata.standards.xmp/xmptimecode/timeformat) { get; set; } | Ruft das im Zeitwert verwendete Format ab oder legt es fest. |
| [TimeValue](../../groupdocs.metadata.standards.xmp/xmptimecode/timevalue) { get; set; } | Ruft den Zeitwert im angegebenen Format ab oder legt ihn fest. Zeitwerte verwenden in allen Formaten einen Doppelpunkt als Trennzeichen, mit Ausnahme von 2997drop und 5994drop, die ein Semikolon verwenden. Die vier Felder zeigen Stunden, Minuten, Sekunden und Frames an: hh:mm:ss:ff |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | Ruft den Namespace-URI ab, der dem angegebenen Präfix zugeordnet ist. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | Gibt den in der Zeichenfolge enthaltenen Wert im XMP-Format zurück. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [SetTimeFormat](../../groupdocs.metadata.standards.xmp/xmptimecode/settimeformat)(XmpTimeFormat) | Legt das Zeitformat fest. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | Gibt a zurückString die diese Instanz darstellt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Siehe auch

* class [XmpComplexType](../xmpcomplextype)
* namensraum [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
