---
title: ID3V2Tag
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente une balise ID3v2. Veuillez trouver plus dinformations surhttps//en.wikipedia.org/wiki/ID3ID3v2https//en.wikipedia.org/wiki/ID3ID3v2 .
type: docs
weight: 490
url: /fr/net/groupdocs.metadata.formats.audio/id3v2tag/
---
## ID3V2Tag class

Représente une balise ID3v2. Veuillez trouver plus d'informations sur[https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2) .

```csharp
public sealed class ID3V2Tag : ID3Tag
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ID3V2Tag](id3v2tag)() | Initialise une nouvelle instance du[`ID3V2Tag`](../id3v2tag) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v2tag/album) { get; set; } | Obtient ou définit le titre de l'album/film/émission. Cette valeur est représentée par le cadre TALB. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v2tag/artist) { get; set; } | Obtient ou définit le(s) artiste(s) principal(aux)/interprète(s) principal(aux)/soliste(s)/groupe d'interprétation. Cette valeur est représentée par le cadre TPE1. |
| [AttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/attachedpictures) { get; set; } | Obtient ou définit les images jointes directement liées au fichier audio. Cette valeur est représentée par le cadre APIC. |
| [Band](../../groupdocs.metadata.formats.audio/id3v2tag/band) { get; set; } | Obtient ou définit le groupe/l'orchestre/l'accompagnement. Cette valeur est représentée par la trame TPE2. |
| [BitsPerMinute](../../groupdocs.metadata.formats.audio/id3v2tag/bitsperminute) { get; set; } | Obtient ou définit le nombre de battements par minute dans la partie principale de l'audio. Cette valeur est représentée par l'image TBPM. |
| [Comments](../../groupdocs.metadata.formats.audio/id3v2tag/comments) { get; set; } | Obtient ou définit les commentaires de l'utilisateur. Cette valeur est représentée par le cadre COMM. Le cadre est destiné à tout type d'informations en texte intégral qui ne rentrent dans aucun autre cadre. |
| [Composers](../../groupdocs.metadata.formats.audio/id3v2tag/composers) { get; set; } | Obtient ou définit les compositeurs. Les noms sont séparés par le caractère "/". Cette valeur est représentée par la trame TCOM. |
| [ContentType](../../groupdocs.metadata.formats.audio/id3v2tag/contenttype) { get; set; } | Obtient ou définit le type de contenu. Cette valeur est représentée par la trame TCON. |
| [Copyright](../../groupdocs.metadata.formats.audio/id3v2tag/copyright) { get; set; } | Obtient ou définit le message de copyright. Cette valeur est représentée par la trame TCPP. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [Date](../../groupdocs.metadata.formats.audio/id3v2tag/date) { get; set; } | Obtient ou définit une chaîne numérique au format JJMM contenant la date de l'enregistrement. Ce champ comporte toujours quatre caractères. Cette valeur est représentée par la trame TDAT. |
| [EncodedBy](../../groupdocs.metadata.formats.audio/id3v2tag/encodedby) { get; set; } | Obtient ou définit le nom de la personne ou de l'organisation qui a encodé le fichier audio. Cette valeur est représentée par le cadre TENC. |
| [Isrc](../../groupdocs.metadata.formats.audio/id3v2tag/isrc) { get; set; } | Obtient ou définit le code ISRC (International Standard Recording Code) (12 caractères). Cette valeur est représentée par la trame TSRC. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [LengthInMilliseconds](../../groupdocs.metadata.formats.audio/id3v2tag/lengthinmilliseconds) { get; set; } | Obtient ou définit la longueur du fichier audio en millisecondes, représentée sous la forme d'une chaîne numérique. Cette valeur est représentée par la trame TLEN. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [MusicalKey](../../groupdocs.metadata.formats.audio/id3v2tag/musicalkey) { get; set; } | Obtient ou définit la tonalité musicale dans laquelle le son commence. Cette valeur est représentée par le cadre TKEY. |
| [OriginalAlbum](../../groupdocs.metadata.formats.audio/id3v2tag/originalalbum) { get; set; } | Obtient ou définit le titre original de l'album/film/émission. Cette valeur est représentée par le cadre TOAL. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [Publisher](../../groupdocs.metadata.formats.audio/id3v2tag/publisher) { get; set; } | Obtient ou définit le nom du label ou de l'éditeur. Cette valeur est représentée par le cadre TPUB. |
| [SizeInBytes](../../groupdocs.metadata.formats.audio/id3v2tag/sizeinbytes) { get; set; } | Obtient ou définit la taille du fichier audio en octets, à l'exclusion de la balise ID3v2, représentée sous la forme d'une chaîne numérique. Cette valeur est représentée par le cadre TSIZ. |
| [SoftwareHardware](../../groupdocs.metadata.formats.audio/id3v2tag/softwarehardware) { get; set; } | Obtient ou définit l'encodeur audio utilisé et ses paramètres lorsque le fichier a été encodé. Cette valeur est représentée par la trame TSSE. |
| [Subtitle](../../groupdocs.metadata.formats.audio/id3v2tag/subtitle) { get; set; } | Obtient ou définit le raffinement des sous-titres/descriptions. Cette valeur est représentée par le cadre TIT3. |
| [TagSize](../../groupdocs.metadata.formats.audio/id3v2tag/tagsize) { get; } | Obtient la taille de la balise. |
| [Time](../../groupdocs.metadata.formats.audio/id3v2tag/time) { get; set; } | Obtient ou définit une chaîne numérique au format HHMM contenant l'heure de l'enregistrement. Ce champ comporte toujours quatre caractères. Cette valeur est représentée par la trame TIME. |
| [Title](../../groupdocs.metadata.formats.audio/id3v2tag/title) { get; set; } | Obtient ou définit le titre/le nom de la chanson/la description du contenu. Cette valeur est représentée par le cadre TIT2. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v2tag/tracknumber) { get; set; } | Obtient ou définit une chaîne numérique contenant le numéro d'ordre du fichier audio sur son enregistrement d'origine. Cette valeur est représentée par la trame TRCK. |
| [TrackPlayCounter](../../groupdocs.metadata.formats.audio/id3v2tag/trackplaycounter) { get; } | Obtient le nombre de fois que le fichier a été lu. Cette valeur est représentée par la trame PCNT. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v2tag/version) { get; } | Obtient la version ID3. |
| [Year](../../groupdocs.metadata.formats.audio/id3v2tag/year) { get; set; } | Obtient ou définit une chaîne numérique avec une année d'enregistrement. Cette trame comporte toujours quatre caractères (jusqu'à l'an 10000). Cette valeur est représentée par la trame TYER. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Add](../../groupdocs.metadata.formats.audio/id3v2tag/add)(ID3V2TagFrame) | Ajoute un cadre au tag. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ajoute des propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Clear](../../groupdocs.metadata.formats.audio/id3v2tag/clear)(string) | Supprime tous les cadres avec l'identifiant spécifié. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Détermine si le package contient une propriété de métadonnées avec le nom spécifié. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trouve les propriétés de métadonnées satisfaisant le prédicat spécifié. La recherche est récursive, elle affecte donc également tous les packages imbriqués. |
| [Get](../../groupdocs.metadata.formats.audio/id3v2tag/get)(string) | Obtient un tableau de cadres avec l'identifiant spécifié. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| [Remove](../../groupdocs.metadata.formats.audio/id3v2tag/remove)(ID3V2TagFrame) | Supprime le cadre spécifié de la balise. |
| [RemoveAttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/removeattachedpictures)() | Supprime toutes les images jointes stockées dans les cadres APIC. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Supprime les propriétés de métadonnées satisfaisant le prédicat spécifié. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Supprime les propriétés de métadonnées inscriptibles du package. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Set](../../groupdocs.metadata.formats.audio/id3v2tag/set)(ID3V2TagFrame) | Supprime tous les cadres ayant le même identifiant que celui spécifié et ajoute le nouveau cadre à la balise. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| [ToList](../../groupdocs.metadata.formats.audio/id3v2tag/tolist)() | Crée une liste à partir du package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Remarques

**Apprendre encore plus**

* [Gestion de la balise ID3v2](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Exemples

Cet exemple montre comment lire la balise ID3v2 dans un fichier MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V2 != null)
    {
        Console.WriteLine(root.ID3V2.Album);
        Console.WriteLine(root.ID3V2.Artist);
        Console.WriteLine(root.ID3V2.Band);
        Console.WriteLine(root.ID3V2.Title);
        Console.WriteLine(root.ID3V2.Composers);
        Console.WriteLine(root.ID3V2.Copyright);
        Console.WriteLine(root.ID3V2.Publisher);
        Console.WriteLine(root.ID3V2.OriginalAlbum);
        Console.WriteLine(root.ID3V2.MusicalKey);

        if (root.ID3V2.AttachedPictures != null)
        {
            foreach (var attachedPicture in root.ID3V2.AttachedPictures)
            {
                Console.WriteLine(attachedPicture.AttachedPictureType);
                Console.WriteLine(attachedPicture.MimeType);
                Console.WriteLine(attachedPicture.Description);

                // ...
            }
        }

        // ...
    }
}
```

### Voir également

* class [ID3Tag](../id3tag)
* espace de noms [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
