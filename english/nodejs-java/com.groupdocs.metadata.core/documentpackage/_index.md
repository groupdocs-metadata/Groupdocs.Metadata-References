---
title: DocumentPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents native metadata in an office document.
type: docs
weight: 81
url: /nodejs-java/com.groupdocs.metadata.core/documentpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public abstract class DocumentPackage extends CustomPackage
```

Represents native metadata in an office document.
## Methods

| Method | Description |
| --- | --- |
| [remove(String propertyName)](#remove-java.lang.String-) | Removes a writable metadata property by the specified name. |
| [clear()](#clear--) | Removes all writable metadata properties from the package. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Removes all built-in metadata properties. |
| [clearCustomProperties()](#clearCustomProperties--) | Removes all custom metadata properties. |
### remove(String propertyName) {#remove-java.lang.String-}
```
public final boolean remove(String propertyName)
```


Removes a writable metadata property by the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | A metadata property name. |

**Returns:**
boolean -  true  if the property is found and deleted; otherwise  false .
### clear() {#clear--}
```
public final void clear()
```


Removes all writable metadata properties from the package.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```


Removes all built-in metadata properties.

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```


Removes all custom metadata properties.

