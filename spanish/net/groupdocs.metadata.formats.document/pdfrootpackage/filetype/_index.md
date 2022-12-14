---
title: FileType
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Obtiene el paquete de metadatos del tipo de archivo.
type: docs
weight: 20
url: /es/net/groupdocs.metadata.formats.document/pdfrootpackage/filetype/
---
## PdfRootPackage.FileType property

Obtiene el paquete de metadatos del tipo de archivo.

```csharp
public PdfTypePackage FileType { get; }
```

### El valor de la propiedad

El paquete de metadatos del tipo de archivo.

### Ejemplos

Este fragmento de código muestra cómo detectar la versión PDF de un documento cargado y extraer información adicional sobre el formato de archivo.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    Console.WriteLine(root.FileType.FileFormat);
    Console.WriteLine(root.FileType.Version);
    Console.WriteLine(root.FileType.MimeType);
    Console.WriteLine(root.FileType.Extension);
}
```

### Ver también

* class [PdfTypePackage](../../pdftypepackage)
* class [PdfRootPackage](../../pdfrootpackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Document](../../pdfrootpackage)
* asamblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
