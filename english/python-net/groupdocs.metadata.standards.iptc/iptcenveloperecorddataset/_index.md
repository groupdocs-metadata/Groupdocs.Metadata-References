---
title: IptcEnvelopeRecordDataSet enumeration
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 80
url: /python-net/groupdocs.metadata.standards.iptc/iptcenveloperecorddataset/
is_root: false
---

## IptcEnvelopeRecordDataSet enumeration

Defines IPTC Envelope Record dataSet numbers.



The IptcEnvelopeRecordDataSet type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| MODEL_VERSION | A binary number identifying the version of the Information<br/><br/><br/>Interchange Model, Part I, utilised by the provider. Version numbers are assigned by IPTC and NAA.<br/><br/><br/>The version number of this record is four (4). |
| DESTINATION | Optional, repeatable, maximum 1024 octets, consisting of sequentially contiguous graphic characters. <br/><br/><br/>This DataSet is to accommodate some providers who require routing information above the appropriate OSI layers. |
| FILE_FORMAT | File format. |
| FILE_FORMAT_VERSION | Mandatory, not repeatable, two octets. <br/><br/><br/>A binary number representing the particular version of the File Format specified in 1:20.<br/><br/><br/>A list of File Formats, including version cross references, is included as Appendix A. |
| SERVICE_IDENTIFIER | Mandatory, not repeatable. Up to 10 octets, consisting of graphic characters.<br/><br/><br/>Identifies the provider and product. |
| ENVELOPE_NUMBER | Mandatory, not repeatable, eight octets, consisting of numeric characters.<br/><br/><br/>The characters form a number that will be unique for the date<br/>specified in 1:70 and for the Service Identifier specified in 1:30.<br/><br/><br/>If identical envelope numbers appear with the same date and<br/>with the same Service Identifier, records 2-9 must be unchanged<br/>from the original. <br/><br/><br/>This is not intended to be a sequential serial<br/>number reception check. |
| PRODUCT_ID | Optional, repeatable. Up to 32 octets, consisting of graphic characters.<br/><br/><br/>Allows a provider to identify subsets of its overall service. <br/><br/><br/>Used to provide receiving organization data on which to select, route, or otherwise handle data. |
| ENVELOPE_PRIORITY | Optional, not repeatable. A single octet, consisting of a numeric character.<br/><br/><br/>Specifies the envelope handling priority and not the editorial urgency (see 2:10, Urgency). <br/>'1' indicates the most urgent, <br/>'5' the normal urgency, <br/>and '8' the least urgent copy. <br/>The numeral '9' indicates a User Defined Priority. <br/>The numeral '0' is reserved for future use. |
| DATE_SENT | Mandatory, not repeatable. Eight octets, consisting of numeric characters.<br/><br/><br/>Uses the format CCYYMMDD (century, year, month, day) as defined in ISO 8601 to indicate year, month and day the service sent the material. |
| TIME_SENT | Uses the format HHMMSS±HHMM where HHMMSS refers to<br/>local hour, minute and seconds and HHMM refers to hours and<br/>minutes ahead (+) or behind (-) Universal Coordinated Time as<br/>described in ISO 8601. This is the time the service sent the<br/>material. |
| CODED_CHARACTER_SET | Optional, not repeatable, up to 32 octets, consisting of one or <br/>more control functions used for the announcement, invocation or <br/>designation of coded character sets. The control functions follow <br/>the ISO 2022 standard and may consist of the escape control <br/>character and one or more graphic characters. For more details <br/>see Appendix C, the IPTC-NAA Code Library. |
| UNO | Invalid (eternal identifier). |
| ARM_IDENTIFIER | The DataSet identifies the Abstract Relationship Method (ARM) which is described <br/>in a document registered by the originator of the ARM with the IPTC and NAA. |
| ARM_VERSION | Binary number representing the particular version of the ARM specified in DataSet 1:120. |



### See Also
* module [`groupdocs.metadata.standards.iptc`](..)
