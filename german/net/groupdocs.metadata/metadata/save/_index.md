---
title: Save
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Speichert alle im geladenen Dokument vorgenommenen Änderungen.
type: docs
weight: 110
url: /de/net/groupdocs.metadata/metadata/save/
---
## Save() {#save}

Speichert alle im geladenen Dokument vorgenommenen Änderungen.

```csharp
public void Save()
```

### Bemerkungen

**Mehr erfahren**

* [Speichern Sie eine geänderte Datei in der ursprünglichen Quelle](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+the+original+source)
* [Speichern Sie eine geänderte Datei an einem angegebenen Ort](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+specified+location)
* [Speichern Sie eine geänderte Datei in einem Stream](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+stream)

### Beispiele

Dieses Beispiel zeigt, wie der geänderte Inhalt in der zugrunde liegenden Quelle gespeichert wird.

```csharp
using (Metadata metadata = new Metadata(Constants.OutputPpt))
{
    // Metadaten hier bearbeiten oder entfernen

    // Speichert das Dokument in der zugrunde liegenden Quelle (Stream oder Datei)
    metadata.Save();
}
```

### Siehe auch

* class [Metadata](../../metadata)
* namensraum [GroupDocs.Metadata](../../metadata)
* Montage [GroupDocs.Metadata](../../../)

---

## Save(Stream) {#save_1}

Speichert den Dokumentinhalt in einem Stream.

```csharp
public void Save(Stream document)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Ein Ausgabestream für das Dokument. |

### Bemerkungen

**Mehr erfahren**

* [Speichern Sie eine geänderte Datei in der ursprünglichen Quelle](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+the+original+source)
* [Speichern Sie eine geänderte Datei an einem angegebenen Ort](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+specified+location)
* [Speichern Sie eine geänderte Datei in einem Stream](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+stream)

### Beispiele

Dieses Beispiel zeigt, wie ein Dokument im angegebenen Stream gespeichert wird.

```csharp
using (MemoryStream stream = new MemoryStream())
{
    using (Metadata metadata = new Metadata(Constants.InputPng))
    {
        // Metadaten hier bearbeiten oder entfernen

        metadata.Save(stream);
    }
}
```

### Siehe auch

* class [Metadata](../../metadata)
* namensraum [GroupDocs.Metadata](../../metadata)
* Montage [GroupDocs.Metadata](../../../)

---

## Save(string) {#save_2}

Speichert den Dokumentinhalt in der angegebenen Datei.

```csharp
public void Save(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der vollständige Name der Ausgabedatei. |

### Bemerkungen

**Mehr erfahren**

* [Speichern Sie eine geänderte Datei in der ursprünglichen Quelle](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+the+original+source)
* [Speichern Sie eine geänderte Datei an einem angegebenen Ort](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+specified+location)
* [Speichern Sie eine geänderte Datei in einem Stream](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+stream)

### Beispiele

Dieses Beispiel zeigt, wie ein Dokument am angegebenen Ort gespeichert wird.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    // Metadaten hier bearbeiten oder entfernen

    metadata.Save(Constants.OutputJpeg);
}
```

### Siehe auch

* class [Metadata](../../metadata)
* namensraum [GroupDocs.Metadata](../../metadata)
* Montage [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->