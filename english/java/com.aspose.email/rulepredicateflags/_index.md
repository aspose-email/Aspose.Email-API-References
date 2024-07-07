---
title: RulePredicateFlags
second_title: Aspose.Email for Java API Reference
description: Represents the RulePredicate flags
type: docs
weight: 630
url: /java/com.aspose.email/rulepredicateflags/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class RulePredicateFlags extends System.Enum
```

Represents the RulePredicate flags
## Fields

| Field | Description |
| --- | --- |
| [ApprovalRequest](#ApprovalRequest) | Incoming messages must be approval requests in order for the condition or exception to apply. |
| [AutomaticForward](#AutomaticForward) | Incoming messages must be automatic forwards in order for the condition or exception to apply. |
| [AutomaticReply](#AutomaticReply) | Incoming messages must be automatic replies in order for the condition or exception to apply. |
| [Encrypted](#Encrypted) | Incoming messages must be S/MIME encrypted in order for the condition or exception to apply. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [HasAttachment](#HasAttachment) | An incoming messages have to have attachments in order for the condition or exception to apply |
| [HasNotAttachment](#HasNotAttachment) | An incoming messages have to have NOT attachments in order for the condition or exception to apply |
| [MeetingRequest](#MeetingRequest) | Incoming messages must be meeting requests in order for the condition or exception to apply. |
| [MeetingResponse](#MeetingResponse) | Incoming messages must be meeting responses in order for the condition or exception to apply. |
| [Ndr](#Ndr) | Incoming messages must be non-delivery reports (NDRs) in order for the condition or exception to apply. |
| [None](#None) | No flags are specified |
| [NotApprovalRequest](#NotApprovalRequest) | Incoming messages must NOT be approval requests in order for the condition or exception to apply. |
| [NotAutomaticForward](#NotAutomaticForward) | Incoming messages must NOT be automatic forwards in order for the condition or exception to apply. |
| [NotAutomaticReply](#NotAutomaticReply) | Incoming messages must NOT be automatic replies in order for the condition or exception to apply. |
| [NotEncrypted](#NotEncrypted) | Incoming messages must not be S/MIME encrypted in order for the condition or exception to apply. |
| [NotMeetingRequest](#NotMeetingRequest) | Incoming messages must NOT be meeting requests in order for the condition or exception to apply. |
| [NotMeetingResponse](#NotMeetingResponse) | Incoming messages must NOT be meeting responses in order for the condition or exception to apply. |
| [NotNdr](#NotNdr) | Incoming messages must NOT be non-delivery reports (NDRs) in order for the condition or exception to apply. |
| [NotPermissionControlled](#NotPermissionControlled) | Incoming messages must NOT be permission controlled (RMS protected) in order for the condition or exception to apply. |
| [NotReadReceipt](#NotReadReceipt) | Incoming messages must NOT be read receipts in order for the condition or exception to apply |
| [NotSentCcMe](#NotSentCcMe) | The owner of the mailbox cannot be in the CcRecipients property of incoming messages in order for the condition or exception to apply. |
| [NotSentOnlyToMe](#NotSentOnlyToMe) | The owner of the mailbox cannot to be the only one in the ToRecipients property of incoming messages in order for the condition or exception to apply. |
| [NotSentToMe](#NotSentToMe) | The owner of the mailbox cannot be in the ToRecipients property of the incoming messages in order for the condition or exception to apply. |
| [NotSigned](#NotSigned) | Incoming messages must NOT be S/MIME signed in order for the condition or exception to apply. |
| [NotVoicemail](#NotVoicemail) | Incoming messages cant NOT be voice mails in order for the condition or exception to apply. |
| [PermissionControlled](#PermissionControlled) | Incoming messages must be permission controlled (RMS protected) in order for the condition or exception to apply. |
| [ReadReceipt](#ReadReceipt) | Incoming messages must be read receipts in order for the condition or exception to apply |
| [SentCcMe](#SentCcMe) | The owner of the mailbox has to be in the CcRecipients property of incoming messages in order for the condition or exception to apply. |
| [SentOnlyToMe](#SentOnlyToMe) | The owner of the mailbox has to be the only one in the ToRecipients property of incoming messages in order for the condition or exception to apply. |
| [SentToMe](#SentToMe) | The owner of the mailbox has to be in the ToRecipients property of incoming messages in order for the condition or exception to apply. |
| [SentToOrCcMe](#SentToOrCcMe) | The owner of the mailbox has to be in either a ToRecipients or CcRecipients property of incoming messages in order for the condition or exception to apply |
| [Signed](#Signed) | Incoming messages must be S/MIME signed in order for the condition or exception to apply. |
| [Voicemail](#Voicemail) | Incoming messages must be voice mails in order for the condition or exception to apply. |
## Methods

| Method | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(System.Enum arg0)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type arg0, Object arg1, String arg2)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> arg0, long arg1, String arg2)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(System.Type arg0, Object arg1)](#getName-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [getName(Class<?> arg0, long arg1)](#getName-java.lang.Class----long-) |  |
| [getNames(System.Type arg0)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> arg0)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type arg0)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> arg0)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> arg0, String arg1)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues(System.Type arg0)](#getValues-com.aspose.ms.System.Type-) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type arg0, Object arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type arg0, String arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type arg0, long arg1)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> arg0, long arg1)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type arg0, String arg1)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type arg0, String arg1, Boolean arg2)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> arg0, String arg1)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> arg0, String arg1, Boolean arg2)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum arg0)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type arg0, Object arg1)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [toString(Class<?> arg0, long arg1)](#toString-java.lang.Class----long-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ApprovalRequest {#ApprovalRequest}
```
public static final int ApprovalRequest
```


Incoming messages must be approval requests in order for the condition or exception to apply.

### AutomaticForward {#AutomaticForward}
```
public static final int AutomaticForward
```


Incoming messages must be automatic forwards in order for the condition or exception to apply.

### AutomaticReply {#AutomaticReply}
```
public static final int AutomaticReply
```


Incoming messages must be automatic replies in order for the condition or exception to apply.

### Encrypted {#Encrypted}
```
public static final int Encrypted
```


Incoming messages must be S/MIME encrypted in order for the condition or exception to apply.

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### HasAttachment {#HasAttachment}
```
public static final int HasAttachment
```


An incoming messages have to have attachments in order for the condition or exception to apply

### HasNotAttachment {#HasNotAttachment}
```
public static final int HasNotAttachment
```


An incoming messages have to have NOT attachments in order for the condition or exception to apply

### MeetingRequest {#MeetingRequest}
```
public static final int MeetingRequest
```


Incoming messages must be meeting requests in order for the condition or exception to apply.

### MeetingResponse {#MeetingResponse}
```
public static final int MeetingResponse
```


Incoming messages must be meeting responses in order for the condition or exception to apply.

### Ndr {#Ndr}
```
public static final int Ndr
```


Incoming messages must be non-delivery reports (NDRs) in order for the condition or exception to apply.

### None {#None}
```
public static final int None
```


No flags are specified

### NotApprovalRequest {#NotApprovalRequest}
```
public static final int NotApprovalRequest
```


Incoming messages must NOT be approval requests in order for the condition or exception to apply.

### NotAutomaticForward {#NotAutomaticForward}
```
public static final int NotAutomaticForward
```


Incoming messages must NOT be automatic forwards in order for the condition or exception to apply.

### NotAutomaticReply {#NotAutomaticReply}
```
public static final int NotAutomaticReply
```


Incoming messages must NOT be automatic replies in order for the condition or exception to apply.

### NotEncrypted {#NotEncrypted}
```
public static final int NotEncrypted
```


Incoming messages must not be S/MIME encrypted in order for the condition or exception to apply.

### NotMeetingRequest {#NotMeetingRequest}
```
public static final int NotMeetingRequest
```


Incoming messages must NOT be meeting requests in order for the condition or exception to apply.

### NotMeetingResponse {#NotMeetingResponse}
```
public static final int NotMeetingResponse
```


Incoming messages must NOT be meeting responses in order for the condition or exception to apply.

### NotNdr {#NotNdr}
```
public static final int NotNdr
```


Incoming messages must NOT be non-delivery reports (NDRs) in order for the condition or exception to apply.

### NotPermissionControlled {#NotPermissionControlled}
```
public static final int NotPermissionControlled
```


Incoming messages must NOT be permission controlled (RMS protected) in order for the condition or exception to apply.

### NotReadReceipt {#NotReadReceipt}
```
public static final int NotReadReceipt
```


Incoming messages must NOT be read receipts in order for the condition or exception to apply

### NotSentCcMe {#NotSentCcMe}
```
public static final int NotSentCcMe
```


The owner of the mailbox cannot be in the CcRecipients property of incoming messages in order for the condition or exception to apply.

### NotSentOnlyToMe {#NotSentOnlyToMe}
```
public static final int NotSentOnlyToMe
```


The owner of the mailbox cannot to be the only one in the ToRecipients property of incoming messages in order for the condition or exception to apply.

### NotSentToMe {#NotSentToMe}
```
public static final int NotSentToMe
```


The owner of the mailbox cannot be in the ToRecipients property of the incoming messages in order for the condition or exception to apply.

### NotSigned {#NotSigned}
```
public static final int NotSigned
```


Incoming messages must NOT be S/MIME signed in order for the condition or exception to apply.

### NotVoicemail {#NotVoicemail}
```
public static final int NotVoicemail
```


Incoming messages cant NOT be voice mails in order for the condition or exception to apply.

### PermissionControlled {#PermissionControlled}
```
public static final int PermissionControlled
```


Incoming messages must be permission controlled (RMS protected) in order for the condition or exception to apply.

### ReadReceipt {#ReadReceipt}
```
public static final int ReadReceipt
```


Incoming messages must be read receipts in order for the condition or exception to apply

### SentCcMe {#SentCcMe}
```
public static final int SentCcMe
```


The owner of the mailbox has to be in the CcRecipients property of incoming messages in order for the condition or exception to apply.

### SentOnlyToMe {#SentOnlyToMe}
```
public static final int SentOnlyToMe
```


The owner of the mailbox has to be the only one in the ToRecipients property of incoming messages in order for the condition or exception to apply.

### SentToMe {#SentToMe}
```
public static final int SentToMe
```


The owner of the mailbox has to be in the ToRecipients property of incoming messages in order for the condition or exception to apply.

### SentToOrCcMe {#SentToOrCcMe}
```
public static final int SentToOrCcMe
```


The owner of the mailbox has to be in either a ToRecipients or CcRecipients property of incoming messages in order for the condition or exception to apply

### Signed {#Signed}
```
public static final int Signed
```


Incoming messages must be S/MIME signed in order for the condition or exception to apply.

### Voicemail {#Voicemail}
```
public static final int Voicemail
```


Incoming messages must be voice mails in order for the condition or exception to apply.

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Enum
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

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
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName(System.Type arg0, Object arg1) {#getName-com.aspose.ms.System.Type-java.lang.Object-}
```
public static String getName(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### get_Caption() {#get-Caption--}
```
public String get_Caption()
```




**Returns:**
java.lang.String
### get_Value() {#get-Value--}
```
public long get_Value()
```




**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

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




### parse(System.Type arg0, String arg1) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(Class<?> arg0, long arg1) {#toString-java.lang.Class----long-}
```
public static String toString(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

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

