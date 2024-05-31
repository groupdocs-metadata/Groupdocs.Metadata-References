---
title: XmpMediaManagementPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the XMP Media Management namespace.
type: docs
weight: 325
url: /java/com.groupdocs.metadata.core/xmpmediamanagementpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpPackage](../../com.groupdocs.metadata.core/xmppackage)
```
public final class XmpMediaManagementPackage extends XmpPackage
```

Represents the XMP Media Management namespace.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage--) | Initializes a new instance of the  XmpMediaManagementPackage  class. |
## Methods

| Method | Description |
| --- | --- |
| [getDerivedFrom()](#getDerivedFrom--) | Gets the reference to the resource from which this one is derived. |
| [setDerivedFrom(XmpResourceRef value)](#setDerivedFrom-com.groupdocs.metadata.core.XmpResourceRef-) | Sets the reference to the resource from which this one is derived. |
| [getDocumentID()](#getDocumentID--) | Gets the common identifier for all versions and renditions of the resource. |
| [setDocumentID(String value)](#setDocumentID-java.lang.String-) | Sets the common identifier for all versions and renditions of the resource. |
| [getHistory()](#getHistory--) | Gets an array of high-level actions that resulted in this resource. |
| [setHistory(XmpResourceEvent[] value)](#setHistory-com.groupdocs.metadata.core.XmpResourceEvent---) | Sets an array of high-level actions that resulted in this resource. |
| [getIngredients()](#getIngredients--) | Gets the references to resources that were incorporated, by inclusion or reference, into this resource. |
| [setIngredients(XmpResourceRef[] value)](#setIngredients-com.groupdocs.metadata.core.XmpResourceRef---) | Sets the references to resources that were incorporated, by inclusion or reference, into this resource. |
| [getInstanceID()](#getInstanceID--) | Gets the identifier for a specific incarnation of a resource, updated each time the file is saved. |
| [setInstanceID(String value)](#setInstanceID-java.lang.String-) | Sets the identifier for a specific incarnation of a resource, updated each time the file is saved. |
| [getManagedFrom()](#getManagedFrom--) | Gets the reference to the document as it was prior to becoming managed. |
| [setManagedFrom(XmpResourceRef value)](#setManagedFrom-com.groupdocs.metadata.core.XmpResourceRef-) | Sets the reference to the document as it was prior to becoming managed. |
| [getManager()](#getManager--) | Gets the name of the asset management system that manages this resource. |
| [setManager(String value)](#setManager-java.lang.String-) | Sets the name of the asset management system that manages this resource. |
| [getManageTo()](#getManageTo--) | Gets the URI identifying the managed resource to the asset management system |
| [setManageTo(String value)](#setManageTo-java.lang.String-) | Sets the URI identifying the managed resource to the asset management system |
| [getManageUI()](#getManageUI--) | Gets the URI that can be used to access information about the managed resource through a web browser. |
| [setManageUI(String value)](#setManageUI-java.lang.String-) | Sets the URI that can be used to access information about the managed resource through a web browser. |
| [getManagerVariant()](#getManagerVariant--) | Gets the particular variant of the asset management system. |
| [setManagerVariant(String value)](#setManagerVariant-java.lang.String-) | Sets the particular variant of the asset management system. |
| [getOriginalDocumentID()](#getOriginalDocumentID--) | Gets the common identifier for the original resource from which the current resource is derived. |
| [setOriginalDocumentID(String value)](#setOriginalDocumentID-java.lang.String-) | Sets the common identifier for the original resource from which the current resource is derived. |
| [getRenditionClass()](#getRenditionClass--) | Gets the rendition class name for this resource. |
| [setRenditionClass(String value)](#setRenditionClass-java.lang.String-) | Sets the rendition class name for this resource. |
| [getRenditionParams()](#getRenditionParams--) | Gets the value that is used to provide additional rendition parameters that are too complex or verbose to encode in xmpMM:RenditionClass. |
| [setRenditionParams(String value)](#setRenditionParams-java.lang.String-) | Sets the value that is used to provide additional rendition parameters that are too complex or verbose to encode in xmpMM:RenditionClass. |
| [getVersionID()](#getVersionID--) | Gets the document version identifier for this resource. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | Sets the document version identifier for this resource. |
| [getVersions()](#getVersions--) | Gets the version history associated with this resource. |
| [setVersions(XmpVersion[] value)](#setVersions-com.groupdocs.metadata.core.XmpVersion---) | Sets the version history associated with this resource. |
### XmpMediaManagementPackage() {#XmpMediaManagementPackage--}
```
public XmpMediaManagementPackage()
```


Initializes a new instance of the  XmpMediaManagementPackage  class.

### getDerivedFrom() {#getDerivedFrom--}
```
public final XmpResourceRef getDerivedFrom()
```


Gets the reference to the resource from which this one is derived.

**Returns:**
[XmpResourceRef](../../com.groupdocs.metadata.core/xmpresourceref) - The the reference to the resource from which this one is derived.
### setDerivedFrom(XmpResourceRef value) {#setDerivedFrom-com.groupdocs.metadata.core.XmpResourceRef-}
```
public final void setDerivedFrom(XmpResourceRef value)
```


Sets the reference to the resource from which this one is derived.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpResourceRef](../../com.groupdocs.metadata.core/xmpresourceref) | The the reference to the resource from which this one is derived. |

### getDocumentID() {#getDocumentID--}
```
public final String getDocumentID()
```


Gets the common identifier for all versions and renditions of the resource.

**Returns:**
java.lang.String - The common identifier for all versions and renditions of the resource.
### setDocumentID(String value) {#setDocumentID-java.lang.String-}
```
public final void setDocumentID(String value)
```


Sets the common identifier for all versions and renditions of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The common identifier for all versions and renditions of the resource. |

### getHistory() {#getHistory--}
```
public final XmpResourceEvent[] getHistory()
```


Gets an array of high-level actions that resulted in this resource.

**Returns:**
com.groupdocs.metadata.core.XmpResourceEvent[] - An array of high-level actions that resulted in this resource.
### setHistory(XmpResourceEvent[] value) {#setHistory-com.groupdocs.metadata.core.XmpResourceEvent---}
```
public final void setHistory(XmpResourceEvent[] value)
```


Sets an array of high-level actions that resulted in this resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpResourceEvent\[\]](../../com.groupdocs.metadata.core/xmpresourceevent) | An array of high-level actions that resulted in this resource. |

### getIngredients() {#getIngredients--}
```
public final XmpResourceRef[] getIngredients()
```


Gets the references to resources that were incorporated, by inclusion or reference, into this resource.

**Returns:**
com.groupdocs.metadata.core.XmpResourceRef[] - The references to resources that were incorporated, by inclusion or reference, into this resource.
### setIngredients(XmpResourceRef[] value) {#setIngredients-com.groupdocs.metadata.core.XmpResourceRef---}
```
public final void setIngredients(XmpResourceRef[] value)
```


Sets the references to resources that were incorporated, by inclusion or reference, into this resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpResourceRef\[\]](../../com.groupdocs.metadata.core/xmpresourceref) | The references to resources that were incorporated, by inclusion or reference, into this resource. |

### getInstanceID() {#getInstanceID--}
```
public final String getInstanceID()
```


Gets the identifier for a specific incarnation of a resource, updated each time the file is saved.

**Returns:**
java.lang.String - The identifier for a specific incarnation of a resource, updated each time a file is saved.
### setInstanceID(String value) {#setInstanceID-java.lang.String-}
```
public final void setInstanceID(String value)
```


Sets the identifier for a specific incarnation of a resource, updated each time the file is saved.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The identifier for a specific incarnation of a resource, updated each time a file is saved. |

### getManagedFrom() {#getManagedFrom--}
```
public final XmpResourceRef getManagedFrom()
```


Gets the reference to the document as it was prior to becoming managed.

**Returns:**
[XmpResourceRef](../../com.groupdocs.metadata.core/xmpresourceref) - The reference to the document as it was prior to becoming managed.
### setManagedFrom(XmpResourceRef value) {#setManagedFrom-com.groupdocs.metadata.core.XmpResourceRef-}
```
public final void setManagedFrom(XmpResourceRef value)
```


Sets the reference to the document as it was prior to becoming managed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpResourceRef](../../com.groupdocs.metadata.core/xmpresourceref) | The reference to the document as it was prior to becoming managed. |

### getManager() {#getManager--}
```
public final String getManager()
```


Gets the name of the asset management system that manages this resource.

**Returns:**
java.lang.String - The name of the asset management system that manages this resource.
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```


Sets the name of the asset management system that manages this resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the asset management system that manages this resource. |

### getManageTo() {#getManageTo--}
```
public final String getManageTo()
```


Gets the URI identifying the managed resource to the asset management system

**Returns:**
java.lang.String - The URI identifying the managed resource to the asset management system.
### setManageTo(String value) {#setManageTo-java.lang.String-}
```
public final void setManageTo(String value)
```


Sets the URI identifying the managed resource to the asset management system

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The URI identifying the managed resource to the asset management system. |

### getManageUI() {#getManageUI--}
```
public final String getManageUI()
```


Gets the URI that can be used to access information about the managed resource through a web browser.

**Returns:**
java.lang.String - The URI that can be used to access information about the managed resource through a web browser.
### setManageUI(String value) {#setManageUI-java.lang.String-}
```
public final void setManageUI(String value)
```


Sets the URI that can be used to access information about the managed resource through a web browser.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The URI that can be used to access information about the managed resource through a web browser. |

### getManagerVariant() {#getManagerVariant--}
```
public final String getManagerVariant()
```


Gets the particular variant of the asset management system.

**Returns:**
java.lang.String - The particular variant of the asset management system. The format of this property is private to the specific asset management system.
### setManagerVariant(String value) {#setManagerVariant-java.lang.String-}
```
public final void setManagerVariant(String value)
```


Sets the particular variant of the asset management system.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The particular variant of the asset management system. The format of this property is private to the specific asset management system. |

### getOriginalDocumentID() {#getOriginalDocumentID--}
```
public final String getOriginalDocumentID()
```


Gets the common identifier for the original resource from which the current resource is derived.

**Returns:**
java.lang.String - The common identifier for the original resource from which the current resource is derived
### setOriginalDocumentID(String value) {#setOriginalDocumentID-java.lang.String-}
```
public final void setOriginalDocumentID(String value)
```


Sets the common identifier for the original resource from which the current resource is derived.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The common identifier for the original resource from which the current resource is derived |

### getRenditionClass() {#getRenditionClass--}
```
public final String getRenditionClass()
```


Gets the rendition class name for this resource.

**Returns:**
java.lang.String - The rendition class name for this resource. This property should be absent or set to default for a resource that is not a derived rendition.
### setRenditionClass(String value) {#setRenditionClass-java.lang.String-}
```
public final void setRenditionClass(String value)
```


Sets the rendition class name for this resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The rendition class name for this resource. This property should be absent or set to default for a resource that is not a derived rendition. |

### getRenditionParams() {#getRenditionParams--}
```
public final String getRenditionParams()
```


Gets the value that is used to provide additional rendition parameters that are too complex or verbose to encode in xmpMM:RenditionClass.

**Returns:**
java.lang.String - The value that is used to provide additional rendition parameters.
### setRenditionParams(String value) {#setRenditionParams-java.lang.String-}
```
public final void setRenditionParams(String value)
```


Sets the value that is used to provide additional rendition parameters that are too complex or verbose to encode in xmpMM:RenditionClass.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value that is used to provide additional rendition parameters. |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


Gets the document version identifier for this resource.

**Returns:**
java.lang.String - The document version identifier for this resource.
### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public final void setVersionID(String value)
```


Sets the document version identifier for this resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The document version identifier for this resource. |

### getVersions() {#getVersions--}
```
public final XmpVersion[] getVersions()
```


Gets the version history associated with this resource.

**Returns:**
com.groupdocs.metadata.core.XmpVersion[] - The version history associated with this resource. Entry [0] is the oldest known version for this document, entry [Versions.Length - 1] is the most recent version.
### setVersions(XmpVersion[] value) {#setVersions-com.groupdocs.metadata.core.XmpVersion---}
```
public final void setVersions(XmpVersion[] value)
```


Sets the version history associated with this resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpVersion\[\]](../../com.groupdocs.metadata.core/xmpversion) | The version history associated with this resource. Entry [0] is the oldest known version for this document, entry [Versions.Length - 1] is the most recent version. |

