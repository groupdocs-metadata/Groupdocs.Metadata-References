---
title: TiffTagID
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Définit les identifiants des balises TIFF.
type: docs
weight: 2100
url: /fr/net/groupdocs.metadata.formats.image/tifftagid/
---
## TiffTagID enumeration

Définit les identifiants des balises TIFF.

```csharp
public enum TiffTagID : ushort
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| GpsVersionID | `0` | Indique la version de GPSInfoIFD. |
| GpsLatitudeRef | `1` | Indique si la latitude est nord ou sud. |
| GpsLatitude | `2` | Indique la latitude. |
| GpsLongitudeRef | `3` | Indique si la longitude est est ou ouest. |
| GpsLongitude | `4` | Indique la longitude. |
| GpsAltitudeRef | `5` | Indique l'altitude utilisée comme altitude de référence. |
| GpsAltitude | `6` | Indique l'altitude basée sur la référence dans GPSAltitudeRef. |
| GpsTimeStamp | `7` | Indique l'heure en UTC (Coordinated Universal Time). |
| GpsSatellites | `8` | indique les satellites GPS utilisés pour les mesures. |
| GpsStatus | `9` | Indique l'état du récepteur GPS lorsque l'image est enregistrée. |
| GpsMeasureMode | `10` | Indique le mode de mesure GPS. |
| GpsDop | `11` | Indique le DOP GPS (degré de précision des données). |
| GpsSpeedRef | `12` | Indique l'unité utilisée pour exprimer la vitesse de déplacement du récepteur GPS |
| GpsSpeed | `13` | Indique la vitesse de déplacement du récepteur GPS. |
| GpsTrackRef | `14` | Indique la référence pour donner le sens de déplacement du récepteur GPS. |
| GpsTrack | `15` | Indique la direction du mouvement du récepteur GPS. |
| GpsImgDirectionRef | `16` | Indique la référence pour donner la direction de l'image lors de sa capture. |
| GpsImgDirection | `17` | Indique la direction de l'image lors de sa capture. |
| GpsMapDatum | `18` | Indique les données de relevé géodésique utilisées par le récepteur GPS. |
| GpsDestLatitudeRef | `19` | Indique si la latitude du point de destination est la latitude nord ou sud. |
| GpsDestLatitude | `20` | Indique la latitude du point de destination. |
| GpsDestLongitudeRef | `21` | Indique si la longitude du point de destination est la longitude est ou ouest. |
| GpsDestLongitude | `22` | Indique la longitude du point de destination. |
| GpsDestBearingRef | `23` | Indique la référence utilisée pour donner le relèvement au point de destination. |
| GpsDestBearing | `24` | Indique le relèvement vers le point de destination. |
| GpsDestDistanceRef | `25` | Indique l'unité utilisée pour exprimer la distance jusqu'au point de destination. |
| GpsDestDistance | `26` | Indique la distance jusqu'au point de destination. |
| GpsProcessingMethod | `27` | Une chaîne de caractères enregistrant le nom de la méthode utilisée pour la localisation. |
| GpsAreaInformation | `28` | Une chaîne de caractères enregistrant le nom de la zone GPS. |
| GpsDateStamp | `29` | Une chaîne de caractères enregistrant les informations de date et d'heure relatives à l'UTC (Coordinated Universal Time). |
| GpsDifferential | `30` | Indique si la correction différentielle est appliquée au récepteur GPS. |
| GpsHPositioningError | `31` | Cette balise indique les erreurs de positionnement horizontal en mètres. |
| NewSubfileType | `254` | Une indication générale du type de données contenues dans ce sous-fichier. |
| SubfileType | `255` | Une indication générale du type de données contenues dans ce sous-fichier. Ce champ est obsolète. Le champ NewSubfileType doit être utilisé à la place |
| ImageWidth | `256` | Le nombre de colonnes dans l'image, c'est-à-dire le nombre de pixels par ligne de balayage. |
| ImageLength | `257` | Le nombre de lignes (parfois décrites comme des lignes de balayage) dans l'image. |
| BitsPerSample | `258` | Nombre de bits par composant. |
| Compression | `259` | Schéma de compression utilisé sur les données d'image. |
| PhotometricInterpretation | `262` | L'espace colorimétrique des données d'image. |
| Threshholding | `263` | Pour les fichiers TIFF noir et blanc qui représentent des nuances de gris, la technique utilisée pour convertir les pixels gris en pixels noir et blanc. |
| CellWidth | `264` | La largeur de la matrice de tramage ou de demi-teinte utilisée pour créer un fichier bi-niveau tramé ou en demi-teinte. |
| CellLength | `265` | La longueur de la matrice de tramage ou de demi-teinte utilisée pour créer un fichier bi-niveau tramé ou en demi-teinte. |
| FillOrder | `266` | L'ordre logique des bits dans un octet. |
| DocumentName | `269` | Le nom du document à partir duquel cette image a été numérisée. |
| ImageDescription | `270` | Une chaîne qui décrit le sujet de l'image. |
| Make | `271` | Le fabricant du scanner. |
| Model | `272` | Le nom ou le numéro de modèle du scanner. |
| StripOffsets | `273` | Pour chaque bande, le décalage d'octet de cette bande. |
| Orientation | `274` | L'orientation de l'image par rapport aux lignes et aux colonnes. |
| SamplesPerPixel | `277` | Le nombre de composants par pixel. |
| RowsPerStrip | `278` | Le nombre de rangées par bande. |
| StripByteCounts | `279` | Pour chaque bande, le nombre d'octets dans la bande après compression. |
| MinSampleValue | `280` | La valeur minimale du composant utilisé. |
| MaxSampleValue | `281` | La valeur maximale du composant utilisé. |
| XResolution | `282` | Le nombre de pixels par ResolutionUnit dans la direction ImageWidth. |
| YResolution | `283` | Le nombre de pixels par ResolutionUnit dans la direction ImageLength. |
| PlanarConfiguration | `284` | Comment les composants de chaque pixel sont stockés. |
| PageName | `285` | Le nom de la page à partir de laquelle cette image a été numérisée. |
| XPosition | `286` | Position X de l'image. |
| YPosition | `287` | Position Y de l'image. |
| FreeOffsets | `288` | Pour chaque chaîne d'octets inutilisés contigus dans un fichier TIFF, le décalage d'octet de la chaîne. |
| FreeByteCounts | `289` | Pour chaque chaîne d'octets inutilisés contigus dans un fichier TIFF, le nombre d'octets dans la chaîne. |
| GrayResponseUnit | `290` | La précision des informations contenues dans la GrayResponseCurve. |
| GrayResponseCurve | `291` | Pour les données en niveaux de gris, la densité optique de chaque valeur de pixel possible. |
| T4Options | `292` | Options d'encodage T4. |
| T6Options | `293` | Options d'encodage T6. |
| ResolutionUnit | `296` | L'unité de mesure pour XResolution et YResolution. |
| PageNumber | `297` | Le numéro de page de la page à partir de laquelle cette image a été numérisée. |
| TransferFunction | `301` | Décrit une fonction de transfert pour l'image dans un style tabulaire. Les composants de pixels peuvent être compensés en gamma, compressés, quantifiés de manière non uniforme ou codés d'une autre manière. La TransferFunction mappe les composants de pixels d'une forme non linéaire BitsPerSample (par exemple 8 bits) en une forme linéaire 16 bits sans perte perceptible de précision. |
| Software | `305` | Nom et numéro de version du ou des progiciels utilisés pour créer l'image. |
| DateTime | `306` | Date et heure de création de l'image. |
| Artist | `315` | Personne qui a créé l'image. |
| HostComputer | `316` | L'ordinateur et/ou le système d'exploitation utilisé au moment de la création de l'image. |
| Predictor | `317` | Cette section définit un prédicteur qui améliore considérablement les taux de compression de certaines images. |
| WhitePoint | `318` | La chromaticité du point blanc de l'image. |
| PrimaryChromaticities | `319` | Les chromaticités des primaires de l'image. |
| ColorMap | `320` | Une carte de couleurs pour les images de couleurs de palette. |
| HalftoneHints | `321` | L'objectif du champ HalftoneHints est de transmettre à la fonction de demi-teinte la plage de niveaux de gris dans une image colorimétriquement spécifiée qui doit conserver les détails tonals. |
| TileWidth | `322` | La largeur de tuile en pixels. Il s'agit du nombre de colonnes dans chaque tuile. |
| TileLength | `323` | La longueur (hauteur) de la tuile en pixels. Il s'agit du nombre de lignes dans chaque tuile. |
| TileOffsets | `324` | Pour chaque tuile, le décalage d'octet de cette tuile, tel qu'il est compressé et stocké sur le disque. Le décalage est spécifié par rapport au début du fichier TIFF. Notez que cela implique que chaque tuile a un emplacement indépendant des emplacements des autres tuiles. |
| TileByteCounts | `325` | Pour chaque tuile, le nombre d'octets (compressés) dans cette tuile. |
| InkSet | `332` | L'ensemble des encres utilisées dans une image séparée (PhotometricInterpretation=5). |
| InkNames | `333` | Le nom de chaque encre utilisée dans une image séparée (PhotometricInterpretation=5), écrit sous la forme d'une liste de chaînes ASCII concaténées terminées par NUL. |
| NumberOfInks | `334` | Le nombre d'encres. Généralement égal à SamplesPerPixel, sauf s'il y a des échantillons supplémentaires. |
| DotRange | `336` | Les valeurs des composants qui correspondent à un point de 0 % et à un point de 100 %. DotRange[0] correspond à un point de 0 % et DotRange[1] correspond à un point de 100 %. |
| ExtraSamples | `338` | Description des composants supplémentaires. |
| SampleFormat | `339` | Ce champ spécifie comment interpréter chaque échantillon de données dans un pixel. |
| SMinSampleValue | `340` | Ce champ spécifie la valeur minimale de l'échantillon. |
| SMaxSampleValue | `341` | Ce nouveau champ spécifie la valeur maximale de l'échantillon. |
| TransferRange | `342` | Étend la plage de TransferFunction. |
| JpegProc | `512` | Ce champ indique le processus JPEG utilisé pour produire les données compressées. |
| JpegInterchangeFormat | `513` | Ce champ indique si un flux binaire au format d'échange JPEG est présent dans le fichier TIFF. |
| JpegInterchangeFormatLength | `514` | Ce champ indique la longueur en octets du format d'échange JPEG bitstream |
| JpegRestartInterval | `515` | Ce champ indique la longueur de l'intervalle de redémarrage utilisé dans les données d'image compressées. |
| JpegLosslessPredictors | `517` | Ce champ pointe vers une liste de valeurs de sélection de prédicteur sans perte, une par composant. |
| JpegPointTransforms | `518` | Ce champ pointe vers une liste de valeurs de transformation ponctuelle, une par composant. |
| JpegQTables | `519` | Ce champ pointe vers une liste de décalages vers les tables de quantification, un par composant. |
| JpegDCTables | `520` | Ce champ pointe vers une liste de décalages vers les tables DC Huffman ou les tables lossless Huffman, une par composant. |
| JpegACTables | `521` | Ce champ pointe vers une liste de décalages vers les tables Huffman AC, un par composant. |
| YCbCrCoefficients | `529` | Coefficients de matrice pour la transformation des données d'image RVB en YCbCr. |
| YCbCrSubSampling | `530` | Le taux d'échantillonnage des composantes de chrominance par rapport à la composante de luminance. |
| YCbCrPositioning | `531` | Spécifie le positionnement des composants de chrominance sous-échantillonnés par rapport aux échantillons de luminance. |
| ReferenceBlackWhite | `532` | Spécifie une paire de valeurs de données d'image de marge et de marge (codes) pour chaque composant de pixel. |
| Copyright | `33432` | Avis de droit d'auteur. |
| UserComment | `37510` | Mots clés ou commentaires sur l'image ; complète ImageDescription. |
| Xmp | `700` | Pointeur vers les métadonnées XMP. |
| ImageID | `32781` | lié à l'OPI. |
| Iptc | `33723` | Métadonnées IPTC (International Press Telecommunications Council). Souvent, le type de données est incorrectement spécifié comme LONG. |
| Photoshop | `34377` | Collection de "blocs de ressources d'image" de Photoshop. |
| ImageLayer | `34732` | Couche d'image. |
| IccProfile | `34675` | Données de profil de couleur. |
| ExifIfd | `34665` | Pointeur vers la collection de toutes les métadonnées EXIF. EXIF utilise des noms de champ plutôt que des balises pour indiquer le contenu du champ. |
| GpsIfd | `34853` | Pointeur vers les données GPS. |
| Makernotes | `37500` | Pointeur vers les données des notes de marque. |
| InteroperabilityIfd | `40965` | IFD d'interopérabilité liée à Exif. |
| CameraOwnerName | `42032` | Nom du propriétaire de la caméra sous forme de chaîne ASCII. |
| BodySerialNumber | `42033` | Numéro de série du boîtier de l'appareil photo sous forme de chaîne ASCII. |
| CfaPattern | `41730` | indique le motif géométrique du réseau de filtres de couleur (CFA) du capteur d'image lorsqu'un capteur de zone de couleur à une puce est utilisé. Cela ne s'applique pas à toutes les méthodes de détection. |
| ExifVersion | `36864` | La version de la norme EXIF prise en charge. |
| ComponentsConfiguration | `37121` | Informations spécifiques aux données compressées. Les canaux de chaque composant sont disposés dans l'ordre du 1er composant au 4ème. |
| FlashpixVersion | `40960` | La version du format Flashpix prise en charge par un fichier FPXR. Si la fonction FPXR prend en charge le format Flashpix Ver. 1.0, cela est indiqué de la même manière qu'ExifVersion en enregistrant "0100" en ASCII de 4 octets. |
| ColorSpace | `40961` | La balise d'informations sur l'espace colorimétrique (ColorSpace) est toujours enregistrée en tant que spécificateur d'espace colorimétrique. Normalement, sRGB (=1) est utilisé pour définir l'espace colorimétrique en fonction des conditions et de l'environnement du moniteur du PC. Si un espace colorimétrique autre que sRGB est utilisé, Non calibré (=FFFF.H) est défini. |
| PixelXDimension | `40962` | Informations spécifiques aux données compressées. Lorsqu'un fichier compressé est enregistré, la largeur valide de l'image significative doit être enregistrée dans cette balise, qu'il y ait ou non des données de remplissage ou un marqueur de redémarrage. |
| PixelYDimension | `40963` | Informations spécifiques aux données compressées. Lorsqu'un fichier compressé est enregistré, la hauteur valide de l'image significative doit être enregistrée dans cette balise, qu'il y ait ou non des données de remplissage ou un marqueur de redémarrage. |
| SceneCaptureType | `41990` | Cette balise indique le type de scène qui a été tourné. Il peut également être utilisé pour enregistrer le mode dans lequel l'image a été prise. |
| Gamma | `42240` | Indique la valeur du coefficient gamma. |
| CompressedBitsPerPixel | `37122` | Informations spécifiques aux données compressées. Le mode de compression utilisé pour une image compressée est indiqué en unités de bits par pixel. |
| RelatedSoundFile | `40964` | Cette balise est utilisée pour enregistrer le nom d'un fichier audio lié aux données d'image. La seule information relationnelle enregistrée ici est le nom et l'extension du fichier audio Exif (une chaîne ASCII composée de 8 caractères + '.' + 3 caractères). |
| DateTimeOriginal | `36867` | La date et l'heure auxquelles les données d'image d'origine ont été générées. Pour un DSC, la date et l'heure de la prise de vue sont enregistrées. Le format est "AAAA:MM:JJ HH:MM:SS" avec l'heure affichée au format 24 heures et la date et l'heure séparées par un caractère blanc. |
| DateTimeDigitized | `36868` | La date et l'heure auxquelles l'image a été stockée sous forme de données numériques. Si, par exemple, une image a été capturée par DSC et en même temps le fichier a été enregistré, alors DateTimeOriginal et DateTimeDigitized auront le même contenu. Le format est "AAAA:MM:JJ HH:MM:SS" avec l'heure affichée au format 24 heures et la date et l'heure séparées par un caractère blanc. |
| OffsetTime | `36880` | Une balise utilisée pour enregistrer le décalage par rapport à UTC (la différence d'heure par rapport au temps universel coordonné, y compris l'heure d'été) de l'heure de la balise DateTime. Le format lors de l'enregistrement du décalage est "±HH:MM". La partie de "±" doit être enregistrée sous la forme "+" ou "-". |
| OffsetTimeOriginal | `36881` | Une balise utilisée pour enregistrer le décalage par rapport à UTC (la différence d'heure par rapport au temps universel coordonné, y compris l'heure d'été) de l'heure de la balise DateTimeOriginal. Le format lors de l'enregistrement du décalage est "±HH:MM". La partie de "±" doit être enregistrée sous la forme "+" ou "-". |
| OffsetTimeDigitized | `36882` | Une balise utilisée pour enregistrer le décalage par rapport à UTC (la différence d'heure par rapport au temps universel coordonné, y compris l'heure d'été) de l'heure de la balise DateTimeDigitized. Le format lors de l'enregistrement du décalage est "±HH:MM". La partie de "±" doit être enregistrée sous la forme "+" ou "-". |
| SubsecTime | `37520` | Une balise utilisée pour enregistrer des fractions de secondes pour la balise DateTime. |
| SubsecTimeOriginal | `37521` | Une balise utilisée pour enregistrer des fractions de secondes pour la balise DateTimeOriginal. |
| SubsecTimeDigitized | `37522` | Une balise utilisée pour enregistrer des fractions de secondes pour la balise DateTimeDigitized. |
| ExposureTime | `33434` | Temps d'exposition, exprimé en secondes (sec). |
| FNumber | `33437` | Le nombre F. |
| ExposureProgram | `34850` | La classe du programme utilisé par l'appareil photo pour régler l'exposition lorsque la photo est prise. |
| SpectralSensitivity | `34852` | Indique la sensibilité spectrale de chaque canal de la caméra utilisée. La valeur du tag est une chaîne ASCII compatible avec la norme développée par le comité technique ASTM. |
| PhotographicSensitivity | `34855` | Cette balise indique la sensibilité de la caméra ou du périphérique d'entrée lorsque l'image a été prise. |
| Oecf | `34856` | Indique la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524. OECF est la relation entre l'entrée optique de la caméra et les valeurs de l'image. |
| SensitivityType | `34864` | La balise SensitivityType indique lequel des paramètres de la norme ISO12232 est la balise PhotographicSensitivity. Bien qu'il s'agisse d'une balise facultative, elle doit être enregistrée lorsqu'une balise PhotographicSensitivity est enregistrée. |
| StandardOutputSensitivity | `34865` | Cette balise indique la valeur de sensibilité de sortie standard d'une caméra ou d'un périphérique d'entrée définie dans la norme ISO 12232. Lors de l'enregistrement de cette balise, les balises PhotographicSensitivity et SensitivityType doivent également être enregistrées. |
| RecommendedExposureIndex | `34866` | Cette balise indique la valeur d'indice d'exposition recommandée d'un appareil photo ou d'un périphérique d'entrée défini dans la norme ISO 12232. Lors de l'enregistrement de cette balise, les balises PhotographicSensitivity et SensitivityType doivent également être enregistrées. |
| IsoSpeed | `34867` | Cette balise indique la valeur de vitesse ISO d'une caméra ou d'un périphérique d'entrée qui est définie dans la norme ISO 12232. Lors de l'enregistrement de cette balise, les balises PhotographicSensitivity et SensitivityType doivent également être enregistrées. |
| ISOSpeedLatitudeYyy | `34868` | Cette balise indique la valeur de latitude de vitesse ISO yyy d'une caméra ou d'un périphérique d'entrée définie dans la norme ISO 12232. |
| ISOSpeedLatitudeZzz | `34869` | Cette balise indique la valeur de latitude de vitesse ISO zzz d'une caméra ou d'un périphérique d'entrée définie dans la norme ISO 12232. |
| ShutterSpeedValue | `37377` | Vitesse d'obturation. L'unité est le réglage APEX (Additive System of Photographic Exposure). |
| ApertureValue | `37378` | L'ouverture de l'objectif. L'unité est la valeur APEX. |
| BrightnessValue | `37379` | La valeur de luminosité. L'unité est la valeur APEX. |
| ExposureBiasValue | `37380` | Le biais d'exposition. L'unité est la valeur APEX. |
| MaxApertureValue | `37381` | Le plus petit nombre F de l'objectif. L'unité est la valeur APEX. |
| SubjectDistance | `37382` | La distance au sujet, donnée en mètres. |
| MeteringMode | `37383` | Le mode de mesure. |
| LightSource | `37384` | Le type de source lumineuse. |
| Flash | `37385` | Cette balise indique l'état du flash lorsque l'image a été prise. Le bit 0 indique l'état de déclenchement du flash, les bits 1 et 2 indiquent l'état de retour du flash, les bits 3 et 4 indiquent le mode flash, le bit 5 indique si la fonction flash est présente et le bit 6 indique le mode "yeux rouges". |
| SubjectArea | `37396` | Cette balise indique l'emplacement et la zone du sujet principal dans la scène globale. |
| FocalLength | `37386` | La distance focale réelle de l'objectif, en mm. La conversion n'est pas faite à la distance focale d'un appareil photo argentique 35 mm. |
| FlashEnergy | `41483` | Indique l'énergie stroboscopique au moment de la capture de l'image, mesurée en secondes de puissance de bougie de faisceau (BCPS). |
| SpatialFrequencyResponse | `41484` | Cette balise enregistre la table de fréquences spatiales de la caméra ou du périphérique d'entrée et les valeurs SFR dans le sens de la largeur de l'image, la hauteur de l'image et la direction diagonale, comme spécifié dans la norme ISO 12233. |
| FocalPlaneXResolution | `41486` | Indique le nombre de pixels dans la direction de la largeur de l'image (X) par FocalPlaneResolutionUnit sur le plan focal de la caméra. |
| FocalPlaneYResolution | `41487` | Indique le nombre de pixels dans la direction de la hauteur de l'image (Y) par FocalPlaneResolutionUnit sur le plan focal de la caméra. |
| FocalPlaneResolutionUnit | `41488` | Indique l'unité de mesure de FocalPlaneXResolution et FocalPlaneYResolution. Cette valeur est identique à ResolutionUnit. |
| SubjectLocation | `41492` | Indique l'emplacement du sujet principal dans la scène. La valeur de cette balise représente le pixel au centre du sujet principal par rapport au bord gauche, avant le traitement de rotation conformément à la balise Rotation. La première valeur indique le numéro de colonne X et la seconde indique le numéro de ligne Y. |
| ExposureIndex | `41493` | Indique l'indice d'exposition sélectionné sur l'appareil photo ou le périphérique d'entrée au moment où l'image est capturée. |
| SensingMethod | `41495` | Indique le type de capteur d'image sur la caméra ou le périphérique d'entrée. |
| FileSource | `41728` | Indique la source de l'image. Si un DSC a enregistré l'image, cette valeur de balise doit toujours être définie sur 3. |
| SceneType | `41729` | Indique le type de scène. Si un DSC a enregistré l'image, cette valeur de balise doit toujours être définie sur 1, indiquant que l'image a été directement photographiée. |
| CustomRendered | `41985` | Cette balise indique l'utilisation d'un traitement spécial sur les données d'image, comme le rendu adapté à la sortie. |
| ExposureMode | `41986` | Cette balise indique le mode d'exposition défini lors de la prise de vue. En mode de bracketing automatique, l'appareil photo prend une série d'images de la même scène avec différents réglages d'exposition. |
| WhiteBalance | `41987` | Cette balise indique le mode de balance des blancs défini lors de la prise de vue. |
| DigitalZoomRatio | `41988` | Cette balise indique le taux de zoom numérique lorsque l'image a été prise. Si le numérateur de la valeur enregistrée est 0, cela indique que le zoom numérique n'a pas été utilisé. |
| FocalLengthIn35mmFilm | `41989` | Cette étiquette indique la distance focale équivalente en supposant un appareil photo argentique 35 mm, en mm. Une valeur de 0 signifie que la distance focale est inconnue. Notez que cette balise diffère de la balise FocalLength. |
| GainControl | `41991` | Cette balise indique le degré d'ajustement global du gain d'image. |
| Contrast | `41992` | Cette balise indique la direction du traitement du contraste appliqué par l'appareil photo lors de la prise de vue. |
| Saturation | `41993` | Cette balise indique le sens du traitement de saturation appliqué par la caméra lors de la prise de vue. |
| Sharpness | `41994` | Cette balise indique le sens du traitement de la netteté appliqué par l'appareil photo lors de la prise de vue. |
| DeviceSettingDescription | `41995` | Cette balise indique des informations sur les conditions de prise de vue d'un modèle d'appareil photo particulier. |
| SubjectDistanceRange | `41996` | Cette balise indique la distance au sujet. |
| CompositeImage | `42080` | Cette balise indique si l'image enregistrée est une image composite* ou non. |
| SourceImageNumberOfCompositeImage | `42081` | Cette balise indique le nombre d'images source (images provisoirement enregistrées) capturées pour une image composite. |
| SourceExposureTimesOfCompositeImage | `42082` | Pour une image composite, cette étiquette enregistre les paramètres relatifs au temps d'exposition des poses pour générer ladite image composite, tels que les temps d'exposition respectifs des images sources capturées (images provisoirement enregistrées). |
| Temperature | `37888` | Température comme situation ambiante au moment de la prise de vue, par exemple la température de la pièce où le photographe tenait l'appareil photo. L'unité est le °C. |
| Humidity | `37889` | Humidité comme situation ambiante au moment de la prise de vue, par exemple l'humidité de la pièce où le photographe tenait l'appareil photo. L'unité est %. |
| Pressure | `37890` | Pression comme situation ambiante au moment de la prise de vue, par exemple l'atmosphère de la pièce où le photographe tenait l'appareil photo ou la pression de l'eau sous la mer. L'unité est hPa. |
| WaterDepth | `37891` | Profondeur de l'eau comme situation ambiante au moment de la prise de vue, par exemple la profondeur de l'eau de l'appareil photo lors de la photographie sous-marine. L'unité est m. |
| Acceleration | `37892` | Accélération (un scalaire quelle que soit la direction) en tant que situation ambiante au moment de la prise de vue, par exemple l'accélération de conduite du véhicule sur lequel le photographe a roulé lors de la prise de vue. L'unité est mGal (10-5 m/s2). |
| CameraElevationAngle | `37893` | Élévation/dépression. angle d'orientation de la caméra (axe optique d'imagerie) en fonction de la situation ambiante au moment de la prise de vue. L'unité est le degré(°). |
| ImageUniqueID | `42016` | Cette balise indique un identifiant attribué de manière unique à chaque image. |
| LensSpecification | `42034` | Cette balise indique la distance focale minimale, la distance focale maximale, le nombre F minimum dans la distance focale minimale, et le nombre F minimum dans la distance focale maximale, qui sont des informations de spécification pour l'objectif utilisé en photographie. |
| LensMake | `42035` | Cette balise enregistre le fabricant de l'objectif sous forme de chaîne ASCII. |
| LensModel | `42036` | Cette balise enregistre le nom et le numéro de modèle de l'objectif sous forme de chaîne ASCII. |
| LensSerialNumber | `42037` | Cette balise enregistre le numéro de série de l'objectif interchangeable utilisé en photographie sous forme de chaîne ASCII. |

### Voir également

* espace de noms [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
