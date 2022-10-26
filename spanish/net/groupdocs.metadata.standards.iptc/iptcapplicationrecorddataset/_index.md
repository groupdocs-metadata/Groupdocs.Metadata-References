---
title: IptcApplicationRecordDataSet
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Define números de conjunto de datos de registro de aplicación IPTC.
type: docs
weight: 2890
url: /es/net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/
---
## IptcApplicationRecordDataSet enumeration

Define números de conjunto de datos de registro de aplicación IPTC.

```csharp
public enum IptcApplicationRecordDataSet
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| RecordVersion | `0` | Representa la versión del registro. Binario. Siempre 2 en archivos JPEG. |
| ObjectTypeReference | `3` | Referencia de tipo de objeto. Patrón utilizado: "/\d{2}:[\w\s]{0,64}?/". |
| ObjectAttributeReference | `4` | La referencia del atributo del objeto. |
| ObjectName | `5` | Se utiliza como referencia abreviada para el objeto. |
| EditStatus | `7` | Estado de los datos del objeto, según la práctica del proveedor. |
| EditorialUpdate | `8` | Indica el tipo de actualización que proporciona este objeto a un objeto anterior. |
| Urgency | `10` | Especifica la urgencia editorial del contenido y no necesariamente la prioridad de manejo de sobres (consulte 1:60, Prioridad de sobres). |
| SubjectReference | `12` | La referencia del asunto. |
| Category | `15` | Identifica el sujeto del objetodatos a juicio del proveedor. |
| SupplementalCategory | `20` | Las categorías suplementarias refinan aún más el tema de un objeto. Solo una única categoría suplementaria puede estar contenida en cada conjunto de datos. Una categoría suplementaria puede incluir cualquiera de las categorías reconocidas como se usa en 2:15. |
| FixtureIdentifier | `22` | El identificador del dispositivo. |
| Keywords | `25` | Se utiliza para indicar palabras específicas de recuperación de información. Cada palabra clave utiliza un único conjunto de datos de palabras clave. Varias palabras clave utilizan varios conjuntos de datos de palabras clave. |
| ContentLocationCode | `26` | Indica el código de un país/ubicación geográfica al que hace referencia el contenido del objeto. |
| ContentLocationName | `27` | Proporciona un nombre completo y publicable de un país/ubicación geográfica al que hace referencia el contenido del objeto, según las directrices del proveedor. |
| ReleaseDate | `30` | Designa en el formato CCAAMMDD la fecha más temprana en que el proveedor pretende que se utilice el objeto. Sigue la norma ISO 8601. |
| ReleaseTime | `35` | Designa en la forma HHMMSS±HHMM la primera vez que el proveedor pretende que se use el objeto. Sigue la norma ISO 8601. |
| ExpirationDate | `37` | Designa en el formato CCAAMMDD la última fecha en la que el proveedor o propietario pretende que se utilicen los datos del objeto. Sigue la norma ISO 8601. |
| SpecialInstructions | `40` | Otras instrucciones editoriales relativas al uso de los datos del objeto, como embargos y advertencias. |
| ActionAdvised | `42` | Indica el tipo de acción que este objeto proporciona a un objeto anterior. |
| ReferenceService | `45` | Identifica el Identificador de Servicio de un sobre anterior al que hace referencia el objeto actual. |
| ReferenceDate | `47` | Identifica la fecha de un sobre anterior al que se refiere el objeto actual. |
| ReferenceNumber | `50` | Identifica el Número de sobre de un sobre anterior al que hace referencia el objeto actual. |
| DateCreated | `55` | Representado en el formato CCAAMMDD para designar la fecha en que se creó el contenido intelectual de los datos del objeto en lugar de la fecha de creación de la representación física. |
| TimeCreated | `60` | Representado en la forma HHMMSS±HHMM para designar el momento en que se creó el contenido intelectual de los datos de objeto material fuente actual en lugar de la creación de la representación física. |
| DigitalCreationDate | `62` | Representado en el formato CCAAMMDD para designar la fecha en que se creó la representación digital de los datos del objeto. |
| DigitalCreationTime | `63` | Representado en la forma HHMMSS±HHMM para designar el momento en que se creó la representación digital de los datos del objeto. |
| OriginatingProgram | `65` | Identifica el tipo de programa utilizado para originar los datos del objeto. |
| ProgramVersion | `70` | Se utiliza para identificar la versión del programa mencionado en 2:65. DataSet 2:70 no es válido si 2:65 no está presente. |
| ObjectCycle | `75` | Consta de un carácter alfabético. Donde: 'a' = mañana, 'p' = tarde, 'b' = ambos. |
| Byline | `80` | Contiene el nombre del creador de los datos del objeto, por ejemplo, escritor, fotógrafo o artista gráfico. |
| BylineTitle | `85` | Un título de línea es el título del creador o creadores de un objeto data. |
| City | `90` | Identifica la ciudad de origen de los datos del objeto de acuerdo con las pautas establecidas por el proveedor. |
| SubLocation | `92` | Identifica la ubicación dentro de una ciudad desde la que se originan los datos del objeto, de acuerdo con las pautas establecidas por el proveedor. |
| ProvinceState | `95` | Identifica Provincia/Estado de origen según lineamientos establecidos por el proveedor. |
| PrimaryLocationCode | `100` | Indica el código del país/ubicación principal donde se creó la propiedad intelectual de los datos del objeto, por ejemplo, se tomó una foto, ocurrió un evento. |
| PrimaryLocationName | `101` | Proporciona el nombre completo y publicable del país/ubicación principal donde se creó la propiedad intelectual de los datos del objeto, de acuerdo con las pautas del proveedor. |
| OriginalTransmissionReference | `103` | Un código que representa la ubicación de la transmisión original según las prácticas del proveedor. |
| Headline | `105` | Una entrada publicable que proporciona una sinopsis del contenido de objectdata. |
| Credit | `110` | Identifica al proveedor de los datos del objeto, no necesariamente al propietario/creador. |
| Source | `115` | El nombre de una persona o parte que tiene una función en la cadena de suministro de contenido. Podría ser una agencia, un miembro de una agencia, un individuo o una combinación. |
| CopyrightNotice | `116` | Contiene cualquier aviso de copyright necesario. |
| Contact | `118` | Identifica la persona u organización que puede proporcionar más antecedentes sobre los datos del objeto. |
| CaptionAbstract | `120` | Una descripción textual de los datos del objeto, especialmente utilizada cuando el objeto no es texto. |
| WriterEditor | `122` | Identificación del nombre de la persona involucrada en la redacción, edición o corrección del objetodato o pie de foto/resumen. |
| RasterizedCaption | `125` | Ancho de la imagen 460 píxeles y altura de la imagen 128 píxeles. Dirección de escaneo de abajo hacia arriba, de izquierda a derecha. |
| ImageType | `130` | Los caracteres numéricos del 1 al 4 indican el número de componentes de una imagen, en sobres simples o múltiples. |
| ImageOrientation | `131` | Indica el diseño del área de la imagen. |
| LanguageIdentifier | `135` | Describe el idioma nacional principal del objeto, de acuerdo con los códigos de 2 letras de ISO 639:1988. |
| AudioType | `150` | El tipo de audio. |
| AudioSamplingRate | `151` | Frecuencia de muestreo Caracteres numéricos, que representan la frecuencia de muestreo en hercios (Hz). |
| AudioSamplingResolution | `152` | El número de bits en cada muestra de audio. |
| AudioDuration | `153` | Duración Designa en el formato HHMMSS el tiempo de ejecución de los datos de un objeto de audio cuando se reproduce a la velocidad a la que se grabó. |
| AudioOutcue | `154` | Identifica el contenido del final de un objeto de audio, según las pautas establecidas por el proveedor. |
| ObjDataPreviewFileFormat | `200` | Un número binario que representa el formato de archivo de la vista previa de ObjectData. |
| ObjDataPreviewFileFormatVer | `201` | Un número binario que representa la versión particular del formato de archivo de vista previa de ObjectData especificado en 2:200. |
| ObjDataPreviewData | `202` | La vista previa de los datos del objeto. |

### Ver también

* espacio de nombres [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
