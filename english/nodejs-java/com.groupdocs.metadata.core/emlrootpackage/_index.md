---
title: EmlRootPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents the root package allowing working with metadata in an EML email message.
type: docs
weight: 93
url: /nodejs-java/com.groupdocs.metadata.core/emlrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage), [com.groupdocs.metadata.core.EmailRootPackage](../../com.groupdocs.metadata.core/emailrootpackage)
```
public class EmlRootPackage extends EmailRootPackage
```

Represents the root package allowing working with metadata in an EML email message.

**Learn more**

 *  [Working with saved Emails][]

This code sample shows how to extract metadata from an EML message.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputEml)) {
>      EmlRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getEmailPackage().getSender());
>      System.out.println(root.getEmailPackage().getSubject());
>      for (String recipient : root.getEmailPackage().getRecipients()) {
>          System.out.println(recipient);
>      }
>      for (String attachedFileName : root.getEmailPackage().getAttachedFileNames()) {
>          System.out.println(attachedFileName);
>      }
>      for (MetadataProperty header : root.getEmailPackage().getHeaders()) {
>          System.out.println(String.format("%s = %s", header.getName(), header.getValue()));
>      }
>      // ...
>  }
>  
> ```
> ```


[Working with saved Emails]: https://docs.groupdocs.com/display/metadatajava/Working+with+saved+Emails
## Methods

| Method | Description |
| --- | --- |
| [getEmlPackage()](#getEmlPackage--) | Gets the EML metadata package. |
### getEmlPackage() {#getEmlPackage--}
```
public final EmlPackage getEmlPackage()
```


Gets the EML metadata package.

**Returns:**
[EmlPackage](../../com.groupdocs.metadata.core/emlpackage) - The EML metadata package.
