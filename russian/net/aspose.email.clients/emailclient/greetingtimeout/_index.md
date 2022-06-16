---
title: GreetingTimeout
second_title: Справочник по Aspose.Email для .NET API
description: Получает или задает время ожидания приветствия которое используется при установлении соединения. Обратите внимание время ожидания приветствия не может быть бесконечным. Почтовые клиенты могут выполнять достаточно длительные операции. Для ограничения времени операций пользователям необходимо использовать свойствоTimeoutaspose.email.clients/emailclient/timeout. Значения этого свойства должны иметь длинные интервалы чтобы не препятствовать длительным операциям. Но в некоторых случаях если EmailClient будет использовать только свойство Timeout установление соединения может занять много времени. Например почтовый клиент может использовать автоматический режим установления соединения. В этом режиме почтовый клиент перебирает все возможные параметры подключения пока соединение не будет установлено. Серверы SMTP IMAP и POP3 в случае корректного установления соединения отправляют клиенту строку приветствия. Серверы могут использовать неявную или явную START TLS инициацию соединения SSL/TLS. Если режим соединения не соответствует например сервер ожидает неявного SSL-соединения но клиент пытается установить незащищенное или явное SSL-соединение сервер выиграл не отправлять строку приветствия. В этом случае пользователь будет долго ждать пока таймаут достигнет строки приветствия и клиент перейдет к следующему варианту подключения. Чтобы избежать этой проблемы было введено свойство GreetingTimeout. Это свойство позволяет установить таймаут для строки приветствия и уменьшить время автоматического установления соединения.
type: docs
weight: 100
url: /ru/net/aspose.email.clients/emailclient/greetingtimeout/
---
## EmailClient.GreetingTimeout property

Получает или задает время ожидания приветствия, которое используется при установлении соединения. Обратите внимание, время ожидания приветствия не может быть бесконечным. Почтовые клиенты могут выполнять достаточно длительные операции. Для ограничения времени операций пользователям необходимо использовать свойство[`Timeout`](../timeout). Значения этого свойства должны иметь длинные интервалы, чтобы не препятствовать длительным операциям. Но в некоторых случаях, если EmailClient будет использовать только свойство Timeout, установление соединения может занять много времени. Например, почтовый клиент может использовать автоматический режим установления соединения. В этом режиме почтовый клиент перебирает все возможные параметры подключения, пока соединение не будет установлено. Серверы SMTP, IMAP и POP3 в случае корректного установления соединения отправляют клиенту строку приветствия. Серверы могут использовать неявную или явную (START TLS) инициацию соединения SSL/TLS. Если режим соединения не соответствует (например, сервер ожидает неявного SSL-соединения, но клиент пытается установить незащищенное или явное SSL-соединение), сервер выиграл не отправлять строку приветствия. В этом случае пользователь будет долго ждать, пока таймаут достигнет строки приветствия, и клиент перейдет к следующему варианту подключения. Чтобы избежать этой проблемы, было введено свойство GreetingTimeout. Это свойство позволяет установить таймаут для строки приветствия и уменьшить время автоматического установления соединения.

```csharp
public int GreetingTimeout { get; set; }
```

### Стоимость имущества

Время ожидания приветствия в миллисекундах

### Смотрите также

* class [EmailClient](../../emailclient)
* пространство имен [Aspose.Email.Clients](../../emailclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->