---
title: ESearchOptions
second_title: Aspose.Email for Java API Reference
description:  ESEARCH Result Options
 This method works only if server supports ESEARCH extension.
type: docs
weight: 162
url: /java/com.aspose.email/esearchoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.QueryField](../../com.aspose.email/queryfield)
```
public class ESearchOptions extends QueryField
```

ESEARCH Result Options This method works only if server supports ESEARCH extension. Please, read more https://tools.ietf.org/html/rfc4315
## Methods

| Method | Description |
| --- | --- |
| [getNotDefined()](#getNotDefined--) | Not defined |
| [getMin()](#getMin--) | Return the lowest message |
| [getMax()](#getMax--) | Return the highest message |
| [op_Addition(ESearchOptions val1, ESearchOptions val2)](#op-Addition-com.aspose.email.ESearchOptions-com.aspose.email.ESearchOptions-) | Plus operation is defined |
| [op_Subtraction(ESearchOptions val1, ESearchOptions val2)](#op-Subtraction-com.aspose.email.ESearchOptions-com.aspose.email.ESearchOptions-) | Minus operation is defined |
| [op_Equality(ESearchOptions val1, ESearchOptions val2)](#op-Equality-com.aspose.email.ESearchOptions-com.aspose.email.ESearchOptions-) | Equel operation is defined |
| [op_Inequality(ESearchOptions val1, ESearchOptions val2)](#op-Inequality-com.aspose.email.ESearchOptions-com.aspose.email.ESearchOptions-) | Not equel operation is defined |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [createQuery(MailQueryBuilder owner)](#createQuery-com.aspose.email.MailQueryBuilder-) | Creates the search key. |
| [createQuery()](#createQuery--) | Creates the search key. |
| [toString()](#toString--) | String representation of an object |
### getNotDefined() {#getNotDefined--}
```
public static ESearchOptions getNotDefined()
```


Not defined

**Returns:**
[ESearchOptions](../../com.aspose.email/esearchoptions)
### getMin() {#getMin--}
```
public static ESearchOptions getMin()
```


Return the lowest message

**Returns:**
[ESearchOptions](../../com.aspose.email/esearchoptions)
### getMax() {#getMax--}
```
public static ESearchOptions getMax()
```


Return the highest message

**Returns:**
[ESearchOptions](../../com.aspose.email/esearchoptions)
### op_Addition(ESearchOptions val1, ESearchOptions val2) {#op-Addition-com.aspose.email.ESearchOptions-com.aspose.email.ESearchOptions-}
```
public static ESearchOptions op_Addition(ESearchOptions val1, ESearchOptions val2)
```


Plus operation is defined

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| val1 | [ESearchOptions](../../com.aspose.email/esearchoptions) |  |
| val2 | [ESearchOptions](../../com.aspose.email/esearchoptions) |  |

**Returns:**
[ESearchOptions](../../com.aspose.email/esearchoptions)
### op_Subtraction(ESearchOptions val1, ESearchOptions val2) {#op-Subtraction-com.aspose.email.ESearchOptions-com.aspose.email.ESearchOptions-}
```
public static ESearchOptions op_Subtraction(ESearchOptions val1, ESearchOptions val2)
```


Minus operation is defined

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| val1 | [ESearchOptions](../../com.aspose.email/esearchoptions) |  |
| val2 | [ESearchOptions](../../com.aspose.email/esearchoptions) |  |

**Returns:**
[ESearchOptions](../../com.aspose.email/esearchoptions)
### op_Equality(ESearchOptions val1, ESearchOptions val2) {#op-Equality-com.aspose.email.ESearchOptions-com.aspose.email.ESearchOptions-}
```
public static boolean op_Equality(ESearchOptions val1, ESearchOptions val2)
```


Equel operation is defined

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| val1 | [ESearchOptions](../../com.aspose.email/esearchoptions) |  |
| val2 | [ESearchOptions](../../com.aspose.email/esearchoptions) |  |

**Returns:**
boolean - 
### op_Inequality(ESearchOptions val1, ESearchOptions val2) {#op-Inequality-com.aspose.email.ESearchOptions-com.aspose.email.ESearchOptions-}
```
public static boolean op_Inequality(ESearchOptions val1, ESearchOptions val2)
```


Not equel operation is defined

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| val1 | [ESearchOptions](../../com.aspose.email/esearchoptions) |  |
| val2 | [ESearchOptions](../../com.aspose.email/esearchoptions) |  |

**Returns:**
boolean - 
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean - 
### createQuery(MailQueryBuilder owner) {#createQuery-com.aspose.email.MailQueryBuilder-}
```
public final MailQuery createQuery(MailQueryBuilder owner)
```


Creates the search key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| owner | [MailQueryBuilder](../../com.aspose.email/mailquerybuilder) | owner |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query.
### createQuery() {#createQuery--}
```
public final MailQuery createQuery()
```


Creates the search key.

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query.
### toString() {#toString--}
```
public String toString()
```


String representation of an object

**Returns:**
java.lang.String - string representation of an object
