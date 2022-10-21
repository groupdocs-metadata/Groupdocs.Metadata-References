---
title: PngInternationalTextChunk
second_title: GroupDocs.Metadata for Java API Reference
description: Represents international textual data extracted from a PNG image.
type: docs
weight: 162
url: /java/com.groupdocs.metadata.core/pnginternationaltextchunk/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.PngTextChunk](../../com.groupdocs.metadata.core/pngtextchunk), [com.groupdocs.metadata.core.PngCompressedTextChunk](../../com.groupdocs.metadata.core/pngcompressedtextchunk)
```
public class PngInternationalTextChunk extends PngCompressedTextChunk
```

Represents international textual data extracted from a PNG image.
## Methods

| Method | Description |
| --- | --- |
| [isCompressed()](#isCompressed--) | Gets a value indicating whether the chunk is compressed. |
| [getLanguage()](#getLanguage--) | Gets the human language used by the translated keyword and the text. |
| [getTranslatedKeyword()](#getTranslatedKeyword--) | Gets the translated keyword that contains a translation of the keyword into the language indicated by the language property. |
### isCompressed() {#isCompressed--}
```
public final boolean isCompressed()
```


Gets a value indicating whether the chunk is compressed.

**Returns:**
boolean - True, if the chunk is compressed; otherwise, false.
### getLanguage() {#getLanguage--}
```
public final String getLanguage()
```


Gets the human language used by the translated keyword and the text.

**Returns:**
java.lang.String - The human language used by the translated keyword and the text.
### getTranslatedKeyword() {#getTranslatedKeyword--}
```
public final String getTranslatedKeyword()
```


Gets the translated keyword that contains a translation of the keyword into the language indicated by the language property.

**Returns:**
java.lang.String - The translated keyword that contains a translation of the keyword into the language indicated by the language property.
