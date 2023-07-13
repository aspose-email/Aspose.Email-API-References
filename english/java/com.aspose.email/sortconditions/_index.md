---
title: SortConditions
second_title: Aspose.Email for Java API Reference
description: Provides the search conditions for the SORT extension.
type: docs
weight: 651
url: /java/com.aspose.email/sortconditions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.BaseSearchConditions](../../com.aspose.email/basesearchconditions)
```
public final class SortConditions extends BaseSearchConditions
```

Provides the search conditions for the SORT extension. Compatibles with SORT IMAP extension described at https://tools.ietf.org/html/rfc5256
## Constructors

| Constructor | Description |
| --- | --- |
| [SortConditions()](#SortConditions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCharset()](#getCharset--) | Gets or sets charset. |
| [getClass()](#getClass--) |  |
| [getReverseBy()](#getReverseBy--) | Gets or sets reverse sort criteria Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order. |
| [getSince()](#getSince--) | Gets or sets the message date since which the search criteria matches. |
| [getSortBy()](#getSortBy--) | Gets or sets sort criteria |
| [getText()](#getText--) | Gets or sets subject text. |
| [getUseUId()](#getUseUId--) | Gets or sets a value indicating whether the search method returns sequence numbers or UIDs of messages. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCharset(String value)](#setCharset-java.lang.String-) | Gets or sets charset. |
| [setReverseBy(int value)](#setReverseBy-int-) | Gets or sets reverse sort criteria Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order. |
| [setSince(Date value)](#setSince-java.util.Date-) | Gets or sets the message date since which the search criteria matches. |
| [setSortBy(int value)](#setSortBy-int-) | Gets or sets sort criteria |
| [setText(String value)](#setText-java.lang.String-) | Gets or sets subject text. |
| [setUseUId(boolean value)](#setUseUId-boolean-) | Gets or sets a value indicating whether the search method returns sequence numbers or UIDs of messages. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SortConditions() {#SortConditions--}
```
public SortConditions()
```


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
### getCharset() {#getCharset--}
```
public final String getCharset()
```


Gets or sets charset. Indicates the charset of the strings that appear in the searching criteria.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getReverseBy() {#getReverseBy--}
```
public final int getReverseBy()
```


Gets or sets reverse sort criteria Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order. Note: REVERSE only reverses a single criterion, and does not affect the implicit "sequence number" sort criterion if all other criteria are identical. Consequently, a sort of REVERSE SUBJECT is not the same as a reverse ordering of a SUBJECT sort. This can be avoided by use of additional criteria, e.g., SUBJECT DATE vs. REVERSE SUBJECT REVERSE DATE. In general, however, it's better (and faster, if the client has a "reverse current ordering" command) to reverse the results in the client instead of issuing a new SORT.

**Returns:**
int
### getSince() {#getSince--}
```
public final Date getSince()
```


Gets or sets the message date since which the search criteria matches.

**Returns:**
java.util.Date
### getSortBy() {#getSortBy--}
```
public final int getSortBy()
```


Gets or sets sort criteria

**Returns:**
int
### getText() {#getText--}
```
public final String getText()
```


Gets or sets subject text.

**Returns:**
java.lang.String
### getUseUId() {#getUseUId--}
```
public final boolean getUseUId()
```


Gets or sets a value indicating whether the search method returns sequence numbers or UIDs of messages.

**Returns:**
boolean
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




### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


Gets or sets charset. Indicates the charset of the strings that appear in the searching criteria.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setReverseBy(int value) {#setReverseBy-int-}
```
public final void setReverseBy(int value)
```


Gets or sets reverse sort criteria Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order. Note: REVERSE only reverses a single criterion, and does not affect the implicit "sequence number" sort criterion if all other criteria are identical. Consequently, a sort of REVERSE SUBJECT is not the same as a reverse ordering of a SUBJECT sort. This can be avoided by use of additional criteria, e.g., SUBJECT DATE vs. REVERSE SUBJECT REVERSE DATE. In general, however, it's better (and faster, if the client has a "reverse current ordering" command) to reverse the results in the client instead of issuing a new SORT.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSince(Date value) {#setSince-java.util.Date-}
```
public final void setSince(Date value)
```


Gets or sets the message date since which the search criteria matches.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setSortBy(int value) {#setSortBy-int-}
```
public final void setSortBy(int value)
```


Gets or sets sort criteria

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Gets or sets subject text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setUseUId(boolean value) {#setUseUId-boolean-}
```
public final void setUseUId(boolean value)
```


Gets or sets a value indicating whether the search method returns sequence numbers or UIDs of messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

