---
title: RemoveProperties
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Verwijdert metadataeigenschappen die voldoen aan het opgegeven predikaat.
type: docs
weight: 100
url: /nl/net/groupdocs.metadata.common/metadatapackage/removeproperties/
---
## MetadataPackage.RemoveProperties method

Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat.

```csharp
public virtual int RemoveProperties(Func<MetadataProperty, bool> predicate)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| predicate | Func`2 | Een functie om elke metadata-eigenschap te testen op een voorwaarde. |

### Winstwaarde

Het aantal getroffen eigendommen.

### Opmerkingen

**Kom meer te weten**

* Meer voorbeelden die het gebruik van deze methode demonstreren: [Metagegevens verwijderen](https://docs.groupdocs.com/display/metadatanet/Removing+metadata)

### Zie ook

* delegate [Func&lt;T,TResult&gt;](../../func-2)
* class [MetadataProperty](../../metadataproperty)
* class [MetadataPackage](../../metadatapackage)
* naamruimte [GroupDocs.Metadata.Common](../../metadatapackage)
* montage [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->