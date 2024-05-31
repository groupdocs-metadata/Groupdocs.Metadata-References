---
title: XmpTimecode
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a timecode value in a video.
type: docs
weight: 345
url: /nodejs-java/com.groupdocs.metadata.core/xmptimecode/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpComplexType](../../com.groupdocs.metadata.core/xmpcomplextype)
```
public final class XmpTimecode extends XmpComplexType
```

Represents a timecode value in a video.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpTimecode()](#XmpTimecode--) | Initializes a new instance of the  XmpTimecode  class. |
| [XmpTimecode(XmpTimeFormat format, String timeValue)](#XmpTimecode-com.groupdocs.metadata.core.XmpTimeFormat-java.lang.String-) | Initializes a new instance of the  XmpTimecode  class. |
## Methods

| Method | Description |
| --- | --- |
| [getTimeFormat()](#getTimeFormat--) | Gets the format used in the time value. |
| [setTimeFormat(String value)](#setTimeFormat-java.lang.String-) | Sets the format used in the time value. |
| [getTimeValue()](#getTimeValue--) | Gets the time value in the specified format. |
| [setTimeValue(String value)](#setTimeValue-java.lang.String-) | Sets the time value in the specified format. |
| [setTimeFormat(XmpTimeFormat timeFormat)](#setTimeFormat-com.groupdocs.metadata.core.XmpTimeFormat-) | Sets the time format. |
### XmpTimecode() {#XmpTimecode--}
```
public XmpTimecode()
```


Initializes a new instance of the  XmpTimecode  class.

### XmpTimecode(XmpTimeFormat format, String timeValue) {#XmpTimecode-com.groupdocs.metadata.core.XmpTimeFormat-java.lang.String-}
```
public XmpTimecode(XmpTimeFormat format, String timeValue)
```


Initializes a new instance of the  XmpTimecode  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | [XmpTimeFormat](../../com.groupdocs.metadata.core/xmptimeformat) | Time format. |
| timeValue | java.lang.String | Time value. |

### getTimeFormat() {#getTimeFormat--}
```
public final String getTimeFormat()
```


Gets the format used in the time value.

**Returns:**
java.lang.String - The format used in the timeValue. One of: 24Timecode, 25Timecode, 2997DropTimecode (semicolon delimiter), 2997NonDropTimecode, 30Timecode, 50Timecode, 5994DropTimecode (semicolon delimiter), 5994NonDropTimecode, 60Timecode, 23976Timecode.
### setTimeFormat(String value) {#setTimeFormat-java.lang.String-}
```
public final void setTimeFormat(String value)
```


Sets the format used in the time value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The format used in the timeValue. One of: 24Timecode, 25Timecode, 2997DropTimecode (semicolon delimiter), 2997NonDropTimecode, 30Timecode, 50Timecode, 5994DropTimecode (semicolon delimiter), 5994NonDropTimecode, 60Timecode, 23976Timecode. |

### getTimeValue() {#getTimeValue--}
```
public final String getTimeValue()
```


Gets the time value in the specified format. Time values use a colon delimiter in all formats except 2997drop and 5994drop, which uses a semicolon. The four fields indicate hours, minutes, seconds, and frames: hh:mm:ss:ff

**Returns:**
java.lang.String - The time value in the specified format. Time values use a colon delimiter in all formats except 2997drop and 5994drop, which uses a semicolon. The four fields indicate hours, minutes, seconds, and frames: hh:mm:ss:ff
### setTimeValue(String value) {#setTimeValue-java.lang.String-}
```
public final void setTimeValue(String value)
```


Sets the time value in the specified format. Time values use a colon delimiter in all formats except 2997drop and 5994drop, which uses a semicolon. The four fields indicate hours, minutes, seconds, and frames: hh:mm:ss:ff

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The time value in the specified format. Time values use a colon delimiter in all formats except 2997drop and 5994drop, which uses a semicolon. The four fields indicate hours, minutes, seconds, and frames: hh:mm:ss:ff |

### setTimeFormat(XmpTimeFormat timeFormat) {#setTimeFormat-com.groupdocs.metadata.core.XmpTimeFormat-}
```
public final void setTimeFormat(XmpTimeFormat timeFormat)
```


Sets the time format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| timeFormat | [XmpTimeFormat](../../com.groupdocs.metadata.core/xmptimeformat) | The time format. |

