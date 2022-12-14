---
title: XmpPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Obtiene o establece el paquete de metadatos XMP.
type: docs
weight: 20
url: /es/net/groupdocs.metadata.formats.video/asfrootpackage/xmppackage/
---
## AsfRootPackage.XmpPackage property

Obtiene o establece el paquete de metadatos XMP.

```csharp
public XmpPacketWrapper XmpPackage { get; set; }
```

### El valor de la propiedad

El paquete de metadatos XMP.

### Observaciones

**Aprende más**

* [Trabajar con metadatos XMP](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Ejemplos

Este ejemplo muestra cómo extraer metadatos XMP de un archivo.

```csharp
using (Metadata metadata = new Metadata(Constants.AsfWithXmp))
{
    var root = metadata.GetRootPackage<AsfRootPackage>();
    if (root.XmpPackage != null)
    {
        if (root.XmpPackage.Schemes.XmpBasic != null)
        {
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.CreatorTool);
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.CreateDate);
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.ModifyDate);
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.Label);
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.Nickname);

            // ...
        }

        if (root.XmpPackage.Schemes.DublinCore != null)
        {
            Console.WriteLine(root.XmpPackage.Schemes.DublinCore.Format);
            Console.WriteLine(root.XmpPackage.Schemes.DublinCore.Coverage);
            Console.WriteLine(root.XmpPackage.Schemes.DublinCore.Identifier);
            Console.WriteLine(root.XmpPackage.Schemes.DublinCore.Source);

            // ...
        }

        if (root.XmpPackage.Schemes.Photoshop != null)
        {
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.ColorMode);
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.IccProfile);
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.Country);
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.City);
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.DateCreated);

            // ... 
        }

        // ...
    }
}
```

### Ver también

* class [XmpPacketWrapper](../../../groupdocs.metadata.standards.xmp/xmppacketwrapper)
* class [AsfRootPackage](../../asfrootpackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Video](../../asfrootpackage)
* asamblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
