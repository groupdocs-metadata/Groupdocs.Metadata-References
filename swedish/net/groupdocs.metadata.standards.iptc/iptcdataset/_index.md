---
title: IptcDataSet
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar en IPTCdatauppsättning metadataegenskap.
type: docs
weight: 2900
url: /sv/net/groupdocs.metadata.standards.iptc/iptcdataset/
---
## IptcDataSet class

Representerar en IPTC-datauppsättning (metadataegenskap).

```csharp
public sealed class IptcDataSet : MetadataProperty
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [IptcDataSet](iptcdataset#constructor)(byte, byte, byte[]) | Initierar en ny instans av[`IptcDataSet`](../iptcdataset) class. |
| [IptcDataSet](iptcdataset#constructor_2)(byte, byte, DateTime) | Initierar en ny instans av[`IptcDataSet`](../iptcdataset) class. |
| [IptcDataSet](iptcdataset#constructor_1)(byte, byte, int) | Initierar en ny instans av[`IptcDataSet`](../iptcdataset) class. |
| [IptcDataSet](iptcdataset#constructor_3)(byte, byte, string) | Initierar en ny instans av[`IptcDataSet`](../iptcdataset) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AlternativeName](../../groupdocs.metadata.standards.iptc/iptcdataset/alternativename) { get; } | Hämtar det alternativa namnet på datamängden. |
| [DataSetNumber](../../groupdocs.metadata.standards.iptc/iptcdataset/datasetnumber) { get; } | Hämtar datamängdsnumret. |
| [Descriptor](../../groupdocs.metadata.common/metadataproperty/descriptor) { get; } | Hämtar beskrivningen som är kopplad till metadataegenskapen. |
| [InterpretedValue](../../groupdocs.metadata.common/metadataproperty/interpretedvalue) { get; } | Hämtar det tolkade egenskapsvärdet, om tillgängligt. Det tolkade värdet är en användarvänlig form av det ursprungliga egenskapsvärdet. Till exempel returnerar den en läsbar sträng istället för numeriska flaggor och id, om det behövs, översätter byte-arrayer till text, etc. |
| [Name](../../groupdocs.metadata.common/metadataproperty/name) { get; } | Hämtar egenskapens namn. |
| [RecordNumber](../../groupdocs.metadata.standards.iptc/iptcdataset/recordnumber) { get; } | Får postnumret. |
| [Tags](../../groupdocs.metadata.common/metadataproperty/tags) { get; } | Får en samling taggar kopplade till egenskapen. |
| [Value](../../groupdocs.metadata.common/metadataproperty/value) { get; } | Hämtar egenskapsvärdet. |

### Anmärkningar

**Läs mer**

* [Arbeta med IPTC IIM-metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Se även

* class [MetadataProperty](../../groupdocs.metadata.common/metadataproperty)
* namnutrymme [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->