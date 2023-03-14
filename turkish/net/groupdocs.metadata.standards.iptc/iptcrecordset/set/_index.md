---
title: Set
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Belirtilen dataSeti uygun kayda ekler veya günceller.
type: docs
weight: 80
url: /tr/net/groupdocs.metadata.standards.iptc/iptcrecordset/set/
---
## IptcRecordSet.Set method

Belirtilen dataSet'i uygun kayda ekler veya günceller.

```csharp
public void Set(IptcDataSet dataSet)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| dataSet | IptcDataSet | Eklenecek/güncellenecek IPTC veri seti. |

### Örnekler

Bu örnek, özel IPTC veri kümelerinin bir dosyaya nasıl ekleneceğini veya güncelleneceğini gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.PsdWithIptc))
{
    IIptc root = metadata.GetRootPackage() as IIptc;
    if (root != null)
    {
        // IPTC paketi yoksa ayarlayın
        if (root.IptcPackage == null)
        {
            root.IptcPackage = new IptcRecordSet();
        }

        // DataSet API'sini kullanarak bilinen bir özellik ekleyin
        root.IptcPackage.Set(new IptcDataSet((byte) IptcRecordType.ApplicationRecord, (byte) IptcApplicationRecordDataSet.BylineTitle, "test code sample"));

        // Özel bir IPTC Veri Kümesi ekleyin
        root.IptcPackage.Set(new IptcDataSet(255, 255, new byte[] { 1, 2, 3 }));

        metadata.Save(Constants.OutputPsd);
    }
}
```

### Ayrıca bakınız

* class [IptcDataSet](../../iptcdataset)
* class [IptcRecordSet](../../iptcrecordset)
* ad alanı [GroupDocs.Metadata.Standards.Iptc](../../iptcrecordset)
* toplantı [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->