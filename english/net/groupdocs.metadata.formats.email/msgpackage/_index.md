---
title: MsgPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents MSG message metadata.
type: docs
weight: 1700
url: /net/groupdocs.metadata.formats.email/msgpackage/
---
## MsgPackage class

Represents MSG message metadata.

```csharp
public class MsgPackage : EmailPackage
```

## Properties

| Name | Description |
| --- | --- |
| [Attachments](../../groupdocs.metadata.formats.email/msgpackage/attachments) { get; set; } | Gets an array of the attached files. |
| [Billing](../../groupdocs.metadata.formats.email/msgpackage/billing) { get; set; } | Contains the billing information associated with an item. |
| [BlindCarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/blindcarboncopyrecipients) { get; set; } | Gets or sets the array of BCC (blind carbon copy) recipients of the email message. |
| [Body](../../groupdocs.metadata.formats.email/msgpackage/body) { get; set; } | Gets the email message text. |
| [BodyHtml](../../groupdocs.metadata.formats.email/msgpackage/bodyhtml) { get; set; } | Gets the BodyRtf of the message converted to HTML, if present, otherwise an empty string. |
| [BodyRtf](../../groupdocs.metadata.formats.email/msgpackage/bodyrtf) { get; set; } | Gets the BodyRtf of the message. |
| [CarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/carboncopyrecipients) { get; set; } | Gets or sets the array of CC (carbon copy) recipients of the email message. |
| [Categories](../../groupdocs.metadata.formats.email/msgpackage/categories) { get; set; } | Gets the array of categories or keywords. |
| [ClientSubmitTime](../../groupdocs.metadata.formats.email/msgpackage/clientsubmittime) { get; set; } | Gets the date and time the message was submit. |
| [ConversationTopic](../../groupdocs.metadata.formats.email/msgpackage/conversationtopic) { get; } | Gets the Conversation Topic. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [DeliveryTime](../../groupdocs.metadata.formats.email/msgpackage/deliverytime) { get; set; } | Gets the date and time the message was delivered. |
| [DisplayBcc](../../groupdocs.metadata.formats.email/msgpackage/displaybcc) { get; } | Gets the Display Bcc. |
| [DisplayCc](../../groupdocs.metadata.formats.email/msgpackage/displaycc) { get; } | Gets the Display Cc. |
| [DisplayName](../../groupdocs.metadata.formats.email/msgpackage/displayname) { get; } | Gets the Display Name. |
| [DisplayNamePrefix](../../groupdocs.metadata.formats.email/msgpackage/displaynameprefix) { get; } | Gets the Display Name Prefix. |
| [DisplayTo](../../groupdocs.metadata.formats.email/msgpackage/displayto) { get; } | Gets the Display To. |
| [Headers](../../groupdocs.metadata.formats.email/emailpackage/headers) { get; set; } | Gets a metadata package containing the email headers. |
| [InternetMessageId](../../groupdocs.metadata.formats.email/msgpackage/internetmessageid) { get; } | Gets the message id of the message. |
| [IsEncrypted](../../groupdocs.metadata.formats.email/msgpackage/isencrypted) { get; } | Gets the Is Encrypted. |
| [IsSigned](../../groupdocs.metadata.formats.email/msgpackage/issigned) { get; } | Gets the Is Signed. |
| [IsTemplate](../../groupdocs.metadata.formats.email/msgpackage/istemplate) { get; } | Gets the Is Template. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [Mileage](../../groupdocs.metadata.formats.email/msgpackage/mileage) { get; set; } | Gets the Mileage. |
| [NormalizedSubject](../../groupdocs.metadata.formats.email/msgpackage/normalizedsubject) { get; } | Gets the Normalized Subject. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [ReadReceiptRequested](../../groupdocs.metadata.formats.email/msgpackage/readreceiptrequested) { get; set; } | Gets the Read Receipt Requested. |
| [Recipients](../../groupdocs.metadata.formats.email/emailpackage/recipients) { get; set; } | Gets or sets the array of the email recipients. |
| [ReplyTo](../../groupdocs.metadata.formats.email/msgpackage/replyto) { get; set; } | Gets the Reply To. |
| [SenderAddressType](../../groupdocs.metadata.formats.email/msgpackage/senderaddresstype) { get; } | Gets the Sender Address Type. |
| [SenderEmailAddress](../../groupdocs.metadata.formats.email/emailpackage/senderemailaddress) { get; set; } | Gets the email address of the sender. |
| [SenderName](../../groupdocs.metadata.formats.email/msgpackage/sendername) { get; set; } | Gets the name of the sender. |
| [SenderSmtpAddress](../../groupdocs.metadata.formats.email/msgpackage/sendersmtpaddress) { get; set; } | Gets the Sender Smtp Address. |
| [SentRepresentingAddressType](../../groupdocs.metadata.formats.email/msgpackage/sentrepresentingaddresstype) { get; } | Gets the Sent Representing Address Type. |
| [SentRepresentingEmailAddress](../../groupdocs.metadata.formats.email/msgpackage/sentrepresentingemailaddress) { get; set; } | Gets the Sent Representing Email Address. |
| [SentRepresentingName](../../groupdocs.metadata.formats.email/msgpackage/sentrepresentingname) { get; set; } | Gets the Sent Representing Name. |
| [SentRepresentingSmtpAddress](../../groupdocs.metadata.formats.email/msgpackage/sentrepresentingsmtpaddress) { get; } | Gets the Sent Representing Smtp Address. |
| [Subject](../../groupdocs.metadata.formats.email/emailpackage/subject) { get; set; } | Gets or sets the email subject. |
| [SubjectPrefix](../../groupdocs.metadata.formats.email/msgpackage/subjectprefix) { get; } | Gets the Subject Prefix. |
| [TransportMessageHeaders](../../groupdocs.metadata.formats.email/msgpackage/transportmessageheaders) { get; } | Gets the Transport Message Headers. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Working with saved Emails](https://docs.groupdocs.com/display/metadatanet/Working+with+saved+Emails)

### See Also

* class [EmailPackage](../emailpackage)
* namespace [GroupDocs.Metadata.Formats.Email](../../groupdocs.metadata.formats.email)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
