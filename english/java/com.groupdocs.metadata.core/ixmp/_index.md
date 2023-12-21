---
title: IXmp
second_title: GroupDocs.Metadata for Java API Reference
description: Defines base operations intended to work with XMP metadata.
type: docs
weight: 351
url: /java/com.groupdocs.metadata.core/ixmp/
---```
public interface IXmp
```

Defines base operations intended to work with XMP metadata.

**Learn more**

 *  [Working with XMP metadata][]

This example demonstrates how to extract XMP metadata from a file.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.PngWithXmp)) {
>      IXmp root = (IXmp) metadata.getRootPackage();
>      if (root.getXmpPackage() != null) {
>          if (root.getXmpPackage().getSchemes().getXmpBasic() != null) {
>              System.out.println(root.getXmpPackage().getSchemes().getXmpBasic().getCreatorTool());
>              System.out.println(root.getXmpPackage().getSchemes().getXmpBasic().getCreateDate());
>              System.out.println(root.getXmpPackage().getSchemes().getXmpBasic().getModifyDate());
>              System.out.println(root.getXmpPackage().getSchemes().getXmpBasic().getLabel());
>              System.out.println(root.getXmpPackage().getSchemes().getXmpBasic().getNickname());
>              // ...
>          }
>          if (root.getXmpPackage().getSchemes().getDublinCore() != null) {
>              System.out.println(root.getXmpPackage().getSchemes().getDublinCore().getFormat());
>              System.out.println(root.getXmpPackage().getSchemes().getDublinCore().getCoverage());
>              System.out.println(root.getXmpPackage().getSchemes().getDublinCore().getIdentifier());
>              System.out.println(root.getXmpPackage().getSchemes().getDublinCore().getSource());
>              // ...
>          }
>          if (root.getXmpPackage().getSchemes().getPhotoshop() != null) {
>              System.out.println(root.getXmpPackage().getSchemes().getPhotoshop().getColorMode());
>              System.out.println(root.getXmpPackage().getSchemes().getPhotoshop().getIccProfile());
>              System.out.println(root.getXmpPackage().getSchemes().getPhotoshop().getCountry());
>              System.out.println(root.getXmpPackage().getSchemes().getPhotoshop().getCity());
>              System.out.println(root.getXmpPackage().getSchemes().getPhotoshop().getDateCreated());
>              // ...
>          }
>          // ...
>      }
>  }
>  
> ```
> ```


[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata
## Methods

| Method | Description |
| --- | --- |
| [getXmpPackage()](#getXmpPackage--) | Gets the XMP metadata package. |
| [setXmpPackage(XmpPacketWrapper value)](#setXmpPackage-com.groupdocs.metadata.core.XmpPacketWrapper-) | Sets the XMP metadata package. |
### getXmpPackage() {#getXmpPackage--}
```
public abstract XmpPacketWrapper getXmpPackage()
```


Gets the XMP metadata package.

**Returns:**
[XmpPacketWrapper](../../com.groupdocs.metadata.core/xmppacketwrapper) - The XMP metadata package.
### setXmpPackage(XmpPacketWrapper value) {#setXmpPackage-com.groupdocs.metadata.core.XmpPacketWrapper-}
```
public abstract void setXmpPackage(XmpPacketWrapper value)
```


Sets the XMP metadata package.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.groupdocs.metadata.core/xmppacketwrapper) | The XMP metadata package. |

