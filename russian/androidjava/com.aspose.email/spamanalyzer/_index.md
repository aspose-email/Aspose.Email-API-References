---
title: SpamAnalyzer
second_title: Aspose.Email for Android via Java API Reference
description: Класс, позволяющий приложениям обнаруживать спам‑письма с помощью самобучающегося байесовского фильтра.
type: docs
weight: 388
url: /ru/androidjava/com.aspose.email/spamanalyzer/
---

**Inheritance:**
java.lang.Object
```
public class SpamAnalyzer
```

Класс, позволяющий приложениям обнаруживать спам‑письма с помощью самобучающегося байесовского фильтра.
## Constructors

| Constructor | Описание |
| --- | --- |
| [SpamAnalyzer()](#SpamAnalyzer--) | Инициализировать новый экземпляр класса [SpamAnalyzer](../../com.aspose.email/spamanalyzer). |
| [SpamAnalyzer(InputStream stream)](#SpamAnalyzer-java.io.InputStream-) | Инициализировать новый экземпляр класса [SpamAnalyzer](../../com.aspose.email/spamanalyzer). |
| [SpamAnalyzer(String filePath)](#SpamAnalyzer-java.lang.String-) | Инициализировать новый экземпляр класса [SpamAnalyzer](../../com.aspose.email/spamanalyzer). |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [loadDatabase(InputStream stream)](#loadDatabase-java.io.InputStream-) | Загружает байесовскую базу данных из потока. |
| [loadDatabase(String filePath)](#loadDatabase-java.lang.String-) | Загружает байесовскую базу данных из файла. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Очищает все статистические данные (байесовская база данных). |
| [saveDatabase(OutputStream stream)](#saveDatabase-java.io.OutputStream-) | Сохраняет байесовскую базу данных в поток. |
| [saveDatabase(String filePath)](#saveDatabase-java.lang.String-) | Сохраняет базу данных Байеса в файл. |
| [test(MailMessage message)](#test-com.aspose.email.MailMessage-) | Анализирует сообщение и возвращает вероятность того, что сообщение является спамом. |
| [toString()](#toString--) |  |
| [trainFilter(MailMessage message, boolean isSpam)](#trainFilter-com.aspose.email.MailMessage-boolean-) | Обучается на указанном сообщении как на спаме или не‑спаме. |
| [trainFilter(MailMessage[] ham, MailMessage[] spam)](#trainFilter-com.aspose.email.MailMessage---com.aspose.email.MailMessage---) | Обучается на указанных сообщениях как на спаме или не‑спаме. |
| [trainFilter(String text, boolean isSpam)](#trainFilter-java.lang.String-boolean-) | Обучается на указанной строке как на спаме или не‑спаме. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SpamAnalyzer() {#SpamAnalyzer--}
```
public SpamAnalyzer()
```


Инициализировать новый экземпляр класса [SpamAnalyzer](../../com.aspose.email/spamanalyzer).

### SpamAnalyzer(InputStream stream) {#SpamAnalyzer-java.io.InputStream-}
```
public SpamAnalyzer(InputStream stream)
```


Инициализировать новый экземпляр класса [SpamAnalyzer](../../com.aspose.email/spamanalyzer).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток, содержащий базу данных Байеса. |

### SpamAnalyzer(String filePath) {#SpamAnalyzer-java.lang.String-}
```
public SpamAnalyzer(String filePath)
```


Инициализировать новый экземпляр класса [SpamAnalyzer](../../com.aspose.email/spamanalyzer).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Полный или относительный путь к файлу, содержащему базу данных Байеса. |

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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadDatabase(InputStream stream) {#loadDatabase-java.io.InputStream-}
```
public final void loadDatabase(InputStream stream)
```


Загружает байесовскую базу данных из потока.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток, содержащий базу данных Байеса. |

### loadDatabase(String filePath) {#loadDatabase-java.lang.String-}
```
public final void loadDatabase(String filePath)
```


Загружает байесовскую базу данных из файла.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Полный или относительный путь к файлу, содержащему базу данных Байеса. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public final void reset()
```


Очищает все статистические данные (байесовская база данных).

### saveDatabase(OutputStream stream) {#saveDatabase-java.io.OutputStream-}
```
public final void saveDatabase(OutputStream stream)
```


Сохраняет байесовскую базу данных в поток.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Выходной поток, содержащий базу данных Байеса. |

### saveDatabase(String filePath) {#saveDatabase-java.lang.String-}
```
public final void saveDatabase(String filePath)
```


Сохраняет базу данных Байеса в файл.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Полный или относительный путь к файлу, содержащему базу данных Байеса. |

### test(MailMessage message) {#test-com.aspose.email.MailMessage-}
```
public final double test(MailMessage message)
```


Анализирует сообщение и возвращает вероятность того, что сообщение является спамом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | MailMessage для тестирования вероятности того, что сообщение является спамом. |

**Returns:**
double — значение типа double в диапазоне 0‑1, где 0 соответствует «определённо не спам» (0 % вероятности спама), а 1 соответствует «определённо спам» (100 % вероятности спама).
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### trainFilter(MailMessage message, boolean isSpam) {#trainFilter-com.aspose.email.MailMessage-boolean-}
```
public final void trainFilter(MailMessage message, boolean isSpam)
```


Обучается на указанном сообщении как на спаме или не‑спаме.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | Ссылка на объект MailMessage, представляющий сообщение для обучения байесовского фильтра. |
| isSpam | boolean | True, если сообщение является спамом; false, если это легитимное сообщение. |

### trainFilter(MailMessage[] ham, MailMessage[] spam) {#trainFilter-com.aspose.email.MailMessage---com.aspose.email.MailMessage---}
```
public final void trainFilter(MailMessage[] ham, MailMessage[] spam)
```


Обучается на указанных сообщениях как на спаме или не‑спаме.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| ham | [MailMessage\[\]](../../com.aspose.email/mailmessage) | Массив объектов MailMessage, которые являются не‑спамом для обучения байесовского фильтра. |
| spam | [MailMessage\[\]](../../com.aspose.email/mailmessage) | Массив объектов MailMessage, которые являются спамом для обучения байесовского фильтра. |

### trainFilter(String text, boolean isSpam) {#trainFilter-java.lang.String-boolean-}
```
public final void trainFilter(String text, boolean isSpam)
```


Обучается на указанной строке как на спаме или не‑спаме.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| text | java.lang.String | Строковое значение для обучения байесовского фильтра. |
| isSpam | boolean | True, если указанная строка является спамом; false, если это легитимный текст. |

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

