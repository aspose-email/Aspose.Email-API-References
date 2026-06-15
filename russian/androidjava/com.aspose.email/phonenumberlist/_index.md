---
title: PhoneNumberList
second_title: Aspose.Email for Android via Java API Reference
description: Список телефонных номеров контакта.
type: docs
weight: 349
url: /ru/androidjava/com.aspose.email/phonenumberlist/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public class PhoneNumberList implements System.Collections.Generic.IGenericList<PhoneNumber>
```

Список телефонных номеров контакта.
## Constructors

| Constructor | Описание |
| --- | --- |
| [PhoneNumberList()](#PhoneNumberList--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [add(PhoneNumber value)](#add-com.aspose.email.PhoneNumber-) | Добавляет элемент в список. |
| [addItem(PhoneNumber value)](#addItem-com.aspose.email.PhoneNumber-) |  |
| [clear()](#clear--) | Удаляет все элементы из списка. |
| [contains(PhoneNumber value)](#contains-com.aspose.email.PhoneNumber-) | Определяет, содержит ли список определённое значение. |
| [containsItem(PhoneNumber value)](#containsItem-com.aspose.email.PhoneNumber-) |  |
| [copyTo(PhoneNumber[] array, int index)](#copyTo-com.aspose.email.PhoneNumber---int-) | Копирует элементы в массив, начиная с указанного индекса массива. |
| [copyToTArray(PhoneNumber[] array, int index)](#copyToTArray-com.aspose.email.PhoneNumber---int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssistant()](#getAssistant--) | Номер телефона помощника по умолчанию |
| [getCallback()](#getCallback--) | Номер обратного звонка по умолчанию |
| [getCar()](#getCar--) | Номер автомобильного телефона по умолчанию |
| [getClass()](#getClass--) |  |
| [getCompany()](#getCompany--) | Номер телефона компании по умолчанию |
| [getCustom()](#getCustom--) | Категория пользовательского телефона по умолчанию |
| [getFax()](#getFax--) | Номер факса по умолчанию |
| [getHome()](#getHome--) | Номер домашнего телефона по умолчанию |
| [getHomeFax()](#getHomeFax--) | Номер домашнего факса по умолчанию |
| [getIsdn()](#getIsdn--) | Номер ISDN телефона по умолчанию |
| [getMobile()](#getMobile--) | Номер мобильного телефона по умолчанию |
| [getPager()](#getPager--) | Номер пейджера по умолчанию |
| [getPrefered()](#getPrefered--) | Основной номер телефона по умолчанию |
| [getRadio()](#getRadio--) | Номер радиотелефона по умолчанию |
| [getTelex()](#getTelex--) | Телекс по умолчанию |
| [getTtyTdd()](#getTtyTdd--) | Tty/Tdd по умолчанию |
| [getWork()](#getWork--) | Рабочий телефон по умолчанию |
| [getWorkFax()](#getWorkFax--) | Рабочий факс по умолчанию |
| [get_Item(int index)](#get-Item-int-) | Получает или задаёт элемент по указанному индексу. |
| [hashCode()](#hashCode--) |  |
| [indexOf(PhoneNumber value)](#indexOf-com.aspose.email.PhoneNumber-) | Определяет индекс конкретного элемента в списке. |
| [indexOfItem(PhoneNumber value)](#indexOfItem-com.aspose.email.PhoneNumber-) |  |
| [insert(int index, PhoneNumber value)](#insert-int-com.aspose.email.PhoneNumber-) | Вставляет элемент в список по указанному индексу. |
| [insertItem(int index, PhoneNumber value)](#insertItem-int-com.aspose.email.PhoneNumber-) |  |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, является ли список только для чтения. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает коллекцию. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(PhoneNumber value)](#remove-com.aspose.email.PhoneNumber-) | Удаляет первое вхождение указанного объекта из списка. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент списка по указанному индексу. |
| [removeItem(PhoneNumber value)](#removeItem-com.aspose.email.PhoneNumber-) |  |
| [setAssistant(String value)](#setAssistant-java.lang.String-) | Номер телефона помощника по умолчанию |
| [setCallback(String value)](#setCallback-java.lang.String-) | Номер обратного звонка по умолчанию |
| [setCar(String value)](#setCar-java.lang.String-) | Номер автомобильного телефона по умолчанию |
| [setCompany(String value)](#setCompany-java.lang.String-) | Номер телефона компании по умолчанию |
| [setCustom(String value)](#setCustom-java.lang.String-) | Категория пользовательского телефона по умолчанию |
| [setFax(String value)](#setFax-java.lang.String-) | Номер факса по умолчанию |
| [setHome(String value)](#setHome-java.lang.String-) | Номер домашнего телефона по умолчанию |
| [setHomeFax(String value)](#setHomeFax-java.lang.String-) | Номер домашнего факса по умолчанию |
| [setIsdn(String value)](#setIsdn-java.lang.String-) | Номер ISDN телефона по умолчанию |
| [setMobile(String value)](#setMobile-java.lang.String-) | Номер мобильного телефона по умолчанию |
| [setPager(String value)](#setPager-java.lang.String-) | Номер пейджера по умолчанию |
| [setPrefered(String value)](#setPrefered-java.lang.String-) | Основной номер телефона по умолчанию |
| [setRadio(String value)](#setRadio-java.lang.String-) | Номер радиотелефона по умолчанию |
| [setTelex(String value)](#setTelex-java.lang.String-) | Телекс по умолчанию |
| [setTtyTdd(String value)](#setTtyTdd-java.lang.String-) | Tty/Tdd по умолчанию |
| [setWork(String value)](#setWork-java.lang.String-) | Рабочий телефон по умолчанию |
| [setWorkFax(String value)](#setWorkFax-java.lang.String-) | Рабочий факс по умолчанию |
| [set_Item(int index, PhoneNumber value)](#set-Item-int-com.aspose.email.PhoneNumber-) | Получает или задаёт элемент по указанному индексу. |
| [size()](#size--) | Получает количество элементов, содержащихся в ICollection. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhoneNumberList() {#PhoneNumberList--}
```
public PhoneNumberList()
```


### add(PhoneNumber value) {#add-com.aspose.email.PhoneNumber-}
```
public final void add(PhoneNumber value)
```


Добавляет элемент в список.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) | Объект, который нужно добавить в список. |

### addItem(PhoneNumber value) {#addItem-com.aspose.email.PhoneNumber-}
```
public void addItem(PhoneNumber value)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) |  |

