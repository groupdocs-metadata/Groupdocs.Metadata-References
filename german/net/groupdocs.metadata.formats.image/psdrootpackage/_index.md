---
title: PsdRootPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt das RootPaket dar das die Arbeit mit Metadaten in einem PhotoshopDokument ermöglicht.
type: docs
weight: 1930
url: /de/net/groupdocs.metadata.formats.image/psdrootpackage/
---
## PsdRootPackage class

Stellt das Root-Paket dar, das die Arbeit mit Metadaten in einem Photoshop-Dokument ermöglicht.

```csharp
public class PsdRootPackage : ImageRootPackage, IExif, IIptc, IXmp
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [ExifPackage](../../groupdocs.metadata.formats.image/psdrootpackage/exifpackage) { get; set; } | Ruft das EXIF-Metadatenpaket ab oder legt es fest. |
| [FileType](../../groupdocs.metadata.formats.image/imagerootpackage/filetype) { get; } | Ruft das Dateityp-Metadatenpaket ab. (2 properties) |
| [ImageResourcePackage](../../groupdocs.metadata.formats.image/psdrootpackage/imageresourcepackage) { get; } | Ruft das Photoshop-Bildressourcen-Metadatenpaket ab. Bildressourcenblöcke sind die grundlegende Baueinheit des nativen Dateiformats von Photoshop. |
| [IptcPackage](../../groupdocs.metadata.formats.image/psdrootpackage/iptcpackage) { get; set; } | Ruft das IPTC-Metadatenpaket ab oder legt es fest. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [PsdPackage](../../groupdocs.metadata.formats.image/psdrootpackage/psdpackage) { get; } | Ruft das Metadatenpaket ab, das Informationen über die PSD-Datei enthält. |
| [XmpPackage](../../groupdocs.metadata.formats.image/psdrootpackage/xmppackage) { get; set; } | Ruft das XMP-Metadatenpaket ab oder legt es fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Bemerkungen

**Mehr erfahren**

* [Arbeiten mit Metadaten in PSD-Bildern](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PSD+images)
* [Arbeiten mit EXIF-Metadaten](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)
* [Arbeiten mit XMP-Metadaten](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)
* [Arbeiten mit IPTC-IIM-Metadaten](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Siehe auch

* class [ImageRootPackage](../imagerootpackage)
* interface [IExif](../../groupdocs.metadata.standards.exif/iexif)
* interface [IIptc](../../groupdocs.metadata.standards.iptc/iiptc)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* namensraum [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
