---
title: MsgPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 80
url: /python-net/groupdocs.metadata.formats.email/msgpackage/
is_root: false
---

## MsgPackage class

Represents MSG message metadata.



**Inheritance:** [`MsgPackage`](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage) → 
[`EmailPackage`](/metadata/python-net/groupdocs.metadata.formats.email/emailpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The MsgPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/count) | Gets the number of metadata properties. |
| [subject](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/subject) | Gets or sets the email subject. |
| [recipients](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/recipients) | Gets or sets the array of the email recipients. |
| [carbon_copy_recipients](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/carbon_copy_recipients) | Gets or sets the array of CC (carbon copy) recipients of the email message. |
| [blind_carbon_copy_recipients](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/blind_carbon_copy_recipients) | Gets or sets the array of BCC (blind carbon copy) recipients of the email message. |
| [sender_email_address](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/sender_email_address) | Gets the email address of the sender. |
| [headers](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/headers) | Gets a metadata package containing the email headers. |
| [body](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/body) | Gets the email message text. |
| [categories](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/categories) | Gets the array of categories or keywords. |
| [delivery_time](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/delivery_time) | Gets the date and time the message was delivered. |
| [client_submit_time](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/client_submit_time) | Gets the date and time the message was submit. |
| [sender_name](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/sender_name) | Gets the name of the sender. |
| [internet_message_id](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/internet_message_id) | Gets the message id of the message. |
| [billing](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/billing) | Contains the billing information associated with an item. |
| [body_html](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/body_html) | Gets the BodyRtf of the message converted to HTML, if present, otherwise an empty string. |
| [body_rtf](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/body_rtf) | Gets the BodyRtf of the message. |
| [conversation_topic](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/conversation_topic) | Gets the Conversation Topic. |
| [display_bcc](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/display_bcc) | Gets the Display Bcc. |
| [display_cc](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/display_cc) | Gets the Display Cc. |
| [display_name](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/display_name) | Gets the Display Name. |
| [display_name_prefix](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/display_name_prefix) | Gets the Display Name Prefix. |
| [display_to](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/display_to) | Gets the Display To. |
| [is_encrypted](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/is_encrypted) | Gets the Is Encrypted. |
| [is_signed](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/is_signed) | Gets the Is Signed. |
| [is_template](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/is_template) | Gets the Is Template. |
| [normalized_subject](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/normalized_subject) | Gets the Normalized Subject. |
| [read_receipt_requested](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/read_receipt_requested) | Gets the Read Receipt Requested. |
| [reply_to](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/reply_to) | Gets the Reply To. |
| [sender_address_type](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/sender_address_type) | Gets the Sender Address Type. |
| [sender_smtp_address](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/sender_smtp_address) | Gets the Sender Smtp Address. |
| [sent_representing_address_type](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/sent_representing_address_type) | Gets the Sent Representing Address Type. |
| [sent_representing_email_address](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/sent_representing_email_address) | Gets the Sent Representing Email Address. |
| [sent_representing_name](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/sent_representing_name) | Gets the Sent Representing Name. |
| [sent_representing_smtp_address](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/sent_representing_smtp_address) | Gets the Sent Representing Smtp Address. |
| [transport_message_headers](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/transport_message_headers) | Gets the Transport Message Headers. |
| [mileage](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/mileage) | Gets the Mileage. |
| [subject_prefix](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/subject_prefix) | Gets the Subject Prefix. |
| [attachments](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/attachments) | Gets an array of the attached files. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.email`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`EmailPackage`](/metadata/python-net/groupdocs.metadata.formats.email/emailpackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`MsgPackage`](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage)
