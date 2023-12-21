---
title: IReleasePageStream
second_title: GroupDocs.Signature for Java API Reference
description: Defines a method which releases the stream created by the passed ICreatePageStream implementation.
type: docs
weight: 13
url: /java/com.groupdocs.metadata.options/ireleasepagestream/
---```
public interface IReleasePageStream
```

Defines a method which releases the stream created by the passed  ICreatePageStream  implementation.
## Methods

| Method | Description |
| --- | --- |
| [releasePageStream(int pageNumber, OutputStream pageStream)](#releasePageStream-int-java.io.OutputStream-) | Represents a method which releases the stream created by the passed  ICreatePageStream  implementation. |
### releasePageStream(int pageNumber, OutputStream pageStream) {#releasePageStream-int-java.io.OutputStream-}
```
public abstract void releasePageStream(int pageNumber, OutputStream pageStream)
```


Represents a method which releases the stream created by the passed  ICreatePageStream  implementation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The page number of a generated page preview. |
| pageStream | java.io.OutputStream | The stream containing the generated page preview.

**Learn more**

 *  [Generate document preview][]


[Generate document preview]: https://docs.groupdocs.com/display/metadatajava/Generate+document+preview |

