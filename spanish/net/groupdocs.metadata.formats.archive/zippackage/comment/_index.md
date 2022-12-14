---
title: Comment
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Obtiene o establece el comentario del archivo ZIP creado por un usuario.
type: docs
weight: 10
url: /es/net/groupdocs.metadata.formats.archive/zippackage/comment/
---
## ZipPackage.Comment property

Obtiene o establece el comentario del archivo ZIP creado por un usuario.

```csharp
public string Comment { get; set; }
```

### El valor de la propiedad

El comentario del usuario.

### Ejemplos

El siguiente fragmento de código muestra cómo eliminar el comentario del usuario de un archivo ZIP.

```csharp
using (Metadata metadata = new Metadata(Constants.InputZip))
{
    var root = metadata.GetRootPackage<ZipRootPackage>();

    root.ZipPackage.Comment = null;

    metadata.Save(Constants.OutputZip);
}
```

### Ver también

* class [ZipPackage](../../zippackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Archive](../../zippackage)
* asamblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
