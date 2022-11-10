---
title: XmpCameraRawPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente le schéma Camera Raw.
type: docs
weight: 3100
url: /fr/net/groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/
---
## XmpCameraRawPackage class

Représente le schéma Camera Raw.

```csharp
public sealed class XmpCameraRawPackage : XmpPackage
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [XmpCameraRawPackage](xmpcamerarawpackage)() | Initialise une nouvelle instance du[`XmpCameraRawPackage`](../xmpcamerarawpackage) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AutoBrightness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autobrightness) { get; set; } | Obtient ou définit la valeur AutoBrightness. Quand c'est vrai,[`Brightness`](./brightness) est automatiquement ajusté. |
| [AutoContrast](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autocontrast) { get; set; } | Obtient ou définit la valeur AutoContrast. Lorsqu'il est vrai, "Contraste" est automatiquement ajusté. |
| [AutoExposure](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autoexposure) { get; set; } | Obtient ou définit la valeur AutoExposure. Lorsqu'il est vrai, "l'exposition" est automatiquement ajustée. |
| [AutoShadows](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autoshadows) { get; set; } | Obtient ou définit la valeur AutoShadows. Lorsque vrai, "Ombres" est automatiquement ajusté. |
| [BlueHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/bluehue) { get; set; } | Obtient ou définit la valeur BlueHue. Null si indéfini. |
| [BlueSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/bluesaturation) { get; set; } | Obtient ou définit la BlueSaturation. Null si indéfini. |
| [Brightness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/brightness) { get; set; } | Obtient ou définit la valeur de luminosité. Null si indéfini. |
| [CameraProfile](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cameraprofile) { get; set; } | Obtient ou définit la valeur CameraProfile. |
| [ChromaticAberrationB](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/chromaticaberrationb) { get; set; } | Obtient ou définit le paramètre "Aberration chromatique, Fix Blue/Yellow Fringe". Null si indéfini. |
| [ChromaticAberrationR](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/chromaticaberrationr) { get; set; } | Obtient ou définit le paramètre "Aberration chromatique, Fix Red/Cyan Fringe". Null si indéfini. |
| [ColorNoiseReduction](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/colornoisereduction) { get; set; } | Obtient ou définit le paramètre de réduction du bruit de couleur. Plage 0 à 100. |
| [Contrast](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/contrast) { get; set; } | Obtient ou définit le paramètre Contraste. Plage -50 à 100. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [CropAngle](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropangle) { get; set; } | Obtient ou définit le paramètre CropAngle. Lorsque HasCrop est vrai, angle du rectangle de recadrage. |
| [CropBottom](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropbottom) { get; set; } | Obtient ou définit le paramètre CropBottom. Lorsque HasCrop est vrai, bas du rectangle de recadrage. |
| [CropHeight](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropheight) { get; set; } | Obtient ou définit la hauteur de l'image recadrée résultante dans[`CropUnits`](./cropunits) unités. |
| [CropLeft](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropleft) { get; set; } | Obtient ou définit le paramètre CropLeft. Lorsque HasCrop est vrai, à gauche du rectangle de recadrage. |
| [CropRight](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropright) { get; set; } | Obtient ou définit le paramètre CropRight. Lorsque HasCrop est vrai, à droite du rectangle de recadrage. |
| [CropTop](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/croptop) { get; set; } | Obtient ou définit le paramètre CropTop. Lorsque HasCrop est vrai, haut du rectangle de recadrage. |
| [CropUnits](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropunits) { get; set; } | Obtient ou définit les unités pour[`CropWidth`](./cropwidth) et[`CropHeight`](./cropheight) . |
| [CropWidth](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropwidth) { get; set; } | Obtient ou définit la largeur de l'image recadrée résultante en[`CropUnits`](./cropunits) unités. |
| [Exposure](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/exposure) { get; set; } | Obtient ou définit le paramètre d'exposition. |
| [GreenHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/greenhue) { get; set; } | Obtient ou définit le paramètre Teinte verte. Plage -100 à 100. |
| [GreenSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/greensaturation) { get; set; } | Obtient ou définit le paramètre Saturation verte. Plage -100 à 100. |
| [HasCrop](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/hascrop) { get; set; } | Obtient ou définit la valeur HasCrop. Lorsque vrai, l'image a un rectangle de recadrage. |
| [HasSettings](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/hassettings) { get; set; } | Obtient ou définit la valeur HasSettings. Lorsque vrai, les paramètres bruts de l'appareil photo ne sont pas ceux par défaut. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [LuminanceSmoothing](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/luminancesmoothing) { get; set; } | Obtient ou définit le paramètre LuminanceSmoothing. Plage 0 à 100. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Obtient l'URI de l'espace de noms. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Récupère le préfixe xmlns. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [RawFileName](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/rawfilename) { get; set; } | Obtient ou définit le nom de fichier pour un fichier brut (pas un chemin complet). |
| [RedHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/redhue) { get; set; } | Obtient ou définit le paramètre Red Hue. Plage -100 à 100. |
| [RedSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/redsaturation) { get; set; } | Obtient ou définit le paramètre Saturation rouge. Plage -100 à 100. |
| [Saturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/saturation) { get; set; } | Obtient ou définit le paramètre Saturation. Plage -100 à 100. |
| [Shadows](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/shadows) { get; set; } | Obtient ou définit le paramètre Ombres. Plage 0 à 100. |
| [ShadowTint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/shadowtint) { get; set; } | Obtient ou définit le paramètre ShadowTint. Plage -100 à 100. |
| [Sharpness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/sharpness) { get; set; } | Obtient ou définit le paramètre Netteté. Plage 0 à 100. |
| [Temperature](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/temperature) { get; set; } | Obtient ou définit le paramètre de température. Plage 2000 à 50000. |
| [Tint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/tint) { get; set; } | Obtient ou définit le paramètre Teinte. Plage -150 à 150. |
| [Version](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/version) { get; set; } | Obtient ou définit la version du plug-in Camera Raw. |
| [VignetteAmount](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/vignetteamount) { get; set; } | Obtient ou définit le paramètre Quantité de vignette. Plage -100 à 100. |
| [VignetteMidpoint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/vignettemidpoint) { get; set; } | Obtient ou définit le paramètre Vignetting Midpoint. Plage 0 à 100. |
| [WhiteBalance](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/whitebalance) { get; } | Obtient le réglage de la balance des blancs. Utilisation[`SetWhiteBalance`](./setwhitebalance) pour définir la valeur de la balance des blancs. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Obtient l'espace de noms XML. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ajoute des propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Supprime toutes les propriétés XMP. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Détermine si le package contient une propriété de métadonnées avec le nom spécifié. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trouve les propriétés de métadonnées satisfaisant le prédicat spécifié. La recherche est récursive, elle affecte donc également tous les packages imbriqués. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Convertit la valeur XMP en représentation XML. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Supprime la propriété avec le nom spécifié. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Supprime les propriétés de métadonnées satisfaisant le prédicat spécifié. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Supprime les propriétés de métadonnées inscriptibles du package. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Définit la propriété booléenne. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | EnsemblesDateTime propriété. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Définit la propriété double. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Définit la propriété entière. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/set#set_7)(string, string) | Ajoute une propriété de chaîne. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Définit la valeur héritée de[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Définit la valeur héritée de[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Définit la valeur héritée de[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| [SetWhiteBalance](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/setwhitebalance)(XmpWhiteBalance) | Définit la balance des blancs. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Voir également

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* espace de noms [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
