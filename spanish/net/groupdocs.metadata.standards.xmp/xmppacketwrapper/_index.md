---
title: XmpPacketWrapper
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Contiene un paquete XMP serializado que incluye encabezado y tráiler. Se puede colocar un envoltorio que consta de un par de instrucciones de procesamiento PI XML alrededor del elemento rdfRDF.
type: docs
weight: 3500
url: /es/net/groupdocs.metadata.standards.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

Contiene un paquete XMP serializado que incluye encabezado y tráiler. Se puede colocar un envoltorio que consta de un par de instrucciones de procesamiento (PI) XML alrededor del elemento rdf:RDF.

```csharp
public class XmpPacketWrapper : MetadataPackage, IXmpType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper#constructor)() | Inicializa una nueva instancia del[`XmpPacketWrapper`](../xmppacketwrapper) clase. |
| [XmpPacketWrapper](xmppacketwrapper#constructor_1)(XmpHeaderPI, XmpTrailerPI, XmpMeta) | Inicializa una nueva instancia del[`XmpPacketWrapper`](../xmppacketwrapper) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [HeaderPI](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/headerpi) { get; set; } | Obtiene o establece la instrucción de procesamiento del encabezado. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Meta](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/meta) { get; set; } | Obtiene o establece el meta XMP. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PackageCount](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/packagecount) { get; } | Obtiene el número de paquetes dentro de la estructura XMP. |
| [Packages](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/packages) { get; } | Obtiene una matriz de[`XmpPackage`](../xmppackage) dentro de XMP. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Schemes](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/schemes) { get; } | Proporciona acceso a esquemas XMP conocidos. |
| [TrailerPI](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/trailerpi) { get; set; } | Obtiene o establece la instrucción de procesamiento del tráiler. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddPackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/addpackage)(XmpPackage) | Agrega el paquete. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [ClearPackages](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/clearpackages)() | Elimina todo[`XmpPackage`](../xmppackage) dentro de XMP. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| [ContainsPackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/containspackage)(string) | Determina si el paquete existe en el contenedor XMP. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [GetPackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/getpackage)(string) | Obtiene el paquete por espacio de nombres uri. |
| [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/getxmprepresentation)() | Devuelve el valor contenido en la cadena en formato XMP. |
| [RemovePackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/removepackage)(XmpPackage) | Elimina el paquete especificado. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos XMP](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Ejemplos

Este ejemplo muestra cómo actualizar las propiedades de metadatos XMP.

```csharp
using (Metadata metadata = new Metadata(Constants.GifWithXmp))
{
    IXmp root = metadata.GetRootPackage() as IXmp;
    if (root != null && root.XmpPackage != null)
    {
        // si no existe tal esquema en el paquete XMP debemos crearlo
        if (root.XmpPackage.Schemes.DublinCore == null)
        {
            root.XmpPackage.Schemes.DublinCore = new XmpDublinCorePackage();
        }
        root.XmpPackage.Schemes.DublinCore.Format = "image/gif";
        root.XmpPackage.Schemes.DublinCore.SetRights("Copyright (C) 2011-2022 GroupDocs. All Rights Reserved");
        root.XmpPackage.Schemes.DublinCore.SetSubject("test");

        if (root.XmpPackage.Schemes.CameraRaw == null)
        {
            root.XmpPackage.Schemes.CameraRaw = new XmpCameraRawPackage();
        }
        root.XmpPackage.Schemes.CameraRaw.Shadows = 50;
        root.XmpPackage.Schemes.CameraRaw.AutoBrightness = true;
        root.XmpPackage.Schemes.CameraRaw.AutoExposure = true;
        root.XmpPackage.Schemes.CameraRaw.CameraProfile = "test";
        root.XmpPackage.Schemes.CameraRaw.Exposure = 0.0001;

        // Si no desea mantener los valores anteriores, simplemente reemplace todo el esquema
        root.XmpPackage.Schemes.XmpBasic = new XmpBasicPackage();
        root.XmpPackage.Schemes.XmpBasic.CreateDate = DateTime.Today;
        root.XmpPackage.Schemes.XmpBasic.BaseUrl = "https://groupdocs.com";
        root.XmpPackage.Schemes.XmpBasic.Rating = 5;

        root.XmpPackage.Schemes.BasicJobTicket = new XmpBasicJobTicketPackage();

        // Establecer una propiedad de tipo complejo
        root.XmpPackage.Schemes.BasicJobTicket.Jobs = new[]
        {
            new XmpJob
            {
                ID = "1",
                Name = "test job",
                Url = "https://groupdocs.com"
            },
        };

        // ... 

        metadata.Save(Constants.OutputGif);
    }
}
```

### Ver también

* class [MetadataPackage](../../groupdocs.metadata.common/metadatapackage)
* interface [IXmpType](../ixmptype)
* espacio de nombres [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
