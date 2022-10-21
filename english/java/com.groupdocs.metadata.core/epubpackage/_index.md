---
title: EpubPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents metadata in a EPUB e-book.
type: docs
weight: 63
url: /java/com.groupdocs.metadata.core/epubpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class EpubPackage extends CustomPackage
```

Represents metadata in a EPUB e-book.

**Learn more**

 *  [Working with metadata in EPUB E-Books][]


[Working with metadata in EPUB E-Books]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+EPUB+E-Books
## Methods

| Method | Description |
| --- | --- |
| [getImageCover()](#getImageCover--) | Gets the image cover as an array of bytes. |
| [getVersion()](#getVersion--) | Gets the EPUB version. |
| [getUniqueIdentifier()](#getUniqueIdentifier--) | Gets the package unique identifier. |
| [getAbstract()](#getAbstract--) | Gets a summary of the resource. |
| [setAbstract(String value)](#setAbstract-java.lang.String-) | Sets a summary of the resource. |
| [getAccessRights()](#getAccessRights--) | Gets the information about who access the resource or an indication of its security status. |
| [setAccessRights(String value)](#setAccessRights-java.lang.String-) | Sets the information about who access the resource or an indication of its security status. |
| [getAccrualMethod()](#getAccrualMethod--) | Gets the method by which items are added to a collection. |
| [setAccrualMethod(String value)](#setAccrualMethod-java.lang.String-) | Sets the method by which items are added to a collection. |
| [getAccrualPeriodicity()](#getAccrualPeriodicity--) | Gets the frequency with which items are added to a collection. |
| [setAccrualPeriodicity(String value)](#setAccrualPeriodicity-java.lang.String-) | Sets the frequency with which items are added to a collection. |
| [getAccrualPolicy()](#getAccrualPolicy--) | Gets the policy governing the addition of items to a collection. |
| [setAccrualPolicy(String value)](#setAccrualPolicy-java.lang.String-) | Sets the policy governing the addition of items to a collection. |
| [getAlternative()](#getAlternative--) | Gets an alternative name for the resource. |
| [setAlternative(String value)](#setAlternative-java.lang.String-) | Sets an alternative name for the resource. |
| [getAudience()](#getAudience--) | Gets a class of agents for whom the resource is intended or useful. |
| [setAudience(String value)](#setAudience-java.lang.String-) | Sets a class of agents for whom the resource is intended or useful. |
| [getAvailable()](#getAvailable--) | Gets the date that the resource became or will become available. |
| [setAvailable(String value)](#setAvailable-java.lang.String-) | Sets the date that the resource became or will become available. |
| [getBibliographicCitation()](#getBibliographicCitation--) | Gets a bibliographic reference for the resource. |
| [setBibliographicCitation(String value)](#setBibliographicCitation-java.lang.String-) | Sets a bibliographic reference for the resource. |
| [getConformsTo()](#getConformsTo--) | Gets an established standard to which the described resource conforms. |
| [setConformsTo(String value)](#setConformsTo-java.lang.String-) | Sets an established standard to which the described resource conforms. |
| [getContributor()](#getContributor--) | Gets an entity responsible for making contributions to the resource. |
| [setContributor(String value)](#setContributor-java.lang.String-) | Sets an entity responsible for making contributions to the resource. |
| [getCoverage()](#getCoverage--) | Gets the spatial or temporal topic of the resource, spatial applicability of the resource, or jurisdiction under which the resource is relevant. |
| [setCoverage(String value)](#setCoverage-java.lang.String-) | Sets the spatial or temporal topic of the resource, spatial applicability of the resource, or jurisdiction under which the resource is relevant. |
| [getCreated()](#getCreated--) | Gets the date of creation of the resource. |
| [setCreated(String value)](#setCreated-java.lang.String-) | Sets the date of creation of the resource. |
| [getCreator()](#getCreator--) | Gets an entity responsible for making the resource. |
| [setCreator(String value)](#setCreator-java.lang.String-) | Sets an entity responsible for making the resource. |
| [getDate()](#getDate--) | Gets a point or period of time associated with an event in the lifecycle of the resource. |
| [setDate(String value)](#setDate-java.lang.String-) | Sets a point or period of time associated with an event in the lifecycle of the resource. |
| [getDateAccepted()](#getDateAccepted--) | Gets the date of acceptance of the resource. |
| [setDateAccepted(String value)](#setDateAccepted-java.lang.String-) | Sets the date of acceptance of the resource. |
| [getDateCopyrighted()](#getDateCopyrighted--) | Gets the date of copyright of the resource. |
| [setDateCopyrighted(String value)](#setDateCopyrighted-java.lang.String-) | Sets the date of copyright of the resource. |
| [getDateSubmitted()](#getDateSubmitted--) | Gets the date of submission of the resource. |
| [setDateSubmitted(String value)](#setDateSubmitted-java.lang.String-) | Sets the date of submission of the resource. |
| [getDescription()](#getDescription--) | Gets an account of the resource. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Sets an account of the resource. |
| [getEducationLevel()](#getEducationLevel--) | Gets a class of agents, defined in terms of progression through an educational or training context, for which the described resource is intended. |
| [setEducationLevel(String value)](#setEducationLevel-java.lang.String-) | Sets a class of agents, defined in terms of progression through an educational or training context, for which the described resource is intended. |
| [getExtent()](#getExtent--) | Gets the size or duration of the resource. |
| [setExtent(String value)](#setExtent-java.lang.String-) | Sets the size or duration of the resource. |
| [getFormat()](#getFormat--) | Gets the file format, physical medium, or dimensions of the resource. |
| [setFormat(String value)](#setFormat-java.lang.String-) | Sets the file format, physical medium, or dimensions of the resource. |
| [hasFormat()](#hasFormat--) | Gets or sets a related resource that is substantially the same as the pre-existing described resource, but in another format. |
| [setHasFormat(String value)](#setHasFormat-java.lang.String-) | Sets a related resource that is substantially the same as the pre-existing described resource, but in another format. |
| [hasPart()](#hasPart--) | Gets or sets a related resource that is included either physically or logically in the described resource. |
| [setPart(String value)](#setPart-java.lang.String-) | Sets a related resource that is included either physically or logically in the described resource. |
| [hasVersion()](#hasVersion--) | Gets or sets a related resource that is a version, edition, or adaptation of the described resource. |
| [setHasVersion(String value)](#setHasVersion-java.lang.String-) | Sets a related resource that is a version, edition, or adaptation of the described resource. |
| [getIdentifier()](#getIdentifier--) | Gets an unambiguous reference to the resource within a given context. |
| [setIdentifier(String value)](#setIdentifier-java.lang.String-) | Sets an unambiguous reference to the resource within a given context. |
| [getInstructionalMethod()](#getInstructionalMethod--) | Gets a process, used to engender knowledge, attitudes and skills, that the described resource is designed to support. |
| [setInstructionalMethod(String value)](#setInstructionalMethod-java.lang.String-) | Sets a process, used to engender knowledge, attitudes and skills, that the described resource is designed to support. |
| [isFormatOf()](#isFormatOf--) | Gets a pre-existing related resource that is substantially the same as the described resource, but in another format. |
| [setFormatOf(String value)](#setFormatOf-java.lang.String-) | Sets a pre-existing related resource that is substantially the same as the described resource, but in another format. |
| [isPartOf()](#isPartOf--) | Gets a related resource in which the described resource is physically or logically included. |
| [setPartOf(String value)](#setPartOf-java.lang.String-) | Sets a related resource in which the described resource is physically or logically included. |
| [isReferencedBy()](#isReferencedBy--) | Gets a related resource that references, cites, or otherwise points to the described resource. |
| [setReferencedBy(String value)](#setReferencedBy-java.lang.String-) | Sets a related resource that references, cites, or otherwise points to the described resource. |
| [isReplacedBy()](#isReplacedBy--) | Gets a related resource that supplants, displaces, or supersedes the described resource. |
| [setReplacedBy(String value)](#setReplacedBy-java.lang.String-) | Sets a related resource that supplants, displaces, or supersedes the described resource. |
| [isRequiredBy()](#isRequiredBy--) | Gets a related resource that requires the described resource to support its function, delivery, or coherence. |
| [setRequiredBy(String value)](#setRequiredBy-java.lang.String-) | Sets a related resource that requires the described resource to support its function, delivery, or coherence. |
| [getIssued()](#getIssued--) | Gets the date of formal issuance of the resource. |
| [setIssued(String value)](#setIssued-java.lang.String-) | Sets the date of formal issuance of the resource. |
| [isVersionOf()](#isVersionOf--) | Gets a related resource of which the described resource is a version, edition, or adaptation. |
| [setVersionOf(String value)](#setVersionOf-java.lang.String-) | Sets a related resource of which the described resource is a version, edition, or adaptation. |
| [getLanguage()](#getLanguage--) | Gets the language of the resource. |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | Sets the language of the resource. |
| [getLicense()](#getLicense--) | Gets a legal document giving official permission to do something with the resource. |
| [setLicense(String value)](#setLicense-java.lang.String-) | Sets a legal document giving official permission to do something with the resource. |
| [getMediator()](#getMediator--) | Gets an entity that mediates access to the resource. |
| [setMediator(String value)](#setMediator-java.lang.String-) | Sets an entity that mediates access to the resource. |
| [getMedium()](#getMedium--) | Gets the material or physical carrier of the resource. |
| [setMedium(String value)](#setMedium-java.lang.String-) | Sets the material or physical carrier of the resource. |
| [getModified()](#getModified--) | Gets the date on which the resource was changed. |
| [setModified(String value)](#setModified-java.lang.String-) | Sets the date on which the resource was changed. |
| [getProvenance()](#getProvenance--) | Gets a statement of any changes in ownership and custody of the resource since its creation that are significant for its authenticity, integrity, and interpretation. |
| [setProvenance(String value)](#setProvenance-java.lang.String-) | Sets a statement of any changes in ownership and custody of the resource since its creation that are significant for its authenticity, integrity, and interpretation. |
| [getPublisher()](#getPublisher--) | Gets an entity responsible for making the resource available. |
| [setPublisher(String value)](#setPublisher-java.lang.String-) | Sets an entity responsible for making the resource available. |
| [getReferences()](#getReferences--) | Gets a related resource that is referenced, cited, or otherwise pointed to by the described resource. |
| [setReferences(String value)](#setReferences-java.lang.String-) | Sets a related resource that is referenced, cited, or otherwise pointed to by the described resource. |
| [getRelation()](#getRelation--) | Gets a related resource. |
| [setRelation(String value)](#setRelation-java.lang.String-) | Sets a related resource. |
| [getReplaces()](#getReplaces--) | Gets a related resource that is supplanted, displaced, or superseded by the described resource. |
| [setReplaces(String value)](#setReplaces-java.lang.String-) | Sets a related resource that is supplanted, displaced, or superseded by the described resource. |
| [getRequires()](#getRequires--) | Gets a related resource that is required by the described resource to support its function, delivery, or coherence. |
| [setRequires(String value)](#setRequires-java.lang.String-) | Sets a related resource that is required by the described resource to support its function, delivery, or coherence. |
| [getRights()](#getRights--) | Gets the information about rights held in and over the resource. |
| [setRights(String value)](#setRights-java.lang.String-) | Sets the information about rights held in and over the resource. |
| [getRightsHolder()](#getRightsHolder--) | Gets a person or organization owning or managing rights over the resource. |
| [setRightsHolder(String value)](#setRightsHolder-java.lang.String-) | Sets a person or organization owning or managing rights over the resource. |
| [getSource()](#getSource--) | Gets a related resource from which the described resource is derived. |
| [setSource(String value)](#setSource-java.lang.String-) | Sets a related resource from which the described resource is derived. |
| [getSpatial()](#getSpatial--) | Gets the spatial characteristics of the resource. |
| [setSpatial(String value)](#setSpatial-java.lang.String-) | Sets the spatial characteristics of the resource. |
| [getSubject()](#getSubject--) | Gets a topic of the resource. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets a topic of the resource. |
| [getTableOfContents()](#getTableOfContents--) | Gets a list of subunits of the resource. |
| [setTableOfContents(String value)](#setTableOfContents-java.lang.String-) | Sets a list of subunits of the resource. |
| [getTemporal()](#getTemporal--) | Gets the temporal characteristics of the resource. |
| [setTemporal(String value)](#setTemporal-java.lang.String-) | Sets the temporal characteristics of the resource. |
| [getTitle()](#getTitle--) | Gets a name given to the resource. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets a name given to the resource. |
| [getType()](#getType--) | Gets the nature or genre of the resource. |
| [setType(String value)](#setType-java.lang.String-) | Sets the nature or genre of the resource. |
| [getValid()](#getValid--) | Gets the date (often a range) of validity of a resource. |
| [setValid(String value)](#setValid-java.lang.String-) | Sets the date (often a range) of validity of a resource. |
### getImageCover() {#getImageCover--}
```
public final byte[] getImageCover()
```


Gets the image cover as an array of bytes.

**Returns:**
byte[] - The image cover.
### getVersion() {#getVersion--}
```
public final String getVersion()
```


Gets the EPUB version.

**Returns:**
java.lang.String - The EPUB version.
### getUniqueIdentifier() {#getUniqueIdentifier--}
```
public final String getUniqueIdentifier()
```


Gets the package unique identifier.

**Returns:**
java.lang.String - The package unique identifier.
### getAbstract() {#getAbstract--}
```
public final String getAbstract()
```


Gets a summary of the resource.

**Returns:**
java.lang.String - A summary of the resource.
### setAbstract(String value) {#setAbstract-java.lang.String-}
```
public final void setAbstract(String value)
```


Sets a summary of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A summary of the resource. |

### getAccessRights() {#getAccessRights--}
```
public final String getAccessRights()
```


Gets the information about who access the resource or an indication of its security status.

**Returns:**
java.lang.String - The information about who access the resource or an indication of its security status.
### setAccessRights(String value) {#setAccessRights-java.lang.String-}
```
public final void setAccessRights(String value)
```


Sets the information about who access the resource or an indication of its security status.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The information about who access the resource or an indication of its security status. |

### getAccrualMethod() {#getAccrualMethod--}
```
public final String getAccrualMethod()
```


Gets the method by which items are added to a collection.

**Returns:**
java.lang.String - The method by which items are added to a collection.
### setAccrualMethod(String value) {#setAccrualMethod-java.lang.String-}
```
public final void setAccrualMethod(String value)
```


Sets the method by which items are added to a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The method by which items are added to a collection. |

### getAccrualPeriodicity() {#getAccrualPeriodicity--}
```
public final String getAccrualPeriodicity()
```


Gets the frequency with which items are added to a collection.

**Returns:**
java.lang.String - The frequency with which items are added to a collection.
### setAccrualPeriodicity(String value) {#setAccrualPeriodicity-java.lang.String-}
```
public final void setAccrualPeriodicity(String value)
```


Sets the frequency with which items are added to a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The frequency with which items are added to a collection. |

### getAccrualPolicy() {#getAccrualPolicy--}
```
public final String getAccrualPolicy()
```


Gets the policy governing the addition of items to a collection.

**Returns:**
java.lang.String - The policy governing the addition of items to a collection.
### setAccrualPolicy(String value) {#setAccrualPolicy-java.lang.String-}
```
public final void setAccrualPolicy(String value)
```


Sets the policy governing the addition of items to a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The policy governing the addition of items to a collection. |

### getAlternative() {#getAlternative--}
```
public final String getAlternative()
```


Gets an alternative name for the resource.

**Returns:**
java.lang.String - An alternative name for the resource.
### setAlternative(String value) {#setAlternative-java.lang.String-}
```
public final void setAlternative(String value)
```


Sets an alternative name for the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | An alternative name for the resource. |

### getAudience() {#getAudience--}
```
public final String getAudience()
```


Gets a class of agents for whom the resource is intended or useful.

**Returns:**
java.lang.String - A class of agents for whom the resource is intended or useful.
### setAudience(String value) {#setAudience-java.lang.String-}
```
public final void setAudience(String value)
```


Sets a class of agents for whom the resource is intended or useful.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A class of agents for whom the resource is intended or useful. |

### getAvailable() {#getAvailable--}
```
public final String getAvailable()
```


Gets the date that the resource became or will become available.

**Returns:**
java.lang.String - The date that the resource became or will become available.
### setAvailable(String value) {#setAvailable-java.lang.String-}
```
public final void setAvailable(String value)
```


Sets the date that the resource became or will become available.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The date that the resource became or will become available. |

### getBibliographicCitation() {#getBibliographicCitation--}
```
public final String getBibliographicCitation()
```


Gets a bibliographic reference for the resource.

**Returns:**
java.lang.String - A bibliographic reference for the resource.
### setBibliographicCitation(String value) {#setBibliographicCitation-java.lang.String-}
```
public final void setBibliographicCitation(String value)
```


Sets a bibliographic reference for the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A bibliographic reference for the resource. |

### getConformsTo() {#getConformsTo--}
```
public final String getConformsTo()
```


Gets an established standard to which the described resource conforms.

**Returns:**
java.lang.String - An established standard to which the described resource conforms.
### setConformsTo(String value) {#setConformsTo-java.lang.String-}
```
public final void setConformsTo(String value)
```


Sets an established standard to which the described resource conforms.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | An established standard to which the described resource conforms. |

### getContributor() {#getContributor--}
```
public final String getContributor()
```


Gets an entity responsible for making contributions to the resource.

**Returns:**
java.lang.String - An entity responsible for making contributions to the resource.
### setContributor(String value) {#setContributor-java.lang.String-}
```
public final void setContributor(String value)
```


Sets an entity responsible for making contributions to the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | An entity responsible for making contributions to the resource. |

### getCoverage() {#getCoverage--}
```
public final String getCoverage()
```


Gets the spatial or temporal topic of the resource, spatial applicability of the resource, or jurisdiction under which the resource is relevant.

**Returns:**
java.lang.String - The spatial or temporal topic of the resource, spatial applicability of the resource, or jurisdiction under which the resource is relevant.
### setCoverage(String value) {#setCoverage-java.lang.String-}
```
public final void setCoverage(String value)
```


Sets the spatial or temporal topic of the resource, spatial applicability of the resource, or jurisdiction under which the resource is relevant.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The spatial or temporal topic of the resource, spatial applicability of the resource, or jurisdiction under which the resource is relevant. |

### getCreated() {#getCreated--}
```
public final String getCreated()
```


Gets the date of creation of the resource.

**Returns:**
java.lang.String - The date of creation of the resource.
### setCreated(String value) {#setCreated-java.lang.String-}
```
public final void setCreated(String value)
```


Sets the date of creation of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The date of creation of the resource. |

### getCreator() {#getCreator--}
```
public final String getCreator()
```


Gets an entity responsible for making the resource.

**Returns:**
java.lang.String - An entity responsible for making the resource.
### setCreator(String value) {#setCreator-java.lang.String-}
```
public final void setCreator(String value)
```


Sets an entity responsible for making the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | An entity responsible for making the resource. |

### getDate() {#getDate--}
```
public final String getDate()
```


Gets a point or period of time associated with an event in the lifecycle of the resource.

**Returns:**
java.lang.String - A point or period of time associated with an event in the lifecycle of the resource.
### setDate(String value) {#setDate-java.lang.String-}
```
public final void setDate(String value)
```


Sets a point or period of time associated with an event in the lifecycle of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A point or period of time associated with an event in the lifecycle of the resource. |

### getDateAccepted() {#getDateAccepted--}
```
public final String getDateAccepted()
```


Gets the date of acceptance of the resource.

**Returns:**
java.lang.String - The date of acceptance of the resource.
### setDateAccepted(String value) {#setDateAccepted-java.lang.String-}
```
public final void setDateAccepted(String value)
```


Sets the date of acceptance of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The date of acceptance of the resource. |

### getDateCopyrighted() {#getDateCopyrighted--}
```
public final String getDateCopyrighted()
```


Gets the date of copyright of the resource.

**Returns:**
java.lang.String - The date of copyright of the resource.
### setDateCopyrighted(String value) {#setDateCopyrighted-java.lang.String-}
```
public final void setDateCopyrighted(String value)
```


Sets the date of copyright of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The date of copyright of the resource. |

### getDateSubmitted() {#getDateSubmitted--}
```
public final String getDateSubmitted()
```


Gets the date of submission of the resource.

**Returns:**
java.lang.String - The date of submission of the resource.
### setDateSubmitted(String value) {#setDateSubmitted-java.lang.String-}
```
public final void setDateSubmitted(String value)
```


Sets the date of submission of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The date of submission of the resource. |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Gets an account of the resource.

**Returns:**
java.lang.String - An account of the resource.
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Sets an account of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | An account of the resource. |

### getEducationLevel() {#getEducationLevel--}
```
public final String getEducationLevel()
```


Gets a class of agents, defined in terms of progression through an educational or training context, for which the described resource is intended.

**Returns:**
java.lang.String - A class of agents, defined in terms of progression through an educational or training context, for which the described resource is intended.
### setEducationLevel(String value) {#setEducationLevel-java.lang.String-}
```
public final void setEducationLevel(String value)
```


Sets a class of agents, defined in terms of progression through an educational or training context, for which the described resource is intended.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A class of agents, defined in terms of progression through an educational or training context, for which the described resource is intended. |

### getExtent() {#getExtent--}
```
public final String getExtent()
```


Gets the size or duration of the resource.

**Returns:**
java.lang.String - The size or duration of the resource.
### setExtent(String value) {#setExtent-java.lang.String-}
```
public final void setExtent(String value)
```


Sets the size or duration of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The size or duration of the resource. |

### getFormat() {#getFormat--}
```
public final String getFormat()
```


Gets the file format, physical medium, or dimensions of the resource.

**Returns:**
java.lang.String - The file format, physical medium, or dimensions of the resource.
### setFormat(String value) {#setFormat-java.lang.String-}
```
public final void setFormat(String value)
```


Sets the file format, physical medium, or dimensions of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The file format, physical medium, or dimensions of the resource. |

### hasFormat() {#hasFormat--}
```
public final String hasFormat()
```


Gets or sets a related resource that is substantially the same as the pre-existing described resource, but in another format.

**Returns:**
java.lang.String - A related resource that is substantially the same as the pre-existing described resource, but in another format.
### setHasFormat(String value) {#setHasFormat-java.lang.String-}
```
public final void setHasFormat(String value)
```


Sets a related resource that is substantially the same as the pre-existing described resource, but in another format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A related resource that is substantially the same as the pre-existing described resource, but in another format. |

### hasPart() {#hasPart--}
```
public final String hasPart()
```


Gets or sets a related resource that is included either physically or logically in the described resource.

**Returns:**
java.lang.String - A related resource that is included either physically or logically in the described resource.
### setPart(String value) {#setPart-java.lang.String-}
```
public final void setPart(String value)
```


Sets a related resource that is included either physically or logically in the described resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A related resource that is included either physically or logically in the described resource. |

### hasVersion() {#hasVersion--}
```
public final String hasVersion()
```


Gets or sets a related resource that is a version, edition, or adaptation of the described resource.

**Returns:**
java.lang.String - A related resource that is a version, edition, or adaptation of the described resource.
### setHasVersion(String value) {#setHasVersion-java.lang.String-}
```
public final void setHasVersion(String value)
```


Sets a related resource that is a version, edition, or adaptation of the described resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A related resource that is a version, edition, or adaptation of the described resource. |

### getIdentifier() {#getIdentifier--}
```
public final String getIdentifier()
```


Gets an unambiguous reference to the resource within a given context.

**Returns:**
java.lang.String - An unambiguous reference to the resource within a given context.
### setIdentifier(String value) {#setIdentifier-java.lang.String-}
```
public final void setIdentifier(String value)
```


Sets an unambiguous reference to the resource within a given context.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | An unambiguous reference to the resource within a given context. |

### getInstructionalMethod() {#getInstructionalMethod--}
```
public final String getInstructionalMethod()
```


Gets a process, used to engender knowledge, attitudes and skills, that the described resource is designed to support.

**Returns:**
java.lang.String - A process, used to engender knowledge, attitudes and skills, that the described resource is designed to support.
### setInstructionalMethod(String value) {#setInstructionalMethod-java.lang.String-}
```
public final void setInstructionalMethod(String value)
```


Sets a process, used to engender knowledge, attitudes and skills, that the described resource is designed to support.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A process, used to engender knowledge, attitudes and skills, that the described resource is designed to support. |

### isFormatOf() {#isFormatOf--}
```
public final String isFormatOf()
```


Gets a pre-existing related resource that is substantially the same as the described resource, but in another format.

**Returns:**
java.lang.String - A pre-existing related resource that is substantially the same as the described resource, but in another format.
### setFormatOf(String value) {#setFormatOf-java.lang.String-}
```
public final void setFormatOf(String value)
```


Sets a pre-existing related resource that is substantially the same as the described resource, but in another format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A pre-existing related resource that is substantially the same as the described resource, but in another format. |

### isPartOf() {#isPartOf--}
```
public final String isPartOf()
```


Gets a related resource in which the described resource is physically or logically included.

**Returns:**
java.lang.String - A related resource in which the described resource is physically or logically included.
### setPartOf(String value) {#setPartOf-java.lang.String-}
```
public final void setPartOf(String value)
```


Sets a related resource in which the described resource is physically or logically included.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A related resource in which the described resource is physically or logically included. |

### isReferencedBy() {#isReferencedBy--}
```
public final String isReferencedBy()
```


Gets a related resource that references, cites, or otherwise points to the described resource.

**Returns:**
java.lang.String - A related resource that references, cites, or otherwise points to the described resource.
### setReferencedBy(String value) {#setReferencedBy-java.lang.String-}
```
public final void setReferencedBy(String value)
```


Sets a related resource that references, cites, or otherwise points to the described resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A related resource that references, cites, or otherwise points to the described resource. |

### isReplacedBy() {#isReplacedBy--}
```
public final String isReplacedBy()
```


Gets a related resource that supplants, displaces, or supersedes the described resource.

**Returns:**
java.lang.String - A related resource that supplants, displaces, or supersedes the described resource.
### setReplacedBy(String value) {#setReplacedBy-java.lang.String-}
```
public final void setReplacedBy(String value)
```


Sets a related resource that supplants, displaces, or supersedes the described resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A related resource that supplants, displaces, or supersedes the described resource. |

### isRequiredBy() {#isRequiredBy--}
```
public final String isRequiredBy()
```


Gets a related resource that requires the described resource to support its function, delivery, or coherence.

**Returns:**
java.lang.String - A related resource that requires the described resource to support its function, delivery, or coherence.
### setRequiredBy(String value) {#setRequiredBy-java.lang.String-}
```
public final void setRequiredBy(String value)
```


Sets a related resource that requires the described resource to support its function, delivery, or coherence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A related resource that requires the described resource to support its function, delivery, or coherence. |

### getIssued() {#getIssued--}
```
public final String getIssued()
```


Gets the date of formal issuance of the resource.

**Returns:**
java.lang.String - The date of formal issuance of the resource.
### setIssued(String value) {#setIssued-java.lang.String-}
```
public final void setIssued(String value)
```


Sets the date of formal issuance of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The date of formal issuance of the resource. |

### isVersionOf() {#isVersionOf--}
```
public final String isVersionOf()
```


Gets a related resource of which the described resource is a version, edition, or adaptation.

**Returns:**
java.lang.String - A related resource of which the described resource is a version, edition, or adaptation.
### setVersionOf(String value) {#setVersionOf-java.lang.String-}
```
public final void setVersionOf(String value)
```


Sets a related resource of which the described resource is a version, edition, or adaptation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A related resource of which the described resource is a version, edition, or adaptation. |

### getLanguage() {#getLanguage--}
```
public final String getLanguage()
```


Gets the language of the resource.

**Returns:**
java.lang.String - The language of the resource.
### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public final void setLanguage(String value)
```


