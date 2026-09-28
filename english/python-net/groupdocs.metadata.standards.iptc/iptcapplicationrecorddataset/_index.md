---
title: IptcApplicationRecordDataSet class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "IptcApplicationRecordDataSet enum — GroupDocs.Metadata for Python via .NET API reference."
type: docs
url: /python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/
is_root: false
weight: 30
---


## IptcApplicationRecordDataSet class

The IptcApplicationRecordDataSet type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| [RECORD_VERSION](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/record_version/) | Represents the record version. Binary. Always 2 in JPEGs. |
| [OBJECT_TYPE_REFERENCE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/object_type_reference/) | Object type reference. Used pattern: "/\d{2}:[\w\s]{0,64}?/". |
| [OBJECT_ATTRIBUTE_REFERENCE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/object_attribute_reference/) | The object attribute reference. |
| [OBJECT_NAME](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/object_name/) | Used as a shorthand reference for the object. |
| [EDIT_STATUS](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/edit_status/) | Status of the objectdata, according to the practice of the provider. |
| [EDITORIAL_UPDATE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/editorial_update/) | Indicates the type of update that this object provides to a previous object. |
| [URGENCY](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/urgency/) | Specifies the editorial urgency of content and not necessarily the envelope handling priority (see 1:60, Envelope Priority). |
| [SUBJECT_REFERENCE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/subject_reference/) | The subject reference. |
| [CATEGORY](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/category/) | Identifies the subject of the objectdata in the opinion of the provider. |
| [SUPPLEMENTAL_CATEGORY](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/supplemental_category/) | Supplemental categories further refine the subject of an objectdata. Only a single supplemental category may be contained in each DataSet. A supplemental category may include any of the recognised categories as used in 2:15. |
| [FIXTURE_IDENTIFIER](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/fixture_identifier/) | The fixture identifier. |
| [KEYWORDS](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/keywords/) | Used to indicate specific information retrieval words. Each keyword uses a single Keywords DataSet. Multiple keywords use multiple Keywords DataSets. |
| [CONTENT_LOCATION_CODE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/content_location_code/) | Indicates the code of a country/geographical location referenced by the content of the object. |
| [CONTENT_LOCATION_NAME](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/content_location_name/) | Provides a full, publishable name of a country/geographical location referenced by the content of the object, according to guidelines of the provider. |
| [RELEASE_DATE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/release_date/) | Designates in the form CCYYMMDD the earliest date the provider intends the object to be used. Follows ISO 8601 standard. |
| [RELEASE_TIME](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/release_time/) | Designates in the form HHMMSS±HHMM the earliest time the provider intends the object to be used. Follows ISO 8601 standard. |
| [EXPIRATION_DATE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/expiration_date/) | Designates in the form CCYYMMDD the latest date the provider or owner intends the objectdata to be used. Follows ISO 8601 standard. |
| [SPECIAL_INSTRUCTIONS](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/special_instructions/) | Other editorial instructions concerning the use of the objectdata, such as embargoes and warnings. |
| [ACTION_ADVISED](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/action_advised/) | Indicates the type of action that this object provides to a previous object. |
| [REFERENCE_SERVICE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/reference_service/) | Identifies the Service Identifier of a prior envelope to which the current object refers. |
| [REFERENCE_DATE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/reference_date/) | Identifies the date of a prior envelope to which the current object refers. |
| [REFERENCE_NUMBER](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/reference_number/) | Identifies the Envelope Number of a prior envelope to which the current object refers. |
| [DATE_CREATED](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/date_created/) | Represented in the form CCYYMMDD to designate the date the intellectual content of the objectdata was created rather than the date of the creation of the physical representation. |
| [TIME_CREATED](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/time_created/) | Represented in the form HHMMSS±HHMM to designate the time the intellectual content of the objectdata current source material was created rather than the creation of the physical representation. |
| [DIGITAL_CREATION_DATE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/digital_creation_date/) | Represented in the form CCYYMMDD to designate the date the digital representation of the objectdata was created. |
| [DIGITAL_CREATION_TIME](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/digital_creation_time/) | Represented in the form HHMMSS±HHMM to designate the time the digital representation of the objectdata was created. |
| [ORIGINATING_PROGRAM](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/originating_program/) | Identifies the type of program used to originate the objectdata. |
| [PROGRAM_VERSION](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/program_version/) | Used to identify the version of the program mentioned in 2:65. DataSet 2:70 is invalid if 2:65 is not present. |
| [OBJECT_CYCLE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/object_cycle/) | Consisting of an alphabetic character. Where: 'a' = morning, 'p' = evening, 'b' = both. |
| [BYLINE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/byline/) | Contains name of the creator of the objectdata, e.g. writer, photographer or graphic artist. |
| [BYLINE_TITLE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/byline_title/) | A by-line title is the title of the creator or creators of an object data. |
| [CITY](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/city/) | Identifies city of objectdata origin according to guidelines established by the provider. |
| [SUB_LOCATION](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/sub_location/) | Identifies the location within a city from which the objectdata originates, according to guidelines established by the provider. |
| [PROVINCE_STATE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/province_state/) | Identifies Province/State of origin according to guidelines established by the provider. |
| [PRIMARY_LOCATION_CODE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/primary_location_code/) | Indicates the code of the country/primary location where the intellectual property of the objectdata was created, e.g. a photo was taken, an event occurred. |
| [PRIMARY_LOCATION_NAME](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/primary_location_name/) | Provides full, publishable, name of the country/primary location where the intellectual property of the objectdata was created, according to guidelines of the provider. |
| [ORIGINAL_TRANSMISSION_REFERENCE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/original_transmission_reference/) | A code representing the location of original transmission according to practices of the provider. |
| [HEADLINE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/headline/) | A publishable entry providing a synopsis of the contents of the objectdata. |
| [CREDIT](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/credit/) | Identifies the provider of the objectdata, not necessarily the owner/creator. |
| [SOURCE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/source/) | The name of a person or party who has a role in the content supply chain. This could be an agency, a member of an agency, an individual or a combination. |
| [COPYRIGHT_NOTICE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/copyright_notice/) | Contains any necessary copyright notice. |
| [CONTACT](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/contact/) | Identifies the person or organization which can provide further background information on the object data. |
| [CAPTION_ABSTRACT](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/caption_abstract/) | A textual description of the objectdata, particularly used where the object is not text. |
| [WRITER_EDITOR](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/writer_editor/) | Identification of the name of the person involved in the writing, editing or correcting the objectdata or caption/abstract. |
| [RASTERIZED_CAPTION](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/rasterized_caption/) | Image width 460 pixels and image height 128 pixels. Scanning direction bottom to top, left to right. |
| [IMAGE_TYPE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/image_type/) | The numeric characters 1 to 4 indicate the number of components in an image, in single or multiple envelopes. |
| [IMAGE_ORIENTATION](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/image_orientation/) | Indicates the layout of the image area. |
| [LANGUAGE_IDENTIFIER](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/language_identifier/) | Describes the major national language of the object, according to the 2-letter codes of ISO 639:1988. |
| [AUDIO_TYPE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/audio_type/) | The audio type. |
| [AUDIO_SAMPLING_RATE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/audio_sampling_rate/) | Sampling rate numeric characters, representing the sampling rate in hertz (Hz). |
| [AUDIO_SAMPLING_RESOLUTION](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/audio_sampling_resolution/) | The number of bits in each audio sample. |
| [AUDIO_DURATION](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/audio_duration/) | Duration Designates in the form HHMMSS the running time of an audio object data when played back at the speed at which it was recorded. |
| [AUDIO_OUTCUE](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/audio_outcue/) | Identifies the content of the end of an audio objectdata, according to guidelines established by the provider. |
| [OBJ_DATA_PREVIEW_FILE_FORMAT](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/obj_data_preview_file_format/) | A binary number representing the file format of the ObjectData Preview. |
| [OBJ_DATA_PREVIEW_FILE_FORMAT_VER](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/obj_data_preview_file_format_ver/) | A binary number representing the particular version of the ObjectData Preview File Format specified in 2:200. |
| [OBJ_DATA_PREVIEW_DATA](/metadata/python-net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/obj_data_preview_data/) | The object data preview. |

### See Also
* module [`groupdocs.metadata.standards.iptc`](/metadata/python-net/groupdocs.metadata.standards.iptc/)
