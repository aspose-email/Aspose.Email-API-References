---
title: MailQuery
second_title: Aspose.Email for Android via Java API Reference
description: Представляет критерии поиска, которые используются для сопоставления нескольких свойств сообщения в почтовом ящике.
type: docs
weight: 196
url: /ru/androidjava/com.aspose.email/mailquery/
---

**Inheritance:**
java.lang.Object
```
public class MailQuery
```

Представляет критерии поиска, которые используются для сопоставления нескольких свойств сообщения в почтовом ящике.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MailQuery(String queryString)](#MailQuery-java.lang.String-) | Инициализирует новый экземпляр класса [MailQuery](../../com.aspose.email/mailquery). |
| [MailQuery(String queryString, String orderByString)](#MailQuery-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса [MailQuery](../../com.aspose.email/mailquery). |
## Methods

| Method | Описание |
| --- | --- |
| [equals(MailQuery other)](#equals-com.aspose.email.MailQuery-) | Указывает, равен ли текущий объект другому объекту того же типа. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный Object этому экземпляру. |
| [getClass()](#getClass--) |  |
| [getOrderByString()](#getOrderByString--) | Строка запроса сортировки. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает String, представляющий этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailQuery(String queryString) {#MailQuery-java.lang.String-}
```
public MailQuery(String queryString)
```


Инициализирует новый экземпляр класса [MailQuery](../../com.aspose.email/mailquery).

--------------------

> ```
> MailQuery mailQuery = new MailQuery("(('From' Contains 'test@test.com' | 'Seen' = 'True') & 'SentDate' >= '12-May-2010')");
> ```

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
|  | queryString | java.lang.String | Строка запроса. |

--------------------

Строка запроса должна иметь следующий вид.

Пример простого выражения:

'<Field name>' <Comparison operator> '<Field value>',

где <Field Name> — имя поля сообщения, по которому производится фильтрация, <Comparison operator> — операторы сравнения, как следует из их названия, позволяют сравнивать поле сообщения с указанным значением, <Field value> — значение, сравниваемое с полем сообщения.

Количество простых выражений может образовать составное, например: (<Simple expression 1> & <Simple expression 2>) | <Simple expression 3>,

где '&' — логический оператор И, '|' — логический оператор ИЛИ

В настоящее время следующие значения допускаются в качестве имени поля (<Field name>):

'To' — представляет поле TO сообщения, 'Text' — представляет строку в заголовке или теле сообщения, 'Bcc' — представляет поле BCC сообщения, 'Body' — представляет строку в теле сообщения, 'Cc' — представляет поле CC сообщения, 'From' — представляет поле From сообщения, 'Subject' — представляет строку в теме сообщения, 'InternalDate' — представляет внутреннюю дату сообщения, 'SentDate' — представляет дату отправки сообщения

Дополнительно, следующие имена полей допускаются для протокола IMAP:

'Answered' — представляет флаг /Answered сообщения, 'Seen' — представляет флаг /Seen сообщения, 'Flagged' — представляет флаг /Flagged сообщения, 'Draft' — представляет флаг /Draft сообщения, 'Deleted' — представляет флаг Deleted/ сообщения, 'Recent' — представляет флаг Recent сообщения, 'MessageSize' — представляет размер (в байтах) сообщения

Дополнительно, следующие имена полей допускаются для Exchange:

'IsRead' — указывает, было ли сообщение прочитано, 'HasAttachment' — указывает, есть ли у сообщения вложения, 'IsSubmitted' — указывает, было ли сообщение отправлено в исходящие, 'ContentClass' — представляет класс содержимого элемента

Дополнительно, следующие имена полей допускаются для файлов pst/ost:

'MessageClass' — представляет класс сообщения, 'ContainerClass' — представляет класс контейнера папки, 'Importance' — представляет важность сообщения, 'MessageSize' — представляет размер (в байтах) сообщения, 'FolderName' — представляет имя папки, 'ContentsCount' — представляет общее количество элементов в папке, 'UnreadContentsCount' — представляет количество непрочитанных элементов в папке. 'Subfolders' — указывает, есть ли у папки подпапки, 'Read' — сообщение помечено как прочитанное, 'HasAttachment' — у сообщения есть как минимум одно вложение, 'Unsent' — сообщение всё ещё находится в процессе составления, 'Unmodified' — сообщение не было изменено с момента первого сохранения (если не отправлено) или доставки (если отправлено), 'FromMe' — пользователь, получающий сообщение, также является пользователем, отправившим сообщение, 'Resend' — сообщение включает запрос на повторную отправку с отчетом о недоставке, 'NotifyRead' — пользователь, отправивший сообщение, запросил уведомление, когда получатель впервые прочитает его, 'NotifyUnread' — пользователь, отправивший сообщение, запросил уведомление, когда получатель удалит его до чтения или объект Message истечёт, 'EverRead' — сообщение было прочитано хотя бы один раз

Значение поля (<Field value>) может принимать следующие значения: для текстовых полей — любая строка, для полей типа дата — строка формата 'd-MMM-yyy', например '10-Feb-2009', для флагов (полей булевого типа) — либо 'True', либо 'False' |

### MailQuery(String queryString, String orderByString) {#MailQuery-java.lang.String-java.lang.String-}
```
public MailQuery(String queryString, String orderByString)
```


Инициализирует новый экземпляр класса [MailQuery](../../com.aspose.email/mailquery).

--------------------

> ```
> MailQuery mailQuery = new MailQuery("", "(('From' OrderBy 'ASC') & ('SentDate' OrderBy 'DESC'))");
> ```

--------------------

Строка запроса сортировки должна иметь следующий вид.

Пример простого выражения:

'<Field name>' OrderBy ['ASC'|'DESC'],

где <Field Name> - имя поля сообщения, через которое выполняется сортировка, ['ASC'|'DESC'] - операторы сортировки, позволяют сортировать по возрастанию или убыванию,

Количество простых выражений может образовать составное, например: (<Simple expression 1> & <Simple expression 2>),

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| queryString | java.lang.String |  |
| orderByString | java.lang.String |  |

### equals(MailQuery other) {#equals-com.aspose.email.MailQuery-}
```
public final boolean equals(MailQuery other)
```


Указывает, равен ли текущий объект другому объекту того же типа.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| other | [MailQuery](../../com.aspose.email/mailquery) | Объект для сравнения с этим объектом. |

**Returns:**
boolean - true, если текущий объект равен параметру other; иначе false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный Object этому экземпляру.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Object для сравнения с этим экземпляром. |

**Returns:**
boolean —  true  если указанный Object равен этому экземпляру; иначе,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOrderByString() {#getOrderByString--}
```
public final String getOrderByString()
```


Строка запроса сортировки.

**Returns:**
java.lang.String
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




### toString() {#toString--}
```
public String toString()
```


Возвращает String, представляющий этот экземпляр.

**Returns:**
java.lang.String - строка запроса, представляющая этот экземпляр.
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

