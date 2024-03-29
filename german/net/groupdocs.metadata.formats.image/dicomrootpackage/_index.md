---
title: DicomRootPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt das Stammpaket dar das mit Metadaten in einem DICOMBild arbeiten soll.
type: docs
weight: 1680
url: /de/net/groupdocs.metadata.formats.image/dicomrootpackage/
---
## DicomRootPackage class

Stellt das Stammpaket dar, das mit Metadaten in einem DICOM-Bild arbeiten soll.

```csharp
public class DicomRootPackage : ImageRootPackage
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [DicomPackage](../../groupdocs.metadata.formats.image/dicomrootpackage/dicompackage) { get; } | Ruft das native DICOM-Metadatenpaket ab. |
| [FileType](../../groupdocs.metadata.formats.image/imagerootpackage/filetype) { get; } | Ruft das Dateityp-Metadatenpaket ab. (2 properties) |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Bemerkungen

**Erfahren Sie mehr**

* [Arbeiten mit DICOM-Metadaten](https://docs.groupdocs.com/display/metadatanet/Working+with+DICOM+metadata)

### Beispiele

Dieses Beispiel zeigt, wie DICOM-formatspezifische Metadateneigenschaften gelesen werden.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDicom))
{
    var root = metadata.GetRootPackage<DicomRootPackage>();
    if (root.DicomPackage != null)
    {
        Console.WriteLine(root.DicomPackage.BitsAllocated);
        Console.WriteLine(root.DicomPackage.LengthValue);
        Console.WriteLine(root.DicomPackage.DicomFound);
        Console.WriteLine(root.DicomPackage.HeaderOffset);
        Console.WriteLine(root.DicomPackage.NumberOfFrames);

        // ...
    }
}
```

### Siehe auch

* class [ImageRootPackage](../imagerootpackage)
* namensraum [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
