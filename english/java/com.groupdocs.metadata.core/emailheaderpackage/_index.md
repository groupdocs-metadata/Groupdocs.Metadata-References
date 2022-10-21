---
title: EmailHeaderPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a metadata package containing email message headers.
type: docs
weight: 57
url: /java/com.groupdocs.metadata.core/emailheaderpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public class EmailHeaderPackage extends CustomPackage
```

Represents a metadata package containing email message headers.

**Learn more**

 *  [Working with saved Emails][]


[Working with saved Emails]: https://docs.groupdocs.com/display/metadatajava/Working+with+saved+Emails
## Methods

| Method | Description |
| --- | --- |
| [get(String header)](#get-java.lang.String-) | Gets the value of the specified header. |
### get(String header) {#get-java.lang.String-}
```
public final String get(String header)
```


Gets the value of the specified header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| header | java.lang.String | An email header. |

**Returns:**
java.lang.String - The value if the package contains the specified header; otherwise, null.
