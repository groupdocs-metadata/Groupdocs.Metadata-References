---
title: ImageResourceID
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Números de identificación estándar de recursos de imágenes. No todos los formatos de archivo utilizan todos los ID. Parte de la información puede almacenarse en otras secciones del archivo.
type: docs
weight: 1750
url: /es/net/groupdocs.metadata.formats.image/imageresourceid/
---
## ImageResourceID enumeration

Números de identificación estándar de recursos de imágenes. No todos los formatos de archivo utilizan todos los ID. Parte de la información puede almacenarse en otras secciones del archivo.

```csharp
public enum ImageResourceID
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| ResolutionInfo | `1005` | Estructura ResolutionInfo. Consulte el Apéndice A en el documento PDF de la Guía API de Photoshop. |
| NamesOfAlphaChannels | `1006` | Nombres de los canales alfa como una serie de cadenas de Pascal. |
| Caption | `1008` | El título como una cadena de Pascal. |
| BorderInformation | `1009` | Información de borde. Contiene un número fijo (2 bytes reales, 2 bytes fracción) para el ancho del borde, y 2 bytes para las unidades del borde (1 = pulgadas, 2 = cm, 3 = puntos, 4 = picas, 5 = columnas). |
| BackgroundColor | `1010` | Color de fondo. [Ver más.](http://www.adobe.com/devnet-apps/photoshop/fileformatashtml/#50577411_31265) |
| PrintFlags | `1011` | Imprimir banderas. Una serie de valores booleanos de un byte (consulte el cuadro de diálogo Configurar página): etiquetas, marcas de corte, barras de color, marcas de registro, negativo, voltear, interpolar, título, banderas de impresión. |
| Grayscale | `1012` | Información de escala de grises y medios tonos multicanal. |
| ColorHalftoning | `1013` | Información de medios tonos de color. |
| DuotoneHalftoning | `1014` | Información de medios tonos de duotono. |
| GrayscaleFunction | `1015` | Escala de grises y función de transferencia multicanal. |
| ColorTransferFunctions | `1016` | Funciones de transferencia de color. |
| DuotoneTransferFunctions | `1017` | Funciones de transferencia de duotono. |
| DuotoneImageInformation | `1018` | Información de imagen de duotono. |
| EPSOptions | `1021` | Opciones EPS. |
| QuickMaskInformation | `1022` | Información de máscara rápida. 2 bytes que contienen ID de canal de máscara rápida; Booleano de 1 byte que indica si la máscara estaba inicialmente vacía. |
| LayerStateInformation | `1024` | Información del estado de la capa. 2 bytes que contienen el índice de la capa de destino (0 = capa inferior). |
| WorkingPath | `1025` | Ruta de trabajo (no guardada). Consulte Ver formato de recurso de ruta. |
| LayersGroupInformation | `1026` | Información del grupo de capas. 2 bytes por capa que contiene un ID de grupo para los grupos de arrastre. Las capas de un grupo tienen el mismo ID de grupo. |
| Iptc | `1028` | Registro IPTC-NAA. Contiene la información Información de archivo.... Consulte la documentación en la carpeta IPTC de la carpeta Documentación. |
| ImageModeForRawFormat | `1029` | Modo de imagen para archivos en formato raw. |
| JpegQuality | `1030` | Calidad JPEG. Privado. |
| GridAndGuidesInfoPhotoshop4 | `1032` | Información de cuadrículas y guías. |
| ThumbnailResourcePhotoshop4 | `1033` | Recurso de miniaturas solo para Photoshop 4.0. |
| CopyrightFlagPhotoshop4 | `1034` | Indicador de derechos de autor. Booleano que indica si la imagen tiene derechos de autor. Se puede configurar a través del conjunto de propiedades o por el usuario en Información de archivo... |
| UrlPhotoshop4 | `1035` | URL . Identificador de una cadena de texto con localizador uniforme de recursos. Se puede configurar a través del conjunto de propiedades o por el usuario en Información de archivo... |
| ThumbnailResourcePhotoshop5 | `1036` | Recurso de miniaturas (reemplaza al recurso 1033). Consulte Ver formato de recursos de miniaturas. |
| GlobalAnglePhotoshop5 | `1037` | Ángulo global. 4 bytes que contienen un número entero entre 0 y 359, que es el ángulo de iluminación global para la capa de efectos. Si no está presente, se supone que es 30. |
| IccProfilePhotoshop5 | `1039` | (Photoshop 5.0) Perfil ICC. Los bytes sin procesar de un perfil de formato ICC (International Color Consortium). Consulte ICC1v42_2006-05.pdf en la carpeta Documentación y icProfileHeader.h en Código de ejemplo\Común\Incluye. |
| WatermarkPhotoshop5 | `1040` | Marca de agua. Un byte. |
| IccUntaggedProfilePhotoshop5 | `1041` | Perfil sin etiqueta ICC. 1 byte que deshabilita cualquier manejo de perfil asumido al abrir el archivo. 1 = intencionalmente sin etiquetar. |
| TransparencyIndexPhotoshop6 | `1047` | Índice de transparencia. 2 bytes para el índice de color transparente, si lo hay. |
| GlobalAltitudePhotoshop6 | `1049` | Altitud global. Entrada de 4 bytes para altitude. |
| SlicesPhotoshop6 | `1050` | Rebanadas (Photoshop 6). |
| WorkflowUrlPhotoshop6 | `1051` | URL de flujo de trabajo. Cadena Unicode. Photoshop 6. |
| AlphaIdentifiersPhotoshop6 | `1053` | Identificadores Alfa. 4 bytes de longitud, seguidos de 4 bytes cada uno para cada identificador alfabético. |
| UrlListPhotoshop6 | `1054` | Lista interna de URL. Recuento de URL de 4 bytes, seguido de 4 bytes de longitud, ID de 4 bytes y cadena Unicode para cada recuento. |
| VersionInfoPhotoshop6 | `1057` | Información de la versión. Versión de 4 bytes, hasRealMergedData de 1 byte, cadena Unicode: nombre del escritor, cadena Unicode: nombre del lector, versión del archivo de 4 bytes. |
| ExifData1Photoshop7 | `1058` | datos EXIF 1,[ver más](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) . |
| ExifData3Photoshop7 | `1059` | [ Datos EXIF 3.](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) |
| XmpPhotoshop7 | `1060` | metadatos XMP. Información del archivo como descripción XML,[ver más](http://www.adobe.com/devnet/xmp) . |
| CaptionDigestPhotoshop7 | `1061` | Resumen de subtítulos. 16 bytes: RSA Data Security, algoritmo de resumen de mensaje MD5. |
| PrintScalePhotoshop7 | `1062` | Escala de impresión. Estilo de 2 bytes (0 = centrado, 1 = tamaño para ajustar, 2 = definido por el usuario). 4 bytes x ubicación (coma flotante). 4 bytes y ubicación (coma flotante). Escala de 4 bytes (coma flotante). |
| PixelAspectRatio | `1064` | Relación de aspecto de píxeles. 4 bytes (versión = 1 o 2), 8 bytes dobles, x/y de un píxel. Versión 2, intentando corregir los valores para NTSC y PAL, previamente desactivados por un factor de aprox. 5%. |
| LayerComps | `1065` | Compensaciones de capa. 4 bytes (versión del descriptor = 16), Descriptor. |
| LayerSelectionIds | `1069` | ID(s) de selección de capa. Cuenta de 2 bytes, lo siguiente se repite para cada cuenta: ID de capa de 4 bytes. |
| PrintInfoCS2 | `1071` | Información de impresión (Photoshop CS2). |
| LayerGroupEnabledIdCS2 | `1072` | Id. de grupos de capas habilitados. 1 byte por cada capa del documento, repetido por longitud del recurso. NOTA: Los grupos de capas tienen marcadores de inicio y finalización (Photoshop CS2). |
| ColorSamplersResourceCS3 | `1073` | Recurso de muestras de color. Consulte también ID 1038 para formato antiguo. |
| MeasurementScaleCS3 | `1074` | Escala de medida. 4 bytes (versión del descriptor = 16), Descriptor. |
| TimelineInformationCS3 | `1075` | Información de la línea de tiempo. 4 bytes (versión del descriptor = 16), Descriptor. |
| SheetDisclosureCS3 | `1076` | Hoja de divulgación. 4 bytes (versión del descriptor = 16), Descriptor. |
| PrintInformationCS5 | `1082` | Información de impresión (Photoshop CS5). |
| PrintStyleCS5 | `1083` | Estilo de impresión (Photoshop CS5). |
| MacintoshNSPrintInfoCS5 | `1084` | Macintosh NSPrintInfo. Información específica del sistema operativo variable para Macintosh. NSPrintInfo. Se recomienda no interpretar ni utilizar estos datos. (Photoshop CS5). |
| WindowsDevmodeCS5 | `1085` | Windows DEVMODE. Información específica del sistema operativo variable para Windows. MODO DEV. Se recomienda no interpretar ni utilizar estos datos. (Photoshop CS5). |
| AutoSaveFilePathCS6 | `1086` | Ruta del archivo de guardado automático. Cadena Unicode. (Photoshop CS6). |
| AutoSaveFormatCS6 | `1087` | Formato de guardado automático. Cadena Unicode. (Photoshop CS6). |
| PathSelectionStateCC | `1088` | Estado de selección de ruta. (Photoshop CC). |
| ImageReadyVariables | `7000` | Variables preparadas para imagen. Representación XML de definición de variables. |
| ImageReadyDatasets | `7001` | Conjuntos de datos listos para imagen. |
| PrintFlagsInformation | `10000` | Imprimir información de banderas. versión de 2 bytes ( = 1), 1 byte de marcas de recorte central, 1 byte ( = 0), valor de ancho de sangrado de 4 bytes, escala de ancho de sangrado de 2 bytes. |

### Ver también

* espacio de nombres [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
