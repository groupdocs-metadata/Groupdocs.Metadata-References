---
title: IptcApplicationRecord
second_title: GroupDocs.Metadata for Java API Reference
description: Represents an IPTC Application Record.
type: docs
weight: 133
url: /java/com.groupdocs.metadata.core/iptcapplicationrecord/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.IptcRecord](../../com.groupdocs.metadata.core/iptcrecord)
```
public final class IptcApplicationRecord extends IptcRecord
```

Represents an IPTC Application Record.

**Learn more**

 *  [Working with IPTC IIM metadata][]


[Working with IPTC IIM metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+IPTC+IIM+metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [IptcApplicationRecord()](#IptcApplicationRecord--) | Initializes a new instance of the  IptcApplicationRecord  class. |
## Methods

| Method | Description |
| --- | --- |
| [getByLine()](#getByLine--) | Gets the name of the creator of the object, e.g. |
| [setByLine(String value)](#setByLine-java.lang.String-) | Sets the name of the creator of the object, e.g. |
| [getByLines()](#getByLines--) | Gets the names of the creators of the object, e.g. |
| [setByLines(String[] value)](#setByLines-java.lang.String---) | Sets the names of the creators of the object, e.g. |
| [getByLineTitle()](#getByLineTitle--) | Gets the title of the creator or creators of the object. |
| [setByLineTitle(String value)](#setByLineTitle-java.lang.String-) | Sets the title of the creator or creators of the object. |
| [getByLineTitles()](#getByLineTitles--) | Gets the titles of the creator or creators of the object. |
| [setByLineTitles(String[] value)](#setByLineTitles-java.lang.String---) | Sets the titles of the creator or creators of the object. |
| [getContentLocationCode()](#getContentLocationCode--) | Gets the content location code. |
| [setContentLocationCode(String value)](#setContentLocationCode-java.lang.String-) | Sets the content location code. |
| [getContentLocationCodes()](#getContentLocationCodes--) | Gets the content location codes. |
| [setContentLocationCodes(String[] value)](#setContentLocationCodes-java.lang.String---) | Sets the content location codes. |
| [getContentLocationName()](#getContentLocationName--) | Gets the content location name. |
| [setContentLocationName(String value)](#setContentLocationName-java.lang.String-) | Sets the content location name. |
| [getContentLocationNames()](#getContentLocationNames--) | Gets the content location names. |
| [setContentLocationNames(String[] value)](#setContentLocationNames-java.lang.String---) | Sets the content location names. |
| [getDateCreated()](#getDateCreated--) | Gets the date the intellectual content of the object was created. |
| [setDateCreated(Date value)](#setDateCreated-java.util.Date-) | Sets the date the intellectual content of the object was created. |
| [getReferenceDate()](#getReferenceDate--) | Gets the date of a prior envelope to which the current object refers. |
| [setReferenceDate(Date value)](#setReferenceDate-java.util.Date-) | Sets the date of a prior envelope to which the current object refers. |
| [getReferenceDates()](#getReferenceDates--) | Gets the dates of a prior envelope to which the current object refers. |
| [getReleaseDate()](#getReleaseDate--) | Gets the release date. |
| [setReleaseDate(Date value)](#setReleaseDate-java.util.Date-) | Sets the release date. |
| [getCredit()](#getCredit--) | Gets information about the provider of the object, not necessarily the owner/creator. |
| [setCredit(String value)](#setCredit-java.lang.String-) | Sets information about the provider of the object, not necessarily the owner/creator. |
| [getHeadline()](#getHeadline--) | Gets a publishable entry providing a synopsis of the contents of the object. |
| [setHeadline(String value)](#setHeadline-java.lang.String-) | Sets a publishable entry providing a synopsis of the contents of the object. |
| [getCopyrightNotice()](#getCopyrightNotice--) | Gets the copyright notice. |
| [setCopyrightNotice(String value)](#setCopyrightNotice-java.lang.String-) | Sets the copyright notice. |
| [getContact()](#getContact--) | Gets information about the person or organisation which can provide further background information on the object. |
| [setContact(String value)](#setContact-java.lang.String-) | Sets information about the person or organisation which can provide further background information on the object. |
| [getContacts()](#getContacts--) | Gets information about the person or organisation which can provide further background information on the object. |
| [setContacts(String[] value)](#setContacts-java.lang.String---) | Sets information about the person or organisation which can provide further background information on the object. |
| [getCity()](#getCity--) | Gets the city. |
| [setCity(String value)](#setCity-java.lang.String-) | Sets the city. |
| [getCaptionAbstract()](#getCaptionAbstract--) | Gets a textual description of the object, particularly used where the object is not text. |
| [setCaptionAbstract(String value)](#setCaptionAbstract-java.lang.String-) | Sets a textual description of the object, particularly used where the object is not text. |
| [getKeywords()](#getKeywords--) | Gets the keywords. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Sets the keywords. |
| [getAllKeywords()](#getAllKeywords--) | Gets the keywords. |
| [setAllKeywords(String[] value)](#setAllKeywords-java.lang.String---) | Sets the keywords. |
| [getProgramVersion()](#getProgramVersion--) | Gets the program version. |
| [setProgramVersion(String value)](#setProgramVersion-java.lang.String-) | Sets the program version. |
| [getByIptcApplicationRecordDataSet(IptcApplicationRecordDataSet dataSetNumber)](#getByIptcApplicationRecordDataSet-com.groupdocs.metadata.core.IptcApplicationRecordDataSet-) | Gets the  IptcDataSet  with the specified number. |
### IptcApplicationRecord() {#IptcApplicationRecord--}
```
public IptcApplicationRecord()
```


Initializes a new instance of the  IptcApplicationRecord  class.

### getByLine() {#getByLine--}
```
public final String getByLine()
```


Gets the name of the creator of the object, e.g. writer, photographer or graphic artist.

**Returns:**
java.lang.String - The name of the creator of the object, e.g. writer, photographer or graphic artist.
### setByLine(String value) {#setByLine-java.lang.String-}
```
public final void setByLine(String value)
```


Sets the name of the creator of the object, e.g. writer, photographer or graphic artist.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the creator of the object, e.g. writer, photographer or graphic artist. |

### getByLines() {#getByLines--}
```
public final String[] getByLines()
```


Gets the names of the creators of the object, e.g. writer, photographer or graphic artist.

**Returns:**
java.lang.String[] - The names of the creators of the object, e.g. writer, photographer or graphic artist.
### setByLines(String[] value) {#setByLines-java.lang.String---}
```
public final void setByLines(String[] value)
```


Sets the names of the creators of the object, e.g. writer, photographer or graphic artist.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The names of the creators of the object, e.g. writer, photographer or graphic artist. |

### getByLineTitle() {#getByLineTitle--}
```
public final String getByLineTitle()
```


Gets the title of the creator or creators of the object.

**Returns:**
java.lang.String - The title of the creator or creators of the object.
### setByLineTitle(String value) {#setByLineTitle-java.lang.String-}
```
public final void setByLineTitle(String value)
```


Sets the title of the creator or creators of the object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The title of the creator or creators of the object. |

### getByLineTitles() {#getByLineTitles--}
```
public final String[] getByLineTitles()
```


Gets the titles of the creator or creators of the object.

**Returns:**
java.lang.String[] - The titles of the creator or creators of the object.
### setByLineTitles(String[] value) {#setByLineTitles-java.lang.String---}
```
public final void setByLineTitles(String[] value)
```


Sets the titles of the creator or creators of the object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The titles of the creator or creators of the object. |

### getContentLocationCode() {#getContentLocationCode--}
```
public final String getContentLocationCode()
```


Gets the content location code.

**Returns:**
java.lang.String - The content location code.
### setContentLocationCode(String value) {#setContentLocationCode-java.lang.String-}
```
public final void setContentLocationCode(String value)
```


Sets the content location code.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The content location code. |

### getContentLocationCodes() {#getContentLocationCodes--}
```
public final String[] getContentLocationCodes()
```


Gets the content location codes.

**Returns:**
java.lang.String[] - The content location codes.
### setContentLocationCodes(String[] value) {#setContentLocationCodes-java.lang.String---}
```
public final void setContentLocationCodes(String[] value)
```


Sets the content location codes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The content location codes. |

### getContentLocationName() {#getContentLocationName--}
```
public final String getContentLocationName()
```


Gets the content location name.

**Returns:**
java.lang.String - The name of the content location.
### setContentLocationName(String value) {#setContentLocationName-java.lang.String-}
```
public final void setContentLocationName(String value)
```


Sets the content location name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the content location. |

### getContentLocationNames() {#getContentLocationNames--}
```
public final String[] getContentLocationNames()
```


Gets the content location names.

**Returns:**
java.lang.String[] - The name of the content locations.
### setContentLocationNames(String[] value) {#setContentLocationNames-java.lang.String---}
```
public final void setContentLocationNames(String[] value)
```


Sets the content location names.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The name of the content locations. |

### getDateCreated() {#getDateCreated--}
```
public final Date getDateCreated()
```


Gets the date the intellectual content of the object was created.

**Returns:**
java.util.Date - The date the intellectual content of the object was created.
### setDateCreated(Date value) {#setDateCreated-java.util.Date-}
```
public final void setDateCreated(Date value)
```


Sets the date the intellectual content of the object was created.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The date the intellectual content of the object was created. |

### getReferenceDate() {#getReferenceDate--}
```
public final Date getReferenceDate()
```


Gets the date of a prior envelope to which the current object refers.

**Returns:**
java.util.Date - The date of a prior envelope to which the current object refers.
### setReferenceDate(Date value) {#setReferenceDate-java.util.Date-}
```
public final void setReferenceDate(Date value)
```


Sets the date of a prior envelope to which the current object refers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The date of a prior envelope to which the current object refers. |

### getReferenceDates() {#getReferenceDates--}
```
public final Date[] getReferenceDates()
```


Gets the dates of a prior envelope to which the current object refers.

**Returns:**
java.util.Date[] - The dates of a prior envelope to which the current object refers.
### getReleaseDate() {#getReleaseDate--}
```
public final Date getReleaseDate()
```


Gets the release date.

**Returns:**
java.util.Date - The release date.
### setReleaseDate(Date value) {#setReleaseDate-java.util.Date-}
```
public final void setReleaseDate(Date value)
```


Sets the release date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The release date. |

### getCredit() {#getCredit--}
```
public final String getCredit()
```


Gets information about the provider of the object, not necessarily the owner/creator.

**Returns:**
java.lang.String - The information about the provider of the object, not necessarily the owner/creator.
### setCredit(String value) {#setCredit-java.lang.String-}
```
public final void setCredit(String value)
```


Sets information about the provider of the object, not necessarily the owner/creator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The information about the provider of the object, not necessarily the owner/creator. |

### getHeadline() {#getHeadline--}
```
public final String getHeadline()
```


Gets a publishable entry providing a synopsis of the contents of the object.

**Returns:**
java.lang.String - A publishable entry providing a synopsis of the contents of the object.
### setHeadline(String value) {#setHeadline-java.lang.String-}
```
public final void setHeadline(String value)
```


Sets a publishable entry providing a synopsis of the contents of the object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A publishable entry providing a synopsis of the contents of the object. |

### getCopyrightNotice() {#getCopyrightNotice--}
```
public final String getCopyrightNotice()
```


Gets the copyright notice.

**Returns:**
java.lang.String - The copyright notice.
### setCopyrightNotice(String value) {#setCopyrightNotice-java.lang.String-}
```
public final void setCopyrightNotice(String value)
```


Sets the copyright notice.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The copyright notice. |

### getContact() {#getContact--}
```
public final String getContact()
```


Gets information about the person or organisation which can provide further background information on the object.

**Returns:**
java.lang.String - The information about the person or organisation which can provide further background information on the object.
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Sets information about the person or organisation which can provide further background information on the object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The information about the person or organisation which can provide further background information on the object. |

### getContacts() {#getContacts--}
```
public final String[] getContacts()
```


Gets information about the person or organisation which can provide further background information on the object.

**Returns:**
java.lang.String[] - The information about the person or organisation which can provide further background information on the object.
### setContacts(String[] value) {#setContacts-java.lang.String---}
```
public final void setContacts(String[] value)
```


Sets information about the person or organisation which can provide further background information on the object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The information about the person or organisation which can provide further background information on the object. |

### getCity() {#getCity--}
```
public final String getCity()
```


Gets the city.

**Returns:**
java.lang.String - The city.
### setCity(String value) {#setCity-java.lang.String-}
```
public final void setCity(String value)
```


Sets the city.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The city. |

### getCaptionAbstract() {#getCaptionAbstract--}
```
public final String getCaptionAbstract()
```


Gets a textual description of the object, particularly used where the object is not text.

**Returns:**
java.lang.String - TheA textual description of the object, particularly used where the object is not text.
### setCaptionAbstract(String value) {#setCaptionAbstract-java.lang.String-}
```
public final void setCaptionAbstract(String value)
```


Sets a textual description of the object, particularly used where the object is not text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | TheA textual description of the object, particularly used where the object is not text. |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```


Gets the keywords.

**Returns:**
java.lang.String - The keywords.
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```


Sets the keywords.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The keywords. |

### getAllKeywords() {#getAllKeywords--}
```
public final String[] getAllKeywords()
```


Gets the keywords.

**Returns:**
java.lang.String[] - The keywords.
### setAllKeywords(String[] value) {#setAllKeywords-java.lang.String---}
```
public final void setAllKeywords(String[] value)
```


Sets the keywords.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The keywords. |

### getProgramVersion() {#getProgramVersion--}
```
public final String getProgramVersion()
```


Gets the program version.

**Returns:**
java.lang.String - The program version.
### setProgramVersion(String value) {#setProgramVersion-java.lang.String-}
```
public final void setProgramVersion(String value)
```


Sets the program version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The program version. |

### getByIptcApplicationRecordDataSet(IptcApplicationRecordDataSet dataSetNumber) {#getByIptcApplicationRecordDataSet-com.groupdocs.metadata.core.IptcApplicationRecordDataSet-}
```
public final IptcDataSet getByIptcApplicationRecordDataSet(IptcApplicationRecordDataSet dataSetNumber)
```


Gets the  IptcDataSet  with the specified number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataSetNumber | [IptcApplicationRecordDataSet](../../com.groupdocs.metadata.core/iptcapplicationrecorddataset) | The dataSet number. |

**Returns:**
[IptcDataSet](../../com.groupdocs.metadata.core/iptcdataset) - The  IptcDataSet  with the specified number.
