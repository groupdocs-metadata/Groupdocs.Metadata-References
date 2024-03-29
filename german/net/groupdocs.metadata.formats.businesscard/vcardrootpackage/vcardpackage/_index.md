---
title: VCardPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Ruft das VCardMetadatenpaket ab.
type: docs
weight: 10
url: /de/net/groupdocs.metadata.formats.businesscard/vcardrootpackage/vcardpackage/
---
## VCardRootPackage.VCardPackage property

Ruft das VCard-Metadatenpaket ab.

```csharp
public VCardPackage VCardPackage { get; }
```

### Eigentumswert

Das VCard-Metadatenpaket.

### Bemerkungen

**Erfahren Sie mehr**

* [Arbeiten mit vCard-Metadaten](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Beispiele

Dieses Codebeispiel zeigt, wie vCard-Felder zusammen mit beschreibenden Parametern extrahiert werden.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVcf))
{
    var root = metadata.GetRootPackage<VCardRootPackage>();

    foreach (var vCard in root.VCardPackage.Cards)
    {
        if (vCard.IdentificationRecordset.PhotoUriRecords != null)
        {
            // Iteriere alle Fotos, die durch URIs dargestellt werden
            foreach (var photoUriRecord in vCard.IdentificationRecordset.PhotoUriRecords)
            {
                // Eigenschaftswert drucken
                Console.WriteLine(photoUriRecord.Value);

                // Einige zusätzliche Parameter der Eigenschaft drucken
                Console.WriteLine(photoUriRecord.ContentType);
                Console.WriteLine(photoUriRecord.MediaTypeParameter);
                if (photoUriRecord.TypeParameters != null)
                {
                    foreach (string parameter in photoUriRecord.TypeParameters)
                    {
                        Console.WriteLine(parameter);
                    }
                }
                Console.WriteLine(photoUriRecord.PrefParameter);
            }
        }
    }
}
```

### Siehe auch

* class [VCardPackage](../../vcardpackage)
* class [VCardRootPackage](../../vcardrootpackage)
* namensraum [GroupDocs.Metadata.Formats.BusinessCard](../../vcardrootpackage)
* Montage [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
