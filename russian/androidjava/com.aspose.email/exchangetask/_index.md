---
title: ExchangeTask
second_title: Aspose.Email for Android via Java API Reference
description: Представляет информацию о задаче Exchange.
type: docs
weight: 127
url: /ru/androidjava/com.aspose.email/exchangetask/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.Task](../../com.aspose.email/task)
```
public final class ExchangeTask extends Task
```

Представляет информацию о задаче Exchange.
## Constructors

| Constructor | Описание |
| --- | --- |
| [ExchangeTask()](#ExchangeTask--) | Инициализирует новый экземпляр класса [ExchangeTask](../../com.aspose.email/exchangetask). |
## Methods

| Method | Описание |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | Освободить все ресурсы. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActualWork()](#getActualWork--) | Получает или задает фактическое количество времени, затрачиваемого на задачу (минуты). |
| [getAttachments()](#getAttachments--) | Получает или задает коллекцию файлов, прикреплённых к задаче. |
| [getAttendees()](#getAttendees--) | Получает или задает участников. |
| [getBillingInformation()](#getBillingInformation--) | Получает или задает информацию о выставлении счета для задачи. |
| [getBody()](#getBody--) | Получает или задает тело задачи. |
| [getClass()](#getClass--) |  |
| [getCompanies()](#getCompanies--) | Получает или задает коллекцию компаний, связанных с задачей. |
| [getCompletionDate()](#getCompletionDate--) | Получает или задает дату, когда пользователь завершил работу над задачей. |
| [getDueDate()](#getDueDate--) | Получает или задает дату, к которой пользователь ожидает завершения работы над задачей. |
| [getMethod()](#getMethod--) | Получает или задает методы iTIP, связанные с задачей. |
| [getMileage()](#getMileage--) | Получает или задает пробег для задачи. |
| [getOrganizer()](#getOrganizer--) | Получает или задает организатора. |
| [getPercentComplete()](#getPercentComplete--) | Получает или задает процент завершения задачи. |
| [getPriority()](#getPriority--) | Получает или задает приоритет задачи. |
| [getRecurrencePattern()](#getRecurrencePattern--) | Получает или задает информацию о повторении для повторяющейся задачи. |
| [getRelatedTo()](#getRelatedTo--) | Получает или задает связанный UID |
| [getReminderDate()](#getReminderDate--) | Получает или задает дату напоминания задачи. |
| [getSequenceId()](#getSequenceId--) | Получает или задает идентификатор последовательности. |
| [getStartDate()](#getStartDate--) | Получает или задает дату начала задачи. |
| [getStatus()](#getStatus--) | Получает или задает статус задачи. |
| [getSubject()](#getSubject--) | Получает или задает тему задачи. |
| [getTotalWork()](#getTotalWork--) | Получает или задает общее количество работы, которое пользователь ожидает выполнить по задаче. |
| [getUniqueId()](#getUniqueId--) | Получает или задает уникальный идентификатор |
| [getUniqueUri()](#getUniqueUri--) | Получает или задает уникальный URI задачи. |
| [hashCode()](#hashCode--) |  |
| [isBodyHtml()](#isBodyHtml--) | Получает или задает значение, указывающее, является ли тело задачи в формате HTML. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [request()](#request--) | Запрашивает объект. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет текущий объект в указанный поток, используя формат MSG. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Сохраняет текущий объект в указанный поток, используя указанный формат. |
| [save(String filePath)](#save-java.lang.String-) | Сохраняет текущий объект в файл, используя формат MSG. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Сохраняет текущий объект в файл, используя указанный формат. |
| [setActualWork(int value)](#setActualWork-int-) | Получает или задает фактическое количество времени, затрачиваемого на задачу (минуты). |
| [setAttachments(AttachmentCollection value)](#setAttachments-com.aspose.email.AttachmentCollection-) | Получает или задает коллекцию файлов, прикреплённых к задаче. |
| [setAttendees(MailAddressCollection value)](#setAttendees-com.aspose.email.MailAddressCollection-) | Получает или задает участников. |
| [setBillingInformation(String value)](#setBillingInformation-java.lang.String-) | Получает или задает информацию о выставлении счета для задачи. |
| [setBody(String value)](#setBody-java.lang.String-) | Получает или задает тело задачи. |
| [setBodyHtml(boolean value)](#setBodyHtml-boolean-) | Получает или задает значение, указывающее, является ли тело задачи в формате HTML. |
| [setCompanies(System.Collections.Specialized.StringCollection value)](#setCompanies-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Получает или задает коллекцию компаний, связанных с задачей. |
| [setCompletionDate(Date value)](#setCompletionDate-java.util.Date-) | Получает или задает дату, когда пользователь завершил работу над задачей. |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | Получает или задает дату, к которой пользователь ожидает завершения работы над задачей. |
| [setMethod(int value)](#setMethod-int-) | Получает или задает методы iTIP, связанные с задачей. |
| [setMileage(String value)](#setMileage-java.lang.String-) | Получает или задает пробег для задачи. |
| [setOrganizer(MailAddress value)](#setOrganizer-com.aspose.email.MailAddress-) | Получает или задает организатора. |
| [setPercentComplete(float value)](#setPercentComplete-float-) | Получает или задает процент завершения задачи. |
| [setPriority(int value)](#setPriority-int-) | Получает или задает приоритет задачи. |
| [setRecurrencePattern(RecurrencePattern value)](#setRecurrencePattern-com.aspose.email.RecurrencePattern-) | Получает или задает информацию о повторении для повторяющейся задачи. |
| [setRelatedTo(String value)](#setRelatedTo-java.lang.String-) | Получает или задает связанный UID |
| [setReminderDate(Date value)](#setReminderDate-java.util.Date-) | Получает или задает дату напоминания задачи. |
| [setSequenceId(int value)](#setSequenceId-int-) | Получает или задает идентификатор последовательности. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Получает или задает дату начала задачи. |
| [setStatus(int value)](#setStatus-int-) | Получает или задает статус задачи. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Получает или задает тему задачи. |
| [setTotalWork(int value)](#setTotalWork-int-) | Получает или задает общее количество работы, которое пользователь ожидает выполнить по задаче. |
| [setUniqueId(String value)](#setUniqueId-java.lang.String-) | Получает или задает уникальный идентификатор |
| [setUniqueUri(String value)](#setUniqueUri-java.lang.String-) | Получает или задает уникальный URI задачи. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExchangeTask() {#ExchangeTask--}
```
public ExchangeTask()
```


Инициализирует новый экземпляр класса [ExchangeTask](../../com.aspose.email/exchangetask).

### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


Освободить все ресурсы.

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
### getActualWork() {#getActualWork--}
```
public final int getActualWork()
```


Получает или задает фактическое количество времени, затрачиваемого на задачу (минуты).

**Returns:**
int
### getAttachments() {#getAttachments--}
```
public final AttachmentCollection getAttachments()
```


Получает или задает коллекцию файлов, прикреплённых к задаче.

**Returns:**
[AttachmentCollection](../../com.aspose.email/attachmentcollection)
### getAttendees() {#getAttendees--}
```
public final MailAddressCollection getAttendees()
```


Получает или задает участников.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getBillingInformation() {#getBillingInformation--}
```
public final String getBillingInformation()
```


Получает или задает информацию о выставлении счета для задачи.

**Returns:**
java.lang.String
### getBody() {#getBody--}
```
public final String getBody()
```


Получает или задает тело задачи.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompanies() {#getCompanies--}
```
public final System.Collections.Specialized.StringCollection getCompanies()
```


Получает или задает коллекцию компаний, связанных с задачей.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### getCompletionDate() {#getCompletionDate--}
```
public final Date getCompletionDate()
```


Получает или задает дату, когда пользователь завершил работу над задачей.

**Returns:**
java.util.Date
### getDueDate() {#getDueDate--}
```
public final Date getDueDate()
```


Получает или задает дату, к которой пользователь ожидает завершения работы над задачей.

**Returns:**
java.util.Date
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Получает или задает методы iTIP, связанные с задачей.

**Returns:**
int
### getMileage() {#getMileage--}
```
public final String getMileage()
```


Получает или задает пробег для задачи.

**Returns:**
java.lang.String
### getOrganizer() {#getOrganizer--}
```
public final MailAddress getOrganizer()
```


Получает или задает организатора.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getPercentComplete() {#getPercentComplete--}
```
public final float getPercentComplete()
```


Получает или задает процент завершения задачи.

**Returns:**
float
### getPriority() {#getPriority--}
```
public final int getPriority()
```


Получает или задает приоритет задачи.

**Returns:**
int
### getRecurrencePattern() {#getRecurrencePattern--}
```
public final RecurrencePattern getRecurrencePattern()
```


Получает или задает информацию о повторении для повторяющейся задачи.

**Returns:**
[RecurrencePattern](../../com.aspose.email/recurrencepattern)
### getRelatedTo() {#getRelatedTo--}
```
public final String getRelatedTo()
```


Получает или задает связанный UID

**Returns:**
java.lang.String
### getReminderDate() {#getReminderDate--}
```
public final Date getReminderDate()
```


Получает или задает дату напоминания задачи.

**Returns:**
java.util.Date
### getSequenceId() {#getSequenceId--}
```
public final int getSequenceId()
```


Получает или задает идентификатор последовательности.

Значение: идентификатор последовательности.

**Returns:**
int
### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Получает или задает дату начала задачи.

**Returns:**
java.util.Date
### getStatus() {#getStatus--}
```
public final int getStatus()
```


Получает или задает статус задачи.

**Returns:**
int
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Получает или задает тему задачи.

**Returns:**
java.lang.String
### getTotalWork() {#getTotalWork--}
```
public final int getTotalWork()
```


Получает или задает общее количество работы, которое пользователь ожидает выполнить по задаче.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final String getUniqueId()
```


Получает или задает уникальный идентификатор

**Returns:**
java.lang.String
### getUniqueUri() {#getUniqueUri--}
```
public final String getUniqueUri()
```


Получает или задает уникальный URI задачи.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBodyHtml() {#isBodyHtml--}
```
public final boolean isBodyHtml()
```


Получает или задает значение, указывающее, является ли тело задачи в формате HTML.

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




### request() {#request--}
```
public final AlternateView request()
```


Запрашивает объект.

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Сохраняет текущий объект в указанный поток, используя формат MSG.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения. |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int saveFormat)
```


Сохраняет текущий объект в указанный поток, используя указанный формат.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения. |
| saveFormat | int | Формат сохранения. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Сохраняет текущий объект в файл, используя формат MSG.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Имя файла. |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public void save(String filePath, int saveFormat)
```


Сохраняет текущий объект в файл, используя указанный формат.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Имя файла. |
| saveFormat | int | Формат сохранения. |

### setActualWork(int value) {#setActualWork-int-}
```
public final void setActualWork(int value)
```


Получает или задает фактическое количество времени, затрачиваемого на задачу (минуты).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setAttachments(AttachmentCollection value) {#setAttachments-com.aspose.email.AttachmentCollection-}
```
public final void setAttachments(AttachmentCollection value)
```


Получает или задает коллекцию файлов, прикреплённых к задаче.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [AttachmentCollection](../../com.aspose.email/attachmentcollection) |  |

### setAttendees(MailAddressCollection value) {#setAttendees-com.aspose.email.MailAddressCollection-}
```
public final void setAttendees(MailAddressCollection value)
```


Получает или задает участников.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### setBillingInformation(String value) {#setBillingInformation-java.lang.String-}
```
public final void setBillingInformation(String value)
```


Получает или задает информацию о выставлении счета для задачи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Получает или задает тело задачи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyHtml(boolean value) {#setBodyHtml-boolean-}
```
public final void setBodyHtml(boolean value)
```


Получает или задает значение, указывающее, является ли тело задачи в формате HTML.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setCompanies(System.Collections.Specialized.StringCollection value) {#setCompanies-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void setCompanies(System.Collections.Specialized.StringCollection value)
```


Получает или задает коллекцию компаний, связанных с задачей.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### setCompletionDate(Date value) {#setCompletionDate-java.util.Date-}
```
public final void setCompletionDate(Date value)
```


Получает или задает дату, когда пользователь завершил работу над задачей.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setDueDate(Date value) {#setDueDate-java.util.Date-}
```
public final void setDueDate(Date value)
```


Получает или задает дату, к которой пользователь ожидает завершения работы над задачей.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Получает или задает методы iTIP, связанные с задачей.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setMileage(String value) {#setMileage-java.lang.String-}
```
public final void setMileage(String value)
```


Получает или задает пробег для задачи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setOrganizer(MailAddress value) {#setOrganizer-com.aspose.email.MailAddress-}
```
public final void setOrganizer(MailAddress value)
```


Получает или задает организатора.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### setPercentComplete(float value) {#setPercentComplete-float-}
```
public final void setPercentComplete(float value)
```


Получает или задает процент завершения задачи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | float |  |

### setPriority(int value) {#setPriority-int-}
```
public final void setPriority(int value)
```


Получает или задает приоритет задачи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setRecurrencePattern(RecurrencePattern value) {#setRecurrencePattern-com.aspose.email.RecurrencePattern-}
```
public final void setRecurrencePattern(RecurrencePattern value)
```


Получает или задает информацию о повторении для повторяющейся задачи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [RecurrencePattern](../../com.aspose.email/recurrencepattern) |  |

### setRelatedTo(String value) {#setRelatedTo-java.lang.String-}
```
public final void setRelatedTo(String value)
```


Получает или задает связанный UID

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setReminderDate(Date value) {#setReminderDate-java.util.Date-}
```
public final void setReminderDate(Date value)
```


Получает или задает дату напоминания задачи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setSequenceId(int value) {#setSequenceId-int-}
```
public final void setSequenceId(int value)
```


Получает или задает идентификатор последовательности.

Значение: идентификатор последовательности.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Получает или задает дату начала задачи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


Получает или задает статус задачи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Получает или задает тему задачи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setTotalWork(int value) {#setTotalWork-int-}
```
public final void setTotalWork(int value)
```


Получает или задает общее количество работы, которое пользователь ожидает выполнить по задаче.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setUniqueId(String value) {#setUniqueId-java.lang.String-}
```
public final void setUniqueId(String value)
```


Получает или задает уникальный идентификатор

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setUniqueUri(String value) {#setUniqueUri-java.lang.String-}
```
public final void setUniqueUri(String value)
```


Получает или задает уникальный URI задачи.

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

