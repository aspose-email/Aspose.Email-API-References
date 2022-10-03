---
title: SortingKey
second_title: Aspose.Email for Java API Reference
description: Sort criterias for SORT command  See more https//tools.ietf.org/html/rfc5256
type: docs
weight: 644
url: /java/com.aspose.email/sortingkey/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SortingKey extends System.Enum
```

Sort criterias for "SORT" command See more: https://tools.ietf.org/html/rfc5256
## Fields

| Field | Description |
| --- | --- |
| [Arrival](#Arrival) | By internal date and time of the message. |
| [Cc](#Cc) | By first "cc" address. |
| [Date](#Date) | By sent date and time. |
| [From](#From) | By first "From" address. |
| [Size](#Size) | By size of the message in octets. |
| [Subject](#Subject) | By subject |
| [To](#To) | By first "To" address. |
### Arrival {#Arrival}
```
public static final int Arrival
```


By internal date and time of the message. This differs from the ON criteria in SEARCH, which uses just the internal date.

### Cc {#Cc}
```
public static final int Cc
```


By first "cc" address.

### Date {#Date}
```
public static final int Date
```


By sent date and time.

### From {#From}
```
public static final int From
```


By first "From" address.

### Size {#Size}
```
public static final int Size
```


By size of the message in octets.

### Subject {#Subject}
```
public static final int Subject
```


By subject

### To {#To}
```
public static final int To
```


By first "To" address.

