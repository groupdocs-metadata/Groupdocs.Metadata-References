---
title: ExifPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Repräsentiert ein EXIFMetadatenpaket Exchangeable Image File Format.
type: docs
weight: 2790
url: /de/net/groupdocs.metadata.standards.exif/exifpackage/
---
## ExifPackage class

Repräsentiert ein EXIF-Metadatenpaket (Exchangeable Image File Format).

```csharp
public class ExifPackage : ExifDictionaryBasePackage
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ExifPackage](exifpackage)() | Initialisiert eine neue Instanz von[`ExifPackage`](../exifpackage) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Artist](../../groupdocs.metadata.standards.exif/exifpackage/artist) { get; set; } | Ruft den Namen des Kamerabesitzers, Fotografen oder Bilderstellers ab oder legt ihn fest. |
| [Copyright](../../groupdocs.metadata.standards.exif/exifpackage/copyright) { get; set; } | Ruft den Urheberrechtshinweis ab oder legt ihn fest. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [DateTime](../../groupdocs.metadata.standards.exif/exifpackage/datetime) { get; set; } | Ruft das Datum und die Uhrzeit der Bilderstellung ab oder legt sie fest. Im EXIF-Standard ist dies das Datum und die Uhrzeit, zu der die Datei geändert wurde. |
| [ExifIfdPackage](../../groupdocs.metadata.standards.exif/exifpackage/exififdpackage) { get; } | Ruft die EXIF-IFD-Daten ab. |
| [GpsPackage](../../groupdocs.metadata.standards.exif/exifpackage/gpspackage) { get; } | Ruft die GPS-Daten ab. |
| [ImageDescription](../../groupdocs.metadata.standards.exif/exifpackage/imagedescription) { get; set; } | Liest oder setzt eine Zeichenkette, die den Titel des Bildes angibt. Es kann ein Kommentar sein wie "1988 Firmenpicknick" oder ähnliches. |
| [ImageLength](../../groupdocs.metadata.standards.exif/exifpackage/imagelength) { get; set; } | Ruft die Anzahl der Bilddatenzeilen ab oder legt sie fest. |
| [ImageWidth](../../groupdocs.metadata.standards.exif/exifpackage/imagewidth) { get; set; } | Ruft die Anzahl der Bilddatenspalten ab oder legt sie fest, gleich der Anzahl der Pixel pro Zeile. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Ruft das TIFF-Tag mit der angegebenen ID ab. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [Make](../../groupdocs.metadata.standards.exif/exifpackage/make) { get; set; } | Ruft den Hersteller des Aufzeichnungsgeräts ab oder legt ihn fest. Dies ist der Hersteller des DSC, Scanners, Videodigitalisierers oder anderer Geräte, die das Bild erzeugt haben. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [Model](../../groupdocs.metadata.standards.exif/exifpackage/model) { get; set; } | Ruft den Modellnamen oder die Modellnummer des Geräts ab oder legt ihn fest. Dies ist der Modellname oder die Modellnummer des DSC, Scanners, Videodigitalisierers oder anderen Geräts, das das Bild erzeugt hat. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [Software](../../groupdocs.metadata.standards.exif/exifpackage/software) { get; set; } | Ruft den Namen und die Version der Software oder Firmware der Kamera oder des Bildeingabegeräts ab oder legt sie fest, die bzw. das zum Generieren des Bilds verwendet wird. |
| [Thumbnail](../../groupdocs.metadata.standards.exif/exifpackage/thumbnail) { get; } | Ruft das Miniaturbild des Bildes ab, das als Byte-Array dargestellt wird. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Entfernt alle im Paket gespeicherten TIFF-Tags. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Entfernt die Eigenschaft mit der angegebenen ID. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Fügt das angegebene Tag hinzu oder ersetzt es. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Erstellt eine Liste aus dem Paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Bemerkungen

**Erfahren Sie mehr**

* [Arbeiten mit EXIF-Metadaten](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Beispiele

Dieses Codebeispiel zeigt, wie allgemeine EXIF-Eigenschaften aktualisiert werden.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        // Setzen Sie das EXIF-Paket, falls es fehlt
        if (root.ExifPackage == null)
        {
            root.ExifPackage = new ExifPackage();
        }

        root.ExifPackage.Copyright = "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.";
        root.ExifPackage.ImageDescription = "test image";
        root.ExifPackage.Software = "GroupDocs.Metadata";

        // ...

        root.ExifPackage.ExifIfdPackage.BodySerialNumber = "test";
        root.ExifPackage.ExifIfdPackage.CameraOwnerName = "GroupDocs";
        root.ExifPackage.ExifIfdPackage.UserComment = "test comment";

        // ...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Siehe auch

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* namensraum [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
