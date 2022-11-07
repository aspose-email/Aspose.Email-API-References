---
title: ESearchOptions
second_title: Aspose.Email for Java API Reference
description: ESEARCH Result Options This method works only if server supports ESEARCH extension.
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
| [createQuery()](#createQuery--) | Creates the search key. |
| [createQuery(MailQueryBuilder owner)](#createQuery-com.aspose.email.MailQueryBuilder-) | Creates the search key. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMax()](#getMax--) | Return the highest message |
| [getMin()](#getMin--) | Return the lowest message |
| [getNotDefined()](#getNotDefined--) | Not defined |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(ESearchOptions val1, ESearchOptions val2)](#op-Addition-com.aspose.email.ESearchOptions-com.aspose.email.ESearchOptions-) | Plus operation is defined |
| [op_Equality(ESearchOptions val1, ESearchOptions val2)](#op-Equality-com.aspose.email.ESearchOptions-com.aspose.email.ESearchOptions-) | Equel operation is defined |
| [op_Inequality(ESearchOptions val1, ESearchOptions val2)](#op-Inequality-com.aspose.email.ESearchOptions-com.aspose.email.ESearchOptions-) | Not equel operation is defined |
| [op_Subtraction(ESearchOptions val1, ESearchOptions val2)](#op-Subtraction-com.aspose.email.ESearchOptions-com.aspose.email.ESearchOptions-) | Minus operation is defined |
| [toString()](#toString--) | String representation of an object |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createQuery() {#createQuery--}
```
public final MailQuery createQuery()
```


Creates the search key.

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMax() {#getMax--}
```
public static ESearchOptions getMax()
```


Return the highest message

**Returns:**
[ESearchOptions](../../com.aspose.email/esearchoptions)
### getMin() {#getMin--}
```
public static ESearchOptions getMin()
```


Return the lowest message

**Returns:**
[ESearchOptions](../../com.aspose.email/esearchoptions)
### getNotDefined() {#getNotDefined--}
```
public static ESearchOptions getNotDefined()
```


Not defined

**Returns:**
[ESearchOptions](../../com.aspose.email/esearchoptions)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
### toString() {#toString--}
```
public String toString()
```


String representation of an object

**Returns:**
java.lang.String - string representation of an object
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

