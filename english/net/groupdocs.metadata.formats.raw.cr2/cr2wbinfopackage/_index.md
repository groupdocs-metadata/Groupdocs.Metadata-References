---
title: Cr2WBInfoPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents Canon MakerNotes tags.
type: docs
weight: 2930
url: /net/groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/
---
## Cr2WBInfoPackage class

Represents Canon MakerNotes tags.

```csharp
public sealed class Cr2WBInfoPackage : RawDictionaryBasePackage
```

## Constructors

| Name | Description |
| --- | --- |
| [Cr2WBInfoPackage](cr2wbinfopackage)() | Initializes a new instance of the [`Cr2WBInfoPackage`](../cr2wbinfopackage) class. |

## Properties

| Name | Description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Item](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/item) { get; } | Gets the Raw tag with the specified id. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [WB_GRBGLevelsAuto](../../groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbglevelsauto) { get; } | Gets the WB_GRBGLevelsAuto. |
| [WB_GRBGLevelsCloudy](../../groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbglevelscloudy) { get; } | Gets the WB_GRBGLevelsCloudy. |
| [WB_GRBGLevelsCustom1](../../groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbglevelscustom1) { get; } | Gets the WB_GRBGLevelsCustom1. |
| [WB_GRBGLevelsCustom2](../../groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbglevelscustom2) { get; } | Gets the WB_GRBGLevelsCustom2. |
| [WB_GRBGLevelsDaylight](../../groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbglevelsdaylight) { get; } | Gets the WB_GRBGLevelsDaylight. |
| [WB_GRBGLevelsFlash](../../groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbglevelsflash) { get; } | Gets the WB_GRBGLevelsFlash. |
| [WB_GRBGLevelsFluorescent](../../groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbglevelsfluorescent) { get; } | Gets the WB_GRBGLevelsFluorescent. |
| [WB_GRBGLevelsFluorHigh](../../groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbglevelsfluorhigh) { get; } | Gets the WB_GRBGLevelsFluorHigh. |
| [WB_GRBGLevelsTungsten](../../groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbglevelstungsten) { get; } | Gets the WB_GRBGLevelsTungsten. |
| [WB_GRBGLevelsUnderwater](../../groupdocs.metadata.formats.raw.cr2/cr2wbinfopackage/wb_grbglevelsunderwater) { get; } | Gets the WB_GRBGLevelsUnderwater. |

## Methods

| Name | Description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Clear](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/clear)() | Removes all Raw tags stored in the package. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [Remove](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/remove)(uint) | Removes the property with the specified id. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [Set](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/set)(RawTag) | Adds or replaces the specified tag. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [ToList](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/tolist)() | Creates a list from the package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### See Also

* class [RawDictionaryBasePackage](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage)
* namespace [GroupDocs.Metadata.Formats.Raw.Cr2](../../groupdocs.metadata.formats.raw.cr2)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
