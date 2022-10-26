---
title: DiagramPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa un paquete de metadatos nativos en formato de diagrama.
type: docs
weight: 890
url: /es/net/groupdocs.metadata.formats.document/diagrampackage/
---
## DiagramPackage class

Representa un paquete de metadatos nativos en formato de diagrama.

```csharp
public class DiagramPackage : DocumentPackage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternateNames](../../groupdocs.metadata.formats.document/diagrampackage/alternatenames) { get; set; } | Obtiene o establece los nombres alternativos del documento. Solo se puede actualizar en formatos VDX y VSX. |
| [BuildNumberCreated](../../groupdocs.metadata.formats.document/diagrampackage/buildnumbercreated) { get; } | Obtiene el número de compilación completo de la instancia utilizada para crear el documento. |
| [BuildNumberEdited](../../groupdocs.metadata.formats.document/diagrampackage/buildnumberedited) { get; } | Obtiene el número de compilación de la última instancia utilizada para editar el documento. |
| [Category](../../groupdocs.metadata.formats.document/diagrampackage/category) { get; set; } | Obtiene o establece el texto descriptivo para el tipo de dibujo, como diagrama de flujo o diseño de oficina. Este texto también se puede ingresar en la interfaz de usuario de Microsoft Visio en el cuadro Categoría del cuadro de diálogo Propiedades. |
| [Company](../../groupdocs.metadata.formats.document/diagrampackage/company) { get; set; } | Obtiene o establece la información ingresada por el usuario que identifica a la empresa que crea el dibujo o la empresa para la que se crea el dibujo. La longitud máxima es de 63 caracteres. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [Creator](../../groupdocs.metadata.formats.document/diagrampackage/creator) { get; set; } | Obtiene o establece la persona que creó o actualizó por última vez el archivo. La longitud máxima es de 63 caracteres.. |
| [Description](../../groupdocs.metadata.formats.document/diagrampackage/description) { get; set; } | Obtiene o establece una cadena de texto descriptivo para el documento. Use este elemento para almacenar información importante sobre el documento, como su propósito, cambios recientes o cambios pendientes. El máximo es 191 caracteres. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/diagrampackage/hyperlinkbase) { get; set; } | Obtiene o establece la ruta que se utilizará para los hipervínculos relativos (hipervínculos para los que se describe la ubicación del archivo vinculado en relación con el diagrama de Microsoft Visio). De forma predeterminada, una ruta de hipervínculo es relativa al documento actual a menos que se especifique una ruta diferente en este elemento. La longitud máxima es de 256 caracteres. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Obtiene el[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con el nombre especificado. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Keywords](../../groupdocs.metadata.formats.document/diagrampackage/keywords) { get; set; } | Obtiene o establece una cadena de texto que identifica temas u otra información importante sobre el archivo, como el nombre del proyecto, el nombre del cliente o el número de versión. La longitud máxima de la cadena es de 63 caracteres. |
| [Language](../../groupdocs.metadata.formats.document/diagrampackage/language) { get; set; } | Obtiene o establece el idioma del documento. Solo se puede actualizar en formatos VSD y VSDX. |
| [Manager](../../groupdocs.metadata.formats.document/diagrampackage/manager) { get; set; } | Obtiene o establece una cadena de texto ingresada por el usuario que identifica a la persona a cargo del proyecto o departamento. La longitud máxima es de 63 caracteres. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [PreviewPicture](../../groupdocs.metadata.formats.document/diagrampackage/previewpicture) { get; set; } | Obtiene o establece la imagen de vista previa. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Subject](../../groupdocs.metadata.formats.document/diagrampackage/subject) { get; set; } | Obtiene o establece una cadena de texto definida por el usuario que describe el contenido del documento. La longitud máxima es de 63 caracteres. |
| [Template](../../groupdocs.metadata.formats.document/diagrampackage/template) { get; set; } | Obtiene o establece un valor de cadena que especifica el nombre de archivo de la plantilla a partir de la cual se creó el documento. |
| [TimeCreated](../../groupdocs.metadata.formats.document/diagrampackage/timecreated) { get; set; } | Obtiene o establece un valor de fecha y hora que indica cuándo se creó el documento. |
| [TimeEdited](../../groupdocs.metadata.formats.document/diagrampackage/timeedited) { get; } | Obtiene un valor de fecha y hora que indica cuándo se editó el documento por última vez. |
| [TimePrinted](../../groupdocs.metadata.formats.document/diagrampackage/timeprinted) { get; } | Obtiene un valor de fecha y hora que indica cuándo se imprimió el documento por última vez. |
| [TimeSaved](../../groupdocs.metadata.formats.document/diagrampackage/timesaved) { get; } | Obtiene un valor de fecha y hora que indica cuándo se guardó el documento por última vez. |
| [Title](../../groupdocs.metadata.formats.document/diagrampackage/title) { get; set; } | Obtiene o establece una cadena de texto definida por el usuario que sirve como título descriptivo para el documento. La longitud máxima es de 63 caracteres. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | Elimina todas las propiedades de metadatos de escritura del paquete. |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | Elimina todas las propiedades de metadatos integradas. |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | Elimina todas las propiedades de metadatos personalizados. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | Elimina una propiedad de metadatos de escritura por el nombre especificado. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set)(string, bool) | Agrega o reemplaza la propiedad de metadatos con el nombre especificado. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_2)(string, DateTime) | Agrega o reemplaza la propiedad de metadatos con el nombre especificado. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_1)(string, double) | Agrega o reemplaza la propiedad de metadatos con el nombre especificado. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_3)(string, string) | Agrega o reemplaza la propiedad de metadatos con el nombre especificado. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos en diagramas](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### Ejemplos

Este ejemplo de código muestra cómo extraer propiedades de metadatos integradas de un diagrama.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.DocumentProperties.Creator);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.TimeCreated);
    Console.WriteLine(root.DocumentProperties.Category);

    // ... 
}
```

### Ver también

* class [DocumentPackage](../documentpackage)
* espacio de nombres [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
