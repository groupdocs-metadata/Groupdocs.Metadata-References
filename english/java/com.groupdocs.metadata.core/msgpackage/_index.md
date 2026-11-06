---
title: MsgPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents MSG message metadata.
type: docs
weight: 165
url: /java/com.groupdocs.metadata.core/msgpackage/
---

**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.EmailPackage](../../com.groupdocs.metadata.core/emailpackage)
```
public class MsgPackage extends EmailPackage
```

Represents MSG message metadata.


**Learn more**

* [Working with saved Emails](../https://docs.groupdocs.com/display/metadatajava/Working+with+saved+Emails)

<br />


## Methods

| Method | Description |
| --- | --- |
| [getBody()](#getBody--) | Gets the email message text.
 |
| [setBody(String value)](#setBody-java.lang.String-) | Sets the email message text.
 |
| [getCategories()](#getCategories--) | Gets the array of categories or keywords.
 |
| [setCategories(String[] value)](#setCategories-java.lang.String---) | Sets the array of categories or keywords.
 |
| [getSenderName()](#getSenderName--) | Gets the display name of the sender.
 |
| [setSenderName(String value)](#setSenderName-java.lang.String-) | Sets the display name of the sender.
 |
| [getAttachments()](#getAttachments--) | Gets an array of the attached files.
 |
| [setAttachments(MsgAttachmentPackage[] value)](#setAttachments-com.groupdocs.metadata.core.MsgAttachmentPackage---) | Sets an array of the attached files.
 |
| [getDeliveryTime()](#getDeliveryTime--) | Gets the date and time the message was delivered.
 |
| [setDeliveryTime(Date value)](#setDeliveryTime-java.util.Date-) | Sets the date and time the message was delivered.
 |
| [getClientSubmitTime()](#getClientSubmitTime--) | Gets the date and time the message was submitted by the client.
 |
| [setClientSubmitTime(Date value)](#setClientSubmitTime-java.util.Date-) | Sets the date and time the message was submitted by the client.
 |
| [getInternetMessageId()](#getInternetMessageId--) | Gets the Internet message identifier of the message.
 |
| [getBilling()](#getBilling--) | Gets the billing information associated with the message.
 |
| [setBilling(String value)](#setBilling-java.lang.String-) | Sets the billing information associated with the message.
 |
| [getBodyHtml()](#getBodyHtml--) | Gets the HTML body of the message.
 |
| [setBodyHtml(String value)](#setBodyHtml-java.lang.String-) | Sets the HTML body of the message.
 |
| [getBodyRtf()](#getBodyRtf--) | Gets the RTF body of the message.
 |
| [setBodyRtf(String value)](#setBodyRtf-java.lang.String-) | Sets the RTF body of the message.
 |
| [getConversationTopic()](#getConversationTopic--) | Gets the conversation topic.
 |
| [getDisplayBcc()](#getDisplayBcc--) | Gets the list of BCC display names.
 |
| [getDisplayCc()](#getDisplayCc--) | Gets the list of CC display names.
 |
| [getDisplayName()](#getDisplayName--) | Gets the display name of the message.
 |
| [getDisplayNamePrefix()](#getDisplayNamePrefix--) | Gets the display name prefix.
 |
| [getDisplayTo()](#getDisplayTo--) | Gets the list of the To display names.
 |
| [isEncrypted()](#isEncrypted--) | Gets the value indicating whether the message is encrypted.
 |
| [isSigned()](#isSigned--) | Gets the value indicating whether the message is signed.
 |
| [isTemplate()](#isTemplate--) | Gets the value indicating whether the message is a template.
 |
| [getNormalizedSubject()](#getNormalizedSubject--) | Gets the normalized subject.
 |
| [getReadReceiptRequested()](#getReadReceiptRequested--) | Gets the value indicating whether a read receipt is requested.
 |
| [setReadReceiptRequested(boolean value)](#setReadReceiptRequested-boolean-) | Sets the value indicating whether a read receipt is requested.
 |
| [getReplyTo()](#getReplyTo--) | Gets the reply-to names.
 |
| [setReplyTo(String value)](#setReplyTo-java.lang.String-) | Sets the reply-to names.
 |
| [getSenderAddressType()](#getSenderAddressType--) | Gets the e-mail address type of the sender.
 |
| [getSenderSmtpAddress()](#getSenderSmtpAddress--) | Gets the SMTP e-mail address of the sender.
 |
| [setSenderSmtpAddress(String value)](#setSenderSmtpAddress-java.lang.String-) | Sets the SMTP e-mail address of the sender.
 |
| [getSentRepresentingAddressType()](#getSentRepresentingAddressType--) | Gets the address type of the sent-representing party.
 |
| [getSentRepresentingEmailAddress()](#getSentRepresentingEmailAddress--) | Gets the e-mail address of the sent-representing party.
 |
| [setSentRepresentingEmailAddress(String value)](#setSentRepresentingEmailAddress-java.lang.String-) | Sets the e-mail address of the sent-representing party.
 |
| [getSentRepresentingName()](#getSentRepresentingName--) | Gets the display name of the sent-representing party.
 |
| [setSentRepresentingName(String value)](#setSentRepresentingName-java.lang.String-) | Sets the display name of the sent-representing party.
 |
| [getSentRepresentingSmtpAddress()](#getSentRepresentingSmtpAddress--) | Gets the SMTP address of the sent-representing party.
 |
| [getTransportMessageHeaders()](#getTransportMessageHeaders--) | Gets the transport message headers.
 |
| [getMileage()](#getMileage--) | Gets the mileage information.
 |
| [setMileage(String value)](#setMileage-java.lang.String-) | Sets the mileage information.
 |
| [getSubjectPrefix()](#getSubjectPrefix--) | Gets the subject prefix.
 |
### getBody() {#getBody--}
```
public final String getBody()
```


Gets the email message text.


**Returns:**
java.lang.String - The email message text.

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Sets the email message text.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The email message text.
 |

### getCategories() {#getCategories--}
```
public final String[] getCategories()
```


Gets the array of categories or keywords.


**Returns:**
java.lang.String[] - The array of categories or keywords.

### setCategories(String[] value) {#setCategories-java.lang.String---}
```
public final void setCategories(String[] value)
```


Sets the array of categories or keywords.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The array of categories or keywords.
 |

### getSenderName() {#getSenderName--}
```
public final String getSenderName()
```


Gets the display name of the sender.


**Returns:**
java.lang.String - The display name of the sender.

### setSenderName(String value) {#setSenderName-java.lang.String-}
```
public final void setSenderName(String value)
```


Sets the display name of the sender.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The display name of the sender.
 |

### getAttachments() {#getAttachments--}
```
public final MsgAttachmentPackage[] getAttachments()
```


Gets an array of the attached files.


**Returns:**
com.groupdocs.metadata.core.MsgAttachmentPackage[] - An array of the attached files.

### setAttachments(MsgAttachmentPackage[] value) {#setAttachments-com.groupdocs.metadata.core.MsgAttachmentPackage---}
```
public final void setAttachments(MsgAttachmentPackage[] value)
```


Sets an array of the attached files.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MsgAttachmentPackage\[\]](../../com.groupdocs.metadata.core/msgattachmentpackage) | An array of the attached files.
 |

### getDeliveryTime() {#getDeliveryTime--}
```
public final Date getDeliveryTime()
```


Gets the date and time the message was delivered.


**Returns:**
java.util.Date - The delivery time.

### setDeliveryTime(Date value) {#setDeliveryTime-java.util.Date-}
```
public final void setDeliveryTime(Date value)
```


Sets the date and time the message was delivered.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The delivery time.
 |

### getClientSubmitTime() {#getClientSubmitTime--}
```
public final Date getClientSubmitTime()
```


Gets the date and time the message was submitted by the client.


**Returns:**
java.util.Date - The client submit time.

### setClientSubmitTime(Date value) {#setClientSubmitTime-java.util.Date-}
```
public final void setClientSubmitTime(Date value)
```


Sets the date and time the message was submitted by the client.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The client submit time.
 |

### getInternetMessageId() {#getInternetMessageId--}
```
public final String getInternetMessageId()
```


Gets the Internet message identifier of the message.


**Returns:**
java.lang.String - The Internet message identifier of the message.

### getBilling() {#getBilling--}
```
public final String getBilling()
```


Gets the billing information associated with the message.


**Returns:**
java.lang.String - The billing information associated with the message.

### setBilling(String value) {#setBilling-java.lang.String-}
```
public final void setBilling(String value)
```


Sets the billing information associated with the message.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The billing information associated with the message.
 |

### getBodyHtml() {#getBodyHtml--}
```
public final String getBodyHtml()
```


Gets the HTML body of the message.


**Returns:**
java.lang.String - The HTML body of the message.

### setBodyHtml(String value) {#setBodyHtml-java.lang.String-}
```
public final void setBodyHtml(String value)
```


Sets the HTML body of the message.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The HTML body of the message.
 |

### getBodyRtf() {#getBodyRtf--}
```
public final String getBodyRtf()
```


Gets the RTF body of the message.


**Returns:**
java.lang.String - The RTF body of the message.

### setBodyRtf(String value) {#setBodyRtf-java.lang.String-}
```
public final void setBodyRtf(String value)
```


Sets the RTF body of the message.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The RTF body of the message.
 |

### getConversationTopic() {#getConversationTopic--}
```
public final String getConversationTopic()
```


Gets the conversation topic.


**Returns:**
java.lang.String - The conversation topic.

### getDisplayBcc() {#getDisplayBcc--}
```
public final String getDisplayBcc()
```


Gets the list of BCC display names.


**Returns:**
java.lang.String - The list of BCC display names.

### getDisplayCc() {#getDisplayCc--}
```
public final String getDisplayCc()
```


Gets the list of CC display names.


**Returns:**
java.lang.String - The list of CC display names.

### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets the display name of the message.


**Returns:**
java.lang.String - The display name of the message.

### getDisplayNamePrefix() {#getDisplayNamePrefix--}
```
public final String getDisplayNamePrefix()
```


Gets the display name prefix.


**Returns:**
java.lang.String - The display name prefix.

### getDisplayTo() {#getDisplayTo--}
```
public final String getDisplayTo()
```


Gets the list of the To display names.


**Returns:**
java.lang.String - The list of the To display names.

### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Gets the value indicating whether the message is encrypted.


**Returns:**
boolean - The value indicating whether the message is encrypted.

### isSigned() {#isSigned--}
```
public final boolean isSigned()
```


Gets the value indicating whether the message is signed.


**Returns:**
boolean - The value indicating whether the message is signed.

### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


Gets the value indicating whether the message is a template.


**Returns:**
boolean - The value indicating whether the message is a template.

### getNormalizedSubject() {#getNormalizedSubject--}
```
public final String getNormalizedSubject()
```


Gets the normalized subject.


**Returns:**
java.lang.String - The normalized subject.

### getReadReceiptRequested() {#getReadReceiptRequested--}
```
public final boolean getReadReceiptRequested()
```


Gets the value indicating whether a read receipt is requested.


**Returns:**
boolean - The value indicating whether a read receipt is requested.

### setReadReceiptRequested(boolean value) {#setReadReceiptRequested-boolean-}
```
public final void setReadReceiptRequested(boolean value)
```


Sets the value indicating whether a read receipt is requested.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | The value indicating whether a read receipt is requested.
 |

### getReplyTo() {#getReplyTo--}
```
public final String getReplyTo()
```


Gets the reply-to names.


**Returns:**
java.lang.String - The reply-to names.

### setReplyTo(String value) {#setReplyTo-java.lang.String-}
```
public final void setReplyTo(String value)
```


Sets the reply-to names.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The reply-to names.
 |

### getSenderAddressType() {#getSenderAddressType--}
```
public final String getSenderAddressType()
```


Gets the e-mail address type of the sender.


**Returns:**
java.lang.String - The e-mail address type of the sender.

### getSenderSmtpAddress() {#getSenderSmtpAddress--}
```
public final String getSenderSmtpAddress()
```


Gets the SMTP e-mail address of the sender.


**Returns:**
java.lang.String - The SMTP e-mail address of the sender.

### setSenderSmtpAddress(String value) {#setSenderSmtpAddress-java.lang.String-}
```
public final void setSenderSmtpAddress(String value)
```


Sets the SMTP e-mail address of the sender.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The SMTP e-mail address of the sender.
 |

### getSentRepresentingAddressType() {#getSentRepresentingAddressType--}
```
public final String getSentRepresentingAddressType()
```


Gets the address type of the sent-representing party.


**Returns:**
java.lang.String - The address type of the sent-representing party.

### getSentRepresentingEmailAddress() {#getSentRepresentingEmailAddress--}
```
public final String getSentRepresentingEmailAddress()
```


Gets the e-mail address of the sent-representing party.


**Returns:**
java.lang.String - The e-mail address of the sent-representing party.

### setSentRepresentingEmailAddress(String value) {#setSentRepresentingEmailAddress-java.lang.String-}
```
public final void setSentRepresentingEmailAddress(String value)
```


Sets the e-mail address of the sent-representing party.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The e-mail address of the sent-representing party.
 |

### getSentRepresentingName() {#getSentRepresentingName--}
```
public final String getSentRepresentingName()
```


Gets the display name of the sent-representing party.


**Returns:**
java.lang.String - The display name of the sent-representing party.

### setSentRepresentingName(String value) {#setSentRepresentingName-java.lang.String-}
```
public final void setSentRepresentingName(String value)
```


Sets the display name of the sent-representing party.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The display name of the sent-representing party.
 |

### getSentRepresentingSmtpAddress() {#getSentRepresentingSmtpAddress--}
```
public final String getSentRepresentingSmtpAddress()
```


Gets the SMTP address of the sent-representing party.


**Returns:**
java.lang.String - The SMTP address of the sent-representing party.

### getTransportMessageHeaders() {#getTransportMessageHeaders--}
```
public final String getTransportMessageHeaders()
```


Gets the transport message headers.


**Returns:**
java.lang.String - The transport message headers.

### getMileage() {#getMileage--}
```
public final String getMileage()
```


Gets the mileage information.


**Returns:**
java.lang.String - The mileage information.

### setMileage(String value) {#setMileage-java.lang.String-}
```
public final void setMileage(String value)
```


Sets the mileage information.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The mileage information.
 |

### getSubjectPrefix() {#getSubjectPrefix--}
```
public final String getSubjectPrefix()
```


Gets the subject prefix.


**Returns:**
java.lang.String - The subject prefix.

