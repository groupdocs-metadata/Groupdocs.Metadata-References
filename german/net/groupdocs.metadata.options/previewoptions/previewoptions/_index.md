---
title: PreviewOptions
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonPreviewOptionsgroupdocs.metadata.options/previewoptions Klasse bewirkt dass der Ausgabestrom geschlossen wird.
type: docs
weight: 10
url: /de/net/groupdocs.metadata.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream) {#constructor}

Initialisiert eine neue Instanz von[`PreviewOptions`](../../previewoptions) Klasse bewirkt, dass der Ausgabestrom geschlossen wird.

```csharp
public PreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Erstellt einen Stream für eine bestimmte Seitenvorschau. |

### Siehe auch

* delegate [CreatePageStream](../../createpagestream)
* class [PreviewOptions](../../previewoptions)
* namensraum [GroupDocs.Metadata.Options](../../previewoptions)
* Montage [GroupDocs.Metadata](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialisiert eine neue Instanz von[`PreviewOptions`](../../previewoptions) Klasse bewirkt, dass der Ausgabestream zur weiteren Verwendung an den Client zurückgegeben wird.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Erstellt einen Stream für eine bestimmte Seitenvorschau |
| releasePageStream | ReleasePageStream | Benachrichtigt, dass die Generierung der Seitenvorschau abgeschlossen ist, und ruft den Ausgabestream ab. |

### Siehe auch

* delegate [CreatePageStream](../../createpagestream)
* delegate [ReleasePageStream](../../releasepagestream)
* class [PreviewOptions](../../previewoptions)
* namensraum [GroupDocs.Metadata.Options](../../previewoptions)
* Montage [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
