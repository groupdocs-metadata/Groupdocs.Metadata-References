---
title: EpubPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Ruft das EPUBMetadatenpaket ab.
type: docs
weight: 20
url: /de/net/groupdocs.metadata.formats.ebook/epubrootpackage/epubpackage/
---
## EpubRootPackage.EpubPackage property

Ruft das EPUB-Metadatenpaket ab.

```csharp
public EpubPackage EpubPackage { get; }
```

### Eigentumswert

Das EPUB-Metadatenpaket.

### Bemerkungen

**Erfahren Sie mehr**

* [Arbeiten mit Metadaten in EPUB E-Books](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+EPUB+E-Books)

### Beispiele

Dieses Codebeispiel zeigt, wie EPUB-formatspezifische Metadateneigenschaften gelesen werden.

```csharp
using (Metadata metadata = new Metadata(Constants.InputEpub))
{
    var root = metadata.GetRootPackage<EpubRootPackage>();

    Console.WriteLine(root.EpubPackage.Version);
    Console.WriteLine(root.EpubPackage.UniqueIdentifier);
    Console.WriteLine(root.EpubPackage.ImageCover != null ? root.EpubPackage.ImageCover.Length : 0);
}
```

### Siehe auch

* class [EpubPackage](../../epubpackage)
* class [EpubRootPackage](../../epubrootpackage)
* namensraum [GroupDocs.Metadata.Formats.Ebook](../../epubrootpackage)
* Montage [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
