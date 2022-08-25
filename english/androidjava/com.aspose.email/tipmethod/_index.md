---
title: TIPMethod
second_title: Aspose.Email for Android via Java API Reference
description:  Defines the iTIP iCalendar Transport-Independent Interoperability Protocol methods associated with an object.
type: docs
weight: 392
url: /java/com.aspose.email/tipmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TIPMethod extends System.Enum
```

Defines the iTIP (iCalendar Transport-Independent Interoperability Protocol) methods associated with an object.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | Method is not defined. |
| [Publish](#Publish) | Post notification of an object. |
| [Request](#Request) | Assign an object. |
| [Reply](#Reply) | Reply to an object request. |
| [Add](#Add) | Add one or more instances to an existing object. |
| [Cancel](#Cancel) | Cancel one or more instances of an existing object. |
| [Refresh](#Refresh) | A request sent to an object Organizer asking for the latest version of an object. |
| [Counter](#Counter) | Counter a REQUEST with an alternative proposal. |
| [DeclineCounter](#DeclineCounter) | Decline a counter proposal by an Attendee. |
### None {#None}
```
public static final int None
```


Method is not defined.

### Publish {#Publish}
```
public static final int Publish
```


Post notification of an object. Used primarily as a method of advertising the existence of an object.

### Request {#Request}
```
public static final int Request
```


Assign an object. This is an explicit assignment to one or more Calendar Users. The REQUEST method is also used to update or change an existing object. Clients that cannot handle REQUEST MAY degrade the method to treat it as a PUBLISH.

### Reply {#Reply}
```
public static final int Reply
```


Reply to an object request.

### Add {#Add}
```
public static final int Add
```


Add one or more instances to an existing object.

### Cancel {#Cancel}
```
public static final int Cancel
```


Cancel one or more instances of an existing object.

### Refresh {#Refresh}
```
public static final int Refresh
```


A request sent to an object Organizer asking for the latest version of an object.

### Counter {#Counter}
```
public static final int Counter
```


Counter a REQUEST with an alternative proposal.

### DeclineCounter {#DeclineCounter}
```
public static final int DeclineCounter
```


Decline a counter proposal by an Attendee.

