---
title: WordProcessingInspectionPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Enthält Informationen zu Dokumententeilen die in manchen Fällen als Metadaten betrachtet werden können.
type: docs
weight: 1270
url: /de/net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/
---
## WordProcessingInspectionPackage class

Enthält Informationen zu Dokumententeilen, die in manchen Fällen als Metadaten betrachtet werden können.

```csharp
public sealed class WordProcessingInspectionPackage : CustomPackage
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Comments](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/comments) { get; } | Ruft ein Array der Benutzerkommentare ab. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/digitalsignatures) { get; } | Ruft ein Array von digitalen Signaturen ab, die im Dokument präsentiert werden. |
| [Fields](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/fields) { get; } | Ruft ein Array von Dokumentfeldern ab. |
| [HiddenText](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/hiddentext) { get; } | Ruft ein Array versteckter Textfragmente ab, die aus dem Dokument extrahiert wurden. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [Revisions](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/revisions) { get; } | Ruft ein Array von digitalen Signaturen ab, die im Dokument präsentiert werden. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AcceptAllRevisions](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/acceptallrevisions)() | Akzeptiert alle erkannten Revisionen im Dokument. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [ClearComments](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clearcomments)() | Entfernt alle erkannten Benutzerkommentare aus dem Dokument. |
| [ClearFields](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clearfields)() | Entfernt alle erkannten Felder aus dem Dokument. |
| [ClearHiddenText](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clearhiddentext)() | Entfernt alle versteckten Textfragmente aus dem Dokument. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [RejectAllRevisions](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/rejectallrevisions)() | Lehnt alle erkannten Revisionen im Dokument ab. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| override [Sanitize](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Bemerkungen

**Erfahren Sie mehr**

* [Arbeiten mit Metadaten in WordProcessing-Dokumenten](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Beispiele

Dieses Codebeispiel zeigt, wie Prüfeigenschaften in einem WordProcessing-Dokument aktualisiert werden.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDoc))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    root.InspectionPackage.ClearComments();
    root.InspectionPackage.AcceptAllRevisions();
    root.InspectionPackage.ClearFields();
    root.InspectionPackage.ClearHiddenText();

    metadata.Save(Constants.OutputDoc);
}
```

### Siehe auch

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namensraum [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
