---
title: IptcRecordSet
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente une collection denregistrements IPTC.
type: docs
weight: 2940
url: /fr/net/groupdocs.metadata.standards.iptc/iptcrecordset/
---
## IptcRecordSet class

Représente une collection d'enregistrements IPTC.

```csharp
public sealed class IptcRecordSet : CustomPackage
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [IptcRecordSet](iptcrecordset#constructor)() | Initialise une nouvelle instance du[`IptcRecordSet`](../iptcrecordset) classe. |
| [IptcRecordSet](iptcrecordset#constructor_1)(IptcDataSet[]) | Initialise une nouvelle instance du[`IptcRecordSet`](../iptcrecordset) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [ApplicationRecord](../../groupdocs.metadata.standards.iptc/iptcrecordset/applicationrecord) { get; set; } | Obtient ou définit l'enregistrement d'application. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [EnvelopeRecord](../../groupdocs.metadata.standards.iptc/iptcrecordset/enveloperecord) { get; set; } | Obtient ou définit l'enregistrement d'enveloppe. |
| [Item](../../groupdocs.metadata.standards.iptc/iptcrecordset/item) { get; } | Obtient le[`IptcRecord`](../iptcrecord) avec le numéro spécifié. (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Add](../../groupdocs.metadata.standards.iptc/iptcrecordset/add)(IptcDataSet) | Ajoute le dataSet spécifié à l'enregistrement approprié. Le dataSet est considéré comme répétable si un dataSet avec le numéro spécifié existe déjà. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ajoute des propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Clear](../../groupdocs.metadata.standards.iptc/iptcrecordset/clear)() | Supprime tous les enregistrements de la collection. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Détermine si le package contient une propriété de métadonnées avec le nom spécifié. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trouve les propriétés de métadonnées satisfaisant le prédicat spécifié. La recherche est récursive, elle affecte donc également tous les packages imbriqués. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| [Remove](../../groupdocs.metadata.standards.iptc/iptcrecordset/remove#remove)(byte) | Supprime l'enregistrement avec le numéro d'enregistrement spécifié. |
| [Remove](../../groupdocs.metadata.standards.iptc/iptcrecordset/remove#remove_1)(byte, byte) | Supprime le dataSet avec l'enregistrement et le numéro de dataSet spécifiés. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Supprime les propriétés de métadonnées satisfaisant le prédicat spécifié. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Supprime les propriétés de métadonnées inscriptibles du package. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Set](../../groupdocs.metadata.standards.iptc/iptcrecordset/set)(IptcDataSet) | Ajoute ou met à jour le dataSet spécifié dans l'enregistrement approprié. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| [ToDataSetList](../../groupdocs.metadata.standards.iptc/iptcrecordset/todatasetlist)() | Crée une liste d'ensembles de données à partir du package. |
| [ToList](../../groupdocs.metadata.standards.iptc/iptcrecordset/tolist)() | Crée une liste à partir du package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Remarques

**Apprendre encore plus**

* [Utilisation des métadonnées IPTC IIM](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Exemples

Cet exemple de code montre comment mettre à jour les propriétés de base des métadonnées IPTC.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IIptc root = metadata.GetRootPackage() as IIptc;
    if (root != null)
    {
        // Définit le package IPTC s'il est manquant
        if (root.IptcPackage == null)
        {
            root.IptcPackage = new IptcRecordSet();
        }

        if (root.IptcPackage.EnvelopeRecord == null)
        {
            root.IptcPackage.EnvelopeRecord = new IptcEnvelopeRecord();
        }

        root.IptcPackage.EnvelopeRecord.DateSent = DateTime.Now;
        root.IptcPackage.EnvelopeRecord.ProductID = Guid.NewGuid().ToString();

        // ...

        if (root.IptcPackage.ApplicationRecord == null)
        {
            root.IptcPackage.ApplicationRecord = new IptcApplicationRecord();
        }

        root.IptcPackage.ApplicationRecord.ByLine = "GroupDocs";
        root.IptcPackage.ApplicationRecord.Headline = "test";
        root.IptcPackage.ApplicationRecord.ByLineTitle = "code sample";
        root.IptcPackage.ApplicationRecord.ReleaseDate = DateTime.Today;

        // ...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Voir également

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espace de noms [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
