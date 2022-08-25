---
title: ModificationSequenceField
second_title: Aspose.Email for Java API Reference
description:  Defines set of values for selected field to search.
type: docs
weight: 515
url: /java/com.aspose.email/modificationsequencefield/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.QueryField](../../com.aspose.email/queryfield)
```
public class ModificationSequenceField extends QueryField
```

Defines set of values for selected field to search.
## Methods

| Method | Description |
| --- | --- |
| [getModificationSequence()](#getModificationSequence--) | Gets values to search |
| [greaterOrEqualTo(long modificationSequence)](#greaterOrEqualTo-long-) | Sets a value to search for messages that have modification sequence greater or equal to this value. |
| [createQuery()](#createQuery--) | Creates the search key. |
| [toString()](#toString--) | Returns a String which represents the object instance. |
### getModificationSequence() {#getModificationSequence--}
```
public final long getModificationSequence()
```


Gets values to search

**Returns:**
long
### greaterOrEqualTo(long modificationSequence) {#greaterOrEqualTo-long-}
```
public final void greaterOrEqualTo(long modificationSequence)
```


Sets a value to search for messages that have modification sequence greater or equal to this value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| modificationSequence | long | Value to search |

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
