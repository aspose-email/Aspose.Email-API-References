---
title: FollowUpOptions
second_title: Aspose.Email for Java API Reference
description: The follow-up settings of a message flag dates reminder categories and voting buttons.
type: docs
weight: 264
url: /java/com.aspose.email/followupoptions/
---

**Inheritance:**
java.lang.Object
```
public final class FollowUpOptions
```

The follow-up settings of a message: flag, dates, reminder, categories and voting buttons.

Fill an instance and pass it to [FollowUpManager.setOptions(MapiMessageItemBase, FollowUpOptions)](../../com.aspose.email/followupmanager\#setOptions-MapiMessageItemBase--FollowUpOptions-), or read the settings of a message with [FollowUpManager.getOptions(MapiMessageItemBase)](../../com.aspose.email/followupmanager\#getOptions-MapiMessageItemBase-).

The following example shows how to use FollowUpOptions to configure follow-up settings for a message.

```

 // Create follow-up options with flag request
 FollowUpOptions options = new FollowUpOptions("Follow up on this message");
 options.setStartDate(new Date());
 options.setDueDate(DateUtils.addDays(new Date(), 7));
 options.setReminderTime(DateUtils.addHours(new Date(), 1));
 options.setCategories("Important;Work");
 options.setVotingButtons("Approve;Reject;More Information");

 // Mark as completed
 options.markAsCompleted(true);

 // Apply options to a MapiMessage
 MapiMessage message = MapiMessage.load("message.msg");
 FollowUpManager.setOptions(message, options);

 // Save the message with follow-up settings
 message.save("message_with_options.msg", SaveOptions.getDefaultMsgUnicode());
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [FollowUpOptions()](#FollowUpOptions--) | Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class. |
| [FollowUpOptions(String flagRequest)](#FollowUpOptions-java.lang.String-) | Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class with the requested action. |
| [FollowUpOptions(String flagRequest, Date startDate, Date dueDate)](#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-) | Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class with the requested action and its dates. |
| [FollowUpOptions(String flagRequest, Date startDate, Date dueDate, Date reminderTime)](#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-java.util.Date-) | Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class with the requested action, its dates and a reminder. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCategories()](#getCategories--) | Gets the categories, separated by semicolons ( ; ). |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | Gets the code page used to encode the strings of the options in an ANSI message. |
| [getDueDate()](#getDueDate--) | Gets the date the follow-up is due. |
| [getFlagRequest()](#getFlagRequest--) | Gets the requested action that Outlook shows with the flag, for example  Follow up . |
| [getRecipientsFlagRequest()](#getRecipientsFlagRequest--) | Gets the requested action that the recipients of the message see with the flag. |
| [getRecipientsReminderTime()](#getRecipientsReminderTime--) | Gets the date and time the recipients of the message are reminded. |
| [getReminderTime()](#getReminderTime--) | Gets the date and time of the reminder. |
| [getStartDate()](#getStartDate--) | Gets the date the follow-up starts. |
| [getVotingButtons()](#getVotingButtons--) | Gets the texts of the voting buttons, separated by semicolons ( ; ). |
| [hashCode()](#hashCode--) |  |
| [isCompleted()](#isCompleted--) | Gets a value indicating whether the flag is marked as completed. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCategories(String value)](#setCategories-java.lang.String-) | Sets the categories, separated by semicolons ( ; ). |
| [setCodePage(int value)](#setCodePage-int-) | Sets the code page used to encode the strings of the options in an ANSI message. |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | Sets the date the follow-up is due. |
| [setFlagRequest(String value)](#setFlagRequest-java.lang.String-) | Sets the requested action that Outlook shows with the flag, for example  Follow up . |
| [setRecipientsFlagRequest(String value)](#setRecipientsFlagRequest-java.lang.String-) | Sets the requested action that the recipients of the message see with the flag. |
| [setRecipientsReminderTime(Date value)](#setRecipientsReminderTime-java.util.Date-) | Sets the date and time the recipients of the message are reminded. |
| [setReminderTime(Date value)](#setReminderTime-java.util.Date-) | Sets the date and time of the reminder. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Sets the date the follow-up starts. |
| [setVotingButtons(String value)](#setVotingButtons-java.lang.String-) | Sets the texts of the voting buttons, separated by semicolons ( ; ). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FollowUpOptions() {#FollowUpOptions--}
```
public FollowUpOptions()
```


Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class.

### FollowUpOptions(String flagRequest) {#FollowUpOptions-java.lang.String-}
```
public FollowUpOptions(String flagRequest)
```


Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class with the requested action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flagRequest | java.lang.String | The requested action, for example  Follow up . |

### FollowUpOptions(String flagRequest, Date startDate, Date dueDate) {#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-}
```
public FollowUpOptions(String flagRequest, Date startDate, Date dueDate)
```


Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class with the requested action and its dates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flagRequest | java.lang.String | The requested action, for example  Follow up . |
| startDate | java.util.Date | The date the follow-up starts. |
| dueDate | java.util.Date | The date the follow-up is due. |

### FollowUpOptions(String flagRequest, Date startDate, Date dueDate, Date reminderTime) {#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-java.util.Date-}
```
public FollowUpOptions(String flagRequest, Date startDate, Date dueDate, Date reminderTime)
```


Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class with the requested action, its dates and a reminder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flagRequest | java.lang.String | The requested action, for example  Follow up . |
| startDate | java.util.Date | The date the follow-up starts. |
| dueDate | java.util.Date | The date the follow-up is due. |
| reminderTime | java.util.Date | The date and time of the reminder. |

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
### getCategories() {#getCategories--}
```
public final String getCategories()
```


Gets the categories, separated by semicolons ( ; ).

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodePage() {#getCodePage--}
```
public final int getCodePage()
```


Gets the code page used to encode the strings of the options in an ANSI message.

**Returns:**
int
### getDueDate() {#getDueDate--}
```
public final Date getDueDate()
```


Gets the date the follow-up is due.

**Returns:**
java.util.Date
### getFlagRequest() {#getFlagRequest--}
```
public final String getFlagRequest()
```


Gets the requested action that Outlook shows with the flag, for example  Follow up .

**Returns:**
java.lang.String
### getRecipientsFlagRequest() {#getRecipientsFlagRequest--}
```
public final String getRecipientsFlagRequest()
```


Gets the requested action that the recipients of the message see with the flag.

**Returns:**
java.lang.String
### getRecipientsReminderTime() {#getRecipientsReminderTime--}
```
public final Date getRecipientsReminderTime()
```


Gets the date and time the recipients of the message are reminded.

**Returns:**
java.util.Date
### getReminderTime() {#getReminderTime--}
```
public final Date getReminderTime()
```


Gets the date and time of the reminder.

**Returns:**
java.util.Date
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets the date the follow-up starts.

**Returns:**
java.util.Date
### getVotingButtons() {#getVotingButtons--}
```
public final String getVotingButtons()
```


Gets the texts of the voting buttons, separated by semicolons ( ; ).

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompleted() {#isCompleted--}
```
public final boolean isCompleted()
```


Gets a value indicating whether the flag is marked as completed.

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




### setCategories(String value) {#setCategories-java.lang.String-}
```
public final void setCategories(String value)
```


Sets the categories, separated by semicolons ( ; ).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCodePage(int value) {#setCodePage-int-}
```
public final void setCodePage(int value)
```


Sets the code page used to encode the strings of the options in an ANSI message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDueDate(Date value) {#setDueDate-java.util.Date-}
```
public final void setDueDate(Date value)
```


Sets the date the follow-up is due.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setFlagRequest(String value) {#setFlagRequest-java.lang.String-}
```
public final void setFlagRequest(String value)
```


Sets the requested action that Outlook shows with the flag, for example  Follow up .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setRecipientsFlagRequest(String value) {#setRecipientsFlagRequest-java.lang.String-}
```
public final void setRecipientsFlagRequest(String value)
```


Sets the requested action that the recipients of the message see with the flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setRecipientsReminderTime(Date value) {#setRecipientsReminderTime-java.util.Date-}
```
public final void setRecipientsReminderTime(Date value)
```


Sets the date and time the recipients of the message are reminded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setReminderTime(Date value) {#setReminderTime-java.util.Date-}
```
public final void setReminderTime(Date value)
```


Sets the date and time of the reminder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Sets the date the follow-up starts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setVotingButtons(String value) {#setVotingButtons-java.lang.String-}
```
public final void setVotingButtons(String value)
```


Sets the texts of the voting buttons, separated by semicolons ( ; ).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

