---
title: ImapMessageFlags
second_title: Aspose.Email for Java API Reference
description: Represents the flags associated with the message.
type: docs
weight: 332
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
| [bitwiseAnd(ImapMessageFlags a, ImapMessageFlags b)](#bitwiseAnd-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-) | Implements the operator &. |
| [bitwiseOr(ImapMessageFlags a, ImapMessageFlags b)](#bitwiseOr-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-) | Implements the operator |. |
| [bitwiseOr(ImapMessageFlags a, String b)](#bitwiseOr-com.aspose.email.ImapMessageFlags-java.lang.String-) | Implements the operator |. |
| [bitwiseOr(String a, ImapMessageFlags b)](#bitwiseOr-java.lang.String-com.aspose.email.ImapMessageFlags-) | Implements the operator |. |
| [equals(ImapMessageFlags other)](#equals-com.aspose.email.ImapMessageFlags-) | Determines whether the specified object is equal to the current object. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to this instance. |
| [getAnswered()](#getAnswered--) | Message has been answered. |
| [getClass()](#getClass--) |  |
| [getDeleted()](#getDeleted--) | Message is "deleted" for removal by later EXPUNGE. |
| [getDraft()](#getDraft--) | Message has been marked as a draft. |
| [getEmpty()](#getEmpty--) | Flags are not set |
| [getFlagged()](#getFlagged--) | Message is "flagged" for urgent/special attention. |
| [getRecent()](#getRecent--) | Message is "recently" arrived in this mailbox. |
| [hasFlag(ImapMessageFlags what)](#hasFlag-com.aspose.email.ImapMessageFlags-) | Returns true if "who" contains the "flag" |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [isEmpty()](#isEmpty--) | Determines whether this instance is empty. |
| [isRead()](#isRead--) | Message has been read. |
| [keyword(String flag)](#keyword-java.lang.String-) | Message has been marked by custom flag. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_BitwiseAnd(ImapMessageFlags a, ImapMessageFlags b)](#op-BitwiseAnd-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-) | Implements the operator &. |
| [op_BitwiseOr(ImapMessageFlags a, ImapMessageFlags b)](#op-BitwiseOr-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-) | Implements the operator |. |
| [op_BitwiseOr(ImapMessageFlags a, String b)](#op-BitwiseOr-com.aspose.email.ImapMessageFlags-java.lang.String-) | Implements the operator |. |
| [op_BitwiseOr(String a, ImapMessageFlags b)](#op-BitwiseOr-java.lang.String-com.aspose.email.ImapMessageFlags-) | Implements the operator |. |
| [op_Equality(ImapMessageFlags a, ImapMessageFlags b)](#op-Equality-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-) | Implements the operator ==. |
| [op_Inequality(ImapMessageFlags a, ImapMessageFlags b)](#op-Inequality-com.aspose.email.ImapMessageFlags-com.aspose.email.ImapMessageFlags-) | Implements the operator !=. |
| [split()](#split--) | Split to Array. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [to_ImapMessageFlags(String type)](#to-ImapMessageFlags-java.lang.String-) | Performs an implicit conversion from long to [ImapMessageFlags](../../com.aspose.email/imapmessageflags). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAnswered() {#getAnswered--}
```
public static ImapMessageFlags getAnswered()
```


Message has been answered.

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getEmpty() {#getEmpty--}
```
public static ImapMessageFlags getEmpty()
```


Flags are not set

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
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Determines whether this instance is empty.

**Returns:**
boolean -  true  if this instance is empty; otherwise,  false .
### isRead() {#isRead--}
```
public static ImapMessageFlags isRead()
```


Message has been read.

**Returns:**
[ImapMessageFlags](../../com.aspose.email/imapmessageflags)
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
### split() {#split--}
```
public final ImapMessageFlags[] split()
```


Split to Array.

**Returns:**
com.aspose.email.ImapMessageFlags[]
### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
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
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

