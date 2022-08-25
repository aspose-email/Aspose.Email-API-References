---
title: FreebusyGroupInfo
second_title: Aspose.Email for Java API Reference
description:  Specifies list of calendars that are members of the groups.
type: docs
weight: 266
url: /java/com.aspose.email/freebusygroupinfo/
---
**Inheritance:**
java.lang.Object
```
public class FreebusyGroupInfo
```

Specifies list of calendars that are members of the groups.
## Constructors

| Constructor | Description |
| --- | --- |
| [FreebusyGroupInfo()](#FreebusyGroupInfo--) | Initializes a new instance of the FreebusyGroupInfo class. |
| [FreebusyGroupInfo(String groupId, ErrorDetails[] errors)](#FreebusyGroupInfo-java.lang.String-com.aspose.email.ErrorDetails---) | Initializes a new instance of the FreebusyGroupInfo class. |
| [FreebusyGroupInfo(String groupId, String[] calendars)](#FreebusyGroupInfo-java.lang.String-java.lang.String---) | Initializes a new instance of the FreebusyGroupInfo class. |
| [FreebusyGroupInfo(String groupId, Iterable<ErrorDetails> errors, Iterable<String> calendars)](#FreebusyGroupInfo-java.lang.String-java.lang.Iterable-com.aspose.email.ErrorDetails--java.lang.Iterable-java.lang.String--) | Initializes a new instance of the FreebusyGroupInfo class. |
## Methods

| Method | Description |
| --- | --- |
| [getGroupId()](#getGroupId--) | Group id |
| [setGroupId(String value)](#setGroupId-java.lang.String-) | Group id |
| [getErrors()](#getErrors--) | Optional error(s) (if computation for the group failed). |
| [getCalendars()](#getCalendars--) | List of calendars' identifiers within a group. |
### FreebusyGroupInfo() {#FreebusyGroupInfo--}
```
public FreebusyGroupInfo()
```


Initializes a new instance of the FreebusyGroupInfo class.

### FreebusyGroupInfo(String groupId, ErrorDetails[] errors) {#FreebusyGroupInfo-java.lang.String-com.aspose.email.ErrorDetails---}
```
public FreebusyGroupInfo(String groupId, ErrorDetails[] errors)
```


Initializes a new instance of the FreebusyGroupInfo class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| groupId | java.lang.String | Group id |
| errors | com.aspose.email.ErrorDetails[] | Optional error(s) (if computation for the group failed). |

### FreebusyGroupInfo(String groupId, String[] calendars) {#FreebusyGroupInfo-java.lang.String-java.lang.String---}
```
public FreebusyGroupInfo(String groupId, String[] calendars)
```


Initializes a new instance of the FreebusyGroupInfo class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| groupId | java.lang.String | Group id |
| calendars | java.lang.String[] | List of calendars' identifiers within a group. |

### FreebusyGroupInfo(String groupId, Iterable<ErrorDetails> errors, Iterable<String> calendars) {#FreebusyGroupInfo-java.lang.String-java.lang.Iterable-com.aspose.email.ErrorDetails--java.lang.Iterable-java.lang.String--}
```
public FreebusyGroupInfo(String groupId, Iterable<ErrorDetails> errors, Iterable<String> calendars)
```


Initializes a new instance of the FreebusyGroupInfo class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| groupId | java.lang.String | Group id |
| errors | java.lang.Iterable<com.aspose.email.ErrorDetails> | Optional error(s) (if computation for the group failed). |
| calendars | java.lang.Iterable<java.lang.String> | List of calendars' identifiers within a group. |

### getGroupId() {#getGroupId--}
```
public final String getGroupId()
```


Group id

**Returns:**
java.lang.String
### setGroupId(String value) {#setGroupId-java.lang.String-}
```
public final void setGroupId(String value)
```


Group id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getErrors() {#getErrors--}
```
public final List<ErrorDetails> getErrors()
```


Optional error(s) (if computation for the group failed).

**Returns:**
java.util.List<com.aspose.email.ErrorDetails>
### getCalendars() {#getCalendars--}
```
public final List<String> getCalendars()
```


List of calendars' identifiers within a group.

**Returns:**
java.util.List<java.lang.String>
