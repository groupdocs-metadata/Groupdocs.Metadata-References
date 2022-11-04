---
title: InspectionPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Obtiene un paquete de metadatos que contiene los resultados de la inspección del documento. El paquete contiene información sobre partes del documento que pueden considerarse metadatos en algunos casos.
type: docs
weight: 40
url: /es/net/groupdocs.metadata.formats.document/wordprocessingrootpackage/inspectionpackage/
---
## WordProcessingRootPackage.InspectionPackage property

Obtiene un paquete de metadatos que contiene los resultados de la inspección del documento. El paquete contiene información sobre partes del documento que pueden considerarse metadatos en algunos casos.

```csharp
public WordProcessingInspectionPackage InspectionPackage { get; }
```

### El valor de la propiedad

Un paquete de metadatos que contiene los resultados de la inspección del documento.

### Observaciones

**Aprende más**

* [Trabajar con metadatos en documentos de WordProcessing](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Ejemplos

Este ejemplo de código muestra cómo inspeccionar un documento de WordProcessing.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDocx))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    if (root.InspectionPackage.Comments != null)
    {
        foreach (var comment in root.InspectionPackage.Comments)
        {
            Console.WriteLine(comment.Author);
            Console.WriteLine(comment.CreatedDate);
            Console.WriteLine(comment.Text);

            // ... 

        }
    }

    if (root.InspectionPackage.DigitalSignatures != null)
    {
        foreach (var signature in root.InspectionPackage.DigitalSignatures)
        {
            Console.WriteLine(signature.CertificateSubject);
            Console.WriteLine(signature.Comments);
            Console.WriteLine(signature.SignTime);

            // ...
        }
    }

    if (root.InspectionPackage.Fields != null)
    {
        foreach (var field in root.InspectionPackage.Fields)
        {
            Console.WriteLine(field.Code);
            Console.WriteLine(field.Result);
        }
    }

    if (root.InspectionPackage.HiddenText != null)
    {
        foreach (var textFragment in root.InspectionPackage.HiddenText)
        {
            Console.WriteLine(textFragment);
        }
    }

    if (root.InspectionPackage.Revisions != null)
    {
         foreach (var revision in root.InspectionPackage.Revisions)
         {
             Console.WriteLine(revision.Author);
             Console.WriteLine(revision.DateTime);
             Console.WriteLine(revision.RevisionType);
          }
     }
}
```

### Ver también

* class [WordProcessingInspectionPackage](../../wordprocessinginspectionpackage)
* class [WordProcessingRootPackage](../../wordprocessingrootpackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Document](../../wordprocessingrootpackage)
* asamblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->