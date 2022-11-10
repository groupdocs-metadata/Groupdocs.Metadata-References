---
title: PresentationInspectionPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Contient des informations sur les parties de présentation qui peuvent être considérées comme des métadonnées dans certains cas.
type: docs
weight: 1080
url: /fr/net/groupdocs.metadata.formats.document/presentationinspectionpackage/
---
## PresentationInspectionPackage class

Contient des informations sur les parties de présentation qui peuvent être considérées comme des métadonnées dans certains cas.

```csharp
public sealed class PresentationInspectionPackage : CustomPackage
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Comments](../../groupdocs.metadata.formats.document/presentationinspectionpackage/comments) { get; } | Obtient un tableau des commentaires. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [HiddenSlides](../../groupdocs.metadata.formats.document/presentationinspectionpackage/hiddenslides) { get; } | Obtient un tableau des diapositives masquées. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ajoute des propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [ClearComments](../../groupdocs.metadata.formats.document/presentationinspectionpackage/clearcomments)() | Supprime tous les commentaires d'utilisateurs détectés de la présentation. |
| [ClearHiddenSlides](../../groupdocs.metadata.formats.document/presentationinspectionpackage/clearhiddenslides)() | Supprime toutes les diapositives masquées détectées de la présentation. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Détermine si le package contient une propriété de métadonnées avec le nom spécifié. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trouve les propriétés de métadonnées satisfaisant le prédicat spécifié. La recherche est récursive, elle affecte donc également tous les packages imbriqués. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/presentationinspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Supprime les propriétés de métadonnées satisfaisant le prédicat spécifié. |
| override [Sanitize](../../groupdocs.metadata.formats.document/presentationinspectionpackage/sanitize)() | Supprime les propriétés de métadonnées inscriptibles du package. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Remarques

**Apprendre encore plus**

* [Utilisation des métadonnées dans les présentations](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Presentations)

### Exemples

Cet exemple de code montre comment nettoyer les propriétés d'inspection dans une présentation.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPpt))
{
    var root = metadata.GetRootPackage<PresentationRootPackage>();

    root.InspectionPackage.ClearComments();
    root.InspectionPackage.ClearHiddenSlides();

    metadata.Save(Constants.OutputPpt);
}
```

### Voir également

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espace de noms [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
