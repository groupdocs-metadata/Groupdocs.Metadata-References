---
title: Metadata
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Inizializza una nuova istanza diMetadatagroupdocs.metadata/metadata classe.
type: docs
weight: 10
url: /it/net/groupdocs.metadata/metadata/metadata/
---
## Metadata(string) {#constructor_2}

Inizializza una nuova istanza di[`Metadata`](../../metadata) classe.

```csharp
public Metadata(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Una stringa che contiene il nome completo del file da cui creare un file[`Metadata`](../../metadata) esempio. |

### Osservazioni

**Saperne di più**

* [Carica da un disco locale](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Carica da un flusso](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Carica un file di un formato specifico](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Carica un documento protetto da password](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Esempi

Questo esempio mostra come caricare un file da un disco locale.

```csharp
using (Metadata metadata = new Metadata(Constants.InputOne))
{
    // Estrai, modifica o rimuovi i metadati qui
}
```

### Guarda anche

* class [Metadata](../../metadata)
* spazio dei nomi [GroupDocs.Metadata](../../metadata)
* assemblea [GroupDocs.Metadata](../../../)

---

## Metadata(Stream) {#constructor}

Inizializza una nuova istanza di[`Metadata`](../../metadata) classe.

```csharp
public Metadata(Stream document)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Un flusso che contiene il documento da caricare. |

### Osservazioni

**Saperne di più**

* [Carica da un disco locale](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Carica da un flusso](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Carica un file di un formato specifico](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Carica un documento protetto da password](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Esempi

Questo esempio mostra come caricare un file da uno stream.

```csharp
using (Stream stream = File.Open(Constants.InputDoc, FileMode.Open, FileAccess.ReadWrite))
using (Metadata metadata = new Metadata(stream))
{
   // Estrai, modifica o rimuovi i metadati qui
}
```

### Guarda anche

* class [Metadata](../../metadata)
* spazio dei nomi [GroupDocs.Metadata](../../metadata)
* assemblea [GroupDocs.Metadata](../../../)

---

## Metadata(string, LoadOptions) {#constructor_3}

Inizializza una nuova istanza di[`Metadata`](../../metadata) classe.

```csharp
public Metadata(string filePath, LoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Una stringa che contiene il nome completo del file da cui creare un file[`Metadata`](../../metadata) esempio. |
| loadOptions | LoadOptions | Opzioni aggiuntive da utilizzare durante il caricamento di un documento. |

### Osservazioni

**Saperne di più**

* [Carica da un disco locale](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Carica da un flusso](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Carica un file di un formato specifico](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Carica un documento protetto da password](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Esempi

Questo esempio mostra come caricare un documento protetto da password.

```csharp
// Specifica la password
var loadOptions = new LoadOptions
{
    Password = "123"
};

using (var metadata = new Metadata(Constants.ProtectedDocx, loadOptions))
{
    // Estrai, modifica o rimuovi i metadati qui
}
```

### Guarda anche

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* spazio dei nomi [GroupDocs.Metadata](../../metadata)
* assemblea [GroupDocs.Metadata](../../../)

---

## Metadata(Stream, LoadOptions) {#constructor_1}

Inizializza una nuova istanza di[`Metadata`](../../metadata) classe.

```csharp
public Metadata(Stream document, LoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Un flusso che contiene il documento da caricare. |
| loadOptions | LoadOptions | Opzioni aggiuntive da utilizzare durante il caricamento di un documento. |

### Osservazioni

**Saperne di più**

* [Carica da un disco locale](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Carica da un flusso](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Carica un file di un formato specifico](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Carica un documento protetto da password](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Guarda anche

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* spazio dei nomi [GroupDocs.Metadata](../../metadata)
* assemblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
