---
title: PdfInspectionPackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Bevat informatie over PDFdocumentonderdelen die in sommige gevallen als metadata kunnen worden beschouwd.
type: docs
weight: 1020
url: /nl/net/groupdocs.metadata.formats.document/pdfinspectionpackage/
---
## PdfInspectionPackage class

Bevat informatie over PDF-documentonderdelen die in sommige gevallen als metadata kunnen worden beschouwd.

```csharp
public sealed class PdfInspectionPackage : CustomPackage
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Annotations](../../groupdocs.metadata.formats.document/pdfinspectionpackage/annotations) { get; } | Krijgt een array van de annotaties. |
| [Attachments](../../groupdocs.metadata.formats.document/pdfinspectionpackage/attachments) { get; } | Krijgt een array van de bijlagen. |
| [Bookmarks](../../groupdocs.metadata.formats.document/pdfinspectionpackage/bookmarks) { get; } | Krijgt een reeks van de bladwijzers. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/pdfinspectionpackage/digitalsignatures) { get; } | Krijgt een array van de digitale handtekeningen. |
| [Fields](../../groupdocs.metadata.formats.document/pdfinspectionpackage/fields) { get; } | Krijgt een array van de formuliervelden. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [ClearAnnotations](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearannotations)() | Verwijdert alle gedetecteerde annotaties uit het document. |
| [ClearAttachments](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearattachments)() | Verwijdert alle gedetecteerde bijlagen uit het document. |
| [ClearBookmarks](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearbookmarks)() | Verwijdert alle gedetecteerde bladwijzers uit het document. |
| [ClearDigitalSignatures](../../groupdocs.metadata.formats.document/pdfinspectionpackage/cleardigitalsignatures)() | Verwijdert alle gedetecteerde digitale handtekeningen uit het document. |
| [ClearFields](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearfields)() | Verwijdert alle gedetecteerde formuliervelden uit het document. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/pdfinspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| override [Sanitize](../../groupdocs.metadata.formats.document/pdfinspectionpackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Opmerkingen

**Kom meer te weten**

* [Werken met metadata in PDF-documenten](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

### Voorbeelden

Dit codevoorbeeld laat zien hoe u de inspectie-eigenschappen in een PDF-document kunt verwijderen.

```csharp
using (Metadata metadata = new Metadata(Constants.SignedPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    root.InspectionPackage.ClearAnnotations();
    root.InspectionPackage.ClearAttachments();
    root.InspectionPackage.ClearFields();
    root.InspectionPackage.ClearBookmarks();
    root.InspectionPackage.ClearDigitalSignatures();

    metadata.Save(Constants.OutputPdf);
}
```

### Zie ook

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* naamruimte [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
