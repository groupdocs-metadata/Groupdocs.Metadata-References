---
title: GetDocumentInfo
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Obtiene información común sobre el documento cargado.
type: docs
weight: 70
url: /es/net/groupdocs.metadata/metadata/getdocumentinfo/
---
## Metadata.GetDocumentInfo method

Obtiene información común sobre el documento cargado.

```csharp
public IDocumentInfo GetDocumentInfo()
```

### Valor_devuelto

Un objeto que representa información común del documento.

### Observaciones

**Aprende más**

* [Obtener información del documento](https://docs.groupdocs.com/display/metadatanet/Get+document+info)

### Ejemplos

Este ejemplo demuestra cómo extraer información básica de formato de un archivo.

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    if (metadata.FileFormat != FileFormat.Unknown)
    {
        IDocumentInfo info = metadata.GetDocumentInfo();
        Console.WriteLine("File format: {0}", info.FileType.FileFormat);
        Console.WriteLine("File extension: {0}", info.FileType.Extension);
        Console.WriteLine("MIME Type: {0}", info.FileType.MimeType);
        Console.WriteLine("Number of pages: {0}", info.PageCount);
        Console.WriteLine("Document size: {0} bytes", info.Size);
        Console.WriteLine("Is document encrypted: {0}", info.IsEncrypted);
    }
}
```

### Ver también

* interface [IDocumentInfo](../../../groupdocs.metadata.common/idocumentinfo)
* class [Metadata](../../metadata)
* espacio de nombres [GroupDocs.Metadata](../../metadata)
* asamblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
