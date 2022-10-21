---
title: OpenTypeLicensingRights
second_title: GroupDocs.Metadata for Java API Reference
description: Indicates font embedding licensing rights for the font.
type: docs
weight: 143
url: /java/com.groupdocs.metadata.core/opentypelicensingrights/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public final class OpenTypeLicensingRights implements IEnumValue
```

Indicates font embedding licensing rights for the font.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | The undefined licensing rights. |
| [UsagePermissionsMask](#UsagePermissionsMask) | Usage permissions mask. |
| [InstallableEmbedding](#InstallableEmbedding) | Installable embedding. |
| [RestrictedLicenseEmbedding](#RestrictedLicenseEmbedding) | Restricted License embedding. |
| [PreviewAndPrintEmbedding](#PreviewAndPrintEmbedding) | Preview and Print embedding. |
| [EditableEmbedding](#EditableEmbedding) | Editable embedding. |
| [NoSubsetting](#NoSubsetting) | No subsetting. |
| [BitmapEmbeddingOnly](#BitmapEmbeddingOnly) | Bitmap embedding only. |
## Methods

| Method | Description |
| --- | --- |
| [getByRawValue(int rawValue)](#getByRawValue-int-) |  |
| [getFirst()](#getFirst--) |  |
| [getAllValues()](#getAllValues--) |  |
| [getEnumValueByRawValue(int rawValue)](#getEnumValueByRawValue-int-) |  |
| [getEnumValueByName(String name)](#getEnumValueByName-java.lang.String-) |  |
| [getRawValueType()](#getRawValueType--) |  |
| [getRawValue()](#getRawValue--) |  |
| [name()](#name--) |  |
| [equals(Object o)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### None {#None}
```
public static final OpenTypeLicensingRights None
```


The undefined licensing rights.

### UsagePermissionsMask {#UsagePermissionsMask}
```
public static final OpenTypeLicensingRights UsagePermissionsMask
```


Usage permissions mask.

### InstallableEmbedding {#InstallableEmbedding}
```
public static final OpenTypeLicensingRights InstallableEmbedding
```


Installable embedding. The font may be embedded, and may be permanently installed for use on a remote systems, or for use by other users.

### RestrictedLicenseEmbedding {#RestrictedLicenseEmbedding}
```
public static final OpenTypeLicensingRights RestrictedLicenseEmbedding
```


Restricted License embedding. The font must not be modified, embedded or exchanged in any manner without first obtaining explicit permission of the legal owner.

### PreviewAndPrintEmbedding {#PreviewAndPrintEmbedding}
```
public static final OpenTypeLicensingRights PreviewAndPrintEmbedding
```


Preview and Print embedding. The font may be embedded, and may be temporarily loaded on other systems for purposes of viewing or printing the document. Documents containing Preview & Print fonts must be opened \\u201cread-only\\u201d; no edits can be applied to the document.

### EditableEmbedding {#EditableEmbedding}
```
public static final OpenTypeLicensingRights EditableEmbedding
```


Editable embedding. The font may be embedded, and may be temporarily loaded on other systems. As with Preview and Print embedding, documents containing Editable fonts may be opened for reading. In addition, editing is permitted, including ability to format new text using the embedded font, and changes may be saved.

### NoSubsetting {#NoSubsetting}
```
public static final OpenTypeLicensingRights NoSubsetting
```


No subsetting. When this bit is set, the font may not be subsetted prior to embedding. Other embedding restrictions specified in bits 0 to 3 and bit 9 also apply.

### BitmapEmbeddingOnly {#BitmapEmbeddingOnly}
```
public static final OpenTypeLicensingRights BitmapEmbeddingOnly
```


Bitmap embedding only. When this bit is set, only bitmaps contained in the font may be embedded. No outline data may be embedded. If there are no bitmaps available in the font, then the font is considered unembeddable and the embedding services will fail. Other embedding restrictions specified in bits 0-3 and 8 also apply.

### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static OpenTypeLicensingRights getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[OpenTypeLicensingRights](../../com.groupdocs.metadata.core/opentypelicensingrights)
### getFirst() {#getFirst--}
```
public static IEnumValue getFirst()
```




**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getAllValues() {#getAllValues--}
```
public Object[] getAllValues()
```


Returns the array of all values defined in the class.

**Returns:**
java.lang.Object[]
### getEnumValueByRawValue(int rawValue) {#getEnumValueByRawValue-int-}
```
public IEnumValue getEnumValueByRawValue(int rawValue)
```


Returns the enumeration value by the raw value associated with it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getEnumValueByName(String name) {#getEnumValueByName-java.lang.String-}
```
public IEnumValue getEnumValueByName(String name)
```


Returns the enumeration value by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getRawValueType() {#getRawValueType--}
```
public RawIntegerType getRawValueType()
```


Returns the underlying type of the raw value of this enumeration value.

**Returns:**
[RawIntegerType](../../com.groupdocs.metadata.core/rawintegertype)
### getRawValue() {#getRawValue--}
```
public int getRawValue()
```


Returns the raw value of this enumeration value.

**Returns:**
int
### name() {#name--}
```
public String name()
```


Returns the name of this enumeration value.

**Returns:**
java.lang.String
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
