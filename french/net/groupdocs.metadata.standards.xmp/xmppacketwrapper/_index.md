---
title: XmpPacketWrapper
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Contient un package XMP sérialisé comprenant un entête et une fin. Un wrapper composé dune paire dinstructions de traitement XML PI peut être placé autour de lélément rdfRDF.
type: docs
weight: 3500
url: /fr/net/groupdocs.metadata.standards.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

Contient un package XMP sérialisé comprenant un en-tête et une fin. Un wrapper composé d'une paire d'instructions de traitement XML (PI) peut être placé autour de l'élément rdf:RDF.

```csharp
public class XmpPacketWrapper : MetadataPackage, IXmpType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper#constructor)() | Initialise une nouvelle instance du[`XmpPacketWrapper`](../xmppacketwrapper) classe. |
| [XmpPacketWrapper](xmppacketwrapper#constructor_1)(XmpHeaderPI, XmpTrailerPI, XmpMeta) | Initialise une nouvelle instance du[`XmpPacketWrapper`](../xmppacketwrapper) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [HeaderPI](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/headerpi) { get; set; } | Obtient ou définit l'instruction de traitement d'en-tête. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtient le[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) avec le nom spécifié. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [Meta](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/meta) { get; set; } | Obtient ou définit la méta XMP. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [PackageCount](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/packagecount) { get; } | Obtient le nombre de packages à l'intérieur de la structure XMP. |
| [Packages](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/packages) { get; } | Obtient un tableau de[`XmpPackage`](../xmppackage) dans XMP. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [Schemes](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/schemes) { get; } | Fournit un accès aux schémas XMP connus. |
| [TrailerPI](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/trailerpi) { get; set; } | Obtient ou définit l'instruction de traitement de fin. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddPackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/addpackage)(XmpPackage) | Ajoute le package. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ajoute des propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [ClearPackages](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/clearpackages)() | Supprime tout[`XmpPackage`](../xmppackage) dans XMP. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Détermine si le package contient une propriété de métadonnées avec le nom spécifié. |
| [ContainsPackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/containspackage)(string) | Détermine si le package existe dans le wrapper XMP. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trouve les propriétés de métadonnées satisfaisant le prédicat spécifié. La recherche est récursive, elle affecte donc également tous les packages imbriqués. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| [GetPackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/getpackage)(string) | Obtient le package par espace de noms uri. |
| [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/getxmprepresentation)() | Renvoie la valeur contenue dans la chaîne au format XMP. |
| [RemovePackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/removepackage)(XmpPackage) | Supprime le package spécifié. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Supprime les propriétés de métadonnées satisfaisant le prédicat spécifié. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Supprime les propriétés de métadonnées inscriptibles du package. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Remarques

**Apprendre encore plus**

* [Utilisation des métadonnées XMP](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Exemples

Cet exemple montre comment mettre à jour les propriétés des métadonnées XMP.

```csharp
using (Metadata metadata = new Metadata(Constants.GifWithXmp))
{
    IXmp root = metadata.GetRootPackage() as IXmp;
    if (root != null && root.XmpPackage != null)
    {
        // s'il n'y a pas un tel schéma dans le package XMP, nous devrions le créer
        if (root.XmpPackage.Schemes.DublinCore == null)
        {
            root.XmpPackage.Schemes.DublinCore = new XmpDublinCorePackage();
        }
        root.XmpPackage.Schemes.DublinCore.Format = "image/gif";
        root.XmpPackage.Schemes.DublinCore.SetRights("Copyright (C) 2011-2022 GroupDocs. All Rights Reserved");
        root.XmpPackage.Schemes.DublinCore.SetSubject("test");

        if (root.XmpPackage.Schemes.CameraRaw == null)
        {
            root.XmpPackage.Schemes.CameraRaw = new XmpCameraRawPackage();
        }
        root.XmpPackage.Schemes.CameraRaw.Shadows = 50;
        root.XmpPackage.Schemes.CameraRaw.AutoBrightness = true;
        root.XmpPackage.Schemes.CameraRaw.AutoExposure = true;
        root.XmpPackage.Schemes.CameraRaw.CameraProfile = "test";
        root.XmpPackage.Schemes.CameraRaw.Exposure = 0.0001;

        // Si vous ne souhaitez pas conserver les anciennes valeurs, remplacez simplement l'ensemble du schéma
        root.XmpPackage.Schemes.XmpBasic = new XmpBasicPackage();
        root.XmpPackage.Schemes.XmpBasic.CreateDate = DateTime.Today;
        root.XmpPackage.Schemes.XmpBasic.BaseUrl = "https://groupdocs.com" ;
        root.XmpPackage.Schemes.XmpBasic.Rating = 5;

        root.XmpPackage.Schemes.BasicJobTicket = new XmpBasicJobTicketPackage();

        // Définit une propriété de type complexe
        root.XmpPackage.Schemes.BasicJobTicket.Jobs = new[]
        {
            new XmpJob
            {
                ID = "1",
                Name = "test job",
                Url = "https://groupdocs.com"
            },
        };

        // ... 

        metadata.Save(Constants.OutputGif);
    }
}
```

### Voir également

* class [MetadataPackage](../../groupdocs.metadata.common/metadatapackage)
* interface [IXmpType](../ixmptype)
* espace de noms [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
