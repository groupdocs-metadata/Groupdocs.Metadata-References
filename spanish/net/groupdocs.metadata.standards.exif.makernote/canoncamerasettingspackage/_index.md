---
title: CanonCameraSettingsPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa la configuración de la cámara CANON.
type: docs
weight: 2810
url: /es/net/groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/
---
## CanonCameraSettingsPackage class

Representa la configuración de la cámara CANON.

```csharp
public sealed class CanonCameraSettingsPackage : CustomPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AFPoint](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/afpoint) { get; } | Obtiene el AFPoint. |
| [CameraIso](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/cameraiso) { get; } | Obtiene la cámara iso. |
| [CanonExposureMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/canonexposuremode) { get; } | Obtiene el modo de exposición canon. |
| [CanonFlashMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/canonflashmode) { get; } | Obtiene el modo flash canon. |
| [CanonImageSize](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/canonimagesize) { get; } | Obtiene el tamaño de la imagen canon. |
| [ContinuousDrive](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/continuousdrive) { get; } | Obtiene la unidad continua. |
| [Contrast](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/contrast) { get; } | Obtiene el contraste. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DigitalZoom](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/digitalzoom) { get; } | Obtiene el zoom digital. |
| [EasyMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/easymode) { get; } | Obtiene el modo fácil. |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/focusmode) { get; } | Obtiene el modo de enfoque. |
| [FocusRange](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/focusrange) { get; } | Obtiene el rango de enfoque. |
| [ImageStabilization](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/imagestabilization) { get; } | Obtiene la estabilización de imagen. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [LensType](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/lenstype) { get; } | Obtiene el tipo de lente. |
| [MacroMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/macromode) { get; } | Obtiene el modo macro. |
| [MaxFocalLength](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/maxfocallength) { get; } | Obtiene la longitud máxima de la focal. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [MeteringMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/meteringmode) { get; } | Obtiene el modo de medición. |
| [MinFocalLength](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/minfocallength) { get; } | Obtiene la longitud mínima de la focal. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Quality](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/quality) { get; } | Obtiene la calidad. |
| [RecordMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/recordmode) { get; } | Obtiene el modo de grabación. |
| [Saturation](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/saturation) { get; } | Obtiene la saturación. |
| [SelfTimer](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/selftimer) { get; } | Obtiene el autodisparador. |
| [Sharpness](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/sharpness) { get; } | Obtiene la nitidez. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Ver también

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* espacio de nombres [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
