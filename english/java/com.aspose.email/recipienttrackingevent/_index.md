---
title: RecipientTrackingEvent
second_title: Aspose.Email for Java API Reference
description:  Represents details for a specific event in the tracking report.
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
| [getDate()](#getDate--) | Gets the time at which the event occurred. |
| [getRecipient()](#getRecipient--) | Gets the recipient for whom the event occurred. |
| [getDeliveryStatus()](#getDeliveryStatus--) | Gets the status for the message. |
| [getEventDescription()](#getEventDescription--) | Gets the processing step for the event |
| [getEventData()](#getEventData--) | Gets data that is associated with the processing step for the event. |
| [getServer()](#getServer--) | Gets the physical server where the event occurred. |
| [getInternalIdentifier()](#getInternalIdentifier--) | Gets an integer value for the event. |
| [getBccRecipient()](#getBccRecipient--) | Gets a value indicating whether the recipient was addressed as a blind carbon copy (BCC) recipient. |
| [getHiddenRecipient()](#getHiddenRecipient--) | Gets a value indicating whether the recipient was added by an organization policy that should be hidden from unprivileged users |
| [getUniquePathId()](#getUniquePathId--) | Gets a string that is different for each path. |
### getDate() {#getDate--}
```
public final Date getDate()
```


Gets the time at which the event occurred.

**Returns:**
java.util.Date
### getRecipient() {#getRecipient--}
```
public final MailAddress getRecipient()
```


Gets the recipient for whom the event occurred.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getDeliveryStatus() {#getDeliveryStatus--}
```
public final String getDeliveryStatus()
```


Gets the status for the message.

**Returns:**
java.lang.String
### getEventDescription() {#getEventDescription--}
```
public final String getEventDescription()
```


Gets the processing step for the event

**Returns:**
java.lang.String
### getEventData() {#getEventData--}
```
public final System.Collections.Specialized.StringCollection getEventData()
```


Gets data that is associated with the processing step for the event.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### getServer() {#getServer--}
```
public final String getServer()
```


Gets the physical server where the event occurred.

**Returns:**
java.lang.String
### getInternalIdentifier() {#getInternalIdentifier--}
```
public final int getInternalIdentifier()
```


Gets an integer value for the event.

**Returns:**
int
### getBccRecipient() {#getBccRecipient--}
```
public final boolean getBccRecipient()
```


Gets a value indicating whether the recipient was addressed as a blind carbon copy (BCC) recipient.

**Returns:**
boolean
### getHiddenRecipient() {#getHiddenRecipient--}
```
public final boolean getHiddenRecipient()
```


Gets a value indicating whether the recipient was added by an organization policy that should be hidden from unprivileged users

**Returns:**
boolean
### getUniquePathId() {#getUniquePathId--}
```
public final String getUniquePathId()
```


Gets a string that is different for each path.

**Returns:**
java.lang.String
