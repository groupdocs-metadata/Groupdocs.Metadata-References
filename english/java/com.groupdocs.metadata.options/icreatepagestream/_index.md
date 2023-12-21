---
title: ICreatePageStream
second_title: GroupDocs.Signature for Java API Reference
description: Defines a method that returns a stream to write page preview data.
type: docs
weight: 12
url: /java/com.groupdocs.metadata.options/icreatepagestream/
---```
public interface ICreatePageStream
```

Defines a method that returns a stream to write page preview data.
## Methods

| Method | Description |
| --- | --- |
| [createPageStream(int pageNumber)](#createPageStream-int-) | Represents a method that returns a stream to write page preview data. |
### createPageStream(int pageNumber) {#createPageStream-int-}
```
public abstract OutputStream createPageStream(int pageNumber)
```


Represents a method that returns a stream to write page preview data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The page number of a page to generate a thumbnail.

**Learn more**

 *  [Generate document preview][]


[Generate document preview]: https://docs.groupdocs.com/display/metadatajava/Generate+document+preview |

**Returns:**
java.io.OutputStream - The stream to write the page preview.
