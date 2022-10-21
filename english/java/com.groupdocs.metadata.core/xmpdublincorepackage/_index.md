---
title: XmpDublinCorePackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the Dublin Core scheme.
type: docs
weight: 264
url: /java/com.groupdocs.metadata.core/xmpdublincorepackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpPackage](../../com.groupdocs.metadata.core/xmppackage)
```
public final class XmpDublinCorePackage extends XmpPackage
```

Represents the Dublin Core scheme.

--------------------

For more information see: http://dublincore.org/documents/usageguide/elements.shtml.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpDublinCorePackage()](#XmpDublinCorePackage--) | Initializes a new instance of the  XmpDublinCorePackage  class. |
## Methods

| Method | Description |
| --- | --- |
| [getContributors()](#getContributors--) | Gets an array of the contributors. |
| [setContributors(String[] value)](#setContributors-java.lang.String---) | Sets an array of the contributors. |
| [getCoverage()](#getCoverage--) | Gets the extent or scope of the resource. |
| [setCoverage(String value)](#setCoverage-java.lang.String-) | Sets the extent or scope of the resource. |
| [getCreators()](#getCreators--) | Gets an array of the creators. |
| [setCreators(String[] value)](#setCreators-java.lang.String---) | Sets an array of the creators. |
| [getDates()](#getDates--) | Gets an array of dates associated with an event in the life cycle of the resource. |
| [setDates(Date[] value)](#setDates-java.util.Date---) | Sets an array of dates associated with an event in the life cycle of the resource. |
| [getDescriptions()](#getDescriptions--) | Gets an array of textual descriptions of the content of the resource, given in various languages. |
| [setDescriptions(XmpLangAlt value)](#setDescriptions-com.groupdocs.metadata.core.XmpLangAlt-) | Sets an array of textual descriptions of the content of the resource, given in various languages. |
| [getFormat()](#getFormat--) | Gets the MIME type of the resource. |
| [setFormat(String value)](#setFormat-java.lang.String-) | Sets the MIME type of the resource. |
| [getIdentifier()](#getIdentifier--) | Gets a string value representing an unambiguous reference to the resource within a given context. |
| [setIdentifier(String value)](#setIdentifier-java.lang.String-) | Sets a string value representing an unambiguous reference to the resource within a given context. |
| [getLanguages()](#getLanguages--) | Gets an array of languages used in the content of the resource. |
| [setLanguages(String[] value)](#setLanguages-java.lang.String---) | Sets an array of languages used in the content of the resource. |
| [getPublishers()](#getPublishers--) | Gets an array of publishers made the resource available. |
| [setPublishers(String[] value)](#setPublishers-java.lang.String---) | Sets an array of publishers made the resource available. |
| [getRelations()](#getRelations--) | Gets an array of the related resources. |
| [setRelations(String[] value)](#setRelations-java.lang.String---) | Sets an array of the related resources. |
| [getRights()](#getRights--) | Gets an array of the informal rights statements, given in various languages. |
| [setRights(XmpLangAlt value)](#setRights-com.groupdocs.metadata.core.XmpLangAlt-) | Sets an array of the informal rights statements, given in various languages. |
| [getSource()](#getSource--) | Gets the related resource from which the described resource is derived. |
| [setSource(String value)](#setSource-java.lang.String-) | Sets the related resource from which the described resource is derived. |
| [getSubjects()](#getSubjects--) | Gets an array of descriptive phrases or keywords that specify the content of the resource. |
| [setSubjects(String[] value)](#setSubjects-java.lang.String---) | Sets an array of descriptive phrases or keywords that specify the content of the resource. |
| [getTitles()](#getTitles--) | Gets the title or name of the resource, given in various languages. |
| [setTitles(XmpLangAlt value)](#setTitles-com.groupdocs.metadata.core.XmpLangAlt-) | Sets the title or name of the resource, given in various languages. |
| [getTypes()](#getTypes--) | Gets an array of string values representing the nature or genre of the resource. |
| [setTypes(String[] value)](#setTypes-java.lang.String---) | Sets an array of string values representing the nature or genre of the resource. |
| [setContributor(String contributor)](#setContributor-java.lang.String-) | Sets a single contributor of the resource. |
| [setCreator(String creator)](#setCreator-java.lang.String-) | Sets a single creator of the resource. |
| [setDate(Date date)](#setDate-java.util.Date-) | Sets a single date associated with the resource. |
| [setDescription(String description)](#setDescription-java.lang.String-) | Sets the resource description, given in a single laguage. |
| [setLanguage(String language)](#setLanguage-java.lang.String-) | Sets a single language associated with the resource. |
| [setPublisher(String publisher)](#setPublisher-java.lang.String-) | Sets a single publisher of the resource. |
| [setRelation(String relation)](#setRelation-java.lang.String-) | Sets a single related resource. |
| [setRights(String rights)](#setRights-java.lang.String-) | Sets the resource rights, given in a single laguage. |
| [setSubject(String subject)](#setSubject-java.lang.String-) | Sets a single subject of the resource. |
| [setTitle(String title)](#setTitle-java.lang.String-) | Sets the resource title, given in a single laguage. |
| [setType(String type)](#setType-java.lang.String-) | Sets a single type of the resource. |
| [set(String name, XmpArray value)](#set-java.lang.String-com.groupdocs.metadata.core.XmpArray-) | Sets the value inherited from  XmpArray  . |
### XmpDublinCorePackage() {#XmpDublinCorePackage--}
```
public XmpDublinCorePackage()
```


Initializes a new instance of the  XmpDublinCorePackage  class.

### getContributors() {#getContributors--}
```
public final String[] getContributors()
```


Gets an array of the contributors.

**Returns:**
java.lang.String[] - An array of the contributors.

--------------------

These contributors should not include those listed in dc:creator.
### setContributors(String[] value) {#setContributors-java.lang.String---}
```
public final void setContributors(String[] value)
```


Sets an array of the contributors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | An array of the contributors.

--------------------

These contributors should not include those listed in dc:creator. |

### getCoverage() {#getCoverage--}
```
public final String getCoverage()
```


Gets the extent or scope of the resource.

**Returns:**
java.lang.String - The extent or scope of the resource.
### setCoverage(String value) {#setCoverage-java.lang.String-}
```
public final void setCoverage(String value)
```


Sets the extent or scope of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The extent or scope of the resource. |

### getCreators() {#getCreators--}
```
public final String[] getCreators()
```


Gets an array of the creators.

**Returns:**
java.lang.String[] - An array of the creators.

--------------------

Entities should be listed in order of decreasing precedence, if such order is significant. Examples of a creator include a person, an organization, or a service. Typically, the name of a creator should be used to indicate the entity.
### setCreators(String[] value) {#setCreators-java.lang.String---}
```
public final void setCreators(String[] value)
```


Sets an array of the creators.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | An array of the creators.

--------------------

Entities should be listed in order of decreasing precedence, if such order is significant. Examples of a creator include a person, an organization, or a service. Typically, the name of a creator should be used to indicate the entity. |

### getDates() {#getDates--}
```
public final Date[] getDates()
```


Gets an array of dates associated with an event in the life cycle of the resource.

**Returns:**
java.util.Date[] - A point or period of time associated with an event in the life cycle of the resource.
### setDates(Date[] value) {#setDates-java.util.Date---}
```
public final void setDates(Date[] value)
```


Sets an array of dates associated with an event in the life cycle of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date[] | A point or period of time associated with an event in the life cycle of the resource. |

### getDescriptions() {#getDescriptions--}
```
public final XmpLangAlt getDescriptions()
```


Gets an array of textual descriptions of the content of the resource, given in various languages.

**Returns:**
[XmpLangAlt](../../com.groupdocs.metadata.core/xmplangalt) - An array of textual descriptions of the content of the resource, given in various languages.
### setDescriptions(XmpLangAlt value) {#setDescriptions-com.groupdocs.metadata.core.XmpLangAlt-}
```
public final void setDescriptions(XmpLangAlt value)
```


Sets an array of textual descriptions of the content of the resource, given in various languages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpLangAlt](../../com.groupdocs.metadata.core/xmplangalt) | An array of textual descriptions of the content of the resource, given in various languages. |

### getFormat() {#getFormat--}
```
public final String getFormat()
```


Gets the MIME type of the resource.

**Returns:**
java.lang.String - The MIME type of the resource.
### setFormat(String value) {#setFormat-java.lang.String-}
```
public final void setFormat(String value)
```


Sets the MIME type of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The MIME type of the resource. |

### getIdentifier() {#getIdentifier--}
```
public final String getIdentifier()
```


Gets a string value representing an unambiguous reference to the resource within a given context.

**Returns:**
java.lang.String - A string value representing an unambiguous reference to the resource within a given context.

--------------------

Recommended best practice is to identify the resource by means of a string conforming to a formal identification system.
### setIdentifier(String value) {#setIdentifier-java.lang.String-}
```
public final void setIdentifier(String value)
```


Sets a string value representing an unambiguous reference to the resource within a given context.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A string value representing an unambiguous reference to the resource within a given context.

--------------------

Recommended best practice is to identify the resource by means of a string conforming to a formal identification system. |

### getLanguages() {#getLanguages--}
```
public final String[] getLanguages()
```


Gets an array of languages used in the content of the resource.

**Returns:**
java.lang.String[] - An array of languages used in the content of the resource.
### setLanguages(String[] value) {#setLanguages-java.lang.String---}
```
public final void setLanguages(String[] value)
```


Sets an array of languages used in the content of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | An array of languages used in the content of the resource. |

### getPublishers() {#getPublishers--}
```
public final String[] getPublishers()
```


Gets an array of publishers made the resource available.

**Returns:**
java.lang.String[] - An array of publishers made the resource available.

--------------------

Examples of a publisher include a person, an organization, or a service. Typically, the name of a publisher should be used to indicate the entity.
### setPublishers(String[] value) {#setPublishers-java.lang.String---}
```
public final void setPublishers(String[] value)
```


Sets an array of publishers made the resource available.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | An array of publishers made the resource available.

--------------------

Examples of a publisher include a person, an organization, or a service. Typically, the name of a publisher should be used to indicate the entity. |

### getRelations() {#getRelations--}
```
public final String[] getRelations()
```


Gets an array of the related resources.

**Returns:**
java.lang.String[] - An array of the related resources.

--------------------

Recommended best practice is to identify the related resource by means of a string conforming to a formal identification system.
### setRelations(String[] value) {#setRelations-java.lang.String---}
```
public final void setRelations(String[] value)
```


Sets an array of the related resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | An array of the related resources.

--------------------

Recommended best practice is to identify the related resource by means of a string conforming to a formal identification system. |

### getRights() {#getRights--}
```
public final XmpLangAlt getRights()
```


Gets an array of the informal rights statements, given in various languages.

**Returns:**
[XmpLangAlt](../../com.groupdocs.metadata.core/xmplangalt) - An array of the informal rights statements, given in various languages.

--------------------

Typically, rights information includes a statement about various property rights associated with the resource, including intellectual property rights.
### setRights(XmpLangAlt value) {#setRights-com.groupdocs.metadata.core.XmpLangAlt-}
```
public final void setRights(XmpLangAlt value)
```


Sets an array of the informal rights statements, given in various languages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpLangAlt](../../com.groupdocs.metadata.core/xmplangalt) | An array of the informal rights statements, given in various languages.

--------------------

Typically, rights information includes a statement about various property rights associated with the resource, including intellectual property rights. |

### getSource() {#getSource--}
```
public final String getSource()
```


Gets the related resource from which the described resource is derived.

**Returns:**
java.lang.String - The related resource from which the described resource is derived.

--------------------

The described resource may be derived from the related resource in whole or in part. Recommended best practice is to identify the related resource by means of a string conforming to a formal identification system.
### setSource(String value) {#setSource-java.lang.String-}
```
public final void setSource(String value)
```


Sets the related resource from which the described resource is derived.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The related resource from which the described resource is derived.

--------------------

The described resource may be derived from the related resource in whole or in part. Recommended best practice is to identify the related resource by means of a string conforming to a formal identification system. |

### getSubjects() {#getSubjects--}
```
public final String[] getSubjects()
```


Gets an array of descriptive phrases or keywords that specify the content of the resource.

**Returns:**
java.lang.String[] - An array of descriptive phrases or keywords that specify the content of the resource.
### setSubjects(String[] value) {#setSubjects-java.lang.String---}
```
public final void setSubjects(String[] value)
```


Sets an array of descriptive phrases or keywords that specify the content of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | An array of descriptive phrases or keywords that specify the content of the resource. |

### getTitles() {#getTitles--}
```
public final XmpLangAlt getTitles()
```


Gets the title or name of the resource, given in various languages.

**Returns:**
[XmpLangAlt](../../com.groupdocs.metadata.core/xmplangalt) - The title or name of the resource, given in various languages.
### setTitles(XmpLangAlt value) {#setTitles-com.groupdocs.metadata.core.XmpLangAlt-}
```
public final void setTitles(XmpLangAlt value)
```


Sets the title or name of the resource, given in various languages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpLangAlt](../../com.groupdocs.metadata.core/xmplangalt) | The title or name of the resource, given in various languages. |

### getTypes() {#getTypes--}
```
public final String[] getTypes()
```


Gets an array of string values representing the nature or genre of the resource.

**Returns:**
java.lang.String[] - An array of string values representing the nature or genre of the resource.
### setTypes(String[] value) {#setTypes-java.lang.String---}
```
public final void setTypes(String[] value)
```


Sets an array of string values representing the nature or genre of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | An array of string values representing the nature or genre of the resource. |

### setContributor(String contributor) {#setContributor-java.lang.String-}
```
public final void setContributor(String contributor)
```


Sets a single contributor of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contributor | java.lang.String | The contributor to set. |

### setCreator(String creator) {#setCreator-java.lang.String-}
```
public final void setCreator(String creator)
```


Sets a single creator of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| creator | java.lang.String | The creator to set. |

### setDate(Date date) {#setDate-java.util.Date-}
```
public final void setDate(Date date)
```


Sets a single date associated with the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| date | java.util.Date | The date to set. |

### setDescription(String description) {#setDescription-java.lang.String-}
```
public final void setDescription(String description)
```


Sets the resource description, given in a single laguage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| description | java.lang.String | The description to set. |

### setLanguage(String language) {#setLanguage-java.lang.String-}
```
public final void setLanguage(String language)
```


Sets a single language associated with the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| language | java.lang.String | The language to set. |

### setPublisher(String publisher) {#setPublisher-java.lang.String-}
```
public final void setPublisher(String publisher)
```


Sets a single publisher of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| publisher | java.lang.String | The publisher to set. |

### setRelation(String relation) {#setRelation-java.lang.String-}
```
public final void setRelation(String relation)
```


Sets a single related resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | java.lang.String | The relation to set. |

### setRights(String rights) {#setRights-java.lang.String-}
```
public final void setRights(String rights)
```


Sets the resource rights, given in a single laguage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rights | java.lang.String | The rights statements to set. |

### setSubject(String subject) {#setSubject-java.lang.String-}
```
public final void setSubject(String subject)
```


Sets a single subject of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subject | java.lang.String | The subject to set. |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public final void setTitle(String title)
```


Sets the resource title, given in a single laguage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| title | java.lang.String | The title to set. |

### setType(String type) {#setType-java.lang.String-}
```
public final void setType(String type)
```


Sets a single type of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | java.lang.String | The type to set. |

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

