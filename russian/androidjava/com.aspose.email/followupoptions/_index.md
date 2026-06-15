---
title: FollowUpOptions
second_title: Aspose.Email for Android via Java API Reference
description: Представляет параметры использования флагов последующего действия и напоминаний в сообщении.
type: docs
weight: 145
url: /ru/androidjava/com.aspose.email/followupoptions/
---

**Inheritance:**
java.lang.Object
```
public final class FollowUpOptions
```

Представляет параметры использования флагов последующего действия и напоминаний в сообщении.
## Constructors

| Constructor | Описание |
| --- | --- |
| [FollowUpOptions()](#FollowUpOptions--) | Инициализирует новый экземпляр класса [FollowUpOptions](../../com.aspose.email/followupoptions). |
| [FollowUpOptions(String flagRequest)](#FollowUpOptions-java.lang.String-) | Инициализирует новый экземпляр класса [FollowUpOptions](../../com.aspose.email/followupoptions). |
| [FollowUpOptions(String flagRequest, Date startDate, Date dueDate)](#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-) | Инициализирует новый экземпляр класса [FollowUpOptions](../../com.aspose.email/followupoptions). |
| [FollowUpOptions(String flagRequest, Date startDate, Date dueDate, Date reminderTime)](#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-java.util.Date-) | Инициализирует новый экземпляр класса [FollowUpOptions](../../com.aspose.email/followupoptions). |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCategories()](#getCategories--) | Получает или задает строку, представляющую список категорий, разделённых точками с запятой (;). |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | Получает или задает кодовую страницу. |
| [getDueDate()](#getDueDate--) | Получает или задает дату, указывающую срок выполнения для помеченного сообщения. |
| [getFlagRequest()](#getFlagRequest--) | Получает или задает строку, указывающую запрошенное действие для электронного сообщения. |
| [getRecipientsFlagRequest()](#getRecipientsFlagRequest--) | Получает или задает строку, указывающую запрошенное действие для получателей электронного сообщения. |
| [getRecipientsReminderTime()](#getRecipientsReminderTime--) | Получает или задает дату для получателей, указывающую дату и время, когда должно сработать напоминание. |
| [getReminderTime()](#getReminderTime--) | Получает или задает дату, указывающую дату и время, когда должно сработать напоминание. |
| [getStartDate()](#getStartDate--) | Получает или задает дату, указывающую начальную дату и время для помеченного сообщения. |
| [getVotingButtons()](#getVotingButtons--) | Получает или задает строку, представляющую список названий кнопок голосования, разделённых точками с запятой (;). |
| [hashCode()](#hashCode--) |  |
| [isCompleted()](#isCompleted--) | Получает значение, указывающее, был ли объект Message помечен как завершённый. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCategories(String value)](#setCategories-java.lang.String-) | Получает или задает строку, представляющую список категорий, разделённых точками с запятой (;). |
| [setCodePage(int value)](#setCodePage-int-) | Получает или задает кодовую страницу. |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | Получает или задает дату, указывающую срок выполнения для помеченного сообщения. |
| [setFlagRequest(String value)](#setFlagRequest-java.lang.String-) | Получает или задает строку, указывающую запрошенное действие для электронного сообщения. |
| [setRecipientsFlagRequest(String value)](#setRecipientsFlagRequest-java.lang.String-) | Получает или задает строку, указывающую запрошенное действие для получателей электронного сообщения. |
| [setRecipientsReminderTime(Date value)](#setRecipientsReminderTime-java.util.Date-) | Получает или задает дату для получателей, указывающую дату и время, когда должно сработать напоминание. |
| [setReminderTime(Date value)](#setReminderTime-java.util.Date-) | Получает или задает дату, указывающую дату и время, когда должно сработать напоминание. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Получает или задает дату, указывающую начальную дату и время для помеченного сообщения. |
| [setVotingButtons(String value)](#setVotingButtons-java.lang.String-) | Получает или задает строку, представляющую список названий кнопок голосования, разделённых точками с запятой (;). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FollowUpOptions() {#FollowUpOptions--}
```
public FollowUpOptions()
```


Инициализирует новый экземпляр класса [FollowUpOptions](../../com.aspose.email/followupoptions).

### FollowUpOptions(String flagRequest) {#FollowUpOptions-java.lang.String-}
```
public FollowUpOptions(String flagRequest)
```


Инициализирует новый экземпляр класса [FollowUpOptions](../../com.aspose.email/followupoptions).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| flagRequest | java.lang.String | Запрос флага. |

### FollowUpOptions(String flagRequest, Date startDate, Date dueDate) {#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-}
```
public FollowUpOptions(String flagRequest, Date startDate, Date dueDate)
```


Инициализирует новый экземпляр класса [FollowUpOptions](../../com.aspose.email/followupoptions).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| flagRequest | java.lang.String | Запрос флага. |
| startDate | java.util.Date | Дата начала. |
| dueDate | java.util.Date | Срок выполнения. |

### FollowUpOptions(String flagRequest, Date startDate, Date dueDate, Date reminderTime) {#FollowUpOptions-java.lang.String-java.util.Date-java.util.Date-java.util.Date-}
```
public FollowUpOptions(String flagRequest, Date startDate, Date dueDate, Date reminderTime)
```


Инициализирует новый экземпляр класса [FollowUpOptions](../../com.aspose.email/followupoptions).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| flagRequest | java.lang.String | Запрос флага. |
| startDate | java.util.Date | Дата начала. |
| dueDate | java.util.Date | Срок выполнения. |
| reminderTime | java.util.Date | Время напоминания. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCategories() {#getCategories--}
```
public final String getCategories()
```


Получает или задает строку, представляющую список категорий, разделённых точками с запятой (;).

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


Получает или задает кодовую страницу.

**Returns:**
int
### getDueDate() {#getDueDate--}
```
public final Date getDueDate()
```


Получает или задает дату, указывающую срок выполнения для помеченного сообщения.

**Returns:**
java.util.Date
### getFlagRequest() {#getFlagRequest--}
```
public final String getFlagRequest()
```


Получает или задает строку, указывающую запрошенное действие для электронного сообщения.

**Returns:**
java.lang.String
### getRecipientsFlagRequest() {#getRecipientsFlagRequest--}
```
public final String getRecipientsFlagRequest()
```


Получает или задает строку, указывающую запрошенное действие для получателей электронного сообщения.

**Returns:**
java.lang.String
### getRecipientsReminderTime() {#getRecipientsReminderTime--}
```
public final Date getRecipientsReminderTime()
```


Получает или задает дату для получателей, указывающую дату и время, когда должно сработать напоминание.

**Returns:**
java.util.Date
### getReminderTime() {#getReminderTime--}
```
public final Date getReminderTime()
```


Получает или задает дату, указывающую дату и время, когда должно сработать напоминание.

**Returns:**
java.util.Date
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Получает или задает дату, указывающую начальную дату и время для помеченного сообщения.

**Returns:**
java.util.Date
### getVotingButtons() {#getVotingButtons--}
```
public final String getVotingButtons()
```


Получает или задает строку, представляющую список названий кнопок голосования, разделённых точками с запятой (;).

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


Получает значение, указывающее, был ли объект Message помечен как завершённый.

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


Получает или задает строку, представляющую список категорий, разделённых точками с запятой (;).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setCodePage(int value) {#setCodePage-int-}
```
public final void setCodePage(int value)
```


Получает или задает кодовую страницу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setDueDate(Date value) {#setDueDate-java.util.Date-}
```
public final void setDueDate(Date value)
```


Получает или задает дату, указывающую срок выполнения для помеченного сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setFlagRequest(String value) {#setFlagRequest-java.lang.String-}
```
public final void setFlagRequest(String value)
```


Получает или задает строку, указывающую запрошенное действие для электронного сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setRecipientsFlagRequest(String value) {#setRecipientsFlagRequest-java.lang.String-}
```
public final void setRecipientsFlagRequest(String value)
```


Получает или задает строку, указывающую запрошенное действие для получателей электронного сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setRecipientsReminderTime(Date value) {#setRecipientsReminderTime-java.util.Date-}
```
public final void setRecipientsReminderTime(Date value)
```


Получает или задает дату для получателей, указывающую дату и время, когда должно сработать напоминание.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setReminderTime(Date value) {#setReminderTime-java.util.Date-}
```
public final void setReminderTime(Date value)
```


Получает или задает дату, указывающую дату и время, когда должно сработать напоминание.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Получает или задает дату, указывающую начальную дату и время для помеченного сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setVotingButtons(String value) {#setVotingButtons-java.lang.String-}
```
public final void setVotingButtons(String value)
```


Получает или задает строку, представляющую список названий кнопок голосования, разделённых точками с запятой (;).

**Parameters:**
| Parameter | Type | Описание |
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
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

