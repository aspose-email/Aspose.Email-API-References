---
title: AccessRole
second_title: Aspose.Email for Java API Reference
description:  The effective access role that the authenticated user has on the calendar.
type: docs
weight: 11
url: /java/com.aspose.email/accessrole/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class AccessRole extends System.Enum
```

The effective access role that the authenticated user has on the calendar.
## Fields

| Field | Description |
| --- | --- |
| [none](#none) | Not defined |
| [freeBusyReader](#freeBusyReader) | Provides read access to free/busy information. |
| [reader](#reader) | Provides read access to the calendar. |
| [writer](#writer) | Provides read and write access to the calendar. |
| [owner](#owner) | Provides ownership of the calendar. |
### none {#none}
```
public static final int none
```


Not defined

### freeBusyReader {#freeBusyReader}
```
public static final int freeBusyReader
```


Provides read access to free/busy information.

### reader {#reader}
```
public static final int reader
```


Provides read access to the calendar. Private events will appear to users with reader access, but event details will be hidden.

### writer {#writer}
```
public static final int writer
```


Provides read and write access to the calendar. Private events will appear to users with writer access, and event details will be visible.

### owner {#owner}
```
public static final int owner
```


Provides ownership of the calendar. This role has all of the permissions of the writer role with the additional ability to see and manipulate ACLs.

