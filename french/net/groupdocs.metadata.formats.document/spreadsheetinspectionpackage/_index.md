---
title: SpreadsheetInspectionPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Contient des informations sur les parties de feuille de calcul qui peuvent être considérées comme des métadonnées dans certains cas.
type: docs
weight: 1190
url: /fr/net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/
---
## SpreadsheetInspectionPackage class

Contient des informations sur les parties de feuille de calcul qui peuvent être considérées comme des métadonnées dans certains cas.

```csharp
public sealed class SpreadsheetInspectionPackage : CustomPackage
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Comments](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/comments) { get; } | Obtient un tableau des commentaires de l'utilisateur. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/digitalsignatures) { get; } | Obtient un tableau de signatures numériques présentées dans le document. |
| [HiddenSheets](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/hiddensheets) { get; } | Obtient un tableau des feuilles masquées. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ajoute des propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [ClearComments](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/clearcomments)() | Supprime tous les commentaires d'utilisateurs détectés de la feuille de calcul. |
| [ClearDigitalSignatures](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/cleardigitalsignatures)() | Supprime toutes les signatures numériques détectées de la feuille de calcul. |
| [ClearHiddenSheets](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/clearhiddensheets)() | Supprime toutes les feuilles masquées détectées de la feuille de calcul. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Détermine si le package contient une propriété de métadonnées avec le nom spécifié. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trouve les propriétés de métadonnées satisfaisant le prédicat spécifié. La recherche est récursive, elle affecte donc également tous les packages imbriqués. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Supprime les propriétés de métadonnées satisfaisant le prédicat spécifié. |
| override [Sanitize](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/sanitize)() | Supprime les propriétés de métadonnées inscriptibles du package. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Remarques

**Apprendre encore plus**

* [Utilisation des métadonnées dans les feuilles de calcul](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Spreadsheets)

### Exemples

Cet exemple de code montre comment supprimer les propriétés d'inspection d'une feuille de calcul.

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    var root = metadata.GetRootPackage<SpreadsheetRootPackage>();

    root.InspectionPackage.ClearComments();
    root.InspectionPackage.ClearDigitalSignatures();
    root.InspectionPackage.ClearHiddenSheets();

    metadata.Save(Constants.OutputXlsx);
}
```

### Voir également

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espace de noms [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
