---
title: XmpResourceRef
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Repräsentiert einen mehrteiligen Verweis auf eine Ressource. Wird verwendet um frühere Versionen Originale von Wiedergaben Originale für abgeleitete Dokumente usw. anzuzeigen.
type: docs
weight: 3550
url: /de/net/groupdocs.metadata.standards.xmp/xmpresourceref/
---
## XmpResourceRef class

Repräsentiert einen mehrteiligen Verweis auf eine Ressource. Wird verwendet, um frühere Versionen, Originale von Wiedergaben, Originale für abgeleitete Dokumente usw. anzuzeigen.

```csharp
public sealed class XmpResourceRef : XmpComplexType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [XmpResourceRef](xmpresourceref)() | Initialisiert eine neue Instanz von[`XmpResourceRef`](../xmpresourceref) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternatePaths](../../groupdocs.metadata.standards.xmp/xmpresourceref/alternatepaths) { get; set; } | Ruft die Fallback-Dateipfade oder -URLs der referenzierten Ressource ab oder legt sie fest. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [DocumentID](../../groupdocs.metadata.standards.xmp/xmpresourceref/documentid) { get; set; } | Ruft den Wert der Eigenschaft xmpMM:DocumentID aus der referenzierten Ressource ab oder legt ihn fest. |
| [FilePath](../../groupdocs.metadata.standards.xmp/xmpresourceref/filepath) { get; set; } | Ruft den Dateipfad oder die URL der referenzierten Ressource ab oder legt ihn fest. |
| [InstanceID](../../groupdocs.metadata.standards.xmp/xmpresourceref/instanceid) { get; set; } | Ruft den Wert der xmpMM:InstanceID-Eigenschaft von der referenzierten Ressource ab oder legt ihn fest. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ruft die ab[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) mit dem angegebenen Namen. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [LastModifyDate](../../groupdocs.metadata.standards.xmp/xmpresourceref/lastmodifydate) { get; set; } | Holt oder setzt den Wert von stEvt: wann die Datei das letzte Mal geschrieben wurde. |
| [Manager](../../groupdocs.metadata.standards.xmp/xmpresourceref/manager) { get; set; } | Ruft den xmpMM:Manager der referenzierten Ressource ab oder legt ihn fest. |
| [ManagerVariant](../../groupdocs.metadata.standards.xmp/xmpresourceref/managervariant) { get; set; } | Ruft den xmpMM:Manager der referenzierten Ressource ab oder legt ihn fest. |
| [ManageTo](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageto) { get; set; } | Ruft xmpMM:ManageTo der referenzierten Ressource ab oder legt sie fest. |
| [ManageUI](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageui) { get; set; } | Ruft die xmpMM:ManageUI der referenzierten Ressource ab oder legt sie fest. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Ruft die Namespace-URIs ab, die in verwendet werden[`XmpComplexType`](../xmpcomplextype) Instanz. |
| [PartMapping](../../groupdocs.metadata.standards.xmp/xmpresourceref/partmapping) { get; set; } | Ruft den Namen oder URI einer Zuordnungsfunktion ab oder legt sie fest, die verwendet wird, um fromPart dem toPart zuzuordnen. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Ruft die Namespace-Präfixe ab, die in verwendet werden[`XmpComplexType`](../xmpcomplextype) Instanz. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [RenditionClass](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionclass) { get; set; } | Ruft den Wert der Eigenschaft xmpMM:RenditionClass aus der referenzierten Ressource ab oder legt ihn fest. |
| [RenditionParams](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionparams) { get; set; } | Ruft den Wert der Eigenschaft xmpMM:RenditionParams aus der referenzierten Ressource ab oder legt ihn fest. |
| [VersionID](../../groupdocs.metadata.standards.xmp/xmpresourceref/versionid) { get; set; } | Ruft den Wert der Eigenschaft xmpMM:RenditionParams aus der referenzierten Ressource ab oder legt ihn fest. |

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
