---
title: ExcelExportOptions
second_title: GroupDocs.Signature for Java API Reference
description: Creates an export options of excel file.
type: docs
weight: 10
url: /java/com.groupdocs.metadata.export/excelexportoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.export.ExportOptions](../../com.groupdocs.metadata.export/exportoptions)
```
public class ExcelExportOptions extends ExportOptions
```

Creates an export options of excel file.
## Constructors

| Constructor | Description |
| --- | --- |
| [ExcelExportOptions()](#ExcelExportOptions--) | Initializes a new instance of the [ExcelExportOptions](../../com.groupdocs.metadata.export/excelexportoptions) class. |
| [ExcelExportOptions(boolean groupCells)](#ExcelExportOptions-boolean-) | Initializes a new instance of the [ExcelExportOptions](../../com.groupdocs.metadata.export/excelexportoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getGroupCells()](#getGroupCells--) | This flag determines whether it is necessary to group rows when exporting to Excel format |
| [setGroupCells(boolean value)](#setGroupCells-boolean-) | This flag determines whether it is necessary to group rows when exporting to Excel format |
### ExcelExportOptions() {#ExcelExportOptions--}
```
public ExcelExportOptions()
```


Initializes a new instance of the [ExcelExportOptions](../../com.groupdocs.metadata.export/excelexportoptions) class.

### ExcelExportOptions(boolean groupCells) {#ExcelExportOptions-boolean-}
```
public ExcelExportOptions(boolean groupCells)
```


Initializes a new instance of the [ExcelExportOptions](../../com.groupdocs.metadata.export/excelexportoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| groupCells | boolean | Group flag. |

### getGroupCells() {#getGroupCells--}
```
public final boolean getGroupCells()
```


This flag determines whether it is necessary to group rows when exporting to Excel format

Value: If the flag is true, the lines will be grouped, otherwise not

**Returns:**
boolean
### setGroupCells(boolean value) {#setGroupCells-boolean-}
```
public final void setGroupCells(boolean value)
```


This flag determines whether it is necessary to group rows when exporting to Excel format

Value: If the flag is true, the lines will be grouped, otherwise not

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

