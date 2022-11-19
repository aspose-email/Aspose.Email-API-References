---
title: BounceResult
second_title: Aspose.Email for Java API Reference
description: Represents result of the message examination as a bounce message.
type: docs
weight: 84
url: /java/com.aspose.email/bounceresult/
---

**Inheritance:**
java.lang.Object
```
public class BounceResult
```

Represents result of the message examination as a bounce message.
## Constructors

| Constructor | Description |
| --- | --- |
| [BounceResult()](#BounceResult--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Indicates the action performed as a result of attempt to deliver the message. |
| [getClass()](#getClass--) |  |
| [getOriginalMessage()](#getOriginalMessage--) | Contains the original message. |
| [getReason()](#getReason--) | For a "failed" or "delayed" recipient, contains the actual diagnostic code issued by the mail transport. |
| [getRecipient()](#getRecipient--) | Indicates the original recipient address as specified by the sender of the message for which the delivery failure report was issued. |
| [getStatus()](#getStatus--) | Contains a transport-independent status code which indicates the delivery status of the message to that recipient. |
| [hashCode()](#hashCode--) |  |
| [isBounced()](#isBounced--) | True if email is a delivery failure or deliver delay report. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BounceResult() {#BounceResult--}
```
public BounceResult()
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
### getAction() {#getAction--}
```
public final int getAction()
```


Indicates the action performed as a result of attempt to deliver the message.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOriginalMessage() {#getOriginalMessage--}
```
public final MailMessage getOriginalMessage()
```


Contains the original message.

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
### getReason() {#getReason--}
```
public final String getReason()
```


For a "failed" or "delayed" recipient, contains the actual diagnostic code issued by the mail transport.

**Returns:**
java.lang.String
### getRecipient() {#getRecipient--}
```
public final String getRecipient()
```


Indicates the original recipient address as specified by the sender of the message for which the delivery failure report was issued.

**Returns:**
java.lang.String
### getStatus() {#getStatus--}
```
public final String getStatus()
```


Contains a transport-independent status code which indicates the delivery status of the message to that recipient.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBounced() {#isBounced--}
```
public final boolean isBounced()
```


True if email is a delivery failure or deliver delay report.

**Returns:**
boolean
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

