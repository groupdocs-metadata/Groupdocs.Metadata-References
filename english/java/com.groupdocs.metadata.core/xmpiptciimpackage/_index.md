---
title: XmpIptcIimPackage
second_title: GroupDocs.Signature for Java API Reference
description: Represents the IPTC-IIM XMP package.
type: docs
weight: 313
url: /java/com.groupdocs.metadata.core/xmpiptciimpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpPackage](../../com.groupdocs.metadata.core/xmppackage)
```
public final class XmpIptcIimPackage extends XmpPackage
```

Represents the IPTC-IIM XMP package.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpIptcIimPackage()](#XmpIptcIimPackage--) | Initializes a new instance of the  XmpIptcIimPackage  class. |
## Methods

| Method | Description |
| --- | --- |
| [getModelVersion()](#getModelVersion--) | Gets the binary number identifying the version of the Information |
| [setModelVersion(Integer value)](#setModelVersion-java.lang.Integer-) | Sets the binary number identifying the version of the Information |
| [getDestination()](#getDestination--) | Gets the destination. |
| [setDestination(String[] value)](#setDestination-java.lang.String---) | Sets the destination. |
| [getFileFormat()](#getFileFormat--) | Gets the binary number identifying the version of the Information |
| [setFileFormat(Integer value)](#setFileFormat-java.lang.Integer-) | Sets the binary number identifying the version of the Information |
| [getFileFormatVersion()](#getFileFormatVersion--) | Gets the file format version. |
| [setFileFormatVersion(Integer value)](#setFileFormatVersion-java.lang.Integer-) | Sets the file format version. |
| [getServiceIdentifier()](#getServiceIdentifier--) | Gets the service identifier. |
| [setServiceIdentifier(String value)](#setServiceIdentifier-java.lang.String-) | Sets the service identifier. |
| [getEnvelopeNumber()](#getEnvelopeNumber--) | Gets the envelope number. |
| [setEnvelopeNumber(String value)](#setEnvelopeNumber-java.lang.String-) | Sets the envelope number. |
| [getProductIDs()](#getProductIDs--) | Gets the product identifiers. |
| [setProductIDs(String[] value)](#setProductIDs-java.lang.String---) | Sets the product identifiers. |
| [getEnvelopePriority()](#getEnvelopePriority--) | Gets the envelope handling priority. |
| [setEnvelopePriority(Integer value)](#setEnvelopePriority-java.lang.Integer-) | Sets the envelope handling priority. |
| [getDateSent()](#getDateSent--) | Gets the date the service sent the material. |
| [setDateSent(Date value)](#setDateSent-java.util.Date-) | Sets the date the service sent the material. |
| [getUniqueNameOfObject()](#getUniqueNameOfObject--) | Gets the unique name of the object. |
| [setUniqueNameOfObject(String value)](#setUniqueNameOfObject-java.lang.String-) | Sets the unique name of the object. |
| [getObjectTypeReference()](#getObjectTypeReference--) | Gets the object type reference. |
| [setObjectTypeReference(String value)](#setObjectTypeReference-java.lang.String-) | Sets the object type reference. |
| [getEditStatus()](#getEditStatus--) | Gets the status of the object data, according to the practice of the provider. |
| [setEditStatus(String value)](#setEditStatus-java.lang.String-) | Sets the status of the object data, according to the practice of the provider. |
| [getUrgency()](#getUrgency--) | Gets the editorial urgency of the content. |
| [setUrgency(Integer value)](#setUrgency-java.lang.Integer-) | Sets the editorial urgency of the content. |
| [getCategory()](#getCategory--) | Gets the subject of the object data in the opinion of the provider. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Sets the subject of the object data in the opinion of the provider. |
| [getSupplementalCategories()](#getSupplementalCategories--) | Gets the supplemental categories. |
| [setSupplementalCategories(String[] value)](#setSupplementalCategories-java.lang.String---) | Sets the supplemental categories. |
| [getFixtureIdentifier()](#getFixtureIdentifier--) | Gets the object data that recurs often and predictably. |
| [setFixtureIdentifier(String value)](#setFixtureIdentifier-java.lang.String-) | Sets the object data that recurs often and predictably. |
| [getContentLocationCodes()](#getContentLocationCodes--) | Gets the content location codes. |
| [setContentLocationCodes(String[] value)](#setContentLocationCodes-java.lang.String---) | Sets the content location codes. |
| [getContentLocationNames()](#getContentLocationNames--) | Gets the content location names. |
| [setContentLocationNames(String[] value)](#setContentLocationNames-java.lang.String---) | Sets the content location names. |
| [getReleaseDate()](#getReleaseDate--) | Gets the earliest date the provider intends the object to be used. |
| [setReleaseDate(Date value)](#setReleaseDate-java.util.Date-) | Sets the earliest date the provider intends the object to be used. |
| [getExpirationDate()](#getExpirationDate--) | Gets the latest date the provider or owner intends the object data to be used. |
| [setExpirationDate(Date value)](#setExpirationDate-java.util.Date-) | Sets the latest date the provider or owner intends the object data to be used. |
| [getActionAdvised()](#getActionAdvised--) | Gets the type of action that this object provides to a previous object. |
| [setActionAdvised(String value)](#setActionAdvised-java.lang.String-) | Sets the type of action that this object provides to a previous object. |
| [getReferenceService()](#getReferenceService--) | Gets the Service Identifier of a prior envelope to which the current object refers. |
| [setReferenceService(String value)](#setReferenceService-java.lang.String-) | Sets the Service Identifier of a prior envelope to which the current object refers. |
| [getReferenceDate()](#getReferenceDate--) | Gets the date of a prior envelope to which the current object refers. |
| [setReferenceDate(Date value)](#setReferenceDate-java.util.Date-) | Sets the date of a prior envelope to which the current object refers. |
| [getReferenceNumber()](#getReferenceNumber--) | Gets the Envelope Number of a prior envelope to which the current object refers. |
| [setReferenceNumber(String value)](#setReferenceNumber-java.lang.String-) | Sets the Envelope Number of a prior envelope to which the current object refers. |
| [getDigitalCreationDate()](#getDigitalCreationDate--) | Gets the date the digital representation of the object data was created. |
| [setDigitalCreationDate(Date value)](#setDigitalCreationDate-java.util.Date-) | Sets the date the digital representation of the object data was created. |
| [getOriginatingProgram()](#getOriginatingProgram--) | Gets the type of program used to originate the object data. |
| [setOriginatingProgram(String value)](#setOriginatingProgram-java.lang.String-) | Sets the type of program used to originate the object data. |
| [getProgramVersion()](#getProgramVersion--) | Gets the program version. |
| [setProgramVersion(String value)](#setProgramVersion-java.lang.String-) | Sets the program version. |
| [getImageType()](#getImageType--) | Gets the type of the image. |
| [setImageType(String value)](#setImageType-java.lang.String-) | Sets the type of the image. |
| [getImageOrientation()](#getImageOrientation--) | Gets the image orientation. |
| [setImageOrientation(String value)](#setImageOrientation-java.lang.String-) | Sets the image orientation. |
| [getLanguageIdentifier()](#getLanguageIdentifier--) | Gets the language identifier according to the 2-letter codes of ISO 639:1988. |
| [setLanguageIdentifier(String value)](#setLanguageIdentifier-java.lang.String-) | Sets the language identifier according to the 2-letter codes of ISO 639:1988. |
| [set(String name, String value)](#set-java.lang.String-java.lang.String-) | Sets string property. |
### XmpIptcIimPackage() {#XmpIptcIimPackage--}
```
public XmpIptcIimPackage()
```


Initializes a new instance of the  XmpIptcIimPackage  class.

### getModelVersion() {#getModelVersion--}
```
public final Integer getModelVersion()
```


Gets the binary number identifying the version of the Information

**Returns:**
java.lang.Integer - The model version.
### setModelVersion(Integer value) {#setModelVersion-java.lang.Integer-}
```
public final void setModelVersion(Integer value)
```


Sets the binary number identifying the version of the Information

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The model version. |

### getDestination() {#getDestination--}
```
public final String[] getDestination()
```


Gets the destination. This DataSet is to accommodate some providers who require routing information above the appropriate OSI layers.

**Returns:**
java.lang.String[] - The destination.
### setDestination(String[] value) {#setDestination-java.lang.String---}
```
public final void setDestination(String[] value)
```


Sets the destination. This DataSet is to accommodate some providers who require routing information above the appropriate OSI layers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The destination. |

### getFileFormat() {#getFileFormat--}
```
public final Integer getFileFormat()
```


Gets the binary number identifying the version of the Information

**Returns:**
java.lang.Integer - The file format.
### setFileFormat(Integer value) {#setFileFormat-java.lang.Integer-}
```
public final void setFileFormat(Integer value)
```


Sets the binary number identifying the version of the Information

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The file format. |

### getFileFormatVersion() {#getFileFormatVersion--}
```
public final Integer getFileFormatVersion()
```


Gets the file format version.

**Returns:**
java.lang.Integer - The file format version.
### setFileFormatVersion(Integer value) {#setFileFormatVersion-java.lang.Integer-}
```
public final void setFileFormatVersion(Integer value)
```


Sets the file format version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The file format version. |

### getServiceIdentifier() {#getServiceIdentifier--}
```
public final String getServiceIdentifier()
```


Gets the service identifier. Identifies the provider and product.

**Returns:**
java.lang.String - The service identifier.
### setServiceIdentifier(String value) {#setServiceIdentifier-java.lang.String-}
```
public final void setServiceIdentifier(String value)
```


Sets the service identifier. Identifies the provider and product.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The service identifier. |

### getEnvelopeNumber() {#getEnvelopeNumber--}
```
public final String getEnvelopeNumber()
```


Gets the envelope number.

**Returns:**
java.lang.String - The envelope number.
### setEnvelopeNumber(String value) {#setEnvelopeNumber-java.lang.String-}
```
public final void setEnvelopeNumber(String value)
```


Sets the envelope number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The envelope number. |

### getProductIDs() {#getProductIDs--}
```
public final String[] getProductIDs()
```


Gets the product identifiers.

**Returns:**
java.lang.String[] - The product identifier.

--------------------

Used to provide receiving organization data on which to select, route, or otherwise handle data.
### setProductIDs(String[] value) {#setProductIDs-java.lang.String---}
```
public final void setProductIDs(String[] value)
```


Sets the product identifiers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The product identifier.

--------------------

Used to provide receiving organization data on which to select, route, or otherwise handle data. |

### getEnvelopePriority() {#getEnvelopePriority--}
```
public final Integer getEnvelopePriority()
```


Gets the envelope handling priority.

**Returns:**
java.lang.Integer - The envelope priority.
### setEnvelopePriority(Integer value) {#setEnvelopePriority-java.lang.Integer-}
```
public final void setEnvelopePriority(Integer value)
```


Sets the envelope handling priority.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The envelope priority. |

### getDateSent() {#getDateSent--}
```
public final Date getDateSent()
```


Gets the date the service sent the material.

**Returns:**
java.util.Date - The date sent.
### setDateSent(Date value) {#setDateSent-java.util.Date-}
```
public final void setDateSent(Date value)
```


Sets the date the service sent the material.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The date sent. |

### getUniqueNameOfObject() {#getUniqueNameOfObject--}
```
public final String getUniqueNameOfObject()
```


Gets the unique name of the object.

**Returns:**
java.lang.String - The unique name of the object.
### setUniqueNameOfObject(String value) {#setUniqueNameOfObject-java.lang.String-}
```
public final void setUniqueNameOfObject(String value)
```


Sets the unique name of the object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The unique name of the object. |

### getObjectTypeReference() {#getObjectTypeReference--}
```
public final String getObjectTypeReference()
```


Gets the object type reference. The Object Type is used to distinguish between different types of objects within the IIM.

**Returns:**
java.lang.String - The object type reference.
### setObjectTypeReference(String value) {#setObjectTypeReference-java.lang.String-}
```
public final void setObjectTypeReference(String value)
```


Sets the object type reference. The Object Type is used to distinguish between different types of objects within the IIM.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The object type reference. |

### getEditStatus() {#getEditStatus--}
```
public final String getEditStatus()
```


Gets the status of the object data, according to the practice of the provider.

**Returns:**
java.lang.String - The edit status.
### setEditStatus(String value) {#setEditStatus-java.lang.String-}
```
public final void setEditStatus(String value)
```


Sets the status of the object data, according to the practice of the provider.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The edit status. |

### getUrgency() {#getUrgency--}
```
public final Integer getUrgency()
```


Gets the editorial urgency of the content.

**Returns:**
java.lang.Integer - The urgency.
### setUrgency(Integer value) {#setUrgency-java.lang.Integer-}
```
public final void setUrgency(Integer value)
```


Sets the editorial urgency of the content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The urgency. |

### getCategory() {#getCategory--}
```
public final String getCategory()
```


Gets the subject of the object data in the opinion of the provider.

**Returns:**
java.lang.String - The category.
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```


Sets the subject of the object data in the opinion of the provider.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The category. |

### getSupplementalCategories() {#getSupplementalCategories--}
```
public final String[] getSupplementalCategories()
```


Gets the supplemental categories.

**Returns:**
java.lang.String[] - The supplemental categories.
### setSupplementalCategories(String[] value) {#setSupplementalCategories-java.lang.String---}
```
public final void setSupplementalCategories(String[] value)
```


Sets the supplemental categories.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The supplemental categories. |

### getFixtureIdentifier() {#getFixtureIdentifier--}
```
public final String getFixtureIdentifier()
```


Gets the object data that recurs often and predictably.

**Returns:**
java.lang.String - The fixture identifier.
### setFixtureIdentifier(String value) {#setFixtureIdentifier-java.lang.String-}
```
public final void setFixtureIdentifier(String value)
```


Sets the object data that recurs often and predictably.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The fixture identifier. |

### getContentLocationCodes() {#getContentLocationCodes--}
```
public final String[] getContentLocationCodes()
```


Gets the content location codes.

**Returns:**
java.lang.String[] - The content location codes.

--------------------

Indicates the code of a country/geographical location referenced by the content of the object.
### setContentLocationCodes(String[] value) {#setContentLocationCodes-java.lang.String---}
```
public final void setContentLocationCodes(String[] value)
```


Sets the content location codes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The content location codes.

--------------------

Indicates the code of a country/geographical location referenced by the content of the object. |

### getContentLocationNames() {#getContentLocationNames--}
```
public final String[] getContentLocationNames()
```


Gets the content location names.

**Returns:**
java.lang.String[] - The content location names.

--------------------

Provides a full, publishable name of a country/geographical location referenced by the content of the object, according to guidelines of the provider.
### setContentLocationNames(String[] value) {#setContentLocationNames-java.lang.String---}
```
public final void setContentLocationNames(String[] value)
```


Sets the content location names.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The content location names.

--------------------

Provides a full, publishable name of a country/geographical location referenced by the content of the object, according to guidelines of the provider. |

### getReleaseDate() {#getReleaseDate--}
```
public final Date getReleaseDate()
```


Gets the earliest date the provider intends the object to be used.

**Returns:**
java.util.Date - The release date.
### setReleaseDate(Date value) {#setReleaseDate-java.util.Date-}
```
public final void setReleaseDate(Date value)
```


Sets the earliest date the provider intends the object to be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The release date. |

### getExpirationDate() {#getExpirationDate--}
```
public final Date getExpirationDate()
```


Gets the latest date the provider or owner intends the object data to be used.

**Returns:**
java.util.Date - The expiration date.
### setExpirationDate(Date value) {#setExpirationDate-java.util.Date-}
```
public final void setExpirationDate(Date value)
```


Sets the latest date the provider or owner intends the object data to be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The expiration date. |

### getActionAdvised() {#getActionAdvised--}
```
public final String getActionAdvised()
```


Gets the type of action that this object provides to a previous object.

**Returns:**
java.lang.String - The type of action.
### setActionAdvised(String value) {#setActionAdvised-java.lang.String-}
```
public final void setActionAdvised(String value)
```


Sets the type of action that this object provides to a previous object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The type of action. |

### getReferenceService() {#getReferenceService--}
```
public final String getReferenceService()
```


Gets the Service Identifier of a prior envelope to which the current object refers.

**Returns:**
java.lang.String - The reference service.
### setReferenceService(String value) {#setReferenceService-java.lang.String-}
```
public final void setReferenceService(String value)
```


Sets the Service Identifier of a prior envelope to which the current object refers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The reference service. |

### getReferenceDate() {#getReferenceDate--}
```
public final Date getReferenceDate()
```


Gets the date of a prior envelope to which the current object refers.

**Returns:**
java.util.Date - The reference date.
### setReferenceDate(Date value) {#setReferenceDate-java.util.Date-}
```
public final void setReferenceDate(Date value)
```


Sets the date of a prior envelope to which the current object refers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The reference date. |

### getReferenceNumber() {#getReferenceNumber--}
```
public final String getReferenceNumber()
```


Gets the Envelope Number of a prior envelope to which the current object refers.

**Returns:**
java.lang.String - The reference number.
### setReferenceNumber(String value) {#setReferenceNumber-java.lang.String-}
```
public final void setReferenceNumber(String value)
```


Sets the Envelope Number of a prior envelope to which the current object refers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The reference number. |

### getDigitalCreationDate() {#getDigitalCreationDate--}
```
public final Date getDigitalCreationDate()
```


Gets the date the digital representation of the object data was created.

**Returns:**
java.util.Date - The digital creation date.
### setDigitalCreationDate(Date value) {#setDigitalCreationDate-java.util.Date-}
```
public final void setDigitalCreationDate(Date value)
```


Sets the date the digital representation of the object data was created.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The digital creation date. |

### getOriginatingProgram() {#getOriginatingProgram--}
```
public final String getOriginatingProgram()
```


Gets the type of program used to originate the object data.

**Returns:**
java.lang.String - The originating program.
### setOriginatingProgram(String value) {#setOriginatingProgram-java.lang.String-}
```
public final void setOriginatingProgram(String value)
```


Sets the type of program used to originate the object data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The originating program. |

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

### getImageType() {#getImageType--}
```
public final String getImageType()
```


Gets the type of the image.

**Returns:**
java.lang.String - The type of the image.

--------------------

The first is a numeric character and the second is an alphabetic character.
### setImageType(String value) {#setImageType-java.lang.String-}
```
public final void setImageType(String value)
```


Sets the type of the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The type of the image.

--------------------

The first is a numeric character and the second is an alphabetic character. |

### getImageOrientation() {#getImageOrientation--}
```
public final String getImageOrientation()
```


Gets the image orientation. Indicates the layout of the image area. Allowed values are P (for Portrait), L (for Landscape) and S (for Square).

**Returns:**
java.lang.String - The image orientation.
### setImageOrientation(String value) {#setImageOrientation-java.lang.String-}
```
public final void setImageOrientation(String value)
```


Sets the image orientation. Indicates the layout of the image area. Allowed values are P (for Portrait), L (for Landscape) and S (for Square).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The image orientation. |

### getLanguageIdentifier() {#getLanguageIdentifier--}
```
public final String getLanguageIdentifier()
```


Gets the language identifier according to the 2-letter codes of ISO 639:1988.

**Returns:**
java.lang.String - The language identifier.
### setLanguageIdentifier(String value) {#setLanguageIdentifier-java.lang.String-}
```
public final void setLanguageIdentifier(String value)
```


Sets the language identifier according to the 2-letter codes of ISO 639:1988.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The language identifier. |

### set(String name, String value) {#set-java.lang.String-java.lang.String-}
```
public void set(String name, String value)
```


Sets string property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XMP metadata property name. |
| value | java.lang.String | XMP metadata property value. |

