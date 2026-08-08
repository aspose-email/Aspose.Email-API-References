---
title: OAuthToken
second_title: Aspose.Email for Android via Java API Reference
description: Содержит данные OAuth‑токена, такие как значение токена, тип токена, дата истечения.
type: docs
weight: 334
url: /ru/androidjava/com.aspose.email/oauthtoken/
---

**Inheritance:**
java.lang.Object
```
public class OAuthToken
```

Содержит данные OAuth‑токена, такие как значение токена, тип токена, дата истечения.
## Constructors

| Constructor | Описание |
| --- | --- |
| [OAuthToken(String token)](#OAuthToken-java.lang.String-) | Инициализирует новый экземпляр класса [OAuthToken](../../com.aspose.email/oauthtoken) |
| [OAuthToken(String token, Date expirationDate)](#OAuthToken-java.lang.String-java.util.Date-) | Инициализирует новый экземпляр класса [OAuthToken](../../com.aspose.email/oauthtoken) |
| [OAuthToken(String token, int tokenType, Date expirationDate)](#OAuthToken-java.lang.String-int-java.util.Date-) | Инициализирует новый экземпляр класса [OAuthToken](../../com.aspose.email/oauthtoken) |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный объект текущему объекту. |
| [getClass()](#getClass--) |  |
| [getExpirationDate()](#getExpirationDate--) | Получает дату истечения срока действия токена. |
| [getExpired()](#getExpired--) | Указывает, истёк ли токен |
| [getToken()](#getToken--) | Получает значение токена |
| [getTokenType()](#getTokenType--) | Получает тип OAuth‑токена |
| [hashCode()](#hashCode--) | Служит хеш-функцией для определённого типа. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает строку, представляющую текущий объект. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OAuthToken(String token) {#OAuthToken-java.lang.String-}
```
public OAuthToken(String token)
```


Инициализирует новый экземпляр класса [OAuthToken](../../com.aspose.email/oauthtoken)

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| токен | java.lang.String | Значение токена обновления |

### OAuthToken(String token, Date expirationDate) {#OAuthToken-java.lang.String-java.util.Date-}
```
public OAuthToken(String token, Date expirationDate)
```


Инициализирует новый экземпляр класса [OAuthToken](../../com.aspose.email/oauthtoken)

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| токен | java.lang.String | Значение токена доступа |
| expirationDate | java.util.Date | Дата истечения срока действия токена. |

### OAuthToken(String token, int tokenType, Date expirationDate) {#OAuthToken-java.lang.String-int-java.util.Date-}
```
public OAuthToken(String token, int tokenType, Date expirationDate)
```


Инициализирует новый экземпляр класса [OAuthToken](../../com.aspose.email/oauthtoken)

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| токен | java.lang.String | Значение токена |
| tokenType | int | Тип токена OAuth |
| expirationDate | java.util.Date | Дата истечения срока действия токена. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный объект текущему объекту.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения с текущим объектом. |

**Returns:**
boolean - true, если указанный объект равен текущему объекту; иначе false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExpirationDate() {#getExpirationDate--}
```
public final Date getExpirationDate()
```


Получает дату истечения срока действия токена.

**Returns:**
java.util.Date
### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


Указывает, истёк ли токен

**Returns:**
boolean
### getToken() {#getToken--}
```
public final String getToken()
```


Получает значение токена

**Returns:**
java.lang.String
### getTokenType() {#getTokenType--}
```
public final int getTokenType()
```


Получает тип OAuth‑токена

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит хеш-функцией для определённого типа.

**Returns:**
int — Хеш-код текущего объекта.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую текущий объект.

**Returns:**
java.lang.String — строка, представляющая текущий объект.
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

