---
title: DocumentStatistics
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Obtiene el paquete de estadísticas del documento.
type: docs
weight: 10
url: /es/net/groupdocs.metadata.formats.document/presentationrootpackage/documentstatistics/
---
## PresentationRootPackage.DocumentStatistics property

Obtiene el paquete de estadísticas del documento.

```csharp
public DocumentStatistics DocumentStatistics { get; }
```

### El valor de la propiedad

El paquete de estadísticas de documentos.

### Observaciones

**Aprende más**

* [Trabajar con metadatos en Presentaciones](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Presentations)

### Ejemplos

Este ejemplo de código demuestra cómo obtener estadísticas de texto simple para una presentación.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPpt))
{
    var root = metadata.GetRootPackage<PresentationRootPackage>();

    Console.WriteLine(root.DocumentStatistics.CharacterCount);
    Console.WriteLine(root.DocumentStatistics.PageCount);
    Console.WriteLine(root.DocumentStatistics.WordCount);
}
```

### Ver también

* class [DocumentStatistics](../../documentstatistics)
* class [PresentationRootPackage](../../presentationrootpackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Document](../../presentationrootpackage)
* asamblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->