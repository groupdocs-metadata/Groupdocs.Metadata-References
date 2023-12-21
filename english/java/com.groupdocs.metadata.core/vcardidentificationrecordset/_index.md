---
title: VCardIdentificationRecordset
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a set of Identification vCard records.
type: docs
weight: 266
url: /java/com.groupdocs.metadata.core/vcardidentificationrecordset/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.VCardBasePackage](../../com.groupdocs.metadata.core/vcardbasepackage), [com.groupdocs.metadata.core.VCardRecordset](../../com.groupdocs.metadata.core/vcardrecordset)
```
public class VCardIdentificationRecordset extends VCardRecordset
```

Represents a set of Identification vCard records. These types are used to capture information associated with the identification and naming of the entity associated with the vCard.

**Learn more**

 *  [Working with vCard metadata][]


[Working with vCard metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+vCard+metadata
## Methods

| Method | Description |
| --- | --- |
| [getFormattedNameRecords()](#getFormattedNameRecords--) | Gets an array containing the formatted text corresponding to the name of the object. |
| [getFormattedNames()](#getFormattedNames--) | Gets an array containing the formatted text corresponding to the name of the object. |
| [getNameRecord()](#getNameRecord--) | Gets the components of the name of the object. |
| [getName()](#getName--) | Gets the components of the name of the object. |
| [getNicknameRecords()](#getNicknameRecords--) | Gets an array containing the text corresponding to the nickname of the object. |
| [getNicknames()](#getNicknames--) | Gets an array containing the text corresponding to the nickname of the object. |
| [getPhotoRecords()](#getPhotoRecords--) | Gets an array containing the image or photograph information that annotates some aspects of the object. |
| [getPhotoBinaryRecords()](#getPhotoBinaryRecords--) | Gets an array containing the image or photograph information represented as binary data that annotates some aspects of the object. |
| [getBinaryPhotos()](#getBinaryPhotos--) | Gets an array containing the image or photograph information represented as binary data that annotates some aspects of the object. |
| [getPhotoUriRecords()](#getPhotoUriRecords--) | Gets an array containing the image or photograph information represented by URIs that annotates some aspects of the object. |
| [getUriPhotos()](#getUriPhotos--) | Gets an array containing the image or photograph information represented by URIs that annotates some aspects of the object. |
| [getBirthdateRecords()](#getBirthdateRecords--) | Gets an array containing the birth date of the object in different representations. |
| [getBirthdateDateTimeRecord()](#getBirthdateDateTimeRecord--) | Gets the birth date of the object. |
| [getDateTimeBirthdate()](#getDateTimeBirthdate--) | Gets the birth date of the object. |
| [getBirthdateTextRecords()](#getBirthdateTextRecords--) | Gets an array containing the birth date of the object in different text representations. |
| [getTextBirthdates()](#getTextBirthdates--) | Gets an array containing the birth date of the object in different text representations. |
| [getAnniversaryRecord()](#getAnniversaryRecord--) | Gets the date of marriage, or equivalent, of the object. |
| [getAnniversaryDateTimeRecord()](#getAnniversaryDateTimeRecord--) | Gets the date of marriage represented as a single date-and-or-time value. |
| [getDateTimeAnniversary()](#getDateTimeAnniversary--) | Gets the date of marriage represented as a single date-and-or-time value. |
| [getAnniversaryTextRecord()](#getAnniversaryTextRecord--) | Gets the date of marriage represented as a single text value. |
| [getTextAnniversary()](#getTextAnniversary--) | Gets the date of marriage represented as a single text value. |
| [getGenderRecord()](#getGenderRecord--) | Gets the components of the sex and gender identity of the object. |
| [getGender()](#getGender--) | Gets the components of the sex and gender identity of the object. |
### getFormattedNameRecords() {#getFormattedNameRecords--}
```
public final VCardTextRecord[] getFormattedNameRecords()
```


Gets an array containing the formatted text corresponding to the name of the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - An array containing the formatted text corresponding to the name of the object.
### getFormattedNames() {#getFormattedNames--}
```
public final String[] getFormattedNames()
```


Gets an array containing the formatted text corresponding to the name of the object.

**Returns:**
java.lang.String[] - An array containing the formatted text corresponding to the name of the object.

--------------------

This property is a simplified version of  FormattedNameRecords .
### getNameRecord() {#getNameRecord--}
```
public final VCardTextRecord getNameRecord()
```


Gets the components of the name of the object.

**Returns:**
[VCardTextRecord](../../com.groupdocs.metadata.core/vcardtextrecord) - The components of the name of the object.
### getName() {#getName--}
```
public final String getName()
```


Gets the components of the name of the object.

**Returns:**
java.lang.String - The components of the name of the object.

--------------------

This property is a simplified version of  NameRecord .
### getNicknameRecords() {#getNicknameRecords--}
```
public final VCardTextRecord[] getNicknameRecords()
```


Gets an array containing the text corresponding to the nickname of the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - An array containing the text corresponding to the nickname of the object.
### getNicknames() {#getNicknames--}
```
public final String[] getNicknames()
```


Gets an array containing the text corresponding to the nickname of the object.

**Returns:**
java.lang.String[] - An array containing the text corresponding to the nickname of the object.

--------------------

This property is a simplified version of  NicknameRecords .
### getPhotoRecords() {#getPhotoRecords--}
```
public final VCardRecord[] getPhotoRecords()
```


Gets an array containing the image or photograph information that annotates some aspects of the object.

**Returns:**
com.groupdocs.metadata.core.VCardRecord[] - An array containing the image or photograph information that annotates some aspects of the object.
### getPhotoBinaryRecords() {#getPhotoBinaryRecords--}
```
public final VCardBinaryRecord[] getPhotoBinaryRecords()
```


Gets an array containing the image or photograph information represented as binary data that annotates some aspects of the object.

**Returns:**
com.groupdocs.metadata.core.VCardBinaryRecord[] - An array containing the image or photograph information represented as binary data that annotates some aspects of the object.

--------------------

This property is a simplified version of  PhotoRecords .
### getBinaryPhotos() {#getBinaryPhotos--}
```
public final byte[][] getBinaryPhotos()
```


Gets an array containing the image or photograph information represented as binary data that annotates some aspects of the object.

**Returns:**
byte[][] - An array containing the image or photograph information represented as binary data that annotates some aspects of the object.

--------------------

This property is a simplified version of  PhotoBinaryRecords .
### getPhotoUriRecords() {#getPhotoUriRecords--}
```
public final VCardTextRecord[] getPhotoUriRecords()
```


Gets an array containing the image or photograph information represented by URIs that annotates some aspects of the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - An array containing the image or photograph information represented by URIs that annotates some aspects of the object.

--------------------

This property is a simplified version of  PhotoRecords .
### getUriPhotos() {#getUriPhotos--}
```
public final String[] getUriPhotos()
```


Gets an array containing the image or photograph information represented by URIs that annotates some aspects of the object.

**Returns:**
java.lang.String[] - An array containing the image or photograph information represented by URIs that annotates some aspects of the object.

--------------------

This property is a simplified version of  PhotoUriRecords .
### getBirthdateRecords() {#getBirthdateRecords--}
```
public final VCardRecord[] getBirthdateRecords()
```


Gets an array containing the birth date of the object in different representations.

**Returns:**
com.groupdocs.metadata.core.VCardRecord[] - An array containing the birth date of the object in different representations.
### getBirthdateDateTimeRecord() {#getBirthdateDateTimeRecord--}
```
public final VCardDateTimeRecord getBirthdateDateTimeRecord()
```


Gets the birth date of the object.

**Returns:**
[VCardDateTimeRecord](../../com.groupdocs.metadata.core/vcarddatetimerecord) - The birth date of the object.

--------------------

This property is a simplified version of  BirthdateRecords .
### getDateTimeBirthdate() {#getDateTimeBirthdate--}
```
public final Date getDateTimeBirthdate()
```


Gets the birth date of the object.

**Returns:**
java.util.Date - The birth date of the object.

--------------------

This property is a simplified version of  BirthdateDateTimeRecord .
### getBirthdateTextRecords() {#getBirthdateTextRecords--}
```
public final VCardTextRecord[] getBirthdateTextRecords()
```


Gets an array containing the birth date of the object in different text representations.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - An array containing the birth date of the object in different text representations.

--------------------

This property is a simplified version of  BirthdateRecords .
### getTextBirthdates() {#getTextBirthdates--}
```
public final String[] getTextBirthdates()
```


Gets an array containing the birth date of the object in different text representations.

**Returns:**
java.lang.String[] - An array containing the birth date of the object in different text representations.

--------------------

This property is a simplified version of  BirthdateTextRecords .
### getAnniversaryRecord() {#getAnniversaryRecord--}
```
public final VCardRecord getAnniversaryRecord()
```


Gets the date of marriage, or equivalent, of the object.

**Returns:**
[VCardRecord](../../com.groupdocs.metadata.core/vcardrecord) - The date of marriage, or equivalent, of the object.
### getAnniversaryDateTimeRecord() {#getAnniversaryDateTimeRecord--}
```
public final VCardDateTimeRecord getAnniversaryDateTimeRecord()
```


Gets the date of marriage represented as a single date-and-or-time value.

**Returns:**
[VCardDateTimeRecord](../../com.groupdocs.metadata.core/vcarddatetimerecord) - The date of marriage represented as a single date-and-or-time value.

--------------------

This property is a simplified version of  AnniversaryRecord .
### getDateTimeAnniversary() {#getDateTimeAnniversary--}
```
public final Date getDateTimeAnniversary()
```


Gets the date of marriage represented as a single date-and-or-time value.

**Returns:**
java.util.Date - The date of marriage represented as a single date-and-or-time value.

--------------------

This property is a simplified version of  AnniversaryDateTimeRecord .
### getAnniversaryTextRecord() {#getAnniversaryTextRecord--}
```
public final VCardTextRecord getAnniversaryTextRecord()
```


Gets the date of marriage represented as a single text value.

**Returns:**
[VCardTextRecord](../../com.groupdocs.metadata.core/vcardtextrecord) - The date of marriage represented as a single text value.

--------------------

This property is a simplified version of  AnniversaryRecord .
### getTextAnniversary() {#getTextAnniversary--}
```
public final String getTextAnniversary()
```


Gets the date of marriage represented as a single text value.

**Returns:**
java.lang.String - The date of marriage represented as a single text value.

--------------------

This property is a simplified version of  AnniversaryTextRecord .
### getGenderRecord() {#getGenderRecord--}
```
public final VCardTextRecord getGenderRecord()
```


Gets the components of the sex and gender identity of the object.

**Returns:**
[VCardTextRecord](../../com.groupdocs.metadata.core/vcardtextrecord) - The components of the sex and gender identity of the object.
### getGender() {#getGender--}
```
public final String getGender()
```


Gets the components of the sex and gender identity of the object.

**Returns:**
java.lang.String - The components of the sex and gender identity of the object.

--------------------

This property is a simplified version of  GenderRecord .
