---
title: Flags
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Obtient les indicateurs dentrée ZIP.
type: docs
weight: 30
url: /fr/net/groupdocs.metadata.formats.archive/zipfile/flags/
---
## ZipFile.Flags property

Obtient les indicateurs d'entrée ZIP.

```csharp
public int Flags { get; }
```

### Valeur de la propriété

Les indicateurs d'entrée ZIP.

### Remarques

Bit 00 : fichier chiffré. Bit 01 : possibilité de compression. Bit 02 : possibilité de compression. Bit 03 : descripteur de données. Bit 04 : déflation renforcée. Bit 05 : données patchées compressées. Bit 06 : cryptage fort. Bit 07-10 : inutilisé. Bit 11 : codage de la langue. Bit 12 : réservé. Bit 13 : valeurs d'en-tête de masque. Bits 14-15 : réservés.

### Voir également

* class [ZipFile](../../zipfile)
* espace de noms [GroupDocs.Metadata.Formats.Archive](../../zipfile)
* Assemblée [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->