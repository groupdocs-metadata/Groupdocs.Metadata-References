---
title: XmpResourceRef
second_title: GroupDocs.Metadata for Java API Reference
description: 
type: docs
weight: 290
url: /java/com.groupdocs.metadata.core/xmpresourceref/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpComplexType](../../com.groupdocs.metadata.core/xmpcomplextype)
```
public final class XmpResourceRef extends XmpComplexType
```

Represents a multiple part reference to a resource. 

 Used to indicate prior versions, originals of renditions, originals for derived documents, and so on.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpResourceRef()](#XmpResourceRef--) | Initializes a new instance of the  XmpResourceRef  class. |
## Methods

| Method | Description |
| --- | --- |
| [getAlternatePaths()](#getAlternatePaths--) | Gets the referenced resource\\u2019s fallback file paths or URLs. |
| [setAlternatePaths(String[] value)](#setAlternatePaths-java.lang.String---) | Sets the referenced resource\\u2019s fallback file paths or URLs. |
| [getDocumentID()](#getDocumentID--) | Gets the value of the xmpMM:DocumentID property from the referenced resource. |
| [setDocumentID(String value)](#setDocumentID-java.lang.String-) | Sets the value of the xmpMM:DocumentID property from the referenced resource. |
| [getFilePath()](#getFilePath--) | Gets the referenced resource\\u2019s file path or URL. |
| [setFilePath(String value)](#setFilePath-java.lang.String-) | Sets the referenced resource\\u2019s file path or URL. |
| [getInstanceID()](#getInstanceID--) | Gets the value of the xmpMM:InstanceID property from the referenced resource. |
| [setInstanceID(String value)](#setInstanceID-java.lang.String-) | Sets the value of the xmpMM:InstanceID property from the referenced resource. |
| [getLastModifyDate()](#getLastModifyDate--) | Gets the value of stEvt:when for the last time the file was written. |
| [setLastModifyDate(Date value)](#setLastModifyDate-java.util.Date-) | Sets the value of stEvt:when for the last time the file was written. |
| [getManager()](#getManager--) | Gets the referenced resource\\u2019s xmpMM:Manager. |
| [setManager(String value)](#setManager-java.lang.String-) | Sets the referenced resource\\u2019s xmpMM:Manager. |
| [getManagerVariant()](#getManagerVariant--) | Gets the referenced resource\\u2019s xmpMM:Manager. |
| [setManagerVariant(String value)](#setManagerVariant-java.lang.String-) | Sets the referenced resource\\u2019s xmpMM:Manager. |
| [getManageTo()](#getManageTo--) | Gets the referenced resource\\u2019s xmpMM:ManageTo. |
| [setManageTo(String value)](#setManageTo-java.lang.String-) | Sets the referenced resource\\u2019s xmpMM:ManageTo. |
| [getManageUI()](#getManageUI--) | Gets the referenced resource\\u2019s xmpMM:ManageUI. |
| [setManageUI(String value)](#setManageUI-java.lang.String-) | Sets the referenced resource\\u2019s xmpMM:ManageUI. |
| [getPartMapping()](#getPartMapping--) | Gets the name or URI of a mapping function used to map the fromPart to the toPart. |
| [setPartMapping(String value)](#setPartMapping-java.lang.String-) | Sets the name or URI of a mapping function used to map the fromPart to the toPart. |
| [getRenditionClass()](#getRenditionClass--) | Gets the value of the xmpMM:RenditionClass property from the referenced resource. |
| [setRenditionClass(String value)](#setRenditionClass-java.lang.String-) | Sets the value of the xmpMM:RenditionClass property from the referenced resource. |
| [getRenditionParams()](#getRenditionParams--) | Gets the value of the xmpMM:RenditionParams property from the referenced resource. |
| [setRenditionParams(String value)](#setRenditionParams-java.lang.String-) | Sets the value of the xmpMM:RenditionParams property from the referenced resource. |
| [getVersionID()](#getVersionID--) | Gets the value of the xmpMM:RenditionParams property from the referenced resource. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | Sets the value of the xmpMM:RenditionParams property from the referenced resource. |
### XmpResourceRef() {#XmpResourceRef--}
```
public XmpResourceRef()
```


Initializes a new instance of the  XmpResourceRef  class.

### getAlternatePaths() {#getAlternatePaths--}
```
public final String[] getAlternatePaths()
```


Gets the referenced resource\\u2019s fallback file paths or URLs.

**Returns:**
java.lang.String[] - The referenced resource\\u2019s fallback file paths or URLs. The sequence order is the recommended order in attempting to locate the resource.
### setAlternatePaths(String[] value) {#setAlternatePaths-java.lang.String---}
```
public final void setAlternatePaths(String[] value)
```


Sets the referenced resource\\u2019s fallback file paths or URLs.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The referenced resource\\u2019s fallback file paths or URLs. The sequence order is the recommended order in attempting to locate the resource. |

### getDocumentID() {#getDocumentID--}
```
public final String getDocumentID()
```


Gets the value of the xmpMM:DocumentID property from the referenced resource.

**Returns:**
java.lang.String - The value of the xmpMM:DocumentID property from the referenced resource.
### setDocumentID(String value) {#setDocumentID-java.lang.String-}
```
public final void setDocumentID(String value)
```


Sets the value of the xmpMM:DocumentID property from the referenced resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value of the xmpMM:DocumentID property from the referenced resource. |

### getFilePath() {#getFilePath--}
```
public final String getFilePath()
```


Gets the referenced resource\\u2019s file path or URL.

**Returns:**
java.lang.String - The referenced resource\\u2019s file path or URL.
### setFilePath(String value) {#setFilePath-java.lang.String-}
```
public final void setFilePath(String value)
```


Sets the referenced resource\\u2019s file path or URL.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The referenced resource\\u2019s file path or URL. |

### getInstanceID() {#getInstanceID--}
```
public final String getInstanceID()
```


Gets the value of the xmpMM:InstanceID property from the referenced resource.

**Returns:**
java.lang.String - The value of the xmpMM:InstanceID property from the referenced resource.
### setInstanceID(String value) {#setInstanceID-java.lang.String-}
```
public final void setInstanceID(String value)
```


Sets the value of the xmpMM:InstanceID property from the referenced resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value of the xmpMM:InstanceID property from the referenced resource. |

### getLastModifyDate() {#getLastModifyDate--}
```
public final Date getLastModifyDate()
```


Gets the value of stEvt:when for the last time the file was written.

**Returns:**
java.util.Date - The value of stEvt:when for the last time the file was written.
### setLastModifyDate(Date value) {#setLastModifyDate-java.util.Date-}
```
public final void setLastModifyDate(Date value)
```


Sets the value of stEvt:when for the last time the file was written.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The value of stEvt:when for the last time the file was written. |

### getManager() {#getManager--}
```
public final String getManager()
```


Gets the referenced resource\\u2019s xmpMM:Manager.

**Returns:**
java.lang.String - The referenced resource\\u2019s xmpMM:Manager.
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```


Sets the referenced resource\\u2019s xmpMM:Manager.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The referenced resource\\u2019s xmpMM:Manager. |

### getManagerVariant() {#getManagerVariant--}
```
public final String getManagerVariant()
```


Gets the referenced resource\\u2019s xmpMM:Manager.

**Returns:**
java.lang.String - The referenced resource\\u2019s xmpMM:Manager.
### setManagerVariant(String value) {#setManagerVariant-java.lang.String-}
```
public final void setManagerVariant(String value)
```


Sets the referenced resource\\u2019s xmpMM:Manager.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The referenced resource\\u2019s xmpMM:Manager. |

### getManageTo() {#getManageTo--}
```
public final String getManageTo()
```


Gets the referenced resource\\u2019s xmpMM:ManageTo.

**Returns:**
java.lang.String - The referenced resource\\u2019s xmpMM:ManageTo.
### setManageTo(String value) {#setManageTo-java.lang.String-}
```
public final void setManageTo(String value)
```


Sets the referenced resource\\u2019s xmpMM:ManageTo.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The referenced resource\\u2019s xmpMM:ManageTo. |

### getManageUI() {#getManageUI--}
```
public final String getManageUI()
```


Gets the referenced resource\\u2019s xmpMM:ManageUI.

**Returns:**
java.lang.String - The referenced resource\\u2019s xmpMM:ManageUI.
### setManageUI(String value) {#setManageUI-java.lang.String-}
```
public final void setManageUI(String value)
```


Sets the referenced resource\\u2019s xmpMM:ManageUI.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The referenced resource\\u2019s xmpMM:ManageUI. |

### getPartMapping() {#getPartMapping--}
```
public final String getPartMapping()
```


Gets the name or URI of a mapping function used to map the fromPart to the toPart.

**Returns:**
java.lang.String - The name or URI of a mapping function used to map the fromPart to the toPart. The default for time mappings is "linear".
### setPartMapping(String value) {#setPartMapping-java.lang.String-}
```
public final void setPartMapping(String value)
```


Sets the name or URI of a mapping function used to map the fromPart to the toPart.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name or URI of a mapping function used to map the fromPart to the toPart. The default for time mappings is "linear". |

### getRenditionClass() {#getRenditionClass--}
```
public final String getRenditionClass()
```


Gets the value of the xmpMM:RenditionClass property from the referenced resource.

**Returns:**
java.lang.String - The value of the xmpMM:RenditionClass property from the referenced resource.
### setRenditionClass(String value) {#setRenditionClass-java.lang.String-}
```
public final void setRenditionClass(String value)
```


Sets the value of the xmpMM:RenditionClass property from the referenced resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value of the xmpMM:RenditionClass property from the referenced resource. |

### getRenditionParams() {#getRenditionParams--}
```
public final String getRenditionParams()
```


Gets the value of the xmpMM:RenditionParams property from the referenced resource.

**Returns:**
java.lang.String - The value of the xmpMM:RenditionParams property from the referenced resource.
### setRenditionParams(String value) {#setRenditionParams-java.lang.String-}
```
public final void setRenditionParams(String value)
```


Sets the value of the xmpMM:RenditionParams property from the referenced resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value of the xmpMM:RenditionParams property from the referenced resource. |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


Gets the value of the xmpMM:RenditionParams property from the referenced resource.

**Returns:**
java.lang.String - The value of the xmpMM:RenditionParams property from the referenced resource.
### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public final void setVersionID(String value)
```


Sets the value of the xmpMM:RenditionParams property from the referenced resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value of the xmpMM:RenditionParams property from the referenced resource. |

