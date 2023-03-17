---
title: ExifGpsPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili metadata GPS dalam paket metadata EXIF.
type: docs
weight: 2770
url: /id/net/groupdocs.metadata.standards.exif/exifgpspackage/
---
## ExifGpsPackage class

Mewakili metadata GPS dalam paket metadata EXIF.

```csharp
public sealed class ExifGpsPackage : ExifDictionaryBasePackage
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [ExifGpsPackage](exifgpspackage)() | Menginisialisasi instance baru dari[`ExifGpsPackage`](../exifgpspackage) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Altitude](../../groupdocs.metadata.standards.exif/exifgpspackage/altitude) { get; set; } | Mendapat atau mengatur ketinggian berdasarkan referensi di[`AltitudeRef`](./altituderef) . Satuan acuannya adalah meter. |
| [AltitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/altituderef) { get; set; } | Mendapatkan atau mengatur ketinggian yang digunakan sebagai ketinggian referensi. Jika referensinya adalah permukaan laut dan ketinggiannya di atas permukaan laut, diberikan 0. Jika ketinggian di bawah permukaan laut, diberi nilai 1 dan ketinggian ditunjukkan sebagai nilai absolut di[`Altitude`](./altitude) tag. |
| [AreaInformation](../../groupdocs.metadata.standards.exif/exifgpspackage/areainformation) { get; set; } | Mendapat atau mengatur string karakter yang merekam nama area GPS. Byte pertama menunjukkan kode karakter yang digunakan, diikuti dengan nama area GPS. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [DataDegreeOfPrecision](../../groupdocs.metadata.standards.exif/exifgpspackage/datadegreeofprecision) { get; set; } | Mendapat atau menyetel DOP GPS (tingkat presisi data). Nilai HDOP ditulis selama pengukuran dua dimensi, dan PDOP selama pengukuran tiga dimensi. |
| [DateStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/datestamp) { get; set; } | Mendapat atau menyetel informasi tanggal dan waktu perekaman string karakter relatif terhadap UTC (Waktu Universal Terkoordinasi). Formatnya YYYY:MM:DD. |
| [DestBearing](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearing) { get; set; } | Mendapat atau menyetel bantalan GPS ke titik tujuan. Rentang nilainya dari 0,00 hingga 359,99. |
| [DestBearingRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearingref) { get; set; } | Mendapat atau mengatur referensi GPS yang digunakan untuk memberikan bantalan ke titik tujuan. 'T' menunjukkan arah yang benar dan 'M' adalah arah magnetik. |
| [DestDistance](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistance) { get; set; } | Mendapat atau mengatur jarak GPS ke titik tujuan. |
| [DestDistanceRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistanceref) { get; set; } | Mendapat atau menyetel unit GPS yang digunakan untuk menyatakan jarak ke titik tujuan. 'K', 'M' dan 'N' mewakili kilometer, mil, dan knot. |
| [DestLatitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatitude) { get; set; } | Mendapat atau menyetel lintang GPS dari titik tujuan. |
| [DestLatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatituderef) { get; set; } | Mendapat atau menetapkan nilai GPS yang menunjukkan apakah garis lintang titik tujuan adalah garis lintang utara atau selatan. Nilai ASCII 'N' menunjukkan garis lintang utara, dan 'S' adalah garis lintang selatan. |
| [DestLongitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongitude) { get; set; } | Mendapat atau menyetel bujur GPS dari titik tujuan. |
| [DestLongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongituderef) { get; set; } | Mendapat atau menetapkan nilai GPS yang menunjukkan apakah bujur titik tujuan adalah bujur timur atau bujur barat. ASCII 'E' menunjukkan bujur timur, dan 'W' adalah bujur barat. |
| [Differential](../../groupdocs.metadata.standards.exif/exifgpspackage/differential) { get; set; } | Mendapat atau menetapkan nilai GPS yang menunjukkan apakah koreksi diferensial diterapkan ke penerima GPS. |
| [GpsTrack](../../groupdocs.metadata.standards.exif/exifgpspackage/gpstrack) { get; set; } | Mendapat atau mengatur arah pergerakan penerima GPS. |
| [ImgDirection](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirection) { get; set; } | Mendapat atau menyetel arah GPS dari gambar saat diambil. Rentang nilainya dari 0,00 hingga 359,99. |
| [ImgDirectionRef](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirectionref) { get; set; } | Mendapatkan atau menyetel referensi GPS untuk memberikan arah gambar saat ditangkap. 'T' menunjukkan arah sebenarnya dan 'M' adalah arah magnetik. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Mendapat tag TIFF dengan id yang ditentukan. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Latitude](../../groupdocs.metadata.standards.exif/exifgpspackage/latitude) { get; set; } | Mendapat atau menyetel lintang GPS. |
| [LatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/latituderef) { get; set; } | Mendapat atau menyetel nilai GPS yang menunjukkan apakah lintang utara atau lintang selatan. |
| [Longitude](../../groupdocs.metadata.standards.exif/exifgpspackage/longitude) { get; set; } | Mendapat atau menyetel bujur GPS. |
| [LongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/longituderef) { get; set; } | Mendapat atau menyetel nilai GPS yang menunjukkan apakah bujur timur atau bujur barat. |
| [MapDatum](../../groupdocs.metadata.standards.exif/exifgpspackage/mapdatum) { get; set; } | Mendapat atau menyetel data survei geodetik yang digunakan oleh penerima GPS. |
| [MeasureMode](../../groupdocs.metadata.standards.exif/exifgpspackage/measuremode) { get; set; } | Mendapatkan atau menyetel mode pengukuran GPS. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [ProcessingMethod](../../groupdocs.metadata.standards.exif/exifgpspackage/processingmethod) { get; set; } | Mendapat atau menetapkan string karakter yang merekam nama metode yang digunakan untuk pencarian lokasi. Byte pertama menunjukkan kode karakter yang digunakan, dan ini diikuti dengan nama metode. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Satellites](../../groupdocs.metadata.standards.exif/exifgpspackage/satellites) { get; set; } | Mendapatkan atau menyetel satelit GPS yang digunakan untuk pengukuran. Tag ini dapat digunakan untuk mendeskripsikan jumlah satelit, nomor ID, sudut elevasi, azimuth, SNR, dan informasi lainnya dalam notasi ASCII. Formatnya tidak ditentukan. Jika penerima GPS tidak mampu melakukan pengukuran, nilai tag harus disetel ke NULL. |
| [Speed](../../groupdocs.metadata.standards.exif/exifgpspackage/speed) { get; set; } | Mendapat atau mengatur kecepatan pergerakan penerima GPS. |
| [SpeedRef](../../groupdocs.metadata.standards.exif/exifgpspackage/speedref) { get; set; } | Mendapat atau mengatur unit yang digunakan untuk menyatakan kecepatan gerakan penerima GPS. 'K' 'M' dan 'N' mewakili kilometer per jam, mil per jam, dan knot. |
| [Status](../../groupdocs.metadata.standards.exif/exifgpspackage/status) { get; set; } | Mendapatkan atau menyetel status penerima GPS saat gambar direkam. |
| [TimeStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/timestamp) { get; set; } | Mendapat atau menetapkan waktu sebagai UTC (Waktu Universal Terkoordinasi). TimeStamp dinyatakan sebagai tiga nilai RATIONAL yang memberikan jam, menit, dan detik. |
| [TrackRef](../../groupdocs.metadata.standards.exif/exifgpspackage/trackref) { get; set; } | Mendapat atau mengatur referensi untuk memberikan arah gerakan penerima GPS. 'T' menunjukkan arah yang benar dan 'M' adalah arah magnetik. |
| [VersionID](../../groupdocs.metadata.standards.exif/exifgpspackage/versionid) { get; set; } | Mendapat atau menyetel versi GPS IFD. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Menghapus semua tag TIFF yang disimpan dalam paket. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Menghapus properti dengan id yang ditentukan. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Menambahkan atau mengganti tag yang ditentukan. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Membuat daftar dari paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Lihat juga

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* ruang nama [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
