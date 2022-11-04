---
title: XmpMeta
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: steht für xmpmeta. Optional. Der Zweck dieses Elements besteht darin XMPMetadaten in allgemeinem XMLText zu identifizieren die andere NichtXMPVerwendungen von RDF enthalten könnten.
type: docs
weight: 3460
url: /de/net/groupdocs.metadata.standards.xmp/xmpmeta/
---
## XmpMeta class

steht für xmpmeta. Optional. Der Zweck dieses Elements besteht darin, XMP-Metadaten in allgemeinem XML-Text zu identifizieren, die andere Nicht-XMP-Verwendungen von RDF enthalten könnten.

```csharp
public sealed class XmpMeta : XmpElementBase, IXmpType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [XmpMeta](xmpmeta)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AdobeXmpToolkit](../../groupdocs.metadata.standards.xmp/xmpmeta/adobexmptoolkit) { get; } | Ruft die Version des Adobe XMP-Toolkits ab. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [ClearAttributes](../../groupdocs.metadata.standards.xmp/xmpelementbase/clearattributes)() | Entfernt alle Attribute. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| [ContainsAttribute](../../groupdocs.metadata.standards.xmp/xmpelementbase/containsattribute)(string) | Ermittelt, ob das Element ein bestimmtes Attribut enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetAttribute](../../groupdocs.metadata.standards.xmp/xmpelementbase/getattribute)(string) | Ruft das Attribut ab. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpmeta/getxmprepresentation)() | Konvertiert den XMP-Wert in die XML-Darstellung. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| override [SetAttribute](../../groupdocs.metadata.standards.xmp/xmpmeta/setattribute)(string, string) | Fügt ein Attribut hinzu. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Siehe auch

* class [XmpElementBase](../xmpelementbase)
* interface [IXmpType](../ixmptype)
* namensraum [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
