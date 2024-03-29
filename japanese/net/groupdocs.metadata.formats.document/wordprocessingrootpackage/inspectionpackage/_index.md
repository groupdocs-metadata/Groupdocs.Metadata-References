---
title: InspectionPackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: ドキュメントの検査結果を含むメタデータ パッケージを取得します パッケージには場合によってはメタデータと見なすことができるドキュメント パーツに関する情報が含まれます
type: docs
weight: 40
url: /ja/net/groupdocs.metadata.formats.document/wordprocessingrootpackage/inspectionpackage/
---
## WordProcessingRootPackage.InspectionPackage property

ドキュメントの検査結果を含むメタデータ パッケージを取得します。 パッケージには、場合によってはメタデータと見なすことができるドキュメント パーツに関する情報が含まれます。

```csharp
public WordProcessingInspectionPackage InspectionPackage { get; }
```

### プロパティ値

ドキュメントの検査結果を含むメタデータ パッケージ.

### 備考

**もっと詳しく知る**

* [WordProcessing ドキュメントでのメタデータの操作](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### 例

このコード サンプルは、WordProcessing ドキュメントを検査する方法を示しています。

```csharp
using (Metadata metadata = new Metadata(Constants.InputDocx))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    if (root.InspectionPackage.Comments != null)
    {
        foreach (var comment in root.InspectionPackage.Comments)
        {
            Console.WriteLine(comment.Author);
            Console.WriteLine(comment.CreatedDate);
            Console.WriteLine(comment.Text);

            // ... 

        }
    }

    if (root.InspectionPackage.DigitalSignatures != null)
    {
        foreach (var signature in root.InspectionPackage.DigitalSignatures)
        {
            Console.WriteLine(signature.CertificateSubject);
            Console.WriteLine(signature.Comments);
            Console.WriteLine(signature.SignTime);

            // ...
        }
    }

    if (root.InspectionPackage.Fields != null)
    {
        foreach (var field in root.InspectionPackage.Fields)
        {
            Console.WriteLine(field.Code);
            Console.WriteLine(field.Result);
        }
    }

    if (root.InspectionPackage.HiddenText != null)
    {
        foreach (var textFragment in root.InspectionPackage.HiddenText)
        {
            Console.WriteLine(textFragment);
        }
    }

    if (root.InspectionPackage.Revisions != null)
    {
         foreach (var revision in root.InspectionPackage.Revisions)
         {
             Console.WriteLine(revision.Author);
             Console.WriteLine(revision.DateTime);
             Console.WriteLine(revision.RevisionType);
          }
     }
}
```

### 関連項目

* class [WordProcessingInspectionPackage](../../wordprocessinginspectionpackage)
* class [WordProcessingRootPackage](../../wordprocessingrootpackage)
* 名前空間 [GroupDocs.Metadata.Formats.Document](../../wordprocessingrootpackage)
* 組み立て [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
