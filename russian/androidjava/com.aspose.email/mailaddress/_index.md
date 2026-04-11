---
title: MailAddress
second_title: Aspose.Email for Android via Java API Reference
description: Представляет адрес сообщения.
type: docs
weight: 188
url: /ru/androidjava/com.aspose.email/mailaddress/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IMailAddress](../../com.aspose.email/imailaddress)
```
public class MailAddress implements IMailAddress
```

Представляет адрес сообщения.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MailAddress(String address, boolean ignoreSmtpCheck)](#MailAddress-java.lang.String-boolean-) | Инициализирует новый экземпляр класса [MailAddress](../../com.aspose.email/mailaddress). |
| [MailAddress(String address, String displayName, boolean ignoreSmtpCheck)](#MailAddress-java.lang.String-java.lang.String-boolean-) | Инициализирует новый экземпляр класса [MailAddress](../../com.aspose.email/mailaddress). |
| [MailAddress(String address, String displayName, Charset displayNameEncoding)](#MailAddress-java.lang.String-java.lang.String-java.nio.charset.Charset-) | Инициализирует новый экземпляр класса [MailAddress](../../com.aspose.email/mailaddress). |
| [MailAddress(String address, String displayName, Charset displayNameEncoding, boolean ignoreSmtpCheck)](#MailAddress-java.lang.String-java.lang.String-java.nio.charset.Charset-boolean-) | Инициализирует новый экземпляр класса [MailAddress](../../com.aspose.email/mailaddress). |
| [MailAddress(String address)](#MailAddress-java.lang.String-) | Инициализирует новый экземпляр класса [MailAddress](../../com.aspose.email/mailaddress). |
| [MailAddress(String address, String displayName)](#MailAddress-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса [MailAddress](../../com.aspose.email/mailaddress). |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный Object текущему экземпляру. |
| [getAddress()](#getAddress--) | Получает или задает адрес электронной почты. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Содержит количество почтовых адресов. |
| [getDisplayName()](#getDisplayName--) | Получает или задает отображаемое имя. |
| [getHost()](#getHost--) | Получает часть адреса, содержащую хост. |
| [getId()](#getId--) | Gets object identification information |
| [getOriginalAddressString()](#getOriginalAddressString--) | Получает или задает исходную строку e-mail адреса. |
| [getParticipationStatus()](#getParticipationStatus--) | Получает или задает статус участия для пользователя календаря. |
| [getUser()](#getUser--) | Получает имя пользователя. |
| [get_Item(int i)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddress(String value)](#setAddress-java.lang.String-) | Получает или задает адрес электронной почты. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Получает или задает отображаемое имя. |
| [setParticipationStatus(int value)](#setParticipationStatus-int-) | Получает или задает статус участия для пользователя календаря. |
| [toString()](#toString--) | Возвращает String, представляющий этот экземпляр. |
| [to_MailAddress(MailAddressCollection addresses)](#to-MailAddress-com.aspose.email.MailAddressCollection-) | Выполняет неявное преобразование из [MailAddressCollection](../../com.aspose.email/mailaddresscollection) в [MailAddress](../../com.aspose.email/mailaddress). |
| [to_MailAddress(String address)](#to-MailAddress-java.lang.String-) | Выполняет неявное преобразование из String в [MailAddress](../../com.aspose.email/mailaddress). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailAddress(String address, boolean ignoreSmtpCheck) {#MailAddress-java.lang.String-boolean-}
```
public MailAddress(String address, boolean ignoreSmtpCheck)
```


Инициализирует новый экземпляр класса [MailAddress](../../com.aspose.email/mailaddress).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| адрес | java.lang.String | Адрес электронной почты. |
| ignoreSmtpCheck | boolean | если установить в  true , то проверка SMTP будет пропущена. |

### MailAddress(String address, String displayName, boolean ignoreSmtpCheck) {#MailAddress-java.lang.String-java.lang.String-boolean-}
```
public MailAddress(String address, String displayName, boolean ignoreSmtpCheck)
```


Инициализирует новый экземпляр класса [MailAddress](../../com.aspose.email/mailaddress).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| адрес | java.lang.String | Адрес электронной почты. |
| displayName | java.lang.String | The display name. |
| ignoreSmtpCheck | boolean | если установить в  true , то проверка SMTP будет пропущена. |

### MailAddress(String address, String displayName, Charset displayNameEncoding) {#MailAddress-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public MailAddress(String address, String displayName, Charset displayNameEncoding)
```


Инициализирует новый экземпляр класса [MailAddress](../../com.aspose.email/mailaddress).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| адрес | java.lang.String | Адрес электронной почты. |
| displayName | java.lang.String | The display name. |
| displayNameEncoding | java.nio.charset.Charset | Кодировка отображаемого имени. |

### MailAddress(String address, String displayName, Charset displayNameEncoding, boolean ignoreSmtpCheck) {#MailAddress-java.lang.String-java.lang.String-java.nio.charset.Charset-boolean-}
```
public MailAddress(String address, String displayName, Charset displayNameEncoding, boolean ignoreSmtpCheck)
```


Инициализирует новый экземпляр класса [MailAddress](../../com.aspose.email/mailaddress).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| адрес | java.lang.String | Адрес электронной почты. |
| displayName | java.lang.String | The display name. |
| displayNameEncoding | java.nio.charset.Charset | Кодировка отображаемого имени. |
| ignoreSmtpCheck | boolean | если установить в  true , то проверка SMTP будет пропущена. |

### MailAddress(String address) {#MailAddress-java.lang.String-}
```
public MailAddress(String address)
```


Инициализирует новый экземпляр класса [MailAddress](../../com.aspose.email/mailaddress).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| адрес | java.lang.String | Адрес электронной почты. |

### MailAddress(String address, String displayName) {#MailAddress-java.lang.String-java.lang.String-}
```
public MailAddress(String address, String displayName)
```


Инициализирует новый экземпляр класса [MailAddress](../../com.aspose.email/mailaddress).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| адрес | java.lang.String | Адрес электронной почты. |
| displayName | java.lang.String | The display name. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный Object текущему экземпляру.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Object для сравнения с этим экземпляром. |

**Returns:**
boolean —  true  если указанный Object равен этому экземпляру; иначе,  false .
### getAddress() {#getAddress--}
```
public final String getAddress()
```


Получает или задает адрес электронной почты.

Значение: Строка, содержащая адрес электронной почты.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public final int getCount()
```


Содержит количество почтовых адресов.

**Returns:**
int
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Получает или задает отображаемое имя.

Значение: Строка, содержащая отображаемое имя.

**Returns:**
java.lang.String
### getHost() {#getHost--}
```
public final String getHost()
```


Получает часть адреса, содержащую хост.

Значение: Строка, содержащая имя хоста.

**Returns:**
java.lang.String
### getId() {#getId--}
```
public final ObjectIdentifier getId()
```


Gets object identification information

**Returns:**
[ObjectIdentifier](../../com.aspose.email/objectidentifier)
### getOriginalAddressString() {#getOriginalAddressString--}
```
public final String getOriginalAddressString()
```


Получает или задает исходную строку e-mail адреса.

Значение: Строка, содержащая оригинальный адрес электронной почты.

**Returns:**
java.lang.String
### getParticipationStatus() {#getParticipationStatus--}
```
public final int getParticipationStatus()
```


Получает или задает статус участия для пользователя календаря.

**Returns:**
int
### getUser() {#getUser--}
```
public final String getUser()
```


Получает имя пользователя.

Значение: Строка, содержащая имя пользователя.

**Returns:**
java.lang.String
### get_Item(int i) {#get-Item-int-}
```
public final MailAddress get_Item(int i)
```


Получает элемент по указанному индексу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| i | int | Нулевой индекс элемента для получения или установки. |

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress) - Returns the element at the specified index.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int — Хеш‑код этого экземпляра, пригодный для использования в алгоритмах хеширования и структурах данных, таких как хеш‑таблица.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


Получает или задает адрес электронной почты.

Значение: Строка, содержащая адрес электронной почты.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Получает или задает отображаемое имя.

Значение: Строка, содержащая отображаемое имя.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setParticipationStatus(int value) {#setParticipationStatus-int-}
```
public final void setParticipationStatus(int value)
```


Получает или задает статус участия для пользователя календаря.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает String, представляющий этот экземпляр.

**Returns:**
java.lang.String — Строка, представляющая этот экземпляр.
### to_MailAddress(MailAddressCollection addresses) {#to-MailAddress-com.aspose.email.MailAddressCollection-}
```
public static MailAddress to_MailAddress(MailAddressCollection addresses)
```


Выполняет неявное преобразование из [MailAddressCollection](../../com.aspose.email/mailaddresscollection) в [MailAddress](../../com.aspose.email/mailaddress).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| addresses | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | Коллекция адресов. |

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress) - The result of the conversion.
### to_MailAddress(String address) {#to-MailAddress-java.lang.String-}
```
public static MailAddress to_MailAddress(String address)
```


Выполняет неявное преобразование из String в [MailAddress](../../com.aspose.email/mailaddress).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| адрес | java.lang.String | Адрес. |

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress) - The result of the conversion.
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

