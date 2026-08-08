---
title: EmailAddressList
second_title: Aspose.Email for Android via Java API Reference
description: Список адресов электронной почты для контакта
type: docs
weight: 116
url: /ru/androidjava/com.aspose.email/emailaddresslist/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public class EmailAddressList implements System.Collections.Generic.IGenericList<EmailAddress>
```

Список адресов электронной почты для контакта
## Constructors

| Constructor | Описание |
| --- | --- |
| [EmailAddressList()](#EmailAddressList--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [add(EmailAddress value)](#add-com.aspose.email.EmailAddress-) | Добавляет элемент в список. |
| [addItem(EmailAddress value)](#addItem-com.aspose.email.EmailAddress-) |  |
| [clear()](#clear--) | Удаляет все элементы из списка. |
| [contains(EmailAddress value)](#contains-com.aspose.email.EmailAddress-) | Определяет, содержит ли список определённое значение. |
| [containsItem(EmailAddress value)](#containsItem-com.aspose.email.EmailAddress-) |  |
| [copyTo(EmailAddress[] array, int index)](#copyTo-com.aspose.email.EmailAddress---int-) | Копирует элементы в массив, начиная с указанного индекса массива. |
| [copyToTArray(EmailAddress[] array, int index)](#copyToTArray-com.aspose.email.EmailAddress---int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEmail1()](#getEmail1--) | Адрес email1 по умолчанию. |
| [getEmail2()](#getEmail2--) | Адрес email2 по умолчанию. |
| [getEmail3()](#getEmail3--) | Адрес email3 по умолчанию. |
| [getHome()](#getHome--) | Адрес домашнего email по умолчанию. |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект, который можно использовать для синхронизации доступа к ICollection. |
| [getWork()](#getWork--) | Адрес рабочего email по умолчанию. |
| [get_Item(EmailAddressCategory category)](#get-Item-com.aspose.email.EmailAddressCategory-) | Адрес email по умолчанию для указанной категории. |
| [get_Item(int index)](#get-Item-int-) | Получает или задаёт элемент по указанному индексу. |
| [hashCode()](#hashCode--) |  |
| [indexOf(EmailAddress value)](#indexOf-com.aspose.email.EmailAddress-) | Определяет индекс конкретного элемента в списке. |
| [indexOfItem(EmailAddress value)](#indexOfItem-com.aspose.email.EmailAddress-) |  |
| [insert(int index, EmailAddress value)](#insert-int-com.aspose.email.EmailAddress-) | Вставляет элемент в список по указанному индексу. |
| [insertItem(int index, EmailAddress value)](#insertItem-int-com.aspose.email.EmailAddress-) |  |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, является ли список только для чтения. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает коллекцию. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(EmailAddress value)](#remove-com.aspose.email.EmailAddress-) | Удаляет первое вхождение указанного объекта из списка. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент списка по указанному индексу. |
| [removeItem(EmailAddress value)](#removeItem-com.aspose.email.EmailAddress-) |  |
| [setEmail1(EmailAddress value)](#setEmail1-com.aspose.email.EmailAddress-) | Адрес email1 по умолчанию. |
| [setEmail2(EmailAddress value)](#setEmail2-com.aspose.email.EmailAddress-) | Адрес email2 по умолчанию. |
| [setEmail3(EmailAddress value)](#setEmail3-com.aspose.email.EmailAddress-) | Адрес email3 по умолчанию. |
| [setHome(EmailAddress value)](#setHome-com.aspose.email.EmailAddress-) | Адрес домашнего email по умолчанию. |
| [setWork(EmailAddress value)](#setWork-com.aspose.email.EmailAddress-) | Адрес рабочего email по умолчанию. |
| [set_Item(EmailAddressCategory category, EmailAddress value)](#set-Item-com.aspose.email.EmailAddressCategory-com.aspose.email.EmailAddress-) | Адрес email по умолчанию для указанной категории. |
| [set_Item(int index, EmailAddress value)](#set-Item-int-com.aspose.email.EmailAddress-) | Получает или задаёт элемент по указанному индексу. |
| [size()](#size--) | Получает количество элементов, содержащихся в ICollection. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmailAddressList() {#EmailAddressList--}
```
public EmailAddressList()
```


### add(EmailAddress value) {#add-com.aspose.email.EmailAddress-}
```
public final void add(EmailAddress value)
```


Добавляет элемент в список.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) | Объект, который нужно добавить в список. |

### addItem(EmailAddress value) {#addItem-com.aspose.email.EmailAddress-}
```
public void addItem(EmailAddress value)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### clear() {#clear--}
```
public final void clear()
```


