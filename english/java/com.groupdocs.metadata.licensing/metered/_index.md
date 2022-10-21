---
title: Metered
second_title: GroupDocs.Metadata for Java API Reference
description: Provides methods to set metered key.
type: docs
weight: 11
url: /java/com.groupdocs.metadata.licensing/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Provides methods to set metered key.
## Constructors

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) | Initializes a new instance of this class. |
## Methods

| Method | Description |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Sets metered public and private key. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Retrieves the amount of MBs processed. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Retrieves the count of credits consumed. |
### Metered() {#Metered--}
```
public Metered()
```


Initializes a new instance of this class.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Sets metered public and private key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | A public key. |
| privateKey | java.lang.String | A private key. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Retrieves the amount of MBs processed.

**Returns:**
double - A double value that represents the consumption quantity.
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Retrieves the count of credits consumed.

**Returns:**
double - A double value that represents the consumption credit.
