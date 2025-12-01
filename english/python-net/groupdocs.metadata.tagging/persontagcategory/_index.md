---
title: PersonTagCategory class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 60
url: /python-net/groupdocs.metadata.tagging/persontagcategory/
is_root: false
---

## PersonTagCategory class

Provides tags that mark metadata properties holding information about the people contributed to file or intellectual content creation. 
These tags can help you to find the document creator, editor or even the client for whom the work was performed.
Despite the name of the category some metadata properties marked with the tags can contain a company name rather than a person's name.



**Inheritance:** [`PersonTagCategory`](/metadata/python-net/groupdocs.metadata.tagging/persontagcategory) → 
[`TagCategory`](/metadata/python-net/groupdocs.metadata.tagging/tagcategory)



The PersonTagCategory type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [creator](/metadata/python-net/groupdocs.metadata.tagging/persontagcategory/creator) | Gets the tag that denotes the original author of a file/document. |
| [contributor](/metadata/python-net/groupdocs.metadata.tagging/persontagcategory/contributor) | Gets the tag that labels a property containing the name of a person who somehow contributed to file creation. <br/>Please note that the tag is not applied towards metadata properties marked with more specific tags from this category. <br/>E.g. if a property labeled with the Creator tag. |
| [editor](/metadata/python-net/groupdocs.metadata.tagging/persontagcategory/editor) | Gets the tag that labels a person who edited a file. <br/>The tag is usually used to mark a property containing information about the last editor. |
| [model](/metadata/python-net/groupdocs.metadata.tagging/persontagcategory/model) | Gets the tag that denotes information about a person the content of the file is about. <br/>For photos that is a person shown in the image. |
| [client](/metadata/python-net/groupdocs.metadata.tagging/persontagcategory/client) | Gets the tag that labels information about the client for whom the file/intellectual content was created. |
| [manager](/metadata/python-net/groupdocs.metadata.tagging/persontagcategory/manager) | Gets the tag that labels information about a person who managed the making process of a file. |
| [publisher](/metadata/python-net/groupdocs.metadata.tagging/persontagcategory/publisher) | Gets the tag marking a person responsible for making the file available. |
| [artist](/metadata/python-net/groupdocs.metadata.tagging/persontagcategory/artist) | Gets the tag that denotes the original performer of a file. |
| [recipient](/metadata/python-net/groupdocs.metadata.tagging/persontagcategory/recipient) | Gets the tag that denotes the original recipients of a mail. |



### See Also
* module [`groupdocs.metadata.tagging`](..)
* class [`PersonTagCategory`](/metadata/python-net/groupdocs.metadata.tagging/persontagcategory)
* class [`TagCategory`](/metadata/python-net/groupdocs.metadata.tagging/tagcategory)
