---
title: DiagramPackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt een native metadatapakket in een diagramindeling.
type: docs
weight: 890
url: /nl/net/groupdocs.metadata.formats.document/diagrampackage/
---
## DiagramPackage class

Vertegenwoordigt een native metadatapakket in een diagramindeling.

```csharp
public class DiagramPackage : DocumentPackage
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternateNames](../../groupdocs.metadata.formats.document/diagrampackage/alternatenames) { get; set; } | Haalt of stelt de alternatieve namen voor het document in. Kan alleen worden bijgewerkt in VDX- en VSX-indelingen. |
| [BuildNumberCreated](../../groupdocs.metadata.formats.document/diagrampackage/buildnumbercreated) { get; } | Haalt het volledige buildnummer op van de instantie die is gebruikt om het document te maken. |
| [BuildNumberEdited](../../groupdocs.metadata.formats.document/diagrampackage/buildnumberedited) { get; } | Haalt het buildnummer op van de instantie die het laatst is gebruikt om het document te bewerken. |
| [Category](../../groupdocs.metadata.formats.document/diagrampackage/category) { get; set; } | Hiermee wordt de beschrijvende tekst voor het type tekening opgehaald of ingesteld, zoals stroomdiagram of kantoorindeling. Deze tekst kan ook worden ingevoerd in de gebruikersinterface van Microsoft Visio in het vak Categorie in het dialoogvenster Eigenschappen. |
| [Company](../../groupdocs.metadata.formats.document/diagrampackage/company) { get; set; } | Haalt de door de gebruiker ingevoerde informatie op of stelt deze in ter identificatie van het bedrijf dat de tekening maakt of het bedrijf waarvoor de tekening wordt gemaakt. Maximale lengte is 63 tekens. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [Creator](../../groupdocs.metadata.formats.document/diagrampackage/creator) { get; set; } | Haalt of stelt de persoon in die het bestand heeft gemaakt of het laatst heeft bijgewerkt. De maximale lengte is 63 tekens.. |
| [Description](../../groupdocs.metadata.formats.document/diagrampackage/description) { get; set; } | Haalt een beschrijvende tekenreeks voor het document op of stelt deze in. Gebruik dit element om belangrijke informatie over het document op te slaan, zoals het doel, recente wijzigingen of wijzigingen die in behandeling zijn. Het maximum is 191 tekens. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/diagrampackage/hyperlinkbase) { get; set; } | Haalt of stelt het pad in dat moet worden gebruikt voor relatieve hyperlinks (hyperlinks waarvoor de gekoppelde bestandslocatie wordt beschreven in relatie tot het Microsoft Visio-diagram). Standaard is een hyperlinkpad relatief ten opzichte van het huidige document, tenzij een ander pad is opgegeven in dit element. Maximale lengte is 256 tekens. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [Keywords](../../groupdocs.metadata.formats.document/diagrampackage/keywords) { get; set; } | Haalt een tekenreeks op of stelt deze in die onderwerpen of andere belangrijke informatie over het bestand identificeert, zoals de projectnaam, de naam van de klant of het versienummer. De maximale tekenreekslengte is 63 tekens. |
| [Language](../../groupdocs.metadata.formats.document/diagrampackage/language) { get; set; } | Hiermee wordt de taal van het document opgehaald of ingesteld. Kan alleen worden bijgewerkt in VSD- en VSDX-indelingen. |
| [Manager](../../groupdocs.metadata.formats.document/diagrampackage/manager) { get; set; } | Haalt of stelt een door de gebruiker ingevoerde tekenreeks op die de persoon identificeert die verantwoordelijk is voor het project of de afdeling. De maximale lengte is 63 tekens. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [PreviewPicture](../../groupdocs.metadata.formats.document/diagrampackage/previewpicture) { get; set; } | Haalt de voorbeeldafbeelding op of stelt deze in. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [Subject](../../groupdocs.metadata.formats.document/diagrampackage/subject) { get; set; } | Haalt een door de gebruiker gedefinieerde tekenreeks op of stelt deze in die de inhoud van het document beschrijft. Maximale lengte is 63 tekens. |
| [Template](../../groupdocs.metadata.formats.document/diagrampackage/template) { get; set; } | Hiermee wordt een tekenreekswaarde opgehaald of ingesteld die de bestandsnaam specificeert van de sjabloon waaruit het document is gemaakt. |
| [TimeCreated](../../groupdocs.metadata.formats.document/diagrampackage/timecreated) { get; set; } | Hiermee wordt een datum- en tijdwaarde opgehaald of ingesteld die aangeeft wanneer het document is gemaakt. |
| [TimeEdited](../../groupdocs.metadata.formats.document/diagrampackage/timeedited) { get; } | Krijgt een datum- en tijdwaarde die aangeeft wanneer het document voor het laatst is bewerkt. |
| [TimePrinted](../../groupdocs.metadata.formats.document/diagrampackage/timeprinted) { get; } | Krijgt een datum- en tijdwaarde die aangeeft wanneer het document voor het laatst is afgedrukt. |
| [TimeSaved](../../groupdocs.metadata.formats.document/diagrampackage/timesaved) { get; } | Krijgt een datum- en tijdwaarde die aangeeft wanneer het document voor het laatst is opgeslagen. |
| [Title](../../groupdocs.metadata.formats.document/diagrampackage/title) { get; set; } | Haalt of stelt een door de gebruiker gedefinieerde tekenreeks op die dient als een beschrijvende titel voor het document. Maximale lengte is 63 tekens. |

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
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set)(string, bool) | Voegt de metadata-eigenschap toe of vervangt deze door de opgegeven naam. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_2)(string, DateTime) | Voegt de metadata-eigenschap toe of vervangt deze door de opgegeven naam. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_1)(string, double) | Voegt de metadata-eigenschap toe of vervangt deze door de opgegeven naam. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_3)(string, string) | Voegt de metadata-eigenschap toe of vervangt deze door de opgegeven naam. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Opmerkingen

**Kom meer te weten**

* [Werken met metadata in diagrammen](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### Voorbeelden

Dit codevoorbeeld laat zien hoe ingebouwde metagegevenseigenschappen uit een diagram kunnen worden geëxtraheerd.

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

### Zie ook

* class [DocumentPackage](../documentpackage)
* naamruimte [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