### clear() {#clear--}
```
public final void clear()
```


Удаляет все элементы из списка.

### contains(PhoneNumber value) {#contains-com.aspose.email.PhoneNumber-}
```
public final boolean contains(PhoneNumber value)
```


Определяет, содержит ли список определённое значение.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) | Объект, который нужно найти в списке. |

**Returns:**
boolean — true, если объект найден в списке; иначе false.
### containsItem(PhoneNumber value) {#containsItem-com.aspose.email.PhoneNumber-}
```
public boolean containsItem(PhoneNumber value)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) |  |

**Returns:**
boolean
### copyTo(PhoneNumber[] array, int index) {#copyTo-com.aspose.email.PhoneNumber---int-}
```
public final void copyTo(PhoneNumber[] array, int index)
```


Копирует элементы в массив, начиная с указанного индекса массива.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| array | [PhoneNumber\[\]](../../com.aspose.email/phonenumber) | Одномерный массив, являющийся получателем элементов, скопированных из коллекций. Массив должен иметь нулевую индексацию. |
| индекс | int | Нулевой индекс в массиве, с которого начинается копирование. |

### copyToTArray(PhoneNumber[] array, int index) {#copyToTArray-com.aspose.email.PhoneNumber---int-}
```
public void copyToTArray(PhoneNumber[] array, int index)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| array | [PhoneNumber\[\]](../../com.aspose.email/phonenumber) |  |
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
### getAssistant() {#getAssistant--}
```
public final String getAssistant()
```


Номер телефона помощника по умолчанию

**Returns:**
java.lang.String
### getCallback() {#getCallback--}
```
public final String getCallback()
```


Номер обратного звонка по умолчанию

**Returns:**
java.lang.String
### getCar() {#getCar--}
```
public final String getCar()
```


Номер автомобильного телефона по умолчанию

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompany() {#getCompany--}
```
public final String getCompany()
```


Номер телефона компании по умолчанию

**Returns:**
java.lang.String
### getCustom() {#getCustom--}
```
public final String getCustom()
```


Категория пользовательского телефона по умолчанию

**Returns:**
java.lang.String
### getFax() {#getFax--}
```
public final String getFax()
```


Номер факса по умолчанию

**Returns:**
java.lang.String
### getHome() {#getHome--}
```
public final String getHome()
```


Номер домашнего телефона по умолчанию

**Returns:**
java.lang.String
### getHomeFax() {#getHomeFax--}
```
public final String getHomeFax()
```


Номер домашнего факса по умолчанию

**Returns:**
java.lang.String
### getIsdn() {#getIsdn--}
```
public final String getIsdn()
```


Номер ISDN телефона по умолчанию

**Returns:**
java.lang.String
### getMobile() {#getMobile--}
```
public final String getMobile()
```


Номер мобильного телефона по умолчанию

**Returns:**
java.lang.String
### getPager() {#getPager--}
```
public final String getPager()
```


Номер пейджера по умолчанию

**Returns:**
java.lang.String
### getPrefered() {#getPrefered--}
```
public final String getPrefered()
```


Основной номер телефона по умолчанию

**Returns:**
java.lang.String
### getRadio() {#getRadio--}
```
public final String getRadio()
```


Номер радиотелефона по умолчанию

**Returns:**
java.lang.String
### getTelex() {#getTelex--}
```
public final String getTelex()
```


Телекс по умолчанию

**Returns:**
java.lang.String
### getTtyTdd() {#getTtyTdd--}
```
public final String getTtyTdd()
```


Tty/Tdd по умолчанию

**Returns:**
java.lang.String
### getWork() {#getWork--}
```
public final String getWork()
```


Рабочий телефон по умолчанию

**Returns:**
java.lang.String
### getWorkFax() {#getWorkFax--}
```
public final String getWorkFax()
```


Рабочий факс по умолчанию

**Returns:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final PhoneNumber get_Item(int index)
```


Получает или задаёт элемент по указанному индексу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| индекс | int | Нулевой индекс элемента для получения или установки. |

**Returns:**
[PhoneNumber](../../com.aspose.email/phonenumber) - The element at the specified index.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indexOf(PhoneNumber value) {#indexOf-com.aspose.email.PhoneNumber-}
```
public final int indexOf(PhoneNumber value)
```


Определяет индекс конкретного элемента в списке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) | Объект, который нужно найти в списке. |

**Returns:**
int - Индекс  value , если он найден в списке; иначе -1.
### indexOfItem(PhoneNumber value) {#indexOfItem-com.aspose.email.PhoneNumber-}
```
public int indexOfItem(PhoneNumber value)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) |  |

