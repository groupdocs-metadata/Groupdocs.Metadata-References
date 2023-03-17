---
title: PdfPackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt native metadata in een PDFdocument.
type: docs
weight: 1030
url: /nl/net/groupdocs.metadata.formats.document/pdfpackage/
---
## PdfPackage class

Vertegenwoordigt native metadata in een PDF-document.

```csharp
public class PdfPackage : DocumentPackage
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/pdfpackage/author) { get; set; } | Haalt de auteur van het document op of stelt deze in. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [CreatedDate](../../groupdocs.metadata.formats.document/pdfpackage/createddate) { get; set; } | Haalt of stelt de datum van documentaanmaak in. |
| [Creator](../../groupdocs.metadata.formats.document/pdfpackage/creator) { get; } | Haalt de maker van het document op. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [Keywords](../../groupdocs.metadata.formats.document/pdfpackage/keywords) { get; set; } | Haalt of stelt de trefwoorden in. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [ModifiedDate](../../groupdocs.metadata.formats.document/pdfpackage/modifieddate) { get; set; } | Haalt of stelt de datum van de laatste wijziging in. |
| [Producer](../../groupdocs.metadata.formats.document/pdfpackage/producer) { get; } | Haalt de documentproducent op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [Subject](../../groupdocs.metadata.formats.document/pdfpackage/subject) { get; set; } | Haalt het onderwerp van het document op of stelt het in. |
| [Title](../../groupdocs.metadata.formats.document/pdfpackage/title) { get; set; } | Haalt de titel van het document op of stelt deze in. |
| [TrappedFlag](../../groupdocs.metadata.formats.document/pdfpackage/trappedflag) { get; set; } | Haalt of stelt de gevangen vlag in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | Verwijdert alle beschrijfbare metadata-eigenschappen uit het pakket. |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | Verwijdert alle ingebouwde metadata-eigenschappen. |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | Verwijdert alle aangepaste metadata-eigenschappen. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | Verwijdert een beschrijfbare metadata-eigenschap met de opgegeven naam. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Set](../../groupdocs.metadata.formats.document/pdfpackage/set)(string, string) | Voegt de metadata-eigenschap toe of vervangt deze door de opgegeven naam. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Opmerkingen

**Kom meer te weten**

* [Werken met metadata in PDF-documenten](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

### Voorbeelden

Dit codefragment laat zien hoe ingebouwde metadata-eigenschappen in een PDF-document kunnen worden bijgewerkt.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedDate = DateTime.Now;
    root.DocumentProperties.Title = "test title";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputPdf);
}
```

### Zie ook

* class [DocumentPackage](../documentpackage)
* naamruimte [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
