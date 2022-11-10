---
title: IptcApplicationRecordDataSet
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Définit les numéros densemble de données denregistrement dapplication IPTC.
type: docs
weight: 2890
url: /fr/net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/
---
## IptcApplicationRecordDataSet enumeration

Définit les numéros d'ensemble de données d'enregistrement d'application IPTC.

```csharp
public enum IptcApplicationRecordDataSet
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| RecordVersion | `0` | Représente la version de l'enregistrement. Binaire. Toujours 2 en JPEG. |
| ObjectTypeReference | `3` | Référence du type d'objet. Modèle utilisé : "/\d{2} :[\w\s]{0,64}?/". |
| ObjectAttributeReference | `4` | La référence d'attribut d'objet. |
| ObjectName | `5` | Utilisé comme référence abrégée pour l'objet. |
| EditStatus | `7` | Statut de l'objectdata, selon la pratique du provider. |
| EditorialUpdate | `8` | Indique le type de mise à jour que cet objet fournit à un objet précédent. |
| Urgency | `10` | Spécifie l'urgence éditoriale du contenu et pas nécessairement la priorité de traitement des enveloppes (voir 1:60, Envelope Priority). |
| SubjectReference | `12` | La référence du sujet. |
| Category | `15` | Identifie le sujet de l'objectdata de l'avis du fournisseur. |
| SupplementalCategory | `20` | Les catégories supplémentaires affinent davantage le sujet d'un objectdata. Une seule catégorie supplémentaire peut être contenue dans chaque DataSet. Une catégorie supplémentaire peut inclure n'importe laquelle des catégories reconnues telles qu'utilisées en 2:15. |
| FixtureIdentifier | `22` | L'identifiant de l'appareil. |
| Keywords | `25` | Utilisé pour indiquer des mots de recherche d'informations spécifiques. Chaque mot-clé utilise un seul jeu de données de mots-clés. Plusieurs mots-clés utilisent plusieurs jeux de données de mots-clés. |
| ContentLocationCode | `26` | Indique le code d'un pays/lieu géographique référencé par le contenu de l'objet. |
| ContentLocationName | `27` | Fournit un nom complet et publiable d'un pays/emplacement géographique référencé par le contenu de l'objet, selon les directives du fournisseur. |
| ReleaseDate | `30` | Désigne sous la forme CCYYMMDD la première date à laquelle le fournisseur souhaite que l'objet soit utilisé. Conforme à la norme ISO 8601. |
| ReleaseTime | `35` | Désigne sous la forme HHMMSS±HHMM la première heure à laquelle le fournisseur a l'intention d'utiliser l'objet. Conforme à la norme ISO 8601. |
| ExpirationDate | `37` | Désigne sous la forme CCYYMMDD la dernière date à laquelle le fournisseur ou le propriétaire souhaite que les données d'objet soient utilisées. Conforme à la norme ISO 8601. |
| SpecialInstructions | `40` | Autres instructions éditoriales concernant l'utilisation des données d'objet, telles que les embargos et les avertissements. |
| ActionAdvised | `42` | Indique le type d'action que cet objet fournit à un objet précédent. |
| ReferenceService | `45` | Identifie l'identifiant de service d'une enveloppe précédente à laquelle l'objet courant se réfère. |
| ReferenceDate | `47` | Identifie la date d'une enveloppe précédente à laquelle se réfère l'objet courant. |
| ReferenceNumber | `50` | Identifie le numéro d'enveloppe d'une enveloppe précédente à laquelle l'objet actuel se réfère. |
| DateCreated | `55` | Représenté sous la forme CCYYMMDD pour désigner la date de création du contenu intellectuel de l'objectdata plutôt que la date de création de la représentation physique. |
| TimeCreated | `60` | Représenté sous la forme HHMMSS±HHMM pour désigner l'heure à laquelle le contenu intellectuel de l'objectdata matériel source actuel a été créé plutôt que la création de la représentation physique. |
| DigitalCreationDate | `62` | Représenté sous la forme CCYYMMDD pour désigner la date à laquelle la représentation numérique de l'objectdata a été créée. |
| DigitalCreationTime | `63` | Représenté sous la forme HHMMSS±HHMM pour désigner l'heure à laquelle la représentation numérique de l'objectdata a été créée. |
| OriginatingProgram | `65` | Identifie le type de programme utilisé pour créer l'objectdata. |
| ProgramVersion | `70` | Utilisé pour identifier la version du programme mentionnée dans 2:65. L'ensemble de données 2:70 n'est pas valide si 2:65 n'est pas présent. |
| ObjectCycle | `75` | Composé d'un caractère alphabétique. Où : 'a' = matin, 'p' = soir, 'b' = les deux. |
| Byline | `80` | Contient le nom du créateur de l'objectdata, par exemple écrivain, photographe ou graphiste. |
| BylineTitle | `85` | Un titre by-line est le titre du créateur ou des créateurs d'une donnée d'objet. |
| City | `90` | Identifie la ville d'origine des données d'objets conformément aux directives établies par le fournisseur. |
| SubLocation | `92` | Identifie l'emplacement dans une ville d'où proviennent les données d'objet, conformément aux directives établies par le fournisseur. |
| ProvinceState | `95` | Identifie la province/l'État d'origine conformément aux directives établies par le fournisseur. |
| PrimaryLocationCode | `100` | Indique le code du pays/lieu principal où la propriété intellectuelle de l'objectdata a été créée, par exemple une photo a été prise, un événement s'est produit. |
| PrimaryLocationName | `101` | Fournit le nom complet, publiable, du pays/emplacement principal où la propriété intellectuelle de l'objectdata a été créée, conformément aux directives du fournisseur. |
| OriginalTransmissionReference | `103` | Un code représentant le lieu de transmission d'origine selon les pratiques du fournisseur. |
| Headline | `105` | Une entrée publiable fournissant un synopsis du contenu de l'objectdata. |
| Credit | `110` | Identifie le fournisseur des données d'objet, pas nécessairement le propriétaire/créateur. |
| Source | `115` | Le nom d'une personne ou d'une partie qui joue un rôle dans la chaîne d'approvisionnement du contenu. Il peut s'agir d'une agence, d'un membre d'une agence, d'un individu ou d'une combinaison. |
| CopyrightNotice | `116` | Contient tout avis de droit d'auteur nécessaire. |
| Contact | `118` | Identifie la personne ou l'organisation qui peut fournir des informations complémentaires sur les données d'objet. |
| CaptionAbstract | `120` | Une description textuelle de l'objectdata, particulièrement utilisée lorsque l'objet n'est pas du texte. |
| WriterEditor | `122` | Identification du nom de la personne impliquée dans la rédaction, l'édition ou la correction des données d'objet ou de la légende/du résumé. |
| RasterizedCaption | `125` | Largeur d'image 460 pixels et hauteur d'image 128 pixels. Sens de numérisation de bas en haut, de gauche à droite. |
| ImageType | `130` | Les caractères numériques de 1 à 4 indiquent le nombre de composants dans une image, dans une ou plusieurs enveloppes. |
| ImageOrientation | `131` | Indique la disposition de la zone d'image. |
| LanguageIdentifier | `135` | Décrit la langue nationale principale de l'objet, selon les codes à 2 lettres de la norme ISO 639:1988. |
| AudioType | `150` | Le type audio. |
| AudioSamplingRate | `151` | Caractères numériques du taux d'échantillonnage, représentant le taux d'échantillonnage en hertz (Hz). |
| AudioSamplingResolution | `152` | Le nombre de bits dans chaque échantillon audio. |
| AudioDuration | `153` | Durée Désigne sous la forme HHMMSS le temps d'exécution d'une donnée d'objet audio lors de sa lecture à la vitesse à laquelle elle a été enregistrée. |
| AudioOutcue | `154` | Identifie le contenu de la fin d'une donnée d'objet audio, conformément aux directives établies par le fournisseur. |
| ObjDataPreviewFileFormat | `200` | Un nombre binaire représentant le format de fichier de l'aperçu ObjectData. |
| ObjDataPreviewFileFormatVer | `201` | Un nombre binaire représentant la version particulière du format de fichier d'aperçu ObjectData spécifié dans 2:200. |
| ObjDataPreviewData | `202` | L'aperçu des données d'objet. |

### Voir également

* espace de noms [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
