---
title: UpdateDocumentStatistics
second_title: GroupDocs.Metadata لمرجع .NET API
description: إعادة حساب عدد الصفحات والفقرات والكلمات والأسطر والأحرف في المستند وتحديث حزم البيانات الوصفية المناسبة.
type: docs
weight: 50
url: /ar/net/groupdocs.metadata.formats.document/wordprocessingrootpackage/updatedocumentstatistics/
---
## WordProcessingRootPackage.UpdateDocumentStatistics method

إعادة حساب عدد الصفحات والفقرات والكلمات والأسطر والأحرف في المستند وتحديث حزم البيانات الوصفية المناسبة.

```csharp
public void UpdateDocumentStatistics()
```

### ملاحظات

**يتعلم أكثر**

* [التعامل مع البيانات الوصفية في مستندات WordProcessing](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### أمثلة

يوضح نموذج التعليمات البرمجية هذا كيفية تحديث إحصائيات المستند لمستند معالجة Word.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDoc))
{
   var root = metadata.GetRootPackage<WordProcessingRootPackage>();

   root.UpdateDocumentStatistics();

   metadata.Save(Constants.OutputDoc);
}
```

### أنظر أيضا

* class [WordProcessingRootPackage](../../wordprocessingrootpackage)
* مساحة الاسم [GroupDocs.Metadata.Formats.Document](../../wordprocessingrootpackage)
* المجسم [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
