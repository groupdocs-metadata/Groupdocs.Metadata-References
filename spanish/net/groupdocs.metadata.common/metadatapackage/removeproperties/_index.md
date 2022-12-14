---
title: RemoveProperties
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Elimina las propiedades de metadatos que cumplen el predicado especificado.
type: docs
weight: 100
url: /es/net/groupdocs.metadata.common/metadatapackage/removeproperties/
---
## MetadataPackage.RemoveProperties method

Elimina las propiedades de metadatos que cumplen el predicado especificado.

```csharp
public virtual int RemoveProperties(Func<MetadataProperty, bool> predicate)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| predicate | Func`2 | Una función para probar cada propiedad de metadatos para una condición. |

### Valor_devuelto

El número de propiedades afectadas.

### Observaciones

**Aprende más**

* Más ejemplos que demuestran los usos de este método: [Eliminación de metadatos](https://docs.groupdocs.com/display/metadatanet/Removing+metadata)

### Ver también

* delegate [Func&lt;T,TResult&gt;](../../func-2)
* class [MetadataProperty](../../metadataproperty)
* class [MetadataPackage](../../metadatapackage)
* espacio de nombres [GroupDocs.Metadata.Common](../../metadatapackage)
* asamblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
