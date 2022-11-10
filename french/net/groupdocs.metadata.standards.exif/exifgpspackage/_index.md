---
title: ExifGpsPackage
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Représente les métadonnées GPS dans un package de métadonnées EXIF.
type: docs
weight: 2770
url: /fr/net/groupdocs.metadata.standards.exif/exifgpspackage/
---
## ExifGpsPackage class

Représente les métadonnées GPS dans un package de métadonnées EXIF.

```csharp
public sealed class ExifGpsPackage : ExifDictionaryBasePackage
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ExifGpsPackage](exifgpspackage)() | Initialise une nouvelle instance du[`ExifGpsPackage`](../exifgpspackage) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Altitude](../../groupdocs.metadata.standards.exif/exifgpspackage/altitude) { get; set; } | Obtient ou définit l'altitude en fonction de la référence dans[`AltitudeRef`](./altituderef) . L'unité de référence est le mètre. |
| [AltitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/altituderef) { get; set; } | Obtient ou définit l'altitude utilisée comme altitude de référence. Si la référence est le niveau de la mer et que l'altitude est au-dessus du niveau de la mer, 0 est donné. Si l'altitude est en dessous du niveau de la mer, la valeur 1 est donnée et l'altitude est indiquée en valeur absolue dans le[`Altitude`](./altitude) balise. |
| [AreaInformation](../../groupdocs.metadata.standards.exif/exifgpspackage/areainformation) { get; set; } | Obtient ou définit la chaîne de caractères enregistrant le nom de la zone GPS. Le premier octet indique le code de caractère utilisé, suivi du nom de la zone GPS. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtient le nombre de propriétés de métadonnées. |
| [DataDegreeOfPrecision](../../groupdocs.metadata.standards.exif/exifgpspackage/datadegreeofprecision) { get; set; } | Obtient ou définit le DOP GPS (degré de précision des données). Une valeur HDOP est écrite lors d'une mesure bidimensionnelle et PDOP lors d'une mesure tridimensionnelle. |
| [DateStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/datestamp) { get; set; } | Obtient ou définit la chaîne de caractères enregistrant les informations de date et d'heure relatives à l'UTC (Coordinated Universal Time). Le format est AAAA:MM:JJ. |
| [DestBearing](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearing) { get; set; } | Obtient ou définit le relèvement GPS vers le point de destination. La plage de valeurs est comprise entre 0,00 et 359,99. |
| [DestBearingRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearingref) { get; set; } | Obtient ou définit la référence GPS utilisée pour donner le relèvement au point de destination. 'T' indique la vraie direction et 'M' est la direction magnétique. |
| [DestDistance](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistance) { get; set; } | Obtient ou définit la distance GPS jusqu'au point de destination. |
| [DestDistanceRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistanceref) { get; set; } | Obtient ou définit l'unité GPS utilisée pour exprimer la distance jusqu'au point de destination. 'K', 'M' et 'N' représentent les kilomètres, les miles et les nœuds. |
| [DestLatitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatitude) { get; set; } | Obtient ou définit la latitude GPS du point de destination. |
| [DestLatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatituderef) { get; set; } | Obtient ou définit la valeur GPS qui indique si la latitude du point de destination est la latitude nord ou sud. La valeur ASCII "N" indique la latitude nord et "S" la latitude sud. |
| [DestLongitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongitude) { get; set; } | Obtient ou définit la longitude GPS du point de destination. |
| [DestLongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongituderef) { get; set; } | Obtient ou définit la valeur GPS qui indique si la longitude du point de destination est la longitude est ou ouest. ASCII 'E' indique la longitude est et 'W' est la longitude ouest. |
| [Differential](../../groupdocs.metadata.standards.exif/exifgpspackage/differential) { get; set; } | Obtient ou définit une valeur GPS qui indique si une correction différentielle est appliquée au récepteur GPS. |
| [GpsTrack](../../groupdocs.metadata.standards.exif/exifgpspackage/gpstrack) { get; set; } | Obtient ou définit la direction du mouvement du récepteur GPS. |
| [ImgDirection](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirection) { get; set; } | Obtient ou définit la direction GPS de l'image lors de sa capture. La plage de valeurs est comprise entre 0,00 et 359,99. |
| [ImgDirectionRef](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirectionref) { get; set; } | Obtient ou définit la référence GPS pour donner la direction de l'image lorsqu'elle est capturée. 'T' indique la vraie direction et 'M' est la direction magnétique. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Obtient la balise TIFF avec l'identifiant spécifié. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtient une collection des noms de propriétés de métadonnées. |
| [Latitude](../../groupdocs.metadata.standards.exif/exifgpspackage/latitude) { get; set; } | Obtient ou définit la latitude GPS. |
| [LatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/latituderef) { get; set; } | Obtient ou définit une valeur GPS indiquant si la latitude est nord ou sud. |
| [Longitude](../../groupdocs.metadata.standards.exif/exifgpspackage/longitude) { get; set; } | Obtient ou définit la longitude GPS. |
| [LongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/longituderef) { get; set; } | Obtient ou définit une valeur GPS indiquant si la longitude est est ou ouest. |
| [MapDatum](../../groupdocs.metadata.standards.exif/exifgpspackage/mapdatum) { get; set; } | Obtient ou définit les données de relevé géodésique utilisées par le récepteur GPS. |
| [MeasureMode](../../groupdocs.metadata.standards.exif/exifgpspackage/measuremode) { get; set; } | Obtient ou définit le mode de mesure GPS. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtient le type de métadonnées. |
| [ProcessingMethod](../../groupdocs.metadata.standards.exif/exifgpspackage/processingmethod) { get; set; } | Obtient ou définit une chaîne de caractères enregistrant le nom de la méthode utilisée pour la localisation. Le premier octet indique le code de caractère utilisé, suivi du nom de la méthode. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtient une collection de descripteurs contenant des informations sur les propriétés accessibles via le moteur de recherche GroupDocs.Metadata. |
| [Satellites](../../groupdocs.metadata.standards.exif/exifgpspackage/satellites) { get; set; } | Obtient ou définit les satellites GPS utilisés pour les mesures. Cette balise peut être utilisée pour décrire le nombre de satellites, leur numéro d'identification, l'angle d'élévation, l'azimut, le SNR et d'autres informations en notation ASCII. Le format n'est pas spécifié. Si le récepteur GPS est incapable de prendre des mesures, la valeur de la balise doit être définie sur NULL. |
| [Speed](../../groupdocs.metadata.standards.exif/exifgpspackage/speed) { get; set; } | Obtient ou définit la vitesse de déplacement du récepteur GPS. |
| [SpeedRef](../../groupdocs.metadata.standards.exif/exifgpspackage/speedref) { get; set; } | Obtient ou définit l'unité utilisée pour exprimer la vitesse de déplacement du récepteur GPS. 'K' 'M' et 'N' représentent les kilomètres par heure, les miles par heure et les nœuds. |
| [Status](../../groupdocs.metadata.standards.exif/exifgpspackage/status) { get; set; } | Obtient ou définit l'état du récepteur GPS lorsque l'image est enregistrée. |
| [TimeStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/timestamp) { get; set; } | Obtient ou définit l'heure au format UTC (Coordinated Universal Time). TimeStamp est exprimé sous la forme de trois valeurs RATIONAL indiquant l'heure, la minute et la seconde. |
| [TrackRef](../../groupdocs.metadata.standards.exif/exifgpspackage/trackref) { get; set; } | Obtient ou définit la référence pour donner la direction du mouvement du récepteur GPS. 'T' indique la vraie direction et 'M' est la direction magnétique. |
| [VersionID](../../groupdocs.metadata.standards.exif/exifgpspackage/versionid) { get; set; } | Obtient ou définit la version du GPS IFD. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ajoute des propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Supprime toutes les balises TIFF stockées dans le package. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Détermine si le package contient une propriété de métadonnées avec le nom spécifié. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trouve les propriétés de métadonnées satisfaisant le prédicat spécifié. La recherche est récursive, elle affecte donc également tous les packages imbriqués. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Supprime la propriété avec l'identifiant spécifié. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Supprime les propriétés de métadonnées satisfaisant le prédicat spécifié. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Supprime les propriétés de métadonnées inscriptibles du package. L'opération est récursive, elle affecte donc également tous les packages imbriqués. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Ajoute ou remplace la balise spécifiée. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Définit les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. Cette méthode est une combinaison de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) et[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si une propriété existante satisfait le prédicat, sa valeur est mise à jour. S'il manque une propriété connue dans le package qui satisfait le prédicat, elle est ajoutée au package. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Crée une liste à partir du package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Met à jour les propriétés de métadonnées connues satisfaisant le prédicat spécifié. L'opération est récursive et affecte donc également tous les packages imbriqués. |

### Remarques

**Apprendre encore plus**

* [Travailler avec les métadonnées EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Voir également

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* espace de noms [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
