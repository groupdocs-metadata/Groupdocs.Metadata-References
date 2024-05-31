---
title: XmpDate
second_title: GroupDocs.Metadata for Java API Reference
description: Represents Date in XMP packet.
type: docs
weight: 310
url: /java/com.groupdocs.metadata.core/xmpdate/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.PropertyValue](../../com.groupdocs.metadata.core/propertyvalue), [com.groupdocs.metadata.core.XmpValueBase](../../com.groupdocs.metadata.core/xmpvaluebase)
```
public final class XmpDate extends XmpValueBase
```

Represents Date in XMP packet.

--------------------

A date-time value is represented using a subset of the formats as defined in Date and Time Formats: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Initializes a new instance of the  XmpDate  class. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Initializes a new instance of the  XmpDate  class. |
## Fields

| Field | Description |
| --- | --- |
| [Iso8601Format](#Iso8601Format) | The ISO 8601 (roundtrip) format string. |
## Methods

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | Gets the value. |
| [getFormat()](#getFormat--) | Gets format string for current value. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Returns string contained value in XMP format. |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Initializes a new instance of the  XmpDate  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dateTime | java.util.Date |  DateTime  value. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Initializes a new instance of the  XmpDate  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dateString | java.lang.String | Date in string representation. |

### Iso8601Format {#Iso8601Format}
```
public static final String Iso8601Format
```


The ISO 8601 (roundtrip) format string.

--------------------

See more: https://en.wikipedia.org/wiki/ISO\_8601.

### getValue() {#getValue--}
```
public final Date getValue()
```


Gets the value.

**Returns:**
java.util.Date - DateTime value.
### getFormat() {#getFormat--}
```
public final String getFormat()
```


Gets format string for current value.

**Returns:**
java.lang.String - XMP date format string.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Returns string contained value in XMP format.

**Returns:**
java.lang.String -  string  contained XMP representation.
