---
title: MapiPropertyFlags
second_title: Aspose.Email for Android via Java API Reference
description:  Represents flags which can be set on a MAPI property.
type: docs
weight: 270
url: /java/com.aspose.email/mapipropertyflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MapiPropertyFlags extends System.Enum
```

Represents flags which can be set on a MAPI property.
## Fields

| Field | Description |
| --- | --- |
| [PROPATTR_MANDATORY](#PROPATTR-MANDATORY) | If this flag is set for a property, that property MUST NOT be deleted from the .msg file (irrespective of which storage it is contained in) and implementations MUST return an error if any attempt is made to do so. |
| [PROPATTR_READABLE](#PROPATTR-READABLE) | If this flag is not set on a property, that property MUST not be read from the .msg file and implementations MUST return an error if any attempt is made to read it. |
| [PROPATTR_WRITABLE](#PROPATTR-WRITABLE) | If this flag is not set on a property, that property MUST not be modified or deleted and implementations MUST return an error if any attempt is made to do so. |
### PROPATTR_MANDATORY {#PROPATTR-MANDATORY}
```
public static final int PROPATTR_MANDATORY
```


If this flag is set for a property, that property MUST NOT be deleted from the .msg file (irrespective of which storage it is contained in) and implementations MUST return an error if any attempt is made to do so. This flag is set in circumstances where the implementation depends on that property always being present in the .msg file once it is written there.

### PROPATTR_READABLE {#PROPATTR-READABLE}
```
public static final int PROPATTR_READABLE
```


If this flag is not set on a property, that property MUST not be read from the .msg file and implementations MUST return an error if any attempt is made to read it. This flag is set on all properties unless there is an implementation-specific reason to prevent a property from being read from the .msg file.

### PROPATTR_WRITABLE {#PROPATTR-WRITABLE}
```
public static final int PROPATTR_WRITABLE
```


If this flag is not set on a property, that property MUST not be modified or deleted and implementations MUST return an error if any attempt is made to do so. This flag is set in circumstances where the implementation depends on the properties being writable.

