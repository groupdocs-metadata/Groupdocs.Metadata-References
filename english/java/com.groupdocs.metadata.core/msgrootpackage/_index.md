---
title: MsgRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package allowing working with metadata in an MSG email message.
type: docs
weight: 134
url: /java/com.groupdocs.metadata.core/msgrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage), [com.groupdocs.metadata.core.EmailRootPackage](../../com.groupdocs.metadata.core/emailrootpackage)
```
public class MsgRootPackage extends EmailRootPackage
```

Represents the root package allowing working with metadata in an MSG email message.

**Learn more**

 *  [Working with saved Emails][]

This code sample shows how to extract metadata from an MSG message.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputMsg)) {
>      MsgRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getMsgPackage().getSender());
>      System.out.println(root.getMsgPackage().getSubject());
>      for (String recipient : root.getMsgPackage().getRecipients()) {
>          System.out.println(recipient);
>      }
>      for (String attachedFileName : root.getMsgPackage().getAttachedFileNames()) {
>          System.out.println(attachedFileName);
>      }
>      for (MetadataProperty header : root.getMsgPackage().getHeaders()) {
>          System.out.println(String.format("%s = %s", header.getName(), header.getValue()));
>      }
>      System.out.println(root.getMsgPackage().getBody());
>      System.out.println(root.getMsgPackage().getDeliveryTime());
>      // ...
>  }
>  
> ```
> ```


[Working with saved Emails]: https://docs.groupdocs.com/display/metadatajava/Working+with+saved+Emails
## Methods

| Method | Description |
| --- | --- |
| [getMsgPackage()](#getMsgPackage--) | Gets the MSG metadata package. |
### getMsgPackage() {#getMsgPackage--}
```
public final MsgPackage getMsgPackage()
```


Gets the MSG metadata package.

**Returns:**
[MsgPackage](../../com.groupdocs.metadata.core/msgpackage) - The MSG metadata package.
