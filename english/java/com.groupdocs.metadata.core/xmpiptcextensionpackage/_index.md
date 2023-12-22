---
title: XmpIptcExtensionPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the IPTC Extension XMP package.
type: docs
weight: 312
url: /java/com.groupdocs.metadata.core/xmpiptcextensionpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpPackage](../../com.groupdocs.metadata.core/xmppackage)
```
public final class XmpIptcExtensionPackage extends XmpPackage
```

Represents the IPTC Extension XMP package.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpIptcExtensionPackage()](#XmpIptcExtensionPackage--) | Initializes a new instance of the  XmpIptcExtensionPackage  class. |
## Methods

| Method | Description |
| --- | --- |
| [getAdditionalModelInformation()](#getAdditionalModelInformation--) | Gets the information about the ethnicity and other facets of the model(s) in a model-released image. |
| [setAdditionalModelInformation(String value)](#setAdditionalModelInformation-java.lang.String-) | Sets the information about the ethnicity and other facets of the model(s) in a model-released image. |
| [getOrganisationInImageCodes()](#getOrganisationInImageCodes--) | Gets codes from a controlled vocabulary for identifying the organisations or companies which are featured in the image. |
| [setOrganisationInImageCodes(String[] value)](#setOrganisationInImageCodes-java.lang.String---) | Sets codes from a controlled vocabulary for identifying the organisations or companies which are featured in the image. |
| [getOrganisationInImageNames()](#getOrganisationInImageNames--) | Gets names of the organisations or companies which are featured in the image. |
| [setOrganisationInImageNames(String[] value)](#setOrganisationInImageNames-java.lang.String---) | Sets names of the organisations or companies which are featured in the image. |
| [getAgesOfModels()](#getAgesOfModels--) | Gets ages of the human models at the time this image was taken in a model released image. |
| [setAgesOfModels(int[] value)](#setAgesOfModels-int---) | Sets ages of the human models at the time this image was taken in a model released image. |
| [getPersonsInImage()](#getPersonsInImage--) | Gets names of the persons the content of the item is about. |
| [setPersonsInImage(String[] value)](#setPersonsInImage-java.lang.String---) | Sets names of the persons the content of the item is about. |
| [getDigitalImageGuid()](#getDigitalImageGuid--) | Gets the globally unique identifier for this digital image. |
| [setDigitalImageGuid(String value)](#setDigitalImageGuid-java.lang.String-) | Sets the globally unique identifier for this digital image. |
| [getDigitalSourceType()](#getDigitalSourceType--) | Gets the type of the source of this digital image. |
| [setDigitalSourceType(String value)](#setDigitalSourceType-java.lang.String-) | Sets the type of the source of this digital image. |
| [getEvent()](#getEvent--) | Gets the description of the specific event at which the photo was taken. |
| [setEvent(XmpLangAlt value)](#setEvent-com.groupdocs.metadata.core.XmpLangAlt-) | Sets the description of the specific event at which the photo was taken. |
| [getIptcLastEdited()](#getIptcLastEdited--) | Gets the date and optionally time when any of the IPTC photo metadata fields has been last edited. |
| [setIptcLastEdited(Date value)](#setIptcLastEdited-java.util.Date-) | Sets the date and optionally time when any of the IPTC photo metadata fields has been last edited. |
| [getMaxAvailableHeight()](#getMaxAvailableHeight--) | Gets the maximum available height in pixels of the original photo from which this photo has been derived by downsizing. |
| [setMaxAvailableHeight(Integer value)](#setMaxAvailableHeight-java.lang.Integer-) | Sets the maximum available height in pixels of the original photo from which this photo has been derived by downsizing. |
| [getMaxAvailableWidth()](#getMaxAvailableWidth--) | Gets the the maximum available width in pixels of the original photo from which this photo has been derived by downsizing. |
| [setMaxAvailableWidth(Integer value)](#setMaxAvailableWidth-java.lang.Integer-) | Sets the the maximum available width in pixels of the original photo from which this photo has been derived by downsizing. |
| [set(String name, String value)](#set-java.lang.String-java.lang.String-) | Sets string property. |
| [set(String name, XmpArray value)](#set-java.lang.String-com.groupdocs.metadata.core.XmpArray-) | Sets the value inherited from  XmpArray  . |
### XmpIptcExtensionPackage() {#XmpIptcExtensionPackage--}
```
public XmpIptcExtensionPackage()
```


Initializes a new instance of the  XmpIptcExtensionPackage  class.

### getAdditionalModelInformation() {#getAdditionalModelInformation--}
```
public final String getAdditionalModelInformation()
```


Gets the information about the ethnicity and other facets of the model(s) in a model-released image.

**Returns:**
java.lang.String - The additional model information.
### setAdditionalModelInformation(String value) {#setAdditionalModelInformation-java.lang.String-}
```
public final void setAdditionalModelInformation(String value)
```


Sets the information about the ethnicity and other facets of the model(s) in a model-released image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The additional model information. |

### getOrganisationInImageCodes() {#getOrganisationInImageCodes--}
```
public final String[] getOrganisationInImageCodes()
```


Gets codes from a controlled vocabulary for identifying the organisations or companies which are featured in the image.

**Returns:**
java.lang.String[] - The codes of the organisations.
### setOrganisationInImageCodes(String[] value) {#setOrganisationInImageCodes-java.lang.String---}
```
public final void setOrganisationInImageCodes(String[] value)
```


Sets codes from a controlled vocabulary for identifying the organisations or companies which are featured in the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The codes of the organisations. |

### getOrganisationInImageNames() {#getOrganisationInImageNames--}
```
public final String[] getOrganisationInImageNames()
```


Gets names of the organisations or companies which are featured in the image.

**Returns:**
java.lang.String[] - Names of the organisations.
### setOrganisationInImageNames(String[] value) {#setOrganisationInImageNames-java.lang.String---}
```
public final void setOrganisationInImageNames(String[] value)
```


Sets names of the organisations or companies which are featured in the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | Names of the organisations. |

### getAgesOfModels() {#getAgesOfModels--}
```
public final int[] getAgesOfModels()
```


Gets ages of the human models at the time this image was taken in a model released image.

**Returns:**
int[] - Ages of the models.
### setAgesOfModels(int[] value) {#setAgesOfModels-int---}
```
public final void setAgesOfModels(int[] value)
```


Sets ages of the human models at the time this image was taken in a model released image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | Ages of the models. |

### getPersonsInImage() {#getPersonsInImage--}
```
public final String[] getPersonsInImage()
```


Gets names of the persons the content of the item is about.

**Returns:**
java.lang.String[] - Names of the persons that are shown in the image.
### setPersonsInImage(String[] value) {#setPersonsInImage-java.lang.String---}
```
public final void setPersonsInImage(String[] value)
```


Sets names of the persons the content of the item is about.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | Names of the persons that are shown in the image. |

### getDigitalImageGuid() {#getDigitalImageGuid--}
```
public final String getDigitalImageGuid()
```


Gets the globally unique identifier for this digital image.

**Returns:**
java.lang.String - The image GUID.

--------------------

It is created and applied by the creator of the digital image at the time of its creation. This value shall not be changed after that time.
### setDigitalImageGuid(String value) {#setDigitalImageGuid-java.lang.String-}
```
public final void setDigitalImageGuid(String value)
```


Sets the globally unique identifier for this digital image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The image GUID.

--------------------

It is created and applied by the creator of the digital image at the time of its creation. This value shall not be changed after that time. |

### getDigitalSourceType() {#getDigitalSourceType--}
```
public final String getDigitalSourceType()
```


Gets the type of the source of this digital image.

**Returns:**
java.lang.String - The type of the source digital file.
### setDigitalSourceType(String value) {#setDigitalSourceType-java.lang.String-}
```
public final void setDigitalSourceType(String value)
```


Sets the type of the source of this digital image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The type of the source digital file. |

### getEvent() {#getEvent--}
```
public final XmpLangAlt getEvent()
```


Gets the description of the specific event at which the photo was taken.

**Returns:**
[XmpLangAlt](../../com.groupdocs.metadata.core/xmplangalt) - The specific event at which the photo was taken.
### setEvent(XmpLangAlt value) {#setEvent-com.groupdocs.metadata.core.XmpLangAlt-}
```
public final void setEvent(XmpLangAlt value)
```


Sets the description of the specific event at which the photo was taken.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpLangAlt](../../com.groupdocs.metadata.core/xmplangalt) | The specific event at which the photo was taken. |

### getIptcLastEdited() {#getIptcLastEdited--}
```
public final Date getIptcLastEdited()
```


Gets the date and optionally time when any of the IPTC photo metadata fields has been last edited.

**Returns:**
java.util.Date - The last edited date.
### setIptcLastEdited(Date value) {#setIptcLastEdited-java.util.Date-}
```
public final void setIptcLastEdited(Date value)
```


Sets the date and optionally time when any of the IPTC photo metadata fields has been last edited.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The last edited date. |

### getMaxAvailableHeight() {#getMaxAvailableHeight--}
```
public final Integer getMaxAvailableHeight()
```


Gets the maximum available height in pixels of the original photo from which this photo has been derived by downsizing.

**Returns:**
java.lang.Integer - The maximum available height.
### setMaxAvailableHeight(Integer value) {#setMaxAvailableHeight-java.lang.Integer-}
```
public final void setMaxAvailableHeight(Integer value)
```


Sets the maximum available height in pixels of the original photo from which this photo has been derived by downsizing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The maximum available height. |

### getMaxAvailableWidth() {#getMaxAvailableWidth--}
```
public final Integer getMaxAvailableWidth()
```


Gets the the maximum available width in pixels of the original photo from which this photo has been derived by downsizing.

**Returns:**
java.lang.Integer - The maximum available width.
### setMaxAvailableWidth(Integer value) {#setMaxAvailableWidth-java.lang.Integer-}
```
public final void setMaxAvailableWidth(Integer value)
```


Sets the the maximum available width in pixels of the original photo from which this photo has been derived by downsizing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The maximum available width. |

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

### set(String name, XmpArray value) {#set-java.lang.String-com.groupdocs.metadata.core.XmpArray-}
```
public void set(String name, XmpArray value)
```


Sets the value inherited from  XmpArray  .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XMP metadata property name. |
| value | [XmpArray](../../com.groupdocs.metadata.core/xmparray) | XMP metadata property value. |

