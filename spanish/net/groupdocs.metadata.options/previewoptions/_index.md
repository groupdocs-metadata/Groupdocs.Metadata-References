---
title: PreviewOptions
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Proporciona opciones para establecer requisitos y transmitir delegados para la generación de vista previa.
type: docs
weight: 2700
url: /es/net/groupdocs.metadata.options/previewoptions/
---
## PreviewOptions class

Proporciona opciones para establecer requisitos y transmitir delegados para la generación de vista previa.

```csharp
public class PreviewOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PreviewOptions](previewoptions#constructor)(CreatePageStream) | Inicializa una nueva instancia del[`PreviewOptions`](../previewoptions)clase que hace que se cierre el flujo de salida. |
| [PreviewOptions](previewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Inicializa una nueva instancia de[`PreviewOptions`](../previewoptions) class que hace que el flujo de salida se devuelva al cliente para su uso posterior. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CacheFolder](../../groupdocs.metadata.options/previewoptions/cachefolder) { get; set; } | Obtiene o establece la carpeta de caché. De manera predeterminada, la carpeta de caché se establece en el directorio temporal local del usuario. |
| [CreatePageStream](../../groupdocs.metadata.options/previewoptions/createpagestream) { get; set; } | Obtiene o establece una instancia del delegado de creación de flujo de páginas. |
| [Height](../../groupdocs.metadata.options/previewoptions/height) { get; set; } | Obtiene o establece la altura de vista previa de la página. |
| [MaxDiskSpaceForCache](../../groupdocs.metadata.options/previewoptions/maxdiskspaceforcache) { get; set; } | Obtiene o establece el espacio de disco máximo disponible para la memoria caché en bytes. El valor predeterminado es 1073741824. |
| [MaxMemoryForCache](../../groupdocs.metadata.options/previewoptions/maxmemoryforcache) { get; set; } | Obtiene o establece la memoria máxima disponible para la memoria caché en bytes. El valor predeterminado es 1073741824. |
| [PageNumbers](../../groupdocs.metadata.options/previewoptions/pagenumbers) { get; set; } | Obtiene o establece una matriz de números de página para generar vistas previas. |
| [PreviewFormat](../../groupdocs.metadata.options/previewoptions/previewformat) { get; set; } | Obtiene o establece el formato de la imagen de vista previa. |
| [ReleasePageStream](../../groupdocs.metadata.options/previewoptions/releasepagestream) { get; set; } | Obtiene o establece una instancia del delegado de finalización de vista previa de página. |
| [Width](../../groupdocs.metadata.options/previewoptions/width) { get; set; } | Obtiene o establece el ancho de vista previa de la página. |

### Observaciones

**Aprende más**

* [Generar vista previa del documento](https://docs.groupdocs.com/display/metadatanet/Generate+document+preview)

### Ver también

* espacio de nombres [GroupDocs.Metadata.Options](../../groupdocs.metadata.options)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->