Удаляет все элементы из списка.

### contains(EmailAddress value) {#contains-com.aspose.email.EmailAddress-}
```
public final boolean contains(EmailAddress value)
```


Определяет, содержит ли список определённое значение.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) | Объект, который нужно найти в списке. |

**Returns:**
boolean — true, если объект найден в списке; иначе false.
### containsItem(EmailAddress value) {#containsItem-com.aspose.email.EmailAddress-}
```
public boolean containsItem(EmailAddress value)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

**Returns:**
boolean
### copyTo(EmailAddress[] array, int index) {#copyTo-com.aspose.email.EmailAddress---int-}
```
public final void copyTo(EmailAddress[] array, int index)
```


Копирует элементы в массив, начиная с указанного индекса массива.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| array | [EmailAddress\[\]](../../com.aspose.email/emailaddress) | Одномерный массив, являющийся получателем элементов, скопированных из коллекций. Массив должен иметь нулевую индексацию. |
| индекс | int | Нулевой индекс в массиве, с которого начинается копирование. |

### copyToTArray(EmailAddress[] array, int index) {#copyToTArray-com.aspose.email.EmailAddress---int-}
```
public void copyToTArray(EmailAddress[] array, int index)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| array | [EmailAddress\[\]](../../com.aspose.email/emailaddress) |  |
| индекс | int |  |

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
### getEmail1() {#getEmail1--}
```
public final EmailAddress getEmail1()
```


Адрес email1 по умолчанию.

**Returns:**
[EmailAddress](../../com.aspose.email/emailaddress)
### getEmail2() {#getEmail2--}
```
public final EmailAddress getEmail2()
```


Адрес email2 по умолчанию.

**Returns:**
[EmailAddress](../../com.aspose.email/emailaddress)
### getEmail3() {#getEmail3--}
```
public final EmailAddress getEmail3()
```


Адрес email3 по умолчанию.

**Returns:**
[EmailAddress](../../com.aspose.email/emailaddress)
### getHome() {#getHome--}
```
public final EmailAddress getHome()
```


Адрес домашнего email по умолчанию.

**Returns:**
[EmailAddress](../../com.aspose.email/emailaddress)
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Возвращает объект, который можно использовать для синхронизации доступа к ICollection.

**Returns:**
java.lang.Object - Объект, который можно использовать для синхронизации доступа к ICollection.
### getWork() {#getWork--}
```
public final EmailAddress getWork()
```


Адрес рабочего email по умолчанию.

**Returns:**
[EmailAddress](../../com.aspose.email/emailaddress)
### get_Item(EmailAddressCategory category) {#get-Item-com.aspose.email.EmailAddressCategory-}
```
public final EmailAddress get_Item(EmailAddressCategory category)
```


Адрес email по умолчанию для указанной категории.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| category | [EmailAddressCategory](../../com.aspose.email/emailaddresscategory) | Категория адреса email. |

**Returns:**
[EmailAddress](../../com.aspose.email/emailaddress) - default email address for specified category.
### get_Item(int index) {#get-Item-int-}
```
public final EmailAddress get_Item(int index)
```


Получает или задаёт элемент по указанному индексу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| индекс | int | Нулевой индекс элемента для получения или установки. |

