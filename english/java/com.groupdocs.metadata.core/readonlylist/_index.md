---
title: ReadOnlyList
second_title: GroupDocs.Metadata for Java API Reference
description: Provides an abstract base class for a strongly typed read-only list.
type: docs
weight: 223
url: /java/com.groupdocs.metadata.core/readonlylist/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.metadata.core.IReadOnlyList
```
public class ReadOnlyList<T> implements IReadOnlyList<T>
```

Provides an abstract base class for a strongly typed read-only list.

 T : The type of the element.
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Gets the number of elements contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index in the collection. |
| [contains(T item)](#contains-T-) | Determines whether the collection contains a specific item. |
| [contains(TagCategory item)](#contains-com.groupdocs.metadata.tagging.TagCategory-) | Determines whether the collection contains a TagCategory item. |
| [indexOf(T item)](#indexOf-T-) | Determines the index of a specific item in the collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through a collection. |
### getCount() {#getCount--}
```
public final int getCount()
```


Gets the number of elements contained in the collection.

**Returns:**
int - The number of elements contained in the collection.
### get_Item(int index) {#get-Item-int-}
```
public final T get_Item(int index)
```


Gets the element at the specified index in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to get. |

**Returns:**
T - The element at the specified index.
### contains(T item) {#contains-T-}
```
public final boolean contains(T item)
```


Determines whether the collection contains a specific item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | T | The item to locate in the collection. |

**Returns:**
boolean - True if the item is found in the collection; otherwise, false.
### contains(TagCategory item) {#contains-com.groupdocs.metadata.tagging.TagCategory-}
```
public final boolean contains(TagCategory item)
```


Determines whether the collection contains a TagCategory item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [TagCategory](../../com.groupdocs.metadata.tagging/tagcategory) | The item to locate in the collection. |

**Returns:**
boolean - True if the item is found in the collection; otherwise, false.
### indexOf(T item) {#indexOf-T-}
```
public final int indexOf(T item)
```


Determines the index of a specific item in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | T | The item to locate in the collection. |

**Returns:**
int - The index of  item  if found in the collection; otherwise, -1.
### iterator() {#iterator--}
```
public final Iterator<T> iterator()
```


Returns an enumerator that iterates through a collection.

**Returns:**
java.util.Iterator<T> - An  IEnumerator\{T\}  object that can be used to iterate through the collection.
