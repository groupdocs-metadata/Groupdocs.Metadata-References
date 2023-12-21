---
title: VCardGeneralRecordset
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a set of General vCard records.
type: docs
weight: 264
url: /java/com.groupdocs.metadata.core/vcardgeneralrecordset/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.VCardBasePackage](../../com.groupdocs.metadata.core/vcardbasepackage), [com.groupdocs.metadata.core.VCardRecordset](../../com.groupdocs.metadata.core/vcardrecordset)
```
public class VCardGeneralRecordset extends VCardRecordset
```

Represents a set of General vCard records.

**Learn more**

 *  [Working with vCard metadata][]


[Working with vCard metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+vCard+metadata
## Methods

| Method | Description |
| --- | --- |
| [getSourceRecords()](#getSourceRecords--) | Gets the array of sources of directory information contained in the content type. |
| [getSources()](#getSources--) | Gets an array containing the sources of the directory information contained in the content type. |
| [getNameOfSource()](#getNameOfSource--) | Gets the textual representation of the SOURCE property. |
| [getKind()](#getKind--) | Gets the kind of the object. |
| [getXmlRecords()](#getXmlRecords--) | Gets an array containing extended XML-encoded vCard data. |
| [getXmlEntries()](#getXmlEntries--) | Gets an array containing extended XML-encoded vCard data. |
### getSourceRecords() {#getSourceRecords--}
```
public final VCardTextRecord[] getSourceRecords()
```


Gets the array of sources of directory information contained in the content type.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The array of sources of directory information contained in the content type.
### getSources() {#getSources--}
```
public final String[] getSources()
```


Gets an array containing the sources of the directory information contained in the content type.

**Returns:**
java.lang.String[] - An array containing the sources of the directory information contained in the content type.

--------------------

This property is a simplified version of  SourceRecords .
### getNameOfSource() {#getNameOfSource--}
```
public final String getNameOfSource()
```


Gets the textual representation of the SOURCE property.

**Returns:**
java.lang.String - The textual representation of the SOURCE property.
### getKind() {#getKind--}
```
public final String getKind()
```


Gets the kind of the object.

**Returns:**
java.lang.String - The kind of object.
### getXmlRecords() {#getXmlRecords--}
```
public final VCardTextRecord[] getXmlRecords()
```


Gets an array containing extended XML-encoded vCard data.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - An array containing extended XML-encoded vCard data.
### getXmlEntries() {#getXmlEntries--}
```
public final String[] getXmlEntries()
```


Gets an array containing extended XML-encoded vCard data.

**Returns:**
java.lang.String[] - An array of extended XML-encoded vCard data.

--------------------

This property is a simplified version of  XmlRecords .
