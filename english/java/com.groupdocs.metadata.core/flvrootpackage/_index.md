---
title: FlvRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package allowing working with metadata in an FLV video.
type: docs
weight: 103
url: /java/com.groupdocs.metadata.core/flvrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmp](../../com.groupdocs.metadata.core/ixmp)
```
public class FlvRootPackage extends RootMetadataPackage implements IXmp
```

Represents the root package allowing working with metadata in an FLV video.

**Learn more**

 *  [Working with metadata in FLV files][]
 *  [Working with XMP metadata][]

This example shows how to read FLV header properties.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputFlv)) {
>      FlvRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getHeader().getVersion());
>      System.out.println(root.getHeader().hasAudioTags());
>      System.out.println(root.getHeader().hasVideoTags());
>      System.out.println(root.getHeader().getTypeFlags());
>  }
>  
> ```
> ```


[Working with metadata in FLV files]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+FLV+files
[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata
## Methods

| Method | Description |
| --- | --- |
| [getXmpPackage()](#getXmpPackage--) | Gets the XMP metadata package. |
| [setXmpPackage(XmpPacketWrapper value)](#setXmpPackage-com.groupdocs.metadata.core.XmpPacketWrapper-) | Sets the XMP metadata package. |
| [getHeader()](#getHeader--) | Gets the FLV header package. |
### getXmpPackage() {#getXmpPackage--}
```
public final XmpPacketWrapper getXmpPackage()
```


Gets the XMP metadata package.

**Returns:**
[XmpPacketWrapper](../../com.groupdocs.metadata.core/xmppacketwrapper) - The XMP metadata package.

**Learn more**

 *  [Working with XMP metadata][]


[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata
### setXmpPackage(XmpPacketWrapper value) {#setXmpPackage-com.groupdocs.metadata.core.XmpPacketWrapper-}
```
public final void setXmpPackage(XmpPacketWrapper value)
```


Sets the XMP metadata package.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.groupdocs.metadata.core/xmppacketwrapper) | The XMP metadata package.

**Learn more**

 *  [Working with XMP metadata][]


[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata |

### getHeader() {#getHeader--}
```
public final FlvHeader getHeader()
```


Gets the FLV header package.

**Returns:**
[FlvHeader](../../com.groupdocs.metadata.core/flvheader) - The FLV header package.
