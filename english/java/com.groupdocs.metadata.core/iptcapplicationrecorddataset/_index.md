---
title: IptcApplicationRecordDataSet
second_title: GroupDocs.Signature for Java API Reference
description: Defines IPTC Application Record dataSet numbers.
type: docs
weight: 361
url: /java/com.groupdocs.metadata.core/iptcapplicationrecorddataset/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum IptcApplicationRecordDataSet extends Enum<IptcApplicationRecordDataSet> implements IEnumValue
```

Defines IPTC Application Record dataSet numbers.
## Fields

| Field | Description |
| --- | --- |
| [RecordVersion](#RecordVersion) | Represents the record version. |
| [ObjectTypeReference](#ObjectTypeReference) | Object type reference. |
| [ObjectAttributeReference](#ObjectAttributeReference) | The object attribute reference. |
| [ObjectName](#ObjectName) | Used as a shorthand reference for the object. |
| [EditStatus](#EditStatus) | Status of the objectdata, according to the practice of the provider. |
| [EditorialUpdate](#EditorialUpdate) | Indicates the type of update that this object provides to a previous object. |
| [Urgency](#Urgency) | Specifies the editorial urgency of content and not necessarily the envelope handling priority (see 1:60, Envelope Priority). |
| [SubjectReference](#SubjectReference) | The subject reference. |
| [Category](#Category) | Identifies the subject of the objectdata in the opinion of the provider. |
| [SupplementalCategory](#SupplementalCategory) |  |
| [FixtureIdentifier](#FixtureIdentifier) | The fixture identifier. |
| [Keywords](#Keywords) | Used to indicate specific information retrieval words. |
| [ContentLocationCode](#ContentLocationCode) | Indicates the code of a country/geographical location referenced by the content of the object. |
| [ContentLocationName](#ContentLocationName) |  |
| [ReleaseDate](#ReleaseDate) | Designates in the form CCYYMMDD the earliest date the provider intends the object to be used. |
| [ReleaseTime](#ReleaseTime) | Designates in the form HHMMSS??HHMM the earliest time the provider intends the object to be used. |
| [ExpirationDate](#ExpirationDate) | Designates in the form CCYYMMDD the latest date the provider or owner intends the objectdata to be used. |
| [SpecialInstructions](#SpecialInstructions) | Other editorial instructions concerning the use of the objectdata, such as embargoes and warnings. |
| [ActionAdvised](#ActionAdvised) | Indicates the type of action that this object provides to a previous object. |
| [ReferenceService](#ReferenceService) | Identifies the Service Identifier of a prior envelope to which the current object refers. |
| [ReferenceDate](#ReferenceDate) | Identifies the date of a prior envelope to which the current object refers. |
| [ReferenceNumber](#ReferenceNumber) | Identifies the Envelope Number of a prior envelope to which the current object refers. |
| [DateCreated](#DateCreated) | Represented in the form CCYYMMDD to designate the date the intellectual content of the objectdata was created rather than the date of the creation of the physical representation. |
| [TimeCreated](#TimeCreated) | Represented in the form HHMMSS??HHMM to designate the time the intellectual content of the objectdata current source material was created rather than the creation of the physical representation. |
| [DigitalCreationDate](#DigitalCreationDate) | Represented in the form CCYYMMDD to designate the date the digital representation of the objectdata was created. |
| [DigitalCreationTime](#DigitalCreationTime) | Represented in the form HHMMSS??HHMM to designate the time the digital representation of the objectdata was created. |
| [OriginatingProgram](#OriginatingProgram) | Identifies the type of program used to originate the objectdata. |
| [ProgramVersion](#ProgramVersion) | Used to identify the version of the program mentioned in 2:65. |
| [ObjectCycle](#ObjectCycle) | Consisting of an alphabetic character. |
| [Byline](#Byline) | Contains name of the creator of the objectdata, e.g. |
| [BylineTitle](#BylineTitle) | A by-line title is the title of the creator or creators of an object data. |
| [City](#City) | Identifies city of objectdata origin according to guidelines established by the provider. |
| [SubLocation](#SubLocation) | Identifies the location within a city from which the objectdata originates, according to guidelines established by the provider. |
| [ProvinceState](#ProvinceState) | Identifies Province/State of origin according to guidelines established by the provider. |
| [PrimaryLocationCode](#PrimaryLocationCode) | Indicates the code of the country/primary location where the intellectual property of the objectdata was created, e.g. |
| [PrimaryLocationName](#PrimaryLocationName) | Provides full, publishable, name of the country/primary location where the intellectual property of the objectdata was created, according to guidelines of the provider. |
| [OriginalTransmissionReference](#OriginalTransmissionReference) | A code representing the location of original transmission according to practices of the provider. |
| [Headline](#Headline) | A publishable entry providing a synopsis of the contents of the objectdata. |
| [Credit](#Credit) | Identifies the provider of the objectdata, not necessarily the owner/creator. |
| [Source](#Source) | The name of a person or party who has a role in the content supply chain. |
| [CopyrightNotice](#CopyrightNotice) | Contains any necessary copyright notice. |
| [Contact](#Contact) | Identifies the person or organization which can provide further background information on the object data. |
| [CaptionAbstract](#CaptionAbstract) | A textual description of the objectdata, particularly used where the object is not text. |
| [WriterEditor](#WriterEditor) | Identification of the name of the person involved in the writing, editing or correcting the objectdata or caption/abstract. |
| [RasterizedCaption](#RasterizedCaption) | Image width 460 pixels and image height 128 pixels. |
| [ImageType](#ImageType) | The numeric characters 1 to 4 indicate the number of components in an image, in single or multiple envelopes. |
| [ImageOrientation](#ImageOrientation) | Indicates the layout of the image area. |
| [LanguageIdentifier](#LanguageIdentifier) | Describes the major national language of the object, according to the 2-letter codes of ISO 639:1988. |
| [AudioType](#AudioType) | The audio type. |
| [AudioSamplingRate](#AudioSamplingRate) | Sampling rate numeric characters, representing the sampling rate in hertz (Hz). |
| [AudioSamplingResolution](#AudioSamplingResolution) | The number of bits in each audio sample. |
| [AudioDuration](#AudioDuration) | Duration Designates in the form HHMMSS the running time of an audio object data when played back at the speed at which it was recorded. |
| [AudioOutcue](#AudioOutcue) | Identifies the content of the end of an audio objectdata, according to guidelines established by the provider. |
| [ObjDataPreviewFileFormat](#ObjDataPreviewFileFormat) | A binary number representing the file format of the ObjectData Preview. |
| [ObjDataPreviewFileFormatVer](#ObjDataPreviewFileFormatVer) | A binary number representing the particular version of the ObjectData Preview File Format specified in 2:200. |
| [ObjDataPreviewData](#ObjDataPreviewData) | The object data preview. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getByRawValue(int rawValue)](#getByRawValue-int-) |  |
| [getFirst()](#getFirst--) |  |
| [getAllValues()](#getAllValues--) |  |
| [getEnumValueByRawValue(int rawValue)](#getEnumValueByRawValue-int-) |  |
| [getEnumValueByName(String name)](#getEnumValueByName-java.lang.String-) |  |
| [getRawValueType()](#getRawValueType--) |  |
| [getRawValue()](#getRawValue--) |  |
### RecordVersion {#RecordVersion}
```
public static final IptcApplicationRecordDataSet RecordVersion
```


Represents the record version. Binary. Always 2 in JPEGs.

### ObjectTypeReference {#ObjectTypeReference}
```
public static final IptcApplicationRecordDataSet ObjectTypeReference
```


Object type reference. Used pattern: "/\\d\{2\}:[\\w\\s]\{0,64\}?/".

### ObjectAttributeReference {#ObjectAttributeReference}
```
public static final IptcApplicationRecordDataSet ObjectAttributeReference
```


The object attribute reference.

### ObjectName {#ObjectName}
```
public static final IptcApplicationRecordDataSet ObjectName
```


Used as a shorthand reference for the object.

--------------------

Changes to existing data, such as updated stories or new crops on photos, should be identified in  EditStatus .

### EditStatus {#EditStatus}
```
public static final IptcApplicationRecordDataSet EditStatus
```


Status of the objectdata, according to the practice of the provider.

### EditorialUpdate {#EditorialUpdate}
```
public static final IptcApplicationRecordDataSet EditorialUpdate
```


Indicates the type of update that this object provides to a previous object.

### Urgency {#Urgency}
```
public static final IptcApplicationRecordDataSet Urgency
```


Specifies the editorial urgency of content and not necessarily the envelope handling priority (see 1:60, Envelope Priority).

### SubjectReference {#SubjectReference}
```
public static final IptcApplicationRecordDataSet SubjectReference
```


The subject reference.

### Category {#Category}
```
public static final IptcApplicationRecordDataSet Category
```


Identifies the subject of the objectdata in the opinion of the provider.

### SupplementalCategory {#SupplementalCategory}
```
public static final IptcApplicationRecordDataSet SupplementalCategory
```


Supplemental categories further refine the subject of an objectdata. 

 Only a single supplemental category may be contained in each DataSet. A supplemental category may include any of the recognised categories as used in 2:15. 



### FixtureIdentifier {#FixtureIdentifier}
```
public static final IptcApplicationRecordDataSet FixtureIdentifier
```


The fixture identifier.

### Keywords {#Keywords}
```
public static final IptcApplicationRecordDataSet Keywords
```


Used to indicate specific information retrieval words. Each keyword uses a single Keywords DataSet. Multiple keywords use multiple Keywords DataSets.

### ContentLocationCode {#ContentLocationCode}
```
public static final IptcApplicationRecordDataSet ContentLocationCode
```


Indicates the code of a country/geographical location referenced by the content of the object.

### ContentLocationName {#ContentLocationName}
```
public static final IptcApplicationRecordDataSet ContentLocationName
```


Provides a full, publishable name of a country/geographical location referenced by the content of the object, 

 according to guidelines of the provider.

### ReleaseDate {#ReleaseDate}
```
public static final IptcApplicationRecordDataSet ReleaseDate
```


Designates in the form CCYYMMDD the earliest date the provider intends the object to be used. Follows ISO 8601 standard.

### ReleaseTime {#ReleaseTime}
```
public static final IptcApplicationRecordDataSet ReleaseTime
```


Designates in the form HHMMSS??HHMM the earliest time the provider intends the object to be used. Follows ISO 8601 standard.

### ExpirationDate {#ExpirationDate}
```
public static final IptcApplicationRecordDataSet ExpirationDate
```


Designates in the form CCYYMMDD the latest date the provider or owner intends the objectdata to be used. Follows ISO 8601 standard.

### SpecialInstructions {#SpecialInstructions}
```
public static final IptcApplicationRecordDataSet SpecialInstructions
```


Other editorial instructions concerning the use of the objectdata, such as embargoes and warnings.

### ActionAdvised {#ActionAdvised}
```
public static final IptcApplicationRecordDataSet ActionAdvised
```


Indicates the type of action that this object provides to a previous object.

### ReferenceService {#ReferenceService}
```
public static final IptcApplicationRecordDataSet ReferenceService
```


Identifies the Service Identifier of a prior envelope to which the current object refers.

### ReferenceDate {#ReferenceDate}
```
public static final IptcApplicationRecordDataSet ReferenceDate
```


Identifies the date of a prior envelope to which the current object refers.

### ReferenceNumber {#ReferenceNumber}
```
public static final IptcApplicationRecordDataSet ReferenceNumber
```


Identifies the Envelope Number of a prior envelope to which the current object refers.

### DateCreated {#DateCreated}
```
public static final IptcApplicationRecordDataSet DateCreated
```


Represented in the form CCYYMMDD to designate the date the intellectual content of the objectdata was created rather than the date of the creation of the physical representation.

--------------------

Follows ISO 8601 standard. Where the month or day cannot be determined, the information will be represented by ???00???. Where the year cannot be determined, the information for century and year will be represented by ???00???.

### TimeCreated {#TimeCreated}
```
public static final IptcApplicationRecordDataSet TimeCreated
```


Represented in the form HHMMSS??HHMM to designate the time the intellectual content of the objectdata current source material was created rather than the creation of the physical representation.

--------------------

Follows ISO 8601 standard.

### DigitalCreationDate {#DigitalCreationDate}
```
public static final IptcApplicationRecordDataSet DigitalCreationDate
```


Represented in the form CCYYMMDD to designate the date the digital representation of the objectdata was created.

### DigitalCreationTime {#DigitalCreationTime}
```
public static final IptcApplicationRecordDataSet DigitalCreationTime
```


Represented in the form HHMMSS??HHMM to designate the time the digital representation of the objectdata was created.

### OriginatingProgram {#OriginatingProgram}
```
public static final IptcApplicationRecordDataSet OriginatingProgram
```


Identifies the type of program used to originate the objectdata.

### ProgramVersion {#ProgramVersion}
```
public static final IptcApplicationRecordDataSet ProgramVersion
```


Used to identify the version of the program mentioned in 2:65. DataSet 2:70 is invalid if 2:65 is not present.

### ObjectCycle {#ObjectCycle}
```
public static final IptcApplicationRecordDataSet ObjectCycle
```


Consisting of an alphabetic character. Where: 'a'(morning, 'p'(evening, 'b'(both.

### Byline {#Byline}
```
public static final IptcApplicationRecordDataSet Byline
```


Contains name of the creator of the objectdata, e.g. writer, photographer or graphic artist.

### BylineTitle {#BylineTitle}
```
public static final IptcApplicationRecordDataSet BylineTitle
```


A by-line title is the title of the creator or creators of an object data.

### City {#City}
```
public static final IptcApplicationRecordDataSet City
```


Identifies city of objectdata origin according to guidelines established by the provider.

### SubLocation {#SubLocation}
```
public static final IptcApplicationRecordDataSet SubLocation
```


Identifies the location within a city from which the objectdata originates, according to guidelines established by the provider.

### ProvinceState {#ProvinceState}
```
public static final IptcApplicationRecordDataSet ProvinceState
```


Identifies Province/State of origin according to guidelines established by the provider.

### PrimaryLocationCode {#PrimaryLocationCode}
```
public static final IptcApplicationRecordDataSet PrimaryLocationCode
```


Indicates the code of the country/primary location where the intellectual property of the objectdata was created, e.g. a photo was taken, an event occurred.

### PrimaryLocationName {#PrimaryLocationName}
```
public static final IptcApplicationRecordDataSet PrimaryLocationName
```


Provides full, publishable, name of the country/primary location where the intellectual property of the objectdata was created, according to guidelines of the provider.

### OriginalTransmissionReference {#OriginalTransmissionReference}
```
public static final IptcApplicationRecordDataSet OriginalTransmissionReference
```


A code representing the location of original transmission according to practices of the provider.

### Headline {#Headline}
```
public static final IptcApplicationRecordDataSet Headline
```


A publishable entry providing a synopsis of the contents of the objectdata.

### Credit {#Credit}
```
public static final IptcApplicationRecordDataSet Credit
```


Identifies the provider of the objectdata, not necessarily the owner/creator.

### Source {#Source}
```
public static final IptcApplicationRecordDataSet Source
```


The name of a person or party who has a role in the content supply chain. This could be an agency, a member of an agency, an individual or a combination.

### CopyrightNotice {#CopyrightNotice}
```
public static final IptcApplicationRecordDataSet CopyrightNotice
```


Contains any necessary copyright notice.

### Contact {#Contact}
```
public static final IptcApplicationRecordDataSet Contact
```


Identifies the person or organization which can provide further background information on the object data.

### CaptionAbstract {#CaptionAbstract}
```
public static final IptcApplicationRecordDataSet CaptionAbstract
```


A textual description of the objectdata, particularly used where the object is not text.

### WriterEditor {#WriterEditor}
```
public static final IptcApplicationRecordDataSet WriterEditor
```


Identification of the name of the person involved in the writing, editing or correcting the objectdata or caption/abstract.

### RasterizedCaption {#RasterizedCaption}
```
public static final IptcApplicationRecordDataSet RasterizedCaption
```


Image width 460 pixels and image height 128 pixels. Scanning direction bottom to top, left to right.

### ImageType {#ImageType}
```
public static final IptcApplicationRecordDataSet ImageType
```


The numeric characters 1 to 4 indicate the number of components in an image, in single or multiple envelopes.

### ImageOrientation {#ImageOrientation}
```
public static final IptcApplicationRecordDataSet ImageOrientation
```


Indicates the layout of the image area.

### LanguageIdentifier {#LanguageIdentifier}
```
public static final IptcApplicationRecordDataSet LanguageIdentifier
```


Describes the major national language of the object, according to the 2-letter codes of ISO 639:1988.

### AudioType {#AudioType}
```
public static final IptcApplicationRecordDataSet AudioType
```


The audio type.

### AudioSamplingRate {#AudioSamplingRate}
```
public static final IptcApplicationRecordDataSet AudioSamplingRate
```


Sampling rate numeric characters, representing the sampling rate in hertz (Hz).

### AudioSamplingResolution {#AudioSamplingResolution}
```
public static final IptcApplicationRecordDataSet AudioSamplingResolution
```


The number of bits in each audio sample.

### AudioDuration {#AudioDuration}
```
public static final IptcApplicationRecordDataSet AudioDuration
```


Duration Designates in the form HHMMSS the running time of an audio object data when played back at the speed at which it was recorded.

### AudioOutcue {#AudioOutcue}
```
public static final IptcApplicationRecordDataSet AudioOutcue
```


Identifies the content of the end of an audio objectdata, according to guidelines established by the provider.

### ObjDataPreviewFileFormat {#ObjDataPreviewFileFormat}
```
public static final IptcApplicationRecordDataSet ObjDataPreviewFileFormat
```


A binary number representing the file format of the ObjectData Preview.

### ObjDataPreviewFileFormatVer {#ObjDataPreviewFileFormatVer}
```
public static final IptcApplicationRecordDataSet ObjDataPreviewFileFormatVer
```


A binary number representing the particular version of the ObjectData Preview File Format specified in 2:200.

### ObjDataPreviewData {#ObjDataPreviewData}
```
public static final IptcApplicationRecordDataSet ObjDataPreviewData
```


The object data preview.

### values() {#values--}
```
public static IptcApplicationRecordDataSet[] values()
```




**Returns:**
com.groupdocs.metadata.core.IptcApplicationRecordDataSet[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static IptcApplicationRecordDataSet valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[IptcApplicationRecordDataSet](../../com.groupdocs.metadata.core/iptcapplicationrecorddataset)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static IptcApplicationRecordDataSet getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[IptcApplicationRecordDataSet](../../com.groupdocs.metadata.core/iptcapplicationrecorddataset)
### getFirst() {#getFirst--}
```
public static IEnumValue getFirst()
```




**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getAllValues() {#getAllValues--}
```
public Object[] getAllValues()
```


Returns the array of all values defined in the class.

**Returns:**
java.lang.Object[]
### getEnumValueByRawValue(int rawValue) {#getEnumValueByRawValue-int-}
```
public IEnumValue getEnumValueByRawValue(int rawValue)
```


Returns the enumeration value by the raw value associated with it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getEnumValueByName(String name) {#getEnumValueByName-java.lang.String-}
```
public IEnumValue getEnumValueByName(String name)
```


Returns the enumeration value by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getRawValueType() {#getRawValueType--}
```
public RawIntegerType getRawValueType()
```


Returns the underlying type of the raw value of this enumeration value.

**Returns:**
[RawIntegerType](../../com.groupdocs.metadata.core/rawintegertype)
### getRawValue() {#getRawValue--}
```
public int getRawValue()
```


Returns the raw value of this enumeration value.

**Returns:**
int
