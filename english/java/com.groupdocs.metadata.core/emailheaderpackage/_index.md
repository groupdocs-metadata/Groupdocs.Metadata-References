---
title: EmailHeaderPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a metadata package containing email message headers.
type: docs
weight: 88
url: /java/com.groupdocs.metadata.core/emailheaderpackage/
---

**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public class EmailHeaderPackage extends CustomPackage
```

Represents a metadata package containing email message headers.


**Learn more**

* [Working with saved Emails](../https://docs.groupdocs.com/display/metadatajava/Working+with+saved+Emails)

<br />


## Methods

| Method | Description |
| --- | --- |
| [get(String header)](#get-java.lang.String-) | Gets the value of the specified header.
 |
| [set(String header, PropertyValue value)](#set-java.lang.String-com.groupdocs.metadata.core.PropertyValue-) | Sets the value of the specified header.
 |
### get(String header) {#get-java.lang.String-}
```
public final String get(String header)
```


Gets the value of the specified header.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| header | java.lang.String | An email header.
 |

**Returns:**
java.lang.String - The value if the package contains the specified header; otherwise, null.

### set(String header, PropertyValue value) {#set-java.lang.String-com.groupdocs.metadata.core.PropertyValue-}
```
public final void set(String header, PropertyValue value)
```


Sets the value of the specified header.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| header | java.lang.String | An email header.
 |
| value | [PropertyValue](../../com.groupdocs.metadata.core/propertyvalue) | The value of the header.
 |

