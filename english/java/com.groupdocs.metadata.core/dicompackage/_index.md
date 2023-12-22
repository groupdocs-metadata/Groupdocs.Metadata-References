---
title: DicomPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents native DICOM metadata.
type: docs
weight: 73
url: /java/com.groupdocs.metadata.core/dicompackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class DicomPackage extends CustomPackage
```

Represents native DICOM metadata.

**Learn more**

 *  [Working with DICOM metadata][]


[Working with DICOM metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+DICOM+metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [DicomPackage()](#DicomPackage--) | Initializes a new instance of the  Metadata  class. |
## Methods

| Method | Description |
| --- | --- |
| [getHeaderOffset()](#getHeaderOffset--) | Gets the header offset. |
| [getHeaderBytes()](#getHeaderBytes--) | Gets the header information by bytes. |
| [getBitsAllocated()](#getBitsAllocated--) | Gets the bits allocated value. |
| [getDicomInfo()](#getDicomInfo--) | Gets the header information of the DICOM file. |
| [getBlues()](#getBlues--) | Gets the array colors of the blue. |
| [getGreens()](#getGreens--) | Gets the array colors of the green. |
| [getReds()](#getReds--) | Gets the array colors of the red. |
| [getNumberOfFrames()](#getNumberOfFrames--) | Gets the number of frames. |
### DicomPackage() {#DicomPackage--}
```
public DicomPackage()
```


Initializes a new instance of the  Metadata  class.

### getHeaderOffset() {#getHeaderOffset--}
```
public final int getHeaderOffset()
```


Gets the header offset.

Value: The header offset.

**Returns:**
int
### getHeaderBytes() {#getHeaderBytes--}
```
public final Byte[] getHeaderBytes()
```


Gets the header information by bytes.

Value: The header bytes.

**Returns:**
java.lang.Byte[]
### getBitsAllocated() {#getBitsAllocated--}
```
public final int getBitsAllocated()
```


Gets the bits allocated value.

**Returns:**
int - The bits allocated.
### getDicomInfo() {#getDicomInfo--}
```
public final String[] getDicomInfo()
```


Gets the header information of the DICOM file.

**Returns:**
java.lang.String[] - The dicom header information.
### getBlues() {#getBlues--}
```
public final byte[] getBlues()
```


Gets the array colors of the blue.

**Returns:**
byte[] - The blue colors.
### getGreens() {#getGreens--}
```
public final byte[] getGreens()
```


Gets the array colors of the green.

**Returns:**
byte[] - The green colors.
### getReds() {#getReds--}
```
public final byte[] getReds()
```


Gets the array colors of the red.

**Returns:**
byte[] - The red colors.
### getNumberOfFrames() {#getNumberOfFrames--}
```
public final int getNumberOfFrames()
```


Gets the number of frames.

**Returns:**
int - The number of frames.