**Returns:**
int
### insert(int index, PhoneNumber value) {#insert-int-com.aspose.email.PhoneNumber-}
```
public final void insert(int index, PhoneNumber value)
```


Вставляет элемент в список по указанному индексу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| индекс | int | Нулевой индекс, по которому должно быть вставлено  value . |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) | Объект, который нужно вставить в список. |

### insertItem(int index, PhoneNumber value) {#insertItem-int-com.aspose.email.PhoneNumber-}
```
public void insertItem(int index, PhoneNumber value)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| индекс | int |  |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) |  |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Получает значение, указывающее, является ли список только для чтения.

**Returns:**
boolean — true, если список только для чтения; иначе false.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<PhoneNumber> iterator()
```


Возвращает перечислитель, который перебирает коллекцию.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.email.PhoneNumber> - Объект IEnumerator, который можно использовать для перебора элементов коллекции.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(PhoneNumber value) {#remove-com.aspose.email.PhoneNumber-}
```
public final boolean remove(PhoneNumber value)
```


Удаляет первое вхождение указанного объекта из списка.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) | Объект, который нужно удалить из списка. |

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

### removeItem(PhoneNumber value) {#removeItem-com.aspose.email.PhoneNumber-}
```
public boolean removeItem(PhoneNumber value)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) |  |

**Returns:**
boolean
### setAssistant(String value) {#setAssistant-java.lang.String-}
```
public final void setAssistant(String value)
```


Номер телефона помощника по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setCallback(String value) {#setCallback-java.lang.String-}
```
public final void setCallback(String value)
```


Номер обратного звонка по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setCar(String value) {#setCar-java.lang.String-}
```
public final void setCar(String value)
```


Номер автомобильного телефона по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Номер телефона компании по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setCustom(String value) {#setCustom-java.lang.String-}
```
public final void setCustom(String value)
```


Категория пользовательского телефона по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setFax(String value) {#setFax-java.lang.String-}
```
public final void setFax(String value)
```


Номер факса по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setHome(String value) {#setHome-java.lang.String-}
```
public final void setHome(String value)
```


Номер домашнего телефона по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setHomeFax(String value) {#setHomeFax-java.lang.String-}
```
public final void setHomeFax(String value)
```


Номер домашнего факса по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setIsdn(String value) {#setIsdn-java.lang.String-}
```
public final void setIsdn(String value)
```


Номер ISDN телефона по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setMobile(String value) {#setMobile-java.lang.String-}
```
public final void setMobile(String value)
```


Номер мобильного телефона по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setPager(String value) {#setPager-java.lang.String-}
```
public final void setPager(String value)
```


Номер пейджера по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setPrefered(String value) {#setPrefered-java.lang.String-}
```
public final void setPrefered(String value)
```


Основной номер телефона по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setRadio(String value) {#setRadio-java.lang.String-}
```
public final void setRadio(String value)
```


Номер радиотелефона по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setTelex(String value) {#setTelex-java.lang.String-}
```
public final void setTelex(String value)
```


Телекс по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setTtyTdd(String value) {#setTtyTdd-java.lang.String-}
```
public final void setTtyTdd(String value)
```


Tty/Tdd по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setWork(String value) {#setWork-java.lang.String-}
```
public final void setWork(String value)
```


Рабочий телефон по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setWorkFax(String value) {#setWorkFax-java.lang.String-}
```
public final void setWorkFax(String value)
```


Рабочий факс по умолчанию

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### set_Item(int index, PhoneNumber value) {#set-Item-int-com.aspose.email.PhoneNumber-}
```
public final void set_Item(int index, PhoneNumber value)
```


Получает или задаёт элемент по указанному индексу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| индекс | int | Нулевой индекс элемента для получения или установки. |
| value | [PhoneNumber](../../com.aspose.email/phonenumber) |  |

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

