---
title: SequenceSetField
second_title: Aspose.Email for Java API Reference
description:  Defines set of values for selected field to search.
type: docs
weight: 627
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
| [getValues()](#getValues--) | Gets values to search |
| [add(SequenceSetBaseValue value)](#add-com.aspose.email.SequenceSetBaseValue-) | Adds value to search. |
| [to_MailQuery(SequenceSetField seqSetField)](#to-MailQuery-com.aspose.email.SequenceSetField-) | Creates the search key. |
| [createQuery()](#createQuery--) | Creates the search key. |
| [toString()](#toString--) | Returns a String which represents the object instance. |
### getValues() {#getValues--}
```
public final SequenceSetBaseValue[] getValues()
```


Gets values to search

**Returns:**
com.aspose.email.SequenceSetBaseValue[]
### add(SequenceSetBaseValue value) {#add-com.aspose.email.SequenceSetBaseValue-}
```
public final void add(SequenceSetBaseValue value)
```


Adds value to search.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SequenceSetBaseValue](../../com.aspose.email/sequencesetbasevalue) | Value to search |

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


Returns a String which represents the object instance.

**Returns:**
java.lang.String - Returns a string which represents the object instance.
