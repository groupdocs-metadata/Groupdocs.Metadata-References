---
title: VCardCommunicationRecordset
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a set of Communication vCard records.
type: docs
weight: 261
url: /java/com.groupdocs.metadata.core/vcardcommunicationrecordset/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.VCardBasePackage](../../com.groupdocs.metadata.core/vcardbasepackage), [com.groupdocs.metadata.core.VCardRecordset](../../com.groupdocs.metadata.core/vcardrecordset)
```
public class VCardCommunicationRecordset extends VCardRecordset
```

Represents a set of Communication vCard records. These properties describe information about how to communicate with the object the vCard represents.

**Learn more**

 *  [Working with vCard metadata][]


[Working with vCard metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+vCard+metadata
## Methods

| Method | Description |
| --- | --- |
| [getTelephoneRecords()](#getTelephoneRecords--) | Gets the telephone numbers for telephony communication with the object. |
| [getTelephones()](#getTelephones--) | Gets the telephone numbers for telephony communication with the object. |
| [getEmailRecords()](#getEmailRecords--) | Gets the electronic mail addresses for communication with the object. |
| [getEmails()](#getEmails--) | Gets the electronic mail addresses for communication with the object. |
| [getMailer()](#getMailer--) | Gets the type of the electronic mail software that is used by the individual associated with the vCard. |
| [getImppRecords()](#getImppRecords--) | Gets the URIs for instant messaging and presence protocol communications with the object. |
| [getImppEntries()](#getImppEntries--) | Gets the URIs for instant messaging and presence protocol communications with the object. |
| [getLanguageRecords()](#getLanguageRecords--) | Gets the languages that may be used for contacting the object. |
| [getLanguages()](#getLanguages--) | Gets the languages that may be used for contacting the object. |
### getTelephoneRecords() {#getTelephoneRecords--}
```
public final VCardTextRecord[] getTelephoneRecords()
```


Gets the telephone numbers for telephony communication with the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The telephone numbers for telephony communication with the object.
### getTelephones() {#getTelephones--}
```
public final String[] getTelephones()
```


Gets the telephone numbers for telephony communication with the object.

**Returns:**
java.lang.String[] - The telephone numbers for telephony communication with the object.

--------------------

This property is a simplified version of  TelephoneRecords .
### getEmailRecords() {#getEmailRecords--}
```
public final VCardTextRecord[] getEmailRecords()
```


Gets the electronic mail addresses for communication with the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The electronic mail addresses array for communication with the object.
### getEmails() {#getEmails--}
```
public final String[] getEmails()
```


Gets the electronic mail addresses for communication with the object.

**Returns:**
java.lang.String[] - The electronic mail addresses array for communication with the object.

--------------------

This property is a simplified version of  EmailRecords .
### getMailer() {#getMailer--}
```
public final String getMailer()
```


Gets the type of the electronic mail software that is used by the individual associated with the vCard.

**Returns:**
java.lang.String - The type of the electronic mail software that is used by the individual associated with the vCard
### getImppRecords() {#getImppRecords--}
```
public final VCardTextRecord[] getImppRecords()
```


Gets the URIs for instant messaging and presence protocol communications with the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The URIs for instant messaging and presence protocol communications with the object.
### getImppEntries() {#getImppEntries--}
```
public final String[] getImppEntries()
```


Gets the URIs for instant messaging and presence protocol communications with the object.

**Returns:**
java.lang.String[] - The URIs for instant messaging and presence protocol communications with the object.

--------------------

This property is a simplified version of  ImppRecords .
### getLanguageRecords() {#getLanguageRecords--}
```
public final VCardTextRecord[] getLanguageRecords()
```


Gets the languages that may be used for contacting the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The languages that may be used for contacting the object.
### getLanguages() {#getLanguages--}
```
public final String[] getLanguages()
```


Gets the languages that may be used for contacting the object.

**Returns:**
java.lang.String[] - The languages that may be used for contacting the object.

--------------------

This property is a simplified version of  LanguageRecords .
