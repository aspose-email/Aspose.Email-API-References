---
title: Task
second_title: Aspose.Email for Android via Java API Reference
description: Представляет информацию о задаче Exchange.
type: docs
weight: 397
url: /ru/androidjava/com.aspose.email/task/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Task implements System.IDisposable, Closeable
```

Представляет информацию о задаче Exchange.
## Constructors

| Constructor | Описание |
| --- | --- |
| [Task()](#Task--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | Освободить все ресурсы. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachments()](#getAttachments--) | Получает или задает коллекцию файлов, прикреплённых к задаче. |
| [getAttendees()](#getAttendees--) | Получает или задает участников. |
| [getBody()](#getBody--) | Получает или задает тело задачи. |
| [getClass()](#getClass--) |  |
| [getDueDate()](#getDueDate--) | Получает или задает дату, к которой пользователь ожидает завершения работы над задачей. |
| [getMethod()](#getMethod--) | Получает или задает методы iTIP, связанные с задачей. |
| [getOrganizer()](#getOrganizer--) | Получает или задает организатора. |
| [getPercentComplete()](#getPercentComplete--) | Получает или задает процент завершения задачи. |
| [getPriority()](#getPriority--) | Получает или задает приоритет задачи. |
| [getRelatedTo()](#getRelatedTo--) | Получает или задает связанный UID |
| [getSequenceId()](#getSequenceId--) | Получает или задает идентификатор последовательности. |
| [getStartDate()](#getStartDate--) | Получает или задает дату начала задачи. |
| [getSubject()](#getSubject--) | Получает или задает тему задачи. |
| [getUniqueId()](#getUniqueId--) | Получает или задает уникальный идентификатор |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [request()](#request--) | Запрашивает объект. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет текущий объект в указанный поток, используя формат MSG. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Сохраняет текущий объект в указанный поток, используя указанный формат. |
| [save(String filePath)](#save-java.lang.String-) | Сохраняет текущий объект в файл, используя формат MSG. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Сохраняет текущий объект в файл, используя указанный формат. |
| [setAttachments(AttachmentCollection value)](#setAttachments-com.aspose.email.AttachmentCollection-) | Получает или задает коллекцию файлов, прикреплённых к задаче. |
| [setAttendees(MailAddressCollection value)](#setAttendees-com.aspose.email.MailAddressCollection-) | Получает или задает участников. |
| [setBody(String value)](#setBody-java.lang.String-) | Получает или задает тело задачи. |
| [setDueDate(Date value)](#setDueDate-java.util.Date-) | Получает или задает дату, к которой пользователь ожидает завершения работы над задачей. |
| [setMethod(int value)](#setMethod-int-) | Получает или задает методы iTIP, связанные с задачей. |
| [setOrganizer(MailAddress value)](#setOrganizer-com.aspose.email.MailAddress-) | Получает или задает организатора. |
| [setPercentComplete(float value)](#setPercentComplete-float-) | Получает или задает процент завершения задачи. |
| [setPriority(int value)](#setPriority-int-) | Получает или задает приоритет задачи. |
| [setRelatedTo(String value)](#setRelatedTo-java.lang.String-) | Получает или задает связанный UID |
| [setSequenceId(int value)](#setSequenceId-int-) | Получает или задает идентификатор последовательности. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Получает или задает дату начала задачи. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Получает или задает тему задачи. |
| [setUniqueId(String value)](#setUniqueId-java.lang.String-) | Получает или задает уникальный идентификатор |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Task() {#Task--}
```
public Task()
```


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
### getRelatedTo() {#getRelatedTo--}
```
public final String getRelatedTo()
```


Получает или задает связанный UID

**Returns:**
java.lang.String
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
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Получает или задает тему задачи.

**Returns:**
java.lang.String
### getUniqueId() {#getUniqueId--}
```
public final String getUniqueId()
```


Получает или задает уникальный идентификатор

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

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Получает или задает тело задачи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setRelatedTo(String value) {#setRelatedTo-java.lang.String-}
```
public final void setRelatedTo(String value)
```


Получает или задает связанный UID

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Получает или задает тему задачи.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setUniqueId(String value) {#setUniqueId-java.lang.String-}
```
public final void setUniqueId(String value)
```


Получает или задает уникальный идентификатор

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

