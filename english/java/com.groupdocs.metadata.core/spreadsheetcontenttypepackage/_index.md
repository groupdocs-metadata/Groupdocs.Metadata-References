---
title: SpreadsheetContentTypePackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a metadata package containing spreadsheet content type properties.
type: docs
weight: 228
url: /java/com.groupdocs.metadata.core/spreadsheetcontenttypepackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public class SpreadsheetContentTypePackage extends CustomPackage
```

Represents a metadata package containing spreadsheet content type properties.
## Methods

| Method | Description |
| --- | --- |
| [set(String propertyName, String propertyValue)](#set-java.lang.String-java.lang.String-) | Adds or replaces the content type property with the specified name. |
| [set(String propertyName, String propertyValue, String propertyType)](#set-java.lang.String-java.lang.String-java.lang.String-) | Adds or replaces the content type property with the specified name. |
| [remove(String propertyName)](#remove-java.lang.String-) | Removes the content type property with the specified name. |
| [clear()](#clear--) | Removes all writable metadata properties. |
| [toList()](#toList--) | Creates a list from the package. |
### set(String propertyName, String propertyValue) {#set-java.lang.String-java.lang.String-}
```
public final void set(String propertyName, String propertyValue)
```


Adds or replaces the content type property with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | The property name. |
| propertyValue | java.lang.String | The property value. |

### set(String propertyName, String propertyValue, String propertyType) {#set-java.lang.String-java.lang.String-java.lang.String-}
```
public final void set(String propertyName, String propertyValue, String propertyType)
```


Adds or replaces the content type property with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | The property name. |
| propertyValue | java.lang.String | The property value. |
| propertyType | java.lang.String | The property type. |

### remove(String propertyName) {#remove-java.lang.String-}
```
public final boolean remove(String propertyName)
```


Removes the content type property with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | The name of the content type property to be removed. |

**Returns:**
boolean -  true  if the property is found and deleted; otherwise  false .
### clear() {#clear--}
```
public final void clear()
```


Removes all writable metadata properties.

### toList() {#toList--}
```
public final IReadOnlyList<SpreadsheetContentTypeProperty> toList()
```


Creates a list from the package.

**Returns:**
[IReadOnlyList](../../com.groupdocs.metadata.core/ireadonlylist) - A list that contains properties from the package.
