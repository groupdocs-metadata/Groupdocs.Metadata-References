---
title: PdfRootPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt das RootPaket dar das die Arbeit mit Metadaten in einem PDFDokument ermöglicht.
type: docs
weight: 1040
url: /de/net/groupdocs.metadata.formats.document/pdfrootpackage/
---
## PdfRootPackage class

Stellt das Root-Paket dar, das die Arbeit mit Metadaten in einem PDF-Dokument ermöglicht.

```csharp
public class PdfRootPackage : DocumentRootPackage<PdfPackage>, IXmp
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| virtual [DocumentProperties](../../groupdocs.metadata.formats.document/documentrootpackage-1/documentproperties) { get; } | Ruft die im Dokument präsentierten nativen Metadateneigenschaften ab. |
| [DocumentStatistics](../../groupdocs.metadata.formats.document/pdfrootpackage/documentstatistics) { get; } | Ruft das Dokumentstatistikpaket ab. |
| [FileType](../../groupdocs.metadata.formats.document/pdfrootpackage/filetype) { get; } | Ruft das Dateityp-Metadatenpaket ab. (2 properties) |
| [InspectionPackage](../../groupdocs.metadata.formats.document/pdfrootpackage/inspectionpackage) { get; } | Ruft ein Metadatenpaket ab, das Inspektionsergebnisse für das Dokument enthält. Das Paket enthält Informationen zu Dokumententeilen, die in einigen Fällen als Metadaten betrachtet werden können. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [XmpPackage](../../groupdocs.metadata.formats.document/pdfrootpackage/xmppackage) { get; set; } | Ruft das XMP-Metadatenpaket ab oder legt es fest. |

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

* [Arbeiten mit Metadaten in PDF-Dokumenten](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)
* [Arbeiten mit XMP-Metadaten](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Beispiele

Dieses Codebeispiel zeigt, wie integrierte Metadateneigenschaften aus einem PDF-Dokument extrahiert werden.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    Console.WriteLine(root.DocumentProperties.Author);
    Console.WriteLine(root.DocumentProperties.CreatedDate);
    Console.WriteLine(root.DocumentProperties.Subject);
    Console.WriteLine(root.DocumentProperties.Producer);
    Console.WriteLine(root.DocumentProperties.Keywords);

    // ... 
}
```

### Siehe auch

* class [DocumentRootPackage&lt;TPackage&gt;](../documentrootpackage-1)
* class [PdfPackage](../pdfpackage)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* namensraum [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
