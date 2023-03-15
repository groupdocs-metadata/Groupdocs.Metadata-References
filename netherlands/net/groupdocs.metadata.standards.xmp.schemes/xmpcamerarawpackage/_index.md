---
title: XmpCameraRawPackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt Camera Rawschema.
type: docs
weight: 3100
url: /nl/net/groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/
---
## XmpCameraRawPackage class

Vertegenwoordigt Camera Raw-schema.

```csharp
public sealed class XmpCameraRawPackage : XmpPackage
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [XmpCameraRawPackage](xmpcamerarawpackage)() | Initialiseert een nieuw exemplaar van het[`XmpCameraRawPackage`](../xmpcamerarawpackage) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AutoBrightness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autobrightness) { get; set; } | Haalt de AutoBrightness-waarde op of stelt deze in. Wanneer waar,[`Brightness`](./brightness) wordt automatisch aangepast. |
| [AutoContrast](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autocontrast) { get; set; } | Hiermee wordt de AutoContrast-waarde opgehaald of ingesteld. Indien waar, wordt "Contrast" automatisch aangepast. |
| [AutoExposure](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autoexposure) { get; set; } | Haalt of stelt de waarde voor automatische belichting in. Indien waar, wordt "Belichting" automatisch aangepast. |
| [AutoShadows](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autoshadows) { get; set; } | Hiermee wordt de AutoShadows-waarde opgehaald of ingesteld. Indien waar, wordt "Schaduwen" automatisch aangepast. |
| [BlueHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/bluehue) { get; set; } | Haalt de BlueHue-waarde op of stelt deze in. Null indien ongedefinieerd. |
| [BlueSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/bluesaturation) { get; set; } | Haalt of stelt de BlueSaturation in. Null indien ongedefinieerd. |
| [Brightness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/brightness) { get; set; } | Haalt de helderheidswaarde op of stelt deze in. Null indien ongedefinieerd. |
| [CameraProfile](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cameraprofile) { get; set; } | Haalt de CameraProfile-waarde op of stelt deze in. |
| [ChromaticAberrationB](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/chromaticaberrationb) { get; set; } | Haalt of stelt de instelling "Chromatische aberratie, blauwe/gele franjes corrigeren" in. Null indien ongedefinieerd. |
| [ChromaticAberrationR](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/chromaticaberrationr) { get; set; } | Haalt de instelling "Chromatische aberratie, rode/cyaanranden corrigeren" op of stelt deze in. Null indien ongedefinieerd. |
| [ColorNoiseReduction](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/colornoisereduction) { get; set; } | Hiermee haalt u de instelling Kleurruisonderdrukking op of stelt u deze in. Bereik 0 tot 100. |
| [Contrast](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/contrast) { get; set; } | Haalt of stelt de contrastinstelling in. Bereik -50 tot 100. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [CropAngle](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropangle) { get; set; } | Haalt de CropAngle-instelling op of stelt deze in. Als HasCrop waar is, hoek van de bijsnijdrechthoek. |
| [CropBottom](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropbottom) { get; set; } | Haalt of stelt de instelling CropBottom in. Als HasCrop waar is, onderkant van de bijsnijdrechthoek. |
| [CropHeight](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropheight) { get; set; } | Hiermee wordt de hoogte van de resulterende bijgesneden afbeelding opgehaald of ingesteld[`CropUnits`](./cropunits) eenheden. |
| [CropLeft](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropleft) { get; set; } | Hiermee wordt de instelling CropLeft opgehaald of ingesteld. Als HasCrop waar is, links van de bijsnijdrechthoek. |
| [CropRight](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropright) { get; set; } | Haalt of stelt de instelling CropRight in. Als HasCrop waar is, rechts van de bijsnijdrechthoek. |
| [CropTop](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/croptop) { get; set; } | Haalt of stelt de CropTop-instelling in. Als HasCrop waar is, bovenkant van de bijsnijdrechthoek. |
| [CropUnits](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropunits) { get; set; } | Krijgt of stelt eenheden in voor[`CropWidth`](./cropwidth) En[`CropHeight`](./cropheight) . |
| [CropWidth](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropwidth) { get; set; } | Hiermee wordt de breedte van de resulterende bijgesneden afbeelding opgehaald of ingesteld[`CropUnits`](./cropunits) eenheden. |
| [Exposure](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/exposure) { get; set; } | Haalt of stelt de belichtingsinstelling in. |
| [GreenHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/greenhue) { get; set; } | Haalt of stelt de Groene Tint instelling in. Bereik -100 tot 100. |
| [GreenSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/greensaturation) { get; set; } | Hiermee wordt de instelling Groenverzadiging opgehaald of ingesteld. Bereik -100 tot 100. |
| [HasCrop](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/hascrop) { get; set; } | Haalt de HasCrop-waarde op of stelt deze in. Indien waar, heeft de afbeelding een bijsnijdrechthoek. |
| [HasSettings](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/hassettings) { get; set; } | Haalt de HasSettings-waarde op of stelt deze in. Indien waar, niet-standaard Camera Raw-instellingen. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [LuminanceSmoothing](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/luminancesmoothing) { get; set; } | Hiermee wordt de LuminanceSmoothing-instelling opgehaald of ingesteld. Bereik 0 tot 100. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Haalt de naamruimte-URI op. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Haalt het xmlns-voorvoegsel op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [RawFileName](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/rawfilename) { get; set; } | Haalt de bestandsnaam voor een onbewerkt bestand op of stelt deze in (geen volledig pad). |
| [RedHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/redhue) { get; set; } | Haalt of stelt de Rode Tint instelling in. Bereik -100 tot 100. |
| [RedSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/redsaturation) { get; set; } | Haalt of stelt de instelling Roodverzadiging in. Bereik -100 tot 100. |
| [Saturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/saturation) { get; set; } | Haalt of stelt de verzadigingsinstelling in. Bereik -100 tot 100. |
| [Shadows](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/shadows) { get; set; } | Hiermee wordt de instelling Schaduwen opgehaald of ingesteld. Bereik 0 tot 100. |
| [ShadowTint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/shadowtint) { get; set; } | Hiermee wordt de ShadowTint-instelling opgehaald of ingesteld. Bereik -100 tot 100. |
| [Sharpness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/sharpness) { get; set; } | Haalt de scherpte-instelling op of stelt deze in. Bereik 0 tot 100. |
| [Temperature](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/temperature) { get; set; } | Haalt of stelt de temperatuurinstelling in. Bereik 2000 tot 50000. |
| [Tint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/tint) { get; set; } | Haalt de Tint-instelling op of stelt deze in. Bereik -150 tot 150. |
| [Version](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/version) { get; set; } | Haalt de versie van de Camera Raw-plug-in op of stelt deze in. |
| [VignetteAmount](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/vignetteamount) { get; set; } | Hiermee wordt de instelling Vignette Amount opgehaald of ingesteld. Bereik -100 tot 100. |
| [VignetteMidpoint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/vignettemidpoint) { get; set; } | Haalt of stelt de Vignettering Midpoint-instelling in. Bereik 0 tot 100. |
| [WhiteBalance](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/whitebalance) { get; } | Krijgt witbalansinstelling. Gebruik[`SetWhiteBalance`](./setwhitebalance) om de witbalanswaarde in te stellen. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Haalt de XML-naamruimte op. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Verwijdert alle XMP-eigenschappen. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Converteert de XMP-waarde naar de XML-weergave. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Verwijdert de eigenschap met de opgegeven naam. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Stelt booleaanse eigenschap in. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | setsDateTime eigendom. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Stelt dubbele eigenschap in. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Stelt integer-eigenschap in. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/set#set_7)(string, string) | Voegt tekenreekseigenschap toe. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Stelt de waarde in die is overgenomen van[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Stelt de waarde in die is overgenomen van[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Stelt de waarde in die is overgenomen van[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [SetWhiteBalance](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/setwhitebalance)(XmpWhiteBalance) | Stelt de witbalans in. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Zie ook

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* naamruimte [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
