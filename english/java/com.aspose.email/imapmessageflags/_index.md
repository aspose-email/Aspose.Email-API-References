---
title: ImapMessageFlags
second_title: Aspose.Email for Java API Reference
description: Represents the flags associated with the message.
type: docs
weight: 314
url: /java/com.aspose.email/imapmessageflags/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class ImapMessageFlags implements System.IEquatable<ImapMessageFlags>
```

Represents the flags associated with the message.
## Methods

| Method | Description |
| --- | --- |
| [keyword(String flag)](#keyword-java.lang.String-) | Message has been marked by custom flag. |
| [getAnswered()](#getAnswered--) | Message has been answered. |
| [getDeleted()](#getDeleted--) | Message is "deleted" for removal by later EXPUNGE. |
| [getDraft()](#getDraft--) | Message has been marked as a draft. |
| [getFlagged()](#getFlagged--) | Message is "flagged" for urgent/special attention. |
| [getRecent()](#getRecent--) | Message is "recently" arrived in this mailbox. |
| [isRead()](#isRead--) | Message has been read. |
| [getEmpty()](#getEmpty--) | Flags are not set |
| [isEmpty()](#isEmpty--) | Determines whether this instance is empty. |
| [split()](#split--) | Split to Array. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to this instance. |
| [to_ImapMessageFlags(String type)](#to-ImapMessageFlags-java.lang.String-) | Performs an implicit conversion from long to [ImapMessageFlags](../../com.aspose.email/imapmessageflags). |
| [op_BitwiseOr(ImapMessageFlags a, ImapMessageFlags b)](#op-BitwiseOr-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-) | Implements the operator |. |
| [op_BitwiseOr(ImapMessageFlags a, String b)](#op-BitwiseOr-com.aspose.email.ImapMessageFlags-java.lang.String-) | Implements the operator |. |
| [op_BitwiseOr(String a, ImapMessageFlags b)](#op-BitwiseOr-java.lang.String-com.aspose.email.ImapMessageFlags-) | Implements the operator |. |
| [op_BitwiseAnd(ImapMessageFlags a, ImapMessageFlags b)](#op-BitwiseAnd-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-) | Implements the operator &. |
| [bitwiseOr(ImapMessageFlags a, ImapMessageFlags b)](#bitwiseOr-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-) | Implements the operator |. |
| [bitwiseOr(ImapMessageFlags a, String b)](#bitwiseOr-com.aspose.email.ImapMessageFlags-java.lang.String-) | Implements the operator |. |
| [bitwiseOr(String a, ImapMessageFlags b)](#bitwiseOr-java.lang.String-com.aspose.email.ImapMessageFlags-) | Implements the operator |. |
| [bitwiseAnd(ImapMessageFlags a, ImapMessageFlags b)](#bitwiseAnd-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-) | Implements the operator &. |
| [hasFlag(ImapMessageFlags what)](#hasFlag-com.aspose.email.ImapMessageFlags-) | Returns true if "who" contains the "flag" |
| [op_Inequality(ImapMessageFlags a, ImapMessageFlags b)](#op-Inequality-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-) | Implements the operator !=. |
| [op_Equality(ImapMessageFlags a, ImapMessageFlags b)](#op-Equality-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-) | Implements the operator ==. |
| [equals(ImapMessageFlags other)](#equals-com.aspose.email.ImapMessageFlags-) | Determines whether the specified object is equal to the current object. |
| [toString()](#toString--) | Returns a String that represents this instance. |
### keyword(String flag) {#keyword-java.lang.String-}
```
public static ImapMessageFlags keyword(String flag)
```


Message has been marked by custom flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flag | java.lang.String |  |

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags)
### getAnswered() {#getAnswered--}
```
public static ImapMessageFlags getAnswered()
```


Message has been answered.

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags)
### getDeleted() {#getDeleted--}
```
public static ImapMessageFlags getDeleted()
```


Message is "deleted" for removal by later EXPUNGE.

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags)
### getDraft() {#getDraft--}
```
public static ImapMessageFlags getDraft()
```


Message has been marked as a draft.

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags)
### getFlagged() {#getFlagged--}
```
public static ImapMessageFlags getFlagged()
```


Message is "flagged" for urgent/special attention.

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags)
### getRecent() {#getRecent--}
```
public static ImapMessageFlags getRecent()
```


Message is "recently" arrived in this mailbox.

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags)
### isRead() {#isRead--}
```
public static ImapMessageFlags isRead()
```


Message has been read.

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags)
### getEmpty() {#getEmpty--}
```
public static ImapMessageFlags getEmpty()
```


Flags are not set

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Determines whether this instance is empty.

**Returns:**
boolean -  true  if this instance is empty; otherwise,  false .
### split() {#split--}
```
public final ImapMessageFlags[] split()
```


Split to Array.

**Returns:**
com.aspose.email.ImapMessageFlags[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified Object is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The Object to compare with this instance. |

**Returns:**
boolean -  true  if the specified Object is equal to this instance; otherwise,  false .
### to_ImapMessageFlags(String type) {#to-ImapMessageFlags-java.lang.String-}
```
public static ImapMessageFlags to_ImapMessageFlags(String type)
```


Performs an implicit conversion from long to [ImapMessageFlags](../../com.aspose.email/imapmessageflags).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | java.lang.String | Value of a type. |

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags) - The result of the conversion.
### op_BitwiseOr(ImapMessageFlags a, ImapMessageFlags b) {#op-BitwiseOr-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-}
```
public static ImapMessageFlags op_BitwiseOr(ImapMessageFlags a, ImapMessageFlags b)
```


Implements the operator |.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | First set of imap message flags. |
| b | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | Second set of imap message flags. |

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags) - The result of the operator.
### op_BitwiseOr(ImapMessageFlags a, String b) {#op-BitwiseOr-com.aspose.email.ImapMessageFlags-java.lang.String-}
```
public static ImapMessageFlags op_BitwiseOr(ImapMessageFlags a, String b)
```


Implements the operator |.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | First set of imap message flags. |
| b | java.lang.String | Second set of imap message flags. |

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags) - The result of the operator.
### op_BitwiseOr(String a, ImapMessageFlags b) {#op-BitwiseOr-java.lang.String-com.aspose.email.ImapMessageFlags-}
```
public static ImapMessageFlags op_BitwiseOr(String a, ImapMessageFlags b)
```


Implements the operator |.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | java.lang.String | First set of imap message flags. |
| b | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | Second set of imap message flags. |

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags) - The result of the operator.
### op_BitwiseAnd(ImapMessageFlags a, ImapMessageFlags b) {#op-BitwiseAnd-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-}
```
public static ImapMessageFlags op_BitwiseAnd(ImapMessageFlags a, ImapMessageFlags b)
```


Implements the operator &.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | First set of imap message flags. |
| b | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | Second set of imap message flags. |

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags) - The result of the operator.
### bitwiseOr(ImapMessageFlags a, ImapMessageFlags b) {#bitwiseOr-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-}
```
public static ImapMessageFlags bitwiseOr(ImapMessageFlags a, ImapMessageFlags b)
```


Implements the operator |.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | First set of imap message flags. |
| b | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | Second set of imap message flags. |

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags) - The result of the operator.
### bitwiseOr(ImapMessageFlags a, String b) {#bitwiseOr-com.aspose.email.ImapMessageFlags-java.lang.String-}
```
public static ImapMessageFlags bitwiseOr(ImapMessageFlags a, String b)
```


Implements the operator |.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | First set of imap message flags. |
| b | java.lang.String | Second set of imap message flags. |

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags) - The result of the operator.
### bitwiseOr(String a, ImapMessageFlags b) {#bitwiseOr-java.lang.String-com.aspose.email.ImapMessageFlags-}
```
public static ImapMessageFlags bitwiseOr(String a, ImapMessageFlags b)
```


Implements the operator |.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | java.lang.String | First set of imap message flags. |
| b | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | Second set of imap message flags. |

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags) - The result of the operator.
### bitwiseAnd(ImapMessageFlags a, ImapMessageFlags b) {#bitwiseAnd-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-}
```
public static ImapMessageFlags bitwiseAnd(ImapMessageFlags a, ImapMessageFlags b)
```


Implements the operator &.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | First set of imap message flags. |
| b | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | Second set of imap message flags. |

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags) - The result of the operator.
### hasFlag(ImapMessageFlags what) {#hasFlag-com.aspose.email.ImapMessageFlags-}
```
public final boolean hasFlag(ImapMessageFlags what)
```


Returns true if "who" contains the "flag"

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| what | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | Imap message flags |

**Returns:**
boolean - 
### op_Inequality(ImapMessageFlags a, ImapMessageFlags b) {#op-Inequality-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-}
```
public static boolean op_Inequality(ImapMessageFlags a, ImapMessageFlags b)
```


Implements the operator !=.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | First set of imap message flags. |
| b | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | Second set of imap message flags. |

**Returns:**
boolean - The result of the operator.
### op_Equality(ImapMessageFlags a, ImapMessageFlags b) {#op-Equality-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-}
```
public static boolean op_Equality(ImapMessageFlags a, ImapMessageFlags b)
```


Implements the operator ==.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | First set of imap message flags. |
| b | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | Second set of imap message flags. |

**Returns:**
boolean - The result of the operator.
### equals(ImapMessageFlags other) {#equals-com.aspose.email.ImapMessageFlags-}
```
public boolean equals(ImapMessageFlags other)
```


Determines whether the specified object is equal to the current object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [ImapMessageFlags](../../com.aspose.email/imapmessageflags) | The object to compare with the current object. |

**Returns:**
boolean - true if the specified object is equal to the current object; otherwise, false.
### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
