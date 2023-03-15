---
title: GetRootPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mendapatkan paket root yang menyediakan akses ke semua properti metadata yang diekstraksi dari file.
type: docs
weight: 80
url: /id/net/groupdocs.metadata/metadata/getrootpackage/
---
## GetRootPackage() {#getrootpackage}

Mendapatkan paket root yang menyediakan akses ke semua properti metadata yang diekstraksi dari file.

```csharp
public RootMetadataPackage GetRootPackage()
```

### Nilai Pengembalian

Paket root menyediakan akses ke semua properti metadata yang diekstraksi dari file.

### Perkataan

**Belajarlah lagi**

* [Lintasi seluruh pohon metadata](https://docs.groupdocs.com/display/metadatanet/Traverse+a+whole+metadata+tree)

### Contoh

Contoh ini mendemonstrasikan cara menjelajahi seluruh pohon metadata untuk file tertentu apa pun formatnya.

```csharp
public static void Run()
{
    using (Metadata metadata = new Metadata(Constants.JpegWithXmp))
    {
        DisplayMetadataTree(metadata.GetRootPackage(), 0);
    }
}

private static void DisplayMetadataTree(MetadataPackage package, int indent)
{
    if (package != null)
    {
        var stringMetadataType = package.MetadataType.ToString();
        Console.WriteLine(stringMetadataType.PadLeft(stringMetadataType.Length + indent));
        foreach (MetadataProperty property in package)
        {
            string stringPropertyRepresentation = string.Format("Name: {0}, Value: {1}", property.Name, property.Value);
            Console.WriteLine(stringPropertyRepresentation.PadLeft(stringPropertyRepresentation.Length + indent + 1));
            if (property.Value != null)
            {
                switch (property.Value.Type)
                {
                    case MetadataPropertyType.Metadata:
                        DisplayMetadataTree(property.Value.ToClass<MetadataPackage>(), indent + 2);
                    break;
                    case MetadataPropertyType.MetadataArray:
                        DisplayMetadataTree(property.Value.ToArray<MetadataPackage>(), indent + 2);
                    break;
                }
            }
        }
    }
}

private static void DisplayMetadataTree(MetadataPackage[] packages, int indent)
{
    if (packages != null)
    {
        foreach (var package in packages)
        {
            DisplayMetadataTree(package, indent);
        }
    }
}
```

### Lihat juga

* class [RootMetadataPackage](../../../groupdocs.metadata.common/rootmetadatapackage)
* class [Metadata](../../metadata)
* ruang nama [GroupDocs.Metadata](../../metadata)
* perakitan [GroupDocs.Metadata](../../../)

---

## GetRootPackage&lt;TRoot&gt;() {#getrootpackage_1}

Mendapatkan paket root yang menyediakan akses ke semua properti metadata yang diekstraksi dari file.

```csharp
public TRoot GetRootPackage<TRoot>()
    where TRoot : RootMetadataPackage
```

| Parameter | Keterangan |
| --- | --- |
| TRoot | Jenis yang tepat dari paket root. |

### Nilai Pengembalian

Paket root menyediakan akses ke semua properti metadata yang diekstraksi dari file.

### Perkataan

**Belajarlah lagi**

* [Lintasi seluruh pohon metadata](https://docs.groupdocs.com/display/metadatanet/Traverse+a+whole+metadata+tree)

### Lihat juga

* class [RootMetadataPackage](../../../groupdocs.metadata.common/rootmetadatapackage)
* class [Metadata](../../metadata)
* ruang nama [GroupDocs.Metadata](../../metadata)
* perakitan [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->