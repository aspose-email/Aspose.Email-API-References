---
title: SortConditions
second_title: Aspose.Email for Java API Reference
description:  Provides the search conditions for the SORT extension.
type: docs
weight: 643
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
| [getSortBy()](#getSortBy--) | Gets or sets sort criteria |
| [setSortBy(int value)](#setSortBy-int-) | Gets or sets sort criteria |
| [getReverseBy()](#getReverseBy--) | Gets or sets reverse sort criteria Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order. |
| [setReverseBy(int value)](#setReverseBy-int-) | Gets or sets reverse sort criteria Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order. |
### SortConditions() {#SortConditions--}
```
public SortConditions()
```


### getSortBy() {#getSortBy--}
```
public final int getSortBy()
```


Gets or sets sort criteria

**Returns:**
int
### setSortBy(int value) {#setSortBy-int-}
```
public final void setSortBy(int value)
```


Gets or sets sort criteria

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getReverseBy() {#getReverseBy--}
```
public final int getReverseBy()
```


Gets or sets reverse sort criteria Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order. Note: REVERSE only reverses a single criterion, and does not affect the implicit "sequence number" sort criterion if all other criteria are identical. Consequently, a sort of REVERSE SUBJECT is not the same as a reverse ordering of a SUBJECT sort. This can be avoided by use of additional criteria, e.g., SUBJECT DATE vs. REVERSE SUBJECT REVERSE DATE. In general, however, it's better (and faster, if the client has a "reverse current ordering" command) to reverse the results in the client instead of issuing a new SORT.

**Returns:**
int
### setReverseBy(int value) {#setReverseBy-int-}
```
public final void setReverseBy(int value)
```


Gets or sets reverse sort criteria Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order. Note: REVERSE only reverses a single criterion, and does not affect the implicit "sequence number" sort criterion if all other criteria are identical. Consequently, a sort of REVERSE SUBJECT is not the same as a reverse ordering of a SUBJECT sort. This can be avoided by use of additional criteria, e.g., SUBJECT DATE vs. REVERSE SUBJECT REVERSE DATE. In general, however, it's better (and faster, if the client has a "reverse current ordering" command) to reverse the results in the client instead of issuing a new SORT.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

