---
title: PresentationPackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt een native metadatapakket in een presentatie.
type: docs
weight: 1090
url: /nl/net/groupdocs.metadata.formats.document/presentationpackage/
---
## PresentationPackage class

Vertegenwoordigt een native metadatapakket in een presentatie.

```csharp
public class PresentationPackage : DocumentPackage
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ApplicationTemplate](../../groupdocs.metadata.formats.document/presentationpackage/applicationtemplate) { get; set; } | Haalt of stelt de toepassingssjabloon in. |
| [Author](../../groupdocs.metadata.formats.document/presentationpackage/author) { get; set; } | Haalt de auteur van het document op of stelt deze in. |
| [Category](../../groupdocs.metadata.formats.document/presentationpackage/category) { get; set; } | Haalt of stelt de categorie in. |
| [Comments](../../groupdocs.metadata.formats.document/presentationpackage/comments) { get; set; } | Krijgt of stelt de opmerkingen in. |
| [Company](../../groupdocs.metadata.formats.document/presentationpackage/company) { get; set; } | Krijgt of stelt het bedrijf in. |
| [ContentStatus](../../groupdocs.metadata.formats.document/presentationpackage/contentstatus) { get; set; } | Haalt de status van de inhoud op of stelt deze in. Kan alleen worden bijgewerkt in een PPTX-document. |
| [ContentType](../../groupdocs.metadata.formats.document/presentationpackage/contenttype) { get; set; } | Hiermee wordt het inhoudstype opgehaald of ingesteld. Kan alleen worden bijgewerkt in een PPTX-document. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [CreatedTime](../../groupdocs.metadata.formats.document/presentationpackage/createdtime) { get; set; } | Haalt de aanmaakdatum van het document op of stelt deze in. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/presentationpackage/hyperlinkbase) { get; set; } | Haalt of stelt de hyperlinkbasis in. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [Keywords](../../groupdocs.metadata.formats.document/presentationpackage/keywords) { get; set; } | Haalt of stelt de trefwoorden in. |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/presentationpackage/lastprinteddate) { get; set; } | Haalt of stelt de laatst afgedrukte datum in. |
| [LastSavedBy](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedby) { get; set; } | Haalt de naam van de laatste auteur op of stelt deze in. |
| [LastSavedTime](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedtime) { get; } | Haalt de datum en tijd op waarop de presentatie voor het laatst is gewijzigd. |
| [Manager](../../groupdocs.metadata.formats.document/presentationpackage/manager) { get; set; } | Haalt of stelt de manager in. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [NameOfApplication](../../groupdocs.metadata.formats.document/presentationpackage/nameofapplication) { get; } | Haalt de naam op van de toepassing die het document heeft gemaakt. |
| [PresentationFormat](../../groupdocs.metadata.formats.document/presentationpackage/presentationformat) { get; } | Haalt het presentatieformaat op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [RevisionNumber](../../groupdocs.metadata.formats.document/presentationpackage/revisionnumber) { get; set; } | Haalt het revisienummer op of stelt het in. |
| [SharedDoc](../../groupdocs.metadata.formats.document/presentationpackage/shareddoc) { get; set; } | Haalt of stelt een waarde in die aangeeft of de presentatie wordt gedeeld door meerdere mensen. Kan alleen worden bijgewerkt in een PPTX-document. |
| [Subject](../../groupdocs.metadata.formats.document/presentationpackage/subject) { get; set; } | Krijgt of stelt het onderwerp in. |
| [Title](../../groupdocs.metadata.formats.document/presentationpackage/title) { get; set; } | Haalt de titel van het document op of stelt deze in. |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/presentationpackage/totaleditingtime) { get; set; } | Haalt de totale bewerkingstijd van het document op of stelt deze in. |
| [Version](../../groupdocs.metadata.formats.document/presentationpackage/version) { get; } | Haalt de applicatieversie op. |

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
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set)(string, bool) | Voegt de metadata-eigenschap toe of vervangt deze door de opgegeven naam. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_3)(string, DateTime) | Voegt de metadata-eigenschap toe of vervangt deze door de opgegeven naam. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_1)(string, double) | Voegt de metadata-eigenschap toe of vervangt deze door de opgegeven naam. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_2)(string, int) | Voegt de metadata-eigenschap toe of vervangt deze door de opgegeven naam. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_4)(string, string) | Voegt de metadata-eigenschap toe of vervangt deze door de opgegeven naam. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Opmerkingen

**Kom meer te weten**

* [Werken met metadata in Presentaties](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Presentations)

### Voorbeelden

Dit voorbeeld laat zien hoe ingebouwde metadata-eigenschappen in een presentatie kunnen worden bijgewerkt.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPptx))
{
    var root = metadata.GetRootPackage<PresentationRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputPptx);
}
```

### Zie ook

* class [DocumentPackage](../documentpackage)
* naamruimte [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
