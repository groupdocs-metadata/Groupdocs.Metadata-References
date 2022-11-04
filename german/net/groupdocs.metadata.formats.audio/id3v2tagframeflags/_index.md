---
title: ID3V2TagFrameFlags
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt Flags dar die in einem ID3v2TagFrame verwendet werden.
type: docs
weight: 510
url: /de/net/groupdocs.metadata.formats.audio/id3v2tagframeflags/
---
## ID3V2TagFrameFlags class

Stellt Flags dar, die in einem ID3v2-Tag-Frame verwendet werden.

```csharp
public sealed class ID3V2TagFrameFlags : IEquatable<ID3V2TagFrameFlags>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Compression](../../groupdocs.metadata.formats.audio/id3v2tagframeflags/compression) { get; } | Ruft einen Wert ab, der angibt, ob der Frame komprimiert ist. |
| [DataLengthIndicator](../../groupdocs.metadata.formats.audio/id3v2tagframeflags/datalengthindicator) { get; } | Ruft einen Wert ab, der angibt, ob ein Datenlängenindikator zu dem Frame hinzugefügt wurde. Der Datenlängenindikator ist der Wert, den man als 'Frame-Länge' schreiben würde wenn alle Frame-Format-Flags auf Null gesetzt wären, dargestellt als synchronsichere 32-Bit-Ganzzahl. |
| [Encryption](../../groupdocs.metadata.formats.audio/id3v2tagframeflags/encryption) { get; } | Ruft einen Wert ab, der angibt, ob der Frame verschlüsselt ist. Wenn gesetzt, wird ein Byte, das angibt, mit welcher Methode verschlüsselt wurde, an den Frame-Header angehängt. |
| [FileAlterPreservation](../../groupdocs.metadata.formats.audio/id3v2tagframeflags/filealterpreservation) { get; } | Ruft das Flag ab, das der Software mitteilt, was mit diesem Frame zu tun ist, wenn er unbekannt ist und die Datei mit Ausnahme des Tags geändert wird. Dies gilt nicht, wenn das Audio vollständig durch andere Audiodaten ersetzt wird. |
| [GroupingIdentity](../../groupdocs.metadata.formats.audio/id3v2tagframeflags/groupingidentity) { get; } | Ruft einen Wert ab, der angibt, ob der Frame zu einer Gruppe von Frames gehört. Wenn gesetzt, wird dem Frame-Header ein Gruppenkennungsbyte hinzugefügt. Jeder Frame mit derselben Gruppenkennung gehört zu derselben Gruppe. |
| [ReadOnly](../../groupdocs.metadata.formats.audio/id3v2tagframeflags/readonly) { get; } | Ruft das Tag ab, das der Software mitteilt, dass der Inhalt dieses Frames schreibgeschützt sein soll. |
| [TagAlterPreservation](../../groupdocs.metadata.formats.audio/id3v2tagframeflags/tagalterpreservation) { get; } | Ruft das Flag ab, das der Software mitteilt, was mit diesem Frame zu tun ist, wenn er unbekannt ist und das Tag in irgendeiner Weise geändert wird. Dies gilt für alle Arten von Änderungen, einschließlich dem Hinzufügen von mehr Polsterung und dem Neuordnen der Rahmen. |
| [Unsynchronisation](../../groupdocs.metadata.formats.audio/id3v2tagframeflags/unsynchronisation) { get; } | Ruft einen Wert ab, der angibt, ob die Unsynchronisierung auf diesen Frame angewendet wurde. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Equals](../../groupdocs.metadata.formats.audio/id3v2tagframeflags/equals#equals)(ID3V2TagFrameFlags) | Gibt an, ob das aktuelle Objekt gleich einem anderen Objekt desselben Typs ist. |
| override [Equals](../../groupdocs.metadata.formats.audio/id3v2tagframeflags/equals#equals_1)(object) | Bestimmt, ob das angegebene Objekt dieser Instanz entspricht. |
| override [GetHashCode](../../groupdocs.metadata.formats.audio/id3v2tagframeflags/gethashcode)() | Gibt einen Hash-Code für diese Instanz zurück. |

### Siehe auch

* namensraum [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->