---
title: Metadata
second_title: GroupDocs.Signature for Java API Reference
description: Provides the main class to access metadata in all supported formats.
type: docs
weight: 10
url: /java/com.groupdocs.metadata/metadata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public final class Metadata implements Closeable
```

Provides the main class to access metadata in all supported formats.
## Constructors

| Constructor | Description |
| --- | --- |
| [Metadata(String filePath)](#Metadata-java.lang.String-) | Initializes a new instance of the  Metadata  class. |
| [Metadata(InputStream document)](#Metadata-java.io.InputStream-) | Initializes a new instance of the  Metadata  class. |
| [Metadata(String filePath, LoadOptions loadOptions)](#Metadata-java.lang.String-com.groupdocs.metadata.options.LoadOptions-) | Initializes a new instance of the  Metadata  class. |
| [Metadata(InputStream document, LoadOptions loadOptions)](#Metadata-java.io.InputStream-com.groupdocs.metadata.options.LoadOptions-) | Initializes a new instance of the  Metadata  class. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Gets the type of the loaded file (if recognized). |
| [getRootPackage()](#getRootPackage--) | Gets the root package providing access to all metadata properties extracted from the file. |
| [<TRoot>getRootPackageGeneric()](#-TRoot-getRootPackageGeneric--) | Gets the root package providing access to all metadata properties extracted from the file. |
| [findProperties(Specification specification)](#findProperties-com.groupdocs.metadata.search.Specification-) | Finds the metadata properties satisfying a specification. |
| [updateProperties(Specification specification, PropertyValue value)](#updateProperties-com.groupdocs.metadata.search.Specification-com.groupdocs.metadata.core.PropertyValue-) | Updates known metadata properties satisfying a specification. |
| [removeProperties(Specification specification)](#removeProperties-com.groupdocs.metadata.search.Specification-) | Removes metadata properties satisfying a specification. |
| [addProperties(Specification specification, PropertyValue value)](#addProperties-com.groupdocs.metadata.search.Specification-com.groupdocs.metadata.core.PropertyValue-) | Adds known metadata properties satisfying the specification. |
| [setProperties(Specification specification, PropertyValue value)](#setProperties-com.groupdocs.metadata.search.Specification-com.groupdocs.metadata.core.PropertyValue-) | Sets known metadata properties satisfying the specification. |
| [sanitize()](#sanitize--) | Removes writable metadata properties from all detected packages or whole packages if possible. |
| [save()](#save--) | Saves all changes made in the loaded document. |
| [save(OutputStream document)](#save-java.io.OutputStream-) | Saves the document content into a stream. |
| [save(String filePath)](#save-java.lang.String-) | Saves the document content to the specified file. |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.metadata.options.PreviewOptions-) | Creates preview images for specified pages. |
| [getDocumentInfo()](#getDocumentInfo--) | Gets common information about the loaded document. |
| [close()](#close--) | Closes the loaded document and releases any system resources associated with it. |
### Metadata(String filePath) {#Metadata-java.lang.String-}
```
public Metadata(String filePath)
```


Initializes a new instance of the  Metadata  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A string that contains the full name of the file from which to create a  Metadata  instance.

**Learn more**

 *  [Load from a local disk][]
 *  [Load from a stream][]
 *  [Load a file of a specific format][]
 *  [Load a password-protected document][]

This example demonstrates how to load a file from a local disk.

> ```
> ```
> 
>  // Constants.InputOne is an absolute or relative path to your document. Ex: @"C:\Docs\source.one"
>  try (Metadata metadata = new Metadata(Constants.InputOne)) {
>      // Extract, edit or remove metadata here
>  }
>  
> ```
> ```


[Load from a local disk]: https://docs.groupdocs.com/display/metadatajava/Load+from+a+local+disk
[Load from a stream]: https://docs.groupdocs.com/display/metadatajava/Load+from+a+stream
[Load a file of a specific format]: https://docs.groupdocs.com/display/metadatajava/Load+a+file+of+a+specific+format
[Load a password-protected document]: https://docs.groupdocs.com/display/metadatajava/Load+a+password-protected+document |

### Metadata(InputStream document) {#Metadata-java.io.InputStream-}
```
public Metadata(InputStream document)
```


Initializes a new instance of the  Metadata  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | A stream that contains the document to load.

**Learn more**

 *  [Load from a local disk][]
 *  [Load from a stream][]
 *  [Load a file of a specific format][]
 *  [Load a password-protected document][]

This example demonstrates how to load a file from a stream.

> ```
> ```
> 
>  // Constants.InputDoc is an absolute or relative path to your document. Ex: @"C:\Docs\source.doc"
>  try (InputStream stream = new FileInputStream(Constants.InputDoc)) {
>      try (Metadata metadata = new Metadata(stream)) {
>          // Extract, edit or remove metadata here
>      }
>  }
>  
> ```
> ```


[Load from a local disk]: https://docs.groupdocs.com/display/metadatajava/Load+from+a+local+disk
[Load from a stream]: https://docs.groupdocs.com/display/metadatajava/Load+from+a+stream
[Load a file of a specific format]: https://docs.groupdocs.com/display/metadatajava/Load+a+file+of+a+specific+format
[Load a password-protected document]: https://docs.groupdocs.com/display/metadatajava/Load+a+password-protected+document |

### Metadata(String filePath, LoadOptions loadOptions) {#Metadata-java.lang.String-com.groupdocs.metadata.options.LoadOptions-}
```
public Metadata(String filePath, LoadOptions loadOptions)
```


Initializes a new instance of the  Metadata  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A string that contains the full name of the file from which to create a  Metadata  instance. |
| loadOptions | [LoadOptions](../../com.groupdocs.metadata.options/loadoptions) | Additional options to use when loading a document.

**Learn more**

 *  [Load from a local disk][]
 *  [Load from a stream][]
 *  [Load a file of a specific format][]
 *  [Load a password-protected document][]

This example demonstrates how to load a password-protected document.

> ```
> ```
> 
>  // Specify the password
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("123");
>  // Constants.ProtectedDocx is an absolute or relative path to your document. Ex: @"C:\Docs\source.docx"
>  try (Metadata metadata = new Metadata(Constants.ProtectedDocx, loadOptions)) {
>      // Extract, edit or remove metadata here
>  }
>  
> ```
> ```


[Load from a local disk]: https://docs.groupdocs.com/display/metadatajava/Load+from+a+local+disk
[Load from a stream]: https://docs.groupdocs.com/display/metadatajava/Load+from+a+stream
[Load a file of a specific format]: https://docs.groupdocs.com/display/metadatajava/Load+a+file+of+a+specific+format
[Load a password-protected document]: https://docs.groupdocs.com/display/metadatajava/Load+a+password-protected+document |

### Metadata(InputStream document, LoadOptions loadOptions) {#Metadata-java.io.InputStream-com.groupdocs.metadata.options.LoadOptions-}
```
public Metadata(InputStream document, LoadOptions loadOptions)
```


Initializes a new instance of the  Metadata  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | A stream that contains the document to load. |
| loadOptions | [LoadOptions](../../com.groupdocs.metadata.options/loadoptions) | Additional options to use when loading a document.

**Learn more**

 *  [Load from a local disk][]
 *  [Load from a stream][]
 *  [Load a file of a specific format][]
 *  [Load a password-protected document][]


[Load from a local disk]: https://docs.groupdocs.com/display/metadatajava/Load+from+a+local+disk
[Load from a stream]: https://docs.groupdocs.com/display/metadatajava/Load+from+a+stream
[Load a file of a specific format]: https://docs.groupdocs.com/display/metadatajava/Load+a+file+of+a+specific+format
[Load a password-protected document]: https://docs.groupdocs.com/display/metadatajava/Load+a+password-protected+document |

### getFileFormat() {#getFileFormat--}
```
public final FileFormat getFileFormat()
```


Gets the type of the loaded file (if recognized).

**Returns:**
[FileFormat](../../com.groupdocs.metadata.core/fileformat) - The type of the loaded file if recognized; otherwise,  F:GroupDocs.Metadata.FileFormat.Unknown .
### getRootPackage() {#getRootPackage--}
```
public final RootMetadataPackage getRootPackage()
```


Gets the root package providing access to all metadata properties extracted from the file.

**Returns:**
[RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage) - The root package providing access to all metadata properties extracted from the file.

**Learn more**

 *  [Traverse a whole metadata tree][]

This example demonstrates how to traverse the whole metadata tree for a specific file regardless of the format.

> ```
> ```
> 
>  public static void run() {
>      try (Metadata metadata = new Metadata(Constants.JpegWithXmp)) {
>          displayMetadataTree(metadata.getRootPackage(), 0);
>      }
>  }
>  private static void displayMetadataTree(MetadataPackage metadata, int indent) {
>      if (metadata != null) {
>          String stringMetadataType = String.valueOf(metadata.getMetadataType());
>          System.out.printf("%" + (stringMetadataType.length() + indent) + "s%n", stringMetadataType);
>          for (MetadataProperty property : metadata) {
>              String stringPropertyRepresentation = "Name: " + property.getName() + ", Value: " + property.getValue();
>              System.out.printf("%" + (stringPropertyRepresentation.length() + indent + 1) + "s%n", stringPropertyRepresentation);
>              if (property.getValue() != null) {
>                  switch (property.getValue().getType()) {
>                      case MetadataPropertyType.Metadata:
>                          displayMetadataTree(property.getValue().toClass(MetadataPackage.class), indent + 2);
>                      break;
>                      case MetadataPropertyType.MetadataArray:
>                          displayMetadataTree(property.getValue().toArray(MetadataPackage.class), indent + 2);
>                      break;
>                  }
>              }
>          }
>      }
>  }
>  private static void displayMetadataTree(MetadataPackage[] metadataArray, int indent) {
>      if (metadataArray != null) {
>          for (MetadataPackage metadata : metadataArray) {
>              displayMetadataTree(metadata, indent);
>          }
>      }
>  }
>  
> ```
> ```


[Traverse a whole metadata tree]: https://docs.groupdocs.com/display/metadatajava/Traverse+a+whole+metadata+tree
### <TRoot>getRootPackageGeneric() {#-TRoot-getRootPackageGeneric--}
```
public final TRoot <TRoot>getRootPackageGeneric()
```


Gets the root package providing access to all metadata properties extracted from the file.

**Learn more**

 *  [Traverse a whole metadata tree][]


[Traverse a whole metadata tree]: https://docs.groupdocs.com/display/metadatajava/Traverse+a+whole+metadata+tree

**Returns:**
TRoot - The root package providing access to all metadata properties extracted from the file.

 TRoot : The exact type of the root package.
### findProperties(Specification specification) {#findProperties-com.groupdocs.metadata.search.Specification-}
```
public final IReadOnlyList<MetadataProperty> findProperties(Specification specification)
```


Finds the metadata properties satisfying a specification. The search is recursive so it affects all nested packages as well.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| specification | [Specification](../../com.groupdocs.metadata.search/specification) | A function to test each metadata property for a condition.

**Learn more**

 *  More examples demonstrating usages of this method: [Extracting metadata][]

This example demonstrates how to search for specific metadata properties using tags.

> ```
> ```
> 
>  // Constants.InputPptx is an absolute or relative path to your document. Ex: @"C:\Docs\source.pptx"
>  try (Metadata metadata = new Metadata(Constants.InputPptx)) {
>      // Fetch all the properties satisfying the predicate:
>      // property contains the name of the last document editor OR the date/time the document was last modified
>      IReadOnlyList properties = metadata.findProperties(
>              new ContainsTagSpecification(Tags.getPerson().getEditor()).or(new ContainsTagSpecification(Tags.getTime().getModified())));
>      for (MetadataProperty property : properties) {
>          System.out.println(String.format("Property name: %s, Property value: %s", property.getName(), property.getValue()));
>      }
>  }
>  
> ```
> ```


[Extracting metadata]: https://docs.groupdocs.com/display/metadatajava/Extracting+metadata |

**Returns:**
[IReadOnlyList](../../com.groupdocs.metadata.core/ireadonlylist) - A collection that contains properties from the package that satisfy the condition.
### updateProperties(Specification specification, PropertyValue value) {#updateProperties-com.groupdocs.metadata.search.Specification-com.groupdocs.metadata.core.PropertyValue-}
```
public final int updateProperties(Specification specification, PropertyValue value)
```


Updates known metadata properties satisfying a specification. The operation is recursive so it affects all nested packages as well.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| specification | [Specification](../../com.groupdocs.metadata.search/specification) | A specification to test each metadata property for a condition. |
| value | [PropertyValue](../../com.groupdocs.metadata.core/propertyvalue) | A new value for the filtered properties.

--------------------

Please note that GroupDocs.Metadata implicitly checks the type of each filtered property. It's impossible to update a property with a value having an inappropriate type.

**Learn more**

 *  More examples demonstrating usages of this method: [Updating metadata][]

This example demonstrates how to update existing metadata properties by various criteria regardless of the file format.

> ```
> ```
> 
>  public class UpdatingMetadata {
>      public static void run() {
>          Date threeDaysAgo = new Date(System.currentTimeMillis() - TimeUnit.DAYS.toMillis(3));
>          File folder = new File(Constants.InputPath);
>          for (File file : folder.listFiles()) {
>              try (Metadata metadata = new Metadata(file.getAbsolutePath())) {
>                  if (metadata.getFileFormat() != FileFormat.Unknown && !metadata.getDocumentInfo().isEncrypted()) {
>                      System.out.println();
>                      System.out.println(file.getName());
>                      // Update the file creation date/time if the existing value is older than 3 days
>                      int affected = metadata.updateProperties(new ContainsTagSpecification(Tags.getTime().getCreated()).and(
>                              new OfTypeSpecification(MetadataPropertyType.DateTime)).and(
>                              new UpdatingMetadata().new DateBeforeSpecification(threeDaysAgo)), new PropertyValue(new Date()));
>                      System.out.println(String.format("Affected properties: %s", affected));
>                      metadata.save(Constants.OutputPath + "output." + FilenameUtils.getExtension(file.getName()));
>                  }
>              }
>          }
>      }
>      // Define your own specifications to filter metadata properties
>      public class DateBeforeSpecification extends Specification {
>          public DateBeforeSpecification(Date date) {
>              setValue(date);
>          }
> 
>          public final Date getValue() {
>              return auto_Value;
>          }
> 
>          private void setValue(Date value) {
>              auto_Value = value;
>          }
> 
>          private Date auto_Value;
> 
>          public boolean isSatisfiedBy(MetadataProperty candidate) {
>              Date date = candidate.getValue().toClass(Date.class);
>              if (date != null) {
>                  return date.before(getValue());
>              }
>              return false;
>          }
>      }
>  }
>  
> ```
> ```


[Updating metadata]: https://docs.groupdocs.com/display/metadatajava/Updating+metadata |

**Returns:**
int - The number of affected properties.
### removeProperties(Specification specification) {#removeProperties-com.groupdocs.metadata.search.Specification-}
```
public final int removeProperties(Specification specification)
```


Removes metadata properties satisfying a specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| specification | [Specification](../../com.groupdocs.metadata.search/specification) | A specification to test each metadata property for a condition.

**Learn more**

 *  More examples demonstrating usages of this method: [Removing metadata][]

This example demonstrates how to remove specific metadata properties using various criteria.

> ```
> ```
> 
>  public class RemoveMetadataProperties {
>      public static void run() {
>          // Constants.InputDocx is an absolute or relative path to your document. Ex: @"C:\Docs\source.docx"
>          try (Metadata metadata = new Metadata(Constants.InputDocx)) {
> 
>              // Remove all the properties satisfying the predicate:
>              // property contains the name of the document author OR
>              // it refers to the last editor OR
>              // the property value is a string that is equal to the given string "John" (to remove any mentions of John from the detected metadata)
>              int affected = metadata.removeProperties(
>                      new ContainsTagSpecification(Tags.getPerson().getCreator()).or(
>                              new ContainsTagSpecification(Tags.getPerson().getEditor())).or(
>                              new OfTypeSpecification(MetadataPropertyType.String).and(new RemoveMetadataProperties().new WithValueSpecification("John"))));
> 
>              System.out.println(String.format("Properties removed: %s", affected));
> 
>              metadata.save(Constants.OutputDocx);
>          }
>      }
> 
>      // Define your own specifications to filter metadata properties
>      public class WithValueSpecification extends Specification {
>          public WithValueSpecification(Object value) {
>              setValue(value);
>          }
> 
>          public final Object getValue() {
>              return auto_Value;
>          }
> 
>          private void setValue(Object value) {
>              auto_Value = value;
>          }
> 
>          private Object auto_Value;
> 
>          public boolean isSatisfiedBy(MetadataProperty candidate) {
>              return candidate.getValue().getRawValue().equals(getValue());
>          }
>      }
>  }
>  
> ```
> ```


[Removing metadata]: https://docs.groupdocs.com/display/metadatajava/Removing+metadata |

**Returns:**
int - The number of affected properties.
### addProperties(Specification specification, PropertyValue value) {#addProperties-com.groupdocs.metadata.search.Specification-com.groupdocs.metadata.core.PropertyValue-}
```
public final int addProperties(Specification specification, PropertyValue value)
```


Adds known metadata properties satisfying the specification. The operation is recursive so it affects all nested packages as well.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| specification | [Specification](../../com.groupdocs.metadata.search/specification) | A specification to test each metadata property for a condition. |
| value | [PropertyValue](../../com.groupdocs.metadata.core/propertyvalue) | A value for the picked properties.

**Learn more**

 *  More examples demonstrating usages of this method: [Adding metadata][]

This example demonstrates how to add some missing metadata properties to a file regardless of its format.

> ```
> ```
> 
>  File folder = new File(Constants.InputPath);
>  for (File file : folder.listFiles()) {
>      try (Metadata metadata = new Metadata(file.getAbsolutePath())) {
>          if (metadata.getFileFormat() != FileFormat.Unknown && !metadata.getDocumentInfo().isEncrypted()) {
>              System.out.println();
>              System.out.println(file.getName());
>              // Add a property containing the file last printing date if it's missing
>              // Note that the property will be added to metadata packages that satisfy the following criteria:
>              // 1) Only existing metadata packages will be affected. No new packages are added during this operation
>              // 2) There should be a known metadata property in the package structure that fits the search condition but is actually missing in the package.
>              // All properties supported by a certain package are usually defined in the specification of a particular metadata standard
>              int affected = metadata.addProperties(new ContainsTagSpecification(Tags.getTime().getPrinted()), new PropertyValue(new Date()));
>              System.out.println(String.format("Affected properties: %s", affected));
>              metadata.save(Constants.OutputPath + "output." + FilenameUtils.getExtension(file.getName()));
>          }
>      }
>  }
>  
> ```
> ```


[Adding metadata]: https://docs.groupdocs.com/display/metadatajava/Adding+metadata |

**Returns:**
int - The number of affected properties.
### setProperties(Specification specification, PropertyValue value) {#setProperties-com.groupdocs.metadata.search.Specification-com.groupdocs.metadata.core.PropertyValue-}
```
public final int setProperties(Specification specification, PropertyValue value)
```


Sets known metadata properties satisfying the specification. The operation is recursive so it affects all nested packages as well. This method is a combination of  AddProperties  and  UpdateProperties . If an existing property satisfies the specification its value is updated. If there is a known property missing in the package that satisfies the specification it is added to the package.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| specification | [Specification](../../com.groupdocs.metadata.search/specification) | A specification to test each metadata property for a condition. |
| value | [PropertyValue](../../com.groupdocs.metadata.core/propertyvalue) | A new value for the filtered properties.

--------------------

Please note that GroupDocs.Metadata implicitly checks the type of each filtered property. It's impossible to set a property with a value having inappropriate type.

**Learn more**

 *  More examples demonstrating usages of this method: [Set metadata properties][]

This example demonstrates how to set specific metadata properties using different criteria.

> ```
> ```
> 
>  // Constants.InputVsdx is an absolute or relative path to your document. Ex: @"C:\Docs\source.vsdx"
>  try (Metadata metadata = new Metadata(Constants.InputVsdx)) {
>      // Set the value of each property that satisfies the predicate:
>      // property contains the date/time the document was created OR modified
>      int affected = metadata.setProperties(
>              new ContainsTagSpecification(Tags.getTime().getCreated()).or(new ContainsTagSpecification(Tags.getTime().getModified())),
>              new PropertyValue(new Date()));
>      System.out.println(String.format("Properties set: %s", affected));
>      metadata.save(Constants.OutputVsdx);
>  }
>  
> ```
> ```


[Set metadata properties]: https://docs.groupdocs.com/display/metadatajava/Set+metadata+properties |

**Returns:**
int - The number of affected properties.
### sanitize() {#sanitize--}
```
public final int sanitize()
```


Removes writable metadata properties from all detected packages or whole packages if possible. The operation is recursive so it affects all nested packages as well.

**Returns:**
int - The number of affected properties.

**Learn more**

 *  More examples demonstrating usages of this method: [Clean metadata][]

This example demonstrates how to remove all detected metadata packages/properties from a file.

> ```
> ```
> 
>  // Constants.InputPdf is an absolute or relative path to your document. Ex: @"C:\Docs\source.pdf"
>  try (Metadata metadata = new Metadata(Constants.InputPdf)) {
>      // Remove detected metadata packages
>      int affected = metadata.sanitize();
>      System.out.println(String.format("Properties removed: %s", affected));
>      metadata.save(Constants.OutputPdf);
>  }
>  
> ```
> ```


[Clean metadata]: https://docs.groupdocs.com/display/metadatajava/Clean+metadata
### save() {#save--}
```
public final void save()
```


Saves all changes made in the loaded document.

**Learn more**

 *  [Save a modified file to the original source][]
 *  [Save a modified file to a specified location][]
 *  [Save a modified file to a stream][]

This example shows how to save the modified content to the underlying file.

> ```
> ```
> 
>  // Constants.InputPpt is an absolute or relative path to your document. Ex: @"C:\Docs\test.ppt"
>  File outputFile = new File(Constants.OutputPpt);
>  outputFile.delete();
>  Files.copy(new File(Constants.InputPpt).toPath(), outputFile.toPath());
>  try (Metadata metadata = new Metadata(Constants.OutputPpt)) {
>      // Edit or remove metadata here
>      // Saves the document to the underlying file
>      metadata.save();
>  }
>  
> ```
> ```


[Save a modified file to the original source]: https://docs.groupdocs.com/display/metadatajava/Save+a+modified+file+to+the+original+source
[Save a modified file to a specified location]: https://docs.groupdocs.com/display/metadatajava/Save+a+modified+file+to+a+specified+location
[Save a modified file to a stream]: https://docs.groupdocs.com/display/metadatajava/Save+a+modified+file+to+a+stream

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Saves the document content into a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | An output stream for the document.

**Learn more**

 *  [Save a modified file to the original source][]
 *  [Save a modified file to a specified location][]
 *  [Save a modified file to a stream][]

This example shows how to save a document to the specified stream.

> ```
> ```
> 
>  try (OutputStream stream = new FileOutputStream(Constants.OutputPng)) {
>      // Constants.InputPng is an absolute or relative path to your document. Ex: @"C:\Docs\test.png"
>      try (Metadata metadata = new Metadata(Constants.InputPng)) {
>          // Edit or remove metadata here
>          metadata.save(stream);
>      }
>  }
>  
> ```
> ```


[Save a modified file to the original source]: https://docs.groupdocs.com/display/metadatajava/Save+a+modified+file+to+the+original+source
[Save a modified file to a specified location]: https://docs.groupdocs.com/display/metadatajava/Save+a+modified+file+to+a+specified+location
[Save a modified file to a stream]: https://docs.groupdocs.com/display/metadatajava/Save+a+modified+file+to+a+stream |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Saves the document content to the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The full name of the output file.

**Learn more**

 *  [Save a modified file to the original source][]
 *  [Save a modified file to a specified location][]
 *  [Save a modified file to a stream][]

This example shows how to save a document to the specified location.

> ```
> ```
> 
>  // Constants.InputJpeg is an absolute or relative path to your document. Ex: @"C:\Docs\test.jpg"
>  try (Metadata metadata = new Metadata(Constants.InputJpeg)) {
>      // Edit or remove metadata here
>      metadata.save(Constants.OutputJpeg);
>  }
>  
> ```
> ```


[Save a modified file to the original source]: https://docs.groupdocs.com/display/metadatajava/Save+a+modified+file+to+the+original+source
[Save a modified file to a specified location]: https://docs.groupdocs.com/display/metadatajava/Save+a+modified+file+to+a+specified+location
[Save a modified file to a stream]: https://docs.groupdocs.com/display/metadatajava/Save+a+modified+file+to+a+stream |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.metadata.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Creates preview images for specified pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.metadata.options/previewoptions) | A set of options for preview generation.

**Learn more**

 *  [Generate document preview][]


[Generate document preview]: https://docs.groupdocs.com/display/metadatajava/Generate+document+preview |

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Gets common information about the loaded document.

**Returns:**
[IDocumentInfo](../../com.groupdocs.metadata.core/idocumentinfo) - An object representing common document information.

**Learn more**

 *  [Get document info][]


[Get document info]: https://docs.groupdocs.com/display/metadatajava/Get+document+info
### close() {#close--}
```
public void close()
```


Closes the loaded document and releases any system resources associated with it.

