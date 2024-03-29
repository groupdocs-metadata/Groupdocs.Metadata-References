---
title: DocumentInfo
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt allgemeine Informationen zu einem geladenen Dokument bereit.
type: docs
weight: 30
url: /de/net/groupdocs.metadata.common/documentinfo/
---
## DocumentInfo class

Stellt allgemeine Informationen zu einem geladenen Dokument bereit.

```csharp
public class DocumentInfo : IDocumentInfo
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FileType](../../groupdocs.metadata.common/documentinfo/filetype) { get; } | Ruft den Dateityp des geladenen Dokuments ab. |
| [IsEncrypted](../../groupdocs.metadata.common/documentinfo/isencrypted) { get; } | Ruft einen Wert ab, der angibt, ob das Dokument verschlüsselt ist und zum Öffnen ein Kennwort erfordert. |
| [PageCount](../../groupdocs.metadata.common/documentinfo/pagecount) { get; } | Ruft die Anzahl der Seiten (Folien, Arbeitsblätter usw.) im geladenen Dokument ab. |
| [Pages](../../groupdocs.metadata.common/documentinfo/pages) { get; } | Ruft eine Sammlung von Objekten ab, die allgemeine Informationen über die Dokumentseiten (Folien, Arbeitsblätter usw.) darstellen. |
| [Size](../../groupdocs.metadata.common/documentinfo/size) { get; } | Ruft die Größe des geladenen Dokuments in Byte ab. |

### Bemerkungen

**Erfahren Sie mehr**

* [Dokumentinformationen erhalten](https://docs.groupdocs.com/display/metadatanet/Get+document+info)

### Beispiele

Dieses Beispiel zeigt, wie grundlegende Formatinformationen aus einer Datei extrahiert werden.

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    if (metadata.FileFormat != FileFormat.Unknown)
    {
        IDocumentInfo info = metadata.GetDocumentInfo();

        Console.WriteLine("File format: {0}", info.FileType.FileFormat);
        Console.WriteLine("File extension: {0}", info.FileType.Extension);
        Console.WriteLine("MIME Type: {0}", info.FileType.MimeType);
        Console.WriteLine("Number of pages: {0}", info.PageCount);
        Console.WriteLine("Document size: {0} bytes", info.Size);
        Console.WriteLine("Is document encrypted: {0}", info.IsEncrypted);
    }
}
```

### Siehe auch

* interface [IDocumentInfo](../idocumentinfo)
* namensraum [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
