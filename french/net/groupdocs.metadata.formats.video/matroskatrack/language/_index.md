---
title: Language
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Obtient la langue de la piste dans le formulaire de langues Matroska. Cet élément DOIT être ignoré si leLanguageIetfgroupdocs.metadata.formats.video/matroskatrack/languageietf Lélément est utilisé dans le même TrackEntry.
type: docs
weight: 50
url: /fr/net/groupdocs.metadata.formats.video/matroskatrack/language/
---
## MatroskaTrack.Language property

Obtient la langue de la piste dans le formulaire de langues Matroska. Cet élément DOIT être ignoré si le[`LanguageIetf`](../languageietf) L'élément est utilisé dans le même TrackEntry.

```csharp
public string Language { get; }
```

### Valeur de la propriété

La langue de la piste dans la forme des langues Matroska.

### Remarques

Les codes de langue peuvent être soit la forme bibliographique à 3 lettres ISO-639-2 (comme "fre" pour le français), ou un tel code de langue suivi d'un tiret et d'un code de pays pour les spécialités en langues (comme "fre-ca" pour le français canadien). Les codes de pays sont les mêmes que ceux utilisés pour les domaines Internet.

### Voir également

* class [MatroskaTrack](../../matroskatrack)
* espace de noms [GroupDocs.Metadata.Formats.Video](../../matroskatrack)
* Assemblée [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->