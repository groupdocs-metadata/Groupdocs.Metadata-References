---
title: MatroskaRootPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents the root package allowing working with metadata in a Matroska video.
type: docs
weight: 150
url: /nodejs-java/com.groupdocs.metadata.core/matroskarootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)
```
public class MatroskaRootPackage extends RootMetadataPackage
```

Represents the root package allowing working with metadata in a Matroska video.

**Learn more**

 *  [Working with metadata in Matroska (MKV) files][Working with metadata in Matroska _MKV_ files]

This example demonstrates how to extract subtitles from an MKV video.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.MkvWithSubtitles)) {
>      MatroskaRootPackage root = metadata.getRootPackageGeneric();
>      for (MatroskaSubtitleTrack subtitleTrack : root.getMatroskaPackage().getSubtitleTracks()) {
>          System.out.println(subtitleTrack.getLanguageIetf() != null ? subtitleTrack.getLanguageIetf() : subtitleTrack.getLanguage());
>          for (MatroskaSubtitle subtitle : subtitleTrack.getSubtitles()) {
>              System.out.println(String.format("Timecode=%s, Duration=%s", subtitle.getTimecode(), subtitle.getDuration()));
>              System.out.println(subtitle.getText());
>          }
>      }
>  }
>  
> ```
> ```


[Working with metadata in Matroska _MKV_ files]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Matroska+%28MKV%29+files
## Methods

| Method | Description |
| --- | --- |
| [getMatroskaPackage()](#getMatroskaPackage--) | Gets the Matroska metadata package. |
### getMatroskaPackage() {#getMatroskaPackage--}
```
public final MatroskaPackage getMatroskaPackage()
```


Gets the Matroska metadata package.

**Returns:**
[MatroskaPackage](../../com.groupdocs.metadata.core/matroskapackage) - The Matroska metadata package.
