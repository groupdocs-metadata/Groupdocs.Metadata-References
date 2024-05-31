---
title: VCardRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package allowing working with metadata in a VCard file.
type: docs
weight: 280
url: /java/com.groupdocs.metadata.core/vcardrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)
```
public class VCardRootPackage extends RootMetadataPackage
```

Represents the root package allowing working with metadata in a VCard file.

**Learn more**

 *  [Working with vCard metadata][]

This code sample demonstrates how to read metadata properties of a vCard file.

> ```
> ```
> 
>  public static void run() {
>      try (Metadata metadata = new Metadata(Constants.InputVcf)) {
>          VCardRootPackage root = metadata.getRootPackageGeneric();
>          for (VCardCard vCard : root.getVCardPackage().getCards()) {
>              System.out.println(vCard.getIdentificationRecordset().getName());
>              PrintArray(vCard.getIdentificationRecordset().getFormattedNames());
>              PrintArray(vCard.getCommunicationRecordset().getEmails());
>              PrintArray(vCard.getCommunicationRecordset().getTelephones());
>              PrintArray(vCard.getDeliveryAddressingRecordset().getAddresses());
>              // ...
>          }
>      }
>  }
>  private static void PrintArray(String[] values) {
>      if (values != null) {
>          for (String value : values) {
>              System.out.println(value);
>          }
>      }
>  }
>  
> ```
> ```


[Working with vCard metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+vCard+metadata
## Methods

| Method | Description |
| --- | --- |
| [getVCardPackage()](#getVCardPackage--) | Gets the VCard metadata package. |
### getVCardPackage() {#getVCardPackage--}
```
public final VCardPackage getVCardPackage()
```


Gets the VCard metadata package.

**Returns:**
[VCardPackage](../../com.groupdocs.metadata.core/vcardpackage) - The VCard metadata package.
