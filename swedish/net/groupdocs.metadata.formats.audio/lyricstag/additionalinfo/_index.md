---
title: AdditionalInfo
second_title: GroupDocs.Metadata for .NET API-referens
description: Hämtar eller ställer in ytterligare information. Detta värde representeras av INFfältet.
type: docs
weight: 20
url: /sv/net/groupdocs.metadata.formats.audio/lyricstag/additionalinfo/
---
## LyricsTag.AdditionalInfo property

Hämtar eller ställer in ytterligare information. Detta värde representeras av INF-fältet.

```csharp
public string AdditionalInfo { get; set; }
```

### Fastighetsvärde

Ytterligare information.

### Anmärkningar

Detta är alltid tre (3) tecken långt i v2.00, men kan vara längre i en framtida standard. Den första byten indikerar väder eller inte att ett textfält finns. "1" för nuvarande och "0" för annars. Det andra tecknet indikerar om det finns en tidsstämpel i sångtexten. Återigen "1" för ja och "0" för nej. Det tredje tecknet förhindrar spår för slumpmässigt urval - "1" om det är inhiberat och "0" om inte.

### Se även

* class [LyricsTag](../../lyricstag)
* namnutrymme [GroupDocs.Metadata.Formats.Audio](../../lyricstag)
* hopsättning [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->