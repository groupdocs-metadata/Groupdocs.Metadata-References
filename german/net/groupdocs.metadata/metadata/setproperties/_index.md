---
title: SetProperties
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Legt bekannte Metadateneigenschaften fest die das angegebene Prädikat erfüllen. Die Operation ist rekursiv sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination ausAddPropertiesgroupdocs.metadata/metadata/addproperties undUpdatePropertiesgroupdocs.metadata/metadata/updateproperties . Wenn eine vorhandene Eigenschaft das Prädikat erfüllt wird ihr Wert aktualisiert. Wenn in einem Paket eine bekannte Eigenschaft fehlt die das Prädikat erfüllt wird sie dem Paket hinzugefügt.
type: docs
weight: 120
url: /de/net/groupdocs.metadata/metadata/setproperties/
---
## Metadata.SetProperties method

Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../addproperties) und[`UpdateProperties`](../updateproperties) . Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn in einem Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt.

```csharp
public int SetProperties(Func<MetadataProperty, bool> predicate, PropertyValue value)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| predicate | Func`2 | Eine Funktion zum Testen jeder Metadateneigenschaft auf eine Bedingung. |
| value | PropertyValue | Ein neuer Wert für die gefilterten Eigenschaften. |

### Rückgabewert

Die Anzahl der betroffenen Eigenschaften.

### Bemerkungen

Bitte beachten Sie, dass GroupDocs.Metadata implizit den Typ jeder gefilterten Eigenschaft überprüft. Es ist unmöglich, eine Eigenschaft mit einem Wert festzulegen, der einen ungeeigneten Typ hat.

**Mehr erfahren**

* [Legen Sie Metadateneigenschaften fest](https://docs.groupdocs.com/display/metadatanet/Set+metadata+properties)

### Beispiele

Dieses Beispiel zeigt, wie bestimmte Metadateneigenschaften anhand verschiedener Kriterien festgelegt werden.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    // Legen Sie den Wert jeder Eigenschaft fest, die das Prädikat erfüllt:
    // Eigenschaft enthält das Datum/die Uhrzeit, zu der das Dokument erstellt oder geändert wurde
    var affected = metadata.SetProperties(
    p => p.Tags.Contains(Tags.Time.Created) || p.Tags.Contains(Tags.Time.Modified),
    new PropertyValue(DateTime.Now));

    Console.WriteLine("Properties set: {0}", affected);

    metadata.Save(Constants.OutputVsdx);
}
```

### Siehe auch

* delegate [Func&lt;T,TResult&gt;](../../../groupdocs.metadata.common/func-2)
* class [MetadataProperty](../../../groupdocs.metadata.common/metadataproperty)
* class [PropertyValue](../../../groupdocs.metadata.common/propertyvalue)
* class [Metadata](../../metadata)
* namensraum [GroupDocs.Metadata](../../metadata)
* Montage [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->