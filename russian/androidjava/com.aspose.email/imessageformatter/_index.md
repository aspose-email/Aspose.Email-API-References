---
title: IMessageFormatter
second_title: Aspose.Email for Android via Java API Reference
description: Предоставляет механизм получения объекта для форматирования сообщения.
type: docs
weight: 460
url: /ru/androidjava/com.aspose.email/imessageformatter/
---
```
public interface IMessageFormatter
```

Предоставляет механизм получения объекта для форматирования сообщения.
## Methods

| Method | Описание |
| --- | --- |
| [format(MailMessage message)](#format-com.aspose.email.MailMessage-) | Форматирует указанное сообщение. |
| [getFormatTemplates()](#getFormatTemplates--) | Получает шаблоны формата. |
### format(MailMessage message) {#format-com.aspose.email.MailMessage-}
```
public abstract void format(MailMessage message)
```


Форматирует указанное сообщение.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | Сообщение. |

### getFormatTemplates() {#getFormatTemplates--}
```
public abstract System.Collections.Specialized.StringDictionary getFormatTemplates()
```


Получает шаблоны формата.

Значение: Шаблоны формата.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringDictionary
