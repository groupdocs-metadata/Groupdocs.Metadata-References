---
title: CadRootPackage
second_title: GroupDocs.Signature for Java API Reference
description: Represents the root package allowing working with metadata in a CAD drawing.
type: docs
weight: 31
url: /java/com.groupdocs.metadata.core/cadrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)
```
public abstract class CadRootPackage extends RootMetadataPackage
```

Represents the root package allowing working with metadata in a CAD drawing.

**Learn more**

 *  [Working with CAD metadata][]

This code sample shows how to read metadata of a CAD drawing.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputDxf)) {
>      CadRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getCadPackage().getAcadVersion());
>      System.out.println(root.getCadPackage().getAuthor());
>      System.out.println(root.getCadPackage().getComments());
>      System.out.println(root.getCadPackage().getCreatedDateTime());
>      System.out.println(root.getCadPackage().getHyperlinkBase());
>      System.out.println(root.getCadPackage().getKeywords());
>      System.out.println(root.getCadPackage().getLastSavedBy());
>      System.out.println(root.getCadPackage().getTitle());
>      // ...
>  }
>  
> ```
> ```


[Working with CAD metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+CAD+metadata
## Methods

| Method | Description |
| --- | --- |
| [getCadPackage()](#getCadPackage--) | Gets the CAD metadata package. |
### getCadPackage() {#getCadPackage--}
```
public final CadPackage getCadPackage()
```


Gets the CAD metadata package.

**Returns:**
[CadPackage](../../com.groupdocs.metadata.core/cadpackage) - The CAD metadata package.
