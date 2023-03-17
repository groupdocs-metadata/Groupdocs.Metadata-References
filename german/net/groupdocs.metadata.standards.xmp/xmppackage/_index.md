---
title: XmpPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Repräsentiert die Basisabstraktion für das XMPPaket.
type: docs
weight: 3490
url: /de/net/groupdocs.metadata.standards.xmp/xmppackage/
---
## XmpPackage class

Repräsentiert die Basisabstraktion für das XMP-Paket.

```csharp
public class XmpPackage : XmpMetadataContainer
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [XmpPackage](xmppackage)(string, string) | Initialisiert eine neue Instanz von[`XmpPackage`](../xmppackage) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Ruft den Namespace-URI ab. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Ruft das xmlns-Präfix ab. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Ruft den XML-Namespace ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Entfernt alle XMP-Eigenschaften. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Entfernt die Eigenschaft mit dem angegebenen Namen. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set)(string, bool) | Legt die boolesche Eigenschaft fest. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_6)(string, DateTime) | SätzeDateTime Eigentum. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_1)(string, double) | Legt die Double-Eigenschaft fest. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_5)(string, int) | Legt die ganzzahlige Eigenschaft fest. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_7)(string, string) | Legt die String-Eigenschaft fest. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_2)(string, XmpArray) | Legt den geerbten Wert fest[`XmpArray`](../xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_3)(string, XmpComplexType) | Legt den geerbten Wert fest[`XmpComplexType`](../xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_4)(string, XmpValueBase) | Legt den geerbten Wert fest[`XmpValueBase`](../xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Bemerkungen

**Erfahren Sie mehr**

* [Arbeiten mit XMP-Metadaten](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Beispiele

Dieses Beispiel zeigt, wie Sie ein benutzerdefiniertes XMP-Paket zu einer Datei in einem beliebigen unterstützten Format hinzufügen.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IXmp root = metadata.GetRootPackage() as IXmp;
    if (root != null)
    {
        var packet = new XmpPacketWrapper();

        var custom = new XmpPackage("gd", "https://groupdocs.com");
        custom.Set("gd:Copyright", "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.");
        custom.Set("gd:CreationDate", DateTime.Today);
        custom.Set("gd:Company", XmpArray.From(new [] { "Aspose", "GroupDocs" }, XmpArrayType.Ordered));

        packet.AddPackage(custom);
        root.XmpPackage = packet;

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Siehe auch

* class [XmpMetadataContainer](../xmpmetadatacontainer)
* namensraum [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
