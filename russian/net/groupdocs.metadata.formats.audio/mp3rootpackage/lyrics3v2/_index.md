---
title: Lyrics3V2
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Получает или задает тег метаданных Lyrics3v2.
type: docs
weight: 40
url: /ru/net/groupdocs.metadata.formats.audio/mp3rootpackage/lyrics3v2/
---
## MP3RootPackage.Lyrics3V2 property

Получает или задает тег метаданных Lyrics3v2.

```csharp
public LyricsTag Lyrics3V2 { get; set; }
```

### Стоимость имущества

Тег метаданных Lyrics3v2.

### Примеры

В этом примере показано, как обновить тег Lyrics в файле MP3

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithLyrics))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.Lyrics3V2 == null)
    {
        root.Lyrics3V2 = new LyricsTag();
    }

    root.Lyrics3V2.Lyrics = "[00:01]Test lyrics";
    root.Lyrics3V2.Artist = "test artist";
    root.Lyrics3V2.Album = "test album";
    root.Lyrics3V2.Track = "test track";

    // Вы можете добавить в тег полностью настраиваемое поле
    root.Lyrics3V2.Set(new LyricsField("ABC", "custom value"));

    // ...

    metadata.Save(Constants.OutputMp3);
}
```

### Смотрите также

* class [LyricsTag](../../lyricstag)
* class [MP3RootPackage](../../mp3rootpackage)
* пространство имен [GroupDocs.Metadata.Formats.Audio](../../mp3rootpackage)
* сборка [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->