---
title: AsfExtendedStreamPropertyFlags
second_title: GroupDocs.Metadata for .NET API-referens
description: Definierar ASF utökade strömegenskapsflaggor.
type: docs
weight: 2300
url: /sv/net/groupdocs.metadata.formats.video/asfextendedstreampropertyflags/
---
## AsfExtendedStreamPropertyFlags enumeration

Definierar ASF utökade strömegenskapsflaggor.

```csharp
[Flags]
public enum AsfExtendedStreamPropertyFlags : uint
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Reliable | `1` | Denna digitala mediaström, om den skickas över ett nätverk, måste överföras via en pålitlig datakommunikationstransportmekanism. |
| Seekable | `2` | Denna flagga bör endast ställas in om strömmen är sökbar. |
| NoCleanpoints | `2` | Strömmen innehåller inga cleanpoints. |
| ResendLiveCleanpoints | `2` | En ström ansluts mitt i sändningen, all information från den senaste renpunkten fram till den aktuella tiden bör skickas innan normal strömning börjar vid den aktuella tidpunkten. |

### Se även

* namnutrymme [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->