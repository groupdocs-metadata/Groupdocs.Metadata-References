---
title: XmpResourceEvent
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt ein übergeordnetes Ereignis dar das bei der Verarbeitung einer Ressource aufgetreten ist.
type: docs
weight: 3540
url: /de/net/groupdocs.metadata.standards.xmp/xmpresourceevent/
---
## XmpResourceEvent class

Stellt ein übergeordnetes Ereignis dar, das bei der Verarbeitung einer Ressource aufgetreten ist.

```csharp
public sealed class XmpResourceEvent : XmpComplexType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [XmpResourceEvent](xmpresourceevent)() | Initialisiert eine neue Instanz von[`XmpResourceEvent`](../xmpresourceevent) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Action](../../groupdocs.metadata.standards.xmp/xmpresourceevent/action) { get; set; } | Ruft die aufgetretene Aktion ab oder legt sie fest. |
| [Changed](../../groupdocs.metadata.standards.xmp/xmpresourceevent/changed) { get; set; } | Ruft eine durch Semikolons getrennte Liste der Teile der Ressource ab, die seit dem vorherigen Ereignisverlauf geändert wurden, oder legt diese fest. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [InstanceID](../../groupdocs.metadata.standards.xmp/xmpresourceevent/instanceid) { get; set; } | Ruft den Wert der xmpMM:InstanceID-Eigenschaft für die geänderte (Ausgabe-)Ressource ab oder legt ihn fest. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Ruft die Namespace-URIs ab, die in verwendet werden[`XmpComplexType`](../xmpcomplextype) Instanz. |
| [Parameters](../../groupdocs.metadata.standards.xmp/xmpresourceevent/parameters) { get; set; } | Ruft die zusätzliche Beschreibung der Aktion ab oder setzt sie. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Ruft die Namespace-Präfixe ab, die in verwendet werden[`XmpComplexType`](../xmpcomplextype) Instanz. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [SoftwareAgent](../../groupdocs.metadata.standards.xmp/xmpresourceevent/softwareagent) { get; set; } | Ruft den Softwareagenten ab oder legt ihn fest, der die Aktion ausgeführt hat. |
| [When](../../groupdocs.metadata.standards.xmp/xmpresourceevent/when) { get; set; } | Ruft den Zeitstempel des Auftretens der Aktion ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | Ruft den Namespace-URI ab, der dem angegebenen Präfix zugeordnet ist. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | Gibt den in der Zeichenfolge enthaltenen Wert im XMP-Format zurück. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | Gibt a zurückString die diese Instanz darstellt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Siehe auch

* class [XmpComplexType](../xmpcomplextype)
* namensraum [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
