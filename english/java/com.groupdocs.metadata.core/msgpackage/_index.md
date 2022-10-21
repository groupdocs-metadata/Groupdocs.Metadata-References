---
title: MsgPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents MSG message metadata.
type: docs
weight: 133
url: /java/com.groupdocs.metadata.core/msgpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.EmailPackage](../../com.groupdocs.metadata.core/emailpackage)
```
public class MsgPackage extends EmailPackage
```

Represents MSG message metadata.

**Learn more**

 *  [Working with saved Emails][]


[Working with saved Emails]: https://docs.groupdocs.com/display/metadatajava/Working+with+saved+Emails
## Methods

| Method | Description |
| --- | --- |
| [getBody()](#getBody--) | Gets the email message text. |
| [getCategories()](#getCategories--) | Gets the array of categories or keywords. |
| [getDeliveryTime()](#getDeliveryTime--) | Gets the date and time the message was delivered. |
### getBody() {#getBody--}
```
public final String getBody()
```


Gets the email message text.

**Returns:**
java.lang.String - The email message text.
### getCategories() {#getCategories--}
```
public final String[] getCategories()
```


Gets the array of categories or keywords.

**Returns:**
java.lang.String[] - The array of categories or keywords.
### getDeliveryTime() {#getDeliveryTime--}
```
public final Date getDeliveryTime()
```


Gets the date and time the message was delivered.

**Returns:**
java.util.Date - The delivery time.
