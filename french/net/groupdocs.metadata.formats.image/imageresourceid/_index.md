---
title: ImageResourceID
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Numéros didentification standard des ressources dimage. Tous les formats de fichiers nutilisent pas tous les identifiants. Certaines informations peuvent être stockées dans dautres sections du fichier.
type: docs
weight: 1750
url: /fr/net/groupdocs.metadata.formats.image/imageresourceid/
---
## ImageResourceID enumeration

Numéros d'identification standard des ressources d'image. Tous les formats de fichiers n'utilisent pas tous les identifiants. Certaines informations peuvent être stockées dans d'autres sections du fichier.

```csharp
public enum ImageResourceID
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| ResolutionInfo | `1005` | structure ResolutionInfo. Voir l'annexe A dans le document PDF du guide de l'API Photoshop. |
| NamesOfAlphaChannels | `1006` | Noms des canaux alpha sous la forme d'une série de chaînes Pascal. |
| Caption | `1008` | La légende sous forme de chaîne Pascal. |
| BorderInformation | `1009` | Informations sur les frontières. Contient un nombre fixe (2 octets réels, 2 octets fraction) pour la largeur de la bordure, et 2 octets pour les unités de bordure (1 = pouces, 2 = cm, 3 = points, 4 = picas, 5 = colonnes). |
| BackgroundColor | `1010` | Couleur de fond. [Voir plus.](http://www.adobe.com/devnet-apps/photoshop/fileformatashtml/#50577411_31265) |
| PrintFlags | `1011` | Imprimer des drapeaux. Une série de valeurs booléennes d'un octet (voir la boîte de dialogue Mise en page) : étiquettes, repères de coupe, barres de couleur, marques de repérage, négatif, retournement, interpolation, légende, indicateurs d'impression. |
| Grayscale | `1012` | Informations sur les niveaux de gris et les demi-teintes multicanaux. |
| ColorHalftoning | `1013` | Informations sur les demi-teintes des couleurs. |
| DuotoneHalftoning | `1014` | Informations sur les demi-teintes bicolores. |
| GrayscaleFunction | `1015` | Niveaux de gris et fonction de transfert multicanal. |
| ColorTransferFunctions | `1016` | Fonctions de transfert de couleur. |
| DuotoneTransferFunctions | `1017` | Fonctions de transfert Duotone. |
| DuotoneImageInformation | `1018` | Informations sur l'image en bichromie. |
| EPSOptions | `1021` | Options EPS. |
| QuickMaskInformation | `1022` | Informations sur le masque rapide. 2 octets contenant l'ID de canal de masque rapide ; 1- octet booléen indiquant si le masque était initialement vide. |
| LayerStateInformation | `1024` | Informations sur l'état de la couche. 2 octets contenant l'index de la couche cible (0 = couche inférieure). |
| WorkingPath | `1025` | Chemin de travail (non enregistré). Voir Voir format de ressource de chemin. |
| LayersGroupInformation | `1026` | Informations sur le groupe de calques. 2 octets par couche contenant un ID de groupe pour les groupes de déplacement. Les calques d'un groupe ont le même ID de groupe. |
| Iptc | `1028` | Enregistrement IPTC-NAA. Contient les informations sur le fichier... Voir la documentation dans le dossier IPTC du dossier Documentation. |
| ImageModeForRawFormat | `1029` | Mode image pour les fichiers au format brut. |
| JpegQuality | `1030` | Qualité JPEG. Privé. |
| GridAndGuidesInfoPhotoshop4 | `1032` | Informations sur la grille et les guides. |
| ThumbnailResourcePhotoshop4 | `1033` | Ressource miniature pour Photoshop 4.0 uniquement. |
| CopyrightFlagPhotoshop4 | `1034` | Indicateur de droit d'auteur. Booléen indiquant si l'image est protégée par le droit d'auteur. Peut être défini via Property suite ou par l'utilisateur dans File Info... |
| UrlPhotoshop4 | `1035` | URL. Descripteur d'une chaîne de texte avec localisateur de ressource uniforme. Peut être défini via Property suite ou par l'utilisateur dans File Info... |
| ThumbnailResourcePhotoshop5 | `1036` | Ressource miniature (remplace la ressource 1033). Voir Voir le format de la ressource Vignette. |
| GlobalAnglePhotoshop5 | `1037` | Angle global. 4 octets contenant un entier compris entre 0 et 359, qui correspond à l'angle d'éclairage global pour le calque d'effets. S'il n'est pas présent, supposé être 30. |
| IccProfilePhotoshop5 | `1039` | (Photoshop 5.0) Profil ICC. Octets bruts d'un profil au format ICC (International Color Consortium). Voir ICC1v42_2006-05.pdf dans le dossier Documentation et icProfileHeader.h dans Sample Code\Common\Includes. |
| WatermarkPhotoshop5 | `1040` | Filigrane. Un octet. |
| IccUntaggedProfilePhotoshop5 | `1041` | Profil non balisé ICC. 1 octet qui désactive toute gestion de profil présumée lors de l'ouverture du fichier. 1 = intentionnellement non étiqueté. |
| TransparencyIndexPhotoshop6 | `1047` | Indice de transparence. 2 octets pour l'indice de couleur transparente, le cas échéant. |
| GlobalAltitudePhotoshop6 | `1049` | Altitude globale. Entrée de 4 octets pour l'altitude. |
| SlicesPhotoshop6 | `1050` | Tranches (Photoshop 6). |
| WorkflowUrlPhotoshop6 | `1051` | URL du flux de travail. Chaîne Unicode. Photoshop 6. |
| AlphaIdentifiersPhotoshop6 | `1053` | Identifiants alpha. 4 octets de longueur, suivis de 4 octets chacun pour chaque identifiant alpha. |
| UrlListPhotoshop6 | `1054` | Liste interne d'URL. Nombre d'URL de 4 octets, suivi de 4 octets de long, d'un ID de 4 octets et d'une chaîne Unicode pour chaque nombre. |
| VersionInfoPhotoshop6 | `1057` | Informations sur la version. Version 4 octets, 1 octet hasRealMergedData , chaîne Unicode : nom du rédacteur, chaîne Unicode : nom du lecteur, version du fichier 4 octets. |
| ExifData1Photoshop7 | `1058` | données EXIF 1,[voir plus](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) . |
| ExifData3Photoshop7 | `1059` | [ Données EXIF 3.](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) |
| XmpPhotoshop7 | `1060` | Métadonnées XMP. Informations sur le fichier sous forme de description XML,[voir plus](http://www.adobe.com/devnet/xmp) . |
| CaptionDigestPhotoshop7 | `1061` | Résumé des sous-titres. 16 octets : sécurité des données RSA, algorithme de résumé de message MD5. |
| PrintScalePhotoshop7 | `1062` | Échelle d'impression. Style de 2 octets (0 = centré, 1 = taille adaptée, 2 = défini par l'utilisateur). 4 octets x emplacement (virgule flottante). 4 octets y emplacement (virgule flottante). Échelle de 4 octets (virgule flottante). |
| PixelAspectRatio | `1064` | Format d'image des pixels. 4 octets (version = 1 ou 2), 8 octets doubles, x/y d'un pixel. Version 2, tentant de corriger les valeurs pour NTSC et PAL, auparavant décalées d'un facteur d'env. 5 %. |
| LayerComps | `1065` | Couche Comp. 4 octets (version du descripteur = 16), Descriptor. |
| LayerSelectionIds | `1069` | ID(s) de sélection de couche. Compte de 2 octets, ce qui suit est répété pour chaque compte : ID de couche de 4 octets. |
| PrintInfoCS2 | `1071` | Informations d'impression (Photoshop CS2). |
| LayerGroupEnabledIdCS2 | `1072` | ID de groupe(s) de calque(s) activé(s). 1 octet pour chaque couche du document, répété par longueur de la ressource. REMARQUE : les groupes de calques ont des marqueurs de début et de fin (Photoshop CS2). |
| ColorSamplersResourceCS3 | `1073` | Ressource d'échantillonneurs de couleurs. Voir également ID 1038 pour l'ancien format. |
| MeasurementScaleCS3 | `1074` | Échelle de mesure. 4 octets (version du descripteur = 16), Descriptor. |
| TimelineInformationCS3 | `1075` | Informations chronologiques. 4 octets (version du descripteur = 16), Descriptor. |
| SheetDisclosureCS3 | `1076` | Divulgation de feuille. 4 octets (version du descripteur = 16), Descriptor. |
| PrintInformationCS5 | `1082` | Informations d'impression (Photoshop CS5). |
| PrintStyleCS5 | `1083` | Style d'impression (Photoshop CS5). |
| MacintoshNSPrintInfoCS5 | `1084` | Macintosh NSPrintInfo. Informations spécifiques au système d'exploitation variable pour Macintosh. NSPrintInfo. Il est recommandé de ne pas interpréter ou utiliser ces données. (Photoshop CS5). |
| WindowsDevmodeCS5 | `1085` | Windows DEVMODE. Informations spécifiques au système d'exploitation variable pour Windows. DEVMODE. Il est recommandé de ne pas interpréter ou utiliser ces données. (Photoshop CS5). |
| AutoSaveFilePathCS6 | `1086` | Chemin d'accès au fichier d'enregistrement automatique. Chaîne Unicode. (Photoshop CS6). |
| AutoSaveFormatCS6 | `1087` | Format d'enregistrement automatique. Chaîne Unicode. (Photoshop CS6). |
| PathSelectionStateCC | `1088` | État de sélection du chemin. (Photoshop CC). |
| ImageReadyVariables | `7000` | Variables prêtes pour l'image. Représentation XML de la définition des variables. |
| ImageReadyDatasets | `7001` | Ensembles de données Image Ready. |
| PrintFlagsInformation | `10000` | Imprimer les informations sur les drapeaux. Version 2 octets ( = 1), 1 octet repères de coupe centraux, 1 octet ( = 0), valeur de largeur de fond perdu 4 octets, échelle de largeur de fond perdu 2 octets. |

### Voir également

* espace de noms [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
