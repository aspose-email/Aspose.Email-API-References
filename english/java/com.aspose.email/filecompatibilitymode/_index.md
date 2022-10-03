---
title: FileCompatibilityMode
second_title: Aspose.Email for Java API Reference
description:  Defines inner conversions 
 that are necessarily to be done when loading 
 or saving a message.
type: docs
weight: 245
url: /java/com.aspose.email/filecompatibilitymode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class FileCompatibilityMode extends System.Enum
```

Defines inner conversions, that are necessarily to be done when loading or saving a message. By default CR is not replaces by CRLF, Tnef-attachment is not saved.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | No values are set. |
| [AllowCROnly](#AllowCROnly) | Shows the necessity of the forced replace of line separators by CRLF. |
| [PreserveTnefAttachments](#PreserveTnefAttachments) | Controls TNEF attachment saving behaviour. |
### None {#None}
```
public static final int None
```


No values are set.

### AllowCROnly {#AllowCROnly}
```
public static final int AllowCROnly
```


Shows the necessity of the forced replace of line separators by CRLF.

### PreserveTnefAttachments {#PreserveTnefAttachments}
```
public static final int PreserveTnefAttachments
```


Controls TNEF attachment saving behaviour. This option affects messages whose winmail.dat TNEF attachment (if present) was decoded at loading. If the option is set, the previously decoded and extracted TNEF will be encoded and packaged again into the winmail.dat attachment during message saving. By default the option isn't set.

