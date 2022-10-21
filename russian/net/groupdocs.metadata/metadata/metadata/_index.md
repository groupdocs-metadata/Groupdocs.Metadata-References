---
title: Metadata
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Инициализирует новый экземплярMetadatagroupdocs.metadata/metadata класс.
type: docs
weight: 10
url: /ru/net/groupdocs.metadata/metadata/metadata/
---
## Metadata(string) {#constructor_2}

Инициализирует новый экземпляр[`Metadata`](../../metadata) класс.

```csharp
public Metadata(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Строка, содержащая полное имя файла, из которого создается[`Metadata`](../../metadata) пример. |

### Примечания

**Учить больше**

* [Загрузить с локального диска](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Загрузка из потока](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Загрузить файл определенного формата](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Загрузите защищенный паролем документ](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Примеры

В этом примере показано, как загрузить файл с локального диска.

```csharp
using (Metadata metadata = new Metadata(Constants.InputOne))
{
    // Извлечение, редактирование или удаление метаданных здесь
}
```

### Смотрите также

* class [Metadata](../../metadata)
* пространство имен [GroupDocs.Metadata](../../metadata)
* сборка [GroupDocs.Metadata](../../../)

---

## Metadata(Stream) {#constructor}

Инициализирует новый экземпляр[`Metadata`](../../metadata) класс.

```csharp
public Metadata(Stream document)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Поток, содержащий загружаемый документ. |

### Примечания

**Учить больше**

* [Загрузить с локального диска](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Загрузка из потока](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Загрузить файл определенного формата](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Загрузите защищенный паролем документ](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Примеры

В этом примере показано, как загрузить файл из потока.

```csharp
using (Stream stream = File.Open(Constants.InputDoc, FileMode.Open, FileAccess.ReadWrite))
using (Metadata metadata = new Metadata(stream))
{
   // Извлечение, редактирование или удаление метаданных здесь
}
```

### Смотрите также

* class [Metadata](../../metadata)
* пространство имен [GroupDocs.Metadata](../../metadata)
* сборка [GroupDocs.Metadata](../../../)

---

## Metadata(string, LoadOptions) {#constructor_3}

Инициализирует новый экземпляр[`Metadata`](../../metadata) класс.

```csharp
public Metadata(string filePath, LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Строка, содержащая полное имя файла, из которого создается[`Metadata`](../../metadata) пример. |
| loadOptions | LoadOptions | Дополнительные параметры для использования при загрузке документа. |

### Примечания

**Учить больше**

* [Загрузить с локального диска](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Загрузка из потока](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Загрузить файл определенного формата](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Загрузите защищенный паролем документ](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Примеры

В этом примере показано, как загрузить защищенный паролем документ.

```csharp
// Указываем пароль
var loadOptions = new LoadOptions
{
    Password = "123"
};

using (var metadata = new Metadata(Constants.ProtectedDocx, loadOptions))
{
    // Извлечение, редактирование или удаление метаданных здесь
}
```

### Смотрите также

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* пространство имен [GroupDocs.Metadata](../../metadata)
* сборка [GroupDocs.Metadata](../../../)

---

## Metadata(Stream, LoadOptions) {#constructor_1}

Инициализирует новый экземпляр[`Metadata`](../../metadata) класс.

```csharp
public Metadata(Stream document, LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Поток, содержащий загружаемый документ. |
| loadOptions | LoadOptions | Дополнительные параметры для использования при загрузке документа. |

### Примечания

**Учить больше**

* [Загрузить с локального диска](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Загрузка из потока](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Загрузить файл определенного формата](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Загрузите защищенный паролем документ](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Смотрите также

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* пространство имен [GroupDocs.Metadata](../../metadata)
* сборка [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
