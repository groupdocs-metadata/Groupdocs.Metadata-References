---
title: MetadataPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents base abstraction for a metadata package.
type: docs
weight: 159
url: /java/com.groupdocs.metadata.core/metadatapackage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class MetadataPackage implements Iterable<MetadataProperty>
```

Represents base abstraction for a metadata package.
## Methods

| Method | Description |
| --- | --- |
| [getMetadataType()](#getMetadataType--) | Gets the metadata type. |
| [getKeys()](#getKeys--) | Gets a collection of the metadata property names. |
| [get_Item(String propertyName)](#get-Item-java.lang.String-) | Gets the  MetadataProperty  with the specified name. |
| [getPropertyDescriptors()](#getPropertyDescriptors--) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [contains(String propertyName)](#contains-java.lang.String-) | Determines whether the package contains a metadata property with the specified name. |
| [getCount()](#getCount--) | Gets the number of metadata properties. |
| [findProperties(Specification specification)](#findProperties-com.groupdocs.metadata.search.Specification-) | Finds the metadata properties satisfying a specification. |
| [updateProperties(Specification specification, PropertyValue value)](#updateProperties-com.groupdocs.metadata.search.Specification-com.groupdocs.metadata.core.PropertyValue-) | Updates known metadata properties satisfying a specification. |
| [removeProperties(Specification specification)](#removeProperties-com.groupdocs.metadata.search.Specification-) | Removes metadata properties satisfying a specification. |
| [addProperties(Specification specification, PropertyValue value)](#addProperties-com.groupdocs.metadata.search.Specification-com.groupdocs.metadata.core.PropertyValue-) | Adds known metadata properties satisfying the specification. |
| [setProperties(Specification specification, PropertyValue value)](#setProperties-com.groupdocs.metadata.search.Specification-com.groupdocs.metadata.core.PropertyValue-) | Sets known metadata properties satisfying the specification. |
| [sanitize()](#sanitize--) | Removes writable metadata properties from the package. |
### getMetadataType() {#getMetadataType--}
```
public final MetadataType getMetadataType()
```


Gets the metadata type.

**Returns:**
[MetadataType](../../com.groupdocs.metadata.core/metadatatype) - The type of the metadata package.
### getKeys() {#getKeys--}
```
public final IReadOnlyList<String> getKeys()
```


Gets a collection of the metadata property names.

**Returns:**
[IReadOnlyList](../../com.groupdocs.metadata.core/ireadonlylist) - A collection of the metadata property names.
### get_Item(String propertyName) {#get-Item-java.lang.String-}
```
public final MetadataProperty get_Item(String propertyName)
```


Gets the  MetadataProperty  with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | The name of the metadata property to be found. Value: The appropriate  MetadataProperty . |

**Returns:**
[MetadataProperty](../../com.groupdocs.metadata.core/metadataproperty) - The  MetadataProperty  if found; otherwise, null.
### getPropertyDescriptors() {#getPropertyDescriptors--}
```
public final IReadOnlyList<PropertyDescriptor> getPropertyDescriptors()
```


Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine.

**Returns:**
[IReadOnlyList](../../com.groupdocs.metadata.core/ireadonlylist) - A collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine.
### iterator() {#iterator--}
```
public final Iterator<MetadataProperty> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
java.util.Iterator<com.groupdocs.metadata.core.MetadataProperty> - An enumerator that can be used to iterate through the collection.
### contains(String propertyName) {#contains-java.lang.String-}
```
public final boolean contains(String propertyName)
```


Determines whether the package contains a metadata property with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | The name of the property to locate in the package. |

**Returns:**
boolean - True if the package contains a property with the specified name; otherwise, false.
### getCount() {#getCount--}
```
public final int getCount()
```


Gets the number of metadata properties.

**Returns:**
int - The number or metadata properties.
### findProperties(Specification specification) {#findProperties-com.groupdocs.metadata.search.Specification-}
```
public IReadOnlyList<MetadataProperty> findProperties(Specification specification)
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
public int updateProperties(Specification specification, PropertyValue value)
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
public int removeProperties(Specification specification)
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
public int addProperties(Specification specification, PropertyValue value)
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
public int setProperties(Specification specification, PropertyValue value)
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
public int sanitize()
```


Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well.

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