Sets the language of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The language of the resource. |

### getLicense() {#getLicense--}
```
public final String getLicense()
```


Gets a legal document giving official permission to do something with the resource.

**Returns:**
java.lang.String - A legal document giving official permission to do something with the resource.
### setLicense(String value) {#setLicense-java.lang.String-}
```
public final void setLicense(String value)
```


Sets a legal document giving official permission to do something with the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A legal document giving official permission to do something with the resource. |

### getMediator() {#getMediator--}
```
public final String getMediator()
```


Gets an entity that mediates access to the resource.

**Returns:**
java.lang.String - An entity that mediates access to the resource.
### setMediator(String value) {#setMediator-java.lang.String-}
```
public final void setMediator(String value)
```


Sets an entity that mediates access to the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | An entity that mediates access to the resource. |

### getMedium() {#getMedium--}
```
public final String getMedium()
```


Gets the material or physical carrier of the resource.

**Returns:**
java.lang.String - The material or physical carrier of the resource.
### setMedium(String value) {#setMedium-java.lang.String-}
```
public final void setMedium(String value)
```


Sets the material or physical carrier of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The material or physical carrier of the resource. |

### getModified() {#getModified--}
```
public final String getModified()
```


Gets the date on which the resource was changed.

**Returns:**
java.lang.String - The date on which the resource was changed.
### setModified(String value) {#setModified-java.lang.String-}
```
public final void setModified(String value)
```


