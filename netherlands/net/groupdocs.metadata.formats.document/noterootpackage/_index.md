---
title: NoteRootPackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt het rootpakket dat bedoeld is om te werken met metadata in een elektronisch notitiebestand.
type: docs
weight: 970
url: /nl/net/groupdocs.metadata.formats.document/noterootpackage/
---
## NoteRootPackage class

Vertegenwoordigt het rootpakket dat bedoeld is om te werken met metadata in een elektronisch notitiebestand.

```csharp
public class NoteRootPackage : RootMetadataPackage
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [DocumentStatistics](../../groupdocs.metadata.formats.document/noterootpackage/documentstatistics) { get; } | Haalt het documentstatistiekenpakket op. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Haalt het metadatapakket van het bestandstype op. |
| [InspectionPackage](../../groupdocs.metadata.formats.document/noterootpackage/inspectionpackage) { get; } | Haalt een metadatapakket op met inspectieresultaten voor het document. Het pakket bevat informatie over documentonderdelen die in sommige gevallen als metadata kunnen worden beschouwd. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Opmerkingen

**Kom meer te weten**

* [Werken met metadata in notitieformaten](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Note+formats)

### Voorbeelden

Dit codevoorbeeld laat zien hoe u een notitiedocument inspecteert.

```csharp
using (Metadata metadata = new Metadata(Constants.InputOne))
{
    var root = metadata.GetRootPackage<NoteRootPackage>();

    if (root.InspectionPackage.Pages != null)
    {
        foreach (var page in root.InspectionPackage.Pages)
        {
            Console.WriteLine(page.Title);
            Console.WriteLine(page.Author);
            Console.WriteLine(page.CreationTime);
            Console.WriteLine(page.LastModificationTime);
        }
    }
}
```

### Zie ook

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* naamruimte [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->