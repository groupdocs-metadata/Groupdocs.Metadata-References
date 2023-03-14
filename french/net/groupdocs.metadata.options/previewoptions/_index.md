---
title: PreviewOptions
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Fournit des options pour définir les exigences et les délégués de flux pour la génération daperçu.
type: docs
weight: 2700
url: /fr/net/groupdocs.metadata.options/previewoptions/
---
## PreviewOptions class

Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçu.

```csharp
public class PreviewOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PreviewOptions](previewoptions#constructor)(CreatePageStream) | Initialise une nouvelle instance du[`PreviewOptions`](../previewoptions) classe provoquant la fermeture du flux de sortie. |
| [PreviewOptions](previewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initialise une nouvelle instance de[`PreviewOptions`](../previewoptions) classe provoquant le retour du flux de sortie au client pour une utilisation ultérieure. |

## Propriétés

| Nom | La description |
| --- | --- |
| [CacheFolder](../../groupdocs.metadata.options/previewoptions/cachefolder) { get; set; } | Obtient ou définit le dossier de cache. Par défaut, le dossier de cache est défini sur le répertoire temporaire local de l'utilisateur. |
| [CreatePageStream](../../groupdocs.metadata.options/previewoptions/createpagestream) { get; set; } | Obtient ou définit une instance du délégué de création de flux de page. |
| [Height](../../groupdocs.metadata.options/previewoptions/height) { get; set; } | Obtient ou définit la hauteur d'aperçu de la page. |
| [MaxDiskSpaceForCache](../../groupdocs.metadata.options/previewoptions/maxdiskspaceforcache) { get; set; } | Obtient ou définit l'espace disque disponible maximum pour le cache en octets. La valeur par défaut est 1073741824. |
| [MaxMemoryForCache](../../groupdocs.metadata.options/previewoptions/maxmemoryforcache) { get; set; } | Obtient ou définit la mémoire maximale disponible pour le cache en mémoire en octets. La valeur par défaut est 1073741824. |
| [PageNumbers](../../groupdocs.metadata.options/previewoptions/pagenumbers) { get; set; } | Obtient ou définit un tableau de numéros de page pour générer des aperçus. |
| [PreviewFormat](../../groupdocs.metadata.options/previewoptions/previewformat) { get; set; } | Obtient ou définit le format de l'image d'aperçu. |
| [ReleasePageStream](../../groupdocs.metadata.options/previewoptions/releasepagestream) { get; set; } | Obtient ou définit une instance du délégué d'achèvement de l'aperçu de la page. |
| [Width](../../groupdocs.metadata.options/previewoptions/width) { get; set; } | Obtient ou définit la largeur de l'aperçu de la page. |

### Remarques

**Apprendre encore plus**

* [Générer un aperçu du document](https://docs.groupdocs.com/display/metadatanet/Generate+document+preview)

### Voir également

* espace de noms [GroupDocs.Metadata.Options](../../groupdocs.metadata.options)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->