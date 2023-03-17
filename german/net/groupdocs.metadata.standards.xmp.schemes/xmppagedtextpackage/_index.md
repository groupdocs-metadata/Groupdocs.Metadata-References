---
title: XmpPagedTextPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Repräsentiert das XMP PagedTextPaket.
type: docs
weight: 3180
url: /de/net/groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/
---
## XmpPagedTextPackage class

Repräsentiert das XMP Paged-Text-Paket.

```csharp
public sealed class XmpPagedTextPackage : XmpPackage
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [XmpPagedTextPackage](xmppagedtextpackage)() | Initialisiert eine neue Instanz von[`XmpPagedTextPackage`](../xmppagedtextpackage) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Colorants](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/colorants) { get; set; } | Ruft ein geordnetes Array von Farbstoffen (Farbfeldern) ab oder legt diese fest, die im Dokument verwendet werden (einschließlich aller in enthaltenen Dokumenten). |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [Fonts](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/fonts) { get; set; } | Ruft ein ungeordnetes Array von Schriftarten ab oder legt diese fest, die im Dokument verwendet werden (einschließlich aller in enthaltenen Dokumenten). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [MaxPageSize](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/maxpagesize) { get; set; } | Ruft die Größe der größten Seite im Dokument ab oder legt sie fest (einschließlich aller in enthaltenen Dokumenten). |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Ruft den Namespace-URI ab. |
| [NumberOfPages](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/numberofpages) { get; set; } | Ruft die Anzahl der Seiten im Dokument ab oder legt sie fest. |
| [PlateNames](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/platenames) { get; set; } | Erhält oder setzt ein geordnetes Array von Plattennamen, die zum Drucken des Dokuments benötigt werden (einschließlich aller in enthaltenen Dokumenten). |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Ruft das xmlns-Präfix ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Ruft den XML-Namespace ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Entfernt alle XMP-Eigenschaften. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Entfernt die Eigenschaft mit dem angegebenen Namen. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Legt die boolesche Eigenschaft fest. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | SätzeDateTime Eigentum. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Legt die Double-Eigenschaft fest. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Legt die ganzzahlige Eigenschaft fest. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/set#set_7)(string, string) | Legt die String-Eigenschaft fest. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmppagedtextpackage/set#set_2)(string, XmpArray) | Legt den geerbten Wert fest[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Legt den geerbten Wert fest[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Legt den geerbten Wert fest[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Siehe auch

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* namensraum [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
