---
title: AdditionalInfo
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Ottiene o imposta le informazioni aggiuntive. Questo valore è rappresentato dal campo INF.
type: docs
weight: 20
url: /it/net/groupdocs.metadata.formats.audio/lyricstag/additionalinfo/
---
## LyricsTag.AdditionalInfo property

Ottiene o imposta le informazioni aggiuntive. Questo valore è rappresentato dal campo INF.

```csharp
public string AdditionalInfo { get; set; }
```

### Valore della proprietà

Le informazioni aggiuntive.

### Osservazioni

Questo è sempre lungo tre (3) caratteri nella versione 2.00, ma potrebbe essere più lungo in uno standard futuro. Il primo byte indica che il tempo o meno è presente un campo testo. "1" per presente e "0" per altrimenti. Il secondo carattere indica se c'è un timestamp nel testo. Di nuovo "1" per sì e "0" per no. Il terzo carattere inibisce le tracce per la selezione casuale - "1" se inibito e "0" in caso contrario.

### Guarda anche

* class [LyricsTag](../../lyricstag)
* spazio dei nomi [GroupDocs.Metadata.Formats.Audio](../../lyricstag)
* assemblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
