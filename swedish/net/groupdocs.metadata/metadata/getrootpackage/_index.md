---
title: GetRootPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Hämtar rotpaketet som ger tillgång till alla metadataegenskaper som extraherats från filen.
type: docs
weight: 80
url: /sv/net/groupdocs.metadata/metadata/getrootpackage/
---
## GetRootPackage() {#getrootpackage}

Hämtar rotpaketet som ger tillgång till alla metadataegenskaper som extraherats från filen.

```csharp
public RootMetadataPackage GetRootPackage()
```

### Returvärde

Rotpaketet ger tillgång till alla metadataegenskaper som extraherats från filen.

### Anmärkningar

**Läs mer**

* [Gå igenom ett helt metadataträd](https://docs.groupdocs.com/display/metadatanet/Traverse+a+whole+metadata+tree)

### Exempel

Det här exemplet visar hur man går igenom hela metadataträdet för en specifik fil oavsett format.

```csharp
public static void Run()
{
    using (Metadata metadata = new Metadata(Constants.JpegWithXmp))
    {
        DisplayMetadataTree(metadata.GetRootPackage(), 0);
    }
}

private static void DisplayMetadataTree(MetadataPackage package, int indent)
{
    if (package != null)
    {
        var stringMetadataType = package.MetadataType.ToString();
        Console.WriteLine(stringMetadataType.PadLeft(stringMetadataType.Length + indent));
        foreach (MetadataProperty property in package)
        {
            string stringPropertyRepresentation = string.Format("Name: {0}, Value: {1}", property.Name, property.Value);
            Console.WriteLine(stringPropertyRepresentation.PadLeft(stringPropertyRepresentation.Length + indent + 1));
            if (property.Value != null)
            {
                switch (property.Value.Type)
                {
                    case MetadataPropertyType.Metadata:
                        DisplayMetadataTree(property.Value.ToClass<MetadataPackage>(), indent + 2);
                    break;
                    case MetadataPropertyType.MetadataArray:
                        DisplayMetadataTree(property.Value.ToArray<MetadataPackage>(), indent + 2);
                    break;
                }
            }
        }
    }
}

private static void DisplayMetadataTree(MetadataPackage[] packages, int indent)
{
    if (packages != null)
    {
        foreach (var package in packages)
        {
            DisplayMetadataTree(package, indent);
        }
    }
}
```

### Se även

* class [RootMetadataPackage](../../../groupdocs.metadata.common/rootmetadatapackage)
* class [Metadata](../../metadata)
* namnutrymme [GroupDocs.Metadata](../../metadata)
* hopsättning [GroupDocs.Metadata](../../../)

---

## GetRootPackage&lt;TRoot&gt;() {#getrootpackage_1}

Hämtar rotpaketet som ger tillgång till alla metadataegenskaper som extraherats från filen.

```csharp
public TRoot GetRootPackage<TRoot>()
    where TRoot : RootMetadataPackage
```

| Parameter | Beskrivning |
| --- | --- |
| TRoot | Den exakta typen av rotpaketet. |

### Returvärde

Rotpaketet ger tillgång till alla metadataegenskaper som extraherats från filen.

### Anmärkningar

**Läs mer**

* [Gå igenom ett helt metadataträd](https://docs.groupdocs.com/display/metadatanet/Traverse+a+whole+metadata+tree)

### Se även

* class [RootMetadataPackage](../../../groupdocs.metadata.common/rootmetadatapackage)
* class [Metadata](../../metadata)
* namnutrymme [GroupDocs.Metadata](../../metadata)
* hopsättning [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->