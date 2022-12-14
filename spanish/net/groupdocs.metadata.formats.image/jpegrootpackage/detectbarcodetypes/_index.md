---
title: DetectBarcodeTypes
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Extrae los tipos de códigos de barras presentados en la imagen.
type: docs
weight: 60
url: /es/net/groupdocs.metadata.formats.image/jpegrootpackage/detectbarcodetypes/
---
## JpegRootPackage.DetectBarcodeTypes method

Extrae los tipos de códigos de barras presentados en la imagen.

```csharp
public string[] DetectBarcodeTypes()
```

### Valor_devuelto

Una matriz de tipos de código de barras.

### Observaciones

**Aprende más**

* [Trabajar con metadatos en imágenes JPEG](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG+images)

### Ejemplos

Este fragmento de código demuestra cómo detectar códigos de barras en una imagen JPEG.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithBarcodes))
{
    var root = metadata.GetRootPackage<JpegRootPackage>();

    var barcodeTypes = root.DetectBarcodeTypes();

    foreach (var barcodeType in barcodeTypes)
    {
        Console.WriteLine(barcodeType);
    }
}
```

### Ver también

* class [JpegRootPackage](../../jpegrootpackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Image](../../jpegrootpackage)
* asamblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
