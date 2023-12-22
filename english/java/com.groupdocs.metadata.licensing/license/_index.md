---
title: License
second_title: GroupDocs.Metadata for Java API Reference
description: Represents GroupDocs.Metadata license.
type: docs
weight: 10
url: /java/com.groupdocs.metadata.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Represents GroupDocs.Metadata license. License class should be applied once per AppDomain.

--------------------

> ```
> This example demonstrates how to setup a license.
>      
>  // initialize License class
>  License license = new License();
>  // set path to .lic file
>  license.SetLicense(@"C:\\GroupDocs.Metadata.lic");
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [License()](#License--) |  |
## Methods

| Method | Description |
| --- | --- |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licenses the component. |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licenses the component. |
### License() {#License--}
```
public License()
```


### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licenses the component.

--------------------

> ```
> This example demonstrates how to setup license.
>      
>  // initialize License class
>  License license = new License();
>  // set path to .lic file
>  license.SetLicense(@"C:\\GroupDocs.Metadata.lic");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licensePath | java.lang.String | The absolute path to a license file. |

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Licenses the component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licenseStream | java.io.InputStream | License stream. |

