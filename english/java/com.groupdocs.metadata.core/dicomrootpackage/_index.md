---
title: DicomRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package intended to work with metadata in a DICOM image.
type: docs
weight: 74
url: /java/com.groupdocs.metadata.core/dicomrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage), [com.groupdocs.metadata.core.ImageRootPackage](../../com.groupdocs.metadata.core/imagerootpackage)
```
public class DicomRootPackage extends ImageRootPackage
```

Represents the root package intended to work with metadata in a DICOM image.

**Learn more**

 *  [Working with DICOM metadata][]

This example demonstrates how to read DICOM format-specific metadata properties.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputDicom)) {
>      DicomRootPackage root = metadata.getRootPackageGeneric();
>      if (root.getDicomPackage() != null) {
>          System.out.println(root.getDicomPackage().getBitsAllocated());
>          System.out.println(root.getDicomPackage().getReds());
>          System.out.println(root.getDicomPackage().getGreens());
>          System.out.println(root.getDicomPackage().getBlues());
>          System.out.println(root.getDicomPackage().getNumberOfFrames());
>          // ...
>      }
>  }
>  
> ```
> ```


[Working with DICOM metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+DICOM+metadata
## Methods

| Method | Description |
| --- | --- |
| [getDicomPackage()](#getDicomPackage--) | Gets the DICOM native metadata package. |
### getDicomPackage() {#getDicomPackage--}
```
public final DicomPackage getDicomPackage()
```


Gets the DICOM native metadata package.

**Returns:**
[DicomPackage](../../com.groupdocs.metadata.core/dicompackage) - The DICOM native metadata package.
