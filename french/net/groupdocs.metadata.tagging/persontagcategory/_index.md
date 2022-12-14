---
title: PersonTagCategory
second_title: Référence de l'API GroupDocs.Metadata pour .NET
description: Fournit des balises qui marquent les propriétés des métadonnées contenant des informations sur les personnes ayant contribué à la création de fichiers ou de contenu intellectuel. Ces balises peuvent vous aider à trouver le créateur du document léditeur ou même le client pour lequel le travail a été effectué. Malgré le nom de la catégorie certaines propriétés de métadonnées marquées avec les balises peuvent contenir un nom de société plutôt que le nom dune personne.
type: docs
weight: 3690
url: /fr/net/groupdocs.metadata.tagging/persontagcategory/
---
## PersonTagCategory class

Fournit des balises qui marquent les propriétés des métadonnées contenant des informations sur les personnes ayant contribué à la création de fichiers ou de contenu intellectuel. Ces balises peuvent vous aider à trouver le créateur du document, l'éditeur ou même le client pour lequel le travail a été effectué. Malgré le nom de la catégorie, certaines propriétés de métadonnées marquées avec les balises peuvent contenir un nom de société plutôt que le nom d'une personne.

```csharp
public class PersonTagCategory : TagCategory
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Client](../../groupdocs.metadata.tagging/persontagcategory/client) { get; } | Obtient la balise qui étiquette les informations sur le client pour lequel le fichier/contenu intellectuel a été créé. |
| [Contributor](../../groupdocs.metadata.tagging/persontagcategory/contributor) { get; } | Obtient la balise qui étiquette une propriété contenant le nom d'une personne qui a contribué d'une manière ou d'une autre à la création du fichier. Veuillez noter que la balise n'est pas appliquée aux propriétés de métadonnées marquées avec des balises plus spécifiques de cette catégorie. Par exemple, si une propriété étiquetée avec la balise Creator. |
| [Creator](../../groupdocs.metadata.tagging/persontagcategory/creator) { get; } | Obtient la balise qui indique l'auteur original d'un fichier/document. |
| [Editor](../../groupdocs.metadata.tagging/persontagcategory/editor) { get; } | Obtient la balise qui étiquette une personne qui a modifié un fichier. La balise est généralement utilisée pour marquer une propriété contenant des informations sur le dernier éditeur. |
| [Manager](../../groupdocs.metadata.tagging/persontagcategory/manager) { get; } | Obtient la balise qui étiquette les informations sur une personne qui a géré le processus de création d'un fichier. |
| [Model](../../groupdocs.metadata.tagging/persontagcategory/model) { get; } | Obtient la balise qui indique des informations sur une personne à propos du contenu du fichier. Pour les photos qui sont une personne montrée dans l'image. |
| [Publisher](../../groupdocs.metadata.tagging/persontagcategory/publisher) { get; } | Obtient la balise marquant une personne responsable de la mise à disposition du fichier. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [ToString](../../groupdocs.metadata.tagging/tagcategory/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |

### Voir également

* class [TagCategory](../tagcategory)
* espace de noms [GroupDocs.Metadata.Tagging](../../groupdocs.metadata.tagging)
* Assemblée [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
