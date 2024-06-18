---
title: XmpPhotoshopPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents Adobe Photoshop namespace.
type: docs
weight: 333
url: /nodejs-java/com.groupdocs.metadata.core/xmpphotoshoppackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpPackage](../../com.groupdocs.metadata.core/xmppackage)
```
public final class XmpPhotoshopPackage extends XmpPackage
```

Represents Adobe Photoshop namespace.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpPhotoshopPackage()](#XmpPhotoshopPackage--) | Initializes a new instance of the  XmpPhotoshopPackage  class. |
## Fields

| Field | Description |
| --- | --- |
| [UrgencyMax](#UrgencyMax) | Urgency max value. |
| [UrgencyMin](#UrgencyMin) | Urgency min value. |
## Methods

| Method | Description |
| --- | --- |
| [getAuthorsPosition()](#getAuthorsPosition--) | Gets the by-line title. |
| [setAuthorsPosition(String value)](#setAuthorsPosition-java.lang.String-) | Sets the by-line title. |
| [getCaptionWriter()](#getCaptionWriter--) | Gets the writer/editor. |
| [setCaptionWriter(String value)](#setCaptionWriter-java.lang.String-) | Sets the writer/editor. |
| [getCategory()](#getCategory--) | Gets the category. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Sets the category. |
| [getCity()](#getCity--) | Gets the city. |
| [setCity(String value)](#setCity-java.lang.String-) | Sets the city. |
| [getColorMode()](#getColorMode--) | Gets the color mode. |
| [setColorMode(XmpPhotoshopColorMode value)](#setColorMode-com.groupdocs.metadata.core.XmpPhotoshopColorMode-) | Sets the color mode. |
| [getCountry()](#getCountry--) | Gets the country. |
| [setCountry(String value)](#setCountry-java.lang.String-) | Sets the country. |
| [getCredit()](#getCredit--) | Gets the credit. |
| [setCredit(String value)](#setCredit-java.lang.String-) | Sets the credit. |
| [getDateCreated()](#getDateCreated--) | Gets the date the intellectual content of the document was created. |
| [setDateCreated(Date value)](#setDateCreated-java.util.Date-) | Sets the date the intellectual content of the document was created. |
| [getHeadline()](#getHeadline--) | Gets the headline. |
| [setHeadline(String value)](#setHeadline-java.lang.String-) | Sets the headline. |
| [getHistory()](#getHistory--) | Gets the history that appears in the FileInfo panel, if activated in the application preferences. |
| [setHistory(String value)](#setHistory-java.lang.String-) | Sets the history that appears in the FileInfo panel, if activated in the application preferences. |
| [getIccProfile()](#getIccProfile--) | Gets the color profile, such as AppleRGB, AdobeRGB1998. |
| [setIccProfile(String value)](#setIccProfile-java.lang.String-) | Sets the color profile, such as AppleRGB, AdobeRGB1998. |
| [getInstructions()](#getInstructions--) | Gets the special instructions. |
| [setInstructions(String value)](#setInstructions-java.lang.String-) | Sets the special instructions. |
| [getSource()](#getSource--) | Gets the source. |
| [setSource(String value)](#setSource-java.lang.String-) | Sets the source. |
| [getState()](#getState--) | Gets the province/state. |
| [setState(String value)](#setState-java.lang.String-) | Sets the province/state. |
| [getSupplementalCategories()](#getSupplementalCategories--) | Gets the supplemental categories. |
| [setSupplementalCategories(String[] value)](#setSupplementalCategories-java.lang.String---) | Sets the supplemental categories. |
| [getTransmissionReference()](#getTransmissionReference--) | Gets the original transmission reference. |
| [setTransmissionReference(String value)](#setTransmissionReference-java.lang.String-) | Sets the original transmission reference. |
| [getUrgency()](#getUrgency--) | Gets the urgency. |
| [setUrgency(Integer value)](#setUrgency-java.lang.Integer-) | Sets the urgency. |
| [set(String name, String value)](#set-java.lang.String-java.lang.String-) | Sets string property. |
### XmpPhotoshopPackage() {#XmpPhotoshopPackage--}
```
public XmpPhotoshopPackage()
```


Initializes a new instance of the  XmpPhotoshopPackage  class.

### UrgencyMax {#UrgencyMax}
```
public static final int UrgencyMax
```


Urgency max value.

### UrgencyMin {#UrgencyMin}
```
public static final int UrgencyMin
```


Urgency min value.

### getAuthorsPosition() {#getAuthorsPosition--}
```
public final String getAuthorsPosition()
```


Gets the by-line title.

**Returns:**
java.lang.String - The authors position.
### setAuthorsPosition(String value) {#setAuthorsPosition-java.lang.String-}
```
public final void setAuthorsPosition(String value)
```


Sets the by-line title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The authors position. |

### getCaptionWriter() {#getCaptionWriter--}
```
public final String getCaptionWriter()
```


Gets the writer/editor.

**Returns:**
java.lang.String - The caption writer.
### setCaptionWriter(String value) {#setCaptionWriter-java.lang.String-}
```
public final void setCaptionWriter(String value)
```


Sets the writer/editor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The caption writer. |

### getCategory() {#getCategory--}
```
public final String getCategory()
```


Gets the category. Limited to 3 7-bit ASCII characters.

**Returns:**
java.lang.String - The category. Limited to 3 ASCII characters.
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```


Sets the category. Limited to 3 7-bit ASCII characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The category. Limited to 3 ASCII characters. |

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

### getColorMode() {#getColorMode--}
```
public final XmpPhotoshopColorMode getColorMode()
```


Gets the color mode.

**Returns:**
[XmpPhotoshopColorMode](../../com.groupdocs.metadata.core/xmpphotoshopcolormode) - The color mode.
### setColorMode(XmpPhotoshopColorMode value) {#setColorMode-com.groupdocs.metadata.core.XmpPhotoshopColorMode-}
```
public final void setColorMode(XmpPhotoshopColorMode value)
```


Sets the color mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPhotoshopColorMode](../../com.groupdocs.metadata.core/xmpphotoshopcolormode) | The color mode. |

### getCountry() {#getCountry--}
```
public final String getCountry()
```


Gets the country.

**Returns:**
java.lang.String - The country.
### setCountry(String value) {#setCountry-java.lang.String-}
```
public final void setCountry(String value)
```


Sets the country.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The country. |

### getCredit() {#getCredit--}
```
public final String getCredit()
```


Gets the credit.

**Returns:**
java.lang.String - The credit.
### setCredit(String value) {#setCredit-java.lang.String-}
```
public final void setCredit(String value)
```


Sets the credit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The credit. |

### getDateCreated() {#getDateCreated--}
```
public final Date getDateCreated()
```


Gets the date the intellectual content of the document was created.

**Returns:**
java.util.Date - The created date of the document.
### setDateCreated(Date value) {#setDateCreated-java.util.Date-}
```
public final void setDateCreated(Date value)
```


Sets the date the intellectual content of the document was created.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The created date of the document. |

### getHeadline() {#getHeadline--}
```
public final String getHeadline()
```


Gets the headline.

**Returns:**
java.lang.String - The headline.
### setHeadline(String value) {#setHeadline-java.lang.String-}
```
public final void setHeadline(String value)
```


Sets the headline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The headline. |

### getHistory() {#getHistory--}
```
public final String getHistory()
```


Gets the history that appears in the FileInfo panel, if activated in the application preferences.

**Returns:**
java.lang.String - The history.
### setHistory(String value) {#setHistory-java.lang.String-}
```
public final void setHistory(String value)
```


Sets the history that appears in the FileInfo panel, if activated in the application preferences.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The history. |

### getIccProfile() {#getIccProfile--}
```
public final String getIccProfile()
```


Gets the color profile, such as AppleRGB, AdobeRGB1998.

**Returns:**
java.lang.String - The ICC profile.
### setIccProfile(String value) {#setIccProfile-java.lang.String-}
```
public final void setIccProfile(String value)
```


Sets the color profile, such as AppleRGB, AdobeRGB1998.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The ICC profile. |

### getInstructions() {#getInstructions--}
```
public final String getInstructions()
```


Gets the special instructions.

**Returns:**
java.lang.String - The special instructions.
### setInstructions(String value) {#setInstructions-java.lang.String-}
```
public final void setInstructions(String value)
```


Sets the special instructions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The special instructions. |

### getSource() {#getSource--}
```
public final String getSource()
```


Gets the source.

**Returns:**
java.lang.String - The source.
### setSource(String value) {#setSource-java.lang.String-}
```
public final void setSource(String value)
```


Sets the source.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The source. |

### getState() {#getState--}
```
public final String getState()
```


Gets the province/state.

**Returns:**
java.lang.String - The province/state.
### setState(String value) {#setState-java.lang.String-}
```
public final void setState(String value)
```


Sets the province/state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The province/state. |

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

### getTransmissionReference() {#getTransmissionReference--}
```
public final String getTransmissionReference()
```


Gets the original transmission reference.

**Returns:**
java.lang.String - The transmission reference.
### setTransmissionReference(String value) {#setTransmissionReference-java.lang.String-}
```
public final void setTransmissionReference(String value)
```


Sets the original transmission reference.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The transmission reference. |

### getUrgency() {#getUrgency--}
```
public final Integer getUrgency()
```


Gets the urgency.

**Returns:**
java.lang.Integer - The urgency.

--------------------

Valid range is 1-8.
### setUrgency(Integer value) {#setUrgency-java.lang.Integer-}
```
public final void setUrgency(Integer value)
```


Sets the urgency.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The urgency.

--------------------

Valid range is 1-8. |

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

