---
title: AdditionalInfo
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Obtient ou définit les informations supplémentaires. Cette valeur est représentée par le champ INF.
type: docs
weight: 20
url: /fr/net/groupdocs.metadata.formats.audio/lyricstag/additionalinfo/
---
## LyricsTag.AdditionalInfo property

Obtient ou définit les informations supplémentaires. Cette valeur est représentée par le champ INF.

```csharp
public string AdditionalInfo { get; set; }
```

### Valeur de la propriété

Les informations complémentaires.

### Remarques

Il s'agit toujours de trois (3) caractères dans la version 2.00, mais cela pourrait être plus long dans une future norme. Le premier octet indique la présence ou non d'un champ de paroles. "1" pour le présent et "0" pour le contraire. Le deuxième caractère indique s'il y a un horodatage dans les paroles. Encore "1" pour oui et "0" pour non. Le troisième caractère inhibe les pistes pour la sélection aléatoire - "1" si inhibé et "0" sinon.

### Voir également

* class [LyricsTag](../../lyricstag)
* espace de noms [GroupDocs.Metadata.Formats.Audio](../../lyricstag)
* Assemblée [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->