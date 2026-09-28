---
title: IptcEnvelopeRecordDataSet class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "IptcEnvelopeRecordDataSet enum — GroupDocs.Metadata for Python via .NET API reference."
type: docs
url: /python-net/groupdocs.metadata.standards.iptc/iptcenveloperecorddataset/
is_root: false
weight: 60
---


## IptcEnvelopeRecordDataSet class

The IptcEnvelopeRecordDataSet type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| [MODEL_VERSION](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecorddataset/model_version/) | A binary number identifying the version of the Information Interchange Model, Part I, utilised by the provider. Version numbers are assigned by IPTC and NAA. The version number of this record is four (4). |
| [DESTINATION](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecorddataset/destination/) | Optional, repeatable, maximum 1024 octets, consisting of sequentially contiguous graphic characters. This DataSet is to accommodate some providers who require routing information above the appropriate OSI layers. |
| [FILE_FORMAT](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecorddataset/file_format/) | File format. |
| [FILE_FORMAT_VERSION](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecorddataset/file_format_version/) | Mandatory, not repeatable, two octets. A binary number representing the particular version of the File Format specified in 1:20. A list of File Formats, including version cross references, is included as Appendix A. |
| [SERVICE_IDENTIFIER](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecorddataset/service_identifier/) | Mandatory, not repeatable. Up to 10 octets, consisting of graphic characters. Identifies the provider and product. |
| [ENVELOPE_NUMBER](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecorddataset/envelope_number/) | Mandatory, not repeatable, eight octets, consisting of numeric characters. The characters form a number that will be unique for the date specified in 1:70 and for the Service Identifier specified in 1:30. If identical envelope numbers appear with the same date and with the same Service Identifier, records 2-9 must be unchanged from the original. This is not intended to be a sequential serial number reception check. |
| [PRODUCT_ID](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecorddataset/product_id/) | Optional, repeatable. Up to 32 octets, consisting of graphic characters. Allows a provider to identify subsets of its overall service. Used to provide receiving organization data on which to select, route, or otherwise handle data. |
| [ENVELOPE_PRIORITY](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecorddataset/envelope_priority/) | Optional, not repeatable. A single octet, consisting of a numeric character. Specifies the envelope handling priority and not the editorial urgency (see 2:10, Urgency). '1' indicates the most urgent, '5' the normal urgency, and '8' the least urgent copy. The numeral '9' indicates a User Defined Priority. The numeral '0' is reserved for future use. |
| [DATE_SENT](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecorddataset/date_sent/) | Mandatory, not repeatable. Eight octets, consisting of numeric characters. Uses the format CCYYMMDD (century, year, month, day) as defined in ISO 8601 to indicate year, month and day the service sent the material. |
| [TIME_SENT](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecorddataset/time_sent/) | Uses the format HHMMSS±HHMM where HHMMSS refers to local hour, minute and seconds and HHMM refers to hours and minutes ahead (+) or behind (-) Universal Coordinated Time as described in ISO 8601. This is the time the service sent the material. |
| [CODED_CHARACTER_SET](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecorddataset/coded_character_set/) | Optional, not repeatable, up to 32 octets, consisting of one or more control functions used for the announcement, invocation or designation of coded character sets. The control functions follow the ISO 2022 standard and may consist of the escape control character and one or more graphic characters. For more details see Appendix C, the IPTC-NAA Code Library. |
| [UNO](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecorddataset/uno/) | Invalid (eternal identifier). |
| [ARM_IDENTIFIER](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecorddataset/arm_identifier/) | The DataSet identifies the Abstract Relationship Method (ARM) which is described in a document registered by the originator of the ARM with the IPTC and NAA. |
| [ARM_VERSION](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcenveloperecorddataset/arm_version/) | Binary number representing the particular version of the ARM specified in DataSet 1:120. |

### See Also
* module [`groupdocs.metadata.standards.iptc`](/metadata/python-net/groupdocs.metadata.standards.iptc/)
