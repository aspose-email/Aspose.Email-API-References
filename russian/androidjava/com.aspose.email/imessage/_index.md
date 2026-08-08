---
title: IMessage
second_title: Aspose.Email for Android via Java API Reference
description: Представляет общий интерфейс сообщения
type: docs
weight: 459
url: /ru/androidjava/com.aspose.email/imessage/
---
```
public interface IMessage
```

Представляет общий интерфейс сообщения
## Methods

| Method | Описание |
| --- | --- |
| [getAttachments()](#getAttachments--) | Получает вложения сообщения |
| [getBcc()](#getBcc--) | Получает получателей BCC |
| [getBody()](#getBody--) | Получает или задает тело сообщения |
| [getBodyType()](#getBodyType--) | Получает тип тела. |
| [getCC()](#getCC--) | Получает получателей CC |
| [getDate()](#getDate--) | Получает дату и время доставки сообщения |
| [getFrom()](#getFrom--) | Получает или задает адрес отправителя |
| [getHtmlBody()](#getHtmlBody--) | Получает или задает тело сообщения в формате HTML |
| [getSubject()](#getSubject--) | Получает или задает тему сообщения |
| [getTo()](#getTo--) | Получает получателей |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет сообщение в указанный поток |
| [save(String fileName)](#save-java.lang.String-) | Сохраняет сообщение в указанный файл |
| [setBody(String value)](#setBody-java.lang.String-) | Получает или задает тело сообщения |
| [setFrom(IMailAddress value)](#setFrom-com.aspose.email.IMailAddress-) | Получает или задает адрес отправителя |
| [setHtmlBody(String value)](#setHtmlBody-java.lang.String-) | Получает или задает тело сообщения в формате HTML |
| [setSubject(String value)](#setSubject-java.lang.String-) | Получает или задает тему сообщения |
### getAttachments() {#getAttachments--}
```
public abstract System.Collections.Generic.IGenericCollection<Attachment> getAttachments()
```


Получает вложения сообщения

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.Attachment>
### getBcc() {#getBcc--}
```
public abstract System.Collections.Generic.IGenericCollection<MailAddress> getBcc()
```


Получает получателей BCC

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.MailAddress>
### getBody() {#getBody--}
```
public abstract String getBody()
```


Получает или задает тело сообщения

**Returns:**
java.lang.String
### getBodyType() {#getBodyType--}
```
public abstract int getBodyType()
```


Получает тип тела.

**Returns:**
int
### getCC() {#getCC--}
```
public abstract System.Collections.Generic.IGenericCollection<MailAddress> getCC()
```


Получает получателей CC

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.MailAddress>
### getDate() {#getDate--}
```
public abstract Date getDate()
```


Получает дату и время доставки сообщения

**Returns:**
java.util.Date
### getFrom() {#getFrom--}
```
public abstract IMailAddress getFrom()
```


Получает или задает адрес отправителя

**Returns:**
[IMailAddress](../../com.aspose.email/imailaddress)
### getHtmlBody() {#getHtmlBody--}
```
public abstract String getHtmlBody()
```


Получает или задает тело сообщения в формате HTML

**Returns:**
java.lang.String
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Получает или задает тему сообщения

**Returns:**
java.lang.String
### getTo() {#getTo--}
```
public abstract System.Collections.Generic.IGenericCollection<MailAddress> getTo()
```


Получает получателей

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.email.MailAddress>
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream stream)
```


Сохраняет сообщение в указанный поток

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения |

### save(String fileName) {#save-java.lang.String-}
```
public abstract void save(String fileName)
```


Сохраняет сообщение в указанный файл

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла |

### setBody(String value) {#setBody-java.lang.String-}
```
public abstract void setBody(String value)
```


Получает или задает тело сообщения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setFrom(IMailAddress value) {#setFrom-com.aspose.email.IMailAddress-}
```
public abstract void setFrom(IMailAddress value)
```


Получает или задает адрес отправителя

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [IMailAddress](../../com.aspose.email/imailaddress) |  |

### setHtmlBody(String value) {#setHtmlBody-java.lang.String-}
```
public abstract void setHtmlBody(String value)
```


Получает или задает тело сообщения в формате HTML

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```


Получает или задает тему сообщения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

