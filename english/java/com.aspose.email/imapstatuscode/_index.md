---
title: ImapStatusCode
second_title: Aspose.Email for Java API Reference
description:  Represents the status responses.
type: docs
weight: 331
url: /java/com.aspose.email/imapstatuscode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImapStatusCode extends System.Enum
```

Represents the status responses.
## Fields

| Field | Description |
| --- | --- |
| [NotDefined](#NotDefined) | Not defined |
| [Ok](#Ok) | The OK response indicates an information message from the server. |
| [No](#No) | The NO response indicates an operational error message from the server. |
| [Bad](#Bad) | The BAD response indicates an error message from the server. |
| [Preauth](#Preauth) | The PREAUTH response is always untagged, and is one of three possible greetings at connection startup. |
| [Bye](#Bye) | The BYE response is always untagged, and indicates that the server is about to close the connection. |
| [Alert](#Alert) | The human-readable text contains a special alert that MUST be presented to the user in a fashion that calls the user's attention to the message. |
| [BadCharset](#BadCharset) | Optionally followed by a parenthesized list of charsets. |
| [Capability](#Capability) | Followed by a list of capabilities. |
| [Parse](#Parse) | The human-readable text represents an error in parsing the [RFC-2822] header or [MIME-IMB] headers of a message in the mailbox. |
| [PermanentFlags](#PermanentFlags) | Followed by a parenthesized list of flags, indicates which of the known flags the client can change permanently. |
| [ReadOnly](#ReadOnly) | The mailbox is selected read-only. |
| [ReadWrite](#ReadWrite) | The mailbox is selected read-write. |
| [TryCreate](#TryCreate) | An APPEND or COPY attempt is failing because the target mailbox does not exist. |
| [UIDNext](#UIDNext) | Indicates the next unique identifier value. |
| [UIDValidity](#UIDValidity) | Indicates the unique identifier validity value. |
| [Unseen](#Unseen) | Indicates the number of the first message without the \\Seen flag set. |
| [Unsolicited](#Unsolicited) | Untagged status responses. |
### NotDefined {#NotDefined}
```
public static final int NotDefined
```


Not defined

### Ok {#Ok}
```
public static final int Ok
```


The OK response indicates an information message from the server. When tagged, it indicates successful completion of the associated command. The human-readable text MAY be presented to the user as an information message. The untagged form indicates an information-only message; the nature of the information MAY be indicated by a response code.

### No {#No}
```
public static final int No
```


The NO response indicates an operational error message from the server. When tagged, it indicates unsuccessful completion of the associated command. The untagged form indicates a warning; the command can still complete successfully. The human-readable text describes the condition.

### Bad {#Bad}
```
public static final int Bad
```


The BAD response indicates an error message from the server. When tagged, it reports a protocol-level error in the client's command; the tag indicates the command that caused the error. The untagged form indicates a protocol-level error for which the associated command can not be determined; it can also indicate an internal server failure. The human-readable text describes the condition.

### Preauth {#Preauth}
```
public static final int Preauth
```


The PREAUTH response is always untagged, and is one of three possible greetings at connection startup. It indicates that the connection has already been authenticated by external means and thus no LOGIN command is needed.

### Bye {#Bye}
```
public static final int Bye
```


The BYE response is always untagged, and indicates that the server is about to close the connection. The human-readable text MAY be displayed to the user in a status report by the client. The difference between a BYE that occurs as part of a normal LOGOUT sequence (the first case) and a BYE that occurs because of a failure (the other three cases) is that the connection closes immediately in the failure case.

### Alert {#Alert}
```
public static final int Alert
```


The human-readable text contains a special alert that MUST be presented to the user in a fashion that calls the user's attention to the message.

### BadCharset {#BadCharset}
```
public static final int BadCharset
```


Optionally followed by a parenthesized list of charsets. A SEARCH failed because the given charset is not supported by this implementation.

### Capability {#Capability}
```
public static final int Capability
```


Followed by a list of capabilities.

### Parse {#Parse}
```
public static final int Parse
```


The human-readable text represents an error in parsing the [RFC-2822] header or [MIME-IMB] headers of a message in the mailbox.

### PermanentFlags {#PermanentFlags}
```
public static final int PermanentFlags
```


Followed by a parenthesized list of flags, indicates which of the known flags the client can change permanently.

### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


The mailbox is selected read-only.

### ReadWrite {#ReadWrite}
```
public static final int ReadWrite
```


The mailbox is selected read-write.

### TryCreate {#TryCreate}
```
public static final int TryCreate
```


An APPEND or COPY attempt is failing because the target mailbox does not exist.

### UIDNext {#UIDNext}
```
public static final int UIDNext
```


Indicates the next unique identifier value.

### UIDValidity {#UIDValidity}
```
public static final int UIDValidity
```


Indicates the unique identifier validity value.

### Unseen {#Unseen}
```
public static final int Unseen
```


Indicates the number of the first message without the \\Seen flag set.

### Unsolicited {#Unsolicited}
```
public static final int Unsolicited
```


Untagged status responses.

