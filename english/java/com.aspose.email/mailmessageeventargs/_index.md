---
title: MailMessageEventArgs
second_title: Aspose.Email for Java API Reference
description: Provides data for the MessageSending and MessageSent events.
type: docs
weight: 371
url: /java/com.aspose.email/mailmessageeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class MailMessageEventArgs extends System.EventArgs
```

Provides data for the MessageSending and MessageSent events.
## Constructors

| Constructor | Description |
| --- | --- |
| [MailMessageEventArgs(MailMessage message)](#MailMessageEventArgs-com.aspose.email.MailMessage-) | Initializes a new instance of the [MailMessageEventArgs](../../com.aspose.email/mailmessageeventargs) class. |
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMessage()](#getMessage--) | Gets the sending message. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailMessageEventArgs(MailMessage message) {#MailMessageEventArgs-com.aspose.email.MailMessage-}
```
public MailMessageEventArgs(MailMessage message)
```


Initializes a new instance of the [MailMessageEventArgs](../../com.aspose.email/mailmessageeventargs) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message. |

### Empty {#Empty}
```
public static final System.EventArgs Empty
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMessage() {#getMessage--}
```
public final MailMessage getMessage()
```


Gets the sending message.

Value: The MailMessage.

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

