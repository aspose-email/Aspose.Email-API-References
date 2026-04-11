---
title: FollowUpManager
second_title: Aspose.Email for Android via Java API Reference
description: Обеспечивает возможность задавать и обрабатывать флаги последующего действия Outlook и категории.
type: docs
weight: 144
url: /ru/androidjava/com.aspose.email/followupmanager/
---

**Inheritance:**
java.lang.Object
```
public class FollowUpManager
```

Обеспечивает возможность устанавливать и обрабатывать флаги и категории последующего действия Outlook. Поддерживает функции добавления и удаления флага в [MapiMessage](../../com.aspose.email/mapimessage) и пометку его как завершённого.
## Constructors

| Constructor | Описание |
| --- | --- |
| [FollowUpManager()](#FollowUpManager--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [addCategory(MapiMessage message, String categoryName)](#addCategory-com.aspose.email.MapiMessage-java.lang.String-) | Добавляет категорию к сообщению. |
| [addVotingButton(MapiMessage message, String displayName)](#addVotingButton-com.aspose.email.MapiMessage-java.lang.String-) | Добавляет кнопку голосования. |
| [clearCategories(MapiMessage message)](#clearCategories-com.aspose.email.MapiMessage-) | Очищает категории. |
| [clearFlag(MapiMessage message)](#clearFlag-com.aspose.email.MapiMessage-) | Очищает флаг последующего действия и напоминание. |
| [clearVotingButtons(MapiMessage message)](#clearVotingButtons-com.aspose.email.MapiMessage-) | Удаляет кнопки голосования. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCategories(MapiMessage message)](#getCategories-com.aspose.email.MapiMessage-) | Получить доступные категории сообщений. |
| [getClass()](#getClass--) |  |
| [getOptions(MapiMessage message)](#getOptions-com.aspose.email.MapiMessage-) | Получает параметры последующего действия сообщения. |
| [getVotingButtons(MapiMessage message)](#getVotingButtons-com.aspose.email.MapiMessage-) | Получить доступные кнопки голосования сообщения. |
| [getVotingButtonsArray(MapiMessage message)](#getVotingButtonsArray-com.aspose.email.MapiMessage-) | Получить доступные кнопки голосования сообщения. |
| [hashCode()](#hashCode--) |  |
| [markAsCompleted(MapiMessage message)](#markAsCompleted-com.aspose.email.MapiMessage-) | Помечает отмеченное сообщение как завершённое. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCategory(MapiMessage message, String categoryName)](#removeCategory-com.aspose.email.MapiMessage-java.lang.String-) | Удаляет категорию. |
| [removeVotingButton(MapiMessage message, String displayName)](#removeVotingButton-com.aspose.email.MapiMessage-java.lang.String-) | Удаляет кнопку голосования. |
| [setFlag(MapiMessage message, String flagRequest)](#setFlag-com.aspose.email.MapiMessage-java.lang.String-) | Устанавливает флаг последующего действия для сообщения. |
| [setFlag(MapiMessage message, String flagRequest, Date startDate, Date dueDate)](#setFlag-com.aspose.email.MapiMessage-java.lang.String-java.util.Date-java.util.Date-) | Устанавливает флаг последующего действия для сообщения. |
| [setFlagForRecipients(MapiMessage message, String flagRequest)](#setFlagForRecipients-com.aspose.email.MapiMessage-java.lang.String-) | Устанавливает флаг для черновика сообщения, чтобы напомнить получателям о последующем действии. |
| [setFlagForRecipients(MapiMessage message, String flagRequest, Date reminderTime)](#setFlagForRecipients-com.aspose.email.MapiMessage-java.lang.String-java.util.Date-) | Устанавливает флаг для черновика сообщения, чтобы напомнить получателям о последующем действии. |
| [setOptions(MapiMessage message, FollowUpOptions options)](#setOptions-com.aspose.email.MapiMessage-com.aspose.email.FollowUpOptions-) | Устанавливает дополнительные параметры последующего действия для сообщения. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FollowUpManager() {#FollowUpManager--}
```
public FollowUpManager()
```


### addCategory(MapiMessage message, String categoryName) {#addCategory-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void addCategory(MapiMessage message, String categoryName)
```


Добавляет категорию к сообщению.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Объект [MapiMessage](../../com.aspose.email/mapimessage), в который будет добавлена категория. |
| categoryName | java.lang.String | Имя категории. |

### addVotingButton(MapiMessage message, String displayName) {#addVotingButton-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void addVotingButton(MapiMessage message, String displayName)
```


Добавляет кнопку голосования.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Объект [MapiMessage](../../com.aspose.email/mapimessage), в который добавлена кнопка голосования. |
| displayName | java.lang.String | Отображаемое имя кнопки. |

### clearCategories(MapiMessage message) {#clearCategories-com.aspose.email.MapiMessage-}
```
public static void clearCategories(MapiMessage message)
```


Очищает категории.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Эта [MapiMessage](../../com.aspose.email/mapimessage), в которой категории будут очищены. |

### clearFlag(MapiMessage message) {#clearFlag-com.aspose.email.MapiMessage-}
```
public static void clearFlag(MapiMessage message)
```


Очищает флаг последующего действия и напоминание.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Эта [MapiMessage](../../com.aspose.email/mapimessage), в которой установлен флаг. |

### clearVotingButtons(MapiMessage message) {#clearVotingButtons-com.aspose.email.MapiMessage-}
```
public static void clearVotingButtons(MapiMessage message)
```


Удаляет кнопки голосования.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Эта [MapiMessage](../../com.aspose.email/mapimessage), в которой категории будут очищены. |

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
### getCategories(MapiMessage message) {#getCategories-com.aspose.email.MapiMessage-}
```
public static System.Collections.IList getCategories(MapiMessage message)
```


Получить доступные категории сообщений.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Эта [MapiMessage](../../com.aspose.email/mapimessage), в которой добавлены категории. |

**Returns:**
com.aspose.ms.System.Collections.IList - Список добавленных категорий.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOptions(MapiMessage message) {#getOptions-com.aspose.email.MapiMessage-}
```
public static FollowUpOptions getOptions(MapiMessage message)
```


Получает параметры последующего действия сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Эта [MapiMessage](../../com.aspose.email/mapimessage), в которой параметры установлены. |

**Returns:**
[FollowUpOptions](../../com.aspose.email/followupoptions) - The [FollowUpOptions](../../com.aspose.email/followupoptions) that represents options for using follow-up flags, reminders, category and voting buttons.
### getVotingButtons(MapiMessage message) {#getVotingButtons-com.aspose.email.MapiMessage-}
```
public static System.Collections.IList getVotingButtons(MapiMessage message)
```


Получить доступные кнопки голосования сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Эта [MapiMessage](../../com.aspose.email/mapimessage), в которой добавлены кнопки. |

**Returns:**
com.aspose.ms.System.Collections.IList - Список добавленных кнопок голосования.
### getVotingButtonsArray(MapiMessage message) {#getVotingButtonsArray-com.aspose.email.MapiMessage-}
```
public static String[] getVotingButtonsArray(MapiMessage message)
```


Получить доступные кнопки голосования сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Эта  MapiMessage  в которой добавлены кнопки. |

**Returns:**
java.lang.String[] - Список добавленных кнопок голосования.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### markAsCompleted(MapiMessage message) {#markAsCompleted-com.aspose.email.MapiMessage-}
```
public static void markAsCompleted(MapiMessage message)
```


Помечает отмеченное сообщение как завершённое.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Эта [MapiMessage](../../com.aspose.email/mapimessage), в которой установлен флаг. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeCategory(MapiMessage message, String categoryName) {#removeCategory-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void removeCategory(MapiMessage message, String categoryName)
```


Удаляет категорию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Сообщение. |
| categoryName | java.lang.String | Имя категории. |

### removeVotingButton(MapiMessage message, String displayName) {#removeVotingButton-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void removeVotingButton(MapiMessage message, String displayName)
```


Удаляет кнопку голосования.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Эта [MapiMessage](../../com.aspose.email/mapimessage), в которой удалена кнопка голосования. |
| displayName | java.lang.String | Отображаемое имя кнопки. |

### setFlag(MapiMessage message, String flagRequest) {#setFlag-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void setFlag(MapiMessage message, String flagRequest)
```


Устанавливает флаг последующего действия для сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Эта [MapiMessage](../../com.aspose.email/mapimessage), в которой будет установлен флаг. |
| flagRequest | java.lang.String | Строка, указывающая запрошенное действие для электронного сообщения. |

### setFlag(MapiMessage message, String flagRequest, Date startDate, Date dueDate) {#setFlag-com.aspose.email.MapiMessage-java.lang.String-java.util.Date-java.util.Date-}
```
public static void setFlag(MapiMessage message, String flagRequest, Date startDate, Date dueDate)
```


Устанавливает флаг последующего действия для сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Эта [MapiMessage](../../com.aspose.email/mapimessage), в которой будет установлен флаг. |
| flagRequest | java.lang.String | Строка, указывающая запрошенное действие для электронного сообщения. |
| startDate | java.util.Date | Дата начала. |
| dueDate | java.util.Date | Срок выполнения. |

### setFlagForRecipients(MapiMessage message, String flagRequest) {#setFlagForRecipients-com.aspose.email.MapiMessage-java.lang.String-}
```
public static void setFlagForRecipients(MapiMessage message, String flagRequest)
```


Устанавливает флаг для черновика сообщения, чтобы напомнить получателям о последующем действии.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Эта [MapiMessage](../../com.aspose.email/mapimessage), в которой будет установлен флаг. |
| flagRequest | java.lang.String | Строка, указывающая запрошенное действие для получателей электронного сообщения. |

### setFlagForRecipients(MapiMessage message, String flagRequest, Date reminderTime) {#setFlagForRecipients-com.aspose.email.MapiMessage-java.lang.String-java.util.Date-}
```
public static void setFlagForRecipients(MapiMessage message, String flagRequest, Date reminderTime)
```


Устанавливает флаг для черновика сообщения, чтобы напомнить получателям о последующем действии.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Эта [MapiMessage](../../com.aspose.email/mapimessage), в которой будет установлен флаг. |
| flagRequest | java.lang.String | Строка, указывающая запрошенное действие для получателей электронного сообщения. |
| reminderTime | java.util.Date | Дата, указывающая дату и время, когда должно произойти напоминание. |

### setOptions(MapiMessage message, FollowUpOptions options) {#setOptions-com.aspose.email.MapiMessage-com.aspose.email.FollowUpOptions-}
```
public static void setOptions(MapiMessage message, FollowUpOptions options)
```


Устанавливает дополнительные параметры последующего действия для сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Эта [MapiMessage](../../com.aspose.email/mapimessage), в которой будет установлен флаг. |
| options | [FollowUpOptions](../../com.aspose.email/followupoptions) | Эти [FollowUpOptions](../../com.aspose.email/followupoptions), представляющие параметры использования флагов последующего действия и напоминаний. |

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

