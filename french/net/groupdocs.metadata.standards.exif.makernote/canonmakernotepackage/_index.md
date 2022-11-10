---
title: CanonMakerNotePackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente les métadonnées CANON MakerNote.
type: docs
weight: 2820
url: /fr/net/groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/
---
## CanonMakerNotePackage class

Représente les métadonnées CANON MakerNote.

```csharp
public sealed class CanonMakerNotePackage : MakerNotePackage
```

## Propriétés

| Nom | La description |
| --- | --- |
| [CameraSettings](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/camerasettings) { get; } | Obtient les paramètres de la caméra. |
| [CanonFileLength](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/canonfilelength) { get; } | Obtient la longueur du fichier canon. |
| [CanonFirmwareVersion](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/canonfirmwareversion) { get; } | Obtient la version du micrologiciel canon. |
| [CanonImageType](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/canonimagetype) { get; } | Obtient le type d'image Canon. |
| [CanonModelID](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/canonmodelid) { get; } | Obtient l'identifiant du modèle canon. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [FileNumber](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/filenumber) { get; } | Obtient le numéro de fichier. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Obtient la balise TIFF avec l'identifiant spécifié. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [OwnerName](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/ownername) { get; } | Obtient le nom du propriétaire. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [SerialNumber](../../groupdocs.metadata.standards.exif.makernote/canonmakernotepackage/serialnumber) { get; } | Obtient le numéro de série. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ajoute des propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Supprime toutes les balises TIFF stockées dans le package. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Détermine si le package contient une propriété de métadonnées avec le nom spécifié. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trouve les propriétés de métadonnées satisfaisant le prédicat spécifié. La recherche est récursive, elle affecte donc également tous les packages imbriqués. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Supprime la propriété avec l'identifiant spécifié. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Supprime les propriétés de métadonnées satisfaisant le prédicat spécifié. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Supprime les propriétés de métadonnées inscriptibles du package. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Ajoute ou remplace la balise spécifiée. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Crée une liste à partir du package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Voir également

* class [MakerNotePackage](../makernotepackage)
* espace de noms [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
