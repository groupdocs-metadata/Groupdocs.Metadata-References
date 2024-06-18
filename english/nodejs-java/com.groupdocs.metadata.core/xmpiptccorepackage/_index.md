---
title: XmpIptcCorePackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents the IPTC Core XMP package.
type: docs
weight: 320
url: /nodejs-java/com.groupdocs.metadata.core/xmpiptccorepackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpPackage](../../com.groupdocs.metadata.core/xmppackage)
```
public final class XmpIptcCorePackage extends XmpPackage
```

Represents the IPTC Core XMP package.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpIptcCorePackage()](#XmpIptcCorePackage--) | Initializes a new instance of the  XmpIptcCorePackage  class. |
## Methods

| Method | Description |
| --- | --- |
| [getCountryCode()](#getCountryCode--) | Gets the code of the country the content is focusing on. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Sets the code of the country the content is focusing on. |
| [getIntellectualGenre()](#getIntellectualGenre--) | Gets the intellectual genre. |
| [setIntellectualGenre(String value)](#setIntellectualGenre-java.lang.String-) | Sets the intellectual genre. |
| [getLocation()](#getLocation--) | Gets the location the content is focusing on. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Sets the location the content is focusing on. |
| [getScenes()](#getScenes--) | Gets the scene of the photo content. |
| [setScenes(String[] value)](#setScenes-java.lang.String---) | Sets the scene of the photo content. |
| [getSubjectCodes()](#getSubjectCodes--) | Gets one or more Subjects from the IPTC "Subject-NewsCodes" taxonomy to categorize the content.Each Subject is represented as a string of 8 digits in an unordered list. |
| [setSubjectCodes(String[] value)](#setSubjectCodes-java.lang.String---) | Sets one or more Subjects from the IPTC "Subject-NewsCodes" taxonomy to categorize the content.Each Subject is represented as a string of 8 digits in an unordered list. |
### XmpIptcCorePackage() {#XmpIptcCorePackage--}
```
public XmpIptcCorePackage()
```


Initializes a new instance of the  XmpIptcCorePackage  class.

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


Gets the code of the country the content is focusing on. The code should be taken from ISO 3166 two or three letter code.

**Returns:**
java.lang.String - The country code.
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


Sets the code of the country the content is focusing on. The code should be taken from ISO 3166 two or three letter code.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The country code. |

### getIntellectualGenre() {#getIntellectualGenre--}
```
public final String getIntellectualGenre()
```


Gets the intellectual genre. Describes the nature, intellectual, artistic or journalistic characteristic of a news object, not specifically its content.

**Returns:**
java.lang.String - The intellectual genre.
### setIntellectualGenre(String value) {#setIntellectualGenre-java.lang.String-}
```
public final void setIntellectualGenre(String value)
```


Sets the intellectual genre. Describes the nature, intellectual, artistic or journalistic characteristic of a news object, not specifically its content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The intellectual genre. |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Gets the location the content is focusing on.

**Returns:**
java.lang.String - The location.

--------------------

This location name could either be the name of a sublocation to a city or the name of a well known location or (natural) monument outside a city. In the sense of a sublocation to a city this element is at the fourth level of a top-down geographical hierarchy.
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Sets the location the content is focusing on.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The location.

--------------------

This location name could either be the name of a sublocation to a city or the name of a well known location or (natural) monument outside a city. In the sense of a sublocation to a city this element is at the fourth level of a top-down geographical hierarchy. |

### getScenes() {#getScenes--}
```
public final String[] getScenes()
```


Gets the scene of the photo content.

**Returns:**
java.lang.String[] - The scene codes.

--------------------

Specifies one or more terms from the IPTC "Scene-NewsCodes". Each Scene is represented as a string of 6 digits in an unordered list
### setScenes(String[] value) {#setScenes-java.lang.String---}
```
public final void setScenes(String[] value)
```


Sets the scene of the photo content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The scene codes.

--------------------

Specifies one or more terms from the IPTC "Scene-NewsCodes". Each Scene is represented as a string of 6 digits in an unordered list |

### getSubjectCodes() {#getSubjectCodes--}
```
public final String[] getSubjectCodes()
```


Gets one or more Subjects from the IPTC "Subject-NewsCodes" taxonomy to categorize the content.Each Subject is represented as a string of 8 digits in an unordered list.

**Returns:**
java.lang.String[] - The subject codes.

--------------------

More about IPTC Subject-NewsCodes at http://www.newscodes.org.
### setSubjectCodes(String[] value) {#setSubjectCodes-java.lang.String---}
```
public final void setSubjectCodes(String[] value)
```


Sets one or more Subjects from the IPTC "Subject-NewsCodes" taxonomy to categorize the content.Each Subject is represented as a string of 8 digits in an unordered list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The subject codes.

--------------------

More about IPTC Subject-NewsCodes at http://www.newscodes.org. |

