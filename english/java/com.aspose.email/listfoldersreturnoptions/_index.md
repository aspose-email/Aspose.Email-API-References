---
title: ListFoldersReturnOptions
second_title: Aspose.Email for Java API Reference
description: Return options for ListFolders operation Please note this options are supported in case if server supports RFC 5258 IMAP LIST Command Extensions See more details in https//tools.ietf.org/html/rfc5258
type: docs
weight: 352
url: /java/com.aspose.email/listfoldersreturnoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ListFoldersReturnOptions extends System.Enum
```

Return options for ListFolders operation Please note, this options are supported in case if server supports RFC 5258 "IMAP LIST Command Extensions" See more details in https://tools.ietf.org/html/rfc5258
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | Not defined |
| [Subscribed](#Subscribed) | SUBSCRIBED - causes the LIST command to return subscription state for all matching mailbox names. |
| [Children](#Children) | CHILDREN - requests mailbox child information. |
### None {#None}
```
public static final int None
```


Not defined

### Subscribed {#Subscribed}
```
public static final int Subscribed
```


SUBSCRIBED - causes the LIST command to return subscription state for all matching mailbox names. The "\\Subscribed" attribute MUST be supported and MUST be accurately computed when the SUBSCRIBED return option is specified. Further, all mailbox flags MUST be accurately computed (this differs from the behavior of the LSUB command).

### Children {#Children}
```
public static final int Children
```


CHILDREN - requests mailbox child information. This option MUST be supported by all servers.

