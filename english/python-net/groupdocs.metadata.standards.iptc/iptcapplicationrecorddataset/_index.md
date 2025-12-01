---
title: IptcApplicationRecordDataSet enumeration
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 70
url: /python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/
is_root: false
---

## IptcApplicationRecordDataSet enumeration

Defines IPTC Application Record dataSet numbers.



The IptcApplicationRecordDataSet type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| RECORD_VERSION | Represents the record version. Binary. Always 2 in JPEGs. |
| OBJECT_TYPE_REFERENCE | Object type reference. Used pattern: "/\d{2}:[\w\s]{0,64}?/". |
| OBJECT_ATTRIBUTE_REFERENCE | The object attribute reference. |
| OBJECT_NAME | Used as a shorthand reference for the object. |
| EDIT_STATUS | Status of the objectdata, according to the practice of the provider. |
| EDITORIAL_UPDATE | Indicates the type of update that this object provides to a previous object. |
| URGENCY | Specifies the editorial urgency of content and not necessarily the envelope handling priority (see 1:60, Envelope Priority). |
| SUBJECT_REFERENCE | The subject reference. |
| CATEGORY | Identifies the subject of the objectdata in the opinion of the provider. |
| SUPPLEMENTAL_CATEGORY | Supplemental categories further refine the subject of an objectdata. <br/><br/>Only a single supplemental category may be contained in each DataSet. A supplemental category may include any of the recognised categories as used in 2:15. |
| FIXTURE_IDENTIFIER | The fixture identifier. |
| KEYWORDS | Used to indicate specific information retrieval words.<br/>Each keyword uses a single Keywords DataSet. Multiple keywords use multiple Keywords DataSets. |
| CONTENT_LOCATION_CODE | Indicates the code of a country/geographical location referenced by the content of the object. |
| CONTENT_LOCATION_NAME | Provides a full, publishable name of a country/geographical location referenced by the content of the object, <br/><br/>according to guidelines of the provider. |
| RELEASE_DATE | Designates in the form CCYYMMDD the earliest date the provider intends the object to be used. Follows ISO 8601 standard. |
| RELEASE_TIME | Designates in the form HHMMSS±HHMM the earliest time the provider intends the object to be used. Follows ISO 8601 standard. |
| EXPIRATION_DATE | Designates in the form CCYYMMDD the latest date the provider or owner intends the objectdata to be used. Follows ISO 8601 standard. |
| SPECIAL_INSTRUCTIONS | Other editorial instructions concerning the use of the objectdata, such as embargoes and warnings. |
| ACTION_ADVISED | Indicates the type of action that this object provides to a previous object. |
| REFERENCE_SERVICE | Identifies the Service Identifier of a prior envelope to which the current object refers. |
| REFERENCE_DATE | Identifies the date of a prior envelope to which the current object refers. |
| REFERENCE_NUMBER | Identifies the Envelope Number of a prior envelope to which the current object refers. |
| DATE_CREATED | Represented in the form CCYYMMDD to designate the date the intellectual content of the objectdata was created rather than the date of the creation of the physical representation. |
| TIME_CREATED | Represented in the form HHMMSS±HHMM to designate the time the intellectual content of the objectdata <br/>current source material was created rather than the creation of the physical representation. |
| DIGITAL_CREATION_DATE | Represented in the form CCYYMMDD to designate the date the digital representation of the objectdata was created. |
| DIGITAL_CREATION_TIME | Represented in the form HHMMSS±HHMM to designate the time the digital representation of the objectdata was created. |
| ORIGINATING_PROGRAM | Identifies the type of program used to originate the objectdata. |
| PROGRAM_VERSION | Used to identify the version of the program mentioned in 2:65. DataSet 2:70 is invalid if 2:65 is not present. |
| OBJECT_CYCLE | Consisting of an alphabetic character. Where: 'a' = morning, 'p' = evening, 'b' = both. |
| BYLINE | Contains name of the creator of the objectdata, e.g. writer, photographer or graphic artist. |
| BYLINE_TITLE | A by-line title is the title of the creator or creators of an object data. |
| CITY | Identifies city of objectdata origin according to guidelines established by the provider. |
| SUB_LOCATION | Identifies the location within a city from which the objectdata originates, according to guidelines established by the provider. |
| PROVINCE_STATE | Identifies Province/State of origin according to guidelines established by the provider. |
| PRIMARY_LOCATION_CODE | Indicates the code of the country/primary location where the intellectual property of the objectdata was created, e.g. a photo was taken, an event occurred. |
| PRIMARY_LOCATION_NAME | Provides full, publishable, name of the country/primary location where the intellectual property of the objectdata was created, <br/>according to guidelines of the provider. |
| ORIGINAL_TRANSMISSION_REFERENCE | A code representing the location of original transmission according to practices of the provider. |
| HEADLINE | A publishable entry providing a synopsis of the contents of the objectdata. |
| CREDIT | Identifies the provider of the objectdata, not necessarily the owner/creator. |
| SOURCE | The name of a person or party who has a role in the content supply chain. <br/>This could be an agency, a member of an agency, an individual or a combination. |
| COPYRIGHT_NOTICE | Contains any necessary copyright notice. |
| CONTACT | Identifies the person or organization which can provide further background information on the object data. |
| CAPTION_ABSTRACT | A textual description of the objectdata, particularly used where the object is not text. |
| WRITER_EDITOR | Identification of the name of the person involved in the writing, editing or correcting the objectdata or caption/abstract. |
| RASTERIZED_CAPTION | Image width 460 pixels and image height 128 pixels. Scanning direction bottom to top, left to right. |
| IMAGE_TYPE | The numeric characters 1 to 4 indicate the number of components in an image, in single or multiple envelopes. |
| IMAGE_ORIENTATION | Indicates the layout of the image area. |
| LANGUAGE_IDENTIFIER | Describes the major national language of the object, according to the 2-letter codes of ISO 639:1988. |
| AUDIO_TYPE | The audio type. |
| AUDIO_SAMPLING_RATE | Sampling rate numeric characters, representing the sampling rate in hertz (Hz). |
| AUDIO_SAMPLING_RESOLUTION | The number of bits in each audio sample. |
| AUDIO_DURATION | Duration Designates in the form HHMMSS the running time of an audio object data when played back at the speed at which it was recorded. |
| AUDIO_OUTCUE | Identifies the content of the end of an audio objectdata, according to guidelines established by the provider. |
| OBJ_DATA_PREVIEW_FILE_FORMAT | A binary number representing the file format of the ObjectData Preview. |
| OBJ_DATA_PREVIEW_FILE_FORMAT_VER | A binary number representing the particular version of the ObjectData Preview File Format specified in 2:200. |
| OBJ_DATA_PREVIEW_DATA | The object data preview. |



### See Also
* module [`groupdocs.metadata.standards.iptc`](..)
