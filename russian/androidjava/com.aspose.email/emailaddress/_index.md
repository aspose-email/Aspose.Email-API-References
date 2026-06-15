---
title: EmailAddress
second_title: Aspose.Email for Android via Java API Reference
description: Представляет адрес электронной почты
type: docs
weight: 114
url: /ru/androidjava/com.aspose.email/emailaddress/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MailAddress](../../com.aspose.email/mailaddress)

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.ms.System.IEquatable
```
public class EmailAddress extends MailAddress implements Comparable<EmailAddress>, System.IEquatable<EmailAddress>
```

Представляет адрес электронной почты
## Constructors

| Constructor | Описание |
| --- | --- |
| [EmailAddress()](#EmailAddress--) | Инициализирует новый экземпляр класса [EmailAddress](../../com.aspose.email/emailaddress). |
| [EmailAddress(String address)](#EmailAddress-java.lang.String-) | Инициализирует новый экземпляр класса [EmailAddress](../../com.aspose.email/emailaddress). |
| [EmailAddress(String address, String displayName)](#EmailAddress-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса [EmailAddress](../../com.aspose.email/emailaddress). |
## Methods

| Method | Описание |
| --- | --- |
| [compareTo(EmailAddress obj)](#compareTo-com.aspose.email.EmailAddress-) | Сравнивает текущий экземпляр с другим объектом того же типа и возвращает целое число, указывающее, предшествует ли текущий экземпляр, следует за ним или находится в той же позиции в порядке сортировки, что и другой объект. |
| [equals(EmailAddress obj)](#equals-com.aspose.email.EmailAddress-) | Определяет, равен ли указанный Object текущему Object. |
| [equals(EmailAddress x, EmailAddress y)](#equals-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-) | Определяет, считаются ли указанные экземпляры объектов равными. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный Object текущему Object. |
| [getAddress()](#getAddress--) | Получает или задает адрес электронной почты. |
| [getCategory()](#getCategory--) | Получает или задает категорию объекта |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Содержит количество почтовых адресов. |
| [getDisplayName()](#getDisplayName--) | Получает или задает отображаемое имя. |
| [getHost()](#getHost--) | Получает часть адреса, содержащую хост. |
| [getId()](#getId--) | Gets object identification information |
| [getOriginalAddressString()](#getOriginalAddressString--) | Получает или задает исходную строку e-mail адреса. |
| [getParticipationStatus()](#getParticipationStatus--) | Получает или задает статус участия для пользователя календаря. |
| [getPrefered()](#getPrefered--) | Получает или задает значение, определяющее, является ли адрес электронной почты предпочтительным. |
| [getRoutingType()](#getRoutingType--) | Получает или задает тип маршрутизации для электронной почты |
| [getUser()](#getUser--) | Получает имя пользователя. |
| [get_Item(int i)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [hashCode()](#hashCode--) | GetHashCode возвращает хеш‑функцию для этого объекта. |
| [hashCode(EmailAddress obj)](#hashCode-com.aspose.email.EmailAddress-) | GetHashCode возвращает хеш-функцию для указанного объекта. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(EmailAddress a, EmailAddress b)](#op-Equality-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-) | Определяет, равны ли указанные объекты. |
| [op_Inequality(EmailAddress a, EmailAddress b)](#op-Inequality-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-) | Определяет, не равны ли указанные объекты. |
| [setAddress(String value)](#setAddress-java.lang.String-) | Получает или задает адрес электронной почты. |
| [setCategory(EmailAddressCategory value)](#setCategory-com.aspose.email.EmailAddressCategory-) | Получает или задает категорию объекта |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Получает или задает отображаемое имя. |
| [setParticipationStatus(int value)](#setParticipationStatus-int-) | Получает или задает статус участия для пользователя календаря. |
| [setPrefered(boolean value)](#setPrefered-boolean-) | Получает или задает значение, определяющее, является ли адрес электронной почты предпочтительным. |
| [setRoutingType(String value)](#setRoutingType-java.lang.String-) | Получает или задает тип маршрутизации для электронной почты |
| [toString()](#toString--) | Возвращает строку, представляющую текущий объект. |
| [to_MailAddress(MailAddressCollection addresses)](#to-MailAddress-com.aspose.email.MailAddressCollection-) | Выполняет неявное преобразование из [MailAddressCollection](../../com.aspose.email/mailaddresscollection) в [MailAddress](../../com.aspose.email/mailaddress). |
| [to_MailAddress(String address)](#to-MailAddress-java.lang.String-) | Выполняет неявное преобразование из String в [MailAddress](../../com.aspose.email/mailaddress). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmailAddress() {#EmailAddress--}
```
public EmailAddress()
```


Инициализирует новый экземпляр класса [EmailAddress](../../com.aspose.email/emailaddress).

### EmailAddress(String address) {#EmailAddress-java.lang.String-}
```
public EmailAddress(String address)
```


Инициализирует новый экземпляр класса [EmailAddress](../../com.aspose.email/emailaddress).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| адрес | java.lang.String | Адрес электронной почты. |

### EmailAddress(String address, String displayName) {#EmailAddress-java.lang.String-java.lang.String-}
```
public EmailAddress(String address, String displayName)
```


Инициализирует новый экземпляр класса [EmailAddress](../../com.aspose.email/emailaddress).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| адрес | java.lang.String | Адрес электронной почты. |
| displayName | java.lang.String | The display name. |

### compareTo(EmailAddress obj) {#compareTo-com.aspose.email.EmailAddress-}
```
public int compareTo(EmailAddress obj)
```


Сравнивает текущий экземпляр с другим объектом того же типа и возвращает целое число, указывающее, предшествует ли текущий экземпляр, следует за ним или находится в той же позиции в порядке сортировки, что и другой объект.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| obj | [EmailAddress](../../com.aspose.email/emailaddress) | Объект для сравнения с этим экземпляром или null. |

**Returns:**
int — Этот метод возвращает: значение меньше 0, если это меньше значения; 0, если это равно значению; значение больше 0, если это больше значения.
### equals(EmailAddress obj) {#equals-com.aspose.email.EmailAddress-}
```
public final boolean equals(EmailAddress obj)
```


Определяет, равен ли указанный Object текущему Object.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| obj | [EmailAddress](../../com.aspose.email/emailaddress) | Объект для сравнения с текущим объектом. |

**Returns:**
boolean - Возвращает логическое значение, указывающее, равен ли переданный объект obj этому.
### equals(EmailAddress x, EmailAddress y) {#equals-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-}
```
public final boolean equals(EmailAddress x, EmailAddress y)
```


Определяет, считаются ли указанные экземпляры объектов равными.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| x | [EmailAddress](../../com.aspose.email/emailaddress) | Первый объект для сравнения. |
| y | [EmailAddress](../../com.aspose.email/emailaddress) | Второй объект для сравнения. |

**Returns:**
boolean — true, если объекты считаются равными; иначе false. Если оба objA и objB равны null, метод возвращает true.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный Object текущему Object.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения с текущим объектом. |

**Returns:**
boolean - Возвращает логическое значение, указывающее, равен ли переданный объект obj этому.
### getAddress() {#getAddress--}
```
public final String getAddress()
```


Получает или задает адрес электронной почты.

Значение: Строка, содержащая адрес электронной почты.

**Returns:**
java.lang.String
### getCategory() {#getCategory--}
```
public final EmailAddressCategory getCategory()
```


Получает или задает категорию объекта

**Returns:**
[EmailAddressCategory](../../com.aspose.email/emailaddresscategory)
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
### getPrefered() {#getPrefered--}
```
public final boolean getPrefered()
```


Получает или задает значение, определяющее, является ли адрес электронной почты предпочтительным.

**Returns:**
boolean
### getRoutingType() {#getRoutingType--}
```
public final String getRoutingType()
```


Получает или задает тип маршрутизации для электронной почты

**Returns:**
java.lang.String
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


GetHashCode возвращает хеш‑функцию для этого объекта.

**Returns:**
int - Возвращает хеш-функцию для этого объекта.
### hashCode(EmailAddress obj) {#hashCode-com.aspose.email.EmailAddress-}
```
public final int hashCode(EmailAddress obj)
```


GetHashCode возвращает хеш-функцию для указанного объекта.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| obj | [EmailAddress](../../com.aspose.email/emailaddress) | Объект, для которого необходимо вернуть хеш-код. |

**Returns:**
int — Возвращает хеш-функцию для указанного объекта.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(EmailAddress a, EmailAddress b) {#op-Equality-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-}
```
public static boolean op_Equality(EmailAddress a, EmailAddress b)
```


Определяет, равны ли указанные объекты.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| a | [EmailAddress](../../com.aspose.email/emailaddress) | Первый объект для сравнения |
| b | [EmailAddress](../../com.aspose.email/emailaddress) | Второй объект для сравнения |

**Returns:**
boolean — Возвращает true, если объекты равны, иначе false.
### op_Inequality(EmailAddress a, EmailAddress b) {#op-Inequality-com.aspose.email.EmailAddress-com.aspose.email.EmailAddress-}
```
public static boolean op_Inequality(EmailAddress a, EmailAddress b)
```


Определяет, не равны ли указанные объекты.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| a | [EmailAddress](../../com.aspose.email/emailaddress) | Первый объект для сравнения |
| b | [EmailAddress](../../com.aspose.email/emailaddress) | Второй объект для сравнения |

**Returns:**
boolean — Возвращает true, если объекты не равны, иначе false.
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

### setCategory(EmailAddressCategory value) {#setCategory-com.aspose.email.EmailAddressCategory-}
```
public final void setCategory(EmailAddressCategory value)
```


Получает или задает категорию объекта

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [EmailAddressCategory](../../com.aspose.email/emailaddresscategory) |  |

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

### setPrefered(boolean value) {#setPrefered-boolean-}
```
public final void setPrefered(boolean value)
```


Получает или задает значение, определяющее, является ли адрес электронной почты предпочтительным.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setRoutingType(String value) {#setRoutingType-java.lang.String-}
```
public final void setRoutingType(String value)
```


Получает или задает тип маршрутизации для электронной почты

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую текущий объект.

**Returns:**
java.lang.String — Возвращает строку, представляющую текущий объект.
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

