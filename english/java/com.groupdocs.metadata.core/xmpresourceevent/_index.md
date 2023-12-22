---
title: XmpResourceEvent
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a high-level event that occurred in the processing of a resource.
type: docs
weight: 328
url: /java/com.groupdocs.metadata.core/xmpresourceevent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpComplexType](../../com.groupdocs.metadata.core/xmpcomplextype)
```
public final class XmpResourceEvent extends XmpComplexType
```

Represents a high-level event that occurred in the processing of a resource.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpResourceEvent()](#XmpResourceEvent--) | Initializes a new instance of the  XmpResourceEvent  class. |
## Methods

| Method | Description |
| --- | --- |
| [getAction()](#getAction--) | Gets the action that occurred. |
| [setAction(String value)](#setAction-java.lang.String-) | Sets the action that occurred. |
| [getChanged()](#getChanged--) | Gets a semicolon-delimited list of the parts of the resource that were changed since the previous event history. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Sets a semicolon-delimited list of the parts of the resource that were changed since the previous event history. |
| [getInstanceID()](#getInstanceID--) | Gets the value of the xmpMM:InstanceID property for the modified (output) resource. |
| [setInstanceID(String value)](#setInstanceID-java.lang.String-) | Sets the value of the xmpMM:InstanceID property for the modified (output) resource. |
| [getParameters()](#getParameters--) | Gets the additional description of the action. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Sets the additional description of the action. |
| [getSoftwareAgent()](#getSoftwareAgent--) | Gets the software agent that performed the action. |
| [setSoftwareAgent(String value)](#setSoftwareAgent-java.lang.String-) | Sets the software agent that performed the action. |
| [getWhen()](#getWhen--) | Gets the timestamp of when the action occurred. |
| [setWhen(Date value)](#setWhen-java.util.Date-) | Sets the timestamp of when the action occurred. |
### XmpResourceEvent() {#XmpResourceEvent--}
```
public XmpResourceEvent()
```


Initializes a new instance of the  XmpResourceEvent  class.

### getAction() {#getAction--}
```
public final String getAction()
```


Gets the action that occurred.

**Returns:**
java.lang.String - The action that occurred. Defined values are: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. New values should be verbs in the past tense.
### setAction(String value) {#setAction-java.lang.String-}
```
public final void setAction(String value)
```


Sets the action that occurred.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The action that occurred. Defined values are: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. New values should be verbs in the past tense. |

### getChanged() {#getChanged--}
```
public final String getChanged()
```


Gets a semicolon-delimited list of the parts of the resource that were changed since the previous event history.

**Returns:**
java.lang.String - A semicolon-delimited list of the parts of the resource that were changed since the previous event history.
### setChanged(String value) {#setChanged-java.lang.String-}
```
public final void setChanged(String value)
```


Sets a semicolon-delimited list of the parts of the resource that were changed since the previous event history.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A semicolon-delimited list of the parts of the resource that were changed since the previous event history. |

### getInstanceID() {#getInstanceID--}
```
public final String getInstanceID()
```


Gets the value of the xmpMM:InstanceID property for the modified (output) resource.

**Returns:**
java.lang.String - The value of the xmpMM:InstanceID property for the modified (output) resource.
### setInstanceID(String value) {#setInstanceID-java.lang.String-}
```
public final void setInstanceID(String value)
```


Sets the value of the xmpMM:InstanceID property for the modified (output) resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value of the xmpMM:InstanceID property for the modified (output) resource. |

### getParameters() {#getParameters--}
```
public final String getParameters()
```


Gets the additional description of the action.

**Returns:**
java.lang.String - The Additional description of the action.
### setParameters(String value) {#setParameters-java.lang.String-}
```
public final void setParameters(String value)
```


Sets the additional description of the action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The Additional description of the action. |

### getSoftwareAgent() {#getSoftwareAgent--}
```
public final String getSoftwareAgent()
```


Gets the software agent that performed the action.

**Returns:**
java.lang.String - The software agent that performed the action.
### setSoftwareAgent(String value) {#setSoftwareAgent-java.lang.String-}
```
public final void setSoftwareAgent(String value)
```


Sets the software agent that performed the action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The software agent that performed the action. |

### getWhen() {#getWhen--}
```
public final Date getWhen()
```


Gets the timestamp of when the action occurred.

**Returns:**
java.util.Date - The timestamp of when the action occurred. For events that create or write to a file, this should be the approximate modification time of the file.
### setWhen(Date value) {#setWhen-java.util.Date-}
```
public final void setWhen(Date value)
```


Sets the timestamp of when the action occurred.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The timestamp of when the action occurred. For events that create or write to a file, this should be the approximate modification time of the file. |

