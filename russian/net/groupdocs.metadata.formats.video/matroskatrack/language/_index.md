---
title: Language
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Получает язык дорожки в форме языков Matroska. Этот элемент ДОЛЖЕН игнорироваться еслиLanguageIetfgroupdocs.metadata.formats.video/matroskatrack/languageietf Элемент используется в том же TrackEntry.
type: docs
weight: 50
url: /ru/net/groupdocs.metadata.formats.video/matroskatrack/language/
---
## MatroskaTrack.Language property

Получает язык дорожки в форме языков Matroska. Этот элемент ДОЛЖЕН игнорироваться, если[`LanguageIetf`](../languageietf) Элемент используется в том же TrackEntry.

```csharp
public string Language { get; }
```

### Стоимость имущества

Язык дорожки в форме языков Матроски.

### Примечания

Коды языков могут представлять собой трехбуквенную библиографическую форму ISO-639-2 (например, «fre» для французского), или такой код языка, за которым следует тире и код страны для языковых специальностей (например, «fre-ca» для канадского французского). Коды стран такие же, как и для интернет-доменов.

### Смотрите также

* class [MatroskaTrack](../../matroskatrack)
* пространство имен [GroupDocs.Metadata.Formats.Video](../../matroskatrack)
* сборка [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->