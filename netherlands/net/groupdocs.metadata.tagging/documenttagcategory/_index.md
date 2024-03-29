---
title: DocumentTagCategory
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Biedt tags die alleen worden toegepast op documentspecifieke eigenschappen. De tags kunnen handig zijn om te bepalen uit welk deel van een kantoordocument een eigenschap is geëxtraheerd.
type: docs
weight: 3660
url: /nl/net/groupdocs.metadata.tagging/documenttagcategory/
---
## DocumentTagCategory class

Biedt tags die alleen worden toegepast op documentspecifieke eigenschappen. De tags kunnen handig zijn om te bepalen uit welk deel van een kantoordocument een eigenschap is geëxtraheerd.

```csharp
public class DocumentTagCategory : TagCategory
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BuiltIn](../../groupdocs.metadata.tagging/documenttagcategory/builtin) { get; } | Haalt de tag op die aangeeft dat de eigenschap die het labelt ingebouwd is. |
| [Field](../../groupdocs.metadata.tagging/documenttagcategory/field) { get; } | Haalt de tag op die een eigenschap aangeeft die informatie bevat over een formulierveld of berekend veld dat is geëxtraheerd uit een document. |
| [HiddenData](../../groupdocs.metadata.tagging/documenttagcategory/hiddendata) { get; } | Haalt de tag op die een documentonderdeel aangeeft dat niet zichtbaar is voor reguliere gebruikers. |
| [Page](../../groupdocs.metadata.tagging/documenttagcategory/page) { get; } | Haalt de tag op die een eigenschap aangeeft die informatie bevat over een documentpagina. |
| [ReadOnly](../../groupdocs.metadata.tagging/documenttagcategory/readonly) { get; } | Haalt de tag op die aangeeft dat de eigenschap die het labelt alleen-lezen is en niet kan worden gewijzigd door GroupDocs.Metadata. |
| [Revision](../../groupdocs.metadata.tagging/documenttagcategory/revision) { get; } | Haal de tag op die een eigenschap labelt met informatie over een documentrevisie (bijgehouden wijziging). |
| [Statistic](../../groupdocs.metadata.tagging/documenttagcategory/statistic) { get; } | Haalt de tag op die een eigenschap aangeeft die documentstatistieken bevat (aantal woorden, aantal tekens, enz.). |
| [UserComment](../../groupdocs.metadata.tagging/documenttagcategory/usercomment) { get; } | Krijgt de tag die gebruikersopmerkingen labelt die worden weergegeven in de documentinhoud. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [ToString](../../groupdocs.metadata.tagging/tagcategory/tostring)() | Retourneert een tekenreeks die het huidige object vertegenwoordigt. |

### Zie ook

* class [TagCategory](../tagcategory)
* naamruimte [GroupDocs.Metadata.Tagging](../../groupdocs.metadata.tagging)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