Sets the date on which the resource was changed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The date on which the resource was changed. |

### getProvenance() {#getProvenance--}
```
public final String getProvenance()
```


Gets a statement of any changes in ownership and custody of the resource since its creation that are significant for its authenticity, integrity, and interpretation.

**Returns:**
java.lang.String - A statement of any changes in ownership and custody of the resource since its creation that are significant for its authenticity, integrity, and interpretation.
### setProvenance(String value) {#setProvenance-java.lang.String-}
```
public final void setProvenance(String value)
```


Sets a statement of any changes in ownership and custody of the resource since its creation that are significant for its authenticity, integrity, and interpretation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A statement of any changes in ownership and custody of the resource since its creation that are significant for its authenticity, integrity, and interpretation. |

### getPublisher() {#getPublisher--}
```
public final String getPublisher()
```


Gets an entity responsible for making the resource available.

**Returns:**
java.lang.String - An entity responsible for making the resource available.
### setPublisher(String value) {#setPublisher-java.lang.String-}
```
public final void setPublisher(String value)
```


Sets an entity responsible for making the resource available.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | An entity responsible for making the resource available. |

### getReferences() {#getReferences--}
```
public final String getReferences()
```


Gets a related resource that is referenced, cited, or otherwise pointed to by the described resource.

**Returns:**
java.lang.String - A related resource that is referenced, cited, or otherwise pointed to by the described resource.
### setReferences(String value) {#setReferences-java.lang.String-}
```
public final void setReferences(String value)
```


