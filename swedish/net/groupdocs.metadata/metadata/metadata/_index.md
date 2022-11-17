---
title: Metadata
second_title: GroupDocs.Metadata for .NET API-referens
description: Initierar en ny instans avMetadatagroupdocs.metadata/metadata class.
type: docs
weight: 10
url: /sv/net/groupdocs.metadata/metadata/metadata/
---
## Metadata(string) {#constructor_2}

Initierar en ny instans av[`Metadata`](../../metadata) class.

```csharp
public Metadata(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | En sträng som innehåller det fullständiga namnet på filen som en[`Metadata`](../../metadata) exempel. |

### Anmärkningar

**Läs mer**

* [Ladda från en lokal disk](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Ladda från en ström](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Ladda en fil av ett specifikt format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Ladda ett lösenordsskyddat dokument](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Exempel

Det här exemplet visar hur man laddar en fil från en lokal disk.

```csharp
using (Metadata metadata = new Metadata(Constants.InputOne))
{
    // Extrahera, redigera eller ta bort metadata här
}
```

### Se även

* class [Metadata](../../metadata)
* namnutrymme [GroupDocs.Metadata](../../metadata)
* hopsättning [GroupDocs.Metadata](../../../)

---

## Metadata(Stream) {#constructor}

Initierar en ny instans av[`Metadata`](../../metadata) class.

```csharp
public Metadata(Stream document)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Stream | En ström som innehåller dokumentet som ska laddas. |

### Anmärkningar

**Läs mer**

* [Ladda från en lokal disk](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Ladda från en ström](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Ladda en fil av ett specifikt format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Ladda ett lösenordsskyddat dokument](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Exempel

Det här exemplet visar hur man laddar en fil från en ström.

```csharp
using (Stream stream = File.Open(Constants.InputDoc, FileMode.Open, FileAccess.ReadWrite))
using (Metadata metadata = new Metadata(stream))
{
   // Extrahera, redigera eller ta bort metadata här
}
```

### Se även

* class [Metadata](../../metadata)
* namnutrymme [GroupDocs.Metadata](../../metadata)
* hopsättning [GroupDocs.Metadata](../../../)

---

## Metadata(string, LoadOptions) {#constructor_3}

Initierar en ny instans av[`Metadata`](../../metadata) class.

```csharp
public Metadata(string filePath, LoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | En sträng som innehåller det fullständiga namnet på filen som en[`Metadata`](../../metadata) exempel. |
| loadOptions | LoadOptions | Ytterligare alternativ att använda när du laddar ett dokument. |

### Anmärkningar

**Läs mer**

* [Ladda från en lokal disk](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Ladda från en ström](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Ladda en fil av ett specifikt format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Ladda ett lösenordsskyddat dokument](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Exempel

Det här exemplet visar hur man laddar ett lösenordsskyddat dokument.

```csharp
// Ange lösenordet
var loadOptions = new LoadOptions
{
    Password = "123"
};

using (var metadata = new Metadata(Constants.ProtectedDocx, loadOptions))
{
    // Extrahera, redigera eller ta bort metadata här
}
```

### Se även

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* namnutrymme [GroupDocs.Metadata](../../metadata)
* hopsättning [GroupDocs.Metadata](../../../)

---

## Metadata(Stream, LoadOptions) {#constructor_1}

Initierar en ny instans av[`Metadata`](../../metadata) class.

```csharp
public Metadata(Stream document, LoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Stream | En ström som innehåller dokumentet som ska laddas. |
| loadOptions | LoadOptions | Ytterligare alternativ att använda när du laddar ett dokument. |

### Anmärkningar

**Läs mer**

* [Ladda från en lokal disk](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Ladda från en ström](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Ladda en fil av ett specifikt format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Ladda ett lösenordsskyddat dokument](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Se även

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* namnutrymme [GroupDocs.Metadata](../../metadata)
* hopsättning [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
