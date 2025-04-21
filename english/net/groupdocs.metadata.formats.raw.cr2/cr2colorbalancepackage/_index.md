---
title: Cr2ColorBalancePackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents Canon MakerNotes tags.
type: docs
weight: 2850
url: /net/groupdocs.metadata.formats.raw.cr2/cr2colorbalancepackage/
---
## Cr2ColorBalancePackage class

Represents Canon MakerNotes tags.

```csharp
public sealed class Cr2ColorBalancePackage : RawDictionaryBasePackage
```

## Constructors

| Name | Description |
| --- | --- |
| [Cr2ColorBalancePackage](cr2colorbalancepackage)() | Initializes a new instance of the [`Cr2ColorBalancePackage`](../cr2colorbalancepackage) class. |

## Properties

| Name | Description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Item](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/item) { get; } | Gets the Raw tag with the specified id. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [WB_RGGBBlackLevels](../../groupdocs.metadata.formats.raw.cr2/cr2colorbalancepackage/wb_rggbblacklevels) { get; } | Gets the WB_RGGBBlackLevels. |
| [WB_RGGBLevelsAuto](../../groupdocs.metadata.formats.raw.cr2/cr2colorbalancepackage/wb_rggblevelsauto) { get; } | Gets the WB_RGGBLevelsAuto. |
| [WB_RGGBLevelsCloudy](../../groupdocs.metadata.formats.raw.cr2/cr2colorbalancepackage/wb_rggblevelscloudy) { get; } | Gets the WB_RGGBLevelsCloudy. |
| [WB_RGGBLevelsDaylight](../../groupdocs.metadata.formats.raw.cr2/cr2colorbalancepackage/wb_rggblevelsdaylight) { get; } | Gets the WB_RGGBLevelsDaylight. |
| [WB_RGGBLevelsFlash](../../groupdocs.metadata.formats.raw.cr2/cr2colorbalancepackage/wb_rggblevelsflash) { get; } | Gets the WB_RGGBLevelsFlash. |
| [WB_RGGBLevelsFluorescent](../../groupdocs.metadata.formats.raw.cr2/cr2colorbalancepackage/wb_rggblevelsfluorescent) { get; } | Gets the WB_RGGBLevelsFluorescent. |
| [WB_RGGBLevelsKelvin](../../groupdocs.metadata.formats.raw.cr2/cr2colorbalancepackage/wb_rggblevelskelvin) { get; } | Gets the WB_RGGBLevelsKelvin. |
| [WB_RGGBLevelsShade](../../groupdocs.metadata.formats.raw.cr2/cr2colorbalancepackage/wb_rggblevelsshade) { get; } | Gets the WB_RGGBLevelsShade. |
| [WB_RGGBLevelsTungsten](../../groupdocs.metadata.formats.raw.cr2/cr2colorbalancepackage/wb_rggblevelstungsten) { get; } | Gets the WB_RGGBLevelsTungsten. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Clear](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/clear)() | Removes all Raw tags stored in the package. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [Remove](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/remove)(uint) | Removes the property with the specified id. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [Set](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/set)(RawTag) | Adds or replaces the specified tag. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [ToList](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/tolist)() | Creates a list from the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### See Also

* class [RawDictionaryBasePackage](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage)
* namespace [GroupDocs.Metadata.Formats.Raw.Cr2](../../groupdocs.metadata.formats.raw.cr2)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
