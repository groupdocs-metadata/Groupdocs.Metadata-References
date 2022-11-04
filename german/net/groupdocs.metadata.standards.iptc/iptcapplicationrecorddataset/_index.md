---
title: IptcApplicationRecordDataSet
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Definiert IPTCAnwendungsdatensatznummern.
type: docs
weight: 2890
url: /de/net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/
---
## IptcApplicationRecordDataSet enumeration

Definiert IPTC-Anwendungsdatensatznummern.

```csharp
public enum IptcApplicationRecordDataSet
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| RecordVersion | `0` | Repräsentiert die Datensatzversion. Binär. Immer 2 in JPEGs. |
| ObjectTypeReference | `3` | Objekttypreferenz. Verwendetes Muster: "/\d{2}:[\w\s]{0,64}?/". |
| ObjectAttributeReference | `4` | Die Objektattributreferenz. |
| ObjectName | `5` | Wird als Kurzreferenz für das Objekt verwendet. |
| EditStatus | `7` | Status der Objektdaten, entsprechend der Praxis des Anbieters. |
| EditorialUpdate | `8` | Gibt die Art der Aktualisierung an, die dieses Objekt für ein vorheriges Objekt bereitstellt. |
| Urgency | `10` | Gibt die redaktionelle Dringlichkeit des Inhalts an und nicht notwendigerweise die Umschlagbehandlungspriorität (siehe 1:60, Umschlagpriorität). |
| SubjectReference | `12` | Die Betreffreferenz. |
| Category | `15` | Identifiziert das Thema der Objektdaten nach Ansicht des Anbieters. |
| SupplementalCategory | `20` | Ergänzende Kategorien verfeinern das Thema von Objektdaten weiter. In jedem DataSet darf nur eine einzige Zusatzkategorie enthalten sein. Eine zusätzliche Kategorie kann jede der anerkannten Kategorien beinhalten, wie sie in 2:15 verwendet werden. |
| FixtureIdentifier | `22` | Die Gerätekennung. |
| Keywords | `25` | Wird verwendet, um bestimmte Wörter zum Abrufen von Informationen anzugeben. Jedes Schlüsselwort verwendet ein einzelnes Schlüsselwort-DataSet. Mehrere Schlüsselwörter verwenden mehrere Schlüsselwort-Datensätze. |
| ContentLocationCode | `26` | Gibt den Code eines Landes/geografischen Standorts an, auf den durch den Inhalt des Objekts verwiesen wird. |
| ContentLocationName | `27` | stellt einen vollständigen, veröffentlichungsfähigen Namen eines Landes/geografischen Standorts bereit, auf das durch den Inhalt des Objekts verwiesen wird, nach Richtlinien des Anbieters. |
| ReleaseDate | `30` | Bezeichnet in der Form CCYYMMDD das früheste Datum, an dem der Anbieter das Objekt verwenden möchte. Entspricht dem ISO 8601-Standard. |
| ReleaseTime | `35` | Bezeichnet in der Form HHMMSS±HHMM den frühesten Zeitpunkt, zu dem der Anbieter das Objekt verwenden will. Entspricht dem ISO 8601-Standard. |
| ExpirationDate | `37` | Bezeichnet in der Form CCYYMMDD das späteste Datum, an dem der Anbieter oder Eigentümer beabsichtigt, die Objektdaten zu verwenden. Entspricht dem ISO 8601-Standard. |
| SpecialInstructions | `40` | Sonstige redaktionelle Hinweise zur Nutzung der Objektdaten, wie Embargos und Verwarnungen. |
| ActionAdvised | `42` | Gibt die Art der Aktion an, die dieses Objekt für ein vorheriges Objekt bereitstellt. |
| ReferenceService | `45` | Identifiziert die Dienstkennung eines früheren Umschlags, auf den sich das aktuelle Objekt bezieht. |
| ReferenceDate | `47` | Identifiziert das Datum eines früheren Umschlags, auf den sich das aktuelle Objekt bezieht. |
| ReferenceNumber | `50` | Identifiziert die Umschlagnummer eines früheren Umschlags, auf den sich das aktuelle Objekt bezieht. |
| DateCreated | `55` | Dargestellt in der Form CCYYMMDD, um das Datum anzugeben, an dem der geistige Inhalt der Objektdaten erstellt wurde, und nicht das Datum der Erstellung der physischen Darstellung. |
| TimeCreated | `60` | Dargestellt in der Form HHMMSS±HHMM, um die Zeit anzugeben, zu der der intellektuelle Inhalt des aktuellen Quellmaterials der Objektdaten erstellt wurde, und nicht die Erstellung der physischen Darstellung. |
| DigitalCreationDate | `62` | Dargestellt in der Form CCYYMMDD, um das Datum anzugeben, an dem die digitale Darstellung der Objektdaten erstellt wurde. |
| DigitalCreationTime | `63` | Dargestellt in der Form HHMMSS±HHMM, um die Zeit anzugeben, zu der die digitale Darstellung der Objektdaten erstellt wurde. |
| OriginatingProgram | `65` | Identifiziert den Programmtyp, der verwendet wurde, um die Objektdaten zu erzeugen. |
| ProgramVersion | `70` | Wird verwendet, um die Version des in 2:65 erwähnten Programms zu identifizieren. DataSet 2:70 ist ungültig, wenn 2:65 nicht vorhanden ist. |
| ObjectCycle | `75` | Bestehend aus einem Buchstaben. Wobei: 'a' = morgens, 'p' = abends, 'b' = beides. |
| Byline | `80` | Enthält Namen des Erstellers der Objektdaten, zB Autor, Fotograf oder Grafiker. |
| BylineTitle | `85` | Ein Verfassertitel ist der Titel des Erstellers oder der Ersteller von Objektdaten. |
| City | `90` | Identifiziert den Ursprungsort der Objektdaten gemäß den vom Anbieter festgelegten Richtlinien. |
| SubLocation | `92` | Identifiziert den Standort innerhalb einer Stadt, von dem die Objektdaten stammen, gemäß den vom Anbieter festgelegten Richtlinien. |
| ProvinceState | `95` | Identifiziert Provinz/Herkunftsstaat gemäß den vom Anbieter festgelegten Richtlinien. |
| PrimaryLocationCode | `100` | Gibt den Code des Landes/Hauptstandorts an, an dem das geistige Eigentum an den Objektdaten erstellt wurde, z. B. ein Foto aufgenommen wurde, ein Ereignis eingetreten ist. |
| PrimaryLocationName | `101` | Liefert den vollständigen, veröffentlichungsfähigen Namen des Landes/Hauptstandorts, an dem das geistige Eigentum an den Objektdaten erstellt wurde, gemäß den Richtlinien des Anbieters. |
| OriginalTransmissionReference | `103` | Ein Code, der den Ort der ursprünglichen Übertragung gemäß den Praktiken des Anbieters darstellt. |
| Headline | `105` | Ein veröffentlichbarer Eintrag, der eine Zusammenfassung des Inhalts der Objektdaten bereitstellt. |
| Credit | `110` | Identifiziert den Anbieter der Objektdaten, nicht unbedingt den Eigentümer/Ersteller. |
| Source | `115` | Der Name einer Person oder Partei, die eine Rolle in der Content-Lieferkette spielt. Dies kann eine Agentur, ein Mitglied einer Agentur, eine Einzelperson oder eine Kombination sein. |
| CopyrightNotice | `116` | Enthält alle erforderlichen Urheberrechtshinweise. |
| Contact | `118` | Identifiziert die Person oder Organisation, die weitere Hintergrundinformationen zu den Objektdaten liefern kann. |
| CaptionAbstract | `120` | Eine Textbeschreibung der Objektdaten, die insbesondere verwendet wird, wenn das Objekt kein Text ist. |
| WriterEditor | `122` | Identifizierung des Namens der Person, die an der Erstellung, Bearbeitung oder Korrektur der Objektdaten oder Bildunterschrift/Abstract beteiligt war. |
| RasterizedCaption | `125` | Bildbreite 460 Pixel und Bildhöhe 128 Pixel. Scanrichtung von unten nach oben, von links nach rechts. |
| ImageType | `130` | Die Ziffern 1 bis 4 geben die Anzahl der Komponenten in einem Bild an, in Einzel- oder Mehrfachumschlägen. |
| ImageOrientation | `131` | Gibt das Layout des Bildbereichs an. |
| LanguageIdentifier | `135` | Beschreibt die wichtigste Landessprache des Objekts gemäß den 2-Buchstaben-Codes von ISO 639:1988. |
| AudioType | `150` | Der Audiotyp. |
| AudioSamplingRate | `151` | Numerische Zeichen für die Abtastrate, die die Abtastrate in Hertz (Hz) darstellen. |
| AudioSamplingResolution | `152` | Die Anzahl der Bits in jedem Audio-Sample. |
| AudioDuration | `153` | Duration Bezeichnet in der Form HHMMSS die Laufzeit eines Audioobjektdatensatzes bei Wiedergabe mit der Geschwindigkeit, mit der er aufgenommen wurde. |
| AudioOutcue | `154` | Identifiziert den Inhalt des Endes von Audio-Objektdaten gemäß den vom Anbieter festgelegten Richtlinien. |
| ObjDataPreviewFileFormat | `200` | Eine Binärzahl, die das Dateiformat der ObjectData-Vorschau darstellt. |
| ObjDataPreviewFileFormatVer | `201` | Eine Binärzahl, die die bestimmte Version des ObjectData-Vorschaudateiformats darstellt, das in 2:200 angegeben ist. |
| ObjDataPreviewData | `202` | Die Vorschau der Objektdaten. |

### Siehe auch

* namensraum [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
