---
title: XmpPackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt basisabstractie voor XMPpakket.
type: docs
weight: 3490
url: /nl/net/groupdocs.metadata.standards.xmp/xmppackage/
---
## XmpPackage class

Vertegenwoordigt basisabstractie voor XMP-pakket.

```csharp
public class XmpPackage : XmpMetadataContainer
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [XmpPackage](xmppackage)(string, string) | Initialiseert een nieuw exemplaar van het[`XmpPackage`](../xmppackage) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Haalt de naamruimte-URI op. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Haalt het xmlns-voorvoegsel op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Haalt de XML-naamruimte op. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Verwijdert alle XMP-eigenschappen. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Converteert de XMP-waarde naar de XML-weergave. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Verwijdert de eigenschap met de opgegeven naam. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set)(string, bool) | Stelt booleaanse eigenschap in. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_6)(string, DateTime) | setsDateTime eigendom. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_1)(string, double) | Stelt dubbele eigenschap in. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_5)(string, int) | Stelt integer-eigenschap in. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_7)(string, string) | Stelt tekenreekseigenschap in. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_2)(string, XmpArray) | Stelt de waarde in die is overgenomen van[`XmpArray`](../xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_3)(string, XmpComplexType) | Stelt de waarde in die is overgenomen van[`XmpComplexType`](../xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_4)(string, XmpValueBase) | Stelt de waarde in die is overgenomen van[`XmpValueBase`](../xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Opmerkingen

**Kom meer te weten**

* [Werken met XMP-metagegevens](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Voorbeelden

Dit voorbeeld laat zien hoe u een aangepast XMP-pakket kunt toevoegen aan een bestand met een willekeurige ondersteunde indeling.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IXmp root = metadata.GetRootPackage() as IXmp;
    if (root != null)
    {
        var packet = new XmpPacketWrapper();

        var custom = new XmpPackage("gd", "https://groepdocs.com");
        custom.Set("gd:Copyright", "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.");
        custom.Set("gd:CreationDate", DateTime.Today);
        custom.Set("gd:Company", XmpArray.From(new [] { "Aspose", "GroupDocs" }, XmpArrayType.Ordered));

        packet.AddPackage(custom);
        root.XmpPackage = packet;

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Zie ook

* class [XmpMetadataContainer](../xmpmetadatacontainer)
* naamruimte [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
