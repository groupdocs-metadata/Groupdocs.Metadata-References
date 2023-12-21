---
title: OpenTypeRootPackage
second_title: GroupDocs.Signature for Java API Reference
description: Represents the root package allowing working with metadata in an OpenType font file.
type: docs
weight: 178
url: /java/com.groupdocs.metadata.core/opentyperootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)
```
public class OpenTypeRootPackage extends RootMetadataPackage
```

Represents the root package allowing working with metadata in an OpenType font file.

**Learn more**

 *  [Working with OpenType fonts][]

This example shows how to read OpenType font metadata.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputTtf)) {
>      OpenTypeRootPackage root = metadata.getRootPackageGeneric();
>      // Read the OpenType font metadata
>      for (OpenTypeFont metadataEntry : root.getOpenTypePackage().getFonts()) {
>          // Display the values of some metadata properties
>          System.out.println(metadataEntry.getCreated());
>          System.out.println(metadataEntry.getDirectionHint());
>          System.out.println(metadataEntry.getEmbeddingLicensingRights());
>          System.out.println(metadataEntry.getFlags());
>          System.out.println(metadataEntry.getFontFamilyName());
>          System.out.println(metadataEntry.getFontRevision());
>          System.out.println(metadataEntry.getFontSubfamilyName());
>          System.out.println(metadataEntry.getFullFontName());
>          System.out.println(metadataEntry.getGlyphBounds());
>          System.out.println(metadataEntry.getMajorVersion());
>          System.out.println(metadataEntry.getMinorVersion());
>          System.out.println(metadataEntry.getModified());
>          System.out.println(metadataEntry.getSfntVersion());
>          System.out.println(metadataEntry.getStyle());
>          System.out.println(metadataEntry.getTypographicFamily());
>          System.out.println(metadataEntry.getTypographicSubfamily());
>          System.out.println(metadataEntry.getWeight());
>          System.out.println(metadataEntry.getWidth());
>          for (OpenTypeBaseNameRecord nameRecord : metadataEntry.getNames()) {
>              System.out.println(nameRecord.getNameID());
>              System.out.println(nameRecord.getPlatform());
>              System.out.println(nameRecord.getValue());
>              if (nameRecord instanceof OpenTypeMacintoshNameRecord) {
>                  OpenTypeMacintoshNameRecord macintoshNameRecord = (OpenTypeMacintoshNameRecord) nameRecord;
>                  System.out.println(macintoshNameRecord.getEncoding());
>                  System.out.println(macintoshNameRecord.getLanguage());
>              } else {
>                  if (nameRecord instanceof OpenTypeUnicodeNameRecord) {
>                      OpenTypeUnicodeNameRecord unicodeNameRecord = (OpenTypeUnicodeNameRecord) nameRecord;
>                      System.out.println(unicodeNameRecord.getEncoding());
>                  } else {
>                      if (nameRecord instanceof OpenTypeWindowsNameRecord) {
>                          OpenTypeWindowsNameRecord windowsNameRecord = (OpenTypeWindowsNameRecord) nameRecord;
>                          System.out.println(windowsNameRecord.getEncoding());
>                          System.out.println(windowsNameRecord.getLanguage());
>                      }
>                  }
>              }
>          }
>      }
>  }
>  
> ```
> ```


[Working with OpenType fonts]: https://docs.groupdocs.com/display/metadatajava/Working+with+OpenType+fonts
## Methods

| Method | Description |
| --- | --- |
| [getOpenTypePackage()](#getOpenTypePackage--) | Gets the OpenType metadata package. |
| [getDigitalSignaturePackage()](#getDigitalSignaturePackage--) | Gets the digital signature metadata package. |
### getOpenTypePackage() {#getOpenTypePackage--}
```
public final OpenTypePackage getOpenTypePackage()
```


Gets the OpenType metadata package.

**Returns:**
[OpenTypePackage](../../com.groupdocs.metadata.core/opentypepackage) - The OpenType metadata package.
### getDigitalSignaturePackage() {#getDigitalSignaturePackage--}
```
public final CmsPackage getDigitalSignaturePackage()
```


Gets the digital signature metadata package.

**Returns:**
[CmsPackage](../../com.groupdocs.metadata.core/cmspackage) - The digital signature metadata package.
