---
title: TiffTagID
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Define ids de etiquetas TIFF.
type: docs
weight: 2100
url: /es/net/groupdocs.metadata.formats.image/tifftagid/
---
## TiffTagID enumeration

Define ids de etiquetas TIFF.

```csharp
public enum TiffTagID : ushort
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| GpsVersionID | `0` | Indica la versión de GPSInfoIFD. |
| GpsLatitudeRef | `1` | Indica si la latitud es latitud norte o latitud sur. |
| GpsLatitude | `2` | Indica la latitud. |
| GpsLongitudeRef | `3` | Indica si la longitud es longitud este u oeste. |
| GpsLongitude | `4` | Indica la longitud. |
| GpsAltitudeRef | `5` | Indica la altitud utilizada como altitud de referencia. |
| GpsAltitude | `6` | Indica la altitud en base a la referencia en GPSAltitudeRef. |
| GpsTimeStamp | `7` | Indica la hora como UTC (Tiempo Universal Coordinado). |
| GpsSatellites | `8` | indica los satélites GPS utilizados para las mediciones. |
| GpsStatus | `9` | Indica el estado del receptor GPS cuando se graba la imagen. |
| GpsMeasureMode | `10` | Indica el modo de medición GPS. |
| GpsDop | `11` | Indica el GPS DOP (grado de precisión de los datos). |
| GpsSpeedRef | `12` | Indica la unidad utilizada para expresar la velocidad de movimiento del receptor GPS |
| GpsSpeed | `13` | Indica la velocidad de movimiento del receptor GPS. |
| GpsTrackRef | `14` | Indica la referencia para dar la dirección de movimiento del receptor GPS. |
| GpsTrack | `15` | Indica la dirección del movimiento del receptor GPS. |
| GpsImgDirectionRef | `16` | Indica la referencia para dar la dirección de la imagen cuando se captura. |
| GpsImgDirection | `17` | Indica la dirección de la imagen cuando fue capturada. |
| GpsMapDatum | `18` | Indica los datos de levantamiento geodésico utilizados por el receptor GPS. |
| GpsDestLatitudeRef | `19` | Indica si la latitud del punto de destino es latitud norte o sur. |
| GpsDestLatitude | `20` | Indica la latitud del punto de destino. |
| GpsDestLongitudeRef | `21` | Indica si la longitud del punto de destino es longitud este u oeste. |
| GpsDestLongitude | `22` | Indica la longitud del punto de destino. |
| GpsDestBearingRef | `23` | Indica la referencia utilizada para dar el rumbo al punto de destino. |
| GpsDestBearing | `24` | Indica el rumbo al punto de destino. |
| GpsDestDistanceRef | `25` | Indica la unidad utilizada para expresar la distancia al punto de destino. |
| GpsDestDistance | `26` | Indica la distancia al punto de destino. |
| GpsProcessingMethod | `27` | Una cadena de caracteres que registra el nombre del método utilizado para encontrar la ubicación. |
| GpsAreaInformation | `28` | Una cadena de caracteres que registra el nombre del área GPS. |
| GpsDateStamp | `29` | Una cadena de caracteres que registra información de fecha y hora relativa a UTC (Tiempo universal coordinado). |
| GpsDifferential | `30` | Indica si se aplica corrección diferencial al receptor GPS. |
| GpsHPositioningError | `31` | Esta etiqueta indica errores de posicionamiento horizontal en metros. |
| NewSubfileType | `254` | Una indicación general del tipo de datos contenidos en este subarchivo. |
| SubfileType | `255` | Una indicación general del tipo de datos contenidos en este subarchivo. Este campo está en desuso. El campo NewSubfileType debe usarse en su lugar |
| ImageWidth | `256` | El número de columnas de la imagen, es decir, el número de píxeles por línea de exploración. |
| ImageLength | `257` | El número de filas (a veces descritas como líneas de escaneo) en la imagen. |
| BitsPerSample | `258` | Número de bits por componente. |
| Compression | `259` | Esquema de compresión utilizado en los datos de la imagen. |
| PhotometricInterpretation | `262` | El espacio de color de los datos de la imagen. |
| Threshholding | `263` | Para archivos TIFF en blanco y negro que representan sombras de gris, la técnica utilizada para convertir píxeles de gris a blanco y negro. |
| CellWidth | `264` | El ancho de la matriz de tramado o medios tonos utilizada para crear un archivo de dos niveles tramado o de medios tonos. |
| CellLength | `265` | La longitud de la matriz de tramado o medios tonos utilizada para crear un archivo de dos niveles tramado o de medios tonos. |
| FillOrder | `266` | El orden lógico de bits dentro de un byte. |
| DocumentName | `269` | El nombre del documento del que se escaneó esta imagen. |
| ImageDescription | `270` | Una cadena que describe el tema de la imagen. |
| Make | `271` | El fabricante del escáner. |
| Model | `272` | El nombre o número del modelo del escáner. |
| StripOffsets | `273` | Para cada franja, el desplazamiento de bytes de esa franja. |
| Orientation | `274` | La orientación de la imagen con respecto a las filas y columnas. |
| SamplesPerPixel | `277` | El número de componentes por píxel. |
| RowsPerStrip | `278` | El número de filas por tira. |
| StripByteCounts | `279` | Para cada tira, el número de bytes en la tira después de la compresión. |
| MinSampleValue | `280` | El valor de componente mínimo utilizado. |
| MaxSampleValue | `281` | El valor de componente máximo utilizado. |
| XResolution | `282` | El número de píxeles por unidad de resolución en la dirección ImageWidth. |
| YResolution | `283` | El número de píxeles por Unidad de resolución en la dirección ImageLength. |
| PlanarConfiguration | `284` | Cómo se almacenan los componentes de cada píxel. |
| PageName | `285` | El nombre de la página desde la que se escaneó esta imagen. |
| XPosition | `286` | Posición X de la imagen. |
| YPosition | `287` | Posición Y de la imagen. |
| FreeOffsets | `288` | Para cada cadena de bytes no utilizados contiguos en un archivo TIFF, el desplazamiento de bytes de la cadena. |
| FreeByteCounts | `289` | Para cada cadena de bytes no utilizados contiguos en un archivo TIFF, el número de bytes en la cadena. |
| GrayResponseUnit | `290` | La precisión de la información contenida en GrayResponseCurve. |
| GrayResponseCurve | `291` | Para datos en escala de grises, la densidad óptica de cada valor de píxel posible. |
| T4Options | `292` | Opciones de codificación T4. |
| T6Options | `293` | Opciones de codificación T6. |
| ResolutionUnit | `296` | La unidad de medida para XResolution y YResolution. |
| PageNumber | `297` | El número de página de la página desde la que se escaneó esta imagen. |
| TransferFunction | `301` | Describe una función de transferencia para la imagen en estilo tabular. Los componentes de píxeles pueden ser compensados con gamma, compansados, cuantificados de manera no uniforme o codificados de alguna otra forma. TransferFunction asigna los componentes de píxeles de una forma no lineal BitsPerSample (por ejemplo, 8 bits) a una forma lineal de 16 bits sin una pérdida perceptible de precisión. |
| Software | `305` | Nombre y número de versión de los paquetes de software usados para crear la imagen. |
| DateTime | `306` | Fecha y hora de creación de la imagen. |
| Artist | `315` | Persona que creó la imagen. |
| HostComputer | `316` | La computadora y/o el sistema operativo en uso en el momento de la creación de la imagen. |
| Predictor | `317` | Esta sección define un Predictor que mejora en gran medida los índices de compresión para algunas imágenes. |
| WhitePoint | `318` | La cromaticidad del punto blanco de la imagen. |
| PrimaryChromaticities | `319` | Las cromaticidades de los primarios de la imagen. |
| ColorMap | `320` | Un mapa de colores para imágenes de paleta de colores. |
| HalftoneHints | `321` | El propósito del campo HalftoneHints es transmitir a la función de medios tonos el rango de niveles de gris dentro de una imagen especificada colorimétricamente que debería retener detalle tonal. |
| TileWidth | `322` | El ancho del mosaico en píxeles. Este es el número de columnas en cada mosaico. |
| TileLength | `323` | La longitud del mosaico (alto) en píxeles. Este es el número de filas en cada mosaico. |
| TileOffsets | `324` | Para cada mosaico, el byte de desplazamiento de ese mosaico, comprimido y almacenado en el disco. El desplazamiento se especifica con respecto al comienzo del archivo TIFF. Tenga en cuenta que esto implica que cada mosaico tiene una ubicación independiente de las ubicaciones de otros mosaicos. |
| TileByteCounts | `325` | Para cada mosaico, el número de bytes (comprimidos) en ese mosaico. |
| InkSet | `332` | El conjunto de tintas utilizadas en una imagen separada (Interpretación fotométrica=5). |
| InkNames | `333` | El nombre de cada tinta utilizada en una imagen separada (Interpretación fotométrica=5), escrito como una lista de cadenas ASCII terminadas en NUL concatenadas. |
| NumberOfInks | `334` | El número de tintas. Por lo general, es igual a SamplesPerPixel, a menos que haya muestras adicionales. |
| DotRange | `336` | Los valores de los componentes que corresponden a un punto 0% y un punto 100%. DotRange[0] corresponde a un 0 % de puntos, y DotRange[1] corresponde a un 100 % de puntos. |
| ExtraSamples | `338` | Descripción de componentes adicionales. |
| SampleFormat | `339` | Este campo especifica cómo interpretar cada muestra de datos en un píxel. |
| SMinSampleValue | `340` | Este campo especifica el valor mínimo de la muestra. |
| SMaxSampleValue | `341` | Este nuevo campo especifica el valor máximo de la muestra. |
| TransferRange | `342` | Expande el rango de TransferFunction. |
| JpegProc | `512` | Este campo indica el proceso JPEG utilizado para producir los datos comprimidos. |
| JpegInterchangeFormat | `513` | Este campo indica si un flujo de bits de formato de intercambio JPEG está presente en el archivo TIFF. |
| JpegInterchangeFormatLength | `514` | Este campo indica la longitud en bytes del formato de intercambio JPEG bitstream |
| JpegRestartInterval | `515` | Este campo indica la duración del intervalo de reinicio utilizado en los datos de la imagen comprimida. |
| JpegLosslessPredictors | `517` | Este campo apunta a una lista de valores de selección de predictor sin pérdida, uno por componente. |
| JpegPointTransforms | `518` | Este campo apunta a una lista de valores de transformación de puntos, uno por componente. |
| JpegQTables | `519` | Este campo apunta a una lista de compensaciones a las tablas de cuantificación, una por componente. |
| JpegDCTables | `520` | Este campo apunta a una lista de compensaciones para las tablas DC Huffman o las tablas Huffman sin pérdidas , una por componente. |
| JpegACTables | `521` | Este campo apunta a una lista de compensaciones a las tablas Huffman AC, una por componente. |
| YCbCrCoefficients | `529` | Los coeficientes de matriz para la transformación de datos de imagen RGB a YCbCr. |
| YCbCrSubSampling | `530` | La relación de muestreo de los componentes de crominancia en relación con el componente de luminancia. |
| YCbCrPositioning | `531` | Especifica el posicionamiento de los componentes de crominancia submuestreados en relación con las muestras de luminancia. |
| ReferenceBlackWhite | `532` | Especifica un par de valores (códigos) de datos de imagen de espacio para la cabeza y espacio para los pies para cada componente de píxel. |
| Copyright | `33432` | Aviso de derechos de autor. |
| UserComment | `37510` | Palabras clave o comentarios sobre la imagen; complementa ImageDescription. |
| Xmp | `700` | Puntero a los metadatos XMP. |
| ImageID | `32781` | relacionado con OPI. |
| Iptc | `33723` | IPTC (Consejo Internacional de Telecomunicaciones de Prensa) metadatos. A menudo, el tipo de datos se especifica incorrectamente como LONG. |
| Photoshop | `34377` | Colección de "Bloques de recursos de imagen" de Photoshop. |
| ImageLayer | `34732` | Capa de imagen. |
| IccProfile | `34675` | Datos de perfil de color. |
| ExifIfd | `34665` | Puntero a la recopilación de todos los metadatos EXIF. EXIF usa nombres de campo en lugar de etiquetas para indicar el contenido del campo. |
| GpsIfd | `34853` | Puntero a datos GPS. |
| Makernotes | `37500` | Puntero a datos de makernotes. |
| InteroperabilityIfd | `40965` | Interoperabilidad relacionada con Exif IFD. |
| CameraOwnerName | `42032` | Nombre del propietario de la cámara como cadena ASCII. |
| BodySerialNumber | `42033` | Número de serie del cuerpo de la cámara como cadena ASCII. |
| CfaPattern | `41730` | indica el patrón geométrico de matriz de filtro de color (CFA) del sensor de imagen cuando se utiliza un sensor de área de color de un chip. No se aplica a todos los métodos de detección. |
| ExifVersion | `36864` | La versión del estándar EXIF compatible. |
| ComponentsConfiguration | `37121` | Información específica de los datos comprimidos. Los canales de cada componente están ordenados desde el primer componente hasta el cuarto. |
| FlashpixVersion | `40960` | La versión del formato Flashpix compatible con un archivo FPXR. Si la función FPXR es compatible con el formato Flashpix Ver. 1.0, esto se indica de manera similar a ExifVersion al registrar "0100" como ASCII de 4 bytes. |
| ColorSpace | `40961` | La etiqueta de información del espacio de color (ColorSpace) siempre se registra como el especificador de espacio de color. Normalmente se usa sRGB (=1) para definir el espacio de color según las condiciones y el entorno del monitor de la PC. Si se utiliza un espacio de color que no sea sRGB, se establece Sin calibrar (=FFFF.H). |
| PixelXDimension | `40962` | Información específica de los datos comprimidos. Cuando se registra un archivo comprimido, el ancho válido de la imagen significativa se registrará en esta etiqueta, haya o no datos de relleno o un marcador de reinicio. |
| PixelYDimension | `40963` | Información específica de los datos comprimidos. Cuando se registra un archivo comprimido, la altura válida de la imagen significativa se registrará en esta etiqueta, haya o no datos de relleno o un marcador de reinicio. |
| SceneCaptureType | `41990` | Esta etiqueta indica el tipo de escena que se filmó. También se puede utilizar para registrar el modo en que se tomó la imagen. |
| Gamma | `42240` | Indica el valor del coeficiente gamma. |
| CompressedBitsPerPixel | `37122` | Información específica de los datos comprimidos. El modo de compresión utilizado para una imagen comprimida se indica en unidades de bits por píxel. |
| RelatedSoundFile | `40964` | Esta etiqueta se utiliza para registrar el nombre de un archivo de audio relacionado con los datos de la imagen. La única información relacional registrada aquí es el nombre del archivo de audio Exif y la extensión (una cadena ASCII que consta de 8 caracteres + '.' + 3 caracteres). |
| DateTimeOriginal | `36867` | La fecha y la hora en que se generaron los datos de la imagen original. Para un DSC, se registran la fecha y la hora en que se tomó la imagen. El formato es "YYYY:MM:DD HH:MM:SS" con la hora en formato de 24 horas y la fecha y la hora separadas por un carácter en blanco. |
| DateTimeDigitized | `36868` | La fecha y la hora en que se almacenó la imagen como datos digitales. Si, por ejemplo, DSC capturó una imagen y al mismo tiempo se grabó el archivo, DateTimeOriginal y DateTimeDigitized tendrán el mismo contenido. El formato es "YYYY:MM:DD HH:MM:SS" con la hora en formato de 24 horas y la fecha y la hora separadas por un carácter en blanco. |
| OffsetTime | `36880` | Una etiqueta que se utiliza para registrar el desplazamiento de UTC (la diferencia horaria con respecto a la hora universal coordinada, incluido el horario de verano) de la hora de la etiqueta DateTime. El formato al registrar el desplazamiento es "±HH:MM". La parte de "±" se registrará como "+" o "-". |
| OffsetTimeOriginal | `36881` | Una etiqueta que se utiliza para registrar el desplazamiento desde UTC (la diferencia horaria con respecto al tiempo universal coordinado, incluido el horario de verano) de la hora de la etiqueta DateTimeOriginal. El formato al registrar el desplazamiento es "±HH:MM". La parte de "±" se registrará como "+" o "-". |
| OffsetTimeDigitized | `36882` | Una etiqueta que se utiliza para registrar el desplazamiento desde UTC (la diferencia horaria con respecto a la hora universal coordinada, incluido el horario de verano) de la hora de la etiqueta DateTimeDigitized. El formato al registrar el desplazamiento es "±HH:MM". La parte de "±" se registrará como "+" o "-". |
| SubsecTime | `37520` | Una etiqueta utilizada para registrar fracciones de segundos para la etiqueta DateTime. |
| SubsecTimeOriginal | `37521` | Una etiqueta utilizada para registrar fracciones de segundos para la etiqueta DateTimeOriginal. |
| SubsecTimeDigitized | `37522` | Una etiqueta utilizada para registrar fracciones de segundos para la etiqueta DateTimeDigitized. |
| ExposureTime | `33434` | Tiempo de exposición, expresado en segundos (seg). |
| FNumber | `33437` | El número F. |
| ExposureProgram | `34850` | La clase del programa utilizado por la cámara para establecer la exposición cuando se toma la fotografía. |
| SpectralSensitivity | `34852` | Indica la sensibilidad espectral de cada canal de la cámara utilizada. El valor de la etiqueta es una cadena ASCII compatible con el estándar desarrollado por el comité técnico de ASTM. |
| PhotographicSensitivity | `34855` | Esta etiqueta indica la sensibilidad de la cámara o dispositivo de entrada cuando se tomó la imagen. |
| Oecf | `34856` | Indica la función de conversión optoeléctrica (OECF) especificada en ISO 14524. OECF es la relación entre la entrada óptica de la cámara y los valores de imagen. |
| SensitivityType | `34864` | La etiqueta SensitivityType indica cuál de los parámetros de ISO12232 es la etiqueta PhotographicSensitivity. Aunque es una etiqueta opcional, debe registrarse cuando se registra una etiqueta PhotographicSensitivity. |
| StandardOutputSensitivity | `34865` | Esta etiqueta indica el valor de sensibilidad de salida estándar de una cámara o dispositivo de entrada definido en ISO 12232. Al registrar esta etiqueta, también deben registrarse las etiquetas PhotographicSensitivity y SensitivityType. |
| RecommendedExposureIndex | `34866` | Esta etiqueta indica el valor del índice de exposición recomendado de una cámara o dispositivo de entrada definido en ISO 12232. Al registrar esta etiqueta, también se deben registrar las etiquetas PhotographicSensitivity y SensitivityType. |
| IsoSpeed | `34867` | Esta etiqueta indica el valor de velocidad ISO de una cámara o dispositivo de entrada que se define en ISO 12232. Al registrar esta etiqueta, también se deben registrar las etiquetas PhotographicSensitivity y SensitivityType. |
| ISOSpeedLatitudeYyy | `34868` | Esta etiqueta indica el valor de latitud yyy de velocidad ISO de una cámara o dispositivo de entrada definido en ISO 12232. |
| ISOSpeedLatitudeZzz | `34869` | Esta etiqueta indica el valor zzz de latitud de velocidad ISO de una cámara o dispositivo de entrada definido en ISO 12232. |
| ShutterSpeedValue | `37377` | Velocidad de obturación. La unidad es el ajuste APEX (Sistema Aditivo de Exposición Fotográfica). |
| ApertureValue | `37378` | La apertura de la lente. La unidad es el valor APEX. |
| BrightnessValue | `37379` | El valor del brillo. La unidad es el valor APEX. |
| ExposureBiasValue | `37380` | El sesgo de exposición. La unidad es el valor APEX. |
| MaxApertureValue | `37381` | El número F más pequeño de la lente. La unidad es el valor APEX. |
| SubjectDistance | `37382` | La distancia al sujeto, dada en metros. |
| MeteringMode | `37383` | El modo de medición. |
| LightSource | `37384` | El tipo de fuente de luz. |
| Flash | `37385` | Esta etiqueta indica el estado del flash cuando se tomó la imagen. El bit 0 indica el estado de disparo del flash, los bits 1 y 2 indican el estado de retorno del flash, Los bits 3 y 4 indican el modo de flash, el bit 5 indica si la función de flash está presente y el bit 6 indica el modo de "ojos rojos". |
| SubjectArea | `37396` | Esta etiqueta indica la ubicación y el área del sujeto principal en la escena general. |
| FocalLength | `37386` | La distancia focal real de la lente, en mm. La conversión no se realiza a la distancia focal de una cámara de película de 35 mm. |
| FlashEnergy | `41483` | Indica la energía estroboscópica en el momento en que se captura la imagen, medida en Beam Candle Power Seconds (BCPS). |
| SpatialFrequencyResponse | `41484` | Esta etiqueta registra la tabla de frecuencia espacial de la cámara o el dispositivo de entrada y los valores SFR en la dirección del ancho de la imagen, la altura de la imagen y la dirección diagonal, como se especifica en ISO 12233. |
| FocalPlaneXResolution | `41486` | Indica el número de píxeles en la dirección del ancho de la imagen (X) por FocalPlaneResolutionUnit en el plano focal de la cámara. |
| FocalPlaneYResolution | `41487` | Indica el número de píxeles en la dirección de la altura de la imagen (Y) por FocalPlaneResolutionUnit en el plano focal de la cámara. |
| FocalPlaneResolutionUnit | `41488` | Indica la unidad para medir FocalPlaneXResolution y FocalPlaneYResolution. Este valor es el mismo que ResolutionUnit. |
| SubjectLocation | `41492` | Indica la ubicación del sujeto principal en la escena. El valor de esta etiqueta representa el píxel en el centro del sujeto principal en relación con el borde izquierdo, antes del procesamiento de rotación según la etiqueta Rotación. El primer valor indica el número de columna X y el segundo indica el número de fila Y. |
| ExposureIndex | `41493` | Indica el índice de exposición seleccionado en la cámara o dispositivo de entrada en el momento de capturar la imagen. |
| SensingMethod | `41495` | Indica el tipo de sensor de imagen en la cámara o dispositivo de entrada. |
| FileSource | `41728` | Indica la fuente de la imagen. Si un DSC grabó la imagen, este valor de etiqueta siempre se establecerá en 3. |
| SceneType | `41729` | Indica el tipo de escena. Si un DSC grabó la imagen, este valor de etiqueta siempre se establecerá en 1, lo que indica que la imagen fue fotografiada directamente. |
| CustomRendered | `41985` | Esta etiqueta indica el uso de un procesamiento especial en los datos de imagen, como la representación orientada a la salida. |
| ExposureMode | `41986` | Esta etiqueta indica el modo de exposición establecido cuando se tomó la imagen. En el modo de horquillado automático, la cámara toma una serie de fotogramas de la misma escena con diferentes ajustes de exposición. |
| WhiteBalance | `41987` | Esta etiqueta indica el modo de balance de blancos establecido cuando se tomó la imagen. |
| DigitalZoomRatio | `41988` | Esta etiqueta indica la relación de zoom digital cuando se tomó la imagen. Si el numerador del valor registrado es 0, esto indica que no se utilizó el zoom digital. |
| FocalLengthIn35mmFilm | `41989` | Esta etiqueta indica la distancia focal equivalente suponiendo una cámara de película de 35 mm, en mm. Un valor de 0 significa que se desconoce la distancia focal. Tenga en cuenta que esta etiqueta difiere de la etiqueta FocalLength. |
| GainControl | `41991` | Esta etiqueta indica el grado de ajuste general de la ganancia de la imagen. |
| Contrast | `41992` | Esta etiqueta indica la dirección del procesamiento de contraste aplicado por la cámara cuando se tomó la imagen. |
| Saturation | `41993` | Esta etiqueta indica la dirección del procesamiento de saturación aplicado por la cámara cuando se tomó la imagen. |
| Sharpness | `41994` | Esta etiqueta indica la dirección del procesamiento de nitidez aplicado por la cámara cuando se tomó la imagen. |
| DeviceSettingDescription | `41995` | Esta etiqueta indica información sobre las condiciones de toma de fotografías de un modelo de cámara en particular. |
| SubjectDistanceRange | `41996` | Esta etiqueta indica la distancia al sujeto. |
| CompositeImage | `42080` | Esta etiqueta indica si la imagen grabada es una imagen compuesta* o no. |
| SourceImageNumberOfCompositeImage | `42081` | Esta etiqueta indica el número de imágenes de origen (imágenes grabadas provisionalmente) capturadas para una imagen compuesta. |
| SourceExposureTimesOfCompositeImage | `42082` | Para una imagen compuesta, esta etiqueta registra los parámetros relacionados con el tiempo de exposición de las exposiciones para generar dicha imagen compuesta, como los respectivos tiempos de exposición de las imágenes fuente capturadas (imágenes grabadas tentativamente). |
| Temperature | `37888` | Temperatura como la situación ambiental en el momento de la toma, por ejemplo, la temperatura ambiente donde el fotógrafo sostenía la cámara. La unidad es °C. |
| Humidity | `37889` | Humedad como la situación ambiental en el momento de la toma, por ejemplo, la humedad de la habitación donde el fotógrafo sostenía la cámara. La unidad es %. |
| Pressure | `37890` | Presión como la situación ambiental en el momento de la toma, por ejemplo, la atmósfera de la habitación donde el fotógrafo sostenía la cámara o la presión del agua bajo el mar. La unidad es hPa. |
| WaterDepth | `37891` | Profundidad del agua como la situación ambiental en el momento de la toma, por ejemplo, la profundidad del agua de la cámara en la fotografía submarina. La unidad es m. |
| Acceleration | `37892` | Aceleración (un escalar independientemente de la dirección) como la situación ambiental en la toma, por ejemplo, la aceleración del vehículo en el que viajaba el fotógrafo en la toma. La unidad es mGal (10-5 m/s2). |
| CameraElevationAngle | `37893` | Elevación/depresión. ángulo de la orientación de la cámara (eje óptico de imagen) como la situación ambiental en el disparo. La unidad es grado(°). |
| ImageUniqueID | `42016` | Esta etiqueta indica un identificador asignado de forma única a cada imagen. |
| LensSpecification | `42034` | Esta etiqueta indica la distancia focal mínima, la distancia focal máxima, el número F mínimo en la distancia focal mínima, y el número F mínimo en la distancia focal máxima, que son información de especificaciones para la lente que se usó en la fotografía. |
| LensMake | `42035` | Esta etiqueta registra el fabricante de la lente como una cadena ASCII. |
| LensModel | `42036` | Esta etiqueta registra el nombre y el número de modelo de la lente como una cadena ASCII. |
| LensSerialNumber | `42037` | Esta etiqueta registra el número de serie de la lente intercambiable que se usó en fotografía como una cadena ASCII. |

### Ver también

* espacio de nombres [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
