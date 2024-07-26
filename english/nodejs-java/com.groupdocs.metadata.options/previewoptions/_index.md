---
title: PreviewOptions
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Provides options to sets requirements and stream delegates for preview generation.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.metadata.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Provides options to sets requirements and stream delegates for preview generation.
## Constructors

| Constructor | Description |
| --- | --- |
| [PreviewOptions(ICreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.metadata.options.ICreatePageStream-) | Initializes a new instance of the  PreviewOptions  class causing the output stream to be closed. |
| [PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.metadata.options.ICreatePageStream-com.groupdocs.metadata.options.IReleasePageStream-) | Initializes a new instance of  PreviewOptions  class causing the output stream to be returned to the client for further use. |
## Methods

| Method | Description |
| --- | --- |
| [getCacheFolder()](#getCacheFolder--) | Gets the cache folder. |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Sets the cache folder. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Gets the maximum available disk space for cache in bytes. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Sets the maximum available disk space for cache in bytes. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Gets the maximum available memory for cache in memory in bytes. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Sets the maximum available memory for cache in memory in bytes. |
| [getWidth()](#getWidth--) | Gets the page preview width. |
| [setWidth(int value)](#setWidth-int-) | Sets the page preview width. |
| [getHeight()](#getHeight--) | Gets the page preview height. |
| [setHeight(int value)](#setHeight-int-) | Sets the page preview height. |
| [getPageNumbers()](#getPageNumbers--) | Gets an array of page numbers to generate previews. |
| [setPageNumbers(int[] value)](#setPageNumbers-int---) | Sets an array of page numbers to generate previews. |
| [getPreviewFormat()](#getPreviewFormat--) | Gets the preview image format. |
| [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.metadata.options.PreviewFormats-) | Sets the preview image format. |
| [getCreatePageStream()](#getCreatePageStream--) | Gets an instance of the page stream creation delegate. |
| [setCreatePageStream(ICreatePageStream value)](#setCreatePageStream-com.groupdocs.metadata.options.ICreatePageStream-) | Sets an instance of the page stream creation delegate. |
| [getReleasePageStream()](#getReleasePageStream--) | Gets an instance of the page preview completion delegate. |
| [setReleasePageStream(IReleasePageStream value)](#setReleasePageStream-com.groupdocs.metadata.options.IReleasePageStream-) | Sets an instance of the page preview completion delegate. |
| [getResolution()](#getResolution--) | Gets or sets the page preview resolution. |
| [setResolution(int value)](#setResolution-int-) | Gets or sets the page preview resolution. |
### PreviewOptions(ICreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.metadata.options.ICreatePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream)
```


Initializes a new instance of the  PreviewOptions  class causing the output stream to be closed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [ICreatePageStream](../../com.groupdocs.metadata.options/icreatepagestream) | Creates a stream for a specific page preview. |

### PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.metadata.options.ICreatePageStream-com.groupdocs.metadata.options.IReleasePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initializes a new instance of  PreviewOptions  class causing the output stream to be returned to the client for further use.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [ICreatePageStream](../../com.groupdocs.metadata.options/icreatepagestream) | Creates a stream for a specific page preview |
| releasePageStream | [IReleasePageStream](../../com.groupdocs.metadata.options/ireleasepagestream) | Notifies that the page preview generation is done and gets the output stream. |

### getCacheFolder() {#getCacheFolder--}
```
public final String getCacheFolder()
```


Gets the cache folder. By default the cache folder is set to user's local temp directory.

**Returns:**
java.lang.String - The cache folder.
### setCacheFolder(String value) {#setCacheFolder-java.lang.String-}
```
public final void setCacheFolder(String value)
```


Sets the cache folder. By default the cache folder is set to user's local temp directory.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The cache folder. |

### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public final int getMaxDiskSpaceForCache()
```


Gets the maximum available disk space for cache in bytes. The default value is 1073741824.

**Returns:**
int - The maximum available disk space for cache in bytes.
### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public final void setMaxDiskSpaceForCache(int value)
```


Sets the maximum available disk space for cache in bytes. The default value is 1073741824.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The maximum available disk space for cache in bytes. |

### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public final int getMaxMemoryForCache()
```


Gets the maximum available memory for cache in memory in bytes. The default value is 1073741824.

**Returns:**
int - The maximum available memory for cache in memory in bytes.
### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public final void setMaxMemoryForCache(int value)
```


Sets the maximum available memory for cache in memory in bytes. The default value is 1073741824.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The maximum available memory for cache in memory in bytes. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets the page preview width.

**Returns:**
int - The page preview width.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Sets the page preview width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The page preview width. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets the page preview height.

**Returns:**
int - The page preview height.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Sets the page preview height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The page preview height. |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Gets an array of page numbers to generate previews.

**Returns:**
int[] - An array of page numbers to generate previews.
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Sets an array of page numbers to generate previews.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | An array of page numbers to generate previews. |

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


Gets the preview image format.

**Returns:**
[PreviewFormats](../../com.groupdocs.metadata.options/previewformats) - The preview image format.
### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.metadata.options.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


Sets the preview image format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PreviewFormats](../../com.groupdocs.metadata.options/previewformats) | The preview image format. |

### getCreatePageStream() {#getCreatePageStream--}
```
public final ICreatePageStream getCreatePageStream()
```


Gets an instance of the page stream creation delegate.

**Returns:**
[ICreatePageStream](../../com.groupdocs.metadata.options/icreatepagestream) - An instance of the page stream creation delegate.
### setCreatePageStream(ICreatePageStream value) {#setCreatePageStream-com.groupdocs.metadata.options.ICreatePageStream-}
```
public final void setCreatePageStream(ICreatePageStream value)
```


Sets an instance of the page stream creation delegate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ICreatePageStream](../../com.groupdocs.metadata.options/icreatepagestream) | An instance of the page stream creation delegate. |

### getReleasePageStream() {#getReleasePageStream--}
```
public final IReleasePageStream getReleasePageStream()
```


Gets an instance of the page preview completion delegate.

**Returns:**
[IReleasePageStream](../../com.groupdocs.metadata.options/ireleasepagestream) - An instance of the page preview completion delegate.
### setReleasePageStream(IReleasePageStream value) {#setReleasePageStream-com.groupdocs.metadata.options.IReleasePageStream-}
```
public final void setReleasePageStream(IReleasePageStream value)
```


Sets an instance of the page preview completion delegate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IReleasePageStream](../../com.groupdocs.metadata.options/ireleasepagestream) | An instance of the page preview completion delegate. |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Gets or sets the page preview resolution.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Gets or sets the page preview resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

