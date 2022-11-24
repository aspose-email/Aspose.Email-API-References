---
title: FollowUpOptions
second_title: Aspose.Email for Java API Reference
description: Represents options for using follow-up flags and reminders in a message.
type: docs
weight: 258
url: /java/com.aspose.email/followupoptions/
---

**Inheritance:**
java.lang.Object
```
public final class FollowUpOptions
```

Represents options for using follow-up flags and reminders in a message.
## Constructors

| Constructor | Description |
| --- | --- |
| [FollowUpOptions()](#FollowUpOptions--) | Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class. |
| [FollowUpOptions(String flagRequest)](#FollowUpOptions-java.lang.String-) | Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class. |
| [FollowUpOptions(String flagRequest, Date startDate, Date dueDate)](#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-) | Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class. |
| [FollowUpOptions(String flagRequest, Date startDate, Date dueDate, Date reminderTime)](#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-java.util.Date-) | Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCategories()](#getCategories--) | Gets or sets string that represents list of the categories, separated by semicolons (;). |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | Gets or sets the code page. |
| [getDueDate()](#getDueDate--) | Gets or sets a date indicating the due date for the flagged message. |
| [getFlagRequest()](#getFlagRequest--) | Gets or sets a string indicating the requested action for an e-mail message. |
| [getRecipientsFlagRequest()](#getRecipientsFlagRequest--) | Gets or sets a string indicating the requested action for recipients of an e-mail message. |
| [getRecipientsReminderTime()](#getRecipientsReminderTime--) | Gets or sets a date for recipients indicating the date and time at which the reminder should occur. |
| [getReminderTime()](#getReminderTime--) | Gets or sets a date indicating the date and time at which the reminder should occur. |
| [getStartDate()](#getStartDate--) | Gets or sets a date specifying the starting date and time for the flagged message. |
| [getVotingButtons()](#getVotingButtons--) | Gets or sets string that represents list of the voting buttons names, separated by semicolons (;). |
| [hashCode()](#hashCode--) |  |
| [isCompleted()](#isCompleted--) | Gets a value indicating whether the Message object was flagged as completed. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCategories(String value)](#setCategories-java.lang.String-) | Gets or sets string that represents list of the categories, separated by semicolons (;). |
| [setCodePage(int value)](#setCodePage-int-) | Gets or sets the code page. |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | Gets or sets a date indicating the due date for the flagged message. |
| [setFlagRequest(String value)](#setFlagRequest-java.lang.String-) | Gets or sets a string indicating the requested action for an e-mail message. |
| [setRecipientsFlagRequest(String value)](#setRecipientsFlagRequest-java.lang.String-) | Gets or sets a string indicating the requested action for recipients of an e-mail message. |
| [setRecipientsReminderTime(Date value)](#setRecipientsReminderTime-java.util.Date-) | Gets or sets a date for recipients indicating the date and time at which the reminder should occur. |
| [setReminderTime(Date value)](#setReminderTime-java.util.Date-) | Gets or sets a date indicating the date and time at which the reminder should occur. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Gets or sets a date specifying the starting date and time for the flagged message. |
| [setVotingButtons(String value)](#setVotingButtons-java.lang.String-) | Gets or sets string that represents list of the voting buttons names, separated by semicolons (;). |
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


Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flagRequest | java.lang.String | The flag request. |

### FollowUpOptions(String flagRequest, Date startDate, Date dueDate) {#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-}
```
public FollowUpOptions(String flagRequest, Date startDate, Date dueDate)
```


Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flagRequest | java.lang.String | The flag request. |
| startDate | java.util.Date | The start Date. |
| dueDate | java.util.Date | The due Date. |

### FollowUpOptions(String flagRequest, Date startDate, Date dueDate, Date reminderTime) {#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-java.util.Date-}
```
public FollowUpOptions(String flagRequest, Date startDate, Date dueDate, Date reminderTime)
```


Initializes a new instance of the [FollowUpOptions](../../com.aspose.email/followupoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flagRequest | java.lang.String | The flag request. |
| startDate | java.util.Date | The start date. |
| dueDate | java.util.Date | The due date. |
| reminderTime | java.util.Date | The reminder time. |

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


Gets or sets string that represents list of the categories, separated by semicolons (;).

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


Gets or sets the code page.

**Returns:**
int
### getDueDate() {#getDueDate--}
```
public final Date getDueDate()
```


Gets or sets a date indicating the due date for the flagged message.

**Returns:**
java.util.Date
### getFlagRequest() {#getFlagRequest--}
```
public final String getFlagRequest()
```


Gets or sets a string indicating the requested action for an e-mail message.

**Returns:**
java.lang.String
### getRecipientsFlagRequest() {#getRecipientsFlagRequest--}
```
public final String getRecipientsFlagRequest()
```


Gets or sets a string indicating the requested action for recipients of an e-mail message.

**Returns:**
java.lang.String
### getRecipientsReminderTime() {#getRecipientsReminderTime--}
```
public final Date getRecipientsReminderTime()
```


Gets or sets a date for recipients indicating the date and time at which the reminder should occur.

**Returns:**
java.util.Date
### getReminderTime() {#getReminderTime--}
```
public final Date getReminderTime()
```


Gets or sets a date indicating the date and time at which the reminder should occur.

**Returns:**
java.util.Date
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets or sets a date specifying the starting date and time for the flagged message.

**Returns:**
java.util.Date
### getVotingButtons() {#getVotingButtons--}
```
public final String getVotingButtons()
```


Gets or sets string that represents list of the voting buttons names, separated by semicolons (;).

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


Gets a value indicating whether the Message object was flagged as completed.

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


Gets or sets string that represents list of the categories, separated by semicolons (;).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCodePage(int value) {#setCodePage-int-}
```
public final void setCodePage(int value)
```


Gets or sets the code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDueDate(Date value) {#setDueDate-java.util.Date-}
```
public final void setDueDate(Date value)
```


Gets or sets a date indicating the due date for the flagged message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setFlagRequest(String value) {#setFlagRequest-java.lang.String-}
```
public final void setFlagRequest(String value)
```


Gets or sets a string indicating the requested action for an e-mail message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setRecipientsFlagRequest(String value) {#setRecipientsFlagRequest-java.lang.String-}
```
public final void setRecipientsFlagRequest(String value)
```


Gets or sets a string indicating the requested action for recipients of an e-mail message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setRecipientsReminderTime(Date value) {#setRecipientsReminderTime-java.util.Date-}
```
public final void setRecipientsReminderTime(Date value)
```


Gets or sets a date for recipients indicating the date and time at which the reminder should occur.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setReminderTime(Date value) {#setReminderTime-java.util.Date-}
```
public final void setReminderTime(Date value)
```


Gets or sets a date indicating the date and time at which the reminder should occur.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Gets or sets a date specifying the starting date and time for the flagged message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setVotingButtons(String value) {#setVotingButtons-java.lang.String-}
```
public final void setVotingButtons(String value)
```


Gets or sets string that represents list of the voting buttons names, separated by semicolons (;).

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

