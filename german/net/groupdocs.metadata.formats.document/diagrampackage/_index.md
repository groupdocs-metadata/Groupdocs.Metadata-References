---
title: DiagramPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt ein natives Metadatenpaket in einem Diagrammformat dar.
type: docs
weight: 890
url: /de/net/groupdocs.metadata.formats.document/diagrampackage/
---
## DiagramPackage class

Stellt ein natives Metadatenpaket in einem Diagrammformat dar.

```csharp
public class DiagramPackage : DocumentPackage
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternateNames](../../groupdocs.metadata.formats.document/diagrampackage/alternatenames) { get; set; } | Ruft die alternativen Namen für das Dokument ab oder legt sie fest. Kann nur in den Formaten VDX und VSX aktualisiert werden. |
| [BuildNumberCreated](../../groupdocs.metadata.formats.document/diagrampackage/buildnumbercreated) { get; } | Ruft die vollständige Build-Nummer der Instanz ab, die zum Erstellen des Dokuments verwendet wurde. |
| [BuildNumberEdited](../../groupdocs.metadata.formats.document/diagrampackage/buildnumberedited) { get; } | Ruft die Build-Nummer der Instanz ab, die zuletzt zum Bearbeiten des Dokuments verwendet wurde. |
| [Category](../../groupdocs.metadata.formats.document/diagrampackage/category) { get; set; } | Ermittelt oder setzt den beschreibenden Text für den Zeichnungstyp, z. B. Flussdiagramm oder Bürolayout. Dieser Text kann auch in der Microsoft Visio-Benutzeroberfläche im Feld Kategorie im Dialogfeld Eigenschaften eingegeben werden. |
| [Company](../../groupdocs.metadata.formats.document/diagrampackage/company) { get; set; } | Ruft die vom Benutzer eingegebenen Informationen ab oder legt sie fest, die das Unternehmen identifizieren, das die Zeichnung erstellt, oder das Unternehmen, für das die Zeichnung erstellt wird. Die maximale Länge beträgt 63 Zeichen. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [Creator](../../groupdocs.metadata.formats.document/diagrampackage/creator) { get; set; } | Ermittelt oder setzt die Person, die die Datei erstellt oder zuletzt aktualisiert hat. Die maximale Länge beträgt 63 Zeichen.. |
| [Description](../../groupdocs.metadata.formats.document/diagrampackage/description) { get; set; } | Ruft eine beschreibende Textzeichenfolge für das Dokument ab oder legt sie fest. Verwenden Sie dieses Element, um wichtige Informationen über das Dokument zu speichern, z. B. seinen Zweck, kürzlich vorgenommene Änderungen oder anstehende Änderungen. Das Maximum beträgt 191 Zeichen. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/diagrampackage/hyperlinkbase) { get; set; } | Ruft den für relative Hyperlinks zu verwendenden Pfad ab oder legt ihn fest (Hyperlinks, für die der Speicherort der verknüpften Datei in Bezug auf das Microsoft Visio-Diagramm beschrieben wird). Standardmäßig ist ein Hyperlink-Pfad relativ zum aktuellen Dokument, sofern kein anderer Pfad angegeben ist in diesem Element. Die maximale Länge beträgt 256 Zeichen. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [Keywords](../../groupdocs.metadata.formats.document/diagrampackage/keywords) { get; set; } | Ruft eine Textzeichenfolge ab oder legt diese fest, die Themen oder andere wichtige Informationen über die Datei identifiziert, z. B. Projektname, Kundenname oder Versionsnummer. Die maximale Zeichenfolgenlänge beträgt 63 Zeichen. |
| [Language](../../groupdocs.metadata.formats.document/diagrampackage/language) { get; set; } | Ruft die Sprache des Dokuments ab oder legt sie fest. Kann nur in den Formaten VSD und VSDX aktualisiert werden. |
| [Manager](../../groupdocs.metadata.formats.document/diagrampackage/manager) { get; set; } | Ruft eine vom Benutzer eingegebene Textzeichenfolge ab oder legt sie fest, die die für das Projekt oder die Abteilung verantwortliche Person identifiziert. Die maximale Länge beträgt 63 Zeichen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [PreviewPicture](../../groupdocs.metadata.formats.document/diagrampackage/previewpicture) { get; set; } | Holt oder setzt das Vorschaubild. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [Subject](../../groupdocs.metadata.formats.document/diagrampackage/subject) { get; set; } | Ruft eine benutzerdefinierte Textzeichenfolge ab oder legt sie fest, die den Inhalt des Dokuments beschreibt. Die maximale Länge beträgt 63 Zeichen. |
| [Template](../../groupdocs.metadata.formats.document/diagrampackage/template) { get; set; } | Ruft einen Zeichenfolgenwert ab oder legt ihn fest, der den Dateinamen der Vorlage angibt, aus der das Dokument erstellt wurde. |
| [TimeCreated](../../groupdocs.metadata.formats.document/diagrampackage/timecreated) { get; set; } | Ruft einen Datums- und Uhrzeitwert ab oder legt diesen fest, der angibt, wann das Dokument erstellt wurde. |
| [TimeEdited](../../groupdocs.metadata.formats.document/diagrampackage/timeedited) { get; } | Ruft einen Datums- und Zeitwert ab, der angibt, wann das Dokument zuletzt bearbeitet wurde. |
| [TimePrinted](../../groupdocs.metadata.formats.document/diagrampackage/timeprinted) { get; } | Ruft einen Datums- und Uhrzeitwert ab, der angibt, wann das Dokument zuletzt gedruckt wurde. |
| [TimeSaved](../../groupdocs.metadata.formats.document/diagrampackage/timesaved) { get; } | Ruft einen Datums- und Uhrzeitwert ab, der angibt, wann das Dokument zuletzt gespeichert wurde. |
| [Title](../../groupdocs.metadata.formats.document/diagrampackage/title) { get; set; } | Ruft eine benutzerdefinierte Textzeichenfolge ab oder legt sie fest, die als beschreibender Titel für das Dokument dient. Die maximale Länge beträgt 63 Zeichen. |

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
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set)(string, bool) | Fügt die Metadateneigenschaft mit dem angegebenen Namen hinzu oder ersetzt sie. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_2)(string, DateTime) | Fügt die Metadateneigenschaft mit dem angegebenen Namen hinzu oder ersetzt sie. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_1)(string, double) | Fügt die Metadateneigenschaft mit dem angegebenen Namen hinzu oder ersetzt sie. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_3)(string, string) | Fügt die Metadateneigenschaft mit dem angegebenen Namen hinzu oder ersetzt sie. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Bemerkungen

**Mehr erfahren**

* [Arbeiten mit Metadaten in Diagrammen](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### Beispiele

Dieses Codebeispiel zeigt, wie integrierte Metadateneigenschaften aus einem Diagramm extrahiert werden.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.DocumentProperties.Creator);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.TimeCreated);
    Console.WriteLine(root.DocumentProperties.Category);

    // ... 
}
```

### Siehe auch

* class [DocumentPackage](../documentpackage)
* namensraum [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
