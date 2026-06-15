---
title: MessageStore
second_title: Aspose.Email for Android via Java API Reference
description: Хранилище сообщений является корнем PST, что примерно соответствует верхней части почтового ящика.
type: docs
weight: 318
url: /ru/androidjava/com.aspose.email/messagestore/
---

**Inheritance:**
java.lang.Object
```
public class MessageStore
```

Хранилище сообщений является корнем PST, что примерно соответствует верхнему уровню почтового ящика.
## Methods

| Method | Описание |
| --- | --- |
| [changeDisplayName(String newName)](#changeDisplayName-java.lang.String-) | Изменяет отображаемое имя PST. |
| [changePassword(String password)](#changePassword-java.lang.String-) | Устанавливает пароль. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisplayName()](#getDisplayName--) | Получает отображаемое имя PST. |
| [getProperties()](#getProperties--) | Получает свойства MAPI объекта хранилища сообщений. |
| [hashCode()](#hashCode--) |  |
| [isPasswordProtected()](#isPasswordProtected--) | Получает значение, указывающее, защищено ли хранилище паролем. |
| [isPasswordValid(String password)](#isPasswordValid-java.lang.String-) | Определяет, является ли указанная строка действительным паролем для хранилища. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setProperty(MapiProperty property)](#setProperty-com.aspose.email.MapiProperty-) | Устанавливает свойство. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### changeDisplayName(String newName) {#changeDisplayName-java.lang.String-}
```
public final void changeDisplayName(String newName)
```


Изменяет отображаемое имя PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| newName | java.lang.String | Новое отображаемое имя хранилища сообщений. |

### changePassword(String password) {#changePassword-java.lang.String-}
```
public final void changePassword(String password)
```


Устанавливает пароль.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| пароль | java.lang.String | Строка, представляющая пароль. |

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
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Получает отображаемое имя PST.

Значение: Строка, представляющая отображаемое имя.

**Returns:**
java.lang.String
### getProperties() {#getProperties--}
```
public final MapiPropertyCollection getProperties()
```


Получает свойства MAPI объекта хранилища сообщений. Хранилище сообщений содержит настройки PST верхнего уровня и метаданные, необходимые для доступа и управления содержимым PST.

Значение: Коллекция [MapiProperty](../../com.aspose.email/mapiproperty).

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Получает значение, указывающее, защищено ли хранилище паролем.

Значение:  true  если хранилище защищено паролем; иначе,  false .

**Returns:**
boolean
### isPasswordValid(String password) {#isPasswordValid-java.lang.String-}
```
public final boolean isPasswordValid(String password)
```


Определяет, является ли указанная строка действительным паролем для хранилища.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| пароль | java.lang.String | Строка пароля. |

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




### setProperty(MapiProperty property) {#setProperty-com.aspose.email.MapiProperty-}
```
public final void setProperty(MapiProperty property)
```


Устанавливает свойство.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | Свойство. |

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