Sets a related resource that is referenced, cited, or otherwise pointed to by the described resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A related resource that is referenced, cited, or otherwise pointed to by the described resource. |

### getRelation() {#getRelation--}
```
public final String getRelation()
```


Gets a related resource.

**Returns:**
java.lang.String - A related resource.
### setRelation(String value) {#setRelation-java.lang.String-}
```
public final void setRelation(String value)
```


Sets a related resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A related resource. |

### getReplaces() {#getReplaces--}
```
public final String getReplaces()
```


Gets a related resource that is supplanted, displaced, or superseded by the described resource.

**Returns:**
java.lang.String - A related resource that is supplanted, displaced, or superseded by the described resource.
### setReplaces(String value) {#setReplaces-java.lang.String-}
```
public final void setReplaces(String value)
```


Sets a related resource that is supplanted, displaced, or superseded by the described resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A related resource that is supplanted, displaced, or superseded by the described resource. |

### getRequires() {#getRequires--}
```
public final String getRequires()
```


Gets a related resource that is required by the described resource to support its function, delivery, or coherence.

**Returns:**
java.lang.String - A related resource that is required by the described resource to support its function, delivery, or coherence.
### setRequires(String value) {#setRequires-java.lang.String-}
```
public final void setRequires(String value)
```


Sets a related resource that is required by the described resource to support its function, delivery, or coherence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A related resource that is required by the described resource to support its function, delivery, or coherence. |

