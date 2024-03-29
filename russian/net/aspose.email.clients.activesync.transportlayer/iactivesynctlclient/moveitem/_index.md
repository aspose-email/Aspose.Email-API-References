---
title: MoveItem
second_title: Справочник по Aspose.Email для .NET API
description: Команда MoveItems перемещает элемент или элементы из одной папки на сервере в другую.
type: docs
weight: 120
url: /ru/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitem/
---
## IActiveSyncTLClient.MoveItem method

Команда MoveItems перемещает элемент или элементы из одной папки на сервере в другую.

```csharp
public MoveItemResponse MoveItem(string srcMsgId, string srcFldId, string dstFldId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcMsgId | String | Указывает идентификатор сервера перемещенного элемента. Значение элемента SrcMsgId может иметь длину до 64 символов. |
| srcFldId | String | Указывает идентификатор сервера исходной папки (то есть папки, содержащей элементы, которые нужно переместить). Значение элемента SrcFldId может содержать до 64 символов в length |
| dstFldId | String | Указывает идентификатор сервера папки назначения (то есть папки, в которую перемещаются элементы). Значение свойства DstFldId может иметь длину до 64 символов. |

### Возвращаемое значение

Возвращает информацию, описывающую перемещенный элемент.

### Смотрите также

* class [MoveItemResponse](../../moveitemresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
