---
title: Metadata
second_title: GroupDocs.Metadata for .NET API Reference
description: Initializes a new instance of the Metadatagroupdocs.metadata/metadata class.
type: docs
weight: 10
url: /net/groupdocs.metadata/metadata/metadata/
---
## Metadata(string) {#constructor_2}

Initializes a new instance of the [`Metadata`](../../metadata) class.

```csharp
public Metadata(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A string that contains the full name of the file from which to create a [`Metadata`](../../metadata) instance. |

### Remarks

**Learn more**

* [Load from a local disk](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Load from a stream](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Load a file of a specific format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Load a password-protected document](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Examples

This example demonstrates how to load a file from a local disk.

```csharp
using (Metadata metadata = new Metadata(Constants.InputOne))
{
    // Extract, edit or remove metadata here
}
```

### See Also

* class [Metadata](../../metadata)
* namespace [GroupDocs.Metadata](../../metadata)
* assembly [GroupDocs.Metadata](../../../)

---

## Metadata(Stream) {#constructor}

Initializes a new instance of the [`Metadata`](../../metadata) class.

```csharp
public Metadata(Stream document)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | A stream that contains the document to load. |

### Remarks

**Learn more**

* [Load from a local disk](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Load from a stream](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Load a file of a specific format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Load a password-protected document](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Examples

This example demonstrates how to load a file from a stream.

```csharp
using (Stream stream = File.Open(Constants.InputDoc, FileMode.Open, FileAccess.ReadWrite))
using (Metadata metadata = new Metadata(stream))
{
   // Extract, edit or remove metadata here
}
```

### See Also

* class [Metadata](../../metadata)
* namespace [GroupDocs.Metadata](../../metadata)
* assembly [GroupDocs.Metadata](../../../)

---

## Metadata(string, LoadOptions) {#constructor_3}

Initializes a new instance of the [`Metadata`](../../metadata) class.

```csharp
public Metadata(string filePath, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A string that contains the full name of the file from which to create a [`Metadata`](../../metadata) instance. |
| loadOptions | LoadOptions | Additional options to use when loading a document. |

### Remarks

**Learn more**

* [Load from a local disk](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Load from a stream](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Load a file of a specific format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Load a password-protected document](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Examples

This example demonstrates how to load a password-protected document.

```csharp
// Specify the password
var loadOptions = new LoadOptions
{
    Password = "123"
};

using (var metadata = new Metadata(Constants.ProtectedDocx, loadOptions))
{
    // Extract, edit or remove metadata here
}
```

### See Also

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* namespace [GroupDocs.Metadata](../../metadata)
* assembly [GroupDocs.Metadata](../../../)

---

## Metadata(Stream, LoadOptions) {#constructor_1}

Initializes a new instance of the [`Metadata`](../../metadata) class.

```csharp
public Metadata(Stream document, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | A stream that contains the document to load. |
| loadOptions | LoadOptions | Additional options to use when loading a document. |

### Remarks

**Learn more**

* [Load from a local disk](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Load from a stream](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Load a file of a specific format](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Load a password-protected document](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### See Also

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* namespace [GroupDocs.Metadata](../../metadata)
* assembly [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
