---
title: TiffTagID
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mendefinisikan id dari tag TIFF.
type: docs
weight: 2100
url: /id/net/groupdocs.metadata.formats.image/tifftagid/
---
## TiffTagID enumeration

Mendefinisikan id dari tag TIFF.

```csharp
public enum TiffTagID : ushort
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| GpsVersionID | `0` | Menunjukkan versi GPSInfoIFD. |
| GpsLatitudeRef | `1` | Menunjukkan apakah lintang utara atau lintang selatan. |
| GpsLatitude | `2` | Menunjukkan garis lintang. |
| GpsLongitudeRef | `3` | Menunjukkan apakah bujur timur atau bujur barat. |
| GpsLongitude | `4` | Menunjukkan garis bujur. |
| GpsAltitudeRef | `5` | Menunjukkan ketinggian yang digunakan sebagai ketinggian referensi. |
| GpsAltitude | `6` | Menunjukkan ketinggian berdasarkan referensi di GPSAltitudeRef. |
| GpsTimeStamp | `7` | Menunjukkan waktu sebagai UTC (Waktu Universal Terkoordinasi). |
| GpsSatellites | `8` | menunjukkan satelit GPS yang digunakan untuk pengukuran. |
| GpsStatus | `9` | Menunjukkan status penerima GPS saat gambar direkam. |
| GpsMeasureMode | `10` | Menunjukkan mode pengukuran GPS. |
| GpsDop | `11` | Menunjukkan GPS DOP (tingkat presisi data). |
| GpsSpeedRef | `12` | Menunjukkan unit yang digunakan untuk menyatakan kecepatan gerakan penerima GPS |
| GpsSpeed | `13` | Menunjukkan kecepatan pergerakan penerima GPS. |
| GpsTrackRef | `14` | Menunjukkan acuan untuk memberikan arah pergerakan penerima GPS. |
| GpsTrack | `15` | Menunjukkan arah pergerakan penerima GPS. |
| GpsImgDirectionRef | `16` | Menandakan referensi untuk memberikan arah gambar saat diambil. |
| GpsImgDirection | `17` | Menunjukkan arah gambar saat diambil. |
| GpsMapDatum | `18` | Menunjukkan data survei geodetik yang digunakan oleh penerima GPS. |
| GpsDestLatitudeRef | `19` | Menunjukkan apakah garis lintang titik tujuan adalah garis lintang utara atau selatan. |
| GpsDestLatitude | `20` | Menunjukkan lintang titik tujuan. |
| GpsDestLongitudeRef | `21` | Menunjukkan apakah bujur titik tujuan adalah bujur timur atau bujur barat. |
| GpsDestLongitude | `22` | Menunjukkan garis bujur titik tujuan. |
| GpsDestBearingRef | `23` | Menunjukkan referensi yang digunakan untuk memberikan bantalan ke titik tujuan. |
| GpsDestBearing | `24` | Menunjukkan bantalan ke titik tujuan. |
| GpsDestDistanceRef | `25` | Menunjukkan satuan yang digunakan untuk menyatakan jarak ke titik tujuan. |
| GpsDestDistance | `26` | Menunjukkan jarak ke titik tujuan. |
| GpsProcessingMethod | `27` | String karakter yang merekam nama metode yang digunakan untuk pencarian lokasi. |
| GpsAreaInformation | `28` | String karakter yang merekam nama area GPS. |
| GpsDateStamp | `29` | Informasi tanggal dan waktu perekaman string karakter relatif terhadap UTC (Coordinated Universal Time). |
| GpsDifferential | `30` | Menunjukkan apakah koreksi diferensial diterapkan ke penerima GPS. |
| GpsHPositioningError | `31` | Tag ini menunjukkan kesalahan pemosisian horizontal dalam meter. |
| NewSubfileType | `254` | Indikasi umum tentang jenis data yang terdapat dalam subfile ini. |
| SubfileType | `255` | Indikasi umum tentang jenis data yang terkandung dalam subfile ini. Kolom ini tidak digunakan lagi. Bidang NewSubfileType harus digunakan sebagai gantinya |
| ImageWidth | `256` | Jumlah kolom pada gambar, yaitu jumlah piksel per baris pemindaian. |
| ImageLength | `257` | Jumlah baris (terkadang digambarkan sebagai garis pindaian) pada gambar. |
| BitsPerSample | `258` | Jumlah bit per komponen. |
| Compression | `259` | Skema kompresi yang digunakan pada data gambar. |
| PhotometricInterpretation | `262` | Ruang warna data gambar. |
| Threshholding | `263` | Untuk file TIFF hitam putih yang merepresentasikan nuansa abu-abu, teknik yang digunakan untuk mengonversi dari piksel abu-abu menjadi piksel hitam putih. |
| CellWidth | `264` | Lebar matriks dithering atau halftoning yang digunakan untuk membuat file dwi-level dithered atau halfton. |
| CellLength | `265` | Panjang matriks dithering atau halftoning yang digunakan untuk membuat file bi-level dithered atau halfton. |
| FillOrder | `266` | Urutan logis bit dalam satu byte. |
| DocumentName | `269` | Nama dokumen tempat gambar ini dipindai. |
| ImageDescription | `270` | String yang mendeskripsikan subjek gambar. |
| Make | `271` | Produsen pemindai. |
| Model | `272` | Nama atau nomor model pemindai. |
| StripOffsets | `273` | Untuk setiap strip, offset byte dari strip tersebut. |
| Orientation | `274` | Orientasi gambar terhadap baris dan kolom. |
| SamplesPerPixel | `277` | Jumlah komponen per piksel. |
| RowsPerStrip | `278` | Jumlah baris per strip. |
| StripByteCounts | `279` | Untuk setiap lajur, jumlah byte dalam lajur setelah kompresi. |
| MinSampleValue | `280` | Nilai minimum komponen yang digunakan. |
| MaxSampleValue | `281` | Nilai maksimum komponen yang digunakan. |
| XResolution | `282` | Jumlah piksel per Unit Resolusi pada arah ImageWidth. |
| YResolution | `283` | Jumlah piksel per Unit Resolusi dalam arah ImageLength. |
| PlanarConfiguration | `284` | Bagaimana komponen setiap piksel disimpan. |
| PageName | `285` | Nama halaman tempat gambar ini dipindai. |
| XPosition | `286` | X posisi gambar. |
| YPosition | `287` | posisi Y gambar. |
| FreeOffsets | `288` | Untuk setiap string byte yang tidak terpakai yang bersebelahan dalam file TIFF, offset byte dari string. |
| FreeByteCounts | `289` | Untuk setiap string byte yang tidak terpakai yang berdekatan dalam file TIFF, jumlah byte dalam string. |
| GrayResponseUnit | `290` | Ketepatan informasi yang terkandung dalam GrayResponseCurve. |
| GrayResponseCurve | `291` | Untuk data skala abu-abu, kerapatan optik dari setiap kemungkinan nilai piksel. |
| T4Options | `292` | Opsi pengkodean T4. |
| T6Options | `293` | Opsi pengkodean T6. |
| ResolutionUnit | `296` | Satuan pengukuran untuk XResolution dan YResolution. |
| PageNumber | `297` | Nomor halaman dari halaman tempat gambar ini dipindai. |
| TransferFunction | `301` | Menjelaskan fungsi transfer untuk gambar dalam gaya tabel. Komponen piksel dapat dikompensasi gamma, dikompensasi, dikuantisasi secara tidak seragam, atau dikodekan dengan cara lain. TransferFunction memetakan komponen piksel dari bentuk non-linear BitsPerSample (mis. 8-bit) menjadi bentuk linier 16-bit tanpa kehilangan akurasi yang terlihat. |
| Software | `305` | Nama dan nomor versi paket perangkat lunak yang digunakan untuk membuat gambar. |
| DateTime | `306` | Tanggal dan waktu pembuatan gambar. |
| Artist | `315` | Orang yang membuat gambar. |
| HostComputer | `316` | Komputer dan/atau sistem operasi yang digunakan pada saat pembuatan gambar. |
| Predictor | `317` | Bagian ini mendefinisikan Predictor yang sangat meningkatkan rasio kompresi untuk beberapa gambar. |
| WhitePoint | `318` | Kromatisitas titik putih gambar. |
| PrimaryChromaticities | `319` | Kromatisitas pendahuluan gambar. |
| ColorMap | `320` | Peta warna untuk gambar warna palet. |
| HalftoneHints | `321` | Tujuan bidang HalftoneHints adalah untuk menyampaikan ke fungsi halftone rentang tingkat abu-abu dalam gambar yang ditentukan secara kolorimetri yang harus mempertahankan detail tonal. |
| TileWidth | `322` | Lebar petak dalam piksel. Ini adalah jumlah kolom di setiap petak. |
| TileLength | `323` | Panjang petak (tinggi) dalam piksel. Ini adalah jumlah baris di setiap petak. |
| TileOffsets | `324` | Untuk setiap ubin, offset byte dari ubin tersebut, seperti yang dikompresi dan disimpan di disk. Offset ditentukan sehubungan dengan awal file TIFF. Perhatikan bahwa ini menyiratkan bahwa setiap petak memiliki lokasi yang terpisah dari lokasi petak lainnya. |
| TileByteCounts | `325` | Untuk setiap petak, jumlah byte (terkompresi) di petak tersebut. |
| InkSet | `332` | Kumpulan tinta yang digunakan dalam gambar terpisah (PhotometricInterpretation=5). |
| InkNames | `333` | Nama setiap tinta yang digunakan dalam gambar terpisah (PhotometricInterpretation=5), ditulis sebagai daftar string ASCII yang diakhiri dengan NUL. |
| NumberOfInks | `334` | Jumlah tinta. Biasanya sama dengan SamplesPerPixel, kecuali ada sampel tambahan. |
| DotRange | `336` | Nilai komponen yang sesuai dengan titik 0% dan titik 100%. DotRange[0] sesuai dengan 0% titik, dan DotRange[1] sesuai dengan 100% titik. |
| ExtraSamples | `338` | Deskripsi komponen tambahan. |
| SampleFormat | `339` | Kolom ini menentukan cara menginterpretasikan setiap sampel data dalam piksel. |
| SMinSampleValue | `340` | Kolom ini menentukan nilai sampel minimum. |
| SMaxSampleValue | `341` | Kolom baru ini menentukan nilai sampel maksimum. |
| TransferRange | `342` | Memperluas jangkauan TransferFunction. |
| JpegProc | `512` | Bidang ini menunjukkan proses JPEG yang digunakan untuk menghasilkan data terkompresi. |
| JpegInterchangeFormat | `513` | Bidang ini menunjukkan apakah bitstream format interchange JPEG ada dalam file TIFF. |
| JpegInterchangeFormatLength | `514` | Bidang ini menunjukkan panjang dalam byte format interchange JPEG bitstream |
| JpegRestartInterval | `515` | Kolom ini menunjukkan panjang interval mulai ulang yang digunakan dalam data gambar terkompresi. |
| JpegLosslessPredictors | `517` | Bidang ini menunjuk ke daftar nilai pilihan prediktor lossless, satu per komponen. |
| JpegPointTransforms | `518` | Bidang ini menunjuk ke daftar nilai transformasi titik, satu per komponen. |
| JpegQTables | `519` | Bidang ini menunjuk ke daftar offset ke tabel kuantisasi, satu per komponen. |
| JpegDCTables | `520` | Bidang ini menunjuk ke daftar offset ke tabel DC Huffman atau tabel Huffman lossless , satu per komponen. |
| JpegACTables | `521` | Bidang ini menunjuk ke daftar offset ke tabel Huffman AC, satu per komponen. |
| YCbCrCoefficients | `529` | Koefisien matriks untuk transformasi dari data gambar RGB ke YCbCr. |
| YCbCrSubSampling | `530` | Rasio sampling komponen chrominance terkait dengan komponen luminance. |
| YCbCrPositioning | `531` | Menentukan posisi komponen chrominance subsampel relatif terhadap sampel luminance. |
| ReferenceBlackWhite | `532` | Menentukan sepasang nilai data gambar headroom dan footroom (kode) untuk setiap komponen piksel. |
| Copyright | `33432` | Pemberitahuan hak cipta. |
| UserComment | `37510` | Kata kunci atau komentar pada gambar; melengkapi ImageDescription. |
| Xmp | `700` | Penunjuk ke metadata XMP. |
| ImageID | `32781` | Terkait OPI. |
| Iptc | `33723` | Metadata IPTC (Dewan Telekomunikasi Pers Internasional). Sering kali, tipe data salah ditentukan sebagai LONG. |
| Photoshop | `34377` | Kumpulan 'Blok Sumber Daya Gambar' Photoshop. |
| ImageLayer | `34732` | Lapisan gambar. |
| IccProfile | `34675` | Data profil warna. |
| ExifIfd | `34665` | Pointer ke koleksi semua Metadata EXIF. EXIF menggunakan nama bidang, bukan tag untuk menunjukkan konten bidang. |
| GpsIfd | `34853` | Penunjuk ke data GPS. |
| Makernotes | `37500` | Penunjuk ke data pembuat catatan. |
| InteroperabilityIfd | `40965` | IFD Interoperabilitas terkait Exif. |
| CameraOwnerName | `42032` | Nama pemilik kamera sebagai string ASCII. |
| BodySerialNumber | `42033` | Nomor seri badan kamera sebagai string ASCII. |
| CfaPattern | `41730` | menunjukkan pola geometris susunan filter warna (CFA) dari sensor gambar saat sensor area warna satu chip digunakan. Itu tidak berlaku untuk semua metode penginderaan. |
| ExifVersion | `36864` | Versi standar EXIF didukung. |
| ComponentsConfiguration | `37121` | Informasi khusus untuk data terkompresi. Saluran dari setiap komponen disusun secara berurutan dari komponen ke-1 hingga ke-4. |
| FlashpixVersion | `40960` | Versi format Flashpix didukung oleh file FPXR. Jika fungsi FPXR mendukung format Flashpix Ver. 1.0, ini ditunjukkan serupa dengan ExifVersion dengan merekam "0100" sebagai ASCII 4-byte. |
| ColorSpace | `40961` | Tag informasi ruang warna (ColorSpace) selalu direkam sebagai penentu ruang warna. Biasanya sRGB (=1) digunakan untuk menentukan ruang warna berdasarkan kondisi dan lingkungan monitor PC. Jika ruang warna selain sRGB digunakan, Tidak dikalibrasi (=FFFF.H) diatur. |
| PixelXDimension | `40962` | Informasi khusus untuk data terkompresi. Saat file terkompresi direkam, lebar valid dari gambar bermakna harus direkam dalam tag ini, terlepas dari apakah ada data padding atau penanda mulai ulang. |
| PixelYDimension | `40963` | Informasi khusus untuk data terkompresi. Saat file terkompresi direkam, ketinggian yang valid dari gambar bermakna harus direkam dalam tag ini, terlepas dari apakah ada data padding atau penanda mulai ulang. |
| SceneCaptureType | `41990` | Tag ini menunjukkan jenis adegan yang diambil. Ini juga dapat digunakan untuk merekam mode pengambilan gambar. |
| Gamma | `42240` | Menunjukkan nilai koefisien gamma. |
| CompressedBitsPerPixel | `37122` | Informasi khusus untuk data terkompresi. Mode kompresi yang digunakan untuk gambar terkompresi ditunjukkan dalam satuan bit per piksel. |
| RelatedSoundFile | `40964` | Tag ini digunakan untuk mencatat nama file audio yang berhubungan dengan data gambar. Satu-satunya informasi relasional yang direkam di sini adalah nama dan ekstensi file audio Exif (string ASCII yang terdiri dari 8 karakter + '.' + 3 karakter). |
| DateTimeOriginal | `36867` | Tanggal dan waktu pembuatan data gambar asli. Untuk DSC, tanggal dan waktu pengambilan gambar direkam. Formatnya adalah "YYYY:MM:DD HH:MM:SS" dengan waktu ditampilkan dalam format 24 jam, dan tanggal serta waktu dipisahkan oleh satu karakter kosong. |
| DateTimeDigitized | `36868` | Tanggal dan waktu saat gambar disimpan sebagai data digital. Jika, misalnya, sebuah gambar diambil oleh DSC dan pada saat yang sama file direkam, maka DateTimeOriginal dan DateTimeDigitized akan memiliki konten yang sama. Formatnya adalah "YYYY:MM:DD HH:MM:SS" dengan waktu ditampilkan dalam format 24 jam, dan tanggal serta waktu dipisahkan oleh satu karakter kosong. |
| OffsetTime | `36880` | Tag yang digunakan untuk merekam offset dari UTC (perbedaan waktu dari Universal Time Coordinated termasuk waktu musim panas) dari waktu tag DateTime. Format saat merekam offset adalah "±HH:MM". Bagian dari "±" harus direkam sebagai "+" atau "-". |
| OffsetTimeOriginal | `36881` | Tag yang digunakan untuk merekam selisih waktu dari UTC (perbedaan waktu dari Koordinasi Waktu Universal termasuk waktu musim panas) dari waktu tag DateTimeOriginal. Format saat merekam selisih adalah "±HH:MM". Bagian dari "±" harus direkam sebagai "+" atau "-". |
| OffsetTimeDigitized | `36882` | Tag yang digunakan untuk merekam offset dari UTC (perbedaan waktu dari Universal Time Coordinated termasuk waktu musim panas) dari waktu tag DateTimeDigitized. Format saat merekam offset adalah "±HH:MM". Bagian dari "±" harus direkam sebagai "+" atau "-". |
| SubsecTime | `37520` | Tag yang digunakan untuk merekam sepersekian detik untuk tag DateTime. |
| SubsecTimeOriginal | `37521` | Tag yang digunakan untuk merekam sepersekian detik untuk tag DateTimeOriginal. |
| SubsecTimeDigitized | `37522` | Tag yang digunakan untuk merekam sepersekian detik untuk tag DateTimeDigitized. |
| ExposureTime | `33434` | Waktu pemaparan, diberikan dalam detik (detik). |
| FNumber | `33437` | Angka F. |
| ExposureProgram | `34850` | Kelas program yang digunakan kamera untuk menyetel eksposur saat gambar diambil. |
| SpectralSensitivity | `34852` | Menunjukkan sensitivitas spektral dari setiap saluran kamera yang digunakan. Nilai tag adalah string ASCII yang kompatibel dengan standar yang dikembangkan oleh komite Teknis ASTM. |
| PhotographicSensitivity | `34855` | Tag ini menunjukkan sensitivitas kamera atau perangkat masukan saat pengambilan gambar. |
| Oecf | `34856` | Menunjukkan Fungsi Konversi Opto-Listrik (OECF) yang ditentukan dalam ISO 14524. OECF adalah hubungan antara input optik kamera dan nilai gambar. |
| SensitivityType | `34864` | Tag SensitivityType menunjukkan salah satu parameter ISO12232 mana yang merupakan tag PhotographicSensitivity. Meskipun merupakan tag opsional, ini harus direkam saat tag Sensitivitas Fotografi direkam. |
| StandardOutputSensitivity | `34865` | Tag ini menunjukkan nilai sensitivitas keluaran standar kamera atau perangkat input yang ditentukan dalam ISO 12232. Saat merekam tag ini, tag PhotographicSensitivity dan SensitivityType juga harus direkam. |
| RecommendedExposureIndex | `34866` | Tag ini menunjukkan nilai indeks eksposur yang direkomendasikan dari kamera atau perangkat input yang ditentukan dalam ISO 12232. Saat merekam tag ini, tag PhotographicSensitivity dan SensitivityType juga harus direkam. |
| IsoSpeed | `34867` | Tag ini menunjukkan nilai kecepatan ISO kamera atau perangkat input yang ditentukan dalam ISO 12232. Saat merekam tag ini, tag PhotographicSensitivity dan SensitivityType juga harus direkam. |
| ISOSpeedLatitudeYyy | `34868` | Tag ini menunjukkan nilai ISO speed latitude yyy dari kamera atau perangkat input yang ditentukan dalam ISO 12232. |
| ISOSpeedLatitudeZzz | `34869` | Tag ini menunjukkan nilai zzz garis lintang kecepatan ISO dari kamera atau perangkat input yang ditentukan dalam ISO 12232. |
| ShutterSpeedValue | `37377` | Kecepatan rana. Satuannya adalah pengaturan APEX (Sistem Aditif Eksposur Fotografi). |
| ApertureValue | `37378` | Bukaan lensa. Satuannya adalah nilai APEX. |
| BrightnessValue | `37379` | Nilai kecerahan. Satuannya adalah nilai APEX. |
| ExposureBiasValue | `37380` | Bias eksposur. Satuannya adalah nilai APEX. |
| MaxApertureValue | `37381` | Angka F terkecil dari lensa. Satuannya adalah nilai APEX. |
| SubjectDistance | `37382` | Jarak ke subjek, diberikan dalam meter. |
| MeteringMode | `37383` | Mode pengukuran. |
| LightSource | `37384` | Jenis sumber cahaya. |
| Flash | `37385` | Tag ini menunjukkan status flash saat gambar diambil. Bit 0 menunjukkan status penyalaan lampu kilat, bit 1 dan 2 menunjukkan status pengembalian lampu kilat, bit 3 dan 4 menunjukkan mode lampu kilat, bit 5 menunjukkan apakah fungsi lampu kilat ada, dan bit 6 menunjukkan mode "mata merah". |
| SubjectArea | `37396` | Tag ini menunjukkan lokasi dan area subjek utama dalam pemandangan keseluruhan. |
| FocalLength | `37386` | Panjang fokus sebenarnya dari lensa, dalam mm. Konversi tidak dilakukan ke panjang fokus kamera film 35 mm. |
| FlashEnergy | `41483` | Menunjukkan energi strobo pada saat gambar diambil, yang diukur dalam Beam Candle Power Seconds (BCPS). |
| SpatialFrequencyResponse | `41484` | Tag ini merekam tabel frekuensi spasial kamera atau perangkat input dan nilai SFR dalam arah lebar gambar, tinggi gambar, dan arah diagonal, sebagaimana ditentukan dalam ISO 12233. |
| FocalPlaneXResolution | `41486` | Menunjukkan jumlah piksel dalam arah lebar gambar (X) per FocalPlaneResolutionUnit pada bidang fokus kamera. |
| FocalPlaneYResolution | `41487` | Menunjukkan jumlah piksel dalam arah tinggi gambar (Y) per FocalPlaneResolutionUnit pada bidang fokus kamera. |
| FocalPlaneResolutionUnit | `41488` | Menunjukkan unit untuk mengukur FocalPlaneXResolution dan FocalPlaneYResolution. Nilai ini sama dengan ResolutionUnit. |
| SubjectLocation | `41492` | Menunjukkan lokasi subjek utama dalam pemandangan. Nilai tag ini mewakili piksel di tengah subjek utama relatif terhadap tepi kiri, sebelum pemrosesan rotasi sesuai tag Rotasi. Nilai pertama menunjukkan nomor kolom X dan kedua menunjukkan nomor baris Y. |
| ExposureIndex | `41493` | Menunjukkan indeks eksposur yang dipilih pada kamera atau perangkat input pada saat pengambilan gambar. |
| SensingMethod | `41495` | Menunjukkan jenis sensor gambar pada kamera atau perangkat masukan. |
| FileSource | `41728` | Menunjukkan sumber gambar. Jika DSC merekam gambar, nilai tag ini harus selalu disetel ke 3. |
| SceneType | `41729` | Menunjukkan jenis adegan. Jika DSC merekam gambar tersebut, nilai tag ini harus selalu disetel ke 1, yang menunjukkan bahwa gambar tersebut langsung difoto. |
| CustomRendered | `41985` | Tag ini menunjukkan penggunaan pemrosesan khusus pada data gambar, seperti rendering yang disesuaikan dengan keluaran. |
| ExposureMode | `41986` | Tag ini menunjukkan mode eksposur yang diatur saat gambar diambil. Dalam mode auto-bracketing, kamera memotret serangkaian frame dari pemandangan yang sama pada pengaturan eksposur yang berbeda. |
| WhiteBalance | `41987` | Tag ini menunjukkan mode keseimbangan putih yang disetel saat gambar diambil. |
| DigitalZoomRatio | `41988` | Tag ini menunjukkan rasio pembesaran digital saat gambar diambil. Jika pembilang dari nilai yang direkam adalah 0, ini menunjukkan bahwa zoom digital tidak digunakan. |
| FocalLengthIn35mmFilm | `41989` | Tag ini menunjukkan panjang fokus setara dengan asumsi kamera film 35mm, dalam mm. Nilai 0 berarti panjang fokus tidak diketahui. Perhatikan bahwa tag ini berbeda dengan tag FocalLength. |
| GainControl | `41991` | Tag ini menunjukkan tingkat penyesuaian perolehan gambar secara keseluruhan. |
| Contrast | `41992` | Tag ini menunjukkan arah pemrosesan kontras yang diterapkan oleh kamera saat gambar diambil. |
| Saturation | `41993` | Tag ini menunjukkan arah pemrosesan saturasi yang diterapkan oleh kamera saat gambar diambil. |
| Sharpness | `41994` | Tag ini menunjukkan arah pemrosesan ketajaman yang diterapkan oleh kamera saat gambar diambil. |
| DeviceSettingDescription | `41995` | Tag ini menunjukkan informasi tentang kondisi pengambilan gambar model kamera tertentu. |
| SubjectDistanceRange | `41996` | Tag ini menunjukkan jarak ke subjek. |
| CompositeImage | `42080` | Tag ini menunjukkan apakah gambar yang direkam merupakan gambar gabungan* atau bukan. |
| SourceImageNumberOfCompositeImage | `42081` | Tag ini menunjukkan jumlah gambar sumber (gambar yang direkam sementara) yang diambil untuk Gambar komposit. |
| SourceExposureTimesOfCompositeImage | `42082` | Untuk gambar gabungan, tag ini mencatat parameter yang berkaitan dengan waktu pemaparan dari pemaparan untuk menghasilkan gambar komposit tersebut, seperti waktu pemaparan masing-masing dari gambar sumber yang diambil (gambar yang direkam sementara). |
| Temperature | `37888` | Temperatur sebagai keadaan sekitar saat pengambilan gambar, misalnya temperatur ruangan tempat fotografer memegang kamera. Satuannya adalah °C. |
| Humidity | `37889` | Kelembapan sebagai keadaan sekitar pada saat pengambilan gambar, misalnya kelembapan ruangan tempat fotografer memegang kamera. Satuannya adalah %. |
| Pressure | `37890` | Tekanan sebagai situasi ambien saat pengambilan gambar, misalnya suasana ruangan tempat fotografer memegang kamera atau tekanan air di bawah laut. Satuannya adalah hPa. |
| WaterDepth | `37891` | Kedalaman air sebagai situasi ambien saat pengambilan gambar, misalnya kedalaman air kamera pada fotografi bawah air. Satuannya adalah m. |
| Acceleration | `37892` | Akselerasi (skalar terlepas dari arah) sebagai situasi ambien pada bidikan, misalnya percepatan mengemudi kendaraan yang ditunggangi fotografer pada bidikan. Satuannya adalah mGal (10-5 m/s2). |
| CameraElevationAngle | `37893` | Ketinggian/depresi. sudut orientasi kamera (pencitraan sumbu optik) sebagai situasi sekitar saat pengambilan gambar. Satuannya adalah derajat(°). |
| ImageUniqueID | `42016` | Tag ini menunjukkan pengidentifikasi yang ditetapkan secara unik untuk setiap gambar. |
| LensSpecification | `42034` | Tag ini mencantumkan panjang fokus minimum, panjang fokus maksimum, angka F minimum pada panjang fokus minimum, dan angka F minimum pada panjang fokus maksimum, yang merupakan informasi spesifikasi lensa yang digunakan dalam fotografi. |
| LensMake | `42035` | Tag ini merekam produsen lensa sebagai string ASCII. |
| LensModel | `42036` | Tag ini merekam nama model dan nomor model lensa sebagai string ASCII. |
| LensSerialNumber | `42037` | Tag ini merekam nomor seri lensa yang dapat dipertukarkan yang digunakan dalam fotografi sebagai string ASCII. |

### Lihat juga

* ruang nama [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
