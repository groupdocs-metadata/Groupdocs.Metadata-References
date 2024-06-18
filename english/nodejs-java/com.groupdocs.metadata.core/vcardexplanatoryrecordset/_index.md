---
title: VCardExplanatoryRecordset
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a set of Explanatory vCard records.
type: docs
weight: 272
url: /nodejs-java/com.groupdocs.metadata.core/vcardexplanatoryrecordset/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.VCardBasePackage](../../com.groupdocs.metadata.core/vcardbasepackage), [com.groupdocs.metadata.core.VCardRecordset](../../com.groupdocs.metadata.core/vcardrecordset)
```
public class VCardExplanatoryRecordset extends VCardRecordset
```

Represents a set of Explanatory vCard records. These properties are concerned with additional explanations, such as that related to informational notes or revisions specific to the vCard.

**Learn more**

 *  [Working with vCard metadata][]


[Working with vCard metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+vCard+metadata
## Methods

| Method | Description |
| --- | --- |
| [getCategoryRecords()](#getCategoryRecords--) | Gets the application category information about the vCard, also known as "tags". |
| [getCategories()](#getCategories--) | Gets the application category information about the vCard, also known as "tags". |
| [getNoteRecords()](#getNoteRecords--) | Gets the supplemental information or comments that are associated with the vCard. |
| [getNotes()](#getNotes--) | Gets the supplemental information or comments that are associated with the vCard. |
| [getProductIdentifierRecord()](#getProductIdentifierRecord--) | Gets the identifier of the product that created the vCard object. |
| [getProductIdentifier()](#getProductIdentifier--) | Gets the identifier of the product that created the vCard object. |
| [getRevision()](#getRevision--) | Gets the revision information about the current vCard. |
| [getSortString()](#getSortString--) | Gets the family name or given name text to be used for national-language-specific sorting of the  VCardIdentificationRecordset.FormattedNames  and  VCardIdentificationRecordset.Name  types. |
| [getSoundRecords()](#getSoundRecords--) | Gets the digital sound content information that annotates some aspects of the vCard. |
| [getSoundBinaryRecords()](#getSoundBinaryRecords--) | Gets the digital sound content information that annotates some aspects of the vCard. |
| [getBinarySounds()](#getBinarySounds--) | Gets the digital sound content information that annotates some aspects of the vCard. |
| [getSoundUriRecords()](#getSoundUriRecords--) | Gets the digital sound content information that annotates some aspects of the vCard. |
| [getUriSounds()](#getUriSounds--) | Gets the digital sound content information that annotates some aspects of the vCard. |
| [getUidRecord()](#getUidRecord--) | Gets the value that represents a globally unique identifier corresponding to the individual or resource associated with the vCard. |
| [getUid()](#getUid--) | Gets the value that represents a globally unique identifier corresponding to the individual or resource associated with the vCard. |
| [getPidIdentifierRecords()](#getPidIdentifierRecords--) | Gets the global meaning of the local PID source identifier. |
| [getPidIdentifiers()](#getPidIdentifiers--) | Gets the global meaning of the local PID source identifier. |
| [getUrlRecords()](#getUrlRecords--) | Gets an array of URLs pointing to websites that represent the person in some way. |
| [getUrls()](#getUrls--) | Gets an array of URLs pointing to websites that represent the person in some way. |
| [getVersion()](#getVersion--) | Gets the version of the vCard specification. |
### getCategoryRecords() {#getCategoryRecords--}
```
public final VCardTextRecord[] getCategoryRecords()
```


Gets the application category information about the vCard, also known as "tags".

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The application category information about the vCard, also known as "tags".
### getCategories() {#getCategories--}
```
public final String[] getCategories()
```


Gets the application category information about the vCard, also known as "tags".

**Returns:**
java.lang.String[] - The application category information about the vCard, also known as "tags".

--------------------

This property is a simplified version of  CategoryRecords .
### getNoteRecords() {#getNoteRecords--}
```
public final VCardTextRecord[] getNoteRecords()
```


Gets the supplemental information or comments that are associated with the vCard.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The supplemental information or comments that are associated with the vCard.
### getNotes() {#getNotes--}
```
public final String[] getNotes()
```


Gets the supplemental information or comments that are associated with the vCard.

**Returns:**
java.lang.String[] - The supplemental information or comments that are associated with the vCard.

--------------------

This property is a simplified version of  NoteRecords .
### getProductIdentifierRecord() {#getProductIdentifierRecord--}
```
public final VCardTextRecord getProductIdentifierRecord()
```


Gets the identifier of the product that created the vCard object.

**Returns:**
[VCardTextRecord](../../com.groupdocs.metadata.core/vcardtextrecord) - The identifier of the product that created the vCard object
### getProductIdentifier() {#getProductIdentifier--}
```
public final String getProductIdentifier()
```


Gets the identifier of the product that created the vCard object.

**Returns:**
java.lang.String - The identifier of the product that created the vCard object

--------------------

This property is a simplified version of  ProductIdentifierRecord .
### getRevision() {#getRevision--}
```
public final Date getRevision()
```


Gets the revision information about the current vCard.

**Returns:**
java.util.Date - The revision information about the current vCard.
### getSortString() {#getSortString--}
```
public final String getSortString()
```


Gets the family name or given name text to be used for national-language-specific sorting of the  VCardIdentificationRecordset.FormattedNames  and  VCardIdentificationRecordset.Name  types.

**Returns:**
java.lang.String - The family name or given name text to be used for national-language-specific sorting of the  VCardIdentificationRecordset.FormattedNames  and  VCardIdentificationRecordset.Name  types.
### getSoundRecords() {#getSoundRecords--}
```
public final VCardRecord[] getSoundRecords()
```


Gets the digital sound content information that annotates some aspects of the vCard.

**Returns:**
com.groupdocs.metadata.core.VCardRecord[] - The digital sound content information that annotates some aspects of the vCard.
### getSoundBinaryRecords() {#getSoundBinaryRecords--}
```
public final VCardBinaryRecord[] getSoundBinaryRecords()
```


Gets the digital sound content information that annotates some aspects of the vCard.

**Returns:**
com.groupdocs.metadata.core.VCardBinaryRecord[] - The digital sound content information that annotates some aspects of the vCard.

--------------------

This property is a simplified version of  SoundRecords .
### getBinarySounds() {#getBinarySounds--}
```
public final byte[][] getBinarySounds()
```


Gets the digital sound content information that annotates some aspects of the vCard.

**Returns:**
byte[][] - The digital sound content information that annotates some aspects of the vCard.

--------------------

This property is a simplified version of  SoundBinaryRecords .
### getSoundUriRecords() {#getSoundUriRecords--}
```
public final VCardTextRecord[] getSoundUriRecords()
```


Gets the digital sound content information that annotates some aspects of the vCard.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The digital sound content information that annotates some aspects of the vCard.

--------------------

This property is a simplified version of  SoundRecords .
### getUriSounds() {#getUriSounds--}
```
public final String[] getUriSounds()
```


Gets the digital sound content information that annotates some aspects of the vCard.

**Returns:**
java.lang.String[] - The digital sound content information that annotates some aspects of the vCard.

--------------------

This property is a simplified version of  SoundUriRecords .
### getUidRecord() {#getUidRecord--}
```
public final VCardTextRecord getUidRecord()
```


Gets the value that represents a globally unique identifier corresponding to the individual or resource associated with the vCard.

**Returns:**
[VCardTextRecord](../../com.groupdocs.metadata.core/vcardtextrecord) - The value that represents a globally unique identifier corresponding.
### getUid() {#getUid--}
```
public final String getUid()
```


Gets the value that represents a globally unique identifier corresponding to the individual or resource associated with the vCard.

**Returns:**
java.lang.String - The value that represents a globally unique identifier corresponding.

--------------------

This property is a simplified version of  UidRecord .
### getPidIdentifierRecords() {#getPidIdentifierRecords--}
```
public final VCardTextRecord[] getPidIdentifierRecords()
```


Gets the global meaning of the local PID source identifier.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The global meaning of the local PID source identifier.
### getPidIdentifiers() {#getPidIdentifiers--}
```
public final String[] getPidIdentifiers()
```


Gets the global meaning of the local PID source identifier.

**Returns:**
java.lang.String[] - The global meaning of the local PID source identifier.

--------------------

This property is a simplified version of  PidIdentifierRecords .
### getUrlRecords() {#getUrlRecords--}
```
public final VCardTextRecord[] getUrlRecords()
```


Gets an array of URLs pointing to websites that represent the person in some way.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - An array of URLs pointing to websites that represent the person in some way.
### getUrls() {#getUrls--}
```
public final String[] getUrls()
```


Gets an array of URLs pointing to websites that represent the person in some way.

**Returns:**
java.lang.String[] - An array of URLs pointing to websites that represent the person in some way.

--------------------

This property is a simplified version of  UrlRecords .
### getVersion() {#getVersion--}
```
public final String getVersion()
```


Gets the version of the vCard specification.

**Returns:**
java.lang.String - The version of the vCard specification.
