---
title: XmpCameraRawPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents Camera Raw schema.
type: docs
weight: 4510
url: /net/groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/
---
## XmpCameraRawPackage class

Represents Camera Raw schema.

```csharp
public sealed class XmpCameraRawPackage : XmpPackage
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpCameraRawPackage](xmpcamerarawpackage)() | Initializes a new instance of the [`XmpCameraRawPackage`](../xmpcamerarawpackage) class. |

## Properties

| Name | Description |
| --- | --- |
| [AutoBrightness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autobrightness) { get; set; } | Gets or sets the AutoBrightness value. When true, [`Brightness`](./brightness) is automatically adjusted. |
| [AutoContrast](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autocontrast) { get; set; } | Gets or sets the AutoContrast value. When true, "Contrast" is automatically adjusted. |
| [AutoExposure](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autoexposure) { get; set; } | Gets or sets the AutoExposure value. When true, "Exposure" is automatically adjusted. |
| [AutoShadows](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autoshadows) { get; set; } | Gets or sets the AutoShadows value. When true, "Shadows" is automatically adjusted. |
| [BlueHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/bluehue) { get; set; } | Gets or sets the BlueHue value. Null if undefined. |
| [BlueSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/bluesaturation) { get; set; } | Gets or sets the BlueSaturation. Null if undefined. |
| [Brightness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/brightness) { get; set; } | Gets or sets the Brightness value. Null if undefined. |
| [CameraProfile](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cameraprofile) { get; set; } | Gets or sets the CameraProfile value. |
| [ChromaticAberrationB](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/chromaticaberrationb) { get; set; } | Gets or sets the "Chromatic Aberration, Fix Blue/Yellow Fringe" setting. Null if undefined. |
| [ChromaticAberrationR](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/chromaticaberrationr) { get; set; } | Gets or sets the "Chromatic Aberration, Fix Red/Cyan Fringe" setting. Null if undefined. |
| [ColorNoiseReduction](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/colornoisereduction) { get; set; } | Gets or sets the Color Noise Reduction setting. Range 0 to 100. |
| [Contrast](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/contrast) { get; set; } | Gets or sets the Contrast setting. Range -50 to 100. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [CropAngle](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropangle) { get; set; } | Gets or sets the CropAngle setting. When HasCrop is true, angle of the crop rectangle. |
| [CropBottom](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropbottom) { get; set; } | Gets or sets the CropBottom setting. When HasCrop is true, bottom of the crop rectangle. |
| [CropHeight](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropheight) { get; set; } | Gets or sets the height of the resulting cropped image in [`CropUnits`](./cropunits) units. |
| [CropLeft](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropleft) { get; set; } | Gets or sets the CropLeft setting. When HasCrop is true, left of the crop rectangle. |
| [CropRight](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropright) { get; set; } | Gets or sets the CropRight setting. When HasCrop is true, right of the crop rectangle. |
| [CropTop](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/croptop) { get; set; } | Gets or sets the CropTop setting. When HasCrop is true, top of the crop rectangle. |
| [CropUnits](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropunits) { get; set; } | Gets or sets units for [`CropWidth`](./cropwidth) and [`CropHeight`](./cropheight). |
| [CropWidth](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropwidth) { get; set; } | Gets or sets the width of the resulting cropped image in [`CropUnits`](./cropunits) units. |
| [Exposure](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/exposure) { get; set; } | Gets or sets the Exposure setting. |
| [GreenHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/greenhue) { get; set; } | Gets or sets the Green Hue setting. Range -100 to 100. |
| [GreenSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/greensaturation) { get; set; } | Gets or sets the Green Saturation setting. Range -100 to 100. |
| [HasCrop](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/hascrop) { get; set; } | Gets or sets the HasCrop value. When true, the image has a cropping rectangle. |
| [HasSettings](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/hassettings) { get; set; } | Gets or sets HasSettings value. When true, non-default camera raw settings. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [LuminanceSmoothing](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/luminancesmoothing) { get; set; } | Gets or sets the LuminanceSmoothing setting. Range 0 to 100. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Gets the namespace URI. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Gets the xmlns prefix. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [RawFileName](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/rawfilename) { get; set; } | Gets or sets the file name for a raw file (not a complete path). |
| [RedHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/redhue) { get; set; } | Gets or sets the Red Hue setting. Range -100 to 100. |
| [RedSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/redsaturation) { get; set; } | Gets or sets the Red Saturation setting. Range -100 to 100. |
| [Saturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/saturation) { get; set; } | Gets or sets the Saturation setting. Range -100 to 100. |
| [Shadows](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/shadows) { get; set; } | Gets or sets the Shadows setting. Range 0 to 100. |
| [ShadowTint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/shadowtint) { get; set; } | Gets or sets the ShadowTint setting. Range -100 to 100. |
| [Sharpness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/sharpness) { get; set; } | Gets or sets the Sharpness setting. Range 0 to 100. |
| [Temperature](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/temperature) { get; set; } | Gets or sets the Temperature setting. Range 2000 to 50000. |
| [Tint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/tint) { get; set; } | Gets or sets the Tint setting. Range -150 to 150. |
| [Version](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/version) { get; set; } | Gets or sets the version of the Camera Raw plug-in. |
| [VignetteAmount](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/vignetteamount) { get; set; } | Gets or sets the Vignette Amount setting. Range -100 to 100. |
| [VignetteMidpoint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/vignettemidpoint) { get; set; } | Gets or sets the Vignetting Midpoint setting. Range 0 to 100. |
| [WhiteBalance](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/whitebalance) { get; } | Gets White Balance setting. Use [`SetWhiteBalance`](./setwhitebalance) to set white balance value. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Gets the XML namespace. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Removes all XMP properties. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Converts the XMP value to the XML representation. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Removes the property with the specified name. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Sets boolean property. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | Sets DateTime property. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Sets double property. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Sets integer property. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/set#set_7)(string, string) | Adds string property. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Sets the value inherited from [`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Sets the value inherited from [`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Sets the value inherited from [`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [SetWhiteBalance](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/setwhitebalance)(XmpWhiteBalance) | Sets the white balance. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### See Also

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* namespace [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
