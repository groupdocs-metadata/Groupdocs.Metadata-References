---
title: Metadata
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Initialise une nouvelle instance duMetadatagroupdocs.metadata/metadata classe.
type: docs
weight: 10
url: /fr/net/groupdocs.metadata/metadata/metadata/
---
## Metadata(string) {#constructor_2}

Initialise une nouvelle instance du[`Metadata`](../../metadata) classe.

```csharp
public Metadata(string filePath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Chaîne contenant le nom complet du fichier à partir duquel créer un[`Metadata`](../../metadata) exemple. |

### Remarques

**Apprendre encore plus**

* [Charger depuis un disque local](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Charger à partir d'un flux](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Charger un fichier d'un format spécifique](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Charger un document protégé par mot de passe](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Exemples

Cet exemple montre comment charger un fichier à partir d'un disque local.

```csharp
using (Metadata metadata = new Metadata(Constants.InputOne))
{
    // Extrayez, modifiez ou supprimez les métadonnées ici
}
```

### Voir également

* class [Metadata](../../metadata)
* espace de noms [GroupDocs.Metadata](../../metadata)
* Assemblée [GroupDocs.Metadata](../../../)

---

## Metadata(Stream) {#constructor}

Initialise une nouvelle instance du[`Metadata`](../../metadata) classe.

```csharp
public Metadata(Stream document)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Stream | Un flux qui contient le document à charger. |

### Remarques

**Apprendre encore plus**

* [Charger depuis un disque local](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Charger à partir d'un flux](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Charger un fichier d'un format spécifique](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Charger un document protégé par mot de passe](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Exemples

Cet exemple montre comment charger un fichier à partir d'un flux.

```csharp
using (Stream stream = File.Open(Constants.InputDoc, FileMode.Open, FileAccess.ReadWrite))
using (Metadata metadata = new Metadata(stream))
{
   // Extrayez, modifiez ou supprimez les métadonnées ici
}
```

### Voir également

* class [Metadata](../../metadata)
* espace de noms [GroupDocs.Metadata](../../metadata)
* Assemblée [GroupDocs.Metadata](../../../)

---

## Metadata(string, LoadOptions) {#constructor_3}

Initialise une nouvelle instance du[`Metadata`](../../metadata) classe.

```csharp
public Metadata(string filePath, LoadOptions loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Chaîne contenant le nom complet du fichier à partir duquel créer un[`Metadata`](../../metadata) exemple. |
| loadOptions | LoadOptions | Options supplémentaires à utiliser lors du chargement d'un document. |

### Remarques

**Apprendre encore plus**

* [Charger depuis un disque local](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Charger à partir d'un flux](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Charger un fichier d'un format spécifique](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Charger un document protégé par mot de passe](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Exemples

Cet exemple montre comment charger un document protégé par mot de passe.

```csharp
// Spécifiez le mot de passe
var loadOptions = new LoadOptions
{
    Password = "123"
};

using (var metadata = new Metadata(Constants.ProtectedDocx, loadOptions))
{
    // Extrayez, modifiez ou supprimez les métadonnées ici
}
```

### Voir également

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* espace de noms [GroupDocs.Metadata](../../metadata)
* Assemblée [GroupDocs.Metadata](../../../)

---

## Metadata(Stream, LoadOptions) {#constructor_1}

Initialise une nouvelle instance du[`Metadata`](../../metadata) classe.

```csharp
public Metadata(Stream document, LoadOptions loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Stream | Un flux qui contient le document à charger. |
| loadOptions | LoadOptions | Options supplémentaires à utiliser lors du chargement d'un document. |

### Remarques

**Apprendre encore plus**

* [Charger depuis un disque local](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Charger à partir d'un flux](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Charger un fichier d'un format spécifique](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Charger un document protégé par mot de passe](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Voir également

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* espace de noms [GroupDocs.Metadata](../../metadata)
* Assemblée [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
