---
title: SequenceSetField
second_title: Aspose.Email for Java API Reference
description: Defines set of values for selected field to search.
type: docs
weight: 635
url: /java/com.aspose.email/sequencesetfield/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.QueryField](../../com.aspose.email/queryfield)
```
public class SequenceSetField extends QueryField
```

Defines set of values for selected field to search.
## Methods

| Method | Description |
| --- | --- |
| [add(SequenceSetBaseValue value)](#add-com.aspose.email.SequenceSetBaseValue-) | Adds value to search. |
| [createQuery()](#createQuery--) | Creates the search key. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getValues()](#getValues--) | Gets values to search |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returns a String which represents the object instance. |
| [to_MailQuery(SequenceSetField seqSetField)](#to-MailQuery-com.aspose.email.SequenceSetField-) | Creates the search key. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(SequenceSetBaseValue value) {#add-com.aspose.email.SequenceSetBaseValue-}
```
public final void add(SequenceSetBaseValue value)
```


Adds value to search.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SequenceSetBaseValue](../../com.aspose.email/sequencesetbasevalue) | Value to search |

### createQuery() {#createQuery--}
```
public final MailQuery createQuery()
```


Creates the search key.

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getValues() {#getValues--}
```
public final SequenceSetBaseValue[] getValues()
```


Gets values to search

**Returns:**
com.aspose.email.SequenceSetBaseValue[]
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




### toString() {#toString--}
```
public String toString()
```


Returns a String which represents the object instance.

**Returns:**
java.lang.String - Returns a string which represents the object instance.
### to_MailQuery(SequenceSetField seqSetField) {#to-MailQuery-com.aspose.email.SequenceSetField-}
```
public static MailQuery to_MailQuery(SequenceSetField seqSetField)
```


Creates the search key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seqSetField | [SequenceSetField](../../com.aspose.email/sequencesetfield) | SequenceSet object instance |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query.
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

