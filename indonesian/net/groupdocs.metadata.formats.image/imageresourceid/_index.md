---
title: ImageResourceID
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Nomor ID standar sumber daya gambar. Tidak semua format file menggunakan semua ID. Beberapa informasi mungkin disimpan di bagian lain file.
type: docs
weight: 1750
url: /id/net/groupdocs.metadata.formats.image/imageresourceid/
---
## ImageResourceID enumeration

Nomor ID standar sumber daya gambar. Tidak semua format file menggunakan semua ID. Beberapa informasi mungkin disimpan di bagian lain file.

```csharp
public enum ImageResourceID
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| ResolutionInfo | `1005` | struktur ResolutionInfo. Lihat Lampiran A dalam dokumen PDF Panduan API Photoshop. |
| NamesOfAlphaChannels | `1006` | Nama saluran alfa sebagai rangkaian string Pascal. |
| Caption | `1008` | Judul sebagai string Pascal. |
| BorderInformation | `1009` | Informasi perbatasan. Berisi bilangan tetap (2 byte real, 2 byte pecahan) untuk lebar border, dan 2 byte untuk border unit (1 = inci, 2 = cm, 3 = titik, 4 = picas, 5 = kolom). |
| BackgroundColor | `1010` | Warna latar belakang. [Lihat lebih banyak.](http://www.adobe.com/devnet-apps/photoshop/fileformatashtml/#50577411_31265) |
| PrintFlags | `1011` | Cetak bendera. Serangkaian nilai boolean satu byte (lihat dialog Pengaturan Laman): label, tanda pangkas, bilah warna, tanda pendaftaran, negatif, balik, interpolasi, teks, tanda cetak. |
| Grayscale | `1012` | Informasi grayscale dan halfton multisaluran. |
| ColorHalftoning | `1013` | Informasi halftoning warna. |
| DuotoneHalftoning | `1014` | Informasi halftoning duotone. |
| GrayscaleFunction | `1015` | Fungsi transfer skala abu-abu dan multisaluran. |
| ColorTransferFunctions | `1016` | Fungsi transfer warna. |
| DuotoneTransferFunctions | `1017` | Fungsi transfer duotone. |
| DuotoneImageInformation | `1018` | Informasi gambar duotone. |
| EPSOptions | `1021` | opsi EPS. |
| QuickMaskInformation | `1022` | Informasi Topeng Cepat. 2 byte berisi ID saluran Quick Mask; 1- byte boolean menunjukkan apakah topeng awalnya kosong. |
| LayerStateInformation | `1024` | Informasi status lapisan. 2 byte berisi indeks lapisan target (0 = lapisan bawah). |
| WorkingPath | `1025` | Jalur kerja (tidak disimpan). Lihat Lihat Format sumber daya jalur. |
| LayersGroupInformation | `1026` | Informasi grup lapisan. 2 byte per lapisan berisi ID grup untuk grup penyeret. Lapisan dalam grup memiliki ID grup yang sama. |
| Iptc | `1028` | catatan IPTC-NAA. Berisi informasi File Info.... Lihat dokumentasi di folder IPTC dari folder Documentation. |
| ImageModeForRawFormat | `1029` | Mode gambar untuk file format mentah. |
| JpegQuality | `1030` | kualitas JPEG. Pribadi. |
| GridAndGuidesInfoPhotoshop4 | `1032` | Informasi kisi dan panduan. |
| ThumbnailResourcePhotoshop4 | `1033` | Sumber gambar mini hanya untuk Photoshop 4.0. |
| CopyrightFlagPhotoshop4 | `1034` | Tanda hak cipta. Boolean menunjukkan apakah gambar memiliki hak cipta. Dapat diatur melalui Property suite atau oleh pengguna di File Info... |
| UrlPhotoshop4 | `1035` | URL. Tangani string teks dengan pencari sumber daya yang seragam. Dapat diatur melalui Property suite atau oleh pengguna di File Info... |
| ThumbnailResourcePhotoshop5 | `1036` | Thumbnail resource (menggantikan resource 1033). Lihat Lihat Format sumber gambar mini. |
| GlobalAnglePhotoshop5 | `1037` | Sudut Global. 4 byte yang berisi bilangan bulat antara 0 dan 359, yang merupakan sudut pencahayaan global untuk lapisan efek. Jika tidak ada, dianggap 30. |
| IccProfilePhotoshop5 | `1039` | (Photoshop 5.0) Profil ICC. Byte mentah dari profil format ICC (International Color Consortium). Lihat ICC1v42_2006-05.pdf di folder Documentation dan icProfileHeader.h di Sample Code\Common\Includes. |
| WatermarkPhotoshop5 | `1040` | Tanda Air. Satu byte. |
| IccUntaggedProfilePhotoshop5 | `1041` | Profil Tanpa Tag ICC. 1 byte yang menonaktifkan penanganan profil yang diasumsikan saat membuka file. 1 = sengaja tidak ditandai. |
| TransparencyIndexPhotoshop6 | `1047` | Indeks Transparansi. 2 byte untuk indeks warna transparan, jika ada. |
| GlobalAltitudePhotoshop6 | `1049` | Ketinggian Global. Entri 4 byte untuk ketinggian. |
| SlicesPhotoshop6 | `1050` | Irisan (Photoshop 6). |
| WorkflowUrlPhotoshop6 | `1051` | URL Alur Kerja. Untaian kode uni. Photoshop 6. |
| AlphaIdentifiersPhotoshop6 | `1053` | Pengidentifikasi Alfa. Panjangnya 4 byte, diikuti dengan masing-masing 4 byte untuk setiap pengidentifikasi alfa. |
| UrlListPhotoshop6 | `1054` | Daftar Internal URL. Jumlah URL 4 byte, diikuti dengan panjang 4 byte, ID 4 byte, dan string Unicode untuk setiap hitungan. |
| VersionInfoPhotoshop6 | `1057` | Info Versi. Versi 4 byte, 1 byte hasRealMergedData , String Unicode: nama penulis, String Unicode: nama pembaca, versi file 4 byte. |
| ExifData1Photoshop7 | `1058` | data EXIF 1,[lihat lebih banyak](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) . |
| ExifData3Photoshop7 | `1059` | [ data EXIF3.](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) |
| XmpPhotoshop7 | `1060` | Metadata XMP. Info file sebagai deskripsi XML,[lihat lebih banyak](http://www.adobe.com/devnet/xmp) . |
| CaptionDigestPhotoshop7 | `1061` | Intisari teks. 16 byte: Keamanan Data RSA, algoritme intisari pesan MD5. |
| PrintScalePhotoshop7 | `1062` | Skala cetak. Gaya 2 byte (0 = terpusat, 1 = ukuran pas, 2 = ditentukan pengguna). 4 byte x lokasi (floating point). 4 byte y lokasi (floating point). skala 4 byte (floating point). |
| PixelAspectRatio | `1064` | Rasio Aspek Piksel. 4 byte (versi = 1 atau 2), 8 byte ganda, x / y piksel. Versi 2, mencoba memperbaiki nilai untuk NTSC dan PAL, yang sebelumnya dinonaktifkan dengan faktor kira-kira. 5%. |
| LayerComps | `1065` | Kompensasi Lapisan. 4 byte (versi deskriptor = 16), Descriptor. |
| LayerSelectionIds | `1069` | ID Pemilihan Lapisan. Hitungan 2 byte, berikut ini diulang untuk setiap hitungan: ID lapisan 4 byte. |
| PrintInfoCS2 | `1071` | Info cetak (Photoshop CS2). |
| LayerGroupEnabledIdCS2 | `1072` | Grup Lapisan ID yang Diaktifkan. 1 byte untuk setiap lapisan dalam dokumen, diulang berdasarkan panjang sumber daya. CATATAN: Grup lapisan memiliki penanda awal dan akhir (Photoshop CS2). |
| ColorSamplersResourceCS3 | `1073` | Sumber sampel warna. Lihat juga ID 1038 untuk format lama. |
| MeasurementScaleCS3 | `1074` | Skala Pengukuran. 4 byte (versi deskriptor = 16), Descriptor. |
| TimelineInformationCS3 | `1075` | Informasi Garis Waktu. 4 byte (versi deskriptor = 16), Descriptor. |
| SheetDisclosureCS3 | `1076` | Pengungkapan Lembar. 4 byte (versi deskriptor = 16), Descriptor. |
| PrintInformationCS5 | `1082` | Cetak Informasi (Photoshop CS5). |
| PrintStyleCS5 | `1083` | Gaya Cetak (Photoshop CS5). |
| MacintoshNSPrintInfoCS5 | `1084` | Macintosh NSPrintInfo. Info spesifik OS variabel untuk Macintosh. NSPrintInfo. Disarankan agar Anda tidak menafsirkan atau menggunakan data ini. (Photoshop CS5). |
| WindowsDevmodeCS5 | `1085` | Windows DEVMODE. Info spesifik OS variabel untuk Windows. MODE DEV. Disarankan agar Anda tidak menafsirkan atau menggunakan data ini. (Photoshop CS5). |
| AutoSaveFilePathCS6 | `1086` | Jalur File Simpan Otomatis. Untaian kode uni. (Photoshop CS6). |
| AutoSaveFormatCS6 | `1087` | Format Simpan Otomatis. Untaian kode uni. (Photoshop CS6). |
| PathSelectionStateCC | `1088` | Status Pemilihan Jalur. (Photoshop CC). |
| ImageReadyVariables | `7000` | Variabel Siap Gambar. Representasi XML dari definisi variabel. |
| ImageReadyDatasets | `7001` | Kumpulan data Image Ready. |
| PrintFlagsInformation | `10000` | Mencetak informasi bendera. versi 2 byte ( = 1), tanda potong tengah 1 byte, 1 byte ( = 0), nilai lebar bleed 4 byte, skala lebar bleed 2 byte. |

### Lihat juga

* ruang nama [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
