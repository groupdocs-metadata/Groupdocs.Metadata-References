---
title: License
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the component license.
type: docs
weight: 10
url: /java/com.groupdocs.metadata.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Represents the component license.
## Constructors

| Constructor | Description |
| --- | --- |
| [License()](#License--) | Initializes a new instance of the  License  class. |
## Methods

| Method | Description |
| --- | --- |
| [setLicense(String filePath)](#setLicense-java.lang.String-) | Licenses the component. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenses the component. |
### License() {#License--}
```
public License()
```


Initializes a new instance of the  License  class.

### setLicense(String filePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String filePath)
```


Licenses the component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The absolute path to license file. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Licenses the component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream containing a valid license. |

