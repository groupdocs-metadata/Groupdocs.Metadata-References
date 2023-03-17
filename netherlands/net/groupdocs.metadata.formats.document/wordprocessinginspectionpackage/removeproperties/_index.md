---
title: RemoveProperties
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Verwijdert metadataeigenschappen die voldoen aan het opgegeven predikaat.
type: docs
weight: 110
url: /nl/net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/removeproperties/
---
## WordProcessingInspectionPackage.RemoveProperties method

Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat.

```csharp
public override int RemoveProperties(Func<MetadataProperty, bool> predicate)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| predicate | Func`2 | Een functie om elke metadata-eigenschap te testen op een voorwaarde. |

### Winstwaarde

Het aantal getroffen eigendommen.

### Zie ook

* delegate [Func&lt;T,TResult&gt;](../../../groupdocs.metadata.common/func-2)
* class [MetadataProperty](../../../groupdocs.metadata.common/metadataproperty)
* class [WordProcessingInspectionPackage](../../wordprocessinginspectionpackage)
* naamruimte [GroupDocs.Metadata.Formats.Document](../../wordprocessinginspectionpackage)
* montage [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->