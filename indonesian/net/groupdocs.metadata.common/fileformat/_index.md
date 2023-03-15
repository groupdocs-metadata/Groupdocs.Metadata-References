---
title: FileFormat
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan format yang dikenali dari file yang dimuat.
type: docs
weight: 40
url: /id/net/groupdocs.metadata.common/fileformat/
---
## FileFormat enumeration

Merupakan format yang dikenali dari file yang dimuat.

```csharp
public enum FileFormat
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| Unknown | `0` | Jenis file tidak dikenali. |
| Presentation | `1` | File presentasi. Anda pasti familiar dengan file ekstensi PPTX dan PPT saat bekerja dengan Microsoft PowerPoint. Ini adalah format file Presentasi yang menyimpan kumpulan rekaman untuk mengakomodasi data presentasi seperti slide, bentuk, teks, animasi, video, audio dan objek tersemat. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/) . |
| Spreadsheet | `2` | File spreadsheet. File spreadsheet berisi data dalam bentuk baris dan kolom. Anda dapat membuka, melihat, dan mengedit file tersebut menggunakan aplikasi perangkat lunak spreadsheet seperti Microsoft Excel yang kini tersedia untuk sistem operasi Windows dan MacOS. Demikian pula, Google sheets adalah alat pembuatan dan pengeditan spreadsheet online gratis yang berfungsi dari browser web apa pun. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/) . |
| WordProcessing | `3` | File pengolah kata. File pengolah kata berisi informasi pengguna dalam format teks biasa atau teks kaya. Format file teks biasa berisi teks yang tidak diformat dan tidak ada pengaturan font atau halaman, dll. yang dapat diterapkan. Sebaliknya, format file teks kaya memungkinkan opsi pemformatan seperti pengaturan jenis font, gaya (tebal, miring, garis bawah, dll.), margin halaman, judul, poin dan angka, dan beberapa fitur pemformatan lainnya. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/) . |
| Diagram | `4` | File diagram. |
| Note | `5` | File catatan elektronik. Program pencatat seperti Microsoft OneNote memungkinkan Anda membuat, membuka, dan mengedit file catatan yang berisi bagian dan halaman untuk menyimpan catatan. Dokumen catatan bisa sesederhana dokumen teks dan juga lebih detail terdiri dari gambar digital, klip audio/video, dan gambar sketsa tangan. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/note-taking/) . |
| ProjectManagement | `6` | Format manajemen proyek. Pernahkah Anda menemukan dan bertanya-tanya apa itu file MPP atau bagaimana cara membukanya? MPP dan file serupa lainnya adalah format file Proyek yang dibuat oleh perangkat lunak Manajemen Proyek seperti Microsoft Project. Sebuah proyek file adalah kumpulan tugas, sumber daya, dan penjadwalannya untuk mendapatkan keluaran terukur dalam bentuk atau produk atau layanan. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/project-management/) . |
| Pdf | `7` | File PDF. Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan dari format file ini adalah untuk memperkenalkan standar untuk representasi dokumen dan bahan referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/view/pdf/) . |
| Tiff | `8` | Gambar TIFF. TIFF atau TIF, Tagged Image File Format, mewakili gambar raster yang dimaksudkan untuk digunakan pada berbagai perangkat yang mematuhi standar format file ini. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/image/tiff/) . |
| Jpeg | `9` | Gambar JPEG. JPEG adalah jenis format gambar yang disimpan menggunakan metode kompresi lossy. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/jpeg/) . |
| Psd | `10` | Gambar PSD. PSD, Dokumen Photoshop, mewakili format file asli Adobe Photoshop yang digunakan untuk perancangan dan pengembangan grafis. File PSD dapat mencakup lapisan gambar, lapisan penyesuaian, masker lapisan, anotasi, informasi file, kata kunci, dan elemen khusus Photoshop lainnya . Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/psd/) . |
| Jpeg2000 | `11` | Gambar Jpeg2000. JPEG 2000 (JPX) adalah sistem pengkodean gambar dan standar kompresi gambar yang canggih. Didesain, menggunakan teknologi wavelet JPEG 2000 dapat mengkodekan konten lossless dalam kualitas apa pun sekaligus. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/jp2/) . |
| Gif | `12` | Gambar GIF. GIF atau Graphical Interchange Format adalah jenis gambar yang sangat terkompresi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/gif/) . |
| Png | `13` | Gambar PNG. PNG, Portable Network Graphics, mengacu pada jenis format file gambar raster yang menggunakan kompresi lossless. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/png/) . |
| Bmp | `14` | Gambar BMP. File berekstensi .BMP mewakili file Gambar Bitmap yang digunakan untuk menyimpan gambar digital bitmap. Gambar ini tidak tergantung pada adaptor grafis dan juga disebut file bitmap (DIB) independen perangkat format. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/bmp/) . |
| Dicom | `15` | Gambar DICOM. DICOM adalah singkatan dari Digital Imaging and Communications in Medicine dan berkaitan dengan bidang Informatika Medis. DICOM adalah kombinasi dari definisi format file dan protokol komunikasi jaringan. Pelajari lebih lanjut tentang format file ini[ Di Sini](https://wiki.fileformat.com/image/dicom/) . |
| WebP | `16` | Gambar WEBP. WebP, diperkenalkan oleh Google, adalah format file gambar web raster modern yang didasarkan pada kompresi lossless dan lossy. Ini memberikan kualitas gambar yang sama sekaligus mengurangi ukuran gambar. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/webp/) . |
| Emf | `17` | Gambar EMF. Enhanced metafile format (EMF) menyimpan gambar grafis perangkat secara independen. Metafile EMF terdiri dari catatan panjang variabel dalam urutan kronologis yang dapat merender gambar yang disimpan setelah diuraikan pada perangkat keluaran apa pun. Pelajari lebih lanjut tentang ini format file[Di Sini](https://wiki.fileformat.com/image/emf/) . |
| Wmf | `18` | Gambar WMF. File dengan ekstensi WMF mewakili Microsoft Windows Metafile (WMF) untuk menyimpan data gambar format vektor dan bitmap. Agar lebih akurat, WMF termasuk dalam kategori format file vektor dari format file Grafik yaitu perangkat independent. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/wmf/) . |
| DjVu | `19` | File DjVu. DjVu adalah format file grafik yang ditujukan untuk dokumen dan buku yang dipindai terutama yang berisi kombinasi teks, gambar, gambar dan foto. Ini dikembangkan oleh AT&amp;T Labs. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/djvu/) . |
| Wav | `20` | File audio WAV. WAV, dikenal dengan WAVE (Waveform Audio File Format), adalah bagian dari spesifikasi Resource Interchange File Format (RIFF) Microsoft untuk menyimpan file audio digital. Format ini tidak menerapkan kompresi apa pun ke bitstream dan menyimpan rekaman audio dengan sampling rate dan bitrate yang berbeda. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/audio/wav/) . |
| Mp3 | `21` | File audio Mp3. File dengan ekstensi MP3 adalah format file yang disandikan secara digital untuk file audio yang secara formal didasarkan pada MPEG-1 Audio Layer III atau MPEG-2 Audio Layer III. Dikembangkan oleh Moving Picture Experts Group ( MPEG) yang menggunakan kompresi audio Lapisan 3. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/audio/mp3/) . |
| Avi | `22` | Video AVI. Format file AVI adalah format file wadah multimedia Audio Video yang diperkenalkan oleh Microsoft. File ini menampung data audio dan video yang dibuat dan dikompres menggunakan beberapa codec (Coder/Decoder) seperti Xvid dan DivX. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/video/avi/) . |
| Flv | `23` | Video FLV. |
| Asf | `24` | Video ASF. Advanced Systems Format (ASF) adalah wadah multimedia digital yang dirancang terutama untuk menyimpan dan mentransmisikan aliran media. Microsoft Windows Media Video (WMV) adalah format video terkompresi dan Microsoft Windows Media Audio (WMA) adalah format video terkompresi format audio terkompresi bersama dengan metadata tambahan dalam penampung ASF yang dikembangkan oleh Microsoft. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/video/wmv/) . |
| Mov | `25` | Video QuickTime. Format File Mov atau QuickTime adalah wadah multimedia yang dikembangkan oleh Apple: berisi satu atau lebih trek, setiap trek berisi jenis data tertentu yaitu Video, Audio, teks dll. Format Mov kompatibel baik dalam Sistem Windows dan Macintosh. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/video/mov/) . |
| Matroska | `26` | Video yang disandikan dengan wadah multimedia Matroska. |
| Zip | `27` | Arsip ZIP. Ekstensi file ZIP mewakili arsip yang dapat menampung satu atau lebih file atau direktori. Arsip dapat memiliki kompresi yang diterapkan pada file yang disertakan untuk mengurangi ukuran file ZIP. Format file ZIP dibuat publik kembali pada Februari 1989 oleh Phil Katz untuk mencapai pengarsipan file dan folder. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/compression/zip/) . |
| VCard | `28` | File VCard. VCF (Virtual Card Format) atau vCard adalah format file digital untuk menyimpan informasi kontak. Format ini banyak digunakan untuk pertukaran data di antara aplikasi pertukaran informasi populer. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/email/vcf/) . |
| Epub | `29` | Buku elektronik EPUB. File dengan ekstensi .EPUB adalah format file e-book yang menyediakan format publikasi digital standar untuk penerbit dan konsumen. Format ini sudah sangat umum sekarang sehingga didukung oleh banyak e-reader dan aplikasi perangkat lunak. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/ebook/epub/) . |
| OpenType | `30` | Font OpenType. |
| Dxf | `31` | Gambar DXF (Drawing Exchange Format). DXF, Drawing Interchange Format, atau Drawing Exchange Format, adalah representasi data yang ditandai dari file gambar AutoCAD. Setiap elemen dalam file memiliki nomor integer awalan yang disebut kode grup. Belajar lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/cad/dxf/) . |
| Dwg | `32` | Gambar DWG. File dengan ekstensi DWG mewakili file biner eksklusif yang digunakan untuk memuat data desain 2D dan 3D. Seperti DXF, yang merupakan file ASCII, DWG mewakili format file biner untuk gambar CAD (Computer Aided Design). Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/cad/dwg/) . |
| Eml | `33` | Pesan email EML. Format file EML mewakili pesan email yang disimpan menggunakan Outlook dan aplikasi lain yang relevan. Hampir semua klien email mendukung format file ini karena sesuai dengan Standar Format Pesan Internet RFC-822. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/email/eml/) . |
| Msg | `34` | Pesan email MSG. MSG adalah format file yang digunakan oleh Microsoft Outlook dan Exchange untuk menyimpan pesan email, kontak, janji temu, atau tugas lainnya. Pesan tersebut mungkin berisi satu atau beberapa kolom email, dengan pengirim, penerima, subjek, tanggal, dan badan pesan, atau informasi kontak, keterangan janji temu, dan satu atau beberapa spesifikasi tugas. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/email/msg/) . |
| Torrent | `35` | File torrent yang berisi metadata tentang file dan folder yang akan didistribusikan. |
| Heif | `36` | Gambar HEIF/HEIC. |

### Lihat juga

* ruang nama [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
