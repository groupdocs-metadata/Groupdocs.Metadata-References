---
title: DublinCorePackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Obtiene el paquete de metadatos Dublin Core extraído del documento.
type: docs
weight: 20
url: /es/net/groupdocs.metadata.formats.document/wordprocessingrootpackage/dublincorepackage/
---
## WordProcessingRootPackage.DublinCorePackage property

Obtiene el paquete de metadatos Dublin Core extraído del documento.

```csharp
public DublinCorePackage DublinCorePackage { get; }
```

### El valor de la propiedad

El paquete de metadatos de Dublin Core extraído del documento.

### Observaciones

**Aprende más**

* [Trabajar con metadatos en documentos de WordProcessing](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Ejemplos

Este ejemplo muestra cómo extraer metadatos Dublin Core de un documento de WordProcessing.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDocx))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    if (root.DublinCorePackage != null)
    {
        Console.WriteLine(root.DublinCorePackage.Format);
        Console.WriteLine(root.DublinCorePackage.Contributor);
        Console.WriteLine(root.DublinCorePackage.Coverage);
        Console.WriteLine(root.DublinCorePackage.Creator);
        Console.WriteLine(root.DublinCorePackage.Source);
        Console.WriteLine(root.DublinCorePackage.Description);

        // ...
    }
}
```

### Ver también

* class [DublinCorePackage](../../../groupdocs.metadata.standards.dublincore/dublincorepackage)
* class [WordProcessingRootPackage](../../wordprocessingrootpackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Document](../../wordprocessingrootpackage)
* asamblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
