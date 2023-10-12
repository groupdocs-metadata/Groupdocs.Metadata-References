---
title: TiffAsciiTag
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a TIFF ASCII tag.
type: docs
weight: 236
url: /java/com.groupdocs.metadata.core/tiffasciitag/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataProperty](../../com.groupdocs.metadata.core/metadataproperty), [com.groupdocs.metadata.core.TiffTag](../../com.groupdocs.metadata.core/tifftag)
```
public final class TiffAsciiTag extends TiffTag
```

Represents a TIFF ASCII tag.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffAsciiTag(TiffTagID tagID, String value)](#TiffAsciiTag-com.groupdocs.metadata.core.TiffTagID-java.lang.String-) | Initializes a new instance of the  TiffAsciiTag  class. |
## Methods

| Method | Description |
| --- | --- |
| [getTagValue()](#getTagValue--) | Gets the tag value. |
### TiffAsciiTag(TiffTagID tagID, String value) {#TiffAsciiTag-com.groupdocs.metadata.core.TiffTagID-java.lang.String-}
```
public TiffAsciiTag(TiffTagID tagID, String value)
```


Initializes a new instance of the  TiffAsciiTag  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagID | [TiffTagID](../../com.groupdocs.metadata.core/tifftagid) | The tag identifier. |
| value | java.lang.String | The value. |

### getTagValue() {#getTagValue--}
```
public final String getTagValue()
```


Gets the tag value.

**Returns:**
java.lang.String - The tag value.