**Returns:**
[EmailAddress](../../com.aspose.email/emailaddress) - The element at the specified index.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indexOf(EmailAddress value) {#indexOf-com.aspose.email.EmailAddress-}
```
public final int indexOf(EmailAddress value)
```


Определяет индекс конкретного элемента в списке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) | Объект, который нужно найти в списке. |

**Returns:**
int - Индекс  value , если он найден в списке; иначе -1.
### indexOfItem(EmailAddress value) {#indexOfItem-com.aspose.email.EmailAddress-}
```
public int indexOfItem(EmailAddress value)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

**Returns:**
int
### insert(int index, EmailAddress value) {#insert-int-com.aspose.email.EmailAddress-}
```
public final void insert(int index, EmailAddress value)
```


Вставляет элемент в список по указанному индексу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| индекс | int | Нулевой индекс, по которому должно быть вставлено  value . |
| value | [EmailAddress](../../com.aspose.email/emailaddress) | Объект, который нужно вставить в список. |

### insertItem(int index, EmailAddress value) {#insertItem-int-com.aspose.email.EmailAddress-}
```
public void insertItem(int index, EmailAddress value)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| индекс | int |  |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Получает значение, указывающее, является ли список только для чтения.

**Returns:**
boolean — true, если список только для чтения; иначе false.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<EmailAddress> iterator()
```


Возвращает перечислитель, который перебирает коллекцию.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.email.EmailAddress> - Объект IEnumerator, который можно использовать для перебора элементов коллекции.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(EmailAddress value) {#remove-com.aspose.email.EmailAddress-}
```
public final boolean remove(EmailAddress value)
```


Удаляет первое вхождение указанного объекта из списка.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) | Объект, который нужно удалить из списка. |

**Returns:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Удаляет элемент списка по указанному индексу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| индекс | int | Нулевой индекс элемента, который нужно удалить. |

### removeItem(EmailAddress value) {#removeItem-com.aspose.email.EmailAddress-}
```
public boolean removeItem(EmailAddress value)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

**Returns:**
boolean
### setEmail1(EmailAddress value) {#setEmail1-com.aspose.email.EmailAddress-}
```
public final void setEmail1(EmailAddress value)
```


Адрес email1 по умолчанию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### setEmail2(EmailAddress value) {#setEmail2-com.aspose.email.EmailAddress-}
```
public final void setEmail2(EmailAddress value)
```


Адрес email2 по умолчанию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### setEmail3(EmailAddress value) {#setEmail3-com.aspose.email.EmailAddress-}
```
public final void setEmail3(EmailAddress value)
```


Адрес email3 по умолчанию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### setHome(EmailAddress value) {#setHome-com.aspose.email.EmailAddress-}
```
public final void setHome(EmailAddress value)
```


Адрес домашнего email по умолчанию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### setWork(EmailAddress value) {#setWork-com.aspose.email.EmailAddress-}
```
public final void setWork(EmailAddress value)
```


Адрес рабочего email по умолчанию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### set_Item(EmailAddressCategory category, EmailAddress value) {#set-Item-com.aspose.email.EmailAddressCategory-com.aspose.email.EmailAddress-}
```
public final void set_Item(EmailAddressCategory category, EmailAddress value)
```


Адрес email по умолчанию для указанной категории.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| category | [EmailAddressCategory](../../com.aspose.email/emailaddresscategory) | Категория адреса email. |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### set_Item(int index, EmailAddress value) {#set-Item-int-com.aspose.email.EmailAddress-}
```
public final void set_Item(int index, EmailAddress value)
```


Получает или задаёт элемент по указанному индексу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| индекс | int | Нулевой индекс элемента для получения или установки. |
| value | [EmailAddress](../../com.aspose.email/emailaddress) |  |

### size() {#size--}
```
public final int size()
```


Получает количество элементов, содержащихся в ICollection.

**Returns:**
int — количество элементов, содержащихся в ICollection.
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

