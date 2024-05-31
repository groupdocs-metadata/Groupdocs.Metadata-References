---
title: XmpElementBase
second_title: GroupDocs.Metadata for Java API Reference
description: Represents base XMP element that contains attributes.
type: docs
weight: 314
url: /java/com.groupdocs.metadata.core/xmpelementbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public abstract class XmpElementBase extends CustomPackage
```

Represents base XMP element that contains attributes.
## Methods

| Method | Description |
| --- | --- |
| [setAttribute(String attribute, String value)](#setAttribute-java.lang.String-java.lang.String-) | Adds the attribute. |
| [clearAttributes()](#clearAttributes--) | Removes all attributes. |
| [containsAttribute(String attribute)](#containsAttribute-java.lang.String-) | Determines whether the element contains a specific attribute. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Gets the attribute. |
### setAttribute(String attribute, String value) {#setAttribute-java.lang.String-java.lang.String-}
```
public void setAttribute(String attribute, String value)
```


Adds the attribute.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attribute | java.lang.String | Attribute key. |
| value | java.lang.String | Attribute value. |

### clearAttributes() {#clearAttributes--}
```
public final void clearAttributes()
```


Removes all attributes.

### containsAttribute(String attribute) {#containsAttribute-java.lang.String-}
```
public final boolean containsAttribute(String attribute)
```


Determines whether the element contains a specific attribute.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attribute | java.lang.String | Attribute name. |

**Returns:**
boolean - true if attribute is exist; otherwise false.
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public final String getAttribute(String attribute)
```


Gets the attribute.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attribute | java.lang.String | The attribute. |

**Returns:**
java.lang.String - The attribute value.
