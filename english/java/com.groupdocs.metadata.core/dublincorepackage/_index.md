---
title: DublinCorePackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a Dublin Core metadata package.
type: docs
weight: 54
url: /java/com.groupdocs.metadata.core/dublincorepackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class DublinCorePackage extends CustomPackage
```

Represents a Dublin Core metadata package.
## Methods

| Method | Description |
| --- | --- |
| [getContributor()](#getContributor--) | Gets the contributor Dublin Core element. |
| [getCoverage()](#getCoverage--) | Gets the coverage Dublin Core element. |
| [getCreator()](#getCreator--) | Gets the creator Dublin Core element. |
| [getDate()](#getDate--) | Gets the date Dublin Core element. |
| [getDescription()](#getDescription--) | Gets the description Dublin Core element. |
| [getFormat()](#getFormat--) | Gets the format Dublin Core element. |
| [getLanguage()](#getLanguage--) | Gets the language Dublin Core element. |
| [getPublisher()](#getPublisher--) | Gets the publisher Dublin Core element. |
| [getRelation()](#getRelation--) | Gets the relation Dublin Core element. |
| [getSource()](#getSource--) | Gets the source Dublin Core element. |
| [getSubject()](#getSubject--) | Gets the subject Dublin Core element. |
| [getTitle()](#getTitle--) | Gets the title Dublin Core element. |
| [getType()](#getType--) | Gets the type Dublin Core element. |
| [getRights()](#getRights--) | Gets the rights Dublin Core element. |
| [getIdentifier()](#getIdentifier--) | Gets the identifier Dublin Core element. |
### getContributor() {#getContributor--}
```
public final String getContributor()
```


Gets the contributor Dublin Core element.

**Returns:**
java.lang.String - An entity responsible for making contributions to the content of the resource. Examples of a Contributor include a person, an organization or a service.
### getCoverage() {#getCoverage--}
```
public final String getCoverage()
```


Gets the coverage Dublin Core element.

**Returns:**
java.lang.String - The extent or scope of the content of the resource. Coverage will typically include spatial location (a place name or geographic co-ordinates), temporal period (a period label, date, or date range) or jurisdiction (such as a named administrative entity).
### getCreator() {#getCreator--}
```
public final String getCreator()
```


Gets the creator Dublin Core element.

**Returns:**
java.lang.String - An entity primarily responsible for making the content of the resource. Examples of a Creator include a person, an organization, or a service.
### getDate() {#getDate--}
```
public final String getDate()
```


Gets the date Dublin Core element.

**Returns:**
java.lang.String - A date associated with an event in the life cycle of the resource. Typically, Date will be associated with the creation or availability of the resource. Recommended best practice for encoding the date value is defined in a profile of ISO 8601 and follows the YYYY-MM-DD format.
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Gets the description Dublin Core element.

**Returns:**
java.lang.String - An account of the content of the resource. Description may include but is not limited to: an abstract, table of contents, reference to a graphical representation of content or a free-text account of the content.
### getFormat() {#getFormat--}
```
public final String getFormat()
```


Gets the format Dublin Core element.

**Returns:**
java.lang.String - The physical or digital manifestation of the resource. Typically, Format may include the media-type or dimensions of the resource. Examples of dimensions include size and duration. Format may be used to determine the software, hardware or other equipment needed to display or operate the resource.
### getLanguage() {#getLanguage--}
```
public final String getLanguage()
```


Gets the language Dublin Core element.

**Returns:**
java.lang.String - A language of the intellectual content of the resource. Recommended best practice for the values of the Language element is defined by RFC 3066 which, in conjunction with ISO 639), defines two- and three-letter primary language tags with optional subtags.
### getPublisher() {#getPublisher--}
```
public final String getPublisher()
```


Gets the publisher Dublin Core element.

**Returns:**
java.lang.String - The entity responsible for making the resource available. Examples of a Publisher include a person, an organization, or a service. Typically, the name of a Publisher should be used to indicate the entity.
### getRelation() {#getRelation--}
```
public final String getRelation()
```


Gets the relation Dublin Core element.

**Returns:**
java.lang.String - A reference to a related resource. Recommended best practice is to reference the resource by means of a string or number conforming to a formal identification system.
### getSource() {#getSource--}
```
public final String getSource()
```


Gets the source Dublin Core element.

**Returns:**
java.lang.String - A Reference to a resource from which the present resource is derived. The present resource may be derived from the Source resource in whole or part. Recommended best practice is to reference the resource by means of a string or number conforming to a formal identification system.
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the subject Dublin Core element.

**Returns:**
java.lang.String - The topic of the content of the resource. Typically, a Subject will be expressed as keywords or key phrases or classification codes that describe the topic of the resource. Recommended best practice is to select a value from a controlled vocabulary or formal classification scheme.
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gets the title Dublin Core element.

**Returns:**
java.lang.String - The name given to the resource. Typically, a Title will be a name by which the resource is formally known.
### getType() {#getType--}
```
public final String getType()
```


Gets the type Dublin Core element.

**Returns:**
java.lang.String - The nature or genre of the content of the resource. Type includes terms describing general categories, functions, genres, or aggregation levels for content. Recommended best practice is to select a value from a controlled vocabulary (for example, the DCMIType vocabulary).
### getRights() {#getRights--}
```
public final String getRights()
```


Gets the rights Dublin Core element.

**Returns:**
java.lang.String - Information about rights held in and over the resource. Typically a Rights element will contain a rights management statement for the resource, or reference a service providing such information. Rights information often encompasses Intellectual Property Rights (IPR), Copyright, and various Property Rights. If the rights element is absent, no assumptions can be made about the status of these and other rights with respect to the resource.
### getIdentifier() {#getIdentifier--}
```
public final String getIdentifier()
```


Gets the identifier Dublin Core element.

**Returns:**
java.lang.String - An unambiguous reference to the resource within a given context. Recommended best practice is to identify the resource by means of a string or number conforming to a formal identification system.
