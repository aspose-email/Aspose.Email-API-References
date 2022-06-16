---
title: AllOrNone
second_title: Справочник по Aspose.Email для .NET API
description: Клиент может включать несколько элементов BodyPreference в командный запрос с разными значениями элемента Type раздел 2.2.2.22.4. По умолчанию сервер возвращает данные усеченные до размера запрошенного TruncationSize для элемента Type который соответствует собственному формату хранения элемента Body элемента. Но если клиент также включает элемент AllOrNone со значением TRUE вместе с элементом TruncationSize он указывает серверу не возвращать усеченный ответ для этого типа когда размер в байтах доступные данные превышают значение элемента TruncationSize. Например клиент может использовать эти два элемента чтобы обозначить что он не может обрабатывать частичные данные в формате Rich Text Format RTF значение элемента Type равно 3. В этом случае если клиент указал несколько элементов BodyPreference сервер выбирает следующий элемент BodyPreference который вернет клиенту максимальное количество основного текста. Предположим что клиент указывает два элемента BodyPreference. Если элемент AllOrNone не определен поиск синхронизация или извлечение усеченного или неусеченного содержимого выполняется так как если бы для значения было установлено значение FALSE.
type: docs
weight: 20
url: /ru/net/aspose.email.clients.activesync.transportlayer/bodypreference/allornone/
---
## BodyPreference.AllOrNone property

Клиент может включать несколько элементов BodyPreference в командный запрос с разными значениями элемента Type (раздел 2.2.2.22.4). По умолчанию сервер возвращает данные, усеченные до размера, запрошенного TruncationSize для элемента Type, который соответствует собственному формату хранения элемента Body элемента. Но если клиент также включает элемент AllOrNone со значением TRUE вместе с элементом TruncationSize, он указывает серверу не возвращать усеченный ответ для этого типа, когда размер (в байтах) доступные данные превышают значение элемента TruncationSize. Например, клиент может использовать эти два элемента, чтобы обозначить, что он не может обрабатывать частичные данные в формате Rich Text Format (RTF) (значение элемента Type равно 3). В этом случае, если клиент указал несколько элементов BodyPreference, сервер выбирает следующий элемент BodyPreference, который вернет клиенту максимальное количество основного текста. Предположим, что клиент указывает два элемента BodyPreference. Если элемент AllOrNone не определен, поиск, синхронизация или извлечение усеченного или неусеченного содержимого выполняется так, как если бы для значения было установлено значение FALSE.

```csharp
public bool? AllOrNone { get; set; }
```

### Смотрите также

* class [BodyPreference](../../bodypreference)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../bodypreference)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->