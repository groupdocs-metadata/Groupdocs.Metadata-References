---
title: MatroskaVideoTrack
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente les métadonnées vidéo dans une vidéo Matroska.
type: docs
weight: 2610
url: /fr/net/groupdocs.metadata.formats.video/matroskavideotrack/
---
## MatroskaVideoTrack class

Représente les métadonnées vidéo dans une vidéo Matroska.

```csharp
public class MatroskaVideoTrack : MatroskaTrack
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AlphaMode](../../groupdocs.metadata.formats.video/matroskavideotrack/alphamode) { get; } | Obtient le mode vidéo alpha. La présence de cet élément indique que l'élément BlockAdditional peut contenir des données Alpha. |
| [CodecID](../../groupdocs.metadata.formats.video/matroskatrack/codecid) { get; } | Obtient un ID correspondant au codec. |
| [CodecName](../../groupdocs.metadata.formats.video/matroskatrack/codecname) { get; } | Obtient une chaîne lisible par l'homme spécifiant le codec. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [DefaultDuration](../../groupdocs.metadata.formats.video/matroskatrack/defaultduration) { get; } | Obtient le nombre de nanosecondes (non mis à l'échelle via[`TimecodeScale`](../matroskasegment/timecodescale) ) par image. |
| [DisplayHeight](../../groupdocs.metadata.formats.video/matroskavideotrack/displayheight) { get; } | Obtient la hauteur des images vidéo à afficher. S'applique à l'image vidéo après recadrage (PixelCrop* Elements). |
| [DisplayUnit](../../groupdocs.metadata.formats.video/matroskavideotrack/displayunit) { get; } | Obtient le comment[`DisplayWidth`](./displaywidth) et[`DisplayHeight`](./displayheight) sont interprétés. |
| [DisplayWidth](../../groupdocs.metadata.formats.video/matroskavideotrack/displaywidth) { get; } | Obtient la largeur des images vidéo à afficher. S'applique à l'image vidéo après recadrage (PixelCrop* Elements). |
| [FieldOrder](../../groupdocs.metadata.formats.video/matroskavideotrack/fieldorder) { get; } | Gets déclare l'ordre des champs de la vidéo. Si FlagInterlaced n'est pas défini sur 1, cet élément DOIT être ignoré. |
| [FlagEnabled](../../groupdocs.metadata.formats.video/matroskatrack/flagenabled) { get; } | Obtient le drapeau activé, vrai si la piste est utilisable. |
| [FlagInterlaced](../../groupdocs.metadata.formats.video/matroskavideotrack/flaginterlaced) { get; } | Obtient un indicateur pour déclarer si la vidéo est connue pour être progressive ou entrelacée et, le cas échéant, pour déclarer des détails sur l'entrelacement. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [Language](../../groupdocs.metadata.formats.video/matroskatrack/language) { get; } | Obtient la langue de la piste dans le formulaire de langues Matroska. Cet élément DOIT être ignoré si le[`LanguageIetf`](../matroskatrack/languageietf) L'élément est utilisé dans le même TrackEntry. |
| [LanguageIetf](../../groupdocs.metadata.formats.video/matroskatrack/languageietf) { get; } | Obtient la langue de la piste selon BCP 47 et en utilisant le registre des sous-étiquettes de langue IANA. Si cet élément est utilisé, alors tout[`Language`](../matroskatrack/language) Les éléments utilisés dans le même TrackEntry DOIVENT être ignorés. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [Name](../../groupdocs.metadata.formats.video/matroskatrack/name) { get; } | Obtient le nom de la piste lisible par l'homme. |
| [PixelCropBottom](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropbottom) { get; } | Obtient le nombre de pixels vidéo à supprimer en bas de l'image. |
| [PixelCropLeft](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropleft) { get; } | Obtient le nombre de pixels vidéo à supprimer à gauche de l'image. |
| [PixelCropRight](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropright) { get; } | Obtient le nombre de pixels vidéo à supprimer à droite de l'image. |
| [PixelCropTop](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcroptop) { get; } | Obtient le nombre de pixels vidéo à supprimer en haut de l'image. |
| [PixelHeight](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelheight) { get; } | Obtient la hauteur des images vidéo encodées en pixels. |
| [PixelWidth](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelwidth) { get; } | Obtient la largeur des images vidéo encodées en pixels. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [StereoMode](../../groupdocs.metadata.formats.video/matroskavideotrack/stereomode) { get; } | Obtient le mode vidéo stéréo-3D. |
| [TrackNumber](../../groupdocs.metadata.formats.video/matroskatrack/tracknumber) { get; } | Obtient le numéro de piste tel qu'utilisé dans l'en-tête de bloc. L'utilisation de plus de 127 pistes n'est pas encouragée, bien que la conception autorise un nombre illimité. |
| [TrackType](../../groupdocs.metadata.formats.video/matroskatrack/tracktype) { get; } | Obtient le type de piste. |
| [TrackUid](../../groupdocs.metadata.formats.video/matroskatrack/trackuid) { get; } | Obtient l'identifiant unique pour identifier la piste. Cela DEVRAIT rester le même lors de la copie directe en flux de la piste vers un autre fichier. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ajoute des propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Détermine si le package contient une propriété de métadonnées avec le nom spécifié. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trouve les propriétés de métadonnées satisfaisant le prédicat spécifié. La recherche est récursive, elle affecte donc également tous les packages imbriqués. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Supprime les propriétés de métadonnées satisfaisant le prédicat spécifié. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Supprime les propriétés de métadonnées inscriptibles du package. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Remarques

**Apprendre encore plus**

* [Utilisation des métadonnées dans les fichiers Matroska (MKV)](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### Voir également

* class [MatroskaTrack](../matroskatrack)
* espace de noms [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
