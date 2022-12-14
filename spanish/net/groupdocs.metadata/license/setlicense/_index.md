---
title: SetLicense
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Licencia el componente.
type: docs
weight: 20
url: /es/net/groupdocs.metadata/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licencia el componente.

```csharp
public void SetLicense(string filePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta absoluta a un archivo de licencia. |

### Ejemplos

Este ejemplo muestra cómo configurar la licencia.

```csharp
// inicializa la clase de licencia
License license = new License();

// establece la ruta al archivo .lic
license.SetLicense(@"C:\\GroupDocs.Metadata.lic");    
```

### Ver también

* class [License](../../license)
* espacio de nombres [GroupDocs.Metadata](../../license)
* asamblea [GroupDocs.Metadata](../../../)

---

## SetLicense(Stream) {#setlicense}

Licencia el componente.

```csharp
public void SetLicense(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de licencia. |

### Ver también

* class [License](../../license)
* espacio de nombres [GroupDocs.Metadata](../../license)
* asamblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
