---
title: MovRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package allowing working with metadata in a QuickTime video.
type: docs
weight: 164
url: /java/com.groupdocs.metadata.core/movrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmp](../../com.groupdocs.metadata.core/ixmp)
```
public class MovRootPackage extends RootMetadataPackage implements IXmp
```

Represents the root package allowing working with metadata in a QuickTime video.

**Learn more**

 *  [Working with metadata in MOV Files][]
 *  [Working with XMP metadata][]

This example shows how to read QuickTime atoms in a MOV video.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputMov)) {
>      MovRootPackage root = metadata.getRootPackageGeneric();
>      for (MovAtom atom : root.getMovPackage().getAtoms()) {
>          System.out.println(atom.getType());
>          System.out.println(atom.getOffset());
>          System.out.println(atom.getSize());
>          // ...
>      }
>  }
>  
> ```
> ```


[Working with metadata in MOV Files]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+MOV+Files
[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata
## Methods

| Method | Description |
| --- | --- |
| [getMovPackage()](#getMovPackage--) | Gets the QuickTime metadata package. |
| [getXmpPackage()](#getXmpPackage--) | Gets the XMP metadata package. |
| [setXmpPackage(XmpPacketWrapper value)](#setXmpPackage-com.groupdocs.metadata.core.XmpPacketWrapper-) | Sets the XMP metadata package. |
### getMovPackage() {#getMovPackage--}
```
public final MovPackage getMovPackage()
```


Gets the QuickTime metadata package.

**Returns:**
[MovPackage](../../com.groupdocs.metadata.core/movpackage) - The QuickTime metadata package.
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

