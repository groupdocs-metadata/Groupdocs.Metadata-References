---
title: CanonCameraSettingsPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili pengaturan kamera CANON.
type: docs
weight: 2810
url: /id/net/groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/
---
## CanonCameraSettingsPackage class

Mewakili pengaturan kamera CANON.

```csharp
public sealed class CanonCameraSettingsPackage : CustomPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AFPoint](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/afpoint) { get; } | Mendapat AFPoint. |
| [CameraIso](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/cameraiso) { get; } | Mendapatkan iso kamera. |
| [CanonExposureMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/canonexposuremode) { get; } | Mendapatkan mode eksposur kanon. |
| [CanonFlashMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/canonflashmode) { get; } | Mendapatkan mode lampu kilat canon. |
| [CanonImageSize](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/canonimagesize) { get; } | Mendapatkan ukuran gambar kanon. |
| [ContinuousDrive](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/continuousdrive) { get; } | Mendapatkan drive berkelanjutan. |
| [Contrast](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/contrast) { get; } | Mendapat kontras. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [DigitalZoom](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/digitalzoom) { get; } | Mendapat zoom digital. |
| [EasyMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/easymode) { get; } | Mendapatkan mode mudah. |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/focusmode) { get; } | Mendapatkan mode fokus. |
| [FocusRange](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/focusrange) { get; } | Mendapat rentang fokus. |
| [ImageStabilization](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/imagestabilization) { get; } | Mendapat stabilisasi gambar. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [LensType](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/lenstype) { get; } | Mendapat jenis lensa. |
| [MacroMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/macromode) { get; } | Mendapatkan mode makro. |
| [MaxFocalLength](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/maxfocallength) { get; } | Mendapatkan panjang fokus maksimum. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [MeteringMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/meteringmode) { get; } | Mendapatkan mode pengukuran. |
| [MinFocalLength](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/minfocallength) { get; } | Mendapatkan panjang fokus minimum. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Quality](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/quality) { get; } | Mendapatkan kualitas. |
| [RecordMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/recordmode) { get; } | Mendapat mode rekam. |
| [Saturation](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/saturation) { get; } | Mendapatkan saturasi. |
| [SelfTimer](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/selftimer) { get; } | Mendapat timer otomatis. |
| [Sharpness](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/sharpness) { get; } | Mendapat ketajaman. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Lihat juga

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ruang nama [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
