---
title: IptcApplicationRecordDataSet
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mendefinisikan nomor DataSet Catatan Aplikasi IPTC.
type: docs
weight: 2890
url: /id/net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/
---
## IptcApplicationRecordDataSet enumeration

Mendefinisikan nomor DataSet Catatan Aplikasi IPTC.

```csharp
public enum IptcApplicationRecordDataSet
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| RecordVersion | `0` | Mewakili versi rekaman. Biner. Selalu 2 dalam format JPEG. |
| ObjectTypeReference | `3` | Referensi tipe objek. Pola yang digunakan: "/\d{2}:[\w\s]{0,64}?/". |
| ObjectAttributeReference | `4` | Referensi atribut objek. |
| ObjectName | `5` | Digunakan sebagai referensi steno untuk objek. |
| EditStatus | `7` | Status objectdata, sesuai praktek provider. |
| EditorialUpdate | `8` | Menunjukkan jenis pembaruan yang disediakan objek ini ke objek sebelumnya. |
| Urgency | `10` | Menentukan urgensi editorial konten dan belum tentu prioritas penanganan amplop (lihat 1:60, Prioritas Amplop). |
| SubjectReference | `12` | Referensi subjek. |
| Category | `15` | Mengidentifikasi subjek objekdata menurut pendapat penyedia. |
| SupplementalCategory | `20` | Kategori tambahan semakin menyempurnakan subjek dari data objek. Hanya satu kategori tambahan yang boleh dimuat dalam setiap Kumpulan Data. Kategori tambahan dapat mencakup salah satu kategori yang diakui seperti yang digunakan dalam 2:15. |
| FixtureIdentifier | `22` | Pengidentifikasi perlengkapan. |
| Keywords | `25` | Digunakan untuk menunjukkan kata-kata pengambilan informasi tertentu. Setiap kata kunci menggunakan Kumpulan Data Kata Kunci tunggal. Beberapa kata kunci menggunakan beberapa Set Data Kata Kunci. |
| ContentLocationCode | `26` | Menunjukkan kode negara/lokasi geografis yang dirujuk oleh konten objek. |
| ContentLocationName | `27` | Memberikan nama lengkap negara/lokasi geografis yang dapat dipublikasikan yang dirujuk oleh konten objek, sesuai pedoman provider. |
| ReleaseDate | `30` | Menunjuk dalam bentuk CCYYMMDD tanggal paling awal penyedia bermaksud objek yang akan digunakan. Mengikuti standar ISO 8601. |
| ReleaseTime | `35` | Menunjuk dalam bentuk HHMMSS±HHMM saat paling awal penyedia menginginkan objek untuk digunakan. Mengikuti standar ISO 8601. |
| ExpirationDate | `37` | Menunjuk dalam bentuk CCYYMMDD tanggal terakhir penyedia atau pemilik menginginkan data objek yang akan digunakan. Mengikuti standar ISO 8601. |
| SpecialInstructions | `40` | Instruksi editorial lainnya terkait penggunaan data objek, seperti embargo dan peringatan. |
| ActionAdvised | `42` | Menunjukkan jenis tindakan yang diberikan objek ini ke objek sebelumnya. |
| ReferenceService | `45` | Mengidentifikasi Pengidentifikasi Layanan dari amplop sebelumnya yang dirujuk oleh objek saat ini. |
| ReferenceDate | `47` | Mengidentifikasi tanggal amplop sebelumnya yang merujuk objek saat ini. |
| ReferenceNumber | `50` | Mengidentifikasi Nomor Amplop dari amplop sebelumnya yang dirujuk objek saat ini. |
| DateCreated | `55` | Diwakili dalam bentuk CCYYMMDD untuk menunjukkan tanggal pembuatan konten intelektual dari data objek, bukan tanggal pembuatan representasi fisik. |
| TimeCreated | `60` | Diwakili dalam bentuk HHMMSS±HHMM untuk menunjukkan waktu konten intelektual dari objectdata materi sumber saat ini dibuat daripada pembuatan representasi fisik. |
| DigitalCreationDate | `62` | Diwakili dalam bentuk CCYYMMDD untuk menunjukkan tanggal pembuatan representasi digital dari data objek. |
| DigitalCreationTime | `63` | Diwakili dalam bentuk HHMMSS±HHMM untuk menunjukkan waktu pembuatan representasi digital dari data objek. |
| OriginatingProgram | `65` | Mengidentifikasi jenis program yang digunakan untuk membuat objectdata. |
| ProgramVersion | `70` | Digunakan untuk mengidentifikasi versi program yang disebutkan di 2:65. DataSet 2:70 tidak valid jika 2:65 tidak ada. |
| ObjectCycle | `75` | Terdiri dari karakter alfabet. Di mana: 'a' = pagi, 'p' = sore, 'b' = keduanya. |
| Byline | `80` | Berisi nama pembuat data objek, misal penulis, fotografer atau seniman grafis. |
| BylineTitle | `85` | Judul by-line adalah judul pencipta atau pembuat data objek. |
| City | `90` | Mengidentifikasi kota asal objek data sesuai pedoman yang ditetapkan oleh penyedia. |
| SubLocation | `92` | Mengidentifikasi lokasi di dalam kota asal data objek, menurut panduan yang ditetapkan oleh penyedia. |
| ProvinceState | `95` | Mengidentifikasi Provinsi/Negara asal sesuai pedoman yang ditetapkan oleh provider. |
| PrimaryLocationCode | `100` | Menunjukkan kode negara/lokasi utama tempat kekayaan intelektual data objek dibuat, misalnya foto diambil, peristiwa terjadi. |
| PrimaryLocationName | `101` | Memberikan nama negara/lokasi utama yang lengkap dan dapat dipublikasikan tempat kekayaan intelektual objekdata dibuat, sesuai dengan pedoman penyedia. |
| OriginalTransmissionReference | `103` | Kode yang mewakili lokasi transmisi asli menurut praktik penyedia. |
| Headline | `105` | Entri yang dapat diterbitkan yang memberikan sinopsis isi objectdata. |
| Credit | `110` | Mengidentifikasi penyedia objectdata, tidak harus pemilik/pencipta. |
| Source | `115` | Nama orang atau pihak yang berperan dalam rantai pasokan konten. Ini bisa berupa agensi, anggota agensi, individu, atau kombinasi. |
| CopyrightNotice | `116` | Berisi pemberitahuan hak cipta yang diperlukan. |
| Contact | `118` | Mengidentifikasi orang atau organisasi yang dapat memberikan informasi latar belakang lebih lanjut tentang data objek. |
| CaptionAbstract | `120` | Deskripsi tekstual dari objectdata, terutama digunakan jika objeknya bukan teks. |
| WriterEditor | `122` | Identifikasi nama orang yang terlibat dalam penulisan, penyuntingan atau koreksi data objek atau keterangan/abstrak. |
| RasterizedCaption | `125` | Lebar gambar 460 piksel dan tinggi gambar 128 piksel. Arah pemindaian dari bawah ke atas, kiri ke kanan. |
| ImageType | `130` | Karakter numerik 1 hingga 4 menunjukkan jumlah komponen dalam gambar, dalam satu atau beberapa amplop. |
| ImageOrientation | `131` | Menunjukkan tata letak area gambar. |
| LanguageIdentifier | `135` | Menjelaskan bahasa nasional utama objek, menurut kode 2 huruf ISO 639:1988. |
| AudioType | `150` | Jenis audio. |
| AudioSamplingRate | `151` | Karakter numerik laju pengambilan sampel, mewakili laju pengambilan sampel dalam hertz (Hz). |
| AudioSamplingResolution | `152` | Jumlah bit dalam setiap sampel audio. |
| AudioDuration | `153` | Duration Menunjuk dalam bentuk HHMMSS waktu berjalan dari data objek audio saat diputar ulang dengan kecepatan saat direkam. |
| AudioOutcue | `154` | Mengidentifikasi konten akhir dari data objek audio, sesuai pedoman yang ditetapkan oleh penyedia. |
| ObjDataPreviewFileFormat | `200` | Angka biner yang mewakili format file ObjectData Preview. |
| ObjDataPreviewFileFormatVer | `201` | Angka biner yang mewakili versi tertentu dari Format File Pratinjau ObjectData yang ditentukan dalam 2:200. |
| ObjDataPreviewData | `202` | Pratinjau data objek. |

### Lihat juga

* ruang nama [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
