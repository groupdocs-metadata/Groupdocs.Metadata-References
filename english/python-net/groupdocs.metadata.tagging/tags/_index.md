---
title: Tags class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 100
url: /python-net/groupdocs.metadata.tagging/tags/
is_root: false
---

## Tags class

Contains various sets of tags with which most important metadata properties are marked.
The tags allow you to find and update metadata properties in different packages regardless of the metadata standard and file format.



The Tags type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [person](/metadata/python-net/groupdocs.metadata.tagging/tags/person) | Gets a set of tags that mark metadata properties holding information about the people contributed to file or intellectual content creation. <br/>These tags can help you to find the document creator, editor or even the client for whom the work was performed. <br/>Despite the name of the category some metadata properties marked with the tags can contain a company name rather than a person's name. |
| [tool](/metadata/python-net/groupdocs.metadata.tagging/tags/tool) | Gets the tags intended to mark metadata properties related to the tools (software and hardware) that were used to create a file. |
| [time](/metadata/python-net/groupdocs.metadata.tagging/tags/time) | Gets a set of tags that mark metadata properties used to describe the lifecycle of a file. <br/>The tags deal with time points when a file or intellectual content was created, edited, printed, etc. |
| [content](/metadata/python-net/groupdocs.metadata.tagging/tags/content) | Gets the tags that are attached to metadata properties describing the content of a file. <br/>The tags are useful to find out the content language, type (genre), subject, rating, etc. |
| [property_type](/metadata/python-net/groupdocs.metadata.tagging/tags/property_type) | Gets a set of tags that bear additional information about the type of a property rather than about its purpose.<br/>Using these tags you can detect metadata properties that contain URL links to external resources, <br/>properties describing fonts, colors, geolocation and so on. |
| [document](/metadata/python-net/groupdocs.metadata.tagging/tags/document) | Gets a set of tags that are applied to document-specific properties only. <br/>The tags can be useful to determine from which part of an office document a property was extracted. |
| [origin](/metadata/python-net/groupdocs.metadata.tagging/tags/origin) | Gets the tags that help a user to determine the origin of a file (e.g. template or another source). |
| [corporate](/metadata/python-net/groupdocs.metadata.tagging/tags/corporate) | Gets a set of tags intended to mark metadata properties related to a company that participated in file creation. |
| [legal](/metadata/python-net/groupdocs.metadata.tagging/tags/legal) | Gets a set of tags that are attached to metadata properties holding information about the owners of the file content <br/>and the rules under which the content can be used. |



### See Also
* module [`groupdocs.metadata.tagging`](..)