### getRights() {#getRights--}
```
public final String getRights()
```


Gets the information about rights held in and over the resource.

**Returns:**
java.lang.String - The information about rights held in and over the resource.
### setRights(String value) {#setRights-java.lang.String-}
```
public final void setRights(String value)
```


Sets the information about rights held in and over the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The information about rights held in and over the resource. |

### getRightsHolder() {#getRightsHolder--}
```
public final String getRightsHolder()
```


Gets a person or organization owning or managing rights over the resource.

**Returns:**
java.lang.String - A person or organization owning or managing rights over the resource.
### setRightsHolder(String value) {#setRightsHolder-java.lang.String-}
```
public final void setRightsHolder(String value)
```


Sets a person or organization owning or managing rights over the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A person or organization owning or managing rights over the resource. |

### getSource() {#getSource--}
```
public final String getSource()
```


Gets a related resource from which the described resource is derived.

**Returns:**
java.lang.String - A related resource from which the described resource is derived.
### setSource(String value) {#setSource-java.lang.String-}
```
public final void setSource(String value)
```


Sets a related resource from which the described resource is derived.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A related resource from which the described resource is derived. |

### getSpatial() {#getSpatial--}
```
public final String getSpatial()
```


Gets the spatial characteristics of the resource.

**Returns:**
java.lang.String - The spatial characteristics of the resource.
### setSpatial(String value) {#setSpatial-java.lang.String-}
```
public final void setSpatial(String value)
```


