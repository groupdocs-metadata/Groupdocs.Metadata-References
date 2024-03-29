---
title: DetectBarcodeTypes
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Extrahiert die Typen der im Bild dargestellten Barcodes.
type: docs
weight: 60
url: /de/net/groupdocs.metadata.formats.image/jpegrootpackage/detectbarcodetypes/
---
## JpegRootPackage.DetectBarcodeTypes method

Extrahiert die Typen der im Bild dargestellten Barcodes.

```csharp
public string[] DetectBarcodeTypes()
```

### Rückgabewert

Ein Array von Barcode-Typen.

### Bemerkungen

**Erfahren Sie mehr**

* [Arbeiten mit Metadaten in JPEG-Bildern](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG+images)

### Beispiele

Dieses Code-Snippet zeigt, wie Barcodes in einem JPEG-Bild erkannt werden.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithBarcodes))
{
    var root = metadata.GetRootPackage<JpegRootPackage>();

    var barcodeTypes = root.DetectBarcodeTypes();

    foreach (var barcodeType in barcodeTypes)
    {
        Console.WriteLine(barcodeType);
    }
}
```

### Siehe auch

* class [JpegRootPackage](../../jpegrootpackage)
* namensraum [GroupDocs.Metadata.Formats.Image](../../jpegrootpackage)
* Montage [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
