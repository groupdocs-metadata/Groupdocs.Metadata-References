---
title: IReadOnlyList
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a read-only collection of elements that can be accessed by index.
type: docs
weight: 359
url: /java/com.groupdocs.metadata.core/ireadonlylist/
---
**All Implemented Interfaces:**
java.lang.Iterable
```
public interface IReadOnlyList<T> extends Iterable<T>
```

Represents a read-only collection of elements that can be accessed by index.

 T : The type of elements in the read-only list.
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Gets the number of elements contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index in the read-only list. |
| [indexOf(T item)](#indexOf-T-) | Determines the index of a specific item in the collection. |
| [contains(T item)](#contains-T-) | Determines whether the collection contains a specific item. |
| [contains(TagCategory item)](#contains-com.groupdocs.metadata.tagging.TagCategory-) | Determines whether the collection contains a TagCategory item. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Gets the number of elements contained in the collection.

**Returns:**
int - The number of elements contained in the collection.
### get_Item(int index) {#get-Item-int-}
```
public abstract T get_Item(int index)
```


Gets the element at the specified index in the read-only list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to get. |

**Returns:**
T - The element at the specified index in the read-only list.
### indexOf(T item) {#indexOf-T-}
```
public abstract int indexOf(T item)
```


Determines the index of a specific item in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | T | The item to locate in the collection. |

**Returns:**
int - The index of  item  if found in the collection; otherwise, -1.
### contains(T item) {#contains-T-}
```
public abstract boolean contains(T item)
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
public abstract boolean contains(TagCategory item)
```


Determines whether the collection contains a TagCategory item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [TagCategory](../../com.groupdocs.metadata.tagging/tagcategory) | The item to locate in the collection. |

**Returns:**
boolean - True if the item is found in the collection; otherwise, false.
