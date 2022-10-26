---
title: Metadata
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Inicializa una nueva instancia delMetadatagroupdocs.metadata/metadata clase.
type: docs
weight: 10
url: /es/net/groupdocs.metadata/metadata/metadata/
---
## Metadata(string) {#constructor_2}

Inicializa una nueva instancia del[`Metadata`](../../metadata) clase.

```csharp
public Metadata(string filePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | Una cadena que contiene el nombre completo del archivo a partir del cual se crea un[`Metadata`](../../metadata) instancia. |

### Observaciones

**Aprende más**

* [Cargar desde un disco local](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Cargar desde un flujo](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Cargar un archivo de un formato específico](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Cargar un documento protegido por contraseña](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Ejemplos

Este ejemplo muestra cómo cargar un archivo desde un disco local.

```csharp
using (Metadata metadata = new Metadata(Constants.InputOne))
{
    // Extrae, edita o elimina metadatos aquí
}
```

### Ver también

* class [Metadata](../../metadata)
* espacio de nombres [GroupDocs.Metadata](../../metadata)
* asamblea [GroupDocs.Metadata](../../../)

---

## Metadata(Stream) {#constructor}

Inicializa una nueva instancia del[`Metadata`](../../metadata) clase.

```csharp
public Metadata(Stream document)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Stream | Una secuencia que contiene el documento que se va a cargar. |

### Observaciones

**Aprende más**

* [Cargar desde un disco local](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Cargar desde un flujo](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Cargar un archivo de un formato específico](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Cargar un documento protegido por contraseña](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Ejemplos

Este ejemplo demuestra cómo cargar un archivo desde un flujo.

```csharp
using (Stream stream = File.Open(Constants.InputDoc, FileMode.Open, FileAccess.ReadWrite))
using (Metadata metadata = new Metadata(stream))
{
   // Extrae, edita o elimina metadatos aquí
}
```

### Ver también

* class [Metadata](../../metadata)
* espacio de nombres [GroupDocs.Metadata](../../metadata)
* asamblea [GroupDocs.Metadata](../../../)

---

## Metadata(string, LoadOptions) {#constructor_3}

Inicializa una nueva instancia del[`Metadata`](../../metadata) clase.

```csharp
public Metadata(string filePath, LoadOptions loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | Una cadena que contiene el nombre completo del archivo a partir del cual se crea un[`Metadata`](../../metadata) instancia. |
| loadOptions | LoadOptions | Opciones adicionales para usar al cargar un documento. |

### Observaciones

**Aprende más**

* [Cargar desde un disco local](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Cargar desde un flujo](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Cargar un archivo de un formato específico](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Cargar un documento protegido por contraseña](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Ejemplos

Este ejemplo muestra cómo cargar un documento protegido por contraseña.

```csharp
// Especificar la contraseña
var loadOptions = new LoadOptions
{
    Password = "123"
};

using (var metadata = new Metadata(Constants.ProtectedDocx, loadOptions))
{
    // Extrae, edita o elimina metadatos aquí
}
```

### Ver también

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* espacio de nombres [GroupDocs.Metadata](../../metadata)
* asamblea [GroupDocs.Metadata](../../../)

---

## Metadata(Stream, LoadOptions) {#constructor_1}

Inicializa una nueva instancia del[`Metadata`](../../metadata) clase.

```csharp
public Metadata(Stream document, LoadOptions loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Stream | Una secuencia que contiene el documento que se va a cargar. |
| loadOptions | LoadOptions | Opciones adicionales para usar al cargar un documento. |

### Observaciones

**Aprende más**

* [Cargar desde un disco local](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Cargar desde un flujo](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Cargar un archivo de un formato específico](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Cargar un documento protegido por contraseña](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Ver también

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* espacio de nombres [GroupDocs.Metadata](../../metadata)
* asamblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
