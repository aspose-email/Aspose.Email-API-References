---
title: MailTips
second_title: Aspose.Email for Java API Reference
description: Represents values for the Mail Tips
type: docs
weight: 377
url: /java/com.aspose.email/mailtips/
---
**Inheritance:**
java.lang.Object
```
public final class MailTips
```

Represents values for the Mail Tips
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomMailTip()](#getCustomMailTip--) | Gets a custom mail tip. |
| [getDeliveryRestricted()](#getDeliveryRestricted--) | Gets a value indicating whether delivery restrictions will prevent the sender's message from reaching the recipient. |
| [getExternalMemberCnt()](#getExternalMemberCnt--) | Gets the number of external members in a group. |
| [getInvalidRecipient()](#getInvalidRecipient--) | Gets a value indicating whether the recipient is invalid. |
| [getMailboxFull()](#getMailboxFull--) | Gets a value indicating whether the mailbox for the recipient is full. |
| [getMaxMsgSize()](#getMaxMsgSize--) | Gets the maximum message size the recipient can accept |
| [getOutOfOffice()](#getOutOfOffice--) | Gets the response message for OOF and the duration for sending this message. |
| [getPendingMailTips()](#getPendingMailTips--) | Gets a value indicating whether the mail tips in this element could not be evaluated before the server's processing timeout expired. |
| [getRecipientAddress()](#getRecipientAddress--) | Gets the mailbox of the recipient. |
| [getTotalMemberCnt()](#getTotalMemberCnt--) | Gets the total number of members in a group. |
| [hashCode()](#hashCode--) |  |
| [isDeliveryRestrictedSpecified()](#isDeliveryRestrictedSpecified--) | Gets a value indicating whether  DeliveryRestricted (\#getDeliveryRestricted.getDeliveryRestricted/\#setDeliveryRestricted(boolean).setDeliveryRestricted(boolean)) is specified |
| [isInvalidRecipientSpecified()](#isInvalidRecipientSpecified--) | Gets a value indicating whether  InvalidRecipient (\#getInvalidRecipient.getInvalidRecipient/\#setInvalidRecipient(boolean).setInvalidRecipient(boolean)) is specified |
| [isMailboxFullSpecified()](#isMailboxFullSpecified--) | Gets a value indicating whether the  MailboxFull (\#getMailboxFull.getMailboxFull/\#setMailboxFull(boolean).setMailboxFull(boolean)) is specified |
| [isModerated()](#isModerated--) | Gets a value indicating whether the recipient's mailbox is being moderated. |
| [isModeratedSpecified()](#isModeratedSpecified--) | Gets a value indicating whether the  IsModerated (\#isModerated.isModerated/\#setModerated(boolean).setModerated(boolean)) is specified |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCustomMailTip() {#getCustomMailTip--}
```
public final String getCustomMailTip()
```


Gets a custom mail tip.

**Returns:**
java.lang.String
### getDeliveryRestricted() {#getDeliveryRestricted--}
```
public final boolean getDeliveryRestricted()
```


Gets a value indicating whether delivery restrictions will prevent the sender's message from reaching the recipient.

**Returns:**
boolean
### getExternalMemberCnt() {#getExternalMemberCnt--}
```
public final int getExternalMemberCnt()
```


Gets the number of external members in a group.

**Returns:**
int
### getInvalidRecipient() {#getInvalidRecipient--}
```
public final boolean getInvalidRecipient()
```


Gets a value indicating whether the recipient is invalid.

**Returns:**
boolean
### getMailboxFull() {#getMailboxFull--}
```
public final boolean getMailboxFull()
```


Gets a value indicating whether the mailbox for the recipient is full.

**Returns:**
boolean
### getMaxMsgSize() {#getMaxMsgSize--}
```
public final int getMaxMsgSize()
```


Gets the maximum message size the recipient can accept

**Returns:**
int
### getOutOfOffice() {#getOutOfOffice--}
```
public final OutOfOfficeMailTip getOutOfOffice()
```


Gets the response message for OOF and the duration for sending this message.

**Returns:**
[OutOfOfficeMailTip](../../com.aspose.email/outofofficemailtip)
### getPendingMailTips() {#getPendingMailTips--}
```
public final int getPendingMailTips()
```


Gets a value indicating whether the mail tips in this element could not be evaluated before the server's processing timeout expired.

**Returns:**
int
### getRecipientAddress() {#getRecipientAddress--}
```
public final MailAddress getRecipientAddress()
```


Gets the mailbox of the recipient.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getTotalMemberCnt() {#getTotalMemberCnt--}
```
public final int getTotalMemberCnt()
```


Gets the total number of members in a group.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDeliveryRestrictedSpecified() {#isDeliveryRestrictedSpecified--}
```
public final boolean isDeliveryRestrictedSpecified()
```


Gets a value indicating whether  DeliveryRestricted (\#getDeliveryRestricted.getDeliveryRestricted/\#setDeliveryRestricted(boolean).setDeliveryRestricted(boolean)) is specified

**Returns:**
boolean
### isInvalidRecipientSpecified() {#isInvalidRecipientSpecified--}
```
public final boolean isInvalidRecipientSpecified()
```


Gets a value indicating whether  InvalidRecipient (\#getInvalidRecipient.getInvalidRecipient/\#setInvalidRecipient(boolean).setInvalidRecipient(boolean)) is specified

**Returns:**
boolean
### isMailboxFullSpecified() {#isMailboxFullSpecified--}
```
public final boolean isMailboxFullSpecified()
```


Gets a value indicating whether the  MailboxFull (\#getMailboxFull.getMailboxFull/\#setMailboxFull(boolean).setMailboxFull(boolean)) is specified

**Returns:**
boolean
### isModerated() {#isModerated--}
```
public final boolean isModerated()
```


Gets a value indicating whether the recipient's mailbox is being moderated.

**Returns:**
boolean
### isModeratedSpecified() {#isModeratedSpecified--}
```
public final boolean isModeratedSpecified()
```


Gets a value indicating whether the  IsModerated (\#isModerated.isModerated/\#setModerated(boolean).setModerated(boolean)) is specified

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

