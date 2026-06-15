---
title: ContactQueryBuilder
second_title: Aspose.Email for Android via Java API Reference
description: Представляет построитель поискового выражения, используемый протоколом Exchange.
type: docs
weight: 82
url: /ru/androidjava/com.aspose.email/contactquerybuilder/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MailQueryBuilder](../../com.aspose.email/mailquerybuilder)
```
public final class ContactQueryBuilder extends MailQueryBuilder
```

Представляет построитель поискового выражения, используемый протоколом Exchange.
## Constructors

| Constructor | Описание |
| --- | --- |
| [ContactQueryBuilder()](#ContactQueryBuilder--) | Инициализирует новый экземпляр класса  ContactQueryBuilder  . |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBcc()](#getBcc--) | Возвращает поле, позволяющее находить сообщения, содержащие указанную строку в поле BCC структуры конверта. |
| [getBody()](#getBody--) | Возвращает поле, позволяющее находить сообщения, содержащие указанную строку в теле сообщения. |
| [getCc()](#getCc--) | Возвращает поле, позволяющее находить сообщения, содержащие указанную строку в поле CC структуры конверта. |
| [getClass()](#getClass--) |  |
| [getContactCreationTime()](#getContactCreationTime--) | Возвращает поле, позволяющее находить элементы с указанным CreationTime. |
| [getContactDisplayName()](#getContactDisplayName--) | Возвращает поле, позволяющее находить контакты, содержащие указанную строку в поле DisplayName. |
| [getCreationTime()](#getCreationTime--) | Возвращает поле, позволяющее находить элементы с указанным CreationTime. |
| [getDefaultEncoding()](#getDefaultEncoding--) | Возвращает кодировку по умолчанию (charset) для построителя запросов. |
| [getDisplayName()](#getDisplayName--) | Возвращает поле, позволяющее находить контакты, содержащие указанную строку в поле DisplayName. |
| [getFrom()](#getFrom--) | Возвращает поле, позволяющее находить сообщения, содержащие указанную строку в поле FROM структуры конверта. |
| [getInternalDate()](#getInternalDate--) | Возвращает поле, позволяющее находить сообщения по внутренней дате. |
| [getQuery()](#getQuery--) | Возвращает запрос. |
| [getSentDate()](#getSentDate--) | Получает поле, позволяющее находить сообщения по дате отправки. |
| [getSubject()](#getSubject--) | Получает поле, позволяющее находить сообщения, содержащие указанную строку в поле SUBJECT структуры конверта. |
| [getText()](#getText--) | Получает поле, позволяющее находить сообщения, содержащие указанную строку в заголовках (subject, from, to, cc) и теле сообщения. |
| [getTo()](#getTo--) | Получает поле, позволяющее находить сообщения, содержащие указанную строку в поле TO структуры конверта. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [or(MailQuery query1, MailQuery query2)](#or-com.aspose.email.MailQuery-com.aspose.email.MailQuery-) | Ищет сообщения, соответствующие любому из поисковых ключей. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ContactQueryBuilder() {#ContactQueryBuilder--}
```
public ContactQueryBuilder()
```


Инициализирует новый экземпляр класса  ContactQueryBuilder  .

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
### getContactCreationTime() {#getContactCreationTime--}
```
public DateComparisonField getContactCreationTime()
```


Возвращает поле, позволяющее находить элементы с указанным CreationTime.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getContactDisplayName() {#getContactDisplayName--}
```
public StringComparisonField getContactDisplayName()
```


Возвращает поле, позволяющее находить контакты, содержащие указанную строку в поле DisplayName.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getCreationTime() {#getCreationTime--}
```
public final DateComparisonField getCreationTime()
```


Возвращает поле, позволяющее находить элементы с указанным CreationTime.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getDefaultEncoding() {#getDefaultEncoding--}
```
public final Charset getDefaultEncoding()
```


Возвращает кодировку по умолчанию (charset) для построителя запросов.

**Returns:**
java.nio.charset.Charset
### getDisplayName() {#getDisplayName--}
```
public final StringComparisonField getDisplayName()
```


Возвращает поле, позволяющее находить контакты, содержащие указанную строку в поле DisplayName.

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
### getInternalDate() {#getInternalDate--}
```
public final DateComparisonField getInternalDate()
```


Возвращает поле, позволяющее находить сообщения по внутренней дате.

Значение: Элемент [DateComparisonField](../../com.aspose.email/datecomparisonfield) представляет поле поиска внутренней даты.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
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

