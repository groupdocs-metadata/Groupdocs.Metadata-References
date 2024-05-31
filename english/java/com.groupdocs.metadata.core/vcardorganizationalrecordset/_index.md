---
title: VCardOrganizationalRecordset
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a set of Organizational vCard records.
type: docs
weight: 276
url: /java/com.groupdocs.metadata.core/vcardorganizationalrecordset/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.VCardBasePackage](../../com.groupdocs.metadata.core/vcardbasepackage), [com.groupdocs.metadata.core.VCardRecordset](../../com.groupdocs.metadata.core/vcardrecordset)
```
public class VCardOrganizationalRecordset extends VCardRecordset
```

Represents a set of Organizational vCard records. These properties are concerned with information associated with characteristics of the organization or organizational units of the object that the vCard represents.

**Learn more**

 *  [Working with vCard metadata][]


[Working with vCard metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+vCard+metadata
## Methods

| Method | Description |
| --- | --- |
| [getTitleRecords()](#getTitleRecords--) | Gets the positions or jobs of the object. |
| [getTitles()](#getTitles--) | Gets the positions or jobs of the object. |
| [getRoleRecords()](#getRoleRecords--) | Gets the functions or parts played in a particular situation by the object. |
| [getRoles()](#getRoles--) | Gets the functions or parts played in a particular situation by the object. |
| [getLogoRecords()](#getLogoRecords--) | Gets the graphic images of the logo associated with the object. |
| [getLogoBinaryRecords()](#getLogoBinaryRecords--) | Gets the graphic images of the logo associated with the object. |
| [getBinaryLogos()](#getBinaryLogos--) | Gets the graphic images of the logo associated with the object. |
| [getLogoUriRecords()](#getLogoUriRecords--) | Gets the URIs of the graphic images of the logo associated with the object. |
| [getUriLogos()](#getUriLogos--) | Gets the URIs of the graphic images of the logo associated with the object. |
| [getAgentRecords()](#getAgentRecords--) | Gets the information about another person who will act on behalf of the vCard object. |
| [getAgentObjectRecord()](#getAgentObjectRecord--) | Gets the information about another person who will act on behalf of the vCard object. |
| [getObjectAgent()](#getObjectAgent--) | Gets the information about another person who will act on behalf of the vCard object. |
| [getAgentUriRecords()](#getAgentUriRecords--) | Gets the information about another person who will act on behalf of the vCard object. |
| [getUriAgents()](#getUriAgents--) | Gets the information about another person who will act on behalf of the vCard object. |
| [getOrganizationNameRecords()](#getOrganizationNameRecords--) | Gets the organizational names and units associated with the object. |
| [getOrganizationNames()](#getOrganizationNames--) | Gets the organizational names and units associated with the object. |
| [getMemberRecords()](#getMemberRecords--) | Gets the members in the group this vCard represents. |
| [getMembers()](#getMembers--) | Gets the members in the group this vCard represents. |
| [getRelationshipRecords()](#getRelationshipRecords--) | Gets the relationships between another entity and the entity represented by this vCard. |
| [getRelationships()](#getRelationships--) | Gets the relationships between another entity and the entity represented by this vCard. |
### getTitleRecords() {#getTitleRecords--}
```
public final VCardTextRecord[] getTitleRecords()
```


Gets the positions or jobs of the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The positions or jobs of the object.
### getTitles() {#getTitles--}
```
public final String[] getTitles()
```


Gets the positions or jobs of the object.

**Returns:**
java.lang.String[] - The positions or jobs of the object.

--------------------

This property is a simplified version of  TitleRecords .
### getRoleRecords() {#getRoleRecords--}
```
public final VCardTextRecord[] getRoleRecords()
```


Gets the functions or parts played in a particular situation by the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The functions or parts played in a particular situation by the object.
### getRoles() {#getRoles--}
```
public final String[] getRoles()
```


Gets the functions or parts played in a particular situation by the object.

**Returns:**
java.lang.String[] - The functions or parts played in a particular situation by the object.

--------------------

This property is a simplified version of  TitleRecords .
### getLogoRecords() {#getLogoRecords--}
```
public final VCardRecord[] getLogoRecords()
```


Gets the graphic images of the logo associated with the object.

**Returns:**
com.groupdocs.metadata.core.VCardRecord[] - The graphic images of the logo associated with the object.
### getLogoBinaryRecords() {#getLogoBinaryRecords--}
```
public final VCardBinaryRecord[] getLogoBinaryRecords()
```


Gets the graphic images of the logo associated with the object.

**Returns:**
com.groupdocs.metadata.core.VCardBinaryRecord[] - The graphic images of the logo associated with the object.

--------------------

This property is a simplified version of  LogoRecords .
### getBinaryLogos() {#getBinaryLogos--}
```
public final byte[][] getBinaryLogos()
```


Gets the graphic images of the logo associated with the object.

**Returns:**
byte[][] - The graphic images of the logo associated with the object.

--------------------

This property is a simplified version of  LogoBinaryRecords .
### getLogoUriRecords() {#getLogoUriRecords--}
```
public final VCardTextRecord[] getLogoUriRecords()
```


Gets the URIs of the graphic images of the logo associated with the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The URIs of the graphic images of the logo associated with the object.

--------------------

This property is a simplified version of  LogoRecords .
### getUriLogos() {#getUriLogos--}
```
public final String[] getUriLogos()
```


Gets the URIs of the graphic images of the logo associated with the object.

**Returns:**
java.lang.String[] - The URIs of the graphic images of the logo associated with the object.

--------------------

This property is a simplified version of  LogoUriRecords .
### getAgentRecords() {#getAgentRecords--}
```
public final VCardRecord[] getAgentRecords()
```


Gets the information about another person who will act on behalf of the vCard object.

**Returns:**
com.groupdocs.metadata.core.VCardRecord[] - The information about another person who will act on behalf of the vCard object.
### getAgentObjectRecord() {#getAgentObjectRecord--}
```
public final VCardAgentRecord getAgentObjectRecord()
```


Gets the information about another person who will act on behalf of the vCard object.

**Returns:**
[VCardAgentRecord](../../com.groupdocs.metadata.core/vcardagentrecord) - The information about another person who will act on behalf of the vCard object.

--------------------

This property is a simplified version of  AgentRecords .
### getObjectAgent() {#getObjectAgent--}
```
public final VCardCard getObjectAgent()
```


Gets the information about another person who will act on behalf of the vCard object.

**Returns:**
[VCardCard](../../com.groupdocs.metadata.core/vcardcard) - The information about another person who will act on behalf of the vCard object.

--------------------

This property is a simplified version of  AgentObjectRecord .
### getAgentUriRecords() {#getAgentUriRecords--}
```
public final VCardTextRecord[] getAgentUriRecords()
```


Gets the information about another person who will act on behalf of the vCard object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The information about another person who will act on behalf of the vCard object.

--------------------

This property is a simplified version of  AgentRecords .
### getUriAgents() {#getUriAgents--}
```
public final String[] getUriAgents()
```


Gets the information about another person who will act on behalf of the vCard object.

**Returns:**
java.lang.String[] - The information about another person who will act on behalf of the vCard object.

--------------------

This property is a simplified version of  AgentUriRecords .
### getOrganizationNameRecords() {#getOrganizationNameRecords--}
```
public final VCardTextRecord[] getOrganizationNameRecords()
```


Gets the organizational names and units associated with the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The organizational names and units associated with the object.
### getOrganizationNames() {#getOrganizationNames--}
```
public final String[] getOrganizationNames()
```


Gets the organizational names and units associated with the object.

**Returns:**
java.lang.String[] - The organizational names and units associated with the object.

--------------------

This property is a simplified version of  OrganizationNameRecords .
### getMemberRecords() {#getMemberRecords--}
```
public final VCardTextRecord[] getMemberRecords()
```


Gets the members in the group this vCard represents.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The members in the group this vCard represents.
### getMembers() {#getMembers--}
```
public final String[] getMembers()
```


Gets the members in the group this vCard represents.

**Returns:**
java.lang.String[] - The members in the group this vCard represents.

--------------------

This property is a simplified version of  MemberRecords .
### getRelationshipRecords() {#getRelationshipRecords--}
```
public final VCardTextRecord[] getRelationshipRecords()
```


Gets the relationships between another entity and the entity represented by this vCard.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The relationships between another entity and the entity represented by this vCard.
### getRelationships() {#getRelationships--}
```
public final String[] getRelationships()
```


Gets the relationships between another entity and the entity represented by this vCard.

**Returns:**
java.lang.String[] - The relationships between another entity and the entity represented by this vCard.

--------------------

This property is a simplified version of  RelationshipRecords .