Sets the spatial characteristics of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The spatial characteristics of the resource. |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets a topic of the resource.

**Returns:**
java.lang.String - A topic of the resource.
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Sets a topic of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A topic of the resource. |

### getTableOfContents() {#getTableOfContents--}
```
public final String getTableOfContents()
```


Gets a list of subunits of the resource.

**Returns:**
java.lang.String - A list of subunits of the resource.
### setTableOfContents(String value) {#setTableOfContents-java.lang.String-}
```
public final void setTableOfContents(String value)
```


Sets a list of subunits of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A list of subunits of the resource. |

### getTemporal() {#getTemporal--}
```
public final String getTemporal()
```


Gets the temporal characteristics of the resource.

**Returns:**
java.lang.String - The temporal characteristics of the resource.
### setTemporal(String value) {#setTemporal-java.lang.String-}
```
public final void setTemporal(String value)
```


Sets the temporal characteristics of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The temporal characteristics of the resource. |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gets a name given to the resource.

**Returns:**
java.lang.String - A name given to the resource.
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Sets a name given to the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A name given to the resource. |

### getType() {#getType--}
```
public final String getType()
```


Gets the nature or genre of the resource.

**Returns:**
java.lang.String - The nature or genre of the resource.
### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


Sets the nature or genre of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The nature or genre of the resource. |

### getValid() {#getValid--}
```
public final String getValid()
```


Gets the date (often a range) of validity of a resource.

**Returns:**
java.lang.String - The date (often a range) of validity of a resource.
### setValid(String value) {#setValid-java.lang.String-}
```
public final void setValid(String value)
```


Sets the date (often a range) of validity of a resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The date (often a range) of validity of a resource. |

