---
title: ExportManager
second_title: GroupDocs.Metadata for Java API Reference
description: Provides a row of methods allowing the user to export metadata properties to various formats.
type: docs
weight: 11
url: /java/com.groupdocs.metadata.export/exportmanager/
---
**Inheritance:**
java.lang.Object
```
public class ExportManager
```

Provides a row of methods allowing the user to export metadata properties to various formats.
## Constructors

| Constructor | Description |
| --- | --- |
| [ExportManager(Iterable<MetadataProperty> properties)](#ExportManager-java.lang.Iterable-com.groupdocs.metadata.core.MetadataProperty--) | Initializes a new instance of the  ExportManager  class. |
## Methods

| Method | Description |
| --- | --- |
| [export(String filePath, ExportFormat format, ExportOptions exportOptions)](#export-java.lang.String-com.groupdocs.metadata.export.ExportFormat-com.groupdocs.metadata.export.ExportOptions-) | Exports the metadata properties to a file. |
| [export(OutputStream document, ExportFormat format, ExportOptions exportOptions)](#export-java.io.OutputStream-com.groupdocs.metadata.export.ExportFormat-com.groupdocs.metadata.export.ExportOptions-) | Exports the metadata properties to a stream. |
| [export(String filePath, ExportFormat format)](#export-java.lang.String-com.groupdocs.metadata.export.ExportFormat-) | Exports the metadata properties to a file. |
| [export(OutputStream document, ExportFormat format)](#export-java.io.OutputStream-com.groupdocs.metadata.export.ExportFormat-) | Exports the metadata properties to a stream. |
### ExportManager(Iterable<MetadataProperty> properties) {#ExportManager-java.lang.Iterable-com.groupdocs.metadata.core.MetadataProperty--}
```
public ExportManager(Iterable<MetadataProperty> properties)
```


Initializes a new instance of the  ExportManager  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| properties | java.lang.Iterable<com.groupdocs.metadata.core.MetadataProperty> | A collection of metadata properties to be exported. |

### export(String filePath, ExportFormat format, ExportOptions exportOptions) {#export-java.lang.String-com.groupdocs.metadata.export.ExportFormat-com.groupdocs.metadata.export.ExportOptions-}
```
public final void export(String filePath, ExportFormat format, ExportOptions exportOptions)
```


Exports the metadata properties to a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The full name of the output file. |
| format | [ExportFormat](../../com.groupdocs.metadata.export/exportformat) | The format of the output file. |
| exportOptions | [ExportOptions](../../com.groupdocs.metadata.export/exportoptions) |  |

### export(OutputStream document, ExportFormat format, ExportOptions exportOptions) {#export-java.io.OutputStream-com.groupdocs.metadata.export.ExportFormat-com.groupdocs.metadata.export.ExportOptions-}
```
public final void export(OutputStream document, ExportFormat format, ExportOptions exportOptions)
```


Exports the metadata properties to a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The full name of the output file. |
| format | [ExportFormat](../../com.groupdocs.metadata.export/exportformat) | The format of the output file. |
| exportOptions | [ExportOptions](../../com.groupdocs.metadata.export/exportoptions) |  |

### export(String filePath, ExportFormat format) {#export-java.lang.String-com.groupdocs.metadata.export.ExportFormat-}
```
public final void export(String filePath, ExportFormat format)
```


Exports the metadata properties to a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The full name of the output file. |
| format | [ExportFormat](../../com.groupdocs.metadata.export/exportformat) | The format of the output file. |

### export(OutputStream document, ExportFormat format) {#export-java.io.OutputStream-com.groupdocs.metadata.export.ExportFormat-}
```
public final void export(OutputStream document, ExportFormat format)
```


Exports the metadata properties to a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The output file stream. |
| format | [ExportFormat](../../com.groupdocs.metadata.export/exportformat) | The format of the output file. |

