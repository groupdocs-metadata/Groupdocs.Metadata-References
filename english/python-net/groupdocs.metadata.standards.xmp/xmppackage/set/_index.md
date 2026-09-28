---
title: set method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Sets a string property."
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/xmppackage/set/
is_root: false
weight: 1060
---


## set {#name-value}

Sets a string property.

```python
def set(self, name, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | XMP metadata property name. |
| value | `str` | XMP metadata property value. |

### Example

```python
from datetime import date
from groupdocs.metadata import Metadata
from groupdocs.metadata.standards.xmp import XmpArray, XmpArrayType, XmpPackage, XmpPacketWrapper

with Metadata("input.jpg") as metadata:
    root = metadata.get_root_package()
    packet = XmpPacketWrapper()

    custom = XmpPackage("gd", "https://groupdocs.com")
    custom.set("gd:Copyright", "Copyright (C) 2026 GroupDocs. All Rights Reserved.")
    custom.set("gd:CreationDate", date.today())
    custom.set("gd:Company", XmpArray.from_(["Aspose", "GroupDocs"], XmpArrayType.ORDERED))

    packet.add_package(custom)
    root.xmp_package = packet
    metadata.save("output.jpg")
```

## set {#name-value}

Sets an integer property.

```python
def set(self, name, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | XMP metadata property name. |
| value | `int` | XMP metadata property value. |

### Example

```python
from groupdocs.metadata.standards.xmp import XmpPackage

package = XmpPackage("gd", "https://groupdocs.com")
package.set("gd:CustomInt", 42)
```

## set {#name-value}

Assigns a boolean XMP metadata property.

```python
def set(self, name, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | XMP metadata property name. |
| value | `bool` | XMP metadata property value. |

### Example

```python
from datetime import date
from groupdocs.metadata.standards.xmp import XmpPackage, XmpArray, XmpArrayType

package = XmpPackage("gd", "https://groupdocs.com")
package.set("gd:Copyright", "Copyright (C) 2026 GroupDocs. All Rights Reserved.")
package.set("gd:CreationDate", date.today())
package.set("gd:Company", XmpArray.from_(["Aspose", "GroupDocs"], XmpArrayType.ORDERED))
```

## set {#name-value}

Sets an XMP metadata property.

```python
def set(self, name, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | XMP metadata property name. |
| value | `datetime` | XMP metadata property value. |

### Example

```python
from datetime import date

from groupdocs.metadata import Metadata
from groupdocs.metadata.standards.xmp import XmpArray, XmpArrayType, XmpPackage, XmpPacketWrapper

with Metadata("input.jpg") as metadata:
    root = metadata.get_root_package()
    packet = XmpPacketWrapper()

    custom = XmpPackage("gd", "https://groupdocs.com")
    custom.set("gd:Copyright", "Copyright (C) 2026 GroupDocs. All Rights Reserved.")
    custom.set("gd:CreationDate", date.today())
    custom.set("gd:Company", XmpArray.from_(["Aspose", "GroupDocs"], XmpArrayType.ORDERED))

    packet.add_package(custom)
    root.xmp_package = packet
    metadata.save("output.jpg")
```

## set {#name-value}

Sets a double property.

```python
def set(self, name, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | XMP metadata property name. |
| value | `float` | XMP metadata property value. |

### Example

```python
from datetime import date
from groupdocs.metadata.standards.xmp import XmpPackage, XmpArray, XmpArrayType

package = XmpPackage("gd", "https://groupdocs.com")
package.set("gd:Copyright", "Copyright (C) 2026 GroupDocs. All Rights Reserved.")
package.set("gd:CreationDate", date.today())
package.set("gd:Company", XmpArray.from_(["Aspose", "GroupDocs"], XmpArrayType.ORDERED))
```

## set {#name-value}

Sets the value inherited from [`XmpValueBase`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpvaluebase/).

```python
def set(self, name, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | XMP metadata property name. |
| value | `XmpValueBase` | XMP metadata property value. |

### Example

```python
from datetime import date

from groupdocs.metadata import Metadata
from groupdocs.metadata.standards.xmp import XmpArray, XmpArrayType, XmpPackage, XmpPacketWrapper


def add_custom_xmp_package():
    with Metadata("input.jpg") as metadata:
        root = metadata.get_root_package()
        packet = XmpPacketWrapper()

        custom = XmpPackage("gd", "https://groupdocs.com")
        custom.set("gd:Copyright", "Copyright (C) 2026 GroupDocs. All Rights Reserved.")
        custom.set("gd:CreationDate", date.today())
        custom.set(
            "gd:Company",
            XmpArray.from_(["Aspose", "GroupDocs"], XmpArrayType.ORDERED)
        )
        packet.add_package(custom)

        root.xmp_package = packet
        metadata.save("output.jpg")
```

## set {#name-value}

Assigns a value to the specified XMP metadata property.

```python
def set(self, name, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | XMP metadata property name. |
| value | `XmpComplexType` | XMP metadata property value. |

### Example

```python
    from datetime import date
    from groupdocs.metadata.standards.xmp import XmpArray, XmpArrayType, XmpPackage

    custom = XmpPackage("gd", "https://groupdocs.com")
    custom.set("gd:Copyright", "Copyright (C) 2026 GroupDocs. All Rights Reserved.")
    custom.set("gd:CreationDate", date.today())
    custom.set("gd:Company", XmpArray.from_(["Aspose", "GroupDocs"], XmpArrayType.ORDERED))
    ```

## set {#name-value}

Sets the value inherited from [`XmpArray`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmparray/).

```python
def set(self, name, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | XMP metadata property name. |
| value | `XmpArray` | XMP metadata property value. |

### Example

```python
from datetime import date
from groupdocs.metadata import Metadata
from groupdocs.metadata.standards.xmp import XmpArray, XmpArrayType, XmpPackage, XmpPacketWrapper

with Metadata("input.jpg") as metadata:
    packet = XmpPacketWrapper()
    custom = XmpPackage("gd", "https://groupdocs.com")
    custom.set("gd:Copyright", "Copyright (C) 2026 GroupDocs. All Rights Reserved.")
    custom.set("gd:CreationDate", date.today())
    custom.set("gd:Company", XmpArray.from_(["Aspose", "GroupDocs"], XmpArrayType.ORDERED))
    packet.add_package(custom)
    metadata.get_root_package().xmp_package = packet
    metadata.save("output.jpg")
```

### See Also
* class [`XmpPackage`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmppackage/)
