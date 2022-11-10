---
title: MpegAudioPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente les métadonnées audio MPEG.
type: docs
weight: 2150
url: /fr/net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/
---
## MpegAudioPackage class

Représente les métadonnées audio MPEG.

```csharp
public sealed class MpegAudioPackage : CustomPackage
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MpegAudioPackage](mpegaudiopackage)() | Initialise une nouvelle instance du[`MpegAudioPackage`](../mpegaudiopackage) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Bitrate](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/bitrate) { get; } | Obtient le débit binaire. |
| [ChannelMode](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/channelmode) { get; } | Obtient le mode du canal. |
| [Copyright](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/copyright) { get; } | Obtient le bit de copyright. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [Emphasis](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/emphasis) { get; } | Obtient l'emphase. |
| [Frequency](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/frequency) { get; } | Obtient la fréquence. |
| [HeaderPosition](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/headerposition) { get; } | Obtient le décalage d'en-tête. |
| [IsOriginal](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/isoriginal) { get; } | Obtient le bit d'origine. |
| [IsProtected](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/isprotected) { get; } | Obtient`vrai` si protégé. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [Layer](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/layer) { get; } | Obtient la description de la couche. Pour un fichier audio MP3, c'est '3'. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [ModeExtensionBits](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/modeextensionbits) { get; } | Obtient les bits d'extension de mode. |
| [MpegAudioVersion](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/mpegaudioversion) { get; } | Obtient la version audio MPEG. Peut être MPEG-1, MPEG-2 etc. |
| [PaddingBit](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/paddingbit) { get; } | Obtient le bit de remplissage. |
| [PrivateBit](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/privatebit) { get; } | Obtient une valeur indiquant si [bit privé]. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |

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

### Exemples

Cet exemple montre comment lire les métadonnées audio MPEG à partir d'un fichier MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    Console.WriteLine(root.MpegAudioPackage.Bitrate);
    Console.WriteLine(root.MpegAudioPackage.ChannelMode);
    Console.WriteLine(root.MpegAudioPackage.Emphasis);
    Console.WriteLine(root.MpegAudioPackage.Frequency);
    Console.WriteLine(root.MpegAudioPackage.HeaderPosition);
    Console.WriteLine(root.MpegAudioPackage.Layer);

    // ...
}
```

### Voir également

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espace de noms [GroupDocs.Metadata.Formats.Mpeg](../../groupdocs.metadata.formats.mpeg)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
