---
title: XmpLangAlt
second_title: GroupDocs.Metadata for Java API Reference
description: 
type: docs
weight: 315
url: /java/com.groupdocs.metadata.core/xmplangalt/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.PropertyValue](../../com.groupdocs.metadata.core/propertyvalue), [com.groupdocs.metadata.core.XmpValueBase](../../com.groupdocs.metadata.core/xmpvaluebase), [com.groupdocs.metadata.core.XmpArray](../../com.groupdocs.metadata.core/xmparray)
```
public final class XmpLangAlt extends XmpArray
```

Represents XMP Language Alternative. 



--------------------

An alternative array of simple text items. Language alternatives facilitate the selection of a simple text item based on a desired language. Each array item shall have an xml:lang qualifier. Each xml:lang value shall be unique among the items.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpLangAlt(String defaultValue)](#XmpLangAlt-java.lang.String-) | Initializes a new instance of the  XmpLangAlt  class. |
| [XmpLangAlt(Hashtable<String,String> dictionary)](#XmpLangAlt-java.util.Hashtable-java.lang.String-java.lang.String--) | Initializes a new instance of the  XmpLangAlt  class. |
## Methods

| Method | Description |
| --- | --- |
| [get_Item(String language)](#get-Item-java.lang.String-) | Gets the value associated with the specified language. |
| [getLanguages()](#getLanguages--) | Gets an array of all languages registered in the instance of  XmpLangAlt . |
| [contains(String language)](#contains-java.lang.String-) | Determines whether the  XmpLangAlt  contains the specified language. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Converts XMP value to the xml representation. |
### XmpLangAlt(String defaultValue) {#XmpLangAlt-java.lang.String-}
```
public XmpLangAlt(String defaultValue)
```


Initializes a new instance of the  XmpLangAlt  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| defaultValue | java.lang.String | The default value. |

### XmpLangAlt(Hashtable<String,String> dictionary) {#XmpLangAlt-java.util.Hashtable-java.lang.String-java.lang.String--}
```
public XmpLangAlt(Hashtable<String,String> dictionary)
```


Initializes a new instance of the  XmpLangAlt  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dictionary | java.util.Hashtable<java.lang.String,java.lang.String> | A dictionary containing values by languages. |

### get_Item(String language) {#get-Item-java.lang.String-}
```
public final String get_Item(String language)
```


Gets the value associated with the specified language.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| language | java.lang.String | The language. Value: String value. |

**Returns:**
java.lang.String - Value for the specified language.
### getLanguages() {#getLanguages--}
```
public final String[] getLanguages()
```


Gets an array of all languages registered in the instance of  XmpLangAlt .

**Returns:**
java.lang.String[] - An array of all languages registered in the instance of  XmpLangAlt .
### contains(String language) {#contains-java.lang.String-}
```
public final boolean contains(String language)
```


Determines whether the  XmpLangAlt  contains the specified language.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| language | java.lang.String | The language to locate in the  XmpLangAlt . |

**Returns:**
boolean - True if the  XmpLangAlt  contains an element with the specified language; otherwise, false.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Converts XMP value to the xml representation.

**Returns:**
java.lang.String - Returns  string  representation of XMP value.
