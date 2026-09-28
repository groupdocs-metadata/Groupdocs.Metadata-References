---
title: to_list method
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Creates a list from the package."
type: docs
url: /python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage/to_list/
is_root: false
weight: 1080
---


## to_list

Creates a list from the package.

```python
def to_list(self):
    ...
```

**Returns:** list[RawTag]: A list that contains all raw tags from the package.

### Example

```python
    from groupdocs.metadata import Metadata

    def read_exif_tags():
        with Metadata("exif.jpg") as metadata:
            root = metadata.get_root_package()
            exif = getattr(root, "exif_package", None)
            if exif is not None:
                for tag in exif.to_list():
                    print(f"{tag.tag_id} = {tag.value}")

                for tag in exif.exif_ifd_package.to_list():
                    print(f"{tag.tag_id} = {tag.value}")

                for tag in exif.gps_package.to_list():
                    print(f"{tag.tag_id} = {tag.value}")

    if __name__ == "__main__":
        read_exif_tags()
    ```

### See Also
* class [`RawDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.formats.raw/rawdictionarybasepackage/)
