---
title: WordProcessingPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt ein natives Metadatenpaket in einem Textverarbeitungsdokument dar.
type: docs
weight: 1280
url: /de/net/groupdocs.metadata.formats.document/wordprocessingpackage/
---
## WordProcessingPackage class

Stellt ein natives Metadatenpaket in einem Textverarbeitungsdokument dar.

```csharp
public class WordProcessingPackage : DocumentPackage
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/wordprocessingpackage/author) { get; set; } | Ruft den Autor des Dokuments ab oder legt ihn fest. |
| [BytesInDocument](../../groupdocs.metadata.formats.document/wordprocessingpackage/bytesindocument) { get; } | Ruft eine Schätzung der Anzahl der Bytes im Dokument ab. |
| [Category](../../groupdocs.metadata.formats.document/wordprocessingpackage/category) { get; set; } | Ruft die Kategorie ab oder legt sie fest. |
| [Comments](../../groupdocs.metadata.formats.document/wordprocessingpackage/comments) { get; set; } | Ruft die Kommentare ab oder legt sie fest. |
| [Company](../../groupdocs.metadata.formats.document/wordprocessingpackage/company) { get; set; } | Ruft das Unternehmen ab oder legt es fest. |
| [ContentStatus](../../groupdocs.metadata.formats.document/wordprocessingpackage/contentstatus) { get; set; } | Ruft den Inhaltsstatus ab oder legt ihn fest. |
| [ContentType](../../groupdocs.metadata.formats.document/wordprocessingpackage/contenttype) { get; set; } | Ruft den Inhaltstyp des Dokuments ab oder legt ihn fest. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [CreatedTime](../../groupdocs.metadata.formats.document/wordprocessingpackage/createdtime) { get; set; } | Ruft das Erstellungsdatum des Dokuments ab oder legt es fest. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/wordprocessingpackage/hyperlinkbase) { get; set; } | Ruft die Hyperlink-Basis ab oder legt sie fest. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [Keywords](../../groupdocs.metadata.formats.document/wordprocessingpackage/keywords) { get; set; } | Ruft die Schlüsselwörter ab oder legt sie fest. |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/wordprocessingpackage/lastprinteddate) { get; set; } | Ruft das letzte gedruckte Datum ab oder setzt es. |
| [LastSavedBy](../../groupdocs.metadata.formats.document/wordprocessingpackage/lastsavedby) { get; set; } | Ruft den Namen des letzten Autors ab oder setzt ihn. |
| [LastSavedTime](../../groupdocs.metadata.formats.document/wordprocessingpackage/lastsavedtime) { get; set; } | Ruft die Zeit der letzten Speicherung ab oder setzt sie. |
| [LinksUpToDate](../../groupdocs.metadata.formats.document/wordprocessingpackage/linksuptodate) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Hyperlinks im Dokument aktuell sind. |
| [Manager](../../groupdocs.metadata.formats.document/wordprocessingpackage/manager) { get; set; } | Ruft den Manager ab oder legt ihn fest. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [NameOfApplication](../../groupdocs.metadata.formats.document/wordprocessingpackage/nameofapplication) { get; } | Ruft den Namen der Anwendung ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [RevisionNumber](../../groupdocs.metadata.formats.document/wordprocessingpackage/revisionnumber) { get; set; } | Ruft die Revisionsnummer ab oder legt sie fest. |
| [Subject](../../groupdocs.metadata.formats.document/wordprocessingpackage/subject) { get; set; } | Ruft den Betreff ab oder legt ihn fest. |
| [Template](../../groupdocs.metadata.formats.document/wordprocessingpackage/template) { get; set; } | Ruft die Vorlage ab oder legt sie fest. |
| [Title](../../groupdocs.metadata.formats.document/wordprocessingpackage/title) { get; set; } | Ruft den Titel des Dokuments ab oder legt ihn fest. |
| [TitlesOfParts](../../groupdocs.metadata.formats.document/wordprocessingpackage/titlesofparts) { get; } | Ruft die Titel der Dokumentteile ab. Schreibgeschützt. |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/wordprocessingpackage/totaleditingtime) { get; set; } | Ruft die gesamte Bearbeitungszeit in Minuten ab oder legt sie fest. |
| [Version](../../groupdocs.metadata.formats.document/wordprocessingpackage/version) { get; } | Ruft die Versionsnummer der Anwendung ab, die das Dokument erstellt hat. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | Entfernt alle beschreibbaren Metadateneigenschaften aus dem Paket. |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | Entfernt alle integrierten Metadateneigenschaften. |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | Entfernt alle benutzerdefinierten Metadateneigenschaften. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | Entfernt eine beschreibbare Metadateneigenschaft mit dem angegebenen Namen. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set)(string, bool) | Fügt die Metadateneigenschaft mit dem angegebenen Namen hinzu oder ersetzt sie. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_3)(string, DateTime) | Fügt die Metadateneigenschaft mit dem angegebenen Namen hinzu oder ersetzt sie. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_1)(string, double) | Fügt die Metadateneigenschaft mit dem angegebenen Namen hinzu oder ersetzt sie. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_2)(string, int) | Fügt die Metadateneigenschaft mit dem angegebenen Namen hinzu oder ersetzt sie. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_4)(string, string) | Fügt die Metadateneigenschaft mit dem angegebenen Namen hinzu oder ersetzt sie. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Bemerkungen

**Erfahren Sie mehr**

* [Arbeiten mit Metadaten in WordProcessing-Dokumenten](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Beispiele

Dieses Codebeispiel zeigt, wie integrierte Metadateneigenschaften in einem WordProcessing-Dokument aktualisiert werden.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDoc))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputDoc);
}
```

### Siehe auch

* class [DocumentPackage](../documentpackage)
* namensraum [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
