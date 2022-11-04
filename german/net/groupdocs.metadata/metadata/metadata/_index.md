---
title: Metadata
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonMetadatagroupdocs.metadata/metadata Klasse.
type: docs
weight: 10
url: /de/net/groupdocs.metadata/metadata/metadata/
---
## Metadata(string) {#constructor_2}

Initialisiert eine neue Instanz von[`Metadata`](../../metadata) Klasse.

```csharp
public Metadata(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Eine Zeichenfolge, die den vollständigen Namen der Datei enthält, aus der eine erstellt werden soll[`Metadata`](../../metadata) Beispiel. |

### Bemerkungen

**Mehr erfahren**

* [Laden von einer lokalen Festplatte](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Aus einem Stream laden](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Laden Sie eine Datei in einem bestimmten Format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Laden Sie ein passwortgeschütztes Dokument](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Beispiele

Dieses Beispiel zeigt, wie eine Datei von einem lokalen Datenträger geladen wird.

```csharp
using (Metadata metadata = new Metadata(Constants.InputOne))
{
    // Metadaten hier extrahieren, bearbeiten oder entfernen
}
```

### Siehe auch

* class [Metadata](../../metadata)
* namensraum [GroupDocs.Metadata](../../metadata)
* Montage [GroupDocs.Metadata](../../../)

---

## Metadata(Stream) {#constructor}

Initialisiert eine neue Instanz von[`Metadata`](../../metadata) Klasse.

```csharp
public Metadata(Stream document)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Ein Stream, der das zu ladende Dokument enthält. |

### Bemerkungen

**Mehr erfahren**

* [Laden von einer lokalen Festplatte](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Aus einem Stream laden](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Laden Sie eine Datei in einem bestimmten Format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Laden Sie ein passwortgeschütztes Dokument](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Beispiele

Dieses Beispiel zeigt, wie eine Datei aus einem Stream geladen wird.

```csharp
using (Stream stream = File.Open(Constants.InputDoc, FileMode.Open, FileAccess.ReadWrite))
using (Metadata metadata = new Metadata(stream))
{
   // Metadaten hier extrahieren, bearbeiten oder entfernen
}
```

### Siehe auch

* class [Metadata](../../metadata)
* namensraum [GroupDocs.Metadata](../../metadata)
* Montage [GroupDocs.Metadata](../../../)

---

## Metadata(string, LoadOptions) {#constructor_3}

Initialisiert eine neue Instanz von[`Metadata`](../../metadata) Klasse.

```csharp
public Metadata(string filePath, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Eine Zeichenfolge, die den vollständigen Namen der Datei enthält, aus der eine erstellt werden soll[`Metadata`](../../metadata) Beispiel. |
| loadOptions | LoadOptions | Zusätzliche Optionen zum Laden eines Dokuments. |

### Bemerkungen

**Mehr erfahren**

* [Laden von einer lokalen Festplatte](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Aus einem Stream laden](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Laden Sie eine Datei in einem bestimmten Format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Laden Sie ein passwortgeschütztes Dokument](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Beispiele

Dieses Beispiel zeigt, wie ein passwortgeschütztes Dokument geladen wird.

```csharp
// Geben Sie das Passwort an
var loadOptions = new LoadOptions
{
    Password = "123"
};

using (var metadata = new Metadata(Constants.ProtectedDocx, loadOptions))
{
    // Metadaten hier extrahieren, bearbeiten oder entfernen
}
```

### Siehe auch

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* namensraum [GroupDocs.Metadata](../../metadata)
* Montage [GroupDocs.Metadata](../../../)

---

## Metadata(Stream, LoadOptions) {#constructor_1}

Initialisiert eine neue Instanz von[`Metadata`](../../metadata) Klasse.

```csharp
public Metadata(Stream document, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Ein Stream, der das zu ladende Dokument enthält. |
| loadOptions | LoadOptions | Zusätzliche Optionen zum Laden eines Dokuments. |

### Bemerkungen

**Mehr erfahren**

* [Laden von einer lokalen Festplatte](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Aus einem Stream laden](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Laden Sie eine Datei in einem bestimmten Format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Laden Sie ein passwortgeschütztes Dokument](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Siehe auch

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* namensraum [GroupDocs.Metadata](../../metadata)
* Montage [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
