---
title: PresentationPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt ein natives Metadatenpaket in einer Präsentation dar.
type: docs
weight: 1090
url: /de/net/groupdocs.metadata.formats.document/presentationpackage/
---
## PresentationPackage class

Stellt ein natives Metadatenpaket in einer Präsentation dar.

```csharp
public class PresentationPackage : DocumentPackage
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ApplicationTemplate](../../groupdocs.metadata.formats.document/presentationpackage/applicationtemplate) { get; set; } | Ruft die Anwendungsvorlage ab oder legt sie fest. |
| [Author](../../groupdocs.metadata.formats.document/presentationpackage/author) { get; set; } | Ruft den Autor des Dokuments ab oder legt ihn fest. |
| [Category](../../groupdocs.metadata.formats.document/presentationpackage/category) { get; set; } | Ruft die Kategorie ab oder legt sie fest. |
| [Comments](../../groupdocs.metadata.formats.document/presentationpackage/comments) { get; set; } | Ruft die Kommentare ab oder legt sie fest. |
| [Company](../../groupdocs.metadata.formats.document/presentationpackage/company) { get; set; } | Ruft das Unternehmen ab oder legt es fest. |
| [ContentStatus](../../groupdocs.metadata.formats.document/presentationpackage/contentstatus) { get; set; } | Ruft den Inhaltsstatus ab oder legt ihn fest. Kann nur in einem PPTX-Dokument aktualisiert werden. |
| [ContentType](../../groupdocs.metadata.formats.document/presentationpackage/contenttype) { get; set; } | Ruft den Inhaltstyp ab oder legt ihn fest. Kann nur in einem PPTX-Dokument aktualisiert werden. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [CreatedTime](../../groupdocs.metadata.formats.document/presentationpackage/createdtime) { get; set; } | Ruft das Erstellungsdatum des Dokuments ab oder legt es fest. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/presentationpackage/hyperlinkbase) { get; set; } | Ruft die Hyperlink-Basis ab oder legt sie fest. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [Keywords](../../groupdocs.metadata.formats.document/presentationpackage/keywords) { get; set; } | Ruft die Schlüsselwörter ab oder legt sie fest. |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/presentationpackage/lastprinteddate) { get; set; } | Ruft das letzte gedruckte Datum ab oder setzt es. |
| [LastSavedBy](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedby) { get; set; } | Ruft den Namen des letzten Autors ab oder setzt ihn. |
| [LastSavedTime](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedtime) { get; } | Ruft Datum und Uhrzeit der letzten Änderung der Präsentation ab. |
| [Manager](../../groupdocs.metadata.formats.document/presentationpackage/manager) { get; set; } | Ruft den Manager ab oder legt ihn fest. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [NameOfApplication](../../groupdocs.metadata.formats.document/presentationpackage/nameofapplication) { get; } | Ruft den Namen der Anwendung ab, die das Dokument erstellt hat. |
| [PresentationFormat](../../groupdocs.metadata.formats.document/presentationpackage/presentationformat) { get; } | Ruft das Präsentationsformat ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [RevisionNumber](../../groupdocs.metadata.formats.document/presentationpackage/revisionnumber) { get; set; } | Ruft die Revisionsnummer ab oder legt sie fest. |
| [SharedDoc](../../groupdocs.metadata.formats.document/presentationpackage/shareddoc) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Präsentation von mehreren Personen geteilt wird. Kann nur in einem PPTX-Dokument aktualisiert werden. |
| [Subject](../../groupdocs.metadata.formats.document/presentationpackage/subject) { get; set; } | Ruft den Betreff ab oder legt ihn fest. |
| [Title](../../groupdocs.metadata.formats.document/presentationpackage/title) { get; set; } | Ruft den Titel des Dokuments ab oder legt ihn fest. |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/presentationpackage/totaleditingtime) { get; set; } | Ruft die gesamte Bearbeitungszeit des Dokuments ab oder setzt sie. |
| [Version](../../groupdocs.metadata.formats.document/presentationpackage/version) { get; } | Ruft die Anwendungsversion ab. |

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
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set)(string, bool) | Fügt die Metadateneigenschaft mit dem angegebenen Namen hinzu oder ersetzt sie. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_3)(string, DateTime) | Fügt die Metadateneigenschaft mit dem angegebenen Namen hinzu oder ersetzt sie. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_1)(string, double) | Fügt die Metadateneigenschaft mit dem angegebenen Namen hinzu oder ersetzt sie. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_2)(string, int) | Fügt die Metadateneigenschaft mit dem angegebenen Namen hinzu oder ersetzt sie. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_4)(string, string) | Fügt die Metadateneigenschaft mit dem angegebenen Namen hinzu oder ersetzt sie. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Bemerkungen

**Mehr erfahren**

* [Arbeiten mit Metadaten in Präsentationen](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Presentations)

### Beispiele

Dieses Beispiel zeigt, wie integrierte Metadateneigenschaften in einer Präsentation aktualisiert werden.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPptx))
{
    var root = metadata.GetRootPackage<PresentationRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputPptx);
}
```

### Siehe auch

* class [DocumentPackage](../documentpackage)
* namensraum [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
