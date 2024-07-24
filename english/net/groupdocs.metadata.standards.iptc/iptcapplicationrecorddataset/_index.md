---
title: IptcApplicationRecordDataSet
second_title: GroupDocs.Metadata for .NET API Reference
description: Defines IPTC Application Record dataSet numbers.
type: docs
weight: 4220
url: /net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/
---
## IptcApplicationRecordDataSet enumeration

Defines IPTC Application Record dataSet numbers.

```csharp
public enum IptcApplicationRecordDataSet
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| RecordVersion | `0` | Represents the record version. Binary. Always 2 in JPEGs. |
| ObjectTypeReference | `3` | Object type reference. Used pattern: "/\d{2}:[\w\s]{0,64}?/". |
| ObjectAttributeReference | `4` | The object attribute reference. |
| ObjectName | `5` | Used as a shorthand reference for the object. |
| EditStatus | `7` | Status of the objectdata, according to the practice of the provider. |
| EditorialUpdate | `8` | Indicates the type of update that this object provides to a previous object. |
| Urgency | `10` | Specifies the editorial urgency of content and not necessarily the envelope handling priority (see 1:60, Envelope Priority). |
| SubjectReference | `12` | The subject reference. |
| Category | `15` | Identifies the subject of the objectdata in the opinion of the provider. |
| SupplementalCategory | `20` | Supplemental categories further refine the subject of an objectdata.  Only a single supplemental category may be contained in each DataSet. A supplemental category may include any of the recognised categories as used in 2:15. |
| FixtureIdentifier | `22` | The fixture identifier. |
| Keywords | `25` | Used to indicate specific information retrieval words. Each keyword uses a single Keywords DataSet. Multiple keywords use multiple Keywords DataSets. |
| ContentLocationCode | `26` | Indicates the code of a country/geographical location referenced by the content of the object. |
| ContentLocationName | `27` | Provides a full, publishable name of a country/geographical location referenced by the content of the object,  according to guidelines of the provider. |
| ReleaseDate | `30` | Designates in the form CCYYMMDD the earliest date the provider intends the object to be used. Follows ISO 8601 standard. |
| ReleaseTime | `35` | Designates in the form HHMMSS±HHMM the earliest time the provider intends the object to be used. Follows ISO 8601 standard. |
| ExpirationDate | `37` | Designates in the form CCYYMMDD the latest date the provider or owner intends the objectdata to be used. Follows ISO 8601 standard. |
| SpecialInstructions | `40` | Other editorial instructions concerning the use of the objectdata, such as embargoes and warnings. |
| ActionAdvised | `42` | Indicates the type of action that this object provides to a previous object. |
| ReferenceService | `45` | Identifies the Service Identifier of a prior envelope to which the current object refers. |
| ReferenceDate | `47` | Identifies the date of a prior envelope to which the current object refers. |
| ReferenceNumber | `50` | Identifies the Envelope Number of a prior envelope to which the current object refers. |
| DateCreated | `55` | Represented in the form CCYYMMDD to designate the date the intellectual content of the objectdata was created rather than the date of the creation of the physical representation. |
| TimeCreated | `60` | Represented in the form HHMMSS±HHMM to designate the time the intellectual content of the objectdata current source material was created rather than the creation of the physical representation. |
| DigitalCreationDate | `62` | Represented in the form CCYYMMDD to designate the date the digital representation of the objectdata was created. |
| DigitalCreationTime | `63` | Represented in the form HHMMSS±HHMM to designate the time the digital representation of the objectdata was created. |
| OriginatingProgram | `65` | Identifies the type of program used to originate the objectdata. |
| ProgramVersion | `70` | Used to identify the version of the program mentioned in 2:65. DataSet 2:70 is invalid if 2:65 is not present. |
| ObjectCycle | `75` | Consisting of an alphabetic character. Where: 'a' = morning, 'p' = evening, 'b' = both. |
| Byline | `80` | Contains name of the creator of the objectdata, e.g. writer, photographer or graphic artist. |
| BylineTitle | `85` | A by-line title is the title of the creator or creators of an object data. |
| City | `90` | Identifies city of objectdata origin according to guidelines established by the provider. |
| SubLocation | `92` | Identifies the location within a city from which the objectdata originates, according to guidelines established by the provider. |
| ProvinceState | `95` | Identifies Province/State of origin according to guidelines established by the provider. |
| PrimaryLocationCode | `100` | Indicates the code of the country/primary location where the intellectual property of the objectdata was created, e.g. a photo was taken, an event occurred. |
| PrimaryLocationName | `101` | Provides full, publishable, name of the country/primary location where the intellectual property of the objectdata was created, according to guidelines of the provider. |
| OriginalTransmissionReference | `103` | A code representing the location of original transmission according to practices of the provider. |
| Headline | `105` | A publishable entry providing a synopsis of the contents of the objectdata. |
| Credit | `110` | Identifies the provider of the objectdata, not necessarily the owner/creator. |
| Source | `115` | The name of a person or party who has a role in the content supply chain. This could be an agency, a member of an agency, an individual or a combination. |
| CopyrightNotice | `116` | Contains any necessary copyright notice. |
| Contact | `118` | Identifies the person or organization which can provide further background information on the object data. |
| CaptionAbstract | `120` | A textual description of the objectdata, particularly used where the object is not text. |
| WriterEditor | `122` | Identification of the name of the person involved in the writing, editing or correcting the objectdata or caption/abstract. |
| RasterizedCaption | `125` | Image width 460 pixels and image height 128 pixels. Scanning direction bottom to top, left to right. |
| ImageType | `130` | The numeric characters 1 to 4 indicate the number of components in an image, in single or multiple envelopes. |
| ImageOrientation | `131` | Indicates the layout of the image area. |
| LanguageIdentifier | `135` | Describes the major national language of the object, according to the 2-letter codes of ISO 639:1988. |
| AudioType | `150` | The audio type. |
| AudioSamplingRate | `151` | Sampling rate numeric characters, representing the sampling rate in hertz (Hz). |
| AudioSamplingResolution | `152` | The number of bits in each audio sample. |
| AudioDuration | `153` | Duration Designates in the form HHMMSS the running time of an audio object data when played back at the speed at which it was recorded. |
| AudioOutcue | `154` | Identifies the content of the end of an audio objectdata, according to guidelines established by the provider. |
| ObjDataPreviewFileFormat | `200` | A binary number representing the file format of the ObjectData Preview. |
| ObjDataPreviewFileFormatVer | `201` | A binary number representing the particular version of the ObjectData Preview File Format specified in 2:200. |
| ObjDataPreviewData | `202` | The object data preview. |

### See Also

* namespace [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
