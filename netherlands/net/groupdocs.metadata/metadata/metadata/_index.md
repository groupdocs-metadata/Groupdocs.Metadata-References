---
title: Metadata
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Initialiseert een nieuw exemplaar van hetMetadatagroupdocs.metadata/metadata klasse.
type: docs
weight: 10
url: /nl/net/groupdocs.metadata/metadata/metadata/
---
## Metadata(string) {#constructor_2}

Initialiseert een nieuw exemplaar van het[`Metadata`](../../metadata) klasse.

```csharp
public Metadata(string filePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Een tekenreeks die de volledige naam bevat van het bestand waaruit een[`Metadata`](../../metadata) voorbeeld. |

### Opmerkingen

**Kom meer te weten**

* [Laad vanaf een lokale schijf](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Laden vanuit een stream](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Laad een bestand met een specifiek formaat](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Laad een met een wachtwoord beveiligd document](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Voorbeelden

Dit voorbeeld laat zien hoe een bestand van een lokale schijf moet worden geladen.

```csharp
using (Metadata metadata = new Metadata(Constants.InputOne))
{
    // Extraheer, bewerk of verwijder metadata hier
}
```

### Zie ook

* class [Metadata](../../metadata)
* naamruimte [GroupDocs.Metadata](../../metadata)
* montage [GroupDocs.Metadata](../../../)

---

## Metadata(Stream) {#constructor}

Initialiseert een nieuw exemplaar van het[`Metadata`](../../metadata) klasse.

```csharp
public Metadata(Stream document)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | Een stroom die het te laden document bevat. |

### Opmerkingen

**Kom meer te weten**

* [Laad vanaf een lokale schijf](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Laden vanuit een stream](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Laad een bestand met een specifiek formaat](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Laad een met een wachtwoord beveiligd document](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Voorbeelden

Dit voorbeeld laat zien hoe een bestand uit een stream moet worden geladen.

```csharp
using (Stream stream = File.Open(Constants.InputDoc, FileMode.Open, FileAccess.ReadWrite))
using (Metadata metadata = new Metadata(stream))
{
   // Extraheer, bewerk of verwijder metadata hier
}
```

### Zie ook

* class [Metadata](../../metadata)
* naamruimte [GroupDocs.Metadata](../../metadata)
* montage [GroupDocs.Metadata](../../../)

---

## Metadata(string, LoadOptions) {#constructor_3}

Initialiseert een nieuw exemplaar van het[`Metadata`](../../metadata) klasse.

```csharp
public Metadata(string filePath, LoadOptions loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Een tekenreeks die de volledige naam bevat van het bestand waaruit een[`Metadata`](../../metadata) voorbeeld. |
| loadOptions | LoadOptions | Extra opties om te gebruiken bij het laden van een document. |

### Opmerkingen

**Kom meer te weten**

* [Laad vanaf een lokale schijf](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Laden vanuit een stream](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Laad een bestand met een specifiek formaat](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Laad een met een wachtwoord beveiligd document](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Voorbeelden

Dit voorbeeld laat zien hoe u een met een wachtwoord beveiligd document laadt.

```csharp
// Geef het wachtwoord op
var loadOptions = new LoadOptions
{
    Password = "123"
};

using (var metadata = new Metadata(Constants.ProtectedDocx, loadOptions))
{
    // Extraheer, bewerk of verwijder metadata hier
}
```

### Zie ook

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* naamruimte [GroupDocs.Metadata](../../metadata)
* montage [GroupDocs.Metadata](../../../)

---

## Metadata(Stream, LoadOptions) {#constructor_1}

Initialiseert een nieuw exemplaar van het[`Metadata`](../../metadata) klasse.

```csharp
public Metadata(Stream document, LoadOptions loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | Een stroom die het te laden document bevat. |
| loadOptions | LoadOptions | Extra opties om te gebruiken bij het laden van een document. |

### Opmerkingen

**Kom meer te weten**

* [Laad vanaf een lokale schijf](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Laden vanuit een stream](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Laad een bestand met een specifiek formaat](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Laad een met een wachtwoord beveiligd document](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Zie ook

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* naamruimte [GroupDocs.Metadata](../../metadata)
* montage [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
