---
title: Cr2ShotInfoPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents Canon MakerNotes tags.
type: docs
weight: 3130
url: /net/groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/
---
## Cr2ShotInfoPackage class

Represents Canon MakerNotes tags.

```csharp
public sealed class Cr2ShotInfoPackage : RawDictionaryBasePackage
```

## Constructors

| Name | Description |
| --- | --- |
| [Cr2ShotInfoPackage](cr2shotinfopackage)() | Initializes a new instance of the [`Cr2ShotInfoPackage`](../cr2shotinfopackage) class. |

## Properties

| Name | Description |
| --- | --- |
| [AEBBracketValue](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/aebbracketvalue) { get; } | Gets the AEBBracketValue. |
| [AFPointsInFocus](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/afpointsinfocus) { get; } | Gets the AFPointsInFocus. |
| [AutoExposureBracketing](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/autoexposurebracketing) { get; } | Gets the AutoExposureBracketing. |
| [AutoISO](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/autoiso) { get; } | Gets the AutoISO. |
| [AutoRotate](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/autorotate) { get; } | Gets the AutoRotate. |
| [BaseISO](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/baseiso) { get; } | Gets the BaseISO. |
| [BulbDuration](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/bulbduration) { get; } | Gets the BulbDuration. |
| [CameraTemperature](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/cameratemperature) { get; } | Gets the CameraTemperature. |
| [CameraType](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/cameratype) { get; } | Gets the CameraType. |
| [ControlMode](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/controlmode) { get; } | Gets the ControlMode. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [ExposureCompensation](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/exposurecompensation) { get; } | Gets the ExposureCompensation. |
| [ExposureTime](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/exposuretime) { get; } | Gets the ExposureTime. |
| [FlashExposureComp](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/flashexposurecomp) { get; } | Gets the FlashExposureComp. |
| [FlashGuideNumber](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/flashguidenumber) { get; } | Gets the FlashGuideNumber. |
| [FlashOutput](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/flashoutput) { get; } | Gets the FlashOutput. |
| [FNumber](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/fnumber) { get; } | Gets the FNumber. |
| [FocusDistanceLower](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/focusdistancelower) { get; } | Gets the FocusDistanceLower. |
| [FocusDistanceUpper](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/focusdistanceupper) { get; } | Gets the FocusDistanceUpper. |
| [Item](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/item) { get; } | Gets the Raw tag with the specified id. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MeasuredEV](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/measuredev) { get; } | Gets the MeasuredEV. |
| [MeasuredEV2](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/measuredev2) { get; } | Gets the MeasuredEV2. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [NDFilter](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/ndfilter) { get; } | Gets the NDFilter. |
| [OpticalZoomCode](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/opticalzoomcode) { get; } | Gets the OpticalZoomCode. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [SelfTimer2](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/selftimer2) { get; } | Gets the SelfTimer2. |
| [SequenceNumber](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/sequencenumber) { get; } | Gets the SequenceNumber. |
| [SlowShutter](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/slowshutter) { get; } | Gets the SlowShutter. |
| [TargetAperture](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/targetaperture) { get; } | Gets the TargetAperture. |
| [TargetExposureTime](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/targetexposuretime) { get; } | Gets the TargetExposureTime. |
| [WhiteBalance](../../groupdocs.metadata.formats.raw.cr2/cr2shotinfopackage/whitebalance) { get; } | Gets the WhiteBalance. |

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
