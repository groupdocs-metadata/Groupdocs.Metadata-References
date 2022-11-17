---
title: XmpCameraRawPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar Camera Rawschema.
type: docs
weight: 3100
url: /sv/net/groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/
---
## XmpCameraRawPackage class

Representerar Camera Raw-schema.

```csharp
public sealed class XmpCameraRawPackage : XmpPackage
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [XmpCameraRawPackage](xmpcamerarawpackage)() | Initierar en ny instans av[`XmpCameraRawPackage`](../xmpcamerarawpackage) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AutoBrightness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autobrightness) { get; set; } | Hämtar eller ställer in värdet för AutoLjusstyrka. När det är sant,[`Brightness`](./brightness) justeras automatiskt. |
| [AutoContrast](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autocontrast) { get; set; } | Hämtar eller ställer in AutoContrast-värdet. När sant justeras "Kontrast" automatiskt. |
| [AutoExposure](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autoexposure) { get; set; } | Hämtar eller ställer in AutoExposure-värdet. När sant, justeras "Exponering" automatiskt. |
| [AutoShadows](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autoshadows) { get; set; } | Hämtar eller ställer in AutoShadows-värdet. När det är sant justeras "Shadows" automatiskt. |
| [BlueHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/bluehue) { get; set; } | Hämtar eller ställer in BlueHue-värdet. Null om odefinierat. |
| [BlueSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/bluesaturation) { get; set; } | Hämtar eller ställer in BlueSaturation. Null om odefinierat. |
| [Brightness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/brightness) { get; set; } | Hämtar eller ställer in ljusstyrka. Null om odefinierat. |
| [CameraProfile](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cameraprofile) { get; set; } | Hämtar eller ställer in CameraProfile-värdet. |
| [ChromaticAberrationB](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/chromaticaberrationb) { get; set; } | Hämtar eller ställer in inställningen "Kromatisk aberration, Fix Blue/Yellow Fringe". Null om odefinierat. |
| [ChromaticAberrationR](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/chromaticaberrationr) { get; set; } | Hämtar eller ställer in inställningen "Kromatisk aberration, Fix Red/Cyan Fringe". Null om odefinierat. |
| [ColorNoiseReduction](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/colornoisereduction) { get; set; } | Hämtar eller ställer in inställningen Färgbrusreducering. Område 0 till 100. |
| [Contrast](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/contrast) { get; set; } | Hämtar eller ställer in kontrastinställningen. Område -50 till 100. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [CropAngle](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropangle) { get; set; } | Hämtar eller ställer in CropAngle-inställningen. När HasCrop är sant, vinkeln på beskärningsrektangeln. |
| [CropBottom](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropbottom) { get; set; } | Hämtar eller ställer in CropBottom-inställningen. När HasCrop är sant, botten av beskärningsrektangeln. |
| [CropHeight](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropheight) { get; set; } | Hämtar eller ställer in höjden på den resulterande beskurna bilden[`CropUnits`](./cropunits) enheter. |
| [CropLeft](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropleft) { get; set; } | Hämtar eller ställer in CropLeft-inställningen. När HasCrop är sant, till vänster om beskärningsrektangeln. |
| [CropRight](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropright) { get; set; } | Hämtar eller ställer in CropRight-inställningen. När HasCrop är sant, till höger om beskärningsrektangeln. |
| [CropTop](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/croptop) { get; set; } | Hämtar eller ställer in CropTop-inställningen. När HasCrop är sant, toppen av beskärningsrektangeln. |
| [CropUnits](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropunits) { get; set; } | Hämtar eller ställer in enheter för[`CropWidth`](./cropwidth) och[`CropHeight`](./cropheight) . |
| [CropWidth](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropwidth) { get; set; } | Hämtar eller ställer in bredden på den resulterande beskurna bilden[`CropUnits`](./cropunits) enheter. |
| [Exposure](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/exposure) { get; set; } | Hämtar eller ställer in exponeringsinställningen. |
| [GreenHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/greenhue) { get; set; } | Hämtar eller ställer in inställningen för grön nyans. Område -100 till 100. |
| [GreenSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/greensaturation) { get; set; } | Hämtar eller ställer in inställningen för grön mättnad. Område -100 till 100. |
| [HasCrop](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/hascrop) { get; set; } | Hämtar eller ställer in HasCrop-värdet. När sant har bilden en beskärningsrektangel. |
| [HasSettings](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/hassettings) { get; set; } | Hämtar eller ställer in HasSettings-värdet. När sant, icke-standardinställningar för Camera Raw. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [LuminanceSmoothing](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/luminancesmoothing) { get; set; } | Hämtar eller ställer in LuminanceSmoothing-inställningen. Område 0 till 100. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Hämtar namnutrymmets URI. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Hämtar xmlns-prefixet. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [RawFileName](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/rawfilename) { get; set; } | Hämtar eller ställer in filnamnet för en råfil (inte en fullständig sökväg). |
| [RedHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/redhue) { get; set; } | Hämtar eller ställer in röd nyans. Område -100 till 100. |
| [RedSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/redsaturation) { get; set; } | Hämtar eller ställer in rödmättnad. Område -100 till 100. |
| [Saturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/saturation) { get; set; } | Hämtar eller ställer in mättnadsinställningen. Område -100 till 100. |
| [Shadows](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/shadows) { get; set; } | Hämtar eller ställer in Skuggor. Område 0 till 100. |
| [ShadowTint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/shadowtint) { get; set; } | Hämtar eller ställer in ShadowTint-inställningen. Område -100 till 100. |
| [Sharpness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/sharpness) { get; set; } | Hämtar eller ställer in skärpa. Område 0 till 100. |
| [Temperature](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/temperature) { get; set; } | Hämtar eller ställer in temperaturinställningen. Område 2000 till 50000. |
| [Tint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/tint) { get; set; } | Hämtar eller ställer in färgtonsinställningen. Område -150 till 150. |
| [Version](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/version) { get; set; } | Hämtar eller ställer in versionen av plugin-programmet Camera Raw. |
| [VignetteAmount](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/vignetteamount) { get; set; } | Hämtar eller ställer in inställningen Vinjettmängd. Område -100 till 100. |
| [VignetteMidpoint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/vignettemidpoint) { get; set; } | Hämtar eller ställer in inställningen Vignetteringsmittpunkt. Område 0 till 100. |
| [WhiteBalance](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/whitebalance) { get; } | Hämtar vitbalansinställning. Använda sig av[`SetWhiteBalance`](./setwhitebalance) för att ställa in vitbalansvärdet. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Hämtar XML-namnutrymmet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Tar bort alla XMP-egenskaper. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Konverterar XMP-värdet till XML-representationen. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Tar bort egenskapen med det angivna namnet. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Ställer in boolesk egenskap. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | SetsDateTime egenskap. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Ställer in dubbel egenskap. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Ställer in heltalsegenskapen. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/set#set_7)(string, string) | Lägger till strängegenskap. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Ställer in värdet som ärvs från[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Ställer in värdet som ärvs från[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Ställer in värdet som ärvs från[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [SetWhiteBalance](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/setwhitebalance)(XmpWhiteBalance) | Ställer in vitbalansen. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Se även

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* namnutrymme [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
