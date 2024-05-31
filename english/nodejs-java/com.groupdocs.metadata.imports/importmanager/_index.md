---
title: ImportManager
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Provides a row of methods allowing the user to export metadata properties to various formats.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.metadata.imports/importmanager/
---
**Inheritance:**
java.lang.Object
```
public class ImportManager
```

Provides a row of methods allowing the user to export metadata properties to various formats.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImportManager(RootMetadataPackage rootMetadataPackage)](#ImportManager-com.groupdocs.metadata.core.RootMetadataPackage-) | Initializes a new instance of the [ImportManager](../../com.groupdocs.metadata.imports/importmanager) class. |
## Methods

| Method | Description |
| --- | --- |
| [import_(String filePath, int format, ImportOptions importOptions)](#import--java.lang.String-int-com.groupdocs.metadata.imports.ImportOptions-) | Exports the metadata properties to a file. |
| [import_(InputStream stream, int format, ImportOptions importOptions)](#import--java.io.InputStream-int-com.groupdocs.metadata.imports.ImportOptions-) | Exports the metadata properties to a file. |
### ImportManager(RootMetadataPackage rootMetadataPackage) {#ImportManager-com.groupdocs.metadata.core.RootMetadataPackage-}
```
public ImportManager(RootMetadataPackage rootMetadataPackage)
```


Initializes a new instance of the [ImportManager](../../com.groupdocs.metadata.imports/importmanager) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rootMetadataPackage | [RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage) | A collection of metadata properties where the import will be performed.. |

### import_(String filePath, int format, ImportOptions importOptions) {#import--java.lang.String-int-com.groupdocs.metadata.imports.ImportOptions-}
```
public final void import_(String filePath, int format, ImportOptions importOptions)
```


Exports the metadata properties to a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The full name of the input file. |
| format | int | The format of the input file. |
| importOptions | [ImportOptions](../../com.groupdocs.metadata.imports/importoptions) | Additional options to use when importing. |

### import_(InputStream stream, int format, ImportOptions importOptions) {#import--java.io.InputStream-int-com.groupdocs.metadata.imports.ImportOptions-}
```
public final void import_(InputStream stream, int format, ImportOptions importOptions)
```


Exports the metadata properties to a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The filestream of the input file. |
| format | int | The format of the input file. |
| importOptions | [ImportOptions](../../com.groupdocs.metadata.imports/importoptions) | Additional options to use when importing. |

