---
title: MovAtom
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a QuickTime atom.
type: docs
weight: 129
url: /java/com.groupdocs.metadata.core/movatom/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)

**All Implemented Interfaces:**
com.groupdocs.metadata.core.IIsoMediaBox
```
public final class MovAtom extends CustomPackage implements IIsoMediaBox
```

Represents a QuickTime atom.

**Learn more**

 *  [Working with metadata in MOV Files][]


[Working with metadata in MOV Files]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+MOV+Files
## Methods

| Method | Description |
| --- | --- |
| [getOffset()](#getOffset--) | Gets the atom offset. |
| [getSize()](#getSize--) | Gets the atom size in bytes. |
| [getLongSize()](#getLongSize--) | Gets the atom size in bytes. |
| [getType()](#getType--) | Gets the 4-characters type. |
| [getDataOffset()](#getDataOffset--) | Gets the data offset. |
| [getDataSize()](#getDataSize--) | Gets the data size in bytes. |
| [hasExtendedSize()](#hasExtendedSize--) | Gets a value indicating whether the extended size field was used to store the atom data. |
### getOffset() {#getOffset--}
```
public final long getOffset()
```


Gets the atom offset.

**Returns:**
long - The atom offset.
### getSize() {#getSize--}
```
public final int getSize()
```


Gets the atom size in bytes.

**Returns:**
int - The atom size.
### getLongSize() {#getLongSize--}
```
public final long getLongSize()
```


Gets the atom size in bytes.

**Returns:**
long - The atom size.
### getType() {#getType--}
```
public final String getType()
```


Gets the 4-characters type.

**Returns:**
java.lang.String - The type.
### getDataOffset() {#getDataOffset--}
```
public final long getDataOffset()
```


Gets the data offset.

**Returns:**
long - The data offset.
### getDataSize() {#getDataSize--}
```
public final int getDataSize()
```


Gets the data size in bytes.

**Returns:**
int - The data size.
### hasExtendedSize() {#hasExtendedSize--}
```
public final boolean hasExtendedSize()
```


Gets a value indicating whether the extended size field was used to store the atom data.

**Returns:**
boolean - True, if the extended size field was used to store the atom data; otherwise, false.
