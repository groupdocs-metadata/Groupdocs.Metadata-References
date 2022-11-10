---
title: DiagramPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente un package de métadonnées natif dans un format de diagramme.
type: docs
weight: 890
url: /fr/net/groupdocs.metadata.formats.document/diagrampackage/
---
## DiagramPackage class

Représente un package de métadonnées natif dans un format de diagramme.

```csharp
public class DiagramPackage : DocumentPackage
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AlternateNames](../../groupdocs.metadata.formats.document/diagrampackage/alternatenames) { get; set; } | Obtient ou définit les autres noms du document. Peut être mis à jour uniquement aux formats VDX et VSX. |
| [BuildNumberCreated](../../groupdocs.metadata.formats.document/diagrampackage/buildnumbercreated) { get; } | Obtient le numéro de build complet de l'instance utilisée pour créer le document. |
| [BuildNumberEdited](../../groupdocs.metadata.formats.document/diagrampackage/buildnumberedited) { get; } | Obtient le numéro de build de la dernière instance utilisée pour modifier le document. |
| [Category](../../groupdocs.metadata.formats.document/diagrampackage/category) { get; set; } | Obtient ou définit le texte descriptif du type de dessin, tel qu'un organigramme ou un agencement de bureau. Ce texte peut également être saisi dans l'interface utilisateur de Microsoft Visio dans la zone Catégorie de la boîte de dialogue Propriétés. |
| [Company](../../groupdocs.metadata.formats.document/diagrampackage/company) { get; set; } | Obtient ou définit les informations saisies par l'utilisateur identifiant la société créant le dessin ou la société pour laquelle le dessin est créé. La longueur maximale est de 63 caractères. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [Creator](../../groupdocs.metadata.formats.document/diagrampackage/creator) { get; set; } | Obtient ou définit la personne qui a créé ou mis à jour le fichier. La longueur maximale est de 63 caractères.. |
| [Description](../../groupdocs.metadata.formats.document/diagrampackage/description) { get; set; } | Obtient ou définit une chaîne de texte descriptive pour le document. Utilisez cet élément pour stocker des informations importantes sur le document, telles que son objectif, les modifications récentes ou les modifications en attente. Le maximum est de 191 caractères. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/diagrampackage/hyperlinkbase) { get; set; } | Obtient ou définit le chemin à utiliser pour les liens hypertexte relatifs (liens hypertexte pour lesquels l'emplacement du fichier lié est décrit par rapport au diagramme Microsoft Visio). Par défaut, un chemin de lien hypertexte est relatif au document actuel, sauf si un chemin différent est spécifié dans cet élément. La longueur maximale est de 256 caractères. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [Keywords](../../groupdocs.metadata.formats.document/diagrampackage/keywords) { get; set; } | Obtient ou définit une chaîne de texte qui identifie les rubriques ou d'autres informations importantes sur le fichier, telles que le nom du projet, le nom du client ou le numéro de version. La longueur maximale de la chaîne est de 63 caractères. |
| [Language](../../groupdocs.metadata.formats.document/diagrampackage/language) { get; set; } | Obtient ou définit la langue du document. Peut être mis à jour uniquement dans les formats VSD et VSDX. |
| [Manager](../../groupdocs.metadata.formats.document/diagrampackage/manager) { get; set; } | Obtient ou définit une chaîne de texte entrée par l'utilisateur identifiant la personne en charge du projet ou du service. La longueur maximale est de 63 caractères. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [PreviewPicture](../../groupdocs.metadata.formats.document/diagrampackage/previewpicture) { get; set; } | Obtient ou définit l'image d'aperçu. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [Subject](../../groupdocs.metadata.formats.document/diagrampackage/subject) { get; set; } | Obtient ou définit une chaîne de texte définie par l'utilisateur qui décrit le contenu du document. La longueur maximale est de 63 caractères. |
| [Template](../../groupdocs.metadata.formats.document/diagrampackage/template) { get; set; } | Obtient ou définit une valeur de chaîne spécifiant le nom de fichier du modèle à partir duquel le document a été créé. |
| [TimeCreated](../../groupdocs.metadata.formats.document/diagrampackage/timecreated) { get; set; } | Obtient ou définit une valeur de date et d'heure indiquant quand le document a été créé. |
| [TimeEdited](../../groupdocs.metadata.formats.document/diagrampackage/timeedited) { get; } | Obtient une valeur de date et d'heure indiquant quand le document a été modifié pour la dernière fois. |
| [TimePrinted](../../groupdocs.metadata.formats.document/diagrampackage/timeprinted) { get; } | Obtient une valeur de date et d'heure indiquant quand le document a été imprimé pour la dernière fois. |
| [TimeSaved](../../groupdocs.metadata.formats.document/diagrampackage/timesaved) { get; } | Obtient une valeur de date et d'heure indiquant quand le document a été enregistré pour la dernière fois. |
| [Title](../../groupdocs.metadata.formats.document/diagrampackage/title) { get; set; } | Obtient ou définit une chaîne de texte définie par l'utilisateur qui sert de titre descriptif pour le document. La longueur maximale est de 63 caractères. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ajoute des propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | Supprime toutes les propriétés de métadonnées inscriptibles du package. |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | Supprime toutes les propriétés de métadonnées intégrées. |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | Supprime toutes les propriétés de métadonnées personnalisées. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Détermine si le package contient une propriété de métadonnées avec le nom spécifié. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trouve les propriétés de métadonnées satisfaisant le prédicat spécifié. La recherche est récursive, elle affecte donc également tous les packages imbriqués. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | Supprime une propriété de métadonnées accessible en écriture par le nom spécifié. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Supprime les propriétés de métadonnées satisfaisant le prédicat spécifié. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Supprime les propriétés de métadonnées inscriptibles du package. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set)(string, bool) | Ajoute ou remplace la propriété metadata par le nom spécifié. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_2)(string, DateTime) | Ajoute ou remplace la propriété metadata par le nom spécifié. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_1)(string, double) | Ajoute ou remplace la propriété metadata par le nom spécifié. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_3)(string, string) | Ajoute ou remplace la propriété metadata par le nom spécifié. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Remarques

**Apprendre encore plus**

* [Utilisation des métadonnées dans les diagrammes](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### Exemples

Cet exemple de code montre comment extraire les propriétés de métadonnées intégrées d'un diagramme.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.DocumentProperties.Creator);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.TimeCreated);
    Console.WriteLine(root.DocumentProperties.Category);

    // ... 
}
```

### Voir également

* class [DocumentPackage](../documentpackage)
* espace de noms [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
