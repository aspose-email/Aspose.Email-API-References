---
title: RecipientTrackingEvent
second_title: Aspose.Email for Java API Reference
description: Represents details for a specific event in the tracking report.
type: docs
weight: 583
url: /java/com.aspose.email/recipienttrackingevent/
---
**Inheritance:**
java.lang.Object
```
public final class RecipientTrackingEvent
```

Represents details for a specific event in the tracking report.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBccRecipient()](#getBccRecipient--) | Gets a value indicating whether the recipient was addressed as a blind carbon copy (BCC) recipient. |
| [getClass()](#getClass--) |  |
| [getDate()](#getDate--) | Gets the time at which the event occurred. |
| [getDeliveryStatus()](#getDeliveryStatus--) | Gets the status for the message. |
| [getEventData()](#getEventData--) | Gets data that is associated with the processing step for the event. |
| [getEventDescription()](#getEventDescription--) | Gets the processing step for the event |
| [getHiddenRecipient()](#getHiddenRecipient--) | Gets a value indicating whether the recipient was added by an organization policy that should be hidden from unprivileged users |
| [getInternalIdentifier()](#getInternalIdentifier--) | Gets an integer value for the event. |
| [getRecipient()](#getRecipient--) | Gets the recipient for whom the event occurred. |
| [getServer()](#getServer--) | Gets the physical server where the event occurred. |
| [getUniquePathId()](#getUniquePathId--) | Gets a string that is different for each path. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBccRecipient() {#getBccRecipient--}
```
public final boolean getBccRecipient()
```


Gets a value indicating whether the recipient was addressed as a blind carbon copy (BCC) recipient.

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDate() {#getDate--}
```
public final Date getDate()
```


Gets the time at which the event occurred.

**Returns:**
java.util.Date
### getDeliveryStatus() {#getDeliveryStatus--}
```
public final String getDeliveryStatus()
```


Gets the status for the message.

**Returns:**
java.lang.String
### getEventData() {#getEventData--}
```
public final System.Collections.Specialized.StringCollection getEventData()
```


Gets data that is associated with the processing step for the event.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### getEventDescription() {#getEventDescription--}
```
public final String getEventDescription()
```


Gets the processing step for the event

**Returns:**
java.lang.String
### getHiddenRecipient() {#getHiddenRecipient--}
```
public final boolean getHiddenRecipient()
```


Gets a value indicating whether the recipient was added by an organization policy that should be hidden from unprivileged users

**Returns:**
boolean
### getInternalIdentifier() {#getInternalIdentifier--}
```
public final int getInternalIdentifier()
```


Gets an integer value for the event.

**Returns:**
int
### getRecipient() {#getRecipient--}
```
public final MailAddress getRecipient()
```


Gets the recipient for whom the event occurred.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getServer() {#getServer--}
```
public final String getServer()
```


Gets the physical server where the event occurred.

**Returns:**
java.lang.String
### getUniquePathId() {#getUniquePathId--}
```
public final String getUniquePathId()
```


Gets a string that is different for each path.

**Returns:**
java.lang.String
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

