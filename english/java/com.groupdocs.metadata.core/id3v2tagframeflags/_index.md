---
title: ID3V2TagFrameFlags
second_title: GroupDocs.Metadata for Java API Reference
description: Represents flags used in a ID3v2 tag frame.
type: docs
weight: 89
url: /java/com.groupdocs.metadata.core/id3v2tagframeflags/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class ID3V2TagFrameFlags implements System.IEquatable<ID3V2TagFrameFlags>
```

Represents flags used in a ID3v2 tag frame.
## Methods

| Method | Description |
| --- | --- |
| [getTagAlterPreservation()](#getTagAlterPreservation--) | Gets the flag that tells the software what to do with this frame if it is unknown and the tag is altered in any way. |
| [getFileAlterPreservation()](#getFileAlterPreservation--) | Gets the flag that tells the software what to do with this frame if it is unknown and the file, excluding the tag, is altered. |
| [getReadOnly()](#getReadOnly--) | Gets the tag that tells the software that the contents of this frame is intended to be read-only. |
| [getCompression()](#getCompression--) | Gets a value indicating whether the frame is compressed. |
| [getEncryption()](#getEncryption--) | Gets a value indicating whether the frame is encrypted. |
| [getGroupingIdentity()](#getGroupingIdentity--) | Gets a value indicating whether the frame belongs to a group of frames. |
| [getUnsynchronisation()](#getUnsynchronisation--) | Gets a value indicating whether unsynchronisation was applied to this frame. |
| [getDataLengthIndicator()](#getDataLengthIndicator--) | Gets a value indicating whether a data length indicator has been added to the frame. |
| [equals(ID3V2TagFrameFlags other)](#equals-com.groupdocs.metadata.core.ID3V2TagFrameFlags-) | Indicates whether the current object is equal to another object of the same type. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified object is equal to this instance. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
### getTagAlterPreservation() {#getTagAlterPreservation--}
```
public final boolean getTagAlterPreservation()
```


Gets the flag that tells the software what to do with this frame if it is unknown and the tag is altered in any way. This applies to all kinds of alterations, including adding more padding and reordering the frames.

**Returns:**
boolean - The flag that tells the software what to do with this frame if it is unknown and the tag is altered in any way.
### getFileAlterPreservation() {#getFileAlterPreservation--}
```
public final boolean getFileAlterPreservation()
```


Gets the flag that tells the software what to do with this frame if it is unknown and the file, excluding the tag, is altered. This does not apply when the audio is completely replaced with other audio data.

**Returns:**
boolean - Gets the flag that tells the software what to do with this frame if it is unknown and the file, excluding the tag, is altered.
### getReadOnly() {#getReadOnly--}
```
public final boolean getReadOnly()
```


Gets the tag that tells the software that the contents of this frame is intended to be read-only.

**Returns:**
boolean - The tag that tells the software that the contents of this frame is intended to be read-only.
### getCompression() {#getCompression--}
```
public final boolean getCompression()
```


Gets a value indicating whether the frame is compressed.

**Returns:**
boolean -  true , if the frame is compressed; otherwise, false.
### getEncryption() {#getEncryption--}
```
public final boolean getEncryption()
```


Gets a value indicating whether the frame is encrypted. If set one byte indicating with which method it was encrypted will be appended to the frame header.

**Returns:**
boolean -  true , if the frame is encrypted; otherwise, false.
### getGroupingIdentity() {#getGroupingIdentity--}
```
public final boolean getGroupingIdentity()
```


Gets a value indicating whether the frame belongs to a group of frames. If set a group identifier byte is added to the frame header. Every frame with the same group identifier belongs to the same group.

**Returns:**
boolean -  true , if the frame belongs to a group of frames; otherwise, false.
### getUnsynchronisation() {#getUnsynchronisation--}
```
public final boolean getUnsynchronisation()
```


Gets a value indicating whether unsynchronisation was applied to this frame.

**Returns:**
boolean -  true , if unsynchronisation was applied to this frame; otherwise, false.
### getDataLengthIndicator() {#getDataLengthIndicator--}
```
public final boolean getDataLengthIndicator()
```


Gets a value indicating whether a data length indicator has been added to the frame. The data length indicator is the value one would write as the 'Frame length' if all of the frame format flags were zeroed, represented as a 32 bit synchsafe integer.

**Returns:**
boolean -  true , if a data length indicator has been added to the frame; otherwise, false.
### equals(ID3V2TagFrameFlags other) {#equals-com.groupdocs.metadata.core.ID3V2TagFrameFlags-}
```
public final boolean equals(ID3V2TagFrameFlags other)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [ID3V2TagFrameFlags](../../com.groupdocs.metadata.core/id3v2tagframeflags) | An object to compare with this object. |

**Returns:**
boolean - true if the current object is equal to the  other  parameter; otherwise, false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified object is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The  System.Object  to compare with this instance. |

**Returns:**
boolean -  true  if the specified  System.Object  is equal to this instance; otherwise,  false .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
