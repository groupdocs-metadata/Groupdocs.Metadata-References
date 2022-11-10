---
title: TorrentPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente les métadonnées du fichier descripteur de torrent. Veuillez trouver plus dinformations surhttps//en.wikipedia.org/wiki/Torrent_filehttps//en.wikipedia.org/wiki/Torrent_file .
type: docs
weight: 2190
url: /fr/net/groupdocs.metadata.formats.peer2peer/torrentpackage/
---
## TorrentPackage class

Représente les métadonnées du fichier descripteur de torrent. Veuillez trouver plus d'informations sur[https://en.wikipedia.org/wiki/Torrent_file](https://en.wikipedia.org/wiki/Torrent_file) .

```csharp
public sealed class TorrentPackage : CustomPackage
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Announce](../../groupdocs.metadata.formats.peer2peer/torrentpackage/announce) { get; set; } | Obtient ou définit l'URL du tracker. |
| [Comment](../../groupdocs.metadata.formats.peer2peer/torrentpackage/comment) { get; set; } | Obtient ou définit le commentaire de l'auteur. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [CreatedBy](../../groupdocs.metadata.formats.peer2peer/torrentpackage/createdby) { get; set; } | Obtient ou définit le nom et la version du programme utilisé pour créer le torrent. |
| [CreationDate](../../groupdocs.metadata.formats.peer2peer/torrentpackage/creationdate) { get; set; } | Obtient ou définit la date de création du torrent. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [PieceLength](../../groupdocs.metadata.formats.peer2peer/torrentpackage/piecelength) { get; } | Obtient le nombre d'octets dans chaque morceau. Pour plus d'informations, veuillez consulter . |
| [Pieces](../../groupdocs.metadata.formats.peer2peer/torrentpackage/pieces) { get; } | Obtient un tableau d'octets composé de la concaténation de toutes les valeurs de hachage SHA1 de 20 octets, une par pièce. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [SharedFiles](../../groupdocs.metadata.formats.peer2peer/torrentpackage/sharedfiles) { get; } | Obtient un tableau contenant les entrées d'informations sur les fichiers partagés. |

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

* [Travailler avec des fichiers TORRENT](https://docs.groupdocs.com/display/metadatanet/Working+with+TORRENT+files)

### Voir également

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espace de noms [GroupDocs.Metadata.Formats.Peer2Peer](../../groupdocs.metadata.formats.peer2peer)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
