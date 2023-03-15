---
title: WavPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan paket metadata asli dalam file audio WAV.
type: docs
weight: 590
url: /id/net/groupdocs.metadata.formats.audio/wavpackage/
---
## WavPackage class

Merupakan paket metadata asli dalam file audio WAV.

```csharp
public sealed class WavPackage : CustomPackage
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [WavPackage](wavpackage)() | Menginisialisasi instance baru dari[`WavPackage`](../wavpackage) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AudioFormat](../../groupdocs.metadata.formats.audio/wavpackage/audioformat) { get; } | Mendapatkan format audio. PCM = 1 (yaitu kuantisasi Linear). Nilai selain 1 menunjukkan beberapa bentuk kompresi. |
| [BitsPerSample](../../groupdocs.metadata.formats.audio/wavpackage/bitspersample) { get; } | Mendapat bit per nilai sampel. |
| [BlockAlign](../../groupdocs.metadata.formats.audio/wavpackage/blockalign) { get; } | Mendapatkan penyelarasan blok. |
| [ByteRate](../../groupdocs.metadata.formats.audio/wavpackage/byterate) { get; } | Mendapatkan kecepatan byte. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [NumberOfChannels](../../groupdocs.metadata.formats.audio/wavpackage/numberofchannels) { get; } | Mendapat jumlah saluran. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [SampleRate](../../groupdocs.metadata.formats.audio/wavpackage/samplerate) { get; } | Mendapat laju sampel. |

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

### Perkataan

**Belajarlah lagi**

* [Menangani metadata dalam file WAV](https://docs.groupdocs.com/display/metadatanet/Handling+metadata+in+WAV+files)

### Contoh

Contoh kode ini menunjukkan cara mengekstrak informasi audio teknis dari file WAV.

```csharp
using (Metadata metadata = new Metadata(Constants.InputWav))
{
    var root = metadata.GetRootPackage<WavRootPackage>();
    if (root.WavPackage != null)
    {
        Console.WriteLine(root.WavPackage.AudioFormat);
        Console.WriteLine(root.WavPackage.BitsPerSample);
        Console.WriteLine(root.WavPackage.BlockAlign);
        Console.WriteLine(root.WavPackage.ByteRate);
        Console.WriteLine(root.WavPackage.NumberOfChannels);
        Console.WriteLine(root.WavPackage.SampleRate);
    }
}
```

### Lihat juga

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ruang nama [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
