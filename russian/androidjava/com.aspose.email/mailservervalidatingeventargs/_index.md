---
title: MailServerValidatingEventArgs
second_title: Aspose.Email for Android via Java API Reference
description: Предоставляет данные для события MailServerValidatingEvent.
type: docs
weight: 198
url: /ru/androidjava/com.aspose.email/mailservervalidatingeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.aspose.email.SyntaxValidatingEventArgs](../../com.aspose.email/syntaxvalidatingeventargs), [com.aspose.email.DomainValidatingEventArgs](../../com.aspose.email/domainvalidatingeventargs)
```
public class MailServerValidatingEventArgs extends DomainValidatingEventArgs
```

Предоставляет данные для события MailServerValidatingEvent.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MailServerValidatingEventArgs(String mail, MailAddress mailaddress, String[] mailExchangeList)](#MailServerValidatingEventArgs-java.lang.String-com.aspose.email.MailAddress-java.lang.String---) | Инициализирует новый экземпляр класса SyntaxValidatingEventArgs. |
## Поля

| Поле | Описание |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDomain()](#getDomain--) | Получает домен. |
| [getMail()](#getMail--) | Получает проверяемый адрес электронной почты. |
| [getMailAddress()](#getMailAddress--) | Получает адрес электронной почты. |
| [getMailExchangeServers()](#getMailExchangeServers--) | Получает список серверов обмена почтой. |
| [getMailExchangeServers_MailServerValidatingEventArgs_New()](#getMailExchangeServers-MailServerValidatingEventArgs-New--) | Получает список серверов обмена почтой. |
| [getResult()](#getResult--) | Получает или задает результат проверки. |
| [getSkip()](#getSkip--) | Указывает, следует ли игнорировать проверку. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setResult(ValidationResult value)](#setResult-com.aspose.email.ValidationResult-) | Получает или задает результат проверки. |
| [setSkip(boolean value)](#setSkip-boolean-) | Указывает, следует ли игнорировать проверку. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailServerValidatingEventArgs(String mail, MailAddress mailaddress, String[] mailExchangeList) {#MailServerValidatingEventArgs-java.lang.String-com.aspose.email.MailAddress-java.lang.String---}
```
public MailServerValidatingEventArgs(String mail, MailAddress mailaddress, String[] mailExchangeList)
```


Инициализирует новый экземпляр класса SyntaxValidatingEventArgs.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| mail | java.lang.String | Строка, содержащая оригинальную копию адреса электронной почты. |
| mailaddress | [MailAddress](../../com.aspose.email/mailaddress) | Объект MailAddress. |
| mailExchangeList | java.lang.String[] | Набор списка серверов обмена почтой. |

### Empty {#Empty}
```
public static final System.EventArgs Empty
```


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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDomain() {#getDomain--}
```
public final String getDomain()
```


Получает домен.

**Returns:**
java.lang.String
### getMail() {#getMail--}
```
public final String getMail()
```


Получает проверяемый адрес электронной почты.

**Returns:**
java.lang.String
### getMailAddress() {#getMailAddress--}
```
public final MailAddress getMailAddress()
```


Получает адрес электронной почты.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### getMailExchangeServers() {#getMailExchangeServers--}
```
public final String[] getMailExchangeServers()
```


Получает список серверов обмена почтой.

**Returns:**
java.lang.String[]
### getMailExchangeServers_MailServerValidatingEventArgs_New() {#getMailExchangeServers-MailServerValidatingEventArgs-New--}
```
public final String[] getMailExchangeServers_MailServerValidatingEventArgs_New()
```


Получает список серверов обмена почтой.

**Returns:**
java.lang.String[]
### getResult() {#getResult--}
```
public final ValidationResult getResult()
```


Получает или задает результат проверки.

**Returns:**
[ValidationResult](../../com.aspose.email/validationresult)
### getSkip() {#getSkip--}
```
public final boolean getSkip()
```


Указывает, следует ли игнорировать проверку.

**Returns:**
boolean
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




### setResult(ValidationResult value) {#setResult-com.aspose.email.ValidationResult-}
```
public final void setResult(ValidationResult value)
```


Получает или задает результат проверки.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [ValidationResult](../../com.aspose.email/validationresult) |  |

### setSkip(boolean value) {#setSkip-boolean-}
```
public final void setSkip(boolean value)
```


Указывает, следует ли игнорировать проверку.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

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

