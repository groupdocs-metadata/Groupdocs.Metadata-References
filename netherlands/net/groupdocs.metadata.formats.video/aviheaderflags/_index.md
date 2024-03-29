---
title: AviHeaderFlags
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt AVI Headervlaggen.
type: docs
weight: 2390
url: /nl/net/groupdocs.metadata.formats.video/aviheaderflags/
---
## AviHeaderFlags enumeration

Vertegenwoordigt AVI Header-vlaggen.

```csharp
[Flags]
public enum AviHeaderFlags
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| HasIndex | `10` | Geeft aan dat het AVI-bestand een index heeft. |
| MustUseIndex | `20` | Geeft aan dat de toepassing de index moet gebruiken in plaats van de fysieke volgorde van de delen in het bestand, om de volgorde van presentatie van de gegevens te bepalen. Deze vlag kan bijvoorbeeld worden gebruikt om een lijst met frames te maken om te bewerken. |
| IsInterleaved | `100` | Geeft aan dat het AVI-bestand interleaved is. |
| TrustCkType | `800` | Gebruik CKType om sleutelframes te vinden. |
| WasCaptureFile | `10000` | Geeft aan dat het AVI-bestand een speciaal toegewezen bestand is dat wordt gebruikt voor het vastleggen van real-time video. Toepassingen moeten de gebruiker waarschuwen voordat ze een bestand met deze vlag overschrijven, omdat de gebruiker dit bestand waarschijnlijk heeft gedefragmenteerd. |
| Copyrighted | `20000` | Geeft aan dat het AVI-bestand auteursrechtelijk beschermde gegevens en software bevat. Wanneer deze vlag wordt gebruikt, mag software niet toestaan dat de gegevens worden gedupliceerd. |

### Zie ook

* naamruimte [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
