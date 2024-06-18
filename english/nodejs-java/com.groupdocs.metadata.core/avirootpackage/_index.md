---
title: AviRootPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents the root package allowing working with metadata in an AVI video.
type: docs
weight: 26
url: /nodejs-java/com.groupdocs.metadata.core/avirootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmp](../../com.groupdocs.metadata.core/ixmp)
```
public class AviRootPackage extends RootMetadataPackage implements IXmp
```

Represents the root package allowing working with metadata in an AVI video.

**Learn more**

 *  [Working with metadata in AVI files][]
 *  [Working with XMP metadata][]

This code snippet shows how to read AVI header properties.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputAvi)) {
>      AviRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getHeader().getAviHeaderFlags());
>      System.out.println(root.getHeader().getHeight());
>      System.out.println(root.getHeader().getWidth());
>      System.out.println(root.getHeader().getTotalFrames());
>      System.out.println(root.getHeader().getInitialFrames());
>      System.out.println(root.getHeader().getMaxBytesPerSec());
>      System.out.println(root.getHeader().getPaddingGranularity());
>      System.out.println(root.getHeader().getStreams());
>      // ...
>  }
>  
> ```
> ```


[Working with metadata in AVI files]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+AVI+files
[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata
## Methods

| Method | Description |
| --- | --- |
| [getXmpPackage()](#getXmpPackage--) | Gets the XMP metadata package. |
| [setXmpPackage(XmpPacketWrapper value)](#setXmpPackage-com.groupdocs.metadata.core.XmpPacketWrapper-) | Sets the XMP metadata package. |
| [getHeader()](#getHeader--) | Gets the AVI header package. |
| [getRiffInfoPackage()](#getRiffInfoPackage--) | Gets the package containing RIFF Info tags. |
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
public final AviHeader getHeader()
```


Gets the AVI header package.

**Returns:**
[AviHeader](../../com.groupdocs.metadata.core/aviheader) - The AVI header package.
### getRiffInfoPackage() {#getRiffInfoPackage--}
```
public final RiffInfoPackage getRiffInfoPackage()
```


Gets the package containing RIFF Info tags.

**Returns:**
[RiffInfoPackage](../../com.groupdocs.metadata.core/riffinfopackage) - The package containing RIFF Info tags.
