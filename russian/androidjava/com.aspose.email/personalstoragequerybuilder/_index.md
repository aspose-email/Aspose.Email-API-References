---
title: PersonalStorageQueryBuilder
second_title: Aspose.Email for Android via Java API Reference
description: Представляет построитель поискового выражения, используемого pst.
type: docs
weight: 346
url: /ru/androidjava/com.aspose.email/personalstoragequerybuilder/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MailQueryBuilder](../../com.aspose.email/mailquerybuilder)
```
public final class PersonalStorageQueryBuilder extends MailQueryBuilder
```

Представляет построитель поискового выражения, используемого pst.
## Constructors

| Constructor | Описание |
| --- | --- |
| [PersonalStorageQueryBuilder()](#PersonalStorageQueryBuilder--) | Инициализирует новый экземпляр класса [PersonalStorageQueryBuilder](../../com.aspose.email/personalstoragequerybuilder). |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findConversationThread(MessageInfo relatedMessage)](#findConversationThread-com.aspose.email.MessageInfo-) | Находит ветку разговора. |
| [getBcc()](#getBcc--) | Возвращает поле, позволяющее находить сообщения, содержащие указанную строку в поле BCC структуры конверта. |
| [getBody()](#getBody--) | Возвращает поле, позволяющее находить сообщения, содержащие указанную строку в теле сообщения. |
| [getCc()](#getCc--) | Возвращает поле, позволяющее находить сообщения, содержащие указанную строку в поле CC структуры конверта. |
| [getClass()](#getClass--) |  |
| [getContainerClass()](#getContainerClass--) | Получает папки с указанным классом сообщения. |
| [getContentsCount()](#getContentsCount--) | Ищет папки с указанным количеством содержимого. |
| [getDefaultEncoding()](#getDefaultEncoding--) | Возвращает кодировку по умолчанию (charset) для построителя запросов. |
| [getFolderName()](#getFolderName--) | Ищет папки с указанным отображаемым именем. |
| [getFrom()](#getFrom--) | Возвращает поле, позволяющее находить сообщения, содержащие указанную строку в поле FROM структуры конверта. |
| [getImportance()](#getImportance--) | Ищет сообщения с указанной важностью. |
| [getInternalDate()](#getInternalDate--) | Возвращает поле, позволяющее находить сообщения по внутренней дате. |
| [getMessageClass()](#getMessageClass--) | Получает сообщения с указанным классом сообщения. |
| [getMessageId()](#getMessageId--) | Получает поле, позволяющее находить сообщения, содержащие указанную строку в поле MessageId структуры конверта. |
| [getMessageSize()](#getMessageSize--) | Ищет сообщения с указанным размером. |
| [getOnlyFoldersCreatedByUser()](#getOnlyFoldersCreatedByUser--) | Получает папки, созданные пользователем, т.е. |
| [getQuery()](#getQuery--) | Возвращает запрос. |
| [getSentDate()](#getSentDate--) | Получает поле, позволяющее находить сообщения по дате отправки. |
| [getSubject()](#getSubject--) | Получает поле, позволяющее находить сообщения, содержащие указанную строку в поле SUBJECT структуры конверта. |
| [getText()](#getText--) | Получает поле, позволяющее находить сообщения, содержащие указанную строку в заголовках (subject, from, to, cc) и теле сообщения. |
| [getTo()](#getTo--) | Получает поле, позволяющее находить сообщения, содержащие указанную строку в поле TO структуры конверта. |
| [getUnreadContentsCount()](#getUnreadContentsCount--) | Ищет папки с указанным количеством непрочитанного содержимого. |
| [hasFlags(long flags)](#hasFlags-long-) | Ищет сообщения с указанными флагами. |
| [hasNoFlags(long flags)](#hasNoFlags-long-) | Ищет сообщения с неуказанными флагами. |
| [hasNoSubfolders()](#hasNoSubfolders--) | Поиск папок, которые не содержат подпапок. |
| [hasSubfolders()](#hasSubfolders--) | Поиск папок, которые содержат подпапки. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [or(MailQuery query1, MailQuery query2)](#or-com.aspose.email.MailQuery-com.aspose.email.MailQuery-) | Ищет сообщения, соответствующие любому из поисковых ключей. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PersonalStorageQueryBuilder() {#PersonalStorageQueryBuilder--}
```
public PersonalStorageQueryBuilder()
```


Инициализирует новый экземпляр класса [PersonalStorageQueryBuilder](../../com.aspose.email/personalstoragequerybuilder).

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
### findConversationThread(MessageInfo relatedMessage) {#findConversationThread-com.aspose.email.MessageInfo-}
```
public final MailQuery findConversationThread(MessageInfo relatedMessage)
```


Находит ветку разговора.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| relatedMessage | [MessageInfo](../../com.aspose.email/messageinfo) | Связанное сообщение. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - 
### getBcc() {#getBcc--}
```
public final StringComparisonField getBcc()
```


Возвращает поле, позволяющее находить сообщения, содержащие указанную строку в поле BCC структуры конверта.

Значение: Элемент [DateComparisonField](../../com.aspose.email/datecomparisonfield) представляет поле поиска BCC.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getBody() {#getBody--}
```
public final StringComparisonField getBody()
```


Возвращает поле, позволяющее находить сообщения, содержащие указанную строку в теле сообщения.

Значение: Элемент [DateComparisonField](../../com.aspose.email/datecomparisonfield) представляет поле поиска тела сообщения.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getCc() {#getCc--}
```
public final StringComparisonField getCc()
```


Возвращает поле, позволяющее находить сообщения, содержащие указанную строку в поле CC структуры конверта.

Значение: Элемент [DateComparisonField](../../com.aspose.email/datecomparisonfield) представляет поле поиска cc.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainerClass() {#getContainerClass--}
```
public final StringComparisonField getContainerClass()
```


Получает папки с указанным классом сообщения.

Значение: [StringComparisonField](../../com.aspose.email/stringcomparisonfield), представляющий класс контейнера.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getContentsCount() {#getContentsCount--}
```
public final IntComparisonField getContentsCount()
```


Ищет папки с указанным количеством содержимого.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getDefaultEncoding() {#getDefaultEncoding--}
```
public final Charset getDefaultEncoding()
```


Возвращает кодировку по умолчанию (charset) для построителя запросов.

**Returns:**
java.nio.charset.Charset
### getFolderName() {#getFolderName--}
```
public final StringComparisonField getFolderName()
```


Ищет папки с указанным отображаемым именем.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getFrom() {#getFrom--}
```
public final StringComparisonField getFrom()
```


Возвращает поле, позволяющее находить сообщения, содержащие указанную строку в поле FROM структуры конверта.

Значение: Элемент [DateComparisonField](../../com.aspose.email/datecomparisonfield) представляет поле поиска from.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getImportance() {#getImportance--}
```
public final IntComparisonField getImportance()
```


Ищет сообщения с указанной важностью.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getInternalDate() {#getInternalDate--}
```
public final DateComparisonField getInternalDate()
```


Возвращает поле, позволяющее находить сообщения по внутренней дате.

Значение: Элемент [DateComparisonField](../../com.aspose.email/datecomparisonfield) представляет поле поиска внутренней даты.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getMessageClass() {#getMessageClass--}
```
public final StringComparisonField getMessageClass()
```


Получает сообщения с указанным классом сообщения.

Значение: [StringComparisonField](../../com.aspose.email/stringcomparisonfield), представляющий класс сообщения.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getMessageId() {#getMessageId--}
```
public final StringComparisonField getMessageId()
```


Получает поле, позволяющее находить сообщения, содержащие указанную строку в поле MessageId структуры конверта.

Значение: [DateComparisonField](../../com.aspose.email/datecomparisonfield), представляющий поле поиска MessageId.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getMessageSize() {#getMessageSize--}
```
public final IntComparisonField getMessageSize()
```


Ищет сообщения с указанным размером.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### getOnlyFoldersCreatedByUser() {#getOnlyFoldersCreatedByUser--}
```
public final BoolComparisonField getOnlyFoldersCreatedByUser()
```


Получает папки, созданные пользователем, т.е. исключает все стандартные IPM‑папки.

Значение: [BoolComparisonField](../../com.aspose.email/boolcomparisonfield), представляющий поле поиска.

**Returns:**
[BoolComparisonField](../../com.aspose.email/boolcomparisonfield)
### getQuery() {#getQuery--}
```
public MailQuery getQuery()
```


Возвращает запрос.

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query.
### getSentDate() {#getSentDate--}
```
public final DateComparisonField getSentDate()
```


Получает поле, позволяющее находить сообщения по дате отправки.

Значение: Элемент [DateComparisonField](../../com.aspose.email/datecomparisonfield) представляет поле поиска даты отправки.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getSubject() {#getSubject--}
```
public final StringComparisonField getSubject()
```


Получает поле, позволяющее находить сообщения, содержащие указанную строку в поле SUBJECT структуры конверта.

Значение: Элемент [DateComparisonField](../../com.aspose.email/datecomparisonfield) представляет поле поиска темы.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getText() {#getText--}
```
public final StringComparisonField getText()
```


Получает поле, позволяющее находить сообщения, содержащие указанную строку в заголовках (subject, from, to, cc) и теле сообщения.

Значение: Элемент [DateComparisonField](../../com.aspose.email/datecomparisonfield) представляет поля поиска текстовых заголовков или тела.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getTo() {#getTo--}
```
public final StringComparisonField getTo()
```


Получает поле, позволяющее находить сообщения, содержащие указанную строку в поле TO структуры конверта.

Значение: Элемент [DateComparisonField](../../com.aspose.email/datecomparisonfield) представляет поле поиска TO.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getUnreadContentsCount() {#getUnreadContentsCount--}
```
public final IntComparisonField getUnreadContentsCount()
```


Ищет папки с указанным количеством непрочитанного содержимого.

**Returns:**
[IntComparisonField](../../com.aspose.email/intcomparisonfield)
### hasFlags(long flags) {#hasFlags-long-}
```
public final MailQuery hasFlags(long flags)
```


Ищет сообщения с указанными флагами.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| flags | long | Флаги. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
### hasNoFlags(long flags) {#hasNoFlags-long-}
```
public final MailQuery hasNoFlags(long flags)
```


Ищет сообщения с неуказанными флагами.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| flags | long | Флаги. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
### hasNoSubfolders() {#hasNoSubfolders--}
```
public final MailQuery hasNoSubfolders()
```


Поиск папок, которые не содержат подпапок.

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
### hasSubfolders() {#hasSubfolders--}
```
public final MailQuery hasSubfolders()
```


Поиск папок, которые содержат подпапки.

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criteria).
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




### or(MailQuery query1, MailQuery query2) {#or-com.aspose.email.MailQuery-com.aspose.email.MailQuery-}
```
public MailQuery or(MailQuery query1, MailQuery query2)
```


Ищет сообщения, соответствующие любому из поисковых ключей. Обеспечивает дизъюнкцию между двумя выражениями (OR).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| query1 | [MailQuery](../../com.aspose.email/mailquery) | Элемент query1. |
| query2 | [MailQuery](../../com.aspose.email/mailquery) | Элемент query2. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
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

