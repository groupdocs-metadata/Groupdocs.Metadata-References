---
title: DocumentTagCategory
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Proporciona etiquetas que se aplican solo a propiedades específicas del documento. Las etiquetas pueden ser útiles para determinar de qué parte de un documento de oficina se extrajo una propiedad.
type: docs
weight: 3660
url: /es/net/groupdocs.metadata.tagging/documenttagcategory/
---
## DocumentTagCategory class

Proporciona etiquetas que se aplican solo a propiedades específicas del documento. Las etiquetas pueden ser útiles para determinar de qué parte de un documento de oficina se extrajo una propiedad.

```csharp
public class DocumentTagCategory : TagCategory
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BuiltIn](../../groupdocs.metadata.tagging/documenttagcategory/builtin) { get; } | Obtiene la etiqueta que indica que la propiedad que etiqueta está incorporada. |
| [Field](../../groupdocs.metadata.tagging/documenttagcategory/field) { get; } | Obtiene la etiqueta que denota una propiedad que contiene información sobre un campo de formulario o un campo calculado extraído de un documento. |
| [HiddenData](../../groupdocs.metadata.tagging/documenttagcategory/hiddendata) { get; } | Obtiene la etiqueta que indica una parte del documento que no es visible para los usuarios normales. |
| [Page](../../groupdocs.metadata.tagging/documenttagcategory/page) { get; } | Obtiene la etiqueta que denota una propiedad que contiene información sobre una página de documento. |
| [ReadOnly](../../groupdocs.metadata.tagging/documenttagcategory/readonly) { get; } | Obtiene la etiqueta que indica que la propiedad que etiqueta es de solo lectura y GroupDocs.Metadata no puede modificarla. |
| [Revision](../../groupdocs.metadata.tagging/documenttagcategory/revision) { get; } | Obtener la etiqueta que etiqueta una propiedad que contiene información sobre la revisión de un documento (cambio registrado). |
| [Statistic](../../groupdocs.metadata.tagging/documenttagcategory/statistic) { get; } | Obtiene la etiqueta que indica una propiedad que contiene estadísticas del documento (recuento de palabras, recuento de caracteres, etc.). |
| [UserComment](../../groupdocs.metadata.tagging/documenttagcategory/usercomment) { get; } | Obtiene la etiqueta que etiqueta los comentarios de los usuarios que se muestran en el contenido del documento. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../groupdocs.metadata.tagging/tagcategory/tostring)() | Devuelve una cadena que representa el objeto actual. |

### Ver también

* class [TagCategory](../tagcategory)
* espacio de nombres [GroupDocs.Metadata.Tagging](../../groupdocs.metadata.tagging)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->