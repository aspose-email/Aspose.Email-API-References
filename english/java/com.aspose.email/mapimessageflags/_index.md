---
title: MapiMessageFlags
second_title: Aspose.Email for Java API Reference
description:  MapiMessageFlags.
type: docs
weight: 444
url: /java/com.aspose.email/mapimessageflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MapiMessageFlags extends System.Enum
```

MapiMessageFlags.
## Fields

| Field | Description |
| --- | --- |
| [MSGFLAG_ZERO](#MSGFLAG-ZERO) |  |
| [MSGFLAG_READ](#MSGFLAG-READ) | The message is marked as having been read. |
| [MSGFLAG_UNMODIFIED](#MSGFLAG-UNMODIFIED) | The message has not been modified since it was first saved (if unsent) or it was delivered (if sent). |
| [MSGFLAG_SUBMIT](#MSGFLAG-SUBMIT) | The message is marked for sending as a result of a call to IMessage::SubmitMessage. |
| [MSGFLAG_UNSENT](#MSGFLAG-UNSENT) | The message is still being composed. |
| [MSGFLAG_HASATTACH](#MSGFLAG-HASATTACH) | The message has at least one attachment. |
| [MSGFLAG_FROMME](#MSGFLAG-FROMME) | The user receiving the message was also the user who sent the message. |
| [MSGFLAG_ASSOCIATED](#MSGFLAG-ASSOCIATED) | MSGFLAG\_ASSOCIATED. |
| [MSGFLAG_RESEND](#MSGFLAG-RESEND) | The message includes a request for a resend operation with a non-delivery report. |
| [MSGFLAG_NOTIFYREAD](#MSGFLAG-NOTIFYREAD) | The user who sent the message has requested notification when a recipient first reads it. |
| [MSGFLAG_NOTIFYUNREAD](#MSGFLAG-NOTIFYUNREAD) | The user who sent the message has requested notification when a recipient deletes it before reading or the Message object expires. |
| [MSGFLAG_EVERREAD](#MSGFLAG-EVERREAD) | The message has been read at least once. |
| [MSGFLAG_ORIGIN_X400](#MSGFLAG-ORIGIN-X400) | The incoming message arrived over an X.400 link. |
| [MSGFLAG_ORIGIN_INTERNET](#MSGFLAG-ORIGIN-INTERNET) | The incoming message arrived over the Internet. |
| [MSGFLAG_ORIGIN_MISC_EXT](#MSGFLAG-ORIGIN-MISC-EXT) | The incoming message arrived over an external link other than X.400 or the Internet. |
### MSGFLAG_ZERO {#MSGFLAG-ZERO}
```
public static final long MSGFLAG_ZERO
```


### MSGFLAG_READ {#MSGFLAG-READ}
```
public static final long MSGFLAG_READ
```


The message is marked as having been read.

### MSGFLAG_UNMODIFIED {#MSGFLAG-UNMODIFIED}
```
public static final long MSGFLAG_UNMODIFIED
```


The message has not been modified since it was first saved (if unsent) or it was delivered (if sent).

### MSGFLAG_SUBMIT {#MSGFLAG-SUBMIT}
```
public static final long MSGFLAG_SUBMIT
```


The message is marked for sending as a result of a call to IMessage::SubmitMessage. Message store providers set this flag; the client has read-only access.

### MSGFLAG_UNSENT {#MSGFLAG-UNSENT}
```
public static final long MSGFLAG_UNSENT
```


The message is still being composed. It is saved, but has not been sent.

### MSGFLAG_HASATTACH {#MSGFLAG-HASATTACH}
```
public static final long MSGFLAG_HASATTACH
```


The message has at least one attachment.

### MSGFLAG_FROMME {#MSGFLAG-FROMME}
```
public static final long MSGFLAG_FROMME
```


The user receiving the message was also the user who sent the message.

### MSGFLAG_ASSOCIATED {#MSGFLAG-ASSOCIATED}
```
public static final long MSGFLAG_ASSOCIATED
```


MSGFLAG\_ASSOCIATED.

### MSGFLAG_RESEND {#MSGFLAG-RESEND}
```
public static final long MSGFLAG_RESEND
```


The message includes a request for a resend operation with a non-delivery report.

### MSGFLAG_NOTIFYREAD {#MSGFLAG-NOTIFYREAD}
```
public static final long MSGFLAG_NOTIFYREAD
```


The user who sent the message has requested notification when a recipient first reads it.

### MSGFLAG_NOTIFYUNREAD {#MSGFLAG-NOTIFYUNREAD}
```
public static final long MSGFLAG_NOTIFYUNREAD
```


The user who sent the message has requested notification when a recipient deletes it before reading or the Message object expires.

### MSGFLAG_EVERREAD {#MSGFLAG-EVERREAD}
```
public static final long MSGFLAG_EVERREAD
```


The message has been read at least once. This flag is set or cleared by the server whenever the [MapiMessageFlags\#MSGFLAG\_READ](../../com.aspose.email/mapimessageflags\#MSGFLAG-READ) flag is set or cleared.

### MSGFLAG_ORIGIN_X400 {#MSGFLAG-ORIGIN-X400}
```
public static final long MSGFLAG_ORIGIN_X400
```


The incoming message arrived over an X.400 link.

### MSGFLAG_ORIGIN_INTERNET {#MSGFLAG-ORIGIN-INTERNET}
```
public static final long MSGFLAG_ORIGIN_INTERNET
```


The incoming message arrived over the Internet.

### MSGFLAG_ORIGIN_MISC_EXT {#MSGFLAG-ORIGIN-MISC-EXT}
```
public static final long MSGFLAG_ORIGIN_MISC_EXT
```


The incoming message arrived over an external link other than X.400 or the Internet.

