---
title: PropertyTypeTagCategory
second_title: GroupDocs.Metadata for Java API Reference
description: Provides tags that bear additional information about the type of a property rather than about its purpose.
type: docs
weight: 17
url: /java/com.groupdocs.metadata.tagging/propertytypetagcategory/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.tagging.TagCategory](../../com.groupdocs.metadata.tagging/tagcategory)
```
public class PropertyTypeTagCategory extends TagCategory
```

Provides tags that bear additional information about the type of a property rather than about its purpose. Using these tags you can detect metadata properties that contain URL links to external resources, properties describing fonts, colors, geolocation and so on.
## Methods

| Method | Description |
| --- | --- |
| [getLink()](#getLink--) | Gets the tag that denotes a property being a link to an external resource. |
| [getHash()](#getHash--) | Gets the tag that labels a property holding a hash of the file content. |
| [getMeasure()](#getMeasure--) | Gets the tag that indicates a property being a measured characteristic of the content. |
| [getDigitalSignature()](#getDigitalSignature--) | Gets the tag that labels a digital signature. |
| [getIdentifier()](#getIdentifier--) | Gets the tag that labels a property containing an identifier of the content. |
| [getLocation()](#getLocation--) | Gets the tag that indicates a property being a reference to a geographical location. |
| [getFont()](#getFont--) | Gets the tag that denotes a property describing font characteristics. |
| [getColor()](#getColor--) | Gets the tag that labels a property describing a color. |
| [getBitrate()](#getBitrate--) | Gets the tag that labels a property describing a bitrate. |
### getLink() {#getLink--}
```
public final PropertyTag getLink()
```


Gets the tag that denotes a property being a link to an external resource.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that denotes a property being a link to an external resource.
### getHash() {#getHash--}
```
public final PropertyTag getHash()
```


Gets the tag that labels a property holding a hash of the file content.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that labels a property holding a hash of the file content.
### getMeasure() {#getMeasure--}
```
public final PropertyTag getMeasure()
```


Gets the tag that indicates a property being a measured characteristic of the content. It can be the file size, number of pages, page size, etc.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that indicates a property being a measured characteristic of the content.
### getDigitalSignature() {#getDigitalSignature--}
```
public final PropertyTag getDigitalSignature()
```


Gets the tag that labels a digital signature.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that labels a digital signature.
### getIdentifier() {#getIdentifier--}
```
public final PropertyTag getIdentifier()
```


Gets the tag that labels a property containing an identifier of the content.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that labels a property containing an identifier of the content.
### getLocation() {#getLocation--}
```
public final PropertyTag getLocation()
```


Gets the tag that indicates a property being a reference to a geographical location. The property can contain the name of a city, full address, GPS coordinates, etc.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that indicates a property being a reference to a geographical location.
### getFont() {#getFont--}
```
public final PropertyTag getFont()
```


Gets the tag that denotes a property describing font characteristics.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that denotes a property describing font characteristics.
### getColor() {#getColor--}
```
public final PropertyTag getColor()
```


Gets the tag that labels a property describing a color.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that labels a property describing a color.
### getBitrate() {#getBitrate--}
```
public final PropertyTag getBitrate()
```


Gets the tag that labels a property describing a bitrate.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that labels a property describing a bitrate.
