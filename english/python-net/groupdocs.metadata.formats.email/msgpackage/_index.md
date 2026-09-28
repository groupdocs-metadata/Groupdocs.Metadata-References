---
title: MsgPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents MSG message metadata."
type: docs
url: /python-net/groupdocs.metadata.formats.email/msgpackage/
is_root: false
weight: 90
---


## MsgPackage class

Represents MSG message metadata.

Learn more

- Working with saved Emails: https://docs.groupdocs.com/display/metadatanet/Working+with+saved+Emails

The MsgPackage type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [add_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties/) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [add_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains/) | Returns True if the package contains a metadata property with the specified name; otherwise, False. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_file/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_string/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [find_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties/) | Finds metadata properties that satisfy the specified predicate, searching recursively through all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [find_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_enumerator](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_enumerator/) | Returns an enumerator that iterates through the collection. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_file/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_string/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [remove_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties/) | Removes metadata properties satisfying the specified predicate. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [remove_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [sanitize](/metadata/python-net/groupdocs.metadata.common/metadatapackage/sanitize/) | Removes writable metadata properties from the package, recursively affecting all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [set_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties/) | Sets known metadata properties satisfying the specified predicate. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [set_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [update_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties/) | Updates known metadata properties that satisfy the specified predicate, recursively affecting all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [update_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Properties
| Property | Description |
| :- | :- |
| [attachments](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/attachments/) | The attached files as a list. |
| [billing](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/billing/) | The billing information associated with an item. |
| [body](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/body/) | The email message text. |
| [body_html](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/body_html/) | The BodyRtf of the message converted to HTML, or an empty string if not present. |
| [body_rtf](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/body_rtf/) | The BodyRtf of the message. |
| [categories](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/categories/) | The array of categories or keywords. |
| [client_submit_time](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/client_submit_time/) | The date and time the message was submitted. The submit time. |
| [conversation_topic](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/conversation_topic/) | The Conversation Topic. |
| [delivery_time](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/delivery_time/) | The date and time the message was delivered. |
| [display_bcc](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/display_bcc/) | The Display Bcc. |
| [display_cc](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/display_cc/) | The Display Cc. |
| [display_name](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/display_name/) | The display name. |
| [display_name_prefix](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/display_name_prefix/) | The Display Name Prefix. |
| [display_to](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/display_to/) | The Display To. |
| [internet_message_id](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/internet_message_id/) | The message id of the message. |
| [is_encrypted](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/is_encrypted/) | The encrypted flag of the MSG package. |
| [is_signed](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/is_signed/) | The signed status of the message package. |
| [is_template](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/is_template/) | The Is Template. |
| [mileage](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/mileage/) | The mileage. |
| [normalized_subject](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/normalized_subject/) | The normalized subject. |
| [read_receipt_requested](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/read_receipt_requested/) | The Read Receipt Requested. |
| [reply_to](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/reply_to/) | The Reply To. |
| [sender_address_type](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/sender_address_type/) | The Sender Address Type. |
| [sender_name](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/sender_name/) | The name of the sender. |
| [sender_smtp_address](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/sender_smtp_address/) | The Sender SMTP address. |
| [sent_representing_address_type](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/sent_representing_address_type/) | The Sent Representing Address Type. |
| [sent_representing_email_address](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/sent_representing_email_address/) | The Sent Representing Email Address. |
| [sent_representing_name](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/sent_representing_name/) | The Sent Representing Name. |
| [sent_representing_smtp_address](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/sent_representing_smtp_address/) | The Sent Representing SMTP address. |
| [subject_prefix](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/subject_prefix/) | The Subject Prefix. |
| [transport_message_headers](/metadata/python-net/groupdocs.metadata.formats.email/msgpackage/transport_message_headers/) | The Transport Message Headers. |
| [blind_carbon_copy_recipients](/metadata/python-net/groupdocs.metadata.formats.email/emailpackage/blind_carbon_copy_recipients/) | The array of BCC (blind carbon copy) recipients of the email message. (inherited from [`EmailPackage`](/metadata/python-net/groupdocs.metadata.formats.email/emailpackage/)) |
| [carbon_copy_recipients](/metadata/python-net/groupdocs.metadata.formats.email/emailpackage/carbon_copy_recipients/) | The array of CC (carbon copy) recipients of the email message. (inherited from [`EmailPackage`](/metadata/python-net/groupdocs.metadata.formats.email/emailpackage/)) |
| [count](/metadata/python-net/groupdocs.metadata.common/metadatapackage/count/) | The number of metadata properties. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [headers](/metadata/python-net/groupdocs.metadata.formats.email/emailpackage/headers/) | The metadata package containing the email headers. (inherited from [`EmailPackage`](/metadata/python-net/groupdocs.metadata.formats.email/emailpackage/)) |
| [keys](/metadata/python-net/groupdocs.metadata.common/metadatapackage/keys/) | The collection of metadata property names. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [know_property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/know_property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [metadata_type](/metadata/python-net/groupdocs.metadata.common/metadatapackage/metadata_type/) | The metadata type of the package. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [recipients](/metadata/python-net/groupdocs.metadata.formats.email/emailpackage/recipients/) | The array of the email recipients. (inherited from [`EmailPackage`](/metadata/python-net/groupdocs.metadata.formats.email/emailpackage/)) |
| [sender_email_address](/metadata/python-net/groupdocs.metadata.formats.email/emailpackage/sender_email_address/) | The email address of the sender. (inherited from [`EmailPackage`](/metadata/python-net/groupdocs.metadata.formats.email/emailpackage/)) |
| [subject](/metadata/python-net/groupdocs.metadata.formats.email/emailpackage/subject/) | The email subject. (inherited from [`EmailPackage`](/metadata/python-net/groupdocs.metadata.formats.email/emailpackage/)) |

### See Also
* module [`groupdocs.metadata.formats.email`](/metadata/python-net/groupdocs.metadata.formats.email/)
