---
title: VCardCard
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente une seule carte extraite dun fichier VCard.
type: docs
weight: 650
url: /fr/net/groupdocs.metadata.formats.businesscard/vcardcard/
---
## VCardCard class

Représente une seule carte extraite d'un fichier VCard.

```csharp
public class VCardCard : VCardRecordset
```

## Propriétés

| Nom | La description |
| --- | --- |
| [CalendarRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/calendarrecordset) { get; } | Obtient les enregistrements du calendrier. |
| [CommunicationRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/communicationrecordset) { get; } | Obtient les enregistrements de communication. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [DeliveryAddressingRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/deliveryaddressingrecordset) { get; } | Obtient les enregistrements d'adressage de livraison. |
| [ExplanatoryRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/explanatoryrecordset) { get; } | Obtient les enregistrements explicatifs. |
| [ExtensionRecords](../../groupdocs.metadata.formats.businesscard/vcardcard/extensionrecords) { get; } | Obtient les enregistrements d'extension privés. |
| [GeneralRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/generalrecordset) { get; } | Obtient les enregistrements généraux. |
| [GeographicalRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/geographicalrecordset) { get; } | Obtient les enregistrements géographiques. |
| [IdentificationRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/identificationrecordset) { get; } | Obtient les enregistrements d'identification. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [OrganizationalRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/organizationalrecordset) { get; } | Obtient les enregistrements de l'organisation. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [SecurityRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/securityrecordset) { get; } | Obtient les enregistrements de sécurité. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ajoute des propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Détermine si le package contient une propriété de métadonnées avec le nom spécifié. |
| [FilterByGroup](../../groupdocs.metadata.formats.businesscard/vcardcard/filterbygroup)(string) | Filtre tous les enregistrements vCard par le nom de groupe passé en paramètre. Pour plus d'informations, veuillez consulter le méthode. |
| [FilterHomeTags](../../groupdocs.metadata.formats.businesscard/vcardcard/filterhometags)() | Filtre tous les enregistrements vCard marqués avec la balise HOME. |
| [FilterPreferred](../../groupdocs.metadata.formats.businesscard/vcardcard/filterpreferred)() | Filtre les enregistrements préférés. |
| [FilterWorkTags](../../groupdocs.metadata.formats.businesscard/vcardcard/filterworktags)() | Filtre tous les enregistrements vCard marqués avec la balise WORK. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trouve les propriétés de métadonnées satisfaisant le prédicat spécifié. La recherche est récursive, elle affecte donc également tous les packages imbriqués. |
| [GetAvailableGroups](../../groupdocs.metadata.formats.businesscard/vcardcard/getavailablegroups)() | Obtient les noms de groupe disponibles. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Supprime les propriétés de métadonnées satisfaisant le prédicat spécifié. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Supprime les propriétés de métadonnées inscriptibles du package. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Remarques

**Apprendre encore plus**

* [Travailler avec les métadonnées vCard](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Exemples

Cet exemple montre comment utiliser les filtres de propriété vCard.

```csharp
public static void Run()
{
    using (Metadata metadata = new Metadata(Constants.InputVcf))
    {
        var root = metadata.GetRootPackage<VCardRootPackage>();

        foreach (var vCard in root.VCardPackage.Cards)
        {
            // Imprimer les numéros de téléphone professionnels et les e-mails professionnels préférés
            var filtered = vCard.FilterWorkTags().FilterPreferred();
            PrintArray(filtered.CommunicationRecordset.Telephones);
            PrintArray(filtered.CommunicationRecordset.Emails);
        }
    }
}

private static void PrintArray(string[] values)
{
    if (values != null)
    {
        foreach (string value in values)
        {
            Console.WriteLine(value);
        }
    }
}
```

### Voir également

* class [VCardRecordset](../vcardrecordset)
* espace de noms [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
