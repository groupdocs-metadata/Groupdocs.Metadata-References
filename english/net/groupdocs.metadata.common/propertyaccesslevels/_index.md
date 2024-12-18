---
title: PropertyAccessLevels
second_title: GroupDocs.Metadata for .NET API Reference
description: Defines access levels for metadata properties.
type: docs
weight: 170
url: /net/groupdocs.metadata.common/propertyaccesslevels/
---
## PropertyAccessLevels enumeration

Defines access levels for metadata properties.

```csharp
[Flags]
public enum PropertyAccessLevels
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Read | `0` | The property is read-only. |
| Update | `1` | It is possible to update the property using the [`UpdateProperties`](../metadatapackage/updateproperties) method. |
| Remove | `2` | The property can be removed through the [`RemoveProperties`](../metadatapackage/removeproperties) method. |
| Add | `4` | It is possible to update the property using the [`AddProperties`](../metadatapackage/addproperties) method. |
| Full | `7` | Grants full access to the property. |
| AddOrUpdate | `5` | It is allowed to add and update the property. All other operations are restricted. |

### See Also

* namespace [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
