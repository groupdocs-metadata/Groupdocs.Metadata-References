---
title: LoadOptions
second_title: GroupDocs.Metadata for Java API Reference
description: Allows a developer to specify additional options such as a password when loading a file.
type: docs
weight: 10
url: /java/com.groupdocs.metadata.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Allows a developer to specify additional options (such as a password) when loading a file.

**Learn more**

 *  [Load from a local disk][]
 *  [Load from a stream][]
 *  [Load a file of a specific format][]
 *  [Load a password-protected document][]


[Load from a local disk]: https://docs.groupdocs.com/display/metadatajava/Load+from+a+local+disk
[Load from a stream]: https://docs.groupdocs.com/display/metadatajava/Load+from+a+stream
[Load a file of a specific format]: https://docs.groupdocs.com/display/metadatajava/Load+a+file+of+a+specific+format
[Load a password-protected document]: https://docs.groupdocs.com/display/metadatajava/Load+a+password-protected+document
## Constructors

| Constructor | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Initializes a new instance of the  LoadOptions  class. |
| [LoadOptions(FileFormat fileFormat)](#LoadOptions-com.groupdocs.metadata.core.FileFormat-) | Initializes a new instance of the  LoadOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [getPassword()](#getPassword--) | Gets the password for opening an encrypted document. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Sets the password for opening an encrypted document. |
| [getFileFormat()](#getFileFormat--) | Gets the exact type of the file that is to be loaded. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initializes a new instance of the  LoadOptions  class.

### LoadOptions(FileFormat fileFormat) {#LoadOptions-com.groupdocs.metadata.core.FileFormat-}
```
public LoadOptions(FileFormat fileFormat)
```


Initializes a new instance of the  LoadOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileFormat | [FileFormat](../../com.groupdocs.metadata.core/fileformat) | The exact type of the file. |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Gets the password for opening an encrypted document.

**Returns:**
java.lang.String - Can be null or empty string. The default value is null. If the document is not encrypted, set this to null or the empty string.
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Sets the password for opening an encrypted document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Can be null or empty string. The default value is null. If the document is not encrypted, set this to null or the empty string. |

### getFileFormat() {#getFileFormat--}
```
public final FileFormat getFileFormat()
```


Gets the exact type of the file that is to be loaded. The default value is  FileFormat.Unknown  which means that the type should be detected automatically.

**Returns:**
[FileFormat](../../com.groupdocs.metadata.core/fileformat) - The exact type of the file that is to be loaded.
