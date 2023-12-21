---
title: EmailPackage
second_title: GroupDocs.Signature for Java API Reference
description: Represents email message metadata.
type: docs
weight: 89
url: /java/com.groupdocs.metadata.core/emailpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public abstract class EmailPackage extends CustomPackage
```

Represents email message metadata.

**Learn more**

 *  [Working with saved Emails][]


[Working with saved Emails]: https://docs.groupdocs.com/display/metadatajava/Working+with+saved+Emails
## Methods

| Method | Description |
| --- | --- |
| [getAttachedFileNames()](#getAttachedFileNames--) | Gets an array of the names of the attached files. |
| [getSubject()](#getSubject--) | Gets the email subject. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the email subject. |
| [getRecipients()](#getRecipients--) | Gets the array of the email recipients. |
| [setRecipients(String[] value)](#setRecipients-java.lang.String---) | Sets the array of the email recipients. |
| [getCarbonCopyRecipients()](#getCarbonCopyRecipients--) | Gets the array of CC (carbon copy) recipients of the email message. |
| [setCarbonCopyRecipients(String[] value)](#setCarbonCopyRecipients-java.lang.String---) | Sets the array of CC (carbon copy) recipients of the email message. |
| [getBlindCarbonCopyRecipients()](#getBlindCarbonCopyRecipients--) | Gets the array of BCC (blind carbon copy) recipients of the email message. |
| [setBlindCarbonCopyRecipients(String[] value)](#setBlindCarbonCopyRecipients-java.lang.String---) | Sets the array of BCC (blind carbon copy) recipients of the email message. |
| [getSender()](#getSender--) | Gets the email address of the sender. |
| [getHeaders()](#getHeaders--) | Gets a metadata package containing the email headers. |
### getAttachedFileNames() {#getAttachedFileNames--}
```
public final String[] getAttachedFileNames()
```


Gets an array of the names of the attached files.

**Returns:**
java.lang.String[] - An array of the names of the attached files.
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the email subject.

**Returns:**
java.lang.String - The email subject.
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Sets the email subject.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The email subject. |

### getRecipients() {#getRecipients--}
```
public final String[] getRecipients()
```


Gets the array of the email recipients.

**Returns:**
java.lang.String[] - The array of the email recipients.
### setRecipients(String[] value) {#setRecipients-java.lang.String---}
```
public final void setRecipients(String[] value)
```


Sets the array of the email recipients.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The array of the email recipients. |

### getCarbonCopyRecipients() {#getCarbonCopyRecipients--}
```
public final String[] getCarbonCopyRecipients()
```


Gets the array of CC (carbon copy) recipients of the email message.

**Returns:**
java.lang.String[] - The array of CC (carbon copy) recipients of the email message.
### setCarbonCopyRecipients(String[] value) {#setCarbonCopyRecipients-java.lang.String---}
```
public final void setCarbonCopyRecipients(String[] value)
```


Sets the array of CC (carbon copy) recipients of the email message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The array of CC (carbon copy) recipients of the email message. |

### getBlindCarbonCopyRecipients() {#getBlindCarbonCopyRecipients--}
```
public final String[] getBlindCarbonCopyRecipients()
```


Gets the array of BCC (blind carbon copy) recipients of the email message.

**Returns:**
java.lang.String[] - The array of BCC (blind carbon copy) recipients of the email message.
### setBlindCarbonCopyRecipients(String[] value) {#setBlindCarbonCopyRecipients-java.lang.String---}
```
public final void setBlindCarbonCopyRecipients(String[] value)
```


Sets the array of BCC (blind carbon copy) recipients of the email message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The array of BCC (blind carbon copy) recipients of the email message. |

### getSender() {#getSender--}
```
public final String getSender()
```


Gets the email address of the sender.

**Returns:**
java.lang.String - The email address of the sender.
### getHeaders() {#getHeaders--}
```
public final EmailHeaderPackage getHeaders()
```


Gets a metadata package containing the email headers.

**Returns:**
[EmailHeaderPackage](../../com.groupdocs.metadata.core/emailheaderpackage) - A metadata package containing the email headers.